# Robotics 9 — Camera Autofocus

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-9-camera-autofocus.html" target="_blank" rel="noopener"><code>robotics-9-camera-autofocus.html</code></a>.
:::

The lens drives toward sharpness at a speed proportional to how far out of focus it is, so the error collapses as
$de/dt = -ke$. This is the **first pure decay** in the robotics series — and secretly your first feedback controller:
commanding speed proportional to error *is* proportional control, with $\tau = 1/k$ as the closed-loop time constant.
"In focus" is a threshold, not zero, since the error decays forever.

<iframe src="../robotics/robotics-9-camera-autofocus.html" title="Robotics 9 — Camera Autofocus — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Structurally **First-Order 1 (The Leaking Tank)**, with focus error in place of water height. It is also the door
into control: raise the gain $k$ too far and the real lens overshoots and hunts, which is where the first-order model
breaks and **Lesson 6 (Second-Order Systems)** takes over.
:::
