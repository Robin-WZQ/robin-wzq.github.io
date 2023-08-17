---
title: "CCLAP: Controllable Chinese Landscape Painting Generation via Latent Diffusion Model"
collection: publications
permalink: /publication/CCLAP
venue: 'ICME (oral)'
date: 2023
citation: '**Zhongqi Wang**, Jie Zhang, Zhilong Ji, Jinfeng Bai, Shiguang Shan. \n Conference on International Conference on Multimedia and Expo (ICME), oral, 2023'
---

[CCLAP](http://Robin-WZQ.github.io/files/CCLAP.pdf)

<a src="https://img.shields.io/badge/cs.CV-2304.04156-b31b1b?logo=arxiv&logoColor=red" href="https://arxiv.org/abs/2304.04156"> <img src="https://img.shields.io/badge/cs.CV-2304.04156-b31b1b?logo=arxiv&logoColor=red">
</a>
<a href="https://huggingface.co/spaces/RobinWZQ/CCLAP"><img src="https://huggingface.co/datasets/huggingface/badges/raw/main/open-in-hf-spaces-sm-dark.svg" alt="Open in Spaces"> </a>

**Conference Accepted:** ICME 2023 (oral)

**Project page:** [Github](https://github.com/Robin-WZQ/CCLAP)

## 👀 Abstract

With the development of deep generative models, recent years have seen great success of Chinese landscape painting generation. However, few works focus on controllable Chinese landscape painting generation due to the lack of data and limited modeling capabilities. In this work, we propose a controllable Chinese landscape painting generation method named CCLAP, which can generate painting with specific content and style based on Latent Diffusion Model. Specifically, it consists of two cascaded modules, i.e., content generator and style aggregator. The content generator module guarantees the content of generated paintings specific to the input text. While the style aggregator module is to generate paintings of a style corresponding to a reference image. Moreover, a new dataset of Chinese landscape paintings named CLAP is collected for comprehensive evaluation. Both the qualitative and quantitative results demonstrate that our method achieves state-of-the-art performance, especially in artfully-composed and artistic conception.

<div align=center>
<img src='https://github.com/Robin-WZQ/CCLAP/blob/main/images/model.png' width=600>
</div>

# 🔨 Demo & Results

You can play with our demo at [huggingface space](https://huggingface.co/spaces/RobinWZQ/CCLAP).

<div align=center>
<img src='https://github.com/Robin-WZQ/CCLAP/blob/main/images/pic1.png' width=600>
</div>

<div align=center>
<img src='https://github.com/Robin-WZQ/CCLAP/blob/main/images/pic2.png' width=600>
</div>


## 📄 Citation

If you find this project useful in your research, please consider cite:
```
@inproceedings{wang2023cclap,
      title={CCLAP: Controllable Chinese Landscape Painting Generation via Latent Diffusion Model}, 
      author={Zhongqi Wang and Jie Zhang and Zhilong Ji and Jinfeng Bai and Shiguang Shan},
      year={2023},
      booktitle={International Conference on Multimedia and Expo (ICME)}
}
```
