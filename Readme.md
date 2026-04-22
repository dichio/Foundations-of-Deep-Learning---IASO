# Foundations of Deep Learning

**Vito Dichio** — Fellow in AI, ENS-PSL  
✉ vito.dichio@psl.eu

*Master's Degree in AI & Society (PSL-PSAI) — Spring 2026*

---

## Overview

This repository contains the lecture slides (PDF) for the **Foundations of Deep Learning** module, part of the Master's course in [Artificial Intelligence and Society at PSL-PSAI](https://psl.eu/en/education/master-s-degree-artificial-intelligence-and-society), Paris, France. The course provides a rigorous, incremental introduction to deep learning, from statistical learning fundamentals to modern architectures.

---

## Course Structure

The module is divided into two parts:

### Part I — Deep Learning Fundamentals
| # | Lecture | Key Topics |
|---|---------|------------|
| 1 | Introduction | Supervised learning, loss minimisation, bias-variance trade-off, linear & non-linear models |
| 2 | Multi-Layer Perceptron | Hidden units, activation functions, output layers, canonical pairs |
| 3 | Losses | Regression & classification losses, canonical link–loss pairs |
| 4 | Gradient Descent | Batch/SGD/mini-batch, Hessian, convergence, optimisers (Momentum, RMSProp, Adam) |
| 5 | Backpropagation | Forward/backward pass, computation graph, reverse-mode autodiff |
| 6 | Training Tricks | Regularisation, vanishing/exploding gradients, training workflow |

### Part II — Architectures & Applications
| # | Lecture | Key Topics |
|---|---------|------------|
| 7 | CNNs / Part I | Inductive bias, computer vision, convolution operator |
| 8 | CNNs / Part II | Multi-channel convolutions, pooling, AlexNet, ResNet, transfer learning |
| 9 | Transformers / Part I | object detection, segmentation (from previous lecture), Natural language, word representations, autoregressive models, RNNs |
| 10 | Transformers / Part II | Attention mechanism, Transformer architecture |
| 11 | Group Oral Presentations | Student presentations on landmark deep learning papers |
| 12 | Natural vs Machine Intelligence | Brief history of AI & new hopes; Neuro-AI: continual learning, energy efficiency, physical world grounding

---

## Bibliography

| Reference | Chapters most relevant to this module |
|-----------|--------------------------------------|
| C. Bishop & H. Bishop, *Deep Learning: Foundations and Concepts*, Springer (2023) | Ch. 1, 4–10, 12 |
| I. Goodfellow, Y. Bengio & A. Courville, *Deep Learning*, MIT Press (2016) | Ch. 5, 10 |
| F. Fleuret, *The Little Book of Deep Learning*, (2024) | Ch. 1, 3–5 |
| T. Hastie, R. Tibshirani & J. Friedman, *The Elements of Statistical Learning*, Springer (2009) | Ch. 2–4 |
| D. Andler, *Intelligence Artificielle, Intelligence Naturelle: la double énigme*, Gallimard (2023) | Ch. 1–6 |

---

## Repository Contents

```
📁 slides/
├── L1_Introduction.pdf
├── L2_MultiLayer_Perceptron.pdf
├── L3_Losses.pdf
├── L4_Gradient_Descent.pdf
├── L5_Backpropagation.pdf
├── L6_Training_Tricks.pdf
├── L7_CNNs_Part_I.pdf
├── L8_CNNs_Part_II.pdf
├── L9_Transformers_Part_I.pdf
├── L10_Transformers_Part_II.pdf  
└── L12_Natural_vs_Machine.pdf 
```

---

## Licence

Slides are shared for educational purposes. Please cite appropriately if you reuse any material.

## Acknowledgements

These slides owe much to many. Special thanks to N. Schreuder and E. De Angelis for their contributions to the course content. I am also grateful to the library of the [INHA](https://www.inha.fr) (Institute National d'Histoire de l'Art, 2 Rue Vivienne, Paris) for providing a wonderful—no seriously, wonderful—place to work during the many hours spent preparing these materials. Above all, thanks to the students: their curiosity, engagement, and questions were the best motivation of all.