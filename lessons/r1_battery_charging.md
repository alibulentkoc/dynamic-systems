# Robotics 1 — Mobile Robot Battery Charging

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-1-battery-charging.html" target="_blank" rel="noopener"><code>robotics-1-battery-charging.html</code></a>.
:::

A warehouse robot docks at 20% and charges toward full. As the pack fills, the charging current tapers, so the
state of charge climbs fast and then crawls — $dSOC/dt = k(100 - SOC)$. The familiar entry point to the series, and
the reason fast-charge policies stop around 80% and top off slowly: the tail is the slow part.

<iframe src="../robotics/robotics-1-battery-charging.html" title="Robotics 1 — Mobile Robot Battery Charging — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
This is **First-Order 2 (RC Circuit)** with a battery on the front. Same equation, same $\tau$, same 63% rule.
:::
