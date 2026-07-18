# First-Order 5 — Grain Drying

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../foundations/grain-drying-lesson.html" target="_blank" rel="noopener"><code>grain-drying-lesson.html</code></a>.
:::

Corn comes off the field near 21% moisture and must reach 15% for safe storage. The thin-layer (Lewis) model,
$dM/dt = -k(M - M_e)$, is Newton's cooling wearing an agricultural hat. The twist is design: the **equilibrium
moisture** $M_e$ is set by the drying air, not the grain — and it acts as a *floor*. If $M_e$ sits above your target,
no amount of drying time will ever get you there. You change the air, not the clock.

<iframe src="../foundations/grain-drying-lesson.html" title="First-Order 5 — Grain Drying — interactive lesson"
        style="width:100%; height:1900px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
"The equilibrium decides what is reachable" is the same lesson as the ceiling in **First-Order 6** and the
steady-state pressure $RQ$ in the hydraulic lessons. It is also a first taste of design thinking: $\tau$ sets *how
fast*, but the equilibrium sets *whether at all*.
:::
