# Tensorflow-2020-Hackathon
GANs and web app generating artificial human faces

Facial detection/recognition algorithms are often biased because the training data doesn't contain enough diverse faces. The solution uses StyleGAN2 to create additional samples to train models on.

# Requirements
* Both Linux and Windows are supported. Linux is recommended for performance and compatibility reasons.
    64-bit Python 3.6 installation. We recommend Anaconda3 with numpy 1.14.3 or newer.
* TensorFlow 1.14 or 1.15 with GPU support. The code does not support TensorFlow 2.0.
* On Windows, you need to use TensorFlow 1.14 — TensorFlow 1.15 will not work.
 * One or more high-end NVIDIA GPUs, NVIDIA drivers, CUDA 10.0 toolkit and cuDNN 7.5.


The model has been pretrained using Flickr-Faces-HQ dataset, which can be found here:
https://github.com/NVlabs/ffhq-dataset

Other pre-trained GAN models can be downloaded from here: https://drive.google.com/drive/folders/1yanUI9m4b4PWzR0eurKNq6JR1Bbfbh6L

# Running
To run the model simply run the notebook in Google Colab or clone the whole codebase and run on your machine.
