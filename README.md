# Multimodal Deep Learning for Recommendation

This is the official GitHub repository for the lecture "_Multimodal Deep Learning for Recommendation_", hosted at the [2024 ACM RecSys Summer School](https://acmrecsys.github.io/rsss2024/) in Bari (Italy).

<div>
  <img src="https://recsys.acm.org/wp-content/uploads/2023/11/RecSysBanner_1000_180.png" alt="SisInfLab" width="600">
  <img src="https://recsys.acm.org/wp-content/uploads/2020/07/Recsys-OG.png" alt="recsys" width="200">
</div>

## Abstract

With the advent of deep learning and, more recently, large models, recommendation systems have greatly refined their capability of profiling users’ preferences and interests that, in most cases, are complex to disentangle. This is especially true for those recommendation algorithms that hugely rely on external side information, such as **multimedia recommender systems**. In specific domains like fashion, music, and movie recommendation, the multi-faceted features characterizing products and services may influence each customer on online selling platforms differently, paving the way to novel multimedia recommendation models that leverage the lesson-learned from **multimodal deep learning**. 

On such premises, this lecture will delve into the topic of multimodal deep learning for recommendation. Specifically, the lecture will provide an introductory, still general, overview of the current literature. First, it will start by outlining the main rationales behind multimedia recommendation, and why a multimodal formalization is currently needed. Then, it will focus on presenting the multimodal deep learning pipeline for multimedia recommendation. This section will also involve an **hands-on** session, where we will learn how to build such a pipeline from scratch, from the multimodal dataset processing to the recommendation training and evaluation. Finally, it will highlight the main research challenges, and how we tackled most of them in recent works.

## Main information

* **Instructor:** [Daniele Malitesta](https://danielemalitesta.github.io/) (reach out to me: [email](mailto:d.malitesta@gmail.com))
* **Date:** Wednesday, October 9, 2024
* **Duration:** 15:30 - 16:50 CET (80 min)
* **Main topics:** Recommender systems, multimodal deep learning

## Schedule

* **Part 0: I wish I had known it in advance! [5 min.]**
  * 0.1: (Some) useful resources to get started
  * 0.2: Field-specific conferences/journals
* **Part 1: One multimodal schema to rule them all [50 min.]**
  * 1.1: Personalized (multimedia) recommendation
  * 1.2: Why do we need a schema anyway?
  * 1.3: **[Theory + Practice]** A unified multimodal schema
* **Part 2: Open challenges and how we solved them [15 min.]**
  * 2.1: Missing modalities in the input data
  * 2.2: Multimodality on user-item interactions
  * 2.3: Pre-trained feature extractors
  * 2.4: Fine-grained multimodal features
  * 2.5: An extensive and fair evaluation
* **Part 3: Q & A time [+∞\*]**

\* Just kidding :-) 

## Useful resources

### Lecture resources
* **Google drive folder:** _Coming soon_
* **Slides:** _Coming soon_
* **Google Colab:** _Coming soon_

### Other useful resources

**Main papers**
| Title                                                                                                              | Paper                                                                | Code                                                       |
|--------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|------------------------------------------------------------|
| Ducho meets Elliot: Large-scale Benchmarks for Multimodal Recommendation                                           | [arXiv](https://arxiv.org/abs/2409.15857)                            | [GitHub](https://github.com/sisinflab/Ducho-meets-Elliot) ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/Ducho-meets-Elliot) |
| Formalizing Multimedia Recommendation through Multimodal Deep Learning                                             | [TORS](https://dl.acm.org/doi/10.1145/3662738)                       | [GitHub](https://github.com/sisinflab/Formal-MultiMod-Rec) ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/Formal-MultiMod-Rec) |
| Ducho 2.0: Towards a More Up-to-Date Unified Framework for the Extraction of Multimodal Features in Recommendation | [The Web Conference](https://dl.acm.org/doi/10.1145/3589335.3651440) | [GitHub](https://github.com/sisinflab/Ducho)  ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/Ducho)             |
| Ducho: A Unified Framework for the Extraction of Multimodal Features in Recommendation                             | [ACM Multimedia](https://dl.acm.org/doi/10.1145/3581783.3613458)     | [GitHub](https://github.com/sisinflab/Ducho)    ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/Ducho)           |

**Side papers**
| Title                                                                                                     | Paper                                                                                                                                                                       | Code                                                                      |
|-----------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| Do We Really Need to Drop Items with Missing Modalities in Multimodal Recommendation?                     | [CIKM](https://arxiv.org/abs/2408.11767)                                                                                                                                    | [GitHub](https://github.com/sisinflab/Graph-Missing-Modalities)      ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/Graph-Missing-Modalities)     |
| Reshaping Graph Recommendation with Edge Graph Collaborative Filtering and Customer Reviews               | [DL4SR@CIKM](https://ceur-ws.org/Vol-3317/Paper7.pdf)                                                                                                                       | [GitHub](https://github.com/sisinflab/Edge-Graph-Collaborative-Filtering) ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/Edge-Graph-Collaborative-Filtering) |
| Leveraging Content-Style Item Representation for Visual Recommendation                                    | [ECIR](https://www.researchgate.net/publication/359723533_Leveraging_Content-Style_Item_Representation_for_Visual_Recommendation)                                          | [GitHub](https://github.com/sisinflab/Content-Style-VRSs)      ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/Content-Style-VRSs)                        |
| A Study on the Relative Importance of Convolutional Neural Networks in Visually-Aware Recommender Systems | [CVFAD@CVPR](https://openaccess.thecvf.com/content/CVPR2021W/CVFAD/papers/Deldjoo_A_Study_on_the_Relative_Importance_of_Convolutional_Neural_Networks_CVPRW_2021_paper.pdf) | [GitHub](https://github.com/sisinflab/CNNs-in-VRSs)       ![GitHub Repo stars](https://img.shields.io/github/stars/sisinflab/CNNs-in-VRSs)                |

## Leave a comment
If you have attended the lecture, please leave a comment in this **anonymous** form. It will take a few minutes, but it can be very important to me to improve the quality of the lecture! Thank you for your contribution!

## Credits

None of the content of this lecture would have been possible without the great contribution of former and current collaborators/supervisors. I wish to thank them all!

**Supervisors (former and current):** Tommaso Di Noia (Poliba), Fragkiskos Malliaros (CentraleSupélec)

**Collaborators (alphabetical order):** Walter Anelli (Poliba), Matteo Attimonelli (Poliba), Giandomenico Cornacchia (IBM Europe) Danilo Danese (Poliba), Angela Di Fazio (Poliba), Antonio Ferrara (Poliba), Giuseppe Gassi (Poliba), Alberto Mancino (Poliba), Felice Merra (AWS GenAI), Claudio Pomo (Poliba), Emanuele Rossi (VantAI).
