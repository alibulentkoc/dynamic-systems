# Circuit 1 — The Single Cylinder

:::{admonition} About this project's simulator
:class: note
The live circuit and the extend/retract asymmetry chart below are a **self-contained HTML/JavaScript file** —
no libraries, no build step. Speeds, forces, pressures, and flows are all computed live from v = Q/A and
F = P·A. Open it directly: <a href="../hyd-circuit-1-single.html" target="_blank" rel="noopener"><code>hyd-circuit-1-single.html</code></a>.
:::

The first of five hydraulic-circuit projects. Master the single cylinder — pump, relief valve, directional
valve, and a differential cylinder driving a load — and the two master equations behind all of fluid power:
**flow sets speed (v = Q/A)** and **pressure sets force (F = P·A)**. Because a rod occupies one side, the cylinder
extends slow-and-strong but retracts fast-and-weak.

<iframe src="../hyd-circuit-1-single.html" title="Circuit 1 — The Single Cylinder — interactive simulator"
        style="width:100%; height:1500px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
This is the building block for the circuits ahead: series cylinders (shared flow), parallel cylinders (shared
pressure), and on/off vs proportional valve control. The compressible-oil dynamics of these cylinders were the
subject of Project 2.
:::
