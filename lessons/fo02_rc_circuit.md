# First-Order 2 — The RC Circuit

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../foundations/rc-circuit-lesson.html" target="_blank" rel="noopener"><code>rc-circuit-lesson.html</code></a>.
:::

Swap water for charge and a tank for a capacitor, and nothing about the mathematics changes. Kirchhoff's voltage
law plays the role the conservation law played before, and $\tau = RC$ falls out as storage ÷ leak once again. What is
new here is the **driven** response: with a source attached, the capacitor does not decay to zero but climbs toward
$V_s$ and stops. That is the first appearance of a **non-zero steady state**, the idea that makes the rest of the
series possible.

<iframe src="../foundations/rc-circuit-lesson.html" title="First-Order 2 — The RC Circuit — interactive lesson"
        style="width:100%; height:1900px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The tank↔circuit analogy sketched here is the same bridge formalised in **Lesson 8 (Mechanical, Electrical,
Hydraulic)**. The driven form $\tau\,dv/dt + v = V_s$ is the template for every "charging" system in the robotics
series — the gripper, the hose, the cylinder, and the accumulator are all this circuit in disguise.
:::
