# COCO RAG Captioning

## 1. Project Overview

This project focuses on **data exploration and preprocessing for image captioning using Retrieval-Augmented Generation (RAG)** techniques.

It uses the Microsoft Common Objects in Context (COCO) dataset, which contains images and their corresponding human-written captions.

The objective of Phase 1 is to prepare a clean, organized, and reproducible dataset that can be used in the following stages of the project.

## 2. Phase 1: Data Exploration and Preprocessing

Phase 1 focuses on the preparation and analysis of the COCO dataset.

The main tasks include:

- Exploring the COCO dataset and its annotations.
- Auditing and validating the selected data.
- Creating and checking dataset splits.
- Preprocessing images and captions.
- Preparing image metadata.
- Generating image and text embeddings.
- Building a vector index using FAISS.
- Performing quality-control checks and documenting the results.
- Generating visualizations and dataset statistics.

## 3. Dataset

The project uses a selected subset of the **Microsoft COCO dataset**.

The dataset contains images and five human-written reference captions per image.

### Dataset Splits

| Dataset split             | Number of images |
| ------------------------- | ---------------: |
| Training / Knowledge Base |           10,000 |
| Validation                |              100 |
| Testing                   |              100 |

The image identifiers for the different splits are stored in JSON files to support reproducibility and split management.

## 4. Preprocessing Workflow

The Phase 1 workflow consists of the following steps:

1. **Dataset Exploration and Audit:** Inspect the dataset, examine its annotations, and check data consistency.
2. **Split Creation:** Prepare image ID files for training, validation, and testing, and perform leakage checks.
3. **Image Preprocessing:** Prepare images for feature extraction.
4. **Caption Preprocessing:** Prepare and clean captions while preserving the original reference captions.
5. **Metadata Preparation:** Organize relevant information associated with the selected images.
6. **Embedding Generation:** Extract vector representations of images and text.
7. **Vector Indexing:** Build a FAISS index to support similarity-based retrieval.
8. **Quality Control:** Check dataset integrity, missing data, duplicates, and other potential inconsistencies.
9. **Data Visualization:** Generate figures and statistics to analyze the dataset.

## 5. Project Status

**Current phase:** Phase 1 — Data Exploration and Pre-processing.

The current work focuses on preparing, analyzing, validating, and documenting the dataset for the subsequent stages of the project.
