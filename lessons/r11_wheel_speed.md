# Robotics 11 — Wheel Speed Controller

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-11-wheel-speed.html" target="_blank" rel="noopener"><code>robotics-11-wheel-speed.html</code></a>.
:::

Command a voltage and the wheel ramps rather than jumps: $\tau\,d\omega/dt + \omega = KV$. Steady speed is linear in
voltage — your throttle map — while $\tau = J/(b + K_tK_e/R_a)$ is rotor inertia over *effective* damping, with
back-EMF adding damping on top of friction. Watch which term gets dropped: this is first order because armature
**inductance** is negligible ($\tau_{elec} \approx 1$ ms vs $\tau_{mech} \approx 1$ s), **not** because inertia is —
inertia is what creates $\tau$ in the first place.

<iframe src="../robotics/robotics-11-wheel-speed.html" title="Robotics 11 — Wheel Speed Controller — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Closes the robotics series where control begins: this transfer from $V$ to $\omega$ is the plant every wheel-speed
loop wraps around, and it reappears as a first-order pole in **Lesson 5 (Transfer Functions)** and as a
one-state model in **Lesson 7 (State Space)**. Keep $L_a$ and it becomes second order — **Lesson 6**.
:::
