# Lesson 1 — Dynamic Systems Everywhere

:::{admonition} About this lesson's demo
:class: note
The comparison below is a **self-contained HTML/JavaScript file** — no libraries, no build step — integrating
the "chase" live. Open it directly:
<a href="../dynamic-systems-everywhere.html" target="_blank" rel="noopener"><code>dynamic-systems-everywhere.html</code></a>.
:::

Push a heavy cart and it eases up to speed, then coasts when you stop; step on a scale and it reads at once. Those
two everyday objects sit at opposite ends of one spectrum — a **dynamic** system responds over time and *remembers*,
a **static** one just mirrors the input now. This first lesson builds that intuition and the single most important
idea in the course: **state**, the compact summary of a system's stored history. The interactive feeds the same push
into a static and a dynamic system so you can watch the difference — and meet the first-order **time constant τ**.

<iframe src="../dynamic-systems-everywhere.html" title="Dynamic Systems Everywhere — interactive lesson"
        style="width:100%; height:1650px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The "chase" dy/dt = (1/τ)(u − y) is the first-order building block behind everything later; **Lesson 2** derives
equations like it from Newton's laws, and **state** becomes the backbone of **state-space** modeling in **Lesson 7**.
:::
