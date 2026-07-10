# Lesson 5 — Transfer Functions

:::{admonition} About this lesson's demos
:class: note
The pole–zero playground and block-diagram cascade below are a **self-contained HTML/JavaScript
file** — no libraries, no build step — computing every response live. Open it directly:
<a href="../transfer-functions.html" target="_blank" rel="noopener"><code>transfer-functions.html</code></a>.
:::

Lesson 4 gave us X(s) = F(s)/(ms²+cs+k). Dividing output by input leaves the transfer function
G(s) = Y(s)/U(s) — a system's complete fingerprint. This lesson adds the two ideas that make it the
engineer's working tool: **zeros** (not just poles) and **block-diagram composition** (series
connection multiplies). Switch on a zero and watch overshoot appear — or push it into the right
half-plane to make the output move the wrong way first.

<iframe src="../transfer-functions.html" title="Transfer Functions — interactive lesson"
        style="width:100%; height:1550px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
Reading G(jω) versus frequency is the subject of Lesson 6 (resonance). Designing feedback loops with
G/(1+GH) builds directly on the composition rules introduced here.
:::
