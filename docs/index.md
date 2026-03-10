# Comparative Analysis of Neural Population Codes
This website serves as a central hub of Google CoLab jupyter notebook tutorials on different metrics to compare neural representations.

While notebooks should be self-contained or contain references to required background material, they're designed to complement the COSYNE 2026 Tutorial: Comparative Analysis of Neural Population Codes. Links to the lecture recordings will be posted here once they are available!

::::::{grid} 2
:gutter: 1

:::::{grid-item}

::::{grid} 1
:gutter: 2

:::{grid-item-card} Part 1: Neural Tuning, Geometry, and Procrustes shape distance
:img-bottom: _static/procrustes.png
:link: https://colab.research.google.com/drive/1jy5d0gqR9-DKFpQcQiCjI0_F12DhODy0?usp=sharing
:class-card: sd-border-2

Build conceptual and mathematical intuition of Procrustes distance and it's extension to linear invariance.
:::   
   
:::{grid-item-card} Part 3: Exploiting Metric Space Properties in Neural Populations
:img-bottom: _static/allen_procrustes.png
:link: https://colab.research.google.com/drive/1fAhi1_JlbxaBJXnTReNvthW2KcJ9j2qb?usp=sharing
:class-card: sd-border-2

Demonstrate how Procrustes distance can be used on real data: computing neural similarity between brain regions and animals using data available through [AllenSDK](https://allensdk.readthedocs.io/en/latest/visual_coding_neuropixels.html).
:::

::::

:::::

:::::{grid-item}

::::{grid} 1
:gutter: 2

:::{grid-item-card} Part 2: Relationship of Procrustes to RSA and CKA
:img-bottom: _static/RSA_CKA.png
:link: https://colab.research.google.com/drive/1WIAN5jDCTGU8KaRga2jwu4LcCo6AmVw9?usp=sharing
:class-card: sd-border-2

Build mathematical intuition of RSA and CKA, understand conditions under which they are equivalent, and show how these metrics are related to Procrustes distance.
:::

:::{grid-item-card} Part 4: Measuring Distance between Mismatched Representations
:img-bottom: _static/soft_matching.png
:link: https://colab.research.google.com/drive/1hksgmS67mqLr3V4_H0faNcv75FuqHnMS?usp=sharing
:class-card: sd-border-2

Soft-matching and partial soft-matching: Extend Procrustes distance to situations when 1-to-1 matches between neurons is not possible or feasible.
:::
::::
:::::
::::::

```{toctree}
:maxdepth: 2
:caption: Contents:
:hidden:

Lab Website <https://neurostatslab.org>
Lab GitHub <https://github.com/neurostatslab>
```