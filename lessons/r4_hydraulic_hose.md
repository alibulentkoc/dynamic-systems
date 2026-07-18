# Robotics 4 — Hydraulic Hose Pressure Build-Up

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-4-hydraulic-hose.html" target="_blank" rel="noopener"><code>robotics-4-hydraulic-hose.html</code></a>.
:::

Start a pump and pressure does not appear instantly. Oil is slightly compressible and the hose walls flex, which
together act as a **hydraulic capacitance** $C_h$ that must be charged before pressure exists. Conservation of volume
gives $C_h\,dP/dt = Q - P/R$, or $\tau\,dP/dt + P = RQ$ with $\tau = R\,C_h$. Stiffer plumbing charges faster.

<iframe src="../robotics/robotics-4-hydraulic-hose.html" title="Robotics 4 — Hydraulic Hose Pressure Build-Up — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
This is the bridge from conservation laws to hydraulics, and the direct fluid analogue of **First-Order 2**. The
hydraulic circuit projects (**Projects 3–7**) assume exactly this pressure-build-up behaviour.
:::
