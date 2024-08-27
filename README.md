# African Wild Classification Project

This repository contains the code and resources for the Arewa Data Science Capstone Project by Group 2, focusing on the classification of African wildlife images using the Densely Connected Convolutional Networks (DenseNet) architecture. This deep learning project is developed with PyTorch and aims to contribute to wildlife conservation efforts by automating the identification process of various animal species.

## Project Overview

This project employs the DenseNet to classify images from the African Wildlife dataset, which includes species such as buffalo, elephant, rhino, and zebra. The goal is to support biodiversity monitoring and conservation through advanced computer vision techniques.

## **Team Members**

- Lukman Jibril Aliyu
- Umar Sani Muhammad
- Bilkisu Isma’il
- Nasiru Mohammed

## Dataset

The [African Wildlife dataset](https://www.kaggle.com/datasets/biancaferreira/african-wildlife) used in this study consists of balanced classes of buffalo, elephant, rhino, and zebra. The dataset is split into training and testing subsets using an 80-20 ratio. Each image is resized to 64x64 pixels and normalized to enhance the model's training and generalization capabilities.

## Methodology

The project utilizes the DenseNet201 architecture initialized with pre-trained ImageNet weights. The feature-extraction layers are frozen to save computational resources, focusing the training on the classification layers. We use the Adam optimizer with a learning rate of 0.001 and a CrossEntropy loss function for multi-class classification.

## Results

The model achieved a final test accuracy of approximately 68%. Training and validation accuracy and losses are documented through graphs on Wandb, showcasing the learning progress and model convergence. The project [paper](https://github.com/lukmanaj/wildlifeclassify/blob/main/project_paper.pdf) further explains the results.

## Deployment

The model is deployed on a Streamlit application for real-world testing and user interaction. Users can upload images to the platform and receive immediate classification results. Access the application [here](https://afriwildlifeclassify.streamlit.app/). A video demo can be found [here](https://youtu.be/Mp5iStr_wzs?si=0CMjfRQRHo72BVKy). For the streamlit implementation, check [here](https://github.com/lukmanaj/wildlifeclassifyapp)

## Future Work

Future directions include expanding the dataset with more diverse animal species, integrating location data, and improving model generalization through advanced data augmentation and training techniques.

## Contributions

We welcome contributions from the community to extend the dataset, enhance the model's performance, or improve the application's functionality.

## Acknowledgments

We extend our gratitude to the Arewa Data Science Academy, most especially our able mentor [Mr Mustapha Abdullahi](https://www.mustaphaabdullahi.com/) and [Dr Shamsuddeen H Muhammad](https://shmuhammadd.github.io/). Special thanks to our mentors and peers for their valuable guidance and feedback.
