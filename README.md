Project Title and short (1-3 sentence) description of what your project does,

Project Title: A Comparison of Computer Vision Models on Image Classification of Melanoma Skin Cancer
Description: This project implements a CNN, ResNet-18, EfficientNet-B0, and a pre-trained ViT-16 to predict a given image as malignant or benign, and tracks the following metrics: training accuracy, validation accuracy, and time per epoch. This project replicates the architecture of models and displays similar results from this research paper.

What it Does section that describes in one paragraph what your project does.

This project implements a CNN, ResNet-18, EfficientNet-B0, and a pre-trained ViT-16. This project replicates the described architectures for the CNN, ResNet-18, and EfficientNet-B0 described in the  research paper “Classification of Melanoma Skin Cancer Based on Image Data Set Using Different Neural Networks.” The ViT model used is the pre-trained ViT-B16 model. This project resizes the input images to 224x224x3, creates a train-test-split and validation set, and passes these resized images to a modified CNN, ResNet-18, EfficientNet-B0, and pre-trained ViT. Following training, training accuracy versus validation accuracy of plotted for each model. EfficientNet-B0 exhibited the best performance on the validation set, and was subsequently evaluated on test data and its performance was compared using SDG, Adam, and AdamW. Using the EfficientNet-B0, we achieve a validation accuracy of 92%.

Quick Start section that concisely explains how to run your project

Download file “.ipynb”
Run code cell that implements kaggle and downloads the dataset "hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images"
Run subsequent code blocks

Video Links section with direct links to your demo and technical walkthrough videos,
Project Demo Link:
Technical Walkthrough Video Link:

Evaluation section that presents any quantitative results, accuracy metrics, or qualitative outcomes from testing,

CNN
ResNet-18
EfficientNet-B0
ViT-B16
EfficientNet-B0 using AdamW
EfficientNet-B0 using SGD
Confusion Matrices for CNN, ResNet-18, EfficientNet-B0, and ViT-B16
Individual Contributions
This project was completed alone and without additional group members.
