# Lesson 6 — Second-Order Systems: Frequency, Damping, Resonance

:::{admonition} About this lesson's demos
:class: note
The driven-resonance demo and the Bode magnitude plot below are a **self-contained HTML/JavaScript
file** — no libraries, no build step — computing |G(jω)| live. Open it directly:
<a href="../second-order-resonance.html" target="_blank" rel="noopener"><code>second-order-resonance.html</code></a>.
:::

Drive a linear system with a steady sinusoid and it answers with a sinusoid at the same frequency,
scaled by |G(jω)|. Near ωₙ that scaling can explode — **resonance** — and the only thing capping it is
damping. Sweep a driven mass through its natural frequency and watch the amplitude balloon, then read the
same story off the Bode magnitude curve.

<iframe src="../second-order-resonance.html" title="Second-Order Systems: Frequency, Damping, Resonance — interactive lesson"
        style="width:100%; height:1550px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The resonant peak is set by pole proximity to the jω axis (Lesson 4); ζ = 0.707 is the flattest-response
design target used throughout controls. Hydraulic line resonance reappears in Project 2.
:::
