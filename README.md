# Leveraging Semi-Supervised Learning for Multimodal Medical Image Classification with Paired CT and MRI

This repository contains the implementation of our research work accepted at the 28th International Conference on Computer and Information Technology (ICCIT 2025).

## Overview

This project presents a comparative study of semi-supervised learning methods for brain disease classification using paired CT and MRI images. The goal is to reduce dependence on labeled medical data while maintaining high classification accuracy.

The approach combines multimodal learning with modern deep learning architectures, including convolutional neural networks and vision transformers.

## Methods

Supervised Models:
ConvNeXt-Tiny
DenseNet-121
MobileNetV3-Large
ViT-Base

Semi-Supervised Methods:
FixMatch
FlexMatch
Mean Teacher

## Results

ConvNeXt-Tiny (Supervised): 96.01 percent
FixMatch (ConvNeXt-Tiny): 92.86 percent
FixMatch (ViT-Small): 92.86 percent
FlexMatch (ViT-Small): 93.43 percent
Mean Teacher: lower performance compared to other methods

## Dataset

The project uses the Paired CT–MRI Disease Dataset.

Dataset details:

* 1167 aligned image slices
* Modalities: CT, T1-weighted MRI, T2-weighted MRI
* Images are spatially aligned across modalities

Dataset download link:
https://www.kaggle.com/datasets/29c3607295965ebb030f2d158fec487412d84c82528dd44f8ef956aef35541aa

## Project Structure

notebooks/
Contains all experiment notebooks including FixMatch, FlexMatch, and Mean Teacher implementations.

## How to Run

Install dependencies:
pip install -r requirements.txt

Run the notebooks from the notebooks folder.

## Paper
## Paper

This work has been accepted at the 28th International Conference on Computer and Information Technology (ICCIT 2025). The full paper will be made available after official publication.

## Authors

Erin Dewan Oishe
Md Arafat Hossain
Mohammad Rifat Ahmed Rashid
Faria Azad Anita
Raiyan Gani
Rashedul Amin Tuhin
Md Sabbir Hossain
Karib Shams
Raihan Ul Islam

## Citation
## Paper

This work has been accepted at the 28th International Conference on Computer and Information Technology (ICCIT 2025). The full paper will be made available after official publication.

## License

This project is for research and academic purposes.
