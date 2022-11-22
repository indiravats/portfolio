---
title: "Accessible Entrepreneurship Support & Facilitation Ecosystem "
description: "A project for Ministry of Skill Development and Entrepreneurship under Smart India Hackathon"
dateString: Jan 2022 - July 2022
draft: false
tags: ["Python", "Machine Learning", "CNN", "LSTM", "Deep Learning",  "AI"]
showToc: false
weight: 201
--- 

[![Accessible Platform for Entrepreneurs](/projects/accessibility-system/video.jpg)](https://www.youtube.com/watch?v=RmOgL6IYQkM)


## Description
In this project, I implemented the paper **[Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044)**. The neural network, a combination of **CNN** and **LSTM**, was trained on the **MS COCO** dataset and it learns to generate captions from images. 

As the network generates the caption, word by word, the model’s gaze (attention) shifts across the image. This allows it to focus on those parts of the image which is more relevant for the next word to be generated. 
![Attention Mechanism](/projects/automated-image-captioning/img1.jpg)

Furthermore, beam search is used during inference to enhance the prediction result. The network was trained in **PyTorch** on an **Nvidia GTX 1060** graphics card for over 80 epochs.