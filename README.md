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
    - [Stable Diffusion Web UI Plugin](#stable-diffusion-web-ui-plugin)
    - [DeOldify Image Colorization on DeepAI](#deoldify-image-colorization-on-deepai)
    - [MyHeritage In Color](#myheritage-in-color)
    - [Google Colab](#google-colab)
    - [DeOldify.NET](#deoldifynet)
  - [Adobe Photoshop](#adobe-photoshop--Link)
  - [BigColor](#bigcolor--repo--download-pre-trained-models)
- [Extra](#extra)
- [License](#license)

## Introduction
I tested 11 different `Github repo implementations`/`models`/`implementations`/`software` of AI Colorization.

**If you only want to see the results visit:** [results.md](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/results.md)

note: the results I present are not definitive, you could perhaps get better results with tweaking the implementation's settings/prompts/parameters etc as well as using the manual methods where available.

I tested the following:

 - https://github.com/piddnad/DDColor - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#ddcolor--repo--model-zoo)
 - https://openmodeldb.info/models/1x-BS-Colorizer - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#bs_colorizervapourizer--model)
 - https://openmodeldb.info/models/1x-SpongeColor-Lite - [Jump to the results](https://github.com/Courage-1984/ai-image-colorization-results?tab=readme-ov-file#spongecolor-lite--model)
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

Model description:
> B/W | 100% Desaturated images. It mostly results in Blue and Yellow images with slight hints of Green, Orange and Magenta. You are free to use this as a pretrain to achieve better results.

| Original  | BS_Colorizer/Vapourizer |
| ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![BS_Colorizer/Vapourizer](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BS_Colorizer%20-%20Vapourizer/1_1x_ColorizerV2_22000G.png) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![BS_Colorizer/Vapourizer](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BS_Colorizer%20-%20Vapourizer/2_1x_ColorizerV2_22000G.png) |

## SpongeColor Lite | [Model](https://openmodeldb.info/models/1x-SpongeColor-Lite)

Model description:
> The first attempt at ESRGAN colorization that produces more than 2 colors. Doesn't work that great but it was a neat experiment.

| Original  | SpongeColor Lite |
| ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![SpongeColor Lite](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/SpongeColor%20Lite/1_1x-SpongeColor-Lite.png) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![SpongeColor Lite](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/SpongeColor%20Lite/2_1x-SpongeColor-Lite.png) |

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

I have tested the following 5 methods:

1. [Stable Diffusion Web UI Plugin](https://github.com/SpenserCai/sd-webui-deoldify)
2. [DeOldify Image Colorization on DeepAI](https://deepai.org/machine-learning-model/colorizer)
3. [MyHeritage In Color](https://www.myheritage.com/incolor)
4. [Google Colab - Stable](https://colab.research.google.com/github/jantic/DeOldify/blob/master/ImageColorizerColabStable.ipynb) | [Google Colab - Artistic](https://colab.research.google.com/github/jantic/DeOldify/blob/master/ImageColorizerColab.ipynb)
5. [DeOldify.NET](https://github.com/ColorfulSoft/DeOldify.NET)

Here is the descriptions of the 5 methods provided by the repo:

1. **Stable Diffusion Web UI Plugin:** Stable Diffusion Web UI Plugin- Photos and video, cross-platform (NEW!).
2. **DeOldify Image Colorization on DeepAI:** Quick Start: The easiest way to colorize images using open source DeOldify (for free!).
3. **MyHeritage In Color:** The most advanced version of DeOldify image colorization is available here, exclusively. Try a few images for free! 
4. **Google Colab - Stable & Artistic:** *no real description provided.*
5. **DeOldify.NET:** ColorfulSoft Windows GUI- Photos/Windows only (No GPU required!).

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


### Google Colab:

Easy to run in your browser, just have to provide a link (`source_url`) to your image before initiating Runtime. Additionally what is nice is this colab also produces multiple outputs generated with different `render_factor` values (10>38, incrementing by 2).

I am only providing the result generated with `render_factor` of `35`. All the results can be seen here: [Google Colab - Stable](https://slow.pics/c/oQ2kYs3P?canvas-mode=fit-height&image-fit=contain) & [Google Colab - Artistic](https://slow.pics/c/OiJ1GVkv?canvas-mode=fit-height&image-fit=contain).

| Original  | Stable 35 | Artistic 35 |
| ------------- | ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![Stable 35](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/Google%20Colab/1-Stable%20Colorizer/1-Stable%20Colorizer-35.png) | ![Artistic 35](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/Google%20Colab/1-Artistic%20Colorizer/1-Artistic%20Colorizer-35.png) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![Stable 35](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/Google%20Colab/2-Stable%20Colorizer/2-Stable%20Colorizer-35.png) | ![Artistic 35](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/Google%20Colab/2-Artistic%20Colorizer/2-Artistic%20Colorizer-35.png) |


### DeOldify.NET:

You run scripts to create `.exe` files which each uses different models. The `.exe` then gives you a nice GUI to select input image, 'DeOldify' and save output image.

Here I only provide the results of the `.exe` using `Artistic colorizer with float32 weights` and `Stable colorizer with float32 weights` as the results from the different models are quite similar. All the results can be seen here: [Stable](https://slow.pics/c/vkDJTEpI?canvas-mode=fit-height&image-fit=contain) & [Artistic](https://slow.pics/c/7BU2GHpj?canvas-mode=fit-height&image-fit=contain).

| Original  | Stable float32 | Artistic float32 |
| ------------- | ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![Stable float32](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/DeOldify.NET/Stable/1-DeOldify.NET.stable_float32.windows.png) | ![Artistic float32](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/DeOldify.NET/Artistic/1-DeOldify.NET.artistic_float32.windows.png) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![Stable float32](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/DeOldify.NET/Stable/2-DeOldify.NET.stable_float32.windows.png) | ![Artistic float32](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/DeOldify/DeOldify.NET/Artistic/2-DeOldify.NET.artistic_float32.windows.png) |

---

# Adobe Photoshop | [Link](https://www.adobe.com/products/photoshop.html)

Using the `Colorize` `Neural Filters` from Adobe Photoshop you can get quite good results. The results I present is the default automatic colorization but you can adjust and edit the results manually to your liking.

| Original  | Adobe Photoshop Neural Filters - Colorize |
| ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![Adobe Photoshop_Neural Filters_Colorize](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/Adobe%20Photoshop/1_Adobe%20Photoshop_Neural%20Filters_Colorize.png) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![Adobe Photoshop_Neural Filters_Colorize](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/Adobe%20Photoshop/2_Adobe%20Photoshop_Neural%20Filters_Colorize.png) |

---

# BigColor | [Repo](https://github.com/KIMGEONUNG/BigColor) | [Download Pre-trained Models](https://drive.google.com/drive/folders/1nLzgE5WJnxp5WF1dkpa1ts6bZ6tVwtep)

BigColor is a bit of a *step-up* from other implementations as it uses the models presented at *ECCV 2022*.

It also provides 4 scripts with the following descriptions:

**infer.bigcolor.e011.sh :** **ImageNet1K Validation :** Use this to get the same inference results as used in the paper.
**colorize.real.sh :** **Real Gray Colorization :** Use this to colorize a real grayscale image with arbitrary resolution.
**colorize.multi_c.sh :** **Multi-modal Solutions :** Use this to test the multiple solutions from a input (*using class vector c*).
**colorize.multi_z.sh :** **Multi-modal Solutions :** Use this to test the multiple solutions from a input (*using random vector z*).

BigColor also uses 'Wordnet' class classification to generate the output image which can be modified to your liking. **infer.bigcolor.e011.sh** uses a hard-coded class, **colorize.real.sh** actually determines the content of the image and then uses appropriate classes, **colorize.multi_c.sh** uses a set of random hard-coded classes and **colorize.multi_z.sh** uses a single hard-coded class.

^ These scripts are setup to use datasets already provided by the repo but I modified the implementation to use my own 2 B&W images. If you can grasp how these scripts work then you could perhaps modify the logic and perhaps get better results than what I got.

**You can check the file names of the [BigColor results](https://github.com/Courage-1984/ai-image-colorization-results/tree/main/Colorization_tests/Results/BigColor) in this repo to see the parameters/arguments and classes used to generate them.**

### BigColor Results:

### infer.bigcolor.e011.sh:

| Original  | infer.bigcolor.e011.sh |
| ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![infer.bigcolor.e011.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_bigcolor/1_class0-tench-n01440764_size3577_resizepowerof_power4_target256_lab_upscale_epoch11.jpg) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![infer.bigcolor.e011.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_bigcolor/2_class0-tench-n01440764_size621_resizepowerof_power4_target256_lab_upscale_epoch11.jpg) |

### colorize.real.sh:

| Original  | colorize.real.sh |
| ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![colorize.real.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_real/1_topk5_size3577_resizepowerof_power4_target256_modeltf_efficientnet_l2_ns_475.jpg.jpg) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![colorize.real.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_real/2_topk5_size621_resizepowerof_power4_target256_modeltf_efficientnet_l2_ns_475.jpg.jpg) |

### colorize.multi_c.sh:

| Original  | colorize.multi_c.sh |
| ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![colorize.multi_c.sh 1](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/1_class100-black_swan-n01860187_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh 2](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/1_class11-goldfinch-n01531178_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh 3](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/1_class14-indigo_bunting-n01537544_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh 4](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/1_class15-robin-n01558993_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh 5](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/1_class88-macaw-n01818515_scale1.0_bias0.0.jpg) |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![colorize.multi_c.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/2_class100-black_swan-n01860187_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/2_class11-goldfinch-n01531178_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/2_class14-indigo_bunting-n01537544_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/2_class15-robin-n01558993_scale1.0_bias0.0.jpg) | ![colorize.multi_c.sh](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/BigColor/results_multi_c/2_class88-macaw-n01818515_scale1.0_bias0.0.jpg) |

### script:

| Original  | script |
| ------------- | ------------- |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png) | ![script]() |
![Original](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png) | ![script]() |



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
