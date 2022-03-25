# White Blood Cells Classification Using Transfer Learning Technique
White blood cells (WBCs) differential counting yields valued information about human health and disease. The current developed automated cell morphology equipments per- form differential count which is based on blood smear image analysis. Previous identification systems for WBCs consist of successive dependent stages; pre-processing, segmentation, feature extraction, feature selection, and classification. There is a real need to employ deep learning methodologies so that the performance of previous WBCs identification systems can be increased.

## Proposed methods
In this project, we propose novel identification system for WBCs based on transfer learning and fine-tuning of existed deep convolutional neural networks.

## About Dataset

The dataset was taken from [here](https://raabindata.com/free-data).
This dataset containing five main classes including mature **neutrophils**, **lymphocytes** (small and large), **eosinophils**, **monocytes**, and **basophils**.



## Pre-trained Model

A pre-trained model is a model that was trained on a large benchmark dataset to solve a problem similar to the one that we want to solve. Accordingly, due to the computational cost of training such models, it is common practice to import and use models from published literature (e.g. VGG, InceptionV3, ResNet50). For this project, I decided to use **InceptionV3** model to perform image classification for brain tumor MRI images.[InceptionV3 Article](http://arxiv.org/abs/1512.00567)

## Basic Requirements

| **Package Name**      | **Version** |
| --------------------- | ----------- |
| `python`              | 3.7.12      |
| `tensorflow`          | 2.6.0       |
| `keras`               | 2.6.0       |
| `keras-preprocessing` | 1.1.2       |
| `matplotlib`          | 3.0.2       |
| `opencv`              | 4.1.2       |
| `scikit-learn`        | 0.22.2      |

## Note
You can see more details about training steps and testing results inside [White_Blood_Cells_Classification.ipynb](https://github.com/masoudnick/White-Blood-Cells-Classification/blob/main/White_Blood_Cells_Classification.ipynb)


