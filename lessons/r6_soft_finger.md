# Robotics 6 — Soft Robotic Finger Inflation

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-6-soft-finger-inflation.html" target="_blank" rel="noopener"><code>robotics-6-soft-finger-inflation.html</code></a>.
:::

Inflate a soft pneumatic finger and it curls toward a target bend, $d\theta/dt = k(\theta_f - \theta)$. Because the
response is first order it is **monotonic — no overshoot**: the finger eases into contact and never bends past its
target and crushes what it is holding. Compliance plus first-order dynamics is precisely why soft robots grasp
delicate things well.

<iframe src="../robotics/robotics-6-soft-finger-inflation.html" title="Robotics 6 — Soft Robotic Finger Inflation — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Mathematically identical to **Robotics 3**, but note what first order *buys* you here. Compare with the oscillation
and overshoot of **Lesson 6 (Second-Order Systems)** — a stiff, underdamped gripper would bounce against the object.
:::
