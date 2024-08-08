# Project Title: Self Driving Car 
This project aims to obtain a segmentation model that is capable of segmenting objects on the highway such as: traffic lights, traffic signs, other vehicles, and also the presence of pedestrians.

# Introduction
![self-driving-patent-newsdesk](https://github.com/user-attachments/assets/d76e50c8-82d4-4c61-a4f0-1eaff0ddeede)
<p align="justify">
  The total number of traffic accidents in Indonesia throughout 2023 was recorded at 116,000 cases. This number increased by 6.8% compared to last year. A total of 45,000 cases out of 116,000 were frontal collisions. This is very important 
  because it is negligence. Self-driving cars are expected to be a solution to reduce the level of traffic accidents which are mostly caused by driver negligence
</p>

# What is to do in this project?
<p align="justify">
  We compare various algorithms of image segmentation i.e. model:Vanilla CNN, VGG-16 dan ResNet-50, and Head Segmentation Model: FCN8, Unet dan Segnet) to get the base model from the value of model loss, validation dice-los, validation accuracy and the result of various segmentation before. 
  After that, we get the Resnet50_Unet as the best model and di fine tuning with several combination of image augmenatation. 
  The last, we implement our best model from fine tuning using hugging face, with the link below:
  https://huggingface.co/spaces/eurekalabdawara/computervision-keras-segmentation
</p>
