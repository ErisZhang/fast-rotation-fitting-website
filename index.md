title: Complementary Dynamics
author: Jiayi Eris Zhang, Seungbae Bang, David I.W. Levin, Alec Jacobson
html header: <meta property="og:image" content="http://www.dgp.toronto.edu/projects/neuralSubdivision/neuralSubdivision_teaser.jpg" />
<meta property="og:description" content="We present a novel approach to enrich arbitrary rig animations with elastodynamic secondary effects. Unlike previous methods which pit rig displacements and physical forces as adversaries against each other, we advocate that
physics should complement artists’ intentions. We propose optimizing for
elastodynamic displacements in the subspace orthogonal to displacements
that can be created by the rig. This ensures that the additional dynamic
motions do not undo the rig animation. The complementary space is highdimensional, algebraically constructed without manual oversight, and capable of rich high-frequency dynamics. Unlike prior tracking methods, we do
not require extra painted weights, segmentation into fixed and free regions
or tracking clusters. Our method is agnostic to the physical model and plugs
into non-linear FEM simulations, geometric as-rigid-as-possible energies, or
mass-spring models. Our method does not require a particular type of rig
and adds secondary effects to skeletal animations, cage-based deformations,
wire deformers, motion capture data, and rigid-body simulations." />
<meta name="twitter:card" content="summary"></meta>
<meta name="og:title" content="Complementary Dynamics"></meta>
css: style.css

# Complementary Dynamics _SIGGRAPH ASIA 2020_

<div class=authors>
Jiayi Eris Zhang, Seungbae Bang, David I.W. Levin, Alec Jacobson <br><br>
University of Toronto
</div>

![](fish_teaser.jpg)

## Abstract
We present a novel approach to enrich arbitrary rig animations with elastodynamic secondary effects. Unlike previous methods which pit rig displacements and physical forces as adversaries against each other, we advocate that
physics should complement artists’ intentions. We propose optimizing for
elastodynamic displacements in the subspace orthogonal to displacements
that can be created by the rig. This ensures that the additional dynamic
motions do not undo the rig animation. The complementary space is highdimensional, algebraically constructed without manual oversight, and capable of rich high-frequency dynamics. Unlike prior tracking methods, we do
not require extra painted weights, segmentation into fixed and free regions
or tracking clusters. Our method is agnostic to the physical model and plugs
into non-linear FEM simulations, geometric as-rigid-as-possible energies, or
mass-spring models. Our method does not require a particular type of rig
and adds secondary effects to skeletal animations, cage-based deformations,
wire deformers, motion capture data, and rigid-body simulations.
## Downloads

 - [Paper (47 MB)](complementary-dynamics.pdf)

## BibTeX

```
@article{Liu:Subdivision:2020,
  title = {Neural Subdivision},
  author = {Hsueh-Ti Derek Liu and Vladimir G. Kim and Siddhartha Chaudhuri and Noam Aigerman 
  and Alec Jacobson},
  year = {2020},
  issue_date = {July 2020}, 
  publisher = {Association for Computing Machinery}, 
  volume = {39}, 
  number = {4}, 
  issn = {0730-0301},
  journal = {ACM Trans. Graph.}, 
}
```

## Acknowledgements 
This work is funded in part by NSERC Discovery (RGPIN–2017–05524, RGPIN-2017–05235, RGPAS–2017–507938, RGPAS–2017–507909), Connaught Fund (503114), CFI-JELF Fund, New Frontiers of Research Fund (NFRFE–201), the Ontario Early Research Award program, the Canada Research Chairs Program, the Fields Centre for Quantitative Analysis and Modelling and gifts by Adobe Systems, Autodesk and MESH Inc. We especially thank Paul Kry for hosting the 2018 Bellairs workshop on Computer Animation and the attendees for inspiring initial project ideas. We thank Otman Benchekroun, Rinat Abdrashitov and Josh Holinaty for proofreading; John Hancock for the IT support; anonymous reviewers for their helpful comments and suggestions.

<!-- `multimarkdown --process-html -o index.{html,md}` -->
