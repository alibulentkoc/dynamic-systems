# Project 2 — Hydraulic Cylinder & Bulk Modulus

:::{admonition} About this project's simulator
:class: note
The natural-frequency explorer and the closed-loop servo below are a **self-contained HTML/JavaScript file** —
no libraries, no build step. Natural frequency, stroke dependence, and the servo step response are all computed
live. Open it directly: <a href="../hydraulic-cylinder.html" target="_blank" rel="noopener"><code>hydraulic-cylinder.html</code></a>.
:::

The fluid-power finale, and the bridge to physical AI. You characterize a hydraulic cylinder as a spring
(k = βA²/V), watch its natural frequency change over the stroke and collapse with air entrainment, then close a
position-control loop and discover the hard engineering limit: **the hydraulic resonance caps how hard you can
control the actuator, and the maximum stable gain scales with bulk modulus β.** A controller tuned for clean oil
goes unstable once air lowers β.

<iframe src="../hydraulic-cylinder.html" title="Project 2 — Hydraulic Cylinder & Bulk Modulus — interactive simulator"
        style="width:100%; height:1650px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The hydraulic spring is the second-order system of Lessons 2, 6, and 8; instability is closed-loop poles crossing
into the right half-plane (Lessons 4, 5); the model is state-space (Lesson 7). Every idea in the course converges
on this one real actuator.
:::
