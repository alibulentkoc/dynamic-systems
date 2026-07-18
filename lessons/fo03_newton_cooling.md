# First-Order 3 — Newton's Cooling

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../foundations/newton-cooling-lesson.html" target="_blank" rel="noopener"><code>newton-cooling-lesson.html</code></a>.
:::

A hot mug cools toward room temperature — not toward zero. Writing an energy balance gives
$dT/dt = -k(T - T_a)$, and the response settles at ambient rather than at the origin. The lesson introduces the move
that tames every equation like it: **shift coordinates** to $\theta = T - T_a$, the gap to equilibrium, and the
problem collapses back into the leaking tank you already solved. Shift, solve, shift back.

<iframe src="../foundations/newton-cooling-lesson.html" title="First-Order 3 — Newton's Cooling — interactive lesson"
        style="width:100%; height:1900px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
That coordinate shift is the workhorse of the whole series — **First-Order 5 and 6** and every robotics lesson use it
to reduce a driven system to pure decay. It is also the same change of variable that turns an equilibrium into the
origin in **Lesson 7 (State Space)**.
:::
