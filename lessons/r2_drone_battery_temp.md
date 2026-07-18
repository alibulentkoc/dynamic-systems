# Robotics 2 — Drone Battery Temperature

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-2-drone-battery-temperature.html" target="_blank" rel="noopener"><code>robotics-2-drone-battery-temperature.html</code></a>.
:::

A drone battery heats as it delivers current while convection carries heat away in proportion to how far above
ambient it sits. The two effects balance at $T_{ss} = T_a + PR$ — the air temperature plus a rise set by power and
thermal resistance — reached on a timescale $\tau = RC$. Thermal protection is exactly this calculation: knowing how
fast the pack heats lets the controller throttle before it hits a limit.

<iframe src="../robotics/robotics-2-drone-battery-temperature.html" title="Robotics 2 — Drone Battery Temperature — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
**First-Order 3 (Newton's Cooling)** run in reverse — heating instead of cooling, same energy balance. Note that
doubling flight power doubles the temperature *rise* but leaves $\tau$ untouched.
:::
