---
layout: page
title: Predicting Incident Bacterial Vaginosis with Machine Learning
description: Longitudinal microbiome modeling to predict bacterial vaginosis before clinical onset.
img: assets/img/12.jpg
importance: 2
category: work
related_publications: true
---


### Overview

Bacterial vaginosis (BV) is a common vaginal condition with high recurrence rates and limited ability to predict disease before symptoms appear. This project developed machine-learning models that identify **incident BV weeks prior to clinical diagnosis** using longitudinal vaginal microbiome data.

The focus was early risk stratification in real patients, rather than retrospective classification.

---

### Approach

- Longitudinal cohort with dense, patient-level sampling before BV onset  
- Vaginal microbiome profiling using 16S rRNA sequencing  
- Artificial neural networks trained on temporal microbial features  
- Built-in explainability using SHAP-based feature attribution  
- Parallel analysis of cohort-level trends and individual patient trajectories  

Models were designed to learn how microbiomes evolve over time leading into disease.

---

### Key Findings

- Predictive signal emerged well before clinical BV diagnosis  
- Model performance remained robust across heterogeneous baseline microbiomes  
- Feature attribution highlighted specific taxa and temporal shifts driving risk  
- Patient-level explanations revealed multiple mechanistic paths to BV  

---

### Outputs

- **U.S. Provisional Patent Application No. 63/778,989**  
  *Predicting Bacterial Vaginosis Development Using Artificial Neural Networks*  
  Inventors: Jacob Elnaggar, Christopher Taylor, John Lammons, Christina Muzny  
  Filed March 27, 2025  

- First-author manuscripts in preparation  
- Conference presentations and invited talks  
- Modeling framework reused in downstream dysbiosis and cancer-related projects  

---

### Clinical Relevance

Early identification of BV risk enables preventive interventions, personalized monitoring strategies, and a generalizable framework for predicting other microbiome-associated diseases. This work established a foundation for translating longitudinal microbiome data into clinically actionable tools.

---

### Tools & Methods

Python · TensorFlow · SHAP · scikit-learn · pandas · longitudinal modeling · reproducible pipelines
