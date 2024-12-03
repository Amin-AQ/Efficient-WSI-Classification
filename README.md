# Integrating Hierarchical Feature Aggregation and Multimodal LLM Pipelines for Efficient Whole Slide Image Classification

This repository contains code and notebooks related to **Hierarchical Feature Aggregation (HFA)** and **BioMedCLIP** pipelines on the BACH dataset. The project is organized into different subfolders for different BACH datasets (BACH-A and BACH-B). Each dataset contains subfolders for different approaches, including **BiomedCLIP** and **HFA**.

## Directory Structure

```
src/
    BACH-A/
        BioMedCLIP/
            biomed_bach_a.ipynb
        HFA/
            hfa_bach_a.ipynb
    BACH-B/
        BiomedCLIP/
            5_fold_cross_validation.ipynb
            patch_level_feature_extraction.ipynb
        HFA/
            5_fold_cross_validation.ipynb
            patch_level_feature_extraction.ipynb
            with_autoencoder.ipynb
            with_pca.ipynb
```

### BACH-A

- **BioMedCLIP**:
  - `biomed_bach_a.ipynb`: Notebook for BioMedCLIP pipeline on BACH-A dataset.

- **HFA**:
  - `hfa_bach_a.ipynb`: Notebook for Hierarchical Feature Aggregation (HFA) pipeline on BACH-A dataset.

### BACH-B

- **BioMedCLIP**:
  - `5_fold_cross_validation.ipynb`: Notebook for 5-fold cross-validation using BioMedCLIP on BACH-B dataset.
  - `patch_level_feature_extraction.ipynb`: Notebook for patch-level feature extraction using BioMedCLIP on BACH-B dataset.

- **HFA**:
  - `5_fold_cross_validation.ipynb`: Notebook for 5-fold cross-validation using HFA on BACH-B dataset.
  - `patch_level_feature_extraction.ipynb`: Notebook for patch-level feature extraction using HFA on BACH-B dataset.
  - `with_autoencoder.ipynb`: Notebook for HFA with autoencoder applied to BACH-B dataset.
  - `with_pca.ipynb`: Notebook for HFA with PCA applied to BACH-B dataset.

## Description

This project applies **Hierarchical Feature Aggregation (HFA)**, a method for feature extraction and aggregation and **BioMedCLIP**, a method for feature extraction based on CLIP, and various experiments involving dimensionality reduction techniques like **PCA** and **autoencoders**.


