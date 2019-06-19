[//]: # (Image Reference)

[image1]: .assets/processed_face_data.png "Generated Faces"

# Face Generation

## Project Overview

In this project, I defined and trained a DCGAN on a dataset of faces. The goal of this project is to get a generator network to generate _new_ images of faces that look as realistic as possble. The image below is a result of the training:

![Generated Faces][image1]


## Project Instruction

### Instruction

1. Clone the repository and navigage to the downloaded folder.
	```
		git clone https://github.com/ayowolet/Face-Generation
		cd Face-Generation
	```
2. Open the `dlnd_face_generation.ipynb` file. The HTML version of the file is also available.
	```
		jupyter notebook dlnd_face_generation.ipynb
	```
3. Read and follow the instructions! This repository does not include the dataset of faces. You can find and download it in the notebook.

## Project Information

### Contents

- Pre-processed Data
- Create a DataLoader
- Define the Model
	- Discriminator
	- Generator
	- Initialize the weights of your network
	- Build complete network
- Discriminator and Generator Losses
- Optimizers
- Training
- Training Loss
- Generator samples from training

### Libraries

The list below represents main libraries and its objects for the project.
- [PyTorch](https://pytorch.org) (Generator and Discriminator)

### Accelerating the Training Process

Training is very time consuming, try to use GPU to train. 

### Amazon Web Services

You can use Amazon Web Services to launch an EC2 GPU instance. It is not free though.
