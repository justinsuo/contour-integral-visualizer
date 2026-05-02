# Contour integral visualizer

Interactive guide for evaluating

$$\int_C \frac{z+2}{z}\,dz, \qquad C: z(\theta) = 2e^{i\theta},\ \theta \in [\pi, 2\pi].$$

Answer: **$4 + 2\pi i$**.

## What's in the page

- **Synchronized triple-panel animation.** Watch $z(\theta)$ trace the lower semicircle, $f(z)$ trace its image curve, and the running integral build head-to-tail to $4 + 2\pi i$ — all driven by one playhead.
- **Domain coloring + vector field.** Phase portrait of $f(z) = (z+2)/z$ (hue = $\arg f$, rings = $|f|$), with toggleable contour, $f$-vectors, $dz$ tangents, and $f \cdot dz$ integrand arrows.
- **Path-comparison tool.** Lower semicircle, upper semicircle, full closed loop, zigzag over the pole — see how the imaginary part tracks the winding number around $z=0$ (residue theorem cross-check).
- **Riemann sum convergence.** Slide $N$ and watch midpoint-rule sums converge.
- **3D landscape.** $|f(z)|$ as a height map with the contour drawn on the surface and a moving point. Three.js + OrbitControls.

Single self-contained HTML file (`index.html`). MathJax and Three.js loaded from CDN; no build step.

## Run

Open `index.html` in any modern browser, or visit the GitHub Pages site.
