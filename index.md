# <center>360 Image Reference-based Super-Resolution using Latitude Aware Convolution Learned from Synthetic to Real
  
### <center>Hee-Jae Kim, Je-Won Kang, Byung-Uk Lee
### <center><i>Ewha Womans University 
  
<center>
<a href="https://github.com/iamheejae/Lat360">code</a>
</center>  

<center><img src="https://user-images.githubusercontent.com/42056469/141894745-a7205d85-9142-4ec2-92ea-a4f2591f2206.png" width="50"></center>
<center><img src="https://user-images.githubusercontent.com/42056469/141826157-30379a39-4bcd-4789-835c-5bfdcbc5fde4.png"></center>

<hr style="border: solid 1px gray;">
## Abstract
<div style="text-align:justify">
High-resolution (HR) 360-degree images offer great advantages wherever an omnidirectional view is necessary such as in autonomous robot systems and virtual reality (VR) applications. One or more 360-degree images in adjacent views can be utilized to significantly improve the resolution of a target 360-degree image. In this paper, we propose an efficient reference-based 360-degree image super-resolution (RefSR) technique to exploit a wide field of view (FoV) among adjacent 360-degree cameras. Effective exploitation of spatial correlation is critical to achieving high quality even though the distortion inherent in the equi-rectangular projection (ERP) is a nontrivial problem. Accordingly, we develop a long-range 360 disparity estimator (DE360) to overcome a large and distorted disparity, particularly near the poles. Latitude-aware convolution (LatConv) is designed to generate more robust features to circumvent the distortion and keep the image quality. We also develop synthetic 360-degree image datasets and introduce a synthetic-to-real learning scheme that transfers knowledge learned from synthetic 360-degree images to a deep neural network conducting super-resolution (SR) of camera-captured images. The proposed network can learn useful features in the ERP-domain using a sufficient number of synthetic samples. The network is then adapted to camera-captured images through the transfer layer with a limited number of real-world datasets.
</div>

<hr style="border: solid 1px gray;">
## Qualitative Result
  
![qualitative_comp](https://user-images.githubusercontent.com/42056469/141894670-9c616724-0ba8-48b2-bb23-6d02dd053555.png)
