# Sleep Stages Classification

Challenge project made in collaboration with the Start-up Dreem.

---

## Context

This repository contains our report and code in the form of a python notebook, which explains every step of the project.

Our work is based on the method of the article "A Comparative Study on Classification of Sleep Stage Based on EEG Signals Using Feature Selection and Classification Algorithms" from Baha Şen & Musa Peker & Abdullah Çavuşoğlu & Fatih V. Çelebi [5] and the features from the article "Sleep Stage Classification Using EEG Signal Analysis: A Comprehensive Survey and New Investigation" from Khald Ali I. Aboalayon 1, Miad Faezipour 1, [4].

In Addition, we applied Power Spectral Density on our data, based on the article "Chambon, Stanislas, Mathieu N. Galtier, Pierrick J. Arnal, Gilles Wainrib, et Alexandre Gramfort. « A Deep Learning Architecture for Temporal Sleep Stage Classification Using Multivariate and Multimodal Time Series ».[6]

The design of the pipeline is based on pre-processing, features extraction and selection, and classification. Features are extracted from both Train and Test data. The model is trained on Training Data from which features have been selected.

## Environment creation

1. create conda environment with name sleep_classification :
   `conda create -f environment.yml`

2. activate environment :
   `conda activate sleep_classification`

## Data

Data remain stricly confidential.
