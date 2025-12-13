# Identifying Tumors in CT and MRI Scans Through Deep Learning and GradCAM 

## Overview
This project aims to help with the problem of black-box models through high performing deep learning model and GradCAM. The goal is to visualize the regions of an image that most influence a model’s prediction, using this [Kaggle Dataset](https://www.kaggle.com/datasets/murtozalikhon/brain-tumor-multimodal-image-ct-and-mri)


### project/
- project.ipynb
- project.html

### src/
- ct.ipynb/: Preprocessing testing for CT scans
- data_exploration.ipynb/: Exploratory data analysis on both CT and MRI scans
- Grad_Cam/
   - Grad_Cam_CNN_CT.ipynb/: Trained stratified k-fold CNN model with evaluations and tested with GradCAM heat maps
   - Grad_CAM_CNN_MRI.ipynb/: Trained stratified k-fold CNN model with evaluations and tested and evaluated with GradCAM heat maps
   - Grad_Cam_Resnet_CT.ipynb/: Trained ResNet model with evaluations and tested and evaluated with GradCAM heat maps
   - Grad_CAM_Resnet_MRI.ipynb/: Trained ResNet model with evaluations and tested and evaluated with GradCAM heat maps
- models/
  - mri.ipynb/: Preprocessed, trained, and evaluated CNN model
  - resnet_for_ct.ipynb/: Preprocessed, trained, and evaluated ResNet CT model
  - resnet_for_mri.ipynb/: Preprocessed, trained, and evaluated ResNet MRI model
  - stratified_k_fold_mri.ipynb/: Preprocessed, trained with stratified k-fold and evaluated CNN MRI model
