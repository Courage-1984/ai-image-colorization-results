# AI Image Colorization results

This repository contains the results of various AI Colorization methods/models tested by me.

I tested 7 different Github repo implementations of AI Colorization.

**If you only want to see the results visit:** https://github.com/Courage-1984/ai-image-colorization-results/blob/main/results.md

note: the results I present are not definitive, you could perhaps get better results with tweaking etc.

I tested the following repos:

 - https://github.com/piddnad/DDColor
 - https://github.com/pmh9960/iColoriT
 - https://github.com/nick8592/text-guided-image-colorization
 - https://github.com/jantic/DeOldify
 - https://github.com/Wazzabeee/image-video-colorization
 - https://github.com/richzhang/colorization
 - https://github.com/junyanz/interactive-deep-colorization

 # Results

 # DDColor | [Repo](https://github.com/piddnad/DDColor) | [Model Zoo](https://github.com/piddnad/DDColor/blob/master/MODEL_ZOO.md)

DDColor offers 4 models (`modelscope`, `artistic`, `paper` & `paper_tiny`), of which I used 3.

I ran them using [chaiNNer](https://github.com/chaiNNer-org/chaiNNer) and I was quite pleased with the **Modelscope** results.
 

| Original  | Modelscope | Artistic | Paper |
| ------------- | ------------- | ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![Modelscope](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/1%20(2)_ddcolor_modelscope.png) | ![Artistic](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/1%20(2)_ddcolor_artistic.png)  | ![Paper](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/1%20(2)_ddcolor_paper.png)
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![Modelscope](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/2_ddcolor_modelscope.png) | ![Artistic](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/2_ddcolor_artistic.png)  | ![Paper](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/2_ddcolor_paper.png)

---

 # iColoriT | [Repo](https://github.com/pmh9960/iColoriT) | [Pretrained iColoriT Checkpoints](https://github.com/pmh9960/iColoriT?tab=readme-ov-file#pretrained-icolorit)

iColoriT offers 3 models (`Base Model (ViT-B)`, `Small Model (ViT-S)` & `Tiny Model (ViT-Ti)`).

I ran iColoriT two different ways:

1. The first was where I used all 3 models and had it *auto* colour the image for me.
2. The second I used the GUI and manually tried my best to colour it in with the hints it provided. I only used the `small` model for this method.

Only issue I found that with the iColoriT, how it's set up, the resulting image you save is not at the full resolution of the original image which is not ideal. You will have to edit the scripts to get the resulting image at full resolution.

## First Method:

| Original  | Base Model (ViT-B) | Small Model (ViT-S) | Tiny Model (ViT-Ti) |
| ------------- | ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="548" /> | ![Base Model (ViT-B)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Base%20Model%20(ViT-B).png) | ![Small Model (ViT-S)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Small%20Model%20(ViT-S).png)  | ![Tiny Model (ViT-Ti)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Tiny%20Model%20(ViT-Ti).png) 
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="548" /> | ![Base Model (ViT-B)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Base%20Model%20(ViT-B).png) | ![Small Model (ViT-S)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Small%20Model%20(ViT-S).png)  | ![Tiny Model (ViT-Ti)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Tiny%20Model%20(ViT-Ti).png)

## Second Method:

| Original  | Small Model (ViT-S) |
| ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="548" /> | ![Modelscope](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT2/1%20Small%20Model%20(ViT-S).png) |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="548" /> | ![Modelscope](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT2/2%20Small%20Model%20(ViT-S).png) |

---

 # Text-Guided-Image-Colorization | [Repo](https://github.com/nick8592/text-guided-image-colorization) | [Download Pre-trained Models](https://github.com/nick8592/text-guided-image-colorization?tab=readme-ov-file#installation)

Text-Guided-Image-Colorization uses a `ControlNet Model`, `Image Captioning Model`, `base model` & `Checkpoint`. Most are sdxl models.

I ran it with the default settings (1st method) as well as alt settings (2nd method) to the default. I also used chatgpt to create prompts for me for the images (I'm not too good at that), so you could perhaps get better results than me with better prompts.

**Here were my settings:**

### 1st method:

```
Select ControlNet Model: sdxl_light_caption_output/checkpoint-30000/controlnet
Select Image Captioning Model: blip-image-captioning-large
positive prompt: chatgpt
negative: low quality, bad quality, low contrast, black and white, bw, monochrome, grainy, blurry, historical, restored, desaturate
seed: 123
Steps: 8
fp16
base model: stabilityai/stable-diffusion-xl-base-1.0
Repository: ByteDance/SDXL-Lightning
Checkpoint: sdxl_lightning_8step_unet.safetensors
```

### 2nd method:

```
Select ControlNet Model: sdxl_light_custom_caption_output/checkpoint-30000/controlnet
Select Image Captioning Model: blip-image-captioning-base
positive prompt: chatgpt
negative: low quality, bad quality, low contrast, black and white, bw, monochrome, grainy, blurry, historical, restored, desaturate
seed: 123
Steps: 8
fp16
base model: stabilityai/stable-diffusion-xl-base-1.0
Repository: ByteDance/SDXL-Lightning
Checkpoint: sdxl_lightning_8step_unet.safetensors
```

**Here were my prompts:**

### 1st image prompt:

```
A black-and-white vintage wedding portrait of a couple. The groom is wearing a black suit, white shirt, and a black tie, with a white flower boutonniere on his left lapel. He has short dark hair and glasses. The bride is dressed in an ornate white wedding gown with lace detailing and long sleeves. She wears a white floral crown over her dark hair styled in a voluminous updo, with a sheer white veil cascading behind her. She holds a bouquet of white and light-colored flowers with trailing stems. The background is plain and neutral.
```


### 2nd image prompt:

```
A black-and-white photo of an older couple standing in front of a classic Volkswagen Beetle car. The man on the right is wearing glasses, a light-colored short-sleeved shirt, dark trousers, and dark shoes. He has a beard and is smiling. The woman on the left is wearing a light blouse, light-colored pants, and white slip-on shoes. She holds a small purse over her left arm and stands close to the man with her hand on his shoulder. The background features a suburban setting with brick houses, tiled roofs, and a driveway. The car has a light exterior and visible striped upholstery inside.
```

### Results

| Original  | 1st Method | 2nd Method |
| ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/text-guided-image-colorization/1%201st.jpeg" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/text-guided-image-colorization/1%202nd.jpeg" width="621" /> |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![1st Method](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/text-guided-image-colorization/2%201st.jpeg) | ![2nd Method](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/text-guided-image-colorization/2%202nd.jpeg)  |

---

### The following 3 implementations all use methods and models presented at *ECCV* and *SIGGRAPH*


 # Colorful Image Colorization | [Repo](https://github.com/richzhang/colorization)

This implementation does the colorization automatically through a demo script and then presents/saves for you a *ECCV* and *SIGGRAPH* colorized version of your input image.

| Original  | ECCV | SIGGRAPH |
| ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/colorization/1_eccv16.png" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/colorization/1_siggraph17.png" width="621" /> |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![ECCV](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/colorization/2_eccv16.png) | ![SIGGRAPH](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/colorization/2_siggraph17.png)  |

---















 # Colorful Image Colorization | [Repo]()

Description Here














 # Colorful Image Colorization | [Repo]()

Description Here





----



<img src="" width="548" />


<img src="" width="621" />



## Second Method:

| Original  | Small Model (ViT-S) |
| ------------- | ------------- |
![Original]() | ![Modelscope]() |
![Original]() | ![Modelscope]() |




| Original  | ECCV | SIGGRAPH |
| ------------- | ------------- | ------------- |
<img src="" width="621" /> | <img src="" width="621" /> | <img src="" width="621" /> |
![Original]() | ![ECCV]() | ![SIGGRAPH]()  |





| Original  | Modelscope | Artistic | Paper |
| ------------- | ------------- | ------------- | ------------- |
![Original]() | ![Modelscope]() | ![Artistic]()  | ![Paper]()
![Original]() | ![Modelscope]() | ![Artistic]()  | ![Paper]()














