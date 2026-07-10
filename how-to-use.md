# How to Use This Course

You can read this course three ways, from lowest to highest effort — and the interactivity
climbs with each.

## 1. Just read it (zero setup)

Every lesson works as a normal web page. All the plots you see were produced by the code
shown right above them, so nothing is hand-waved. This is the fastest way through and is
perfectly fine for a first pass.

## 2. Run the code live in your browser

Look for the **rocket icon** (🚀) at the top of a lesson and choose **Live Code** (Thebe)
or **Binder**. After a short spin-up, the code cells become editable and runnable right on
the page. Change a number, press run, watch the plot update. This is where the **sliders
and widgets** come alive.

## 3. Run everything locally (recommended if you're serious)

```bash
# 1. Get the course files, then from the course folder:
pip install -r requirements.txt

# 2. Option A — read as a website you build yourself:
jupyter-book build .
#    then open _build/html/index.html

# 3. Option B — open the lessons as real notebooks and tinker:
pip install jupytext
jupyter lab
#    open any lessons/*.md file — Jupyter Lab treats it as a notebook
```

## About the interactive widgets

Some demos use **`ipywidgets`** sliders. These only move when the code is actually running
(browser "Live Code", Binder, or a local Jupyter). In the static website they appear as a
snapshot at their default settings, and we always show a **static plot** alongside so the
lesson makes sense either way. Wherever you see a slider, the caption tells you what to try.

## A note on the math

You need comfortable-not-expert calculus: what a derivative and an integral *mean*. You do
**not** need to remember integration tricks or Laplace tables — we build those up slowly
and explain every symbol the first time it appears.

:::{admonition} The one habit that makes this stick
:class: tip
When you meet a new equation, pause and ask: *"If I made this one symbol bigger, what would
physically happen to the machine?"* If you can answer that, you understand the equation. If
you can't yet, that's exactly what the surrounding text is there to fix.
:::
