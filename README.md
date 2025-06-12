# Perlin noise and randomness Animation

## Interact
To experience the animation:

- **Move mouse slowly** across the canvas.  
  → Horizontal position (`mouseX`) affects the **wave center** and noise displacement.  
  → Vertical position (`mouseY`) controls the **amplitude** of the waves.

---

## My Approach to Animation
I focused on using **Perlin noise combined with mouse interaction and time** to animate both **parallel line groups** and **trapezoid shapes**. The objective was to achieve an organic, glowing, and fluid movement that evolves without harsh transitions.

---

## Animation Driver  
**Perlin Noise + Mouse Interaction + Time**

- `getAmplitudeVariance(x, y)` adds smooth, locally varying noise to vertical line positions.
- `mouseX` affects **wave center** through `xVertex0`.
- `mouseY` affects **amplitude** of deformation.
- `millis()` introduces subtle background motion even when the mouse is idle.

---


## Visual Inspirations

**Craig S. Kaplan's Line Work**  
Influenced my layered Perlin-deformed lines.  
 → [Reference Link](https://openprocessing.org/sketch/683686)
 ![Image](images/Kaplan.jpg)