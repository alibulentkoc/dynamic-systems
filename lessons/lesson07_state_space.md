# Lesson 7 — State-Space Modeling

:::{admonition} About this lesson's demos
:class: note
The A-matrix anatomy view and the state-flow field below are a **self-contained HTML/JavaScript
file** — no libraries, no build step — computing eigenvalues, flow fields, and trajectories live.
Open it directly: <a href="../state-space.html" target="_blank" rel="noopener"><code>state-space.html</code></a>.
:::

Lesson 3 defined a system's *state* as the minimum you must know now (position and velocity for a
spring). State-space turns that into the language of modern control: ẋ = Ax + Bu, y = Cx + Du. The
unifying punchline of the whole course lives here — **the eigenvalues of A are exactly the poles**, the
same λ's from every earlier lesson, now stored inside a matrix.

<iframe src="../state-space.html" title="State-Space Modeling — interactive lesson"
        style="width:100%; height:1550px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Placing the eigenvalues of A − BK is state-feedback pole placement — the design goal glimpsed in every
s-plane lesson. State-space is also the natural home for the multi-domain models of Lesson 8.
:::
