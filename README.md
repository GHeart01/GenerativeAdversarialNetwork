# Generative Adversarial Network (GAN) Project

## Description
This project explores the use of Generative Adversarial Networks (GANs) to perform style transfer, converting photographic images into Monet-style paintings. The project is inspired by the Kaggle competition, "I'm Something of a Painter Myself," which challenges participants to mimic the unique style of artists like Claude Monet using algorithms.

### Key Features:
- **Dataset**: Includes ~300 authentic Monet paintings and ~7,000 landscape photographs for training and testing.
- **Image Format**: Images are provided in both TFRecord and JPEG formats, typically sized 256x256 or 512x512 pixels.
- **Challenge**: Train a GAN to transform photos into Monet-style artworks, leveraging a generator and discriminator that work adversarially.

## Table of Contents
1. [Description](#description)
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
3. [GAN Model](#gan-model)
4. [Results and Analysis](#results-and-analysis)
5. [Hyperparameter Tuning](#hyperparameter-tuning)


## Exploratory Data Analysis (EDA)
The notebook begins with an exploratory analysis of the dataset, including:
- Loading and visualizing sample images from the Monet and photo datasets.
- Basic data inspection to understand the structure and format of the provided images.

## GAN Model
The project implements a GAN consisting of:
- **Generator**: Transforms input photos into Monet-style paintings.
- **Discriminator**: Evaluates the generated images against real Monet paintings, providing feedback to improve the generator.

Key steps:
1. **Data Preparation**: Loading and preprocessing the dataset.
2. **Model Architecture**: Defining the generator and discriminator networks.
3. **Training**: Adversarial training process to optimize both networks.

## Results and Analysis
- Evaluation of the generated images to assess how well the GAN captures Monet's style.
- Comparison of results before and after training, highlighting improvements and challenges.

## Hyperparameter Tuning
Experimentation with different hyperparameters to optimize the GAN's performance, such as:
- Learning rates for the generator and discriminator.
- Batch sizes and number of training epochs.
- Architectural variations (e.g., layer depths, activation functions).



