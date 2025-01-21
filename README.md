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

 


| Codec  | H264 | HEVC | AV1 |
| ------------- | ------------- | ------------- | ------------- |
| NVENC | ![image](Colorization_tests/Results/DDColor/1 (2)_ddcolor_artistic.png) | ![NVENC 5000 HEVC](https://user-images.githubusercontent.com/62084776/214811174-ee5b74d8-d2b7-452c-bb1d-4639e3caaf35.png) | ![NVENC AV1 5000 (This result is newer than the others)](https://user-images.githubusercontent.com/62084776/214814427-30998c97-f1b8-46eb-8d6d-9a641e577c02.png)
| QuickSync | ![Intel 5000 H264](https://user-images.githubusercontent.com/62084776/214811330-636fafb9-c26e-4fff-ab1b-d433f281bf34.png) | ![Intel 5000 HEVC](https://user-images.githubusercontent.com/62084776/214811303-ed0a5f7c-5dff-42b2-b6d0-f64197fb4f80.png) | ![Intel 5000 AV1](https://user-images.githubusercontent.com/62084776/214811266-d9be2cef-332f-461d-9829-e11edfc52d28.png)
| CPU | ![CPU 5000 H264](https://user-images.githubusercontent.com/62084776/214811364-56dabe72-e9b0-4511-9781-934c8e0fb890.png) | ![CPU 5000 HEVC](https://user-images.githubusercontent.com/62084776/214811396-f5fc4a33-08d0-4186-864e-23d25ff8e792.png) | ![SVT-AV1 5000](https://user-images.githubusercontent.com/62084776/214811438-f0f01aa0-cf86-4f21-970c-38975e57a7e9.png)
| AMD | ![AMF H264 5000](https://user-images.githubusercontent.com/62084776/215026472-6aadb941-6ec3-4097-b96d-af3338f6db07.png) | ![AMF HEVC 5000](https://user-images.githubusercontent.com/62084776/215026483-215e7d54-f487-497e-915e-6412ab5cd7fc.png) | |

