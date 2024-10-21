<h2 align="center"> <a href="https://github.com/nazmul-karim170/SAVE-Text2Video-Diffusion">
SAVE: Spectral-Shift-Aware Adaptation of Image Diffusion Models for Text-guided Video Editing</a></h2>
<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub for the latest update.  </h2>

<h5 align="center">

[![webpage](https://img.shields.io/badge/Webpage-blue)](https://free-editor.github.io/)
[![arXiv](https://img.shields.io/badge/Arxiv-2312.09313-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2312.13663)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/nazmul-karim170/SAVE-Text2Video-Diffusion/blob/main/LICENSE) 


</h5>

## [Project page](https://free-editor.github.io/) | [Paper](https://arxiv.org/abs/2312.13663) 


<img src="asset/Results.png"/>

## 😮 Highlights

SAVE allows you to edit your video in a matter of **3 minutes!** instead of **30 minutes!** in SOTA. 

### 💡 Efficient, High-quality, and Fast-speed
- Stable Diffusion (SD) for image generation   -->   high-quality
- Only fine-tune the Singular Values of the Query Matrices  --> Efficient Adaptation
- Regularize the singular value updates 


## 🚩 **Updates**

Welcome to **watch** 👀 this repository for the latest updates.

✅ **[2024.06.07]** : We have released our code

✅ **[2023.12.01]** : We have released our paper, SAVE on [arXiv](https://arxiv.org/abs/2305.18670).

✅ **[2023.12.01]** : Release [project page](https://save-textguidedvideoediting.github.io/).


## 🛠️ Methodology

<img src="asset/Main.png"/>

### Implementation of SAVE Algorithm.

First, create a conda environment using this
	
 	conda create -n save

First Install the following packages-
	
	pip install -r requirements.txt
	
Run the following command to edit a given video. 
	
	python Edit_Video_SAVE.py
	
Change the "--config" option in arguments to provide a new video.

## 🚀 Video-Editing Results

### Qualitative comparison

<img src="asset/Compare.png"/>

### Quantitative comparison

<img src="asset/quant_S.png"/>

## 👍 **Acknowledgement**
This work is built on many amazing research works and open-source projects, thanks a lot to all the authors for sharing!
* [Tune-A-Video](https://github.com/showlab/Tune-A-Video)
* [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
* [Diffusers](https://github.com/huggingface/diffusers)

## ✏️ Citation
If you find our paper and code useful in your research, please consider giving a star :star: and a citation :pencil:.

```BibTeX
@misc{karim2023save,
      title={SAVE: Spectral-Shift-Aware Adaptation of Image Diffusion Models for Text-driven Video Editing}, 
      author={Nazmul Karim and Umar Khalid and Mohsen Joneidi and Chen Chen and Nazanin Rahnavard},
      year={2023},
      eprint={2305.18670},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
<!---->
