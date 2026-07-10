# Lesson 4 — Why the Laplace Transform Was Invented

:::{admonition} About this lesson's demos
:class: note
The draggable s-plane and the system-poles picture below are a **self-contained HTML/JavaScript
file** — no libraries, no build step — computing every waveform and pole location live. Open it
directly: <a href="../laplace-transform.html" target="_blank" rel="noopener"><code>laplace-transform.html</code></a>.
:::

Lesson 3 ended on the roots λ of the characteristic equation. This lesson explains the tool that
gives those roots a home: the Laplace transform turns calculus into algebra (d/dt → ×s), an ODE into
a fraction, and the roots into **poles** living in the **s-plane**. Drag a pole to see the signal it
represents, then watch the mass–spring–damper's poles migrate as you change damping.

<iframe src="../laplace-transform.html" title="Why the Laplace Transform Was Invented — interactive lesson"
        style="width:100%; height:1500px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
X(s) = F(s)/(ms²+cs+k) is the **transfer function** we formalize in Lesson 5. The left-half-plane
stability rule here is the backbone of every design lesson that follows.
:::
