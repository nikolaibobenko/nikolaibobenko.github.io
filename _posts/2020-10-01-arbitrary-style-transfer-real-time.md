---
layout: post
title: Arbitrary Style Transfer in Real Time!
date: 2020-10-01
description: A walk through the style transfer paper
categories: papersexplained
tags: papersexplained
---

Here is my presentation of the style transfer paper. This method allows to train a single network to transfer arbitrary styles between arbitrary images and is very fast at generation time.

Notable is the definition of style. It is simply defined as the statistics (In this case first and second moment) of the middle layers of some pretrained image recognition network. It is not obvious that this should be the correct definition of style but these results indicate that it is a useful one. Furthermore now there is work building on this idea. Most notably NVidia's [StyleGAN](https://arxiv.org/abs/1812.04948) uses these style transfer layers to allow for human face generation on a level that has been out of reach before.

{% include video.liquid path="https://www.youtube.com/embed/jDadRuMSTHQ" class="img-fluid rounded z-depth-1" %}
