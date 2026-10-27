# Deep Learning Notes

Ground-up study notes on neural networks and deep learning, with extra detail, intuition, and simple worked examples. The aim is a clearer path for readers who want the ideas from first principles.

Formation of these notes borrows heavily from the [original course website (CSC2516)](https://r-three.github.io/deep-learning-lecture-notes/).

**Website:** [https://jerryyao-uofc.github.io/deep-learning-notes/](https://jerryyao-uofc.github.io/deep-learning-notes/)

## Notes

| # | Title | Status |
|---|-------|--------|
| 07 | [Attention & Self-Attention](./notes/07-attention/) | Published |
| 08 | Transformers | Upcoming |
| 06 | Sequences & RNNs | Upcoming |
| 05 | CNNs & Residuals | Upcoming |
| 04 | Gradient Methods | Upcoming |
| 03 | Regularization & Autodiff | Upcoming |
| 02 | MLPs & Backprop | Upcoming |
| 01 | Linear & Logistic Regression | Upcoming |

Each published note is maintained as LaTeX and shown on the site as:

1. a **rendered HTML reading view** (generated from the `.tex`), and
2. the **embedded `.tex` source** on the same page (not a PDF viewer).

## Lecture 07 — Attention & Self-Attention

- Reading page: [`notes/07-attention/`](./notes/07-attention/)
- LaTeX source: [`notes/07-attention/lecture-07-attention.tex`](./notes/07-attention/lecture-07-attention.tex)
- Root copy (for local compile): [`lecture-07-attention.tex`](./lecture-07-attention.tex)

**Topics:** attention as associative memory, soft one-nearest-neighbor, sequence-to-sequence with attention, self-attention toy walk-through, formal self-attention & path length, position encodings, multi-headed attention, attention pooling in a full network.

### Rebuild the note page from LaTeX

```bash
pandoc lecture-07-attention.tex -f latex -t html5 --mathjax --toc --toc-depth=2 -o notes/07-attention/body.html
# then regenerate notes/07-attention/index.html with the site wrapper (or re-run the project build script)
pdflatex lecture-07-attention.tex   # optional PDF
```

## GitHub Pages

This repository is set up for GitHub Pages from the `main` branch root (`index.html`). After pushing, the site is available at the URL above.
