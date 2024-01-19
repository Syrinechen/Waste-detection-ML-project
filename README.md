# Waste-detection-ML-project

This repository contains the implementation and experimentation with YOLOv7 for object detection in waste sorting, focusing on a synthetic dataset. The project is organized as follows:

## Notebooks
training.ipynb: Jupyter notebook for training the YOLOv7 model on the synthetic dataset.
eval.ipynb: Jupyter notebook for evaluating the trained YOLOv7 model on the synthetic dataset.

Note that to reproduce the training experiments, the notebooks need to be run on colab (or vm with nvidia gpu)

## Data Generation

The data_generation folder contains scripts for generating the synthetic dataset used in training. These scripts cover various scenarios, including contrast variations, rotations, and overlapping elements.

## Results

The runs folder contains plots and visualizations of the results of the training and evaluation processes.

## YOLOv7 Implementation

The yolov7 folder is a submodule containing the YOLOv7 implementation. It is necessary for running the training and evaluation scripts in the notebooks.
