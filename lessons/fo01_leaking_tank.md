# First-Order 1 — The Leaking Tank

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../foundations/leaking-tank-lesson.html" target="_blank" rel="noopener"><code>leaking-tank-lesson.html</code></a>.
A four-tab sandbox explorer covering the same system from other angles sits alongside it:
<a href="../foundations/leaking-tank-demo.html" target="_blank" rel="noopener"><code>leaking-tank-demo.html</code></a>.
:::

Water drains from a tank and the level falls — quickly at first, then ever more slowly, never quite reaching
empty. That curve is the plainest dynamic system there is, and it is the ancestor of every response in this course.
The lesson builds it from scratch: choose the **state** (height), write a conservation law (what accumulates equals
what flows in minus what flows out), and out drops $dh/dt = -h/\tau$. Along the way the **time constant** $\tau$
stops being a formula and becomes a thing you can see: the storage divided by the leak.

<iframe src="../foundations/leaking-tank-lesson.html" title="First-Order 1 — The Leaking Tank — interactive lesson"
        style="width:100%; height:1900px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
This is the decay half of the first-order family. **Lesson 1** met the chase $dy/dt = (1/\tau)(u - y)$; here you
derive it. Every lesson that follows is this same equation with different labels — and $\tau = $ storage ÷ leak is
the pattern you will reuse in **First-Order 2–6** and throughout the robotics series.
:::
