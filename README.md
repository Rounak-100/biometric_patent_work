# Adaptive Quality-Aware and Spoof-Resistant Multimodal Biometric Verification

## Overview

This repository presents an adaptive multimodal biometric verification framework using **Palmprint** and **Iris** biometrics. The proposed system integrates **Quality Assessment**, **Spoof Detection**, **Adaptive Gated Fusion**, **Dynamic Trust Scoring**, and **Siamese Metric Learning** to achieve robust and secure biometric authentication.

The framework learns discriminative multimodal embeddings using EfficientNet-based Siamese networks and Triplet Loss while supporting efficient deployment on edge devices through model optimization techniques.

---

## Files

* **palm-unimodal-code.ipynb**
  Siamese biometric verification using palmprint images.

* **iris-unimodal-code.ipynb**
  Siamese biometric verification using iris images.

* **proposed-multimodal-model.ipynb**
  Proposed multimodal verification framework with quality-aware gated fusion and trust scoring

* **proposed_model_architecture.png**
  Visual illustration of the proposed multimodal gated Siamese architecture.

* **siamese_model_workflow_diagram.png**
  Workflow diagram illustrating the Siamese metric learning pipeline for biometric verification.

---

## Dataset

Experiments are conducted on the **Multimodal University of Bologna (MULB) Dataset** using Palmprint and Iris modalities.

Dataset:

```bash
https://www.kaggle.com/datasets/olankadhim/multimodal-biometric-dataset-mulb
```

Update dataset paths inside the notebooks before execution.

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Train

### Palm Verification Model

```bash
palm-unimodal-code.ipynb
```

### Iris Verification Model

```bash
iris-unimodal-code.ipynb
```

### Proposed Multimodal Model

```bash
proposed-multimodal-model.ipynb
```

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* FAR
* FRR
* EER
* Spoof Detection Accuracy
* Trust Score Analysis

---

## Key Contributions

* Quality-Aware Biometric Verification
* Spoof-Resistant Authentication
* Adaptive Gated Feature Fusion
* Dynamic Trust Scoring
* Siamese Metric Learning with Triplet Loss
* Edge-Optimized Deployment

---
