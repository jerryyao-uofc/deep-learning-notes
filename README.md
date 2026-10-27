# Deep Learning Notes

Ground-up study notes on neural networks and deep learning, with extra detail, intuition, and simple worked examples. The aim is a clearer path for readers who want the ideas from first principles without jumping straight into dense lecture form.

These notes borrow heavily from the original [CSC2516 course lecture notes](https://r-three.github.io/deep-learning-lecture-notes/) (Neural Networks and Deep Learning).

**Website:** [https://jerryyao-uofc.github.io/deep-learning-notes/](https://jerryyao-uofc.github.io/deep-learning-notes/)

## Lecture 07 — Attention and Self-Attention

| File | Description |
|------|-------------|
| [`lecture-07-attention.pdf`](./lecture-07-attention.pdf) | Compiled notes (start here) |
| [`lecture-07-attention.tex`](./lecture-07-attention.tex) | LaTeX source |
| [`index.html`](./index.html) | GitHub Pages landing page |

**Topics covered:** attention as associative memory, soft 1-NN, sequence-to-sequence with attention, self-attention (worked toy example), path length, position encodings, multi-headed attention, and attention pooling in a full network.

### Rebuild the PDF

```bash
pdflatex lecture-07-attention.tex
pdflatex lecture-07-attention.tex
```

Requires a standard TeX Live install (`amsmath`, `booktabs`, `tikz`, `hyperref`).
