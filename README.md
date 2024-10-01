# Cityscape Segmentation using Segformer Architecture

## Project Overview
This project implements semantic segmentation on the Cityscape dataset using the Segformer architecture. The model is trained to segment urban scenes into various classes, including roads, buildings, cars, pedestrians, and 19 such classes in total.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Architecture](#architecture)

## Introduction
Semantic segmentation is a pixel-level classification task aimed at assigning a class label to every pixel in an image. This project uses the Segformer architecture to perform segmentation on the Cityscape dataset, which contains images of urban environments.

## Dataset
At the time of this project a total of 19 classes were considered,
There were 2380 train images, 
595 validation images,
500 test Images
For more information on the dataset, visit the official [Cityscape Dataset](https://www.cityscapes-dataset.com/).

## Architecture
Segformer is a transformer-based model designed for semantic segmentation tasks. It leverages both local and global feature representations, providing a robust and scalable solution for vision tasks. This project uses the Segformer implementation from scratch, the model was built using the pytorch modular approach.

## Installation

To run this project, 
