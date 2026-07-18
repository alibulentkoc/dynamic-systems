# Foundations of Dynamic Systems — Interactive First-Order Lessons

Self-contained, offline **interactive lessons on first-order dynamical systems**, built as drop-in supporting material for a course. Every lesson teaches the same idea — one stored quantity relaxing toward an equilibrium — through a different physical system, so students see that a leaking tank, an RC circuit, a cooling coffee cup, and a hydraulic cylinder are all the *same equation* in different clothing:

```
τ dx/dt + x = x_target        →        x(t) = x∞ + Δ·e^(−t/τ)
```

Each lesson follows one arc: **choose the state → build the equation from a balance law → solve it → watch it respond**, ending with takeaways, quick-check questions, and worked exercises.

## View it

- **Live (GitHub Pages):** enable Pages for this repo (Settings → Pages → Build and deployment → *GitHub Actions*). The included workflow publishes the site on every push to `main`. The landing page is `index.html`.
- **Locally:** just open `index.html` in any browser — or open any individual lesson file directly. No server, no build, no internet required.

## What's inside

### Foundations — one law across physical domains
Work these in order; each introduces one new idea.

| # | Lesson | Domain | New idea |
|---|--------|--------|----------|
| 01 | Leaking Tank | Fluid | pure decay; where τ comes from |
| 02 | RC Circuit | Electrical | driven response to a non-zero steady state |
| 03 | Newton's Cooling | Thermal | decay to non-zero equilibrium; coordinate shift |
| 04 | Drag & Terminal Velocity | Mechanical | equilibrium from a force balance |
| 05 | Grain Drying | Agricultural | equilibrium as a floor; unreachable targets |
| 06 | Study Hours & Grades | Learning | approach to a ceiling; independent variable ≠ time |

Plus `leaking-tank-demo.html`, the original four-tab sandbox explorer.

### Fluid-Powered Physical AI — the robotics series
Ordered from familiar toward the hydraulic and fluid-power systems central to physical AI. Same first-order structure throughout.

| # | Lesson | Domain |
|---|--------|--------|
| R1 | Mobile Robot Battery Charging | Electrical |
| R2 | Drone Battery Temperature | Thermal |
| R3 | Pneumatic Gripper Pressure | Pneumatic |
| R4 | Hydraulic Hose Pressure Build-Up | Hydraulic |
| R5 | Hydraulic Cylinder Chamber Filling | Electrohydraulic |
| R6 | Soft Robotic Finger Inflation | Physical AI |
| R7 | Hydraulic Accumulator Charging | Servo-Hydraulic |

## Structure

```
.
├── index.html                     landing page (links every lesson)
├── lessons/
│   ├── foundations/               the six domain lessons + tabbed demo
│   └── robotics/                  the seven-lesson robotics series
├── .github/workflows/deploy.yml   GitHub Pages deploy on push to main
├── .nojekyll                      serve files as-is (no Jekyll processing)
├── LICENSE                        MIT
└── README.md
```

## Design notes

- **Self-contained.** Each lesson is a single HTML file with all CSS and JavaScript inline. Zero external URLs, CDNs, fonts, or trackers — verified. Everything works offline and will keep working long-term.
- **Vanilla stack.** Plain JavaScript and `<canvas>`; system fonts only. No frameworks, no build step.
- **Consistent house style.** A lab-instrument / oscilloscope aesthetic shared across all lessons.
- **Embeddable.** Because there are no dependencies, any lesson drops cleanly into an LMS, a course website, or a Jupyter Book via an `<iframe>`.

## Reuse in another course

These are designed to be portable. To include a lesson in your own course site, either link to the hosted page or copy the single HTML file and embed it:

```html
<iframe src="lessons/robotics/robotics-3-pneumatic-gripper.html"
        style="width:100%;height:900px;border:0"></iframe>
```

## License

Released under the [MIT License](LICENSE) — free to use, adapt, and redistribute, including in your own courses, with attribution.
