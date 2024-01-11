---
title: "Causal analysis of social bias towards faces in CLIP"
collection: publications
permalink:
doi: 
date: 2024-01-11
venue: 
paperurl: 
citation: 
preprint: true
---

<u>Abstract:</u>
We propose the first experimental study to measure bias in social perception in the latent space of multi-modal models. Previous studies compute *correlations* between a model's social judgments and protected attributes, such as race, age, and gender, using *observational* wild-collected human-annotated datasets, such as FairFace. In order to establish {\em causal} links between protected attributes and algorithmic bias, we use a synthetic dataset of face images instead, CausalFace, where both legally protected attributes and potential confound attributes, such as facial expression, lighting, and pose, are controlled independently and systematically, and thus allow an {\em experimental} exploration, which lets us reach causal conclusions.
Our analysis is based on measuring cosine similarities between images and word prompts, including valence words drawn from the two leading social psychology theories elucidating human stereotypes: The ABC Model and the Stereotype Content Model.
We find that non-protected attributes are powerful confounds and profoundly influence social perception, injecting variability in measurements whose size is comparable to that induced by legally protected attributes. Clear intersecting biases of race, gender, and age only emerge when these unprotected attributes are controlled for, which is only possible using CausalFace. Observational datasets do not permit a similar level of insight due to spurious correlations introduced by uncontrolled attributes and a lack of specific annotations.

Text-to-image Models  | Artificial Intelligence | Causal Fairness Analysis | Bias | Stereotyping



