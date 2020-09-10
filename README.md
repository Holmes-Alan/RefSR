# Reference based Face Super-resolution

By Zhi-Song Liu, Wan-Chi Siu and Yui-am Chan

We propose a novel Conditional Variational AutoEncoder model for this Reference based Face Super-Resolution (RefSR-VAE). By using the encoder to map the reference image to the joint latent space, we can then use the decoder to sample the encoder results to super-resolve low-resolution facial images to generate super-resolution images with good visual quality.

The paper can be found in [IEEE](https://ieeexplore.ieee.org/abstract/document/8792098)

# BibTex
       @ARTICLE{8792098,  
               author={Z. {Liu} and W. {Siu} and Y. {Chan}},  
              journal={IEEE Access},   
              title={Reference Based Face Super-Resolution},   
              year={2019},  
              volume={7},  
              number={},  
              pages={129112-129126},
       }
        
# For proposed RefSR-VAE model, we claim the following points:

• We firstly propose a Single Image Super-Resolution via conditional Variational AutoEncoder (SISR-VAE) 

• We further propose a Reference based face SR via conditional Variational AutoEncoder (RefSR-VAE) to resolve face SR with large up-scaling factors. 

• Finally, we will introduce a new Reference based (RefSR-Face) dataset for the SR of face images for training and testing. 

# Dependencies
    Python > 3.0
    OpenCV library
    CAFE
    NVIDIA GPU + CUDA
    MATLAB 6.0 or above

# Complete Architecture
The complete architecture is shown as follows,

![structure](/figures/fig3.png)

# Dataset
We propose a Reference based face SR dataset. It is modified from VGGFace2. The target is to collect facial images across different sex, races and so on. Each identity should include several facial images with various poses, ages, emotions and so on. We show some example in the following figure.
![sample](/figures/sample.PNG)

You can download the dataset from the 


# Implementation
You can download the pre-trained models from

For RefSR-VAE, 
run RefSR_VAE.ipynb

For SISR-VAE,
run VAE-SR.ipynv

# Visual Comparison

## compare with state-of-the-art
This figure shows the comparison among different face SR algorithms on RefSR dataset
![figure1](/figures/compare_1.PNG)

## compare with state-of-the-art
This figure shows the facial identity transfer on RefSR dataset
![figure1](/figures/compare_2.PNG)

Please check the paper for more quantitative and qualitative comparison on different datasets
