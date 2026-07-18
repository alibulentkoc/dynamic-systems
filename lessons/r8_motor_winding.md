# Robotics 8 — Robot Joint Motor Winding Heating

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-8-motor-winding-heating.html" target="_blank" rel="noopener"><code>robotics-8-motor-winding-heating.html</code></a>.
:::

A robot joint cycles all shift and its motor windings heat: copper losses pour in heat while the housing sheds it to
the room. The balance settles at $T_{ss} = T_a + K I^2$ — note the **square**. Double the current and the temperature
rise *quadruples*, which is why a modest overload cooks a motor. The system stays first order in $T$ even though the
input map is nonlinear in $I$.

<iframe src="../robotics/robotics-8-motor-winding-heating.html" title="Robotics 8 — Robot Joint Motor Winding Heating — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
**Robotics 2 (Drone Battery Temperature)** with a different heat source, and the same energy balance as
**First-Order 3**. The practical payoff is thermal protection: $\tau$ is minutes, so a brief overload is survivable
while the same current sustained is not — precisely what $I^2t$ models exploit.
:::
