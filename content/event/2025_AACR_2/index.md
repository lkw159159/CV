---
title: "Poster Presentation in 2025 AACR (#7263)"

event: AACR Annual Meeting 2025
event_url: https://www.aacr.org/meeting/aacr-annual-meeting-2025/

location: McCormick Place Convention Center
address:
  city: Chicago
  region: Illinois
  country: United States

class: "expanded-content"

summary: 'Development and validation of a machine learning framework for immune phenotype classification and immunotherapy response prediction in lung cancer'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-04-30T09:00:00Z'
date_end: '2025-04-30T12:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-03-18T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false
image: 
  src: "/CV/event/2025_AACR/featured.jpg"
  caption: 'Image credit: [**AACR**](https://oncodaily.com/blog/214078)'
---

<br><br>

**Background**<br>
Tumor immune microenvironment composition significantly influences immunotherapy outcomes in lung cancer, with immune-inflamed tumors demonstrating higher response rates compared to immune-non-inflamed tumors. This study aimed to develop a machine learning framework to classify immune phenotypes in lung cancer using TCGA data and validate its utility in predicting immunotherapy response with real-world patient samples. Existing approaches, such as the Lunit SCOPE technique, have been employed for immune phenotype characterization but face limitations in handling tumor heterogeneity and adapting to diverse datasets, underscoring the need for more robust tools. 


<br><br>

**Methods**<br>
A baseline machine learning model was constructed using six tree-based classifiers: Random Forest, Extremely Randomized Trees, AdaBoost, Gradient Boosting, XGBoost, and LightGBM. Feature importance scoring identified critical immune-related gene expression profiles, including markers from interferon signaling, T-cell activation, and cytokine regulation pathways. Model optimization incorporated 15 classifiers, leveraging advanced hyperparameter tuning and ensemble learning strategies to improve accuracy, Matthew's correlation coefficient (MCC), and area under the ROC curve (AUROC). Classification training and validation were performed on 447 TCGA lung cancer samples, divided into 80% training and 20% validation subsets, stratified into immune-inflamed and immune-non-inflamed phenotypes based on bulk RNA-seq gene expression datasets.  
The final model demonstrated robust adaptability to tumor heterogeneity and was independently tested on 87 patient samples labeled through the Lunit SCOPE framework, stratified into immunotherapy responders and non-responders. Correlation analysis assessed the relationship between immune phenotypes and therapeutic outcomes. The optimized model exceeded the performance of Lunit SCOPE, achieving an AUROC >0.90 in classifying immune-inflamed versus immune-non inflamed samples in the TCGA dataset. Testing on real-world patient samples further confirmed its ability to accurately predict immunotherapy response, supporting the hypothesis that immune-inflamed tumors derive greater benefit from treatment. This machine learning framework demonstrates superior accuracy and adaptability compared to existing techniques, offering significant potential to improve patient stratification, reduce ineffective treatments, and guide precision immunotherapy in lung cancer. 


<br><br>

**Conclusion**<br>
Future directions include integrating multi-omics datasets to further refine predictive capabilities and assess its generalizability across other cancer types.
