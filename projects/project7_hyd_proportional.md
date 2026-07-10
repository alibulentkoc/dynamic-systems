# Circuit 5 — Proportional Control

:::{admonition} About this project's simulator
:class: note
The interactive below is a **self-contained HTML/JavaScript file** — no libraries, no build step, computed
live. Open it directly: <a href="../hyd-circuit-5-proportional.html" target="_blank" rel="noopener"><code>hyd-circuit-5-proportional.html</code></a>.
:::

A proportional valve meters flow to the error, u = Kp·(x*−x), making the closed loop **first-order with a smooth exponential approach** (τ = A/Kp) — no chatter. Push the gain too hard and the compressible-oil resonance of Project 2 bites.

<iframe src="../hyd-circuit-5-proportional.html" title="Circuit 5 — Proportional Control — interactive simulator"
        style="width:100%; height:1550px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Completes the control ladder above on/off (Circuit 4); the gain limit is the hydraulic resonance investigated in Project 2.
:::
