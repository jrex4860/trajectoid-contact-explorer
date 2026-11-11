# Trajectoid Contact-Line Explorer

Interactive geometry viewer for a Sobolev-style trajectoid with programmable shape.

- A heavy core keeps the centre of mass at height `r`; the shell (radius `R`) is shaved by every ground plane met while rolling a programmed path `κ(s)`.
- The contact curve on the body has geodesic curvature equal to the path curvature; each piece sits at `ρ = min(R, r / cos δ)`.
- Contact-line controls: left/right half-length, hollow centre (two-rail).
- The plane view shows how much of each contact line survives when the contact curve wraps the body (Sobolev periodicity limit).

Geometry and no-slip kinematics only, not a physics simulation. Based on Sobolev et al., *Nature* 620 (2023), doi:10.1038/s41586-023-06306-y.

Open `index.html` in a browser, or visit the GitHub Pages site.

## Pages

- `index.html`: continuous Sobolev-style shell, contact-line explorer. Export the current body as binary STL (mm, 180×360 or 360×720 grid).
- `pieces.html`: the same body built from rigid prismatic pieces on a Goldberg tiling (piece strokes, interference, real contact, CM ripple).
