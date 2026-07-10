# Foundations of Dynamic Systems

An intuition-first, **interactive** mini-course that takes you from everyday physics to Laplace transforms,
state space, and fluid-power control — building toward robotics, mechatronics, and physical AI.

Every lesson and project is a **self-contained HTML page** (vanilla JavaScript + `<canvas>`, **no libraries,
no CDNs, no network**) with live, tunable simulations, wrapped into a browsable [Jupyter Book](https://jupyterbook.org).
The full symbolic derivations are provided as an executable SymPy notebook.

## Quick start

```bash
pip install -r requirements.txt
jupyter-book build .
# then open _build/html/index.html
```

Or just open any file in `demos/` directly in a browser — each one runs standalone, offline, forever.

## What's inside

**Lessons**
1. Dynamic Systems Everywhere · Orders of a System (0th–3rd)
2. Modeling with Newton's Laws
3. Differential Equations, Read Physically
4. Why the Laplace Transform Was Invented
5. Transfer Functions
6. Second-Order Systems: Frequency, Damping, Resonance
7. State-Space Modeling
8. One Language: Mechanical, Electrical, Hydraulic

**Projects**
- Project 1 — Model & Simulate a Car Suspension (comfort-vs-handling trade-off)
- Project 2 — Hydraulic Cylinder & Bulk Modulus (resonance & servo stability)

**Hydraulic Circuits** (fluid-power series)
1. The Single Cylinder — `v = Q/A`, `F = P·A`, differential areas
2. Cylinders in Series — shared flow, pressures add
3. Cylinders in Parallel — shared pressure, flow divides (lightest load first)
4. On/Off Control — bang-bang hunting and the deadband trade-off
5. Proportional Control — smooth metered approach, gain vs the resonance limit

**Derivations & Solutions**
- An executable **SymPy** notebook + an interactive HTML page deriving `x(t)` three ways
  (classical ODE, Laplace transform, state-space matrix exponential) and proving they agree.

## Design principles

- **Intuition first:** physical phenomenon → intuition → engineering example → math → interpretation.
- **Zero dependencies in the demos:** system fonts only, hand-rendered math, no external URLs — built to run
  in any browser for years.
- **Everything is verified:** each simulation's physics is checked numerically (Node/SymPy) before shipping,
  and every interactive is smoke-tested headless.

## Repository layout

```
demos/         self-contained interactive HTML lessons (the primary artifacts)
lessons/       Jupyter Book pages (MyST) that embed each demo
projects/      project pages (car suspension, hydraulic cylinder, circuits)
derivations/   SymPy notebook + HTML companion (full worked solutions)
assets/ code/ solutions/   supporting material
_config.yml _toc.yml        Jupyter Book configuration
```

## Publishing

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the book and deploys it to
**GitHub Pages**. Enable Pages once under *Settings → Pages → Source: GitHub Actions*.

## License

Released under the [MIT License](LICENSE).
