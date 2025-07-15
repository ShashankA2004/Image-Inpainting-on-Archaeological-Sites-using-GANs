# Image-Inpainting-on-Archaeological-Sites-using-GANs
## Image Inpainting on Archeological Dataset using Context Encoder GAN
This repository contains the implementation and evaluation of a novel approach for enhancing the quality of picture inpainting in archaeological datasets. The proposed method uses context encoder GAN by incorporating the MS-SSIM loss function, which effectively denoises the output. The goal is to reconstruct damaged or missing portions of images commonly found in archaeological photographs due to the passage of time or excavation procedures.

## Introduction
Image inpainting is a widely used technique in various domains, including image editing, object removal, and image restoration. In the context of archaeological data, this technique becomes valuable for restoring and analyzing historical images. This paper presents a novel approach that significantly improves the quality of picture inpainting in archaeological datasets. intro_images

## Methodology
The proposed approach is based on the Context Encoder GAN architecture, a generative adversarial network designed for image inpainting tasks. To enhance restoration quality, we incorporate the MS-SSIM loss function, which guides the network to produce more structurally consistent and visually pleasing results. This loss function helps preserve important features and details during the inpainting process.

![Architecture](https://github.com/ShashankA2004/Image-Inpainting-on-Archaeological-Sites-using-GANs/blob/main/methodology.jpg?raw=true)


## Experimental Setup
To evaluate the effectiveness of our approach, we conducted experiments using datasets from archaeological sites. These datasets consist of photographs with missing or damaged areas caused by the passage of time or excavation procedures. We compare the results of our approach with the baseline UNet model in terms of the Structural Similarity Index (SSIM) score.

## Results
Our experimental results demonstrate that the proposed approach achieves strong inpainting performance on archaeological images. We obtained an SSIM score of 0.92 and a PSNR of 28.42, indicating high structural similarity and good signal-to-noise ratio in the restored images. 

<p align="center">
  <img src="https://github.com/ShashankA2004/Image-Inpainting-on-Archaeological-Sites-using-GANs/blob/main/results.jpg?raw=true" alt="Results Image" width="600"/>
</p>

## Conclusion
The suggested approach provides a valuable tool for academics and archaeologists working with archaeological data. By enhancing the picture restoration and analysis capabilities, our method enables researchers to effectively reconstruct damaged or missing portions of images, thereby improving the understanding and interpretation of archaeological datasets. Furthermore, by integrating the model into mobile applications, we aim to empower users to examine and restore their own archaeological images conveniently.

## Acknowledgments
We would like to thank the archaeological community and my university.Their contribution has been instrumental in the development and evaluation of the proposed approach.
