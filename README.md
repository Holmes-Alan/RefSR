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

• we further propose a Reference based face SR via conditional Variational AutoEncoder (RefSR-VAE) to resolve face SR with large up-scaling factors. 

• Finally, we will introduce a new Reference based (RefSR-Face) dataset for the SR of face images for training and testing. 

# Dependencies
    Python > 3.0
    OpenCV library
    CAFE
    NVIDIA GPU + CUDA
    MATLAB 6.0 or above
