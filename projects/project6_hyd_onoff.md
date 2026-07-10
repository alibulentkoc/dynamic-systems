# Circuit 4 — On/Off Control

:::{admonition} About this project's simulator
:class: note
The interactive below is a **self-contained HTML/JavaScript file** — no libraries, no build step, computed
live. Open it directly: <a href="../hyd-circuit-4-onoff.html" target="_blank" rel="noopener"><code>hyd-circuit-4-onoff.html</code></a>.
:::

A solenoid valve that's only fully-open or shut drives the cylinder at one speed, so it overshoots, reverses, and **hunts in a limit cycle** around the target. A deadband trades chatter for a wider dead zone.

<iframe src="../hyd-circuit-4-onoff.html" title="Circuit 4 — On/Off Control — interactive simulator"
        style="width:100%; height:1550px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
First-order motion from Lesson 1 meets real valve dynamics; contrast with the smooth proportional control of Circuit 5.
:::
