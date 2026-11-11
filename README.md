# TactileLens fine-tuning report

A single static web page (`index.html`) by Aaron Seth Nagtalon (Aaeyron), part of the TactileLens capstone.

It covers:

- **The data:** im2latex-100k filtered to expressions using general-algebra notation (the source formulas come from physics papers): the filter rules, counts at each step, examples, the leak guard between splits, and the limits.
- **Two fine-tuning runs** of the app's offline formula model (PP-FormulaNet_plus-S), each scored strict and spacing-normalized, with their training charts.
- **What changed during fine-tuning:** weight change per part of the model, kinds of mistakes before and after, the model's confidence, and before/after examples.

This repository holds only the page. No datasets, checkpoints or code are included. The page needs no build step: Vercel serves `index.html` as a static site.
