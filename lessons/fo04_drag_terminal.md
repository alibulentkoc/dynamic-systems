# First-Order 4 — Drag & Terminal Velocity

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../foundations/drag-terminal-lesson.html" target="_blank" rel="noopener"><code>drag-terminal-lesson.html</code></a>.
:::

Drop an object through air and it does not accelerate forever: drag grows with speed until it cancels the driving
force, and the velocity levels off. Newton's second law with linear drag, $m\,dv/dt = F - bv$, is first order in
$v$ — and the terminal velocity $v_t = F/b$ is not something you integrate for, it is something you read off a
**force balance** by setting the derivative to zero. Meanwhile $\tau = m/b$: inertia over damping.

<iframe src="../foundations/drag-terminal-lesson.html" title="First-Order 4 — Drag & Terminal Velocity — interactive lesson"
        style="width:100%; height:1900px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Setting $\dot{x} = 0$ to find equilibrium *before* solving is the habit this lesson drills, and it carries into every
steady-state calculation in the book. Keep the second derivative and this same mechanical system becomes the
mass–spring–damper of **Lesson 6** — first order is what you get when inertia is negligible.
:::
