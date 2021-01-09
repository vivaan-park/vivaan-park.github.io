---
layout: post
title: "CNN을 이용하여 월리 찾기"
date: 2021-01-09 21:31:27 +0900
description: 월리를 찾아라 # Add post description (optional)
img: where-is-wally/wally.jpg # Add image post (optional)
tags: [Deep Learning, CNN] # add tag
git: where-is-wally # git repository name
---
# Where's Wally?

'월리를 찾아라'는 거대한 한 장의 그림속에서 월리라 불리는 캐릭터를 찾는 놀이입니다.  

여기서는 [Tiramisu]를 이용하여 여러 캐릭터들이 빽빽하게 섞여있는 이미지에서 월리를 찾아내는 모델을 생성합니다.  
또한, 이미지에서 월리가 아닌 부분을 투명하게 마스킹하여 예측 결과를 나타냅니다.

# Preview
![preview](/assets/img/where-is-wally/preview.png)

[Tiramisu]: https://arxiv.org/abs/1611.09326