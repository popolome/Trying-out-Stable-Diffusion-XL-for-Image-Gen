# Trying-out-Stable-Diffusion-XL-for-Image-Gen
Trying the SDXL for generating image from text prompt

Below are the images I have generated (for full code please see the python code file at https://github.com/popolome/Trying-out-Stable-Diffusion-XL-for-Image-Gen/blob/main/Trying_out_Stable_Diffusion_XL_for_Image_Gen.ipynb):

<br>

**Realistic Korean Woman**

| Version 1 | Version 2 | Version 3 Cropped | Version 4 | Version 5 |
| :---: | :---: | :---: | :---: | :---: |
| ![Woman 1](Photo%20Outputs/realistic_cute_woman_1.png) | ![Woman 2](Photo%20Outputs/realistic_cute_woman_2.png) | ![Woman 3 Cropped](Photo%20Outputs/realistic_cute_woman_3.png) | ![Woman 4](Photo%20Outputs/realistic_cute_woman_4.png) | ![Woman 5](Photo%20Outputs/realistic_cute_woman_5.png) |

<br>

**Realistic Samurai Man**

| Version 1 | Version 2 | Version 3 Cropped | Version 4 | Version 5 | Version 6 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| ![Samurai 1](Photo%20Outputs/realistic_samurai_man_1.png) | ![Samurai 2](Photo%20Outputs/realistic_samurai_man_2.png) | ![Samurai 3 Cropped](Photo%20Outputs/realistic_samurai_man_3.png) | ![Samurai 4](Photo%20Outputs/realistic_samurai_man_4.png) | ![Samurai 5](Photo%20Outputs/realistic_samurai_man_5.png) | ![Samurai 6](Photo%20Outputs/realistic_samurai_man_6.png) |

<br>

**Anime**

| Version 1 Cat | Version 2 Totoro on Car|
| :---: | :---: |
| ![Fat Anime Cat](Photo%20Outputs/Fat_Cat_Anime.png) | ![Totoro](Photo%20Outputs/Totoro.png) |

<br>

**Notes from Me**
Honestly, it's a fun small learning journey, I did encountered several errors before being able to make it to the fine-tuning stage of the image.
1) Using the default VAE from stable diffusion caused mismatch of FP32 and FP16.
2) Switched to madebyollin/sdxl-vae-fp16-fix and make everything FP16, loads so much faster.
3) This requires more than 16gb RAM and 24/32 GPU VRAM.
4) This requires PyTorch, not TensorFlow.
5) I do not recommend building stable diffusion model from scratch in industry, use pre-trained models instead.
6) Learnt to keep generating different images with either another prompt or the same.

<br>

This is just a project for my portfolio and learning to be a Data Scientist.
That's all from me.

<br>

Yours Truly,
<br>
**Jun Kit Mak**
