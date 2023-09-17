---
title: Integrating SMC and Plackett-Luce Model for Accurate Analysis of Partial Order
summary: Undergraduate Project
tags:
  - Monte Carlo methods
  - Partial Order
date: '2023-06-21T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This dissertation centers on the comprehensive investigation of partial order ranking (POR) models and their practical implications in dynamic systems. Partial orders, in this context, refer to binary relations characterized by reflexivity, antisymmetry, and transitivity—a less restrictive form of total orders. They are often represented by transitively closed, directed, and acyclic graphs, wherein the order relations are represented by edges linking elements. In contrast, total orders entail a full ordering of elements, meaning that every pair of elements in a set holds a relational connection.

Traditionally, the Plackett-Luce model, introduced by Luce and Plackett, has been a cornerstone in modeling total orders. This model assigns weights to individual items and posits that the probability of an item's ranking in a particular position is directly proportional to the product of its inherent ability and the abilities of all items ranked higher. However, the Plackett-Luce model encounters challenges when confronted with partially ordered data, as it struggles to accurately reflect the variability in relative positions due to its reliance on fixed element weights. To surmount this limitation, this dissertation introduces a multi-dimensional model, wherein elements are each assigned multiple weights. This novel approach permits a more precise representation of partially ordered data, facilitating the adaptation of element weights in relation to one another.

In recent years, the interest in applying POR has surged across various domains, including information retrieval, natural language processing, and machine learning. Traditional partial order models primarily catered to static systems, where the order structure was presumed to be constant and known in advance. However, recent advances in the field, exemplified by the works of Watt and others, have expanded the scope of partial order models to dynamic systems, where the order structure evolves over time. Many real-world scenarios exhibit this dynamism, such as news article ranking based on relevance, product comparisons derived from customer feedback, and athlete evaluations based on performance.

To address this evolving paradigm, this dissertation introduces a POR approach that extends it into a stochastic process involving latent variables. This model takes the form of a Hidden Markov model, observed through random linear extensions extracted from suborders of the partial order at sequential sampling times. By modeling the underlying order structure as a dynamic process, the proposed method adeptly captures temporal changes in the order structure. Furthermore, employing Sequential Monte Carlo (SMC) with Markov Chain Monte Carlo (MCMC) resampling enhances algorithmic stability and performance, making it suitable for large-scale and high-dimensional data scenarios.

The overarching goal of this dissertation is to enhance the comprehension of POR in dynamic systems and showcase the efficacy of the proposed methodology through simulations and real-world case studies. This approach has the potential to significantly elevate the performance of POR in diverse applications where the underlying order structure undergoes temporal shifts or is inherently challenging to directly observe. Additionally, it contributes to the development of more versatile and potent ranking models for dynamic systems and advances the theoretical underpinnings of ranking methodologies.

In summary, this dissertation presents a compelling case for the amalgamation of the Metropolis-coupled Markov chain Monte Carlo method and the normalizing constant to achieve robust mixing of Markov chains, resulting in precise estimations of total order rankings. The integration of the Plackett-Luce model into partial order estimation, coupled with Sequential Monte Carlo, offers an accurate and computationally efficient approach for handling complex online systems. However, there exist areas ripe for further exploration and refinement, including comparative analyses with basic MCMC methods and optimization of the speed of reference ranking retrieval through the Plackett-Luce model. By addressing these challenges and building upon the promising outcomes of this study, the proposed approach stands poised to make substantial contributions to the field of ranking estimation across a wide array of applications. This research lays a solid foundation for future investigations into ranking estimation, particularly in the context of intricate systems where conventional methods may fall short. As these techniques continue to evolve, we can anticipate increasingly precise and efficient solutions to ranking problems spanning diverse domains.