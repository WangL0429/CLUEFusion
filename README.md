# ILEFuse

The code will be released soon.

# Abstract

Infrared and visible image fusion struggles to produce high-quality results under suboptimal illumination. 
  Existing fusion methods only consider low-light enhancement as a “stepping stone” to improve visual quality, without effectively combining the characteristics of infrared and visible images, thus limiting performance under extreme lighting conditions.
  To overcome these limitations, this paper proposes a Coupled Learning for Unified Enhancement and Fusion, called CLUEFusion, which provides an appropriate illumination condition for infrared and visible image fusion through interaction-driven low-light enhancement.
  Specifically, the proposed shared illumination enhancement network is designed to learn and refine the illumination characteristics of low-light visible images. Building on these enhanced features, the scene recovery network integrates them with the complementary characteristics of infrared images.
  The one-pass imaging process enhances visibility and color rendition under low-light conditions and ensures efficient multimodal integration. 
  Leveraging the illumination–color estimator, fusion priors are fed back to the enhancement stage, steering the shared illumination enhancement network to produce illumination-consistent results with well-balanced colors and pronounced contrast.
  Extensive experiments demonstrate that our CLUEFusion not only produces outstanding fusion results but also enhances high-level visual tasks. 

# Experiments

![LLVIP_1](fig/LLVIP_1.png)
![LLVIP_2](fig/LLVIP_2.png)
