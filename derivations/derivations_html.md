# Derivations & Solutions (interactive)

:::{admonition} About this page
:class: note
This is the **self-contained HTML companion** to the SymPy notebook — the same three derivations, typeset for
offline reading, plus an interactive that plots all three routes at once so you can watch them coincide. No
libraries, no network. Open it directly: <a href="../derivations-solutions.html" target="_blank" rel="noopener"><code>derivations-solutions.html</code></a>.
:::

The lessons taught the ideas; this companion does the algebra. It solves the mass–spring–damper three
independent ways — classically by hand, via the Laplace transform, and through the state-space matrix
exponential — and shows all three land on the identical closed-form $x(t)$. Every closed form was derived and
cross-checked with SymPy (see the executable notebook alongside this page).

<iframe src="../derivations-solutions.html" title="Derivations & Solutions — interactive"
        style="width:100%; height:1650px; border:1px solid #D3DDE4; border-radius:12px;"
        loading="lazy"></iframe>

:::{admonition} Where this connects
:class: seealso
The characteristic roots (Lesson 3), the poles (Lessons 4–5), and the eigenvalues of $A$ (Lesson 7) are the same
numbers — this page shows why, by producing one $x(t)$ from all three.
:::
