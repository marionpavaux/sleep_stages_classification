# Sleep Stages Classification

Challenge project made in collaboration with the Start-up Dreem. 

This repository contains our report in the form of a python notebook, which explains every step of our project.

Our work is based on the method of the article "A Comparative Study on Classification of Sleep Stage Based on EEG Signals Using Feature Selection and Classification Algorithms" from Baha Şen & Musa Peker & Abdullah Çavuşoğlu & Fatih V. Çelebi [5] and the features from the article "Sleep Stage Classification Using EEG Signal Analysis: A Comprehensive Survey and New Investigation" from Khald Ali I. Aboalayon 1, Miad Faezipour 1, [4].

In Addition, we applied Power Spectral Density on our data, based on the article "Chambon, Stanislas, Mathieu N. Galtier, Pierrick J. Arnal, Gilles Wainrib, et Alexandre Gramfort. « A Deep Learning Architecture for Temporal Sleep Stage Classification Using Multivariate and Multimodal Time Series ».[6]

The design of the pipeline is based on pre-processing, features extraction and selection, and classification. Features are extracted from both Train and Test data. The model is trained on Training Data from which features have been selected. 


## Environment creation ##

<ol>

<li>create conda environment with name sleep_classification</li>
conda create -n sleep_classification anaconda python=3.9

<li>activate environment 
conda activate sleep_classification

<li>install antropy</li> 
pip install antropy

<li>install eeglib</li> 
pip install eeglib

<li>install pywt</li>
conda install pywavelets

<li>update the environment 
conda update --all 

</ol>

## Data ##

Data remain stricly confidential.