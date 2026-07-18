# Second-Order 1 — Mass, Spring & Damper

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../second-order/second-order-1-mass-spring-damper.html" target="_blank" rel="noopener"><code>second-order-1-mass-spring-damper.html</code></a>.
:::

Add a spring to a mass and the system gains something no first-order lesson could show you: it can **overshoot**.
The reason is structural — energy now has *two* places to live, the spring's stretch and the mass's motion, so it can
slosh between them and carry the mass straight past its target. Two parameters take over from $\tau$:
$\omega_n = \sqrt{k/m}$ sets how fast it rings, and $\zeta = c/(2\sqrt{km})$ decides whether it rings at all.

<iframe src="../second-order/second-order-1-mass-spring-damper.html" title="Second-Order 1 — Mass, Spring & Damper — interactive lesson"
        style="width:100%; height:2050px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
This is where **First-Order 4 (Drag & Terminal Velocity)** was heading: keep the spring term Newton's law and you get
this. It is also the plant behind **Project 1 (Car Suspension)**, and the same system solved three ways in the
**Derivations** companion.
:::
