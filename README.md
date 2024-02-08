# PVTAD: ALZHEIMER'S DISEASE DIAGNOSIS USING PYRAMID VISION TRANSFORMER APPLIED TO WHITE MATTER OF T1-WEIGHTED STRUCTURAL MRI DATA
This repository contains the code for this research article:<br>
Maryam Akhavan Aghdam, Serdar Bozdan, Fahad Saeed, Alzheimer’s Dissease (2024), PVTAD: ALZHEIMER'S DISEASE DIAGNOSIS USING PYRAMID VISION TRANSFORMER APPLIED TO WHITE MATTER OF T1-WEIGHTED STRUCTURAL MRI DATA

## Prerequisites
Required packages can be installed on python3.6 environment.
### Installing Libraries & Dependencies
```
pip install tensorflow
pip install keras
pip install scikit-learn
pip install tfimm
pip install timm
pip install opencv-python
```
### Data
In this research, we used T1-weighted magnetization prepared rapid gradient echo (MPRAGE) sMRI scans from Alzheimer’s Disease Neuroimaging Initiative (ADNI) database. 
We decomposed each 3D preprocessed WM of sMRI data into 2D coronal slices.

## Train & Test
All models including ResNet-18, standard ViT(Tiny), Pyramid ViT (Tiny), and parallel ResNet-18 & standard ViT(Tiny)were implemented in PVTAD_Project.ipynb <br><br> Run PVTAD_Project.ipynb

In case of any questions please contact: makha003@fiu.edu 
