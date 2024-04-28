# Facial Recognition Models for Diverse Indian Demographics

This repository contains the datasets, model codes, and test scripts for the facial recognition study titled "Surveying Facial Recognition Models for Diverse Indian Demographics: A Comparative Analysis on LFW and Custom Dataset". This research evaluates various facial recognition models using two datasets: the Labeled Faces in the Wild (LFW) and the custom IITJ Faces of Academia Dataset (JFAD).

## Repository Contents

- **Datasets**: Contains both the LFW subset and the JFAD dataset.
  - `LFW_subset`: Images from the LFW dataset used in our experiments.
  - `JFAD`: Our custom dataset created for this study.
- **Models**: IPYNB notebooks containing code for models used for facial recognition.
  - `CNN`: Code for the Convolutional Neural Network model.
  - `HybridModel`: Code for the Hybrid Model combining traditional and deep learning approaches.
  - `Traditional Models`: Code for traditional models like PCA, LDA, etc.
- **Scripts**: Utility scripts for data processing and testing.
  - `cv_preprocessing_v1.ipynb`: Script for preprocessing images from both datasets.
  - `test_webcam.py`: Script to run real-time facial recognition using a webcam.

## Setup

Clone this repository:
- git clone `https://github.com/niharikadadu/Surveying-Facial-Recognition-Models-for-Diverse-Indian-Demographics`

## Running the Models:

To run a model, download the corresponding ipynb file and the required dataset. 


## Datasets

### LFW Dataset Subset

This subset of the LFW dataset has been curated to mirror the structure of our custom JFAD in terms of the number of images per subject. Details on how this subset was created are given in the report. 

### IITJ Faces of Academia Dataset (JFAD)

This dataset includes 400 images representing 40 subjects, designed to reflect the ethnic diversity of the Indian academic community. More details are provided in the JFAD directory.

## Contributors
- Pranav Pant B21CS088
- Niharika Dadu B21CS052
- Harsh Vardhan Singh B21CS032
- Anshul Thakur B21CS085




