# Explainable COVID-19 CT Image Classification

This repository contains the source code for the study:

"An Explainable Transfer Learning Framework for Multi-Class COVID-19 CT Image Classification"

The project investigates transfer-learning-based deep learning models for the classification of chest CT images into three classes:

- NiCT: Non-infectious CT
- nCT: Non-COVID CT
- pCT: COVID-19 positive CT

The evaluated architectures include DenseNet121, MobileNetV2, EfficientNetB3, and ConvNeXt-Tiny. ViT-B/16 is also evaluated as a Vision Transformer baseline.

## Repository Contents

The repository contains the code used for model training, evaluation, and explainability analysis.

The exact scripts and notebook names are listed in the repository.

## Dataset

The experiments use the iCTCF2024 CT image dataset.

The dataset is not included in this repository. Users must obtain the dataset from its original source and organize the images according to the directory structure expected by the code.

## Requirements

The code was developed using Python and TensorFlow/Keras.

The required Python packages and their versions are listed in `requirements.txt`.

## Installation

Clone the repository:

git clone https://github.com/redamcomputer/COVID19_CT_Classification.git
cd COVID19_CT_Classification
