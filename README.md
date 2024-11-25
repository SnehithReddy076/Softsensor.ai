# Digital Pathology and NLP Tasks

## Introduction

This project focuses on tasks related to digital pathology and natural language processing (NLP). Digital pathology involves analyzing whole slide images (WSIs) to support pathologists by identifying potential disease locations. NLP is used to process and extract valuable knowledge from pathology-related text data.

The objectives include:
- **Image Tiling and Processing**: Preprocessing WSIs for tissue analysis.
- **Deep Learning Classification**: Differentiating between normal and reactive lymph nodes.
- **NLP-Based Knowledge Extraction**: Constructing a dictionary of organ-specific terms using information from a pathology website.

---

## Data Overview

### Provided Data
The dataset consists of two WSIs:
1. **Normal Lymph Node**: File with `.svs` extension.
2. **Reactive Lymph Node**: File with `.svs` extension.

### Data Source
The data is available in the folder `assignment data`, which includes the WSIs under the folder `whole slide images`.

### External Resources
- **Pathology Knowledge**: Extracted from the website [Pathology Outlines](https://www.pathologyoutlines.com/).

---

## Tasks Description

### Task 1: Image Tiling
Break down the WSIs into smaller tiles or patches containing maximum tissue content for efficient analysis.

### Task 2: Image Preprocessing
Normalize stain variations across WSIs to ensure visual similarity using appropriate image processing techniques.

### Task 3: Image Classification
Train a deep learning classification model to distinguish between the two categories:
- **Normal Lymph Node**
- **Reactive Lymph Node**

Provide model performance metrics, including:
- Accuracy
- Loss Graphs
- Confusion Matrix

### Task 4: NLP Dictionary Creation
Using NLP, create a dictionary where:
- **Keys**: Names of organs (e.g., Adrenal gland).
- **Values**: Associated terms extracted from the website content.

---


### Features
- **Automated Tiling:** Break down WSIs into manageable patches for better processing.
- **Stain Normalization:** Address inter-laboratory variations in slide appearances.
- **Deep Learning:** Robust classification of lymph node categories with performance evaluation.
- **NLP Extraction:** Automated dictionary creation to support pathology interpretation.
