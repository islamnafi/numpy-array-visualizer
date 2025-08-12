Visualize 1D, 2D, and 3D NumPy-style arrays in an interactive 3D scene made using **Three.js**. Paste your array, click **Visualize**, and explore it with orbit controls, color mapping, labels, and tooltips.

---

## Features
- Supports Python/NumPy-style arrays (`[ ]`, `[[ ]]`, `np.array(...)`) up to 3D.
- Auto-cleans wrappers, trailing commas, and dtype info.
- Displays dimensions and validates rectangular shape.
- Interactive 3D with orbit/pan/zoom and hover tooltips.
- Cool-to-warm color mapping (blue → red).
- Reset view, toggle wireframe, go back to input.

---

## Controls
- **Orbit:** Left-drag  
- **Pan:** Right-drag / Ctrl+drag  
- **Zoom:** Scroll/pinch  
- **Toolbar:** Reset View, Toggle Wireframe, Back  

## Input Examples
```text
[1, 2, 3, 4]
[[1,2,3],[4,5,6]]
np.array([[[1,2],[3,4]], [[5,6],[7,8]]])
