# Sessrumnir — Parametric Wardrobe Planner & Character Workbench

Sessrumnir is a 3D parametric wardrobe planner, fitted-garment generator, and virtual character dress-up workbench. Designed for gamedevs, digital tailors, and character designers, Sessrumnir combines real-time mesh fitting, parametric body scaling, and garment morphing in a high-performance interactive 3D viewport.

---

## 👗 Key Features & Module Breakdown

### 📐 Parametric Body & Character Fitting (`avatar`)
- **Current**: 3D character mesh viewer, real-time height/weight/chest/waist slider adjustments, and bone skeleton scaling.
- **Planned / Roadmap**: Full parametric body morph targets, custom avatar mesh import (.gltf / .fbx), skin tone customization, and pose library.

### 👔 Garment & Wardrobe Generator (`wardrobe`)
- **Current**: Parametric fitted-wardrobe placement, fabric color/texture switching, and automatic mesh clipping prevention.
- **Planned / Roadmap**: Real-time cloth physics simulation, seam pattern generator, multi-layer clothing stack, and material shader editor (leather, silk, denim, metallic).

### 🎮 3D Engine & Workbench (`engine`)
- **Current**: Interactive WebGL 2 / Three.js 3D viewport with OrbitControls, PBR lighting, and shadow rendering.
- **Planned / Roadmap**: Native Godot 4 engine migration (`godot/`), offline standalone desktop executable, high-res 3D screenshot exporter, and GLTF model export with fitted clothes.

---

## 🏗️ Architecture & Technology Stack

- **Current Web Prototype**: TypeScript, Vite, Three.js, WebGL 2.
- **Desktop Roadmap**: Godot 4.x (GodotSteam C++ engine extension), GLTF 2.0 importer/exporter.
- **Licensing**: AGPL-3.0.

---

## 🛠️ Building & Running

```bash
# Install dependencies
npm install

# Start local development server
npm run dev

# Production build
npm run build
```

---

## 📜 License

Sessrumnir is released under the **GNU Affero General Public License v3.0** (AGPL-3.0). See [`LICENSE`](LICENSE) for details.
