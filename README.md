# Animal Face Image Classifier

This project uses a convolutional neural network (CNN) built with PyTorch to classify animal faces into three categories: dogs, cats, and wild animals.

## Overview

This repository contains a Jupyter Notebook (`image_classifier_.ipynb`) that demonstrates how to build, train, and evaluate a CNN for classifying images of animal faces. The model is trained on the "Animal Faces" dataset from Kaggle.

## Project Structure

*   `image_classifier_.ipynb`: Jupyter Notebook containing the complete code for the image classification task.
*   `animal-faces/`: (Directory) Contains the downloaded and extracted "Animal Faces" dataset. The structure within this directory will be:
    *   `afhq/`
        *   `train/`
            *   `cat/` (Contains cat images)
            *   `dog/` (Contains dog images)
            *   `wild/` (Contains wild animal images)
        *  `val/` (Validation Set - same structure as train)
        *   `test/` (Test set - same structure as train)

*   `requirements.txt`: A list of Python packages required to run the code.
*   `README.md`: This file, providing an overview of the project and instructions for running the code.

## Dependencies

*   Python 3
*   PyTorch (>=1.10.0)
*   Torchvision (>=0.11.0)
*   NumPy (>=1.21.0)
*   Pandas (>=1.3.0)
*   Scikit-learn (>=0.24.0)
*   Matplotlib (>=3.4.0)
*   Pillow (PIL) (>=8.0.0)
*   `opendatasets` (For automatic download of the dataset)

You can install these dependencies using `pip`:

```bash
pip install -r requirements.txt