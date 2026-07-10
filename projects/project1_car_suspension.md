# Project 1 — Model & Simulate a Car Suspension

:::{admonition} About this project's simulator
:class: note
The ride simulator and comfort–handling trade study below are a **self-contained HTML/JavaScript file** —
no libraries, no build step. The ride is integrated live with RK4; the trade-off curves are computed from
the model's frequency response on load. Open it directly: <a href="../car-suspension.html" target="_blank" rel="noopener"><code>car-suspension.html</code></a>.
:::

This capstone puts the whole course to work on one machine. You model a quarter of a car as a two-mass,
4th-order system (Lessons 2 & 7), drive it over a bumpy road and feel the shock absorber work, then use a
frequency-response trade study to confront the real engineering truth: **comfort and road holding want
different damping, so there is no single best setting — only a defensible compromise.**

<iframe src="../car-suspension.html" title="Project 1 — Car Suspension — interactive simulator"
        style="width:100%; height:1650px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Body bounce and wheel hop are the system's two resonances (Lesson 6); the road speed sets the excitation
frequency; the shock sets the damping ratio (Lesson 2). The same state-space model (Lesson 7) is what a real
active-suspension controller runs on.
:::
