# Robotics 5 — Hydraulic Cylinder Chamber Filling

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-5-hydraulic-cylinder-filling.html" target="_blank" rel="noopener"><code>robotics-5-hydraulic-cylinder-filling.html</code></a>.
:::

A servo valve meters oil into a cylinder chamber and pressure builds toward its commanded value. Hold the piston
still and this is a clean first-order pressure system — the beating heart of an electrohydraulic actuator. The design
insight is where $\tau$ comes from: $C_h$ is chamber volume divided by the oil's **bulk modulus**, so entrained air
softens the oil, inflates $C_h$, and makes the actuator sluggish and spongy. That is why bleeding air matters.

<iframe src="../robotics/robotics-5-hydraulic-cylinder-filling.html" title="Robotics 5 — Hydraulic Cylinder Chamber Filling — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The core of **Project 2 (Hydraulic Cylinder)** and **Project 3 (Single Cylinder)**. Add piston motion and load and
this first-order pressure loop becomes the inner dynamics of the full servo-hydraulic system.
:::
