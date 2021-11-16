<span style="font-family: 'Lucida Console';">foo</span>

# <center>360 Image Reference-based Super-Resolution using Latitude Aware Convolution Learned from Synthetic to Real #
  
### <center>Hee-Jae Kim, Je-Won Kang, Byung-Uk Lee ###
### <center><i>Ewha Womans University ###
  
<center><a href="https://github.com/iamheejae/Lat360">code</a></center>  
    
  
<center><img src="https://user-images.githubusercontent.com/42056469/141900193-de252325-673c-4797-9f1c-ebbcc11666a0.png" width="500" vspace="25px"></center>
    
    
<center><img src="https://user-images.githubusercontent.com/42056469/141826157-30379a39-4bcd-4789-835c-5bfdcbc5fde4.png" vspace="25px"></center>
  
## Abstract ##
<div style="text-align:justify">
High-resolution (HR) 360-degree images offer great advantages wherever an omnidirectional view is necessary such as in autonomous robot systems and virtual reality (VR) applications. One or more 360-degree images in adjacent views can be utilized to significantly improve the resolution of a target 360-degree image. In this paper, we propose an efficient reference-based 360-degree image super-resolution (RefSR) technique to exploit a wide field of view (FoV) among adjacent 360-degree cameras. Effective exploitation of spatial correlation is critical to achieving high quality even though the distortion inherent in the equi-rectangular projection (ERP) is a nontrivial problem. Accordingly, we develop a long-range 360 disparity estimator (DE360) to overcome a large and distorted disparity, particularly near the poles. Latitude-aware convolution (LatConv) is designed to generate more robust features to circumvent the distortion and keep the image quality. We also develop synthetic 360-degree image datasets and introduce a synthetic-to-real learning scheme that transfers knowledge learned from synthetic 360-degree images to a deep neural network conducting super-resolution (SR) of camera-captured images. The proposed network can learn useful features in the ERP-domain using a sufficient number of synthetic samples. The network is then adapted to camera-captured images through the transfer layer with a limited number of real-world datasets.
</div>

## Qualitative Result ##

<center><img src="https://user-images.githubusercontent.com/42056469/141894670-9c616724-0ba8-48b2-bb23-6d02dd053555.png" vspace="25px"></center>

## Acknowledgement ##
<div style="text-align:justify">  
This work was supported by the MSIT(Ministry of Science and ICT), Korea, under the ITRC(Information Technology Research Center) support program(IITP-2021-2020-0-01460) supervised by the IITP(Institute for Information & Communications Technology Planning & Evaluation)

This work was supported by the Institute of Information & Communications Technology Planning & Evaluation (IITP) grant funded by the Korea government(MSIT) (No. 2020-0-00920, Development of Ultra High Resolution Unstructured Plenoptic Video Storage/Compression/Streaming Technology for Medium to Large Space). 
</div>

<center><img src="https://user-images.githubusercontent.com/42056469/141919797-a847b341-d8ab-42ca-ae80-62be1c041b4e.png" vspace="25px"></center>
  
