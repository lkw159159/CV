---
title: "Poster Presentation in 2025 AACR (#2427)"

event: AACR Annual Meeting 2025
event_url: https://www.aacr.org/meeting/aacr-annual-meeting-2025/

location: McCormick Place Convention Center
address:
  city: Chicago
  region: Illinois
  country: United States

class: "expanded-content"

summary: 'Optimization of preprocessing strategies for developing AI-based disease diagnosis model using whole transcriptomic data'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-04-28T09:00:00Z'
date_end: '2025-04-28T12:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-03-18T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false
image: 
  src: "featured.jpg"
  caption: 'Image credit: [**AACR**](https://oncodaily.com/blog/214078)'
  focal_point: Right


---

<br><br>

**Background**<br>
Current research in medicine and biology predominantly focuses on applying artificial intelligence (AI) to analyze patient-specific imaging data, such as CT and MRI scans. However, the application of AI to next-generation sequencing (NGS) data, particularly transcriptomics, remains underutilized. RNA sequencing data is prone to biological and technical variability during generation, and the choice of error-correction and preprocessing methods can significantly influence downstream analyses. These challenges underscore the need for clear and systematic guidelines to optimize transcriptome data for AI-based analyses. In this study, we aim to identify optimal preprocessing strategies for developing AI models leveraging transcriptomic data. 

<br><br>

**Methods**<br>
We utilized RNA sequencing datasets from 25 independent cohorts, comprising over 5,800 patients with conditions such as lung adenocarcinoma, colorectal cancer, diabetes, and other diseases. A total of 18 combinatorial preprocessing pipelines were systematically assessed, encompassing 6 normalization methods (Raw, CPMTMM, RLE, UQ, RPKM, TPM) and 3 scaling methods (None, MinMax, Z-score). Over 20,000 transcripts were processed using each combination of normalization and scaling techniques. We then developed disease diagnosis models using 13 machine learning and deep learning algorithms. The performance of these models was evaluated to identify the most effective preprocessing strategies for transcriptomic data. 

<br><br>

**Conclusion**<br>
We identified algorithm-specific optimal preprocessing strategies to develop robust AI models utilizing transcriptomic data. Performance variations driven by normalization and scaling methods were observed for each algorithm, with these differences being particularly pronounced in datasets characterized by inherently lower model performance (difficult tasks). Our findings underscore the critical role of preprocessing in shaping model outcomes and provide a foundation for the development of tailored AI frameworks for disease diagnosis. This study offers a systematic approach to optimize transcriptomics-based predictive modeling, advancing the integration of AI into transcriptomic data analysis for clinical applications.