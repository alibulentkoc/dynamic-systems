# Lesson — Orders of a System (0th → 3rd)

:::{admonition} About this lesson's demos
:class: note
Every interactive demo below is a **self-contained HTML/JavaScript file** with *no external
libraries and no build step*. It computes each response curve live from the equations, draws
it on a plain `<canvas>`, and will run in any browser for years to come — offline, unaffected
by library updates. You can also open it directly: <a href="../orders-of-systems.html" target="_blank" rel="noopener"><code>orders-of-systems.html</code></a>.
:::

The order of a system — zeroth, first, second, third — tells you how it will respond to a push
*before you solve anything*. This lesson builds that intuition one order at a time, with live
oscilloscope-style traces you drive with sliders. Work through it below, or pop it out
full-screen with the link above.

<iframe src="../orders-of-systems.html" title="Orders of a System — interactive lesson"
        style="width:100%; height:1400px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The tank-cascade thread here (1 tank → 1st order, 2 → 2nd, 3 → 3rd) is pure fluid power, and
the third-order "actuator lag + plant" model is exactly the shape of a **hydraulic servo axis**.
We formalize the mass–spring–damper (2nd order) in Lesson 6 and the hydraulic cylinder in
Project 2.
:::
