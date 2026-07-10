# Lesson 2 — Modeling with Newton's Laws

:::{admonition} About this lesson's demo
:class: note
The mass–spring–damper below is a **self-contained HTML/JavaScript file** — no libraries, no
build step — that integrates m·ẍ + c·ẋ + k·x = F live and animates the physics with a real-time
free-body diagram. Open it directly: <a href="../newton-modeling.html" target="_blank" rel="noopener"><code>newton-modeling.html</code></a>.
:::

Lesson 1 showed *that* second-order systems overshoot and ring; the Orders lesson showed the
family of responses. This lesson answers **where the equation comes from** — built from F = ma,
one physical part at a time — and connects the mass, spring, and damper you can hold in your hand
directly to ωₙ and ζ.

<iframe src="../newton-modeling.html" title="Modeling with Newton's Laws — interactive lesson"
        style="width:100%; height:1500px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The same force-bookkeeping produces the equations for RLC circuits and hydraulic actuators — the
subject of Lesson 8. The quarter-car version is built in Project 1, and the hydraulic-cylinder
"spring" in Project 2.
:::
