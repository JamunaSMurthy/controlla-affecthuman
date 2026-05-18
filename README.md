<div align="center">

# Controlla Project Page

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=2600&pause=900&color=363636&center=true&vCenter=true&width=900&lines=Graph-constrained+latent+geometry;Identity-preserving+multimodal+affective+control;Controllability+as+structured+semantic+movement)](https://git.io/typing-svg)

Static research webpage for **Controlla: Learning Controllability via Graph-Constrained Latent Geometry**.

[![Project Page](https://img.shields.io/badge/Page-index.html-363636?style=for-the-badge)](index.html)
[![Dataset](https://img.shields.io/badge/Dataset-AffectHuman--43K-0f766e?style=for-the-badge)](https://huggingface.co/datasets/iamjamuna/AffectHuman-43K)
[![Code](https://img.shields.io/badge/Code-Controlla-1f2937?style=for-the-badge&logo=github)](https://github.com/JamunaSMurthy/Controlla)

![Controlla teaser](data/teaser.png)

</div>

## About Controlla

**Controlla** treats controllability as a property of the latent space itself, rather than only an instruction applied at inference time. The framework learns factorized identity and attribute representations, then aligns controllable attributes with graph priors so semantic edits move along structured paths while reference identity stays stable.

This project page presents Controlla through the lens of **identity-preserving multimodal affective control**. In that setting, a reference image specifies who should remain consistent, while affective control signals from text, audio, and emotion labels specify how the expression should change.

## What This Page Highlights

| Section | What it shows |
|---|---|
| Core idea | Control as graph-constrained latent geometry |
| Novelty | Representation-level controllability, graph-constrained optimal transport, and leakage-aware evaluation |
| Baselines | Comparisons against editing, personalization, and control-based generation methods |
| AffectHuman-43K | A multimodal benchmark with identity-disjoint splits and affective control signals |
| Geometry analysis | Ablations showing why meaningful graph structure matters |
| Extensibility | Pose and lighting examples beyond affective control |

## Visual Story

The page uses the figures in [`data/`](data/) to walk through the research narrative:

- `teaser.png` introduces Controlla's graph-structured control setup.
- `figure1.png` through `figure6.png` show baseline comparisons and qualitative behavior.
- `graphinterpolation.png`, `figure13.png`, and `graph2.png` explain graph construction and traversal.
- `Figure14.png` and `Figure15.png` summarize AffectHuman-43K examples.
- `figure11.jpg` and `figure12.jpg` show plug-in pose and lighting control.
- `sensitivity.png` reports how graph regularization changes performance.

## Repository Layout

```text
.
├── index.html      # Static project page
├── README.md       # Repository overview
└── data/           # Teasers, figures, graph visuals, and result images
```

## Local Preview

Open [`index.html`](index.html) in a browser to view the page locally. The site is intentionally static, so it does not require a build step, package install, or development server.

## Citation

```bibtex
@article{murthy2026controlla,
  author  = {Murthy, Jamuna S. and Monsefi, Amin Karimi and Ramnath, Rajiv},
  title   = {Controlla: Learning Controllability via Graph-Constrained Latent Geometry},
  year    = {2026}
}
```

<div align="center">

Built for a research page that makes the central Controlla idea visible quickly: structured semantic movement, stable identity, and graph-aware multimodal control.

</div>
