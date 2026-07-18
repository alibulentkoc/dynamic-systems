# Robotics 10 — Vision Confidence Build-Up

:::{admonition} About this lesson's demo
:class: note
This lesson is a **self-contained HTML/JavaScript file** — no libraries, no build step, works offline. Open it
directly: <a href="../robotics/robotics-10-vision-confidence.html" target="_blank" rel="noopener"><code>robotics-10-vision-confidence.html</code></a>.
:::

A robot observes an object repeatedly and grows more certain. Each look adds evidence in proportion to the doubt
that remains, $dC/dt = k(1 - C)$, so confidence climbs toward certainty and never quite arrives. That asymptote is
why perception stacks act on a **threshold** (say 95%) rather than waiting for 1.0. This models the *shape* real
Bayesian or Kalman updating produces — it is not itself a Bayesian derivation.

<iframe src="../robotics/robotics-10-vision-confidence.html" title="Robotics 10 — Vision Confidence Build-Up — interactive lesson"
        style="width:100%; height:1750px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The same ceiling logic as **First-Order 6 (Study Hours & Grades)** — only the independent variable changed. Every
halving of the remaining doubt costs a fixed $0.69\tau$, which is exactly the diminishing-returns argument, applied
to belief instead of knowledge.
:::
