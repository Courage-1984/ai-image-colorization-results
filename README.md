# AI Image Colorization results

This repository contains the results of various AI Colorization methods/models tested by me.

I tested 7 different Github repo implementations of AI Colorization.

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




 # iColoriT | [Repo](https://github.com/pmh9960/iColoriT) | [Pretrained iColoriT Checkpoints](https://github.com/pmh9960/iColoriT?tab=readme-ov-file#pretrained-icolorit)

iColoriT offers 3 models (`Base Model (ViT-B)`, `Small Model (ViT-S)` & `Tiny Model (ViT-Ti)`).

I ran iColoriT two different ways:

1. The first was where I used all 3 models and had it *auto* colour the image for me.
2. The second I used the GUI and manually tried my best to colour it in with the hints it provided. I only used the `small` model for this method.

Only issue I found that with the iColoriT, how it's set up, the resulting image you save is not at the full resolution of the original image which is not ideal. You will have to edit the scripts to get the resulting image at full resolution.

| Original  | Base Model (ViT-B) | Small Model (ViT-S) | Tiny Model (ViT-Ti) |
| ------------- | ------------- | ------------- | ------------- |
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/1.png" width="548" /> | ![Base Model (ViT-B)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Base%20Model%20(ViT-B).png) | ![Small Model (ViT-S)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Small%20Model%20(ViT-S).png)  | ![Tiny Model (ViT-Ti)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/1%20Tiny%20Model%20(ViT-Ti).png) 
<img src="https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/bw_images/2.png" width="548" /> | ![Base Model (ViT-B)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Base%20Model%20(ViT-B).png) | ![Small Model (ViT-S)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Small%20Model%20(ViT-S).png)  | ![Tiny Model (ViT-Ti)](https://github.com/Courage-1984/ai-image-colorization-results/blob/main/Colorization_tests/Results/iColoriT/iColoriT1/2%20Tiny%20Model%20(ViT-Ti).png)



----



| Original  | Modelscope | Artistic | Paper |
| ------------- | ------------- | ------------- | ------------- |
![Original]() | ![Modelscope]() | ![Artistic]()  | ![Paper]()
![Original]() | ![Modelscope]() | ![Artistic]()  | ![Paper]()














