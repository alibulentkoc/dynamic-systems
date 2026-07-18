# Robotics 7 — Hydraulic Accumulator Charging

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-7-accumulator-charging.html" target="_blank" rel="noopener"><code>robotics-7-accumulator-charging.html</code></a>.
:::

Oil pumped into an accumulator compresses a nitrogen cushion, storing energy as pressure: $\tau\,dP/dt + P = P_s$.
Discharge is the same equation with the source removed — stored oil bleeds back out to supply bursts the pump alone
cannot. It is the energy buffer at the foundation of servo-hydraulic systems, and it closes the loop on the series.

<iframe src="../robotics/robotics-7-accumulator-charging.html" title="Robotics 7 — Hydraulic Accumulator Charging — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Discharging an accumulator **is the leaking tank** of **First-Order 1**, with gas compressibility playing the part
of the tank's cross-section. Charging is the driven version. Fourteen lessons, one equation — and the accumulator is
where the fluid-power projects (**Projects 4–7**) get their stiffness.
:::
