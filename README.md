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
  <img src="https://github.com/priyanshu1405/Enhanced-Brain-Tumor-Visuals/blob/main/BW.png" />
</p>
<br>
•	Prepare the dataset by normalizing, resizing, and augmenting the images to ensure data consistency and improve model robustness. <br>
•	Utilizing a U-net architecture as the foundation for image colorization. <br>
•	Implement a GAN to refine the colorization results. The generator network produces colorized images, while the discriminator network evaluates the realism of the colorization. <br>
<br>
<p align="center">   
  <img src="https://miro.medium.com/v2/resize:fit:1400/1*jhYv-BI-dEQe85I7B4qjcQ.png" width="700" height="350" />
<strong>Generator Model: </strong> To implement our generator model, we used a U-Net architecture. The U-Net has a reputation for being efficient at translating images into other images. U-Net is a convolutional neural network architecture used for tasks like image segmentation and image-to-image translation.
</p>
<br>
<p align="center">   
  <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.researchgate.net%2Ffigure%2FPatchGAN-discriminator-Each-value-of-the-output-matrix-represents-the-probability-of_fig1_323904616&psig=AOvVaw0AQsT4aaGBSIy1DEolKAQl&ust=1720007005209000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCICbz8ajiIcDFQAAAAAdAAAAABAE" width="700" height="350" />
<strong>Discriminator Model: </strong> A patch discriminator was used to
 assess the realism of the colorized images. This discriminator
 produces multiple real/fake judgments for patches of the
 image, allowing for more precise feedback during training.

</p>
<br>

•	Training the U-net and GAN components on the prepared dataset, optimizing them to generate high-quality colorized medical images.
