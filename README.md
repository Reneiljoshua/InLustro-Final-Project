# Text Classification for Biomedical Publications with CNN and LSTM 📚🔬

## Overview ℹ️

This project is dedicated to classifying biomedical text publications into specific cancer types using state-of-the-art deep learning techniques. By leveraging Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks, our aim is to facilitate cancer research and enhance clinical decision-making processes in oncology.

## Problem Statement:

Biomedical research generates a vast amount of textual data, including research articles, clinical reports, and scholarly publications, which contain valuable insights into various aspects of cancer biology, treatment, and management. However, the sheer volume and complexity of this data make it challenging for researchers and clinicians to efficiently extract relevant information and identify trends or patterns.

Traditional manual methods of categorizing and analyzing biomedical text publications are time-consuming, labor-intensive, and prone to errors. Moreover, with the exponential growth of research literature in the field of oncology, there is an urgent need for automated solutions that can accurately classify and organize these publications based on specific cancer types.

Therefore, the problem statement revolves around developing a robust and scalable deep learning-based classification system capable of automatically categorizing biomedical text publications into relevant cancer types. The system should be able to process large volumes of textual data efficiently, while also providing accurate and interpretable classification results.

## Installation 🔧

To run the code locally, follow these steps:

1. Clone this repository:(https://github.com/Reneiljoshua/Text-Classification-for-Biomedical-Publications-with-CNN-and-LSTM/blob/main/Text%20Classification%20for%20Biomedical%20Publications%20with%20CNN%20and%20LSTM.ipynb)
2. Install the required dependencies:

## Usage 🚀

1. **Prepare the dataset:**
- Download the dataset from Kaggle and place it in the `data/` directory.
- Use the provided preprocessing scripts in the `preprocessing/` directory to clean, tokenize, and encode the text data.

2. **Train the models:**
- Execute the training scripts to train CNN and LSTM models respectively.
- Experiment with hyperparameters and model architectures to optimize performance.

3. **Evaluation:**
- Assess model performance using metrics such as accuracy, precision, recall, and F1-score.
- Conduct cross-validation and analyze the confusion matrix to evaluate model effectiveness and generalization.

4. **Deployment:**
- Deploy the trained models into a production environment for real-world applications, such as automated document classification in research databases or clinical decision support systems.

## Further Documentation 📑
For more detailed information, please refer to the presentation documentation included in the `docs/` directory. You can also explore the Kaggle dataset and additional resources to gain deeper insights into the project.

## Data 📊

The dataset used in this project is sourced from reputable journals and databases, encompassing a diverse range of cancer-related research articles. Each publication is meticulously labeled with the corresponding cancer type, including Thyroid Cancer, Colon Cancer, and Lung Cancer among others. You can explore the dataset in more detail on [**https://www.kaggle.com/dataset**](https://www.kaggle.com/datasets/falgunipatel19/biomedical-text-publication-classification).
