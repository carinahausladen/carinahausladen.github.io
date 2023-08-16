---
title: "Investigating bias in text-to-image models: A theory-driven approach to study the organizational structure of stereotypes in CLIP"
collection: ongoing-projects
permalink: ongoing-projects/clip
date: 2023-08-15
---

<u>Collaborators:</u>

Colin Camerer (Caltech)

<u>Abstract:</u>

Bias in artificial intelligence (AI) has emerged as a critical research topic. However, a comprehensive theoretical model is often absent from many existing studies. To devise efficacious mitigation strategies, a nuanced comprehension of biases inherent in large generative AI systems is paramount. The stereotype content model (SCM), developed in social psychology, offers insights into how stereotypes are organized in human cognition. This study investigates whether a similar structure exists in large language-to-image models, focusing on CLIP. 

Our investigation employs a recently published dataset that enables a causal investigation of stereotypes. The dataset was ingeniously constructed by setting an initial seed in a Generative Adversarial Network (GAN). This seed was subsequently manipulated systematically via latent space traversals to represent various combinations of sensitive attributes, specifically focusing on race and gender. This manipulation ensured that any difference between a pseudo-identity (seed) and its altered version is solely due to the changed sensitive attribute, while all potential confounding variables, such as lighting, pose, and expression, are held constant. This methodology permits us to draw causal conclusions about the social warmth and competence perception of various demographic groups.

Overall, our research focuses on two different datasets: A causal dataset and the non-causal FairFace dataset. We found statistically significant differences among all race and gender categories in both datasets, investigated via t-tests. Our most salient findings indicate that Asians are perceived as warmer and more competent than other races, and females are viewed as warmer and more competent than males. These findings contradict certain social psychology perspectives, providing novel insights into AI bias.

A unique advantage of this paper is that the application of the SCM enables us to explore intersectionality. In particular, we identified three clusters of warmth and competence perceptions over all intersection groups within the causal dataset. This clustering suggests that females are consistently perceived more favorably than their male counterparts.

Our robustness checks, performed via pairwise comparisons of faces, reaffirm our findings. This investigation illuminates implicit biases in AI systems, thereby informing debiasing strategies targeting these root causes. Future research could investigate the effect of repositioning the embedding space towards the middle, moving away from the extremes of warmth and competence. Another promising direction is to explore the benefits of hyperbolic over Euclidean spaces for embedding hierarchical representations in shared text and image representations.