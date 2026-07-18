# Second-Order 2 — The RLC Circuit

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../second-order/second-order-2-rlc-circuit.html" target="_blank" rel="noopener"><code>second-order-2-rlc-circuit.html</code></a>.
:::

Put an inductor in series with your RC circuit and the electrical twin of the mass-spring-damper appears. The
inductor is the mass: it stores energy in current and resists change, so it overshoots and pumps the capacitor past
the supply. Watch the resistor switch roles — in **First-Order 2** more $R$ meant *slower charging*; here more $R$
means *more damping*, $\zeta = (R/2)\sqrt{C/L}$. Same component, opposite job.

<iframe src="../second-order/second-order-2-rlc-circuit.html" title="Second-Order 2 — The RLC Circuit — interactive lesson"
        style="width:100%; height:2050px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The full electrical–mechanical analogy of **Lesson 8**: inductance ↔ mass, compliance ↔ 1/stiffness, resistance ↔
damping. Drop $R$ toward zero and the ringing never stops — that is an oscillator, and it is why snubber design is a
compromise.
:::
