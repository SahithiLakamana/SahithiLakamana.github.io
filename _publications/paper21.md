---
title: "Automatic inference of bi-rads final assessment categories from narrative mammography report findings."
date: 2019-06-18T12:33:46+10:00
weight: 22
---

Imon Banerjee, **Selen Bozkurt**, Emel Alkim, Hersh Sagreiya, Allison W Kurian,
and Daniel L Rubin. 

We propose an efficient natural language processing approach for inferring the BI-RADS final assessment categories by analyzing only the mammogram findings reported by the mammographer in narrative form. The proposed hybrid method integrates semantic term embedding with distributional semantics, producing a context-aware vector representation of unstructured mammography reports. A large corpus of unannotated mammography reports (300,000) was used to learn the context of the key-terms using a distributional semantics approach, and the trained model was applied to generate context-aware vector representations of the reports annotated with BI-RADS category (22,091). The vectorized reports were utilized to train a supervised classifier to derive the BI-RADS assessment class. Even though the majority of the proposed embedding pipeline is unsupervised, the classifier was able to recognize substantial semantic information for deriving the BI-RADS categorization not only on a holdout internal testset and also on an external validation set (1900 reports). Our proposed method outperforms a recently published domain-specific rule-based system and could be relevant for evaluating concordance between radiologists. With minimal requirement for task specific customization, the proposed method can be easily transferable to a different domain to support large scale text mining or derivation of patient phenotype.