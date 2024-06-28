# Monet to Photo Image Generation

This repository contains the code for generating images in the style of Monet using a CycleGAN model. The project is part of a Kaggle competition, where the objective is to transform photos into Monet-style paintings and vice versa.

## Project Overview

This project involves training a CycleGAN model to generate images in the style of Monet. The model takes input images and generates corresponding images in the Monet style. The generated images are then saved in a zip file for submission to the competition.

## Directory Structure
GAN_Monet.ipynb

## Usage
Train the Model: Use the training notebook provided in the notebooks directory to train the CycleGAN model. Ensure you have the training data in the data directory.

Generate Images: Use the trained model to generate Monet-style images. The save_generated_images_to_zip function in the notebook will save the generated images into a zip file for submission.

Submission: The generated images are saved in a zip file (images.zip). This file can be submitted to the Kaggle competition.
