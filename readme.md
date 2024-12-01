# Lighting and Objects with Three.js

This project demonstrates the use of various types of lights in a Three.js scene, along with interactive GUI controls for adjusting light properties. It also includes several 3D objects to showcase the lighting effects.

---

## Features

### Lights
The project includes the following light types:
1. **Ambient Light**  
   Provides a base level of illumination affecting all objects equally.
2. **Directional Light**  
   Mimics sunlight; casts parallel rays in a specific direction.
3. **Hemisphere Light**  
   Emits light from a sky color to a ground color.
4. **Point Light**  
   Emits light in all directions from a specific point.
5. **Spot Light**  
   Emits a cone-shaped beam of light.
6. **Rect Area Light**  
   Provides a rectangular area of light. Works only with `MeshStandardMaterial`.

### Helpers
Visual helpers for better understanding light positions and directions:
- `HemisphereLightHelper`
- `DirectionalLightHelper`
- `PointLightHelper`
- `SpotLightHelper`
- `RectAreaLightHelper`

### GUI Controls
Interactive GUI controls are provided via **lil-gui** to adjust the properties of lights dynamically:
- Change light color
- Adjust light intensity

### Objects
The scene includes a set of 3D objects using `MeshStandardMaterial`:
- **Sphere**
- **Cube**
- **Torus**
- **Plane**

### Camera and Controls
- **Perspective Camera** provides a realistic 3D perspective.
- **OrbitControls** allows interactive rotation, zoom, and pan of the scene.

---

## Setup
Run this followed commands:

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server
npm run dev

# Build for production in the dist/ directory
npm run build
```
![image](https://github.com/user-attachments/assets/ce07efdd-acc4-4db0-8c82-abe9032e78ed)
