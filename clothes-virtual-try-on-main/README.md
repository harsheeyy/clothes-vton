# Cloths Virtual Try On
This Project is made by Harshith Tadikonda & Bashwanth Kalavakuri students of SRM INSTITUTE OF SCIENCE AND TECHNOLOGY
[![Open in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SwayamInSync/clothes-virtual-try-on/blob/main/setup_gradio.ipynb)
  IMPLEMENTATION


![demonstraion of Virtual trail on VITON](https://github.com/user-attachments/assets/5592915e-e7b6-4e1c-b3a5-667d328196d6)









![video demonstration of AR Virtual trail on using SnapAR and Unity](https://github.com/user-attachments/assets/af17bf25-1fbb-4810-984c-1de3f720e591)


[Implentation of ar for Virtual trail on](https://github.com/user-attachments/assets/1db0e8de-bc44-4ead-91e2-b8c4e987c4f3)


For a Virtual Trial Room project—whether it's using AI (for static image try-on) or AR (for real-time overlay)—the libraries and tools you use depend on your tech stack and approach. Here's a breakdown for both AI-based and AR-based virtual try-ons:



1. AI-Based Virtual Try-On (Image-based)

These systems are like trying on clothes in a selfie or model image using deep learning.

Core Libraries:

Python

OpenCV – image processing

NumPy – numerical operations

PIL (Pillow) – image manipulation

matplotlib – debugging visualizations



Deep Learning:

PyTorch or TensorFlow – for model training/inference

Torchvision – pre-trained models and image transformations


Pretrained Models / Architectures:

VITON / VITON-HD – for virtual try-on (clothing warping + rendering)

ClothFlow, CP-VTON, TryOnGAN – alternative models

Human Parsing (for segmenting body parts):

Libraries: self-supervised-segmentation, DensePose, or custom UNet-based parsers



Other Utilities:

SciPy – for advanced warping or transformations

scikit-image – additional image processing

albumentations – for data augmentation during training




2. AR-Based Virtual Try-On (Real-time using Camera)

These are used for mobile/web-based AR experiences.

Frameworks & SDKs:

Unity + Vuforia / AR Foundation

SnapLens Studio (for Snapchat filters)

8thWall (WebAR platform)

Spark AR (Meta/Instagram)

WebXR or Three.js + AR.js (browser-based)


Languages & Tools:

C# (for Unity)

JavaScript (for WebAR)

Blender / Maya – for 3D model creation

GLTF / USDZ – for 3D file formats




Bonus Tools (both types):

LabelMe / Supervisely – for manual data annotation

WandB / TensorBoard – for experiment tracking

Google Colab / Jupyter – for prototyping



