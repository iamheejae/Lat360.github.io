# <center>360 Image Reference-based Super-Resolution using Latitude Aware Convolution Learned from Synthetic to Real #
  
### <center>Hee-Jae Kim, Je-Won Kang, Byung-Uk Lee ###
### <center><i>Ewha Womans University ###
 
<center><img src="https://user-images.githubusercontent.com/42056469/141900193-de252325-673c-4797-9f1c-ebbcc11666a0.png" width="500" vspace="25px"></center>
    
<center><img src="https://user-images.githubusercontent.com/42056469/142144304-87285e6b-490f-4df4-8b6a-b5ea4b6941b8.png" vspace="25px"></center>

<center><img src="https://user-images.githubusercontent.com/42056469/143158150-7d83e0d3-471c-4b63-acdf-883cbeb29017.png" width="100" vspace="25px"></center>  
<center><a href="https://github.com/iamheejae/Lat360">[code] </a></center>   
<center><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9617634">[paper]</a></center>     
    
## Abstract ##
<div style="text-align:justify">
High-resolution (HR) 360-degree images offer great advantages wherever an omnidirectional view is necessary such as in autonomous robot systems and virtual reality (VR) applications. One or more 360-degree images in adjacent views can be utilized to significantly improve the resolution of a target 360-degree image. In this paper, we propose an efficient reference-based 360-degree image super-resolution (RefSR) technique to exploit a wide field of view (FoV) among adjacent 360-degree cameras. Effective exploitation of spatial correlation is critical to achieving high quality even though the distortion inherent in the equi-rectangular projection (ERP) is a nontrivial problem. Accordingly, we develop a long-range 360 disparity estimator (DE360) to overcome a large and distorted disparity, particularly near the poles. Latitude-aware convolution (LatConv) is designed to generate more robust features to circumvent the distortion and keep the image quality. We also develop synthetic 360-degree image datasets and introduce a synthetic-to-real learning scheme that transfers knowledge learned from synthetic 360-degree images to a deep neural network conducting super-resolution (SR) of camera-captured images. The proposed network can learn useful features in the ERP-domain using a sufficient number of synthetic samples. The network is then adapted to camera-captured images through the transfer layer with a limited number of real-world datasets.
</div>

## Dataset ##

### Synthetic360 Dataset ###
We use Unity software to render 400 virtual indoor/outdoor scenes. In each scenes, we record six reference videos from the virtual cameras positioned in 3D space around the target viewpoint. In half of the scenes, each camera is located 25 cm from the center. In the other half, the distance is set to 50 cm to test with various levels of similarity. 
  
<div style="width:47%; float:left;">
<center><img src="https://user-images.githubusercontent.com/42056469/147194351-cb451da5-e930-47ef-bca1-58b3de3009e6.jpg" width="300" vspace="25px"></center>
</div>
<div style="width:47%; float:right;">
<center><img src="https://user-images.githubusercontent.com/42056469/147195115-3fcb0b78-49ef-4304-9ff0-64bf86755c3e.png" width="250" vspace="25px"></center>
</div> 
  
<div style="clear:both;">
</div>
  
<div style="width:47%; float:left;">
<img src="https://user-images.githubusercontent.com/42056469/147187983-95abd413-55b6-425f-8ccb-c9ba21060cb0.gif" width="500" vspace="25px">
<center><figcaption>Target viewpoint</figcaption></center>
<img src="https://user-images.githubusercontent.com/42056469/147187720-00f376d5-739e-4999-b457-e1f5e7530f7c.gif" width="500" vspace="25px">
<center><figcaption>Refernce viewpoint 1</figcaption></center>
</div>
<div style="width:47%; float:right;">
<img src="https://user-images.githubusercontent.com/42056469/147187699-ca03abcb-7eae-48db-a6e3-0c0078b9ae0e.gif" width="500" vspace="25px">
<center><figcaption>Refernce viewpoint 2</figcaption></center>
<img src="https://user-images.githubusercontent.com/42056469/147187749-e79a8e33-6160-4774-8173-e80e78c93970.gif" width="500" vspace="25px">
<center><figcaption>Refernce viewpoint 3</figcaption></center>
</div> 

<div style="clear:both;">
</div>
  
## Qualitative Result ##
<div style="text-align:justify; float:inherit;">  
<center><img src="https://user-images.githubusercontent.com/42056469/141894670-9c616724-0ba8-48b2-bb23-6d02dd053555.png" vspace="25px"></center>
</div>
  
## Acknowledgement ##
<div style="text-align:justify; float:inherit;">  
This work was supported by the MSIT(Ministry of Science and ICT), Korea, under the ITRC(Information Technology Research Center) support program(IITP-2021-2020-0-01460) supervised by the IITP(Institute for Information & Communications Technology Planning & Evaluation).
</div>
  
<div style="text-align:justify; float:inherit;">  
This work was supported by the Institute of Information & Communications Technology Planning & Evaluation (IITP) grant funded by the Korea government(MSIT) (No. 2020-0-00920, Development of Ultra High Resolution Unstructured Plenoptic Video Storage/Compression/Streaming Technology for Medium to Large Space). 
</div>

<center><img src="https://user-images.githubusercontent.com/42056469/141919797-a847b341-d8ab-42ca-ae80-62be1c041b4e.png" vspace="25px"></center>

