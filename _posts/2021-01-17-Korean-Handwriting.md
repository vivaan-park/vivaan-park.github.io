---
layout: post
title: "GAN을 이용하여 한글 손글씨 생성하기"
date: 2021-01-17 20:24:49 +0900
description: 한글 손글씨 생성 # Add post description (optional)
img: korean-handwriting/korean.jpg # Add image post (optional)
tags: [Deep Learning, GAN] # add tag
git: korean-handwriting # git repository name
---
# Korean Handwriting

Generative Adversarial Network(이하 GAN)이란 데이터를 생성해내는 생성자(Generator)와 생성된 데이터가 진짜인지 가짜인지 구분하는 구분자(Discriminator) 두 개의 모델로 구성됩니다. 생성자의 목적은 최대한 그럴듯한 가짜 데이터를 만들어내는 것이며, 구분자의 목적은 생성자가 만든 데이터가 가짜인지 진짜인지 구분하는 것입니다. 흔히들 생성자를 위조지폐범, 구분자를 경찰에 비유하여 설명합니다.  

이 프로젝트에서는 이러한 GAN 알고리즘을 이용하여, 한글 손글씨와 유사한 이미지를 생성합니다. 다만, 가-힣 까지의 총 11,172개의 한글을 학습하다보니 조금 괴상한 단어들이 결과로 생성되었습니다. 이는 더 적은 종류의 데이터를 사용하거나(예를 들어, 가-마 정도의 데이터), 더 많은 시간 학습한다면 개선될 것이라 생각합니다.

# Preview
![preview](/assets/img/korean-handwriting/preview.gif)
