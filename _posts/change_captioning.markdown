---
layout: post
title:  "Finding it at another side: A viewpoint-adapted matching encoder for change captioning"
date:   2020-13-11
categories: DeepLearning VideoCaptioning ChangeCaptioning ReinforcementLearning
---
![main](/assets/img/changecaptioning.jpeg)


<div class="grid-wrapper">
  <div style="grid-column: span 3;">
    <p class="blue" style="margin-top:0px; margin-bottom:0px;">
      <b>Xiangxi Shi</b>
      &nbsp;&nbsp; <a href="https://yangxuntu.github.io/" class="author-link">Xu Yang</a>
      &nbsp;&nbsp; <a href="https://gujiuxiang.com/" class="author-link">Jiuxiang Gu</a>
      &nbsp;&nbsp; <a href="https://raihanjoty.github.io/" class="author-link">Shafiq Joty</a>
      &nbsp;&nbsp; <a href="https://www.ntu.edu.sg/home/asjfcai/" class="author-link">Jianfei Cai</a>
    </p>
    <p style="margin-top:0px;"><i>ECCV, 2020</i></p>
    <p align="justify">
Change Captioning is a task that aims to describe the difference between images with natural language. Most existing methods treat this problem as a difference judgment without the existence of distractors, such as viewpoint changes. However, in practice, viewpoint changes happen often and can overwhelm the semantic difference to be described. In this paper, we propose a novel visual encoder to explicitly distinguish viewpoint changes from semantic changes in the change captioning task. Moreover, we further simulate the attention preference of humans and propose a novel reinforcement learning process to fine-tune the attention directly with language evaluation rewards. Extensive experimental results show that our method outperforms the state-of-the-art approaches by a large margin in both Spot-the-Diff and CLEVR-Change datasets .
