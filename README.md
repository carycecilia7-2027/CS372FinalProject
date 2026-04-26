
**Project Title:** A Comparison of Computer Vision Models on Image Classification of Melanoma Skin Cancer

**Description:** This project implements a CNN, ResNet-18, EfficientNet-B0, and a pre-trained ViT-16 to predict a given image as malignant or benign, and tracks the following metrics: training accuracy, validation accuracy, and time per epoch. This project replicates the architecture of models and displays similar results from this research paper: https://pmc.ncbi.nlm.nih.gov/articles/PMC11607306/.

**What it Does**
This project implements a CNN, ResNet-18, EfficientNet-B0, and a pre-trained ViT-16. This project replicates the described architectures for the CNN, ResNet-18, and EfficientNet-B0 described in the  research paper “Classification of Melanoma Skin Cancer Based on Image Data Set Using Different Neural Networks.” The ViT model used is the pre-trained ViT-B16 model. This project resizes the input images to 224x224x3, creates a train-test-split and validation set, and passes these resized images to a modified CNN, ResNet-18, EfficientNet-B0, and pre-trained ViT. Following training, training accuracy versus validation accuracy of plotted for each model. EfficientNet-B0 exhibited the best performance on the validation set, and was subsequently evaluated on test data and its performance was compared using SDG, Adam, and AdamW. Using the EfficientNet-B0, we achieve a validation accuracy of 92%.

**Quick Start**
1. Download file “CeciliaCary_MLProject_Final.ipynb”
2. Run code cell that implements kaggle and downloads the dataset "hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images". This project uses a kaggle dataset that can be found here: https://www.kaggle.com/datasets/hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images
3. Run subsequent code blocks

**Video Links** 
1. Project Demo Link (Drive):
   https://drive.google.com/drive/folders/19FuVZkoVb3yJmvrR4nahyRd1awfaaLC9
   
   Project Demo Link (Youtube): https://youtu.be/Vr4NccpSAvs
   
2. Technical Walkthrough Video Link (Drive): https://drive.google.com/drive/folders/19FuVZkoVb3yJmvrR4nahyRd1awfaaLC9
   
   Technical Walkthrough Video Link (Youtibe): https://youtu.be/2Mq8pz8kRts

**Evaluation**
1. Training and Validation Plots
CNN
<img width="1219" height="388" alt="Screenshot 2026-04-26 at 1 33 46 PM" src="https://github.com/user-attachments/assets/200866fe-eec7-4c61-8502-35fc7d6bef23" />

ResNet-18
<img width="1194" height="389" alt="Screenshot 2026-04-26 at 1 34 17 PM" src="https://github.com/user-attachments/assets/27ea59be-0560-412f-9e15-ecd32de3d376" />

EfficientNet-B0
<img width="1198" height="386" alt="Screenshot 2026-04-26 at 1 34 40 PM" src="https://github.com/user-attachments/assets/a971e60e-c050-41d5-8b5a-d462b5bbfbb4" />

ViT-B16
<img width="1186" height="383" alt="Screenshot 2026-04-26 at 1 35 09 PM" src="https://github.com/user-attachments/assets/923d7688-e452-4967-afdf-eb87141ed31d" />

2. Evaluation on Test Data 
Summary Table
<img width="793" height="202" alt="Screenshot 2026-04-25 at 6 04 34 PM" src="https://github.com/user-attachments/assets/1fda1039-6f9f-4c57-b4bc-00a2d9f92816" />
Confusion Matrices
<img width="630" height="655" alt="Screenshot 2026-04-25 at 6 07 22 PM" src="https://github.com/user-attachments/assets/5b86385a-841e-4982-82b3-727710ee46e4" />

Error Analysis: Problematic Test Data That Were Mislabeled By Model
<img width="633" height="510" alt="Screenshot 2026-04-25 at 6 07 42 PM" src="https://github.com/user-attachments/assets/35627bdd-9b29-42c9-ada3-3372e9d474ee" />
<img width="634" height="525" alt="Screenshot 2026-04-25 at 6 08 06 PM" src="https://github.com/user-attachments/assets/95c6a79c-18a0-4ca0-8bb5-6bdbf70462b2" />

**Individual Contributions**
This project was completed alone and without additional group members.
