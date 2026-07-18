# Second-Order 3 — Hydraulic Cylinder Driving a Load

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../second-order/second-order-3-hydraulic-cylinder-load.html" target="_blank" rel="noopener"><code>second-order-3-hydraulic-cylinder-load.html</code></a>.
:::

Oil looks incompressible until you hang a heavy load on it. The trapped column is a stiff spring,
$k_h = 4\beta A^2/V_t$, and with the load as the mass you get the **hydraulic natural frequency**
$\omega_h = \sqrt{4\beta A^2/(V_t M)}$ — about 62 Hz at the default numbers. This is the single most important figure
in servo-hydraulic design: your control bandwidth is capped near $\omega_h/3$ no matter how good the valve is.

<iframe src="../second-order/second-order-3-hydraulic-cylinder-load.html" title="Second-Order 3 — Hydraulic Cylinder Driving a Load — interactive lesson"
        style="width:100%; height:2050px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The payoff of the whole arc. **Robotics 5** treated trapped oil as a capacitance that merely charged; add the load's
inertia and it becomes a resonance. Shorten the column, bleed the air (restore $\beta$), lighten the load — nothing
else moves $\omega_h$. This governs **Projects 2–7** and every fluid-powered axis in the course.
:::
