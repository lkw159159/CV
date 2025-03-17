---
title: 'DOGpred: A Novel Deep Learning Framework for Accurate Identification of Human
  O-linked Threonine Glycosylation Sites'
authors:
- Ki Wook Lee*
- Nhat Truong Pham*
- Hye Jung Min
- Hyun Woo Park
- Ji Won Lee
- Han-En Lo
- Na Young Kwon
- Jimin Seo
- Illia Shaginyan
- Heeje Cho
- ' others'
date: '2025-03-15T00:00:00Z'
publishDate: '2025-03-17T11:52:15.524178Z'
publication_types:
- article-journal
publication: '*Journal of Molecular Biology*'
abstract: O-linked glycosylation is a crucial post-translational modification that regulates protein function and biological processes. Dysregulation of this process is associated with various diseases, underscoring the need to accurately identify O-linked glycosylation sites on proteins. Current experimental methods for identifying O-linked threonine glycosylation (OTG) sites are often complex and costly. Consequently, developing computational tools that predict these sites based on protein features is crucial. Such tools can complement experimental approaches, enhancing our understanding of the role of OTG dysregulation in diseases and uncovering potential therapeutic targets. In this study, we developed DOGpred, a deep learning-based predictor for precisely identifying human OTGs using high-latent feature representations. Initially, we extracted nine different conventional feature descriptors (CFDs) and nine pre-trained protein language model (PLM)-based embeddings. Notably, each feature was encoded as a 2D tensor, capturing both the sequential and inherent feature characteristics. Subsequently, we designed a stacked convolutional neural network (CNN) module to learn spatial feature representations from CFDs and a stacked recurrent neural network (RNN) module to learn temporal feature representations from PLM-based embeddings. These features were integrated using attention-based fusion mechanisms to generate high-level feature representations for final classification. Ablation analysis and independent tests demonstrated that the optimal model (DOGpred), employing a stacked 1D CNN and a stacked attention-based RNN modules with cross-attention feature fusion, achieved the best performance on the training dataset and significantly outperformed machine learning-based single-feature models and state-of-the-art methods on independent datasets. Furthermore, DOGpred is publicly available at https://github.com/JeonRPM/DOGpred/ for free access and usage.

summary: a deep learning-based predictor for precisely identifying human OTGs using high-latent feature representations.

featured: true

tags:
 - Deep Learning Model

links:
 - name: Link
   url: https://www.sciencedirect.com/science/article/pii/S0022283625000439

image:
   caption: 'Image credit: [**JMB**](https://www.sciencedirect.com/science/article/pii/S0022283625000439#f0035)'
   focal_point: ""
   preview_only: false
 
---
