# Face-Aging-Using-GAN-and-cycle-GAN

## Project Aim

The aim of this project is to implement a CycleGAN model with Instance Normalization to perform face aging. The goal is to convert images between young and old age groups using the UTKFace dataset.

## Objectives

- **Develop a CycleGAN Model:** Implement a CycleGAN model that uses Instance Normalization to enhance performance for style transfer tasks, specifically for face aging.
- **Image Translation:** Train the model to convert facial images between young and old age groups.
- **Dataset Utilization:** Use the UTKFace dataset, which contains a diverse set of facial images labeled with age, gender, and ethnicity, to train and evaluate the model.

## Dataset

The UTKFace dataset includes images of faces labeled with age, gender, and ethnicity. It will be used to train the CycleGAN model for the task of face aging. You can download the dataset from [UTKFace Dataset](https://s3.amazonaws.com/udacity-aind/datasets/UTKFace/UTKFace.tar.gz).

## Model Architecture

CycleGAN uses two sets of generators and discriminators:
- **Generators:** Transform images from one domain (e.g., young faces) to another domain (e.g., old faces) and vice versa.
- **Discriminators:** Evaluate the realism of generated images compared to real images from the target domain.

Instance Normalization is employed instead of Batch Normalization to better handle style transfer tasks.
