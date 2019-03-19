# GAN-Face-Generator
In this project, i defined and train a DCGAN on a dataset of faces. The goal is to get a generator network to generate new images of faces that look as realistic as possible.

# Getting Started

## Get the Data
You'll be using the CelebFaces Attributes Dataset [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN) and so, you should prepare to define deeper networks and train them for a longer time to get good results. It is suggested that you utilize a GPU for training.

### Prerequisites

* Python 3.
* Numpy 
* Pandas
* MatPlotLib
* OpenCv
* Pytorch. 

## Project Instruction

### Instructions
1. Clone the repository and navigate to the downloaded folder.
	```	
	git clone https://github.com/shyamStarwalt/GAN-Face-Generator.git
	```

2. Download and Install Anaconda [from here](https://www.anaconda.com/)

3. Install the above packages mentioned in the Prerequisites (Anaconda Prompt)

4. Open the cloned repository and navigate to
	```
	cd Face-Generator
	```
5. Open the Face-Generator.ipynb
	```
	jupyter notebook Face-Generator.ipynb	
	```
6. Read and follow the instructions! This repository doesn't include any dataset you need. You can check out the getting started to download them.

## Project Information

### Contents

- Intro
- Step 0: Import Datasets
- Step 1: Define the Model
- Step 2: create a discriminator and a generator.
- Step 3: Create a GAN to Generate new faces (from Scratch) 
- Step 4: Build a complete network
- Step 5: Write your Algorithm
- Step 6: Test Your Algorithm

## Losses

### Model scratch:
Training loss: 3.508 ... Validation loss: 0.127

### Accuracy:

### Model scratch:
Accuracy : 14%

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* The data comes from Udacity.
