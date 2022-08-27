# Bezier-curves
A simple interactive Bézier curves renderer in Python. Part of the exam of "Didattica dell'informatica" at the University of Bologna, A.Y. 2021/22.

---

The Bezier curve is calculated with the de Castelau algorithm.

TODO: immagini, dipendenze

The application has two modes:
1. *modeling mode*: to place the control points and edit the control polygon
2. *animation mode*: to play the curve's rendering animation (while in this mode the curve cannot be edit)

The switching between the two modes will not affect the placed control points in any way.

- Single left click to place a new control point (only in *modeling mode*)
- Left click & drag on an existing control point to change its position (only in *modeling mode*)
- Single right click on an existing control point to remove it (only in *modeling mode*)
- "a" to switch between *modeling* and *animation* mode
- "c" to clear the canvas 
- "q" to quit the application
