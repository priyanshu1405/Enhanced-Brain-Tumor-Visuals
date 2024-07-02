# Enhanced Brain Tumor Detection using U-Net and GAN-based Colorization

<p align="center">   
    <a href="https://pytorch.org/" alt="PyTorch">
      <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?e&logo=PyTorch&logoColor=white" /></a>
</p>

The official repository for [**Enhanced Brain Tumor Detection using U-Net and GAN-based Colorization**](https://github.com/priyanshu1405/Enhanced-Brain-Tumor-Visuals).

## Abstract
Medical images are essential for diagnosis and planning of treatment in the field of brain tumor detection. 
Grayscale images, however, frequently lack the visual depth required for precise interpretation. 
By creating a solid system specifically designed for automatic colorization of black-and-white medical photos, 
our research study aims to overcome this problem. The main goal is to improve medical picture research and analysis by adding more visual data, particularly in the context of brain tumor diagnosis.

## Relevance
•	Precision in Diagnosis: The addition of color to medical photographs helps draw attention to minute details and irregularities that are essential for a precise diagnosis of brain tumors.<br>
•	Colorization helps medical professionals better grasp the spatial relationships within images, which helps in the evaluation of tumor size, location, and features.<br>
•	Effective Brain Tumor Detection Requires Timely and Accurate Image Analysis: Automated colorization speeds image analysis, saving crucial time for medical professionals and reducing errors brought on by image fatigue.

## Implementation:
•	Choosing a comprehensive dataset that focuses particularly on black-and-white medical photos linked to the identification of brain tumors. <br>
<p align="center">   
  <img src="https://github.com/priyanshu1405/Enhanced-Brain-Tumor-Visuals/blob/main/BW.png" /></a>
</p>
•	Prepare the dataset by normalizing, resizing, and augmenting the images to ensure data consistency and improve model robustness. <br>
•	Utilizing a U-net architecture as the foundation for image colorization. <br>
•	Implement a GAN to refine the colorization results. The generator network produces colorized images, while the discriminator network evaluates the realism of the colorization. <br>
•	Training the U-net and GAN components on the prepared dataset, optimizing them to generate high-quality colorized medical images.
