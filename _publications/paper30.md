---
title: "Using automatically extracted information from mammography reports for decision-support."
date: 2019-06-18T12:33:46+10:00
weight: 13
---

**Selen Bozkurt**, Francisco Gimenez, Elizabeth S Burnside, Kemal H Gulkesen,
and Daniel L Rubin. 

# Objective
To evaluate a system we developed that connects natural language processing (NLP) for information extraction from narrative text mammography reports with a Bayesian network for decision-support about breast cancer diagnosis. The ultimate goal of this system is to provide decision support as part of the workflow of producing the radiology report.

# Materials and methods 
We built a system that uses an NLP information extraction system (which extract BI-RADS descriptors and clinical information from mammography reports) to provide the necessary inputs to a Bayesian network (BN) decision support system (DSS) that estimates lesion malignancy from BI-RADS descriptors. We used this integrated system to predict diagnosis of breast cancer from radiology text reports and evaluated it with a reference standard of 300 mammography reports. We collected two different outputs from the DSS: (1) the probability of malignancy and (2) the BI-RADS final assessment category. Since NLP may produce imperfect inputs to the DSS, we compared the difference between using perfect ("reference standard") structured inputs to the DSS ("RS-DSS") vs NLP-derived inputs ("NLP-DSS") on the output of the DSS using the concordance correlation coefficient. We measured the classification accuracy of the BI-RADS final assessment category when using NLP-DSS, compared with the ground truth category established by the radiologist.

# Results
The NLP-DSS and RS-DSS had closely matched probabilities, with a mean paired difference of 0.004±0.025. The concordance correlation of these paired measures was 0.95. The accuracy of the NLP-DSS to predict the correct BI-RADS final assessment category was 97.58%.

# Conclusion
The accuracy of the information extracted from mammography reports using the NLP system was sufficient to provide accurate DSS results. We believe our system could ultimately reduce the variation in practice in mammography related to assessment of malignant lesions and improve management decisions.