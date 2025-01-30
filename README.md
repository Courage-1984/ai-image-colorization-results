# AI Image Colorization Results

This repository contains the results of various AI Colorization methods/models tested by me.

## Table of Contents
- [Introduction](#introduction)
- [Results](#results)
  - [DDColor](#ddcolor--repo--model-zoo)
  - [Other Open Models (old)](#other-open-models-old)
    - [BS_Colorizer/Vapourizer](#bs_colorizervapourizer--model)
    - [SpongeColor Lite](#spongecolor-lite--model)
  - [iColoriT](#icolorit--repo--pretrained-icolorit-checkpoints)
  - [Text-Guided-Image-Colorization](#text-guided-image-colorization--repo--download-pre-trained-models)
  - [Colorful Image Colorization](#colorful-image-colorization--repo)
  - [Image Video Colorization](#image-video-colorization--repo)
  - [Interactive Deep Colorization](#interactive-deep-colorization--repo)
  - [DeOldify](#deoldify--repo--pretrained-weights)
- [Extra](#extra)
- [License](#license)

## Introduction
I tested 11 different `Github repo implementations`/`models`/`implementations`/`software` of AI Colorization.

**If you only want to see the results visit:** [results.md](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/results.md)

note: the results I present are not definitive, you could perhaps get better results with tweaking the implementation's settings/prompts/parameters etc as well as using the manual methods where available.

I tested the following:

 - https://github.com/piddnad/DDColor - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#ddcolor--repo--model-zoo)
 - https://github.com/pmh9960/iColoriT - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#icolorit--repo--pretrained-icolorit-checkpoints)
 - https://github.com/nick8592/text-guided-image-colorization - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#text-guided-image-colorization--repo--download-pre-trained-models)
 - https://github.com/richzhang/colorization - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#colorful-image-colorization--repo)
 - https://github.com/Wazzabeee/image-video-colorization - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#colorful-image-colorization--repo)
 - https://github.com/junyanz/interactive-deep-colorization - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#interactive-deep-colorization--repo)
 - https://github.com/jantic/DeOldify - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#deoldify--repo--pretrained-weights)


# Results

# DDColor | [Repo](https://github.com/piddnad/DDColor) | [Model Zoo](https://github.com/piddnad/DDColor/blob/master/MODEL_ZOO.md)

DDColor offers 4 models (`modelscope`, `artistic`, `paper` & `paper_tiny`), of which I used 3.

I ran them using [chaiNNer](https://github.com/chaiNNer-org/chaiNNer) and I was quite pleased with the **Modelscope** results.


| Original  | Modelscope | Artistic | Paper |
| ------------- | ------------- | ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![Modelscope](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/1%20(2)_ddcolor_modelscope.png) | ![Artistic](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/1%20(2)_ddcolor_artistic.png)  | ![Paper](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/1%20(2)_ddcolor_paper.png)
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![Modelscope](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/2_ddcolor_modelscope.png) | ![Artistic](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/2_ddcolor_artistic.png)  | ![Paper](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DDColor/2_ddcolor_paper.png)

---

# Other Open Models (old)

These models are very old and don't produce very good results but I thought I would include them for completeness.

I ran them using [chaiNNer](https://github.com/chaiNNer-org/chaiNNer).

## BS_Colorizer/Vapourizer | [Model](https://openmodeldb.info/models/1x-BS-Colorizer)

| Original  | BS_Colorizer/Vapourizer |
| ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="621" /> | ![BS_Colorizer/Vapourizer](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BS_Colorizer%20-%20Vapourizer/1_1x_ColorizerV2_22000G.png) |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="621" /> | ![BS_Colorizer/Vapourizer](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BS_Colorizer%20-%20Vapourizer/2_1x_ColorizerV2_22000G.png) |

## SpongeColor Lite | [Model](https://openmodeldb.info/models/1x-SpongeColor-Lite)

| Original  | SpongeColor Lite |
| ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="621" /> | ![SpongeColor Lite](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/SpongeColor%20Lite/1_1x-SpongeColor-Lite.png) |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="621" /> | ![SpongeColor Lite](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/SpongeColor%20Lite/2_1x-SpongeColor-Lite.png) |

---

# iColoriT | [Repo](https://github.com/pmh9960/iColoriT) | [Pretrained iColoriT Checkpoints](https://github.com/pmh9960/iColoriT?tab=readme-ov-file#pretrained-icolorit)

iColoriT offers 3 models (`Base Model (ViT-B)`, `Small Model (ViT-S)` & `Tiny Model (ViT-Ti)`).

I ran iColoriT two different ways:

1. The first was where I used all 3 models and had it *auto* colour the image for me.
2. The second I used the GUI and manually tried my best to colour it in with the hints it provided. I only used the `small` model for this method.

Only issue I found that with the iColoriT, how it's set up, the resulting image you save is not at the full resolution of the original image which is not ideal. You will have to edit the scripts to get the resulting image at full resolution.

### First Method:

| Original  | Base Model (ViT-B) | Small Model (ViT-S) | Tiny Model (ViT-Ti) |
| ------------- | ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="548" /> | ![Base Model (ViT-B)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Base%20Model%20(ViT-B).png) | ![Small Model (ViT-S)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Small%20Model%20(ViT-S).png)  | ![Tiny Model (ViT-Ti)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Tiny%20Model%20(ViT-Ti).png) 
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="548" /> | ![Base Model (ViT-B)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Base%20Model%20(ViT-B).png) | ![Small Model (ViT-S)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Small%20Model%20(ViT-S).png)  | ![Tiny Model (ViT-Ti)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Tiny%20Model%20(ViT-Ti).png)

### Second Method:

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

### Text-Guided-Image-Colorization Results:

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

# Image Video Colorization | [Repo](https://github.com/Wazzabeee/image-video-colorization)

This implementation is a bit more user friendly then the previous one has it offers a GUI. It also offers extra functionality where you can colorize input videos and YouTube links/videos along with the option of colorizing images.

The image colorization results is the same as the previous implementation. I did not test videos.

| Original  | ECCV | SIGGRAPH |
| ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/image-video-colorization/1%20ECCV16.jpg" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/image-video-colorization/1%20SIGGRAPH17.jpg" width="621" /> |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![ECCV](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/image-video-colorization/2%20ECCV16.jpg) | ![SIGGRAPH](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/image-video-colorization/2%20SIGGRAPH17.jpg)  |

---

# Interactive Deep Colorization | [Repo](https://github.com/junyanz/interactive-deep-colorization)

This implementation also provides a GUI. It initially does an auto colorization of your input image but then you can also manually colorize your input image. What is nice when you manually colorize your input image is that it provides you with colour hints and a color gamut which both are this implementation's estimation of what it thinks the colour should be at the point which you selected on the input image.

This implementation uses model from *SIGGRAPH*.

| Original  | Auto | Manual |
| ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/interactive-deep-colorization/1%20auto.png" width="621" /> | <img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/interactive-deep-colorization/1%20manual.png" width="621" /> |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![Auto](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/interactive-deep-colorization/2%20auto.png) | ![Manual](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/interactive-deep-colorization/2%20manual.png)  |

---

# DeOldify | [Repo](https://github.com/jantic/DeOldify) | [Pretrained Weights](https://github.com/jantic/DeOldify?tab=readme-ov-file#pretrained-weights)

This implementation can be used from a couple of places, each producing different results.

I have tested the following 3 methods:

1. [Stable Diffusion Web UI Plugin](https://github.com/SpenserCai/sd-webui-deoldify)
2. [DeOldify Image Colorization on DeepAI](https://deepai.org/machine-learning-model/colorizer)
3. [MyHeritage In Color](https://www.myheritage.com/incolor)

Here is the descriptions of the 3 methods provided by the repo:

1. **Stable Diffusion Web UI Plugin:** Stable Diffusion Web UI Plugin- Photos and video, cross-platform (NEW!).
2. **DeOldify Image Colorization on DeepAI:** Quick Start: The easiest way to colorize images using open source DeOldify (for free!)
3. **MyHeritage In Color:** The most advanced version of DeOldify image colorization is available here, exclusively. Try a few images for free! 

### DeOldify Results:


### Stable Diffusion Web UI Plugin:

For this method there is 4 results as I used all the various possible combinations of the settings of this plugin.

The **DeOldify Stable Diffusion Web UI Plugin Settings** were as follows:

```
1st combination: "render_factor=42, artistic=False, pre_decolorization=False"
2nd combination: "render_factor=42, artistic=False, pre_decolorization=True"
3rd combination: "render_factor=42, artistic=True, pre_decolorization=False"
4th combination: "render_factor=42, artistic=True, pre_decolorization=True"
```

| Original  | 1st combination | 2nd combination | 3rd combination | 4th combination |
| ------------- | ------------- | ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="934" /> | ![1st combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/1%201st.png) | ![2nd combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/1%202nd.png)  | ![3rd combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/1%203rd.png) | ![4th combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/1%204th.png)
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="934" /> | ![1st combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/2%201st.png) | ![2nd combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/2%202nd.png)  | ![3rd combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/2%203rd.png) | ![4th combination](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/sd-webui-deoldify/2%204th.png)


### DeOldify Image Colorization on DeepAI:

Unfortunately this doesn't give your image back at full resolution.

| Original  | Colorized Result |
| ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="554" /> | ![Colorized Result](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/deepai/1.jpg) |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="554" /> | ![Colorized Result](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/deepai/2.jpg) |


### MyHeritage In Color:

Unfortunately this doesn't give your image back at full resolution.

| Original  | Colorized Result |
| ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="894" /> | ![Colorized Result](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/myheritage/1.jpg) |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="894" /> | ![Colorized Result](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/myheritage/2.jpg) |


---

### Hope you found this useful!

---

## Extra

Here is another nice [Colorization Showcase](https://phhofm.github.io/upscale/colorization.html)

---

## License

**Creative Commons Attribution Share Alike 4.0 International (CC-BY-SA-4.0)**

[AI Image Colorization Results](https://github.com/Courage-1984/ai-image-colorization-results) © 2025 by [Courage (Courage-1984)](https://github.com/Courage-1984) is licensed under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1)  <img width="20" height="20" src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/cc.png">   <img width="20" height="20" src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/cc-by.png">   <img width="20" height="20" src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/cc-sa.png"> 

---
