# Deep Learning Notes

Study notes from CSC2516 (Neural Networks and Deep Learning), written to be readable on their own.

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
