---
layout: post
title: "Inverters"
categories: lut
mathjax: yes
---

Inversions of image colour components.

## Channel Inversion

| ![](/img/TestWheel.png) | ![Channel Inversion](/img/ChannelInversionTestWheel.png) |
| :---: | :---: |
| Inverts the image by inverting the channel values. |

$$ f(x) = 1-x $$

White becomes black and vice versa. Hues are rotated 180° – red becomes cyan, green becomes magenta and blue becomes yellow.

## Hue Inversion

| ![Hue Inversion](/img/HueInversionTestWheel.png) | Point reflection / rotation of the colour wheel without inversion of the Lightness. |

## Lightness Inversion

| ![Lightness Inversion](/img/LightnessInversionTestWheel.png) | This inverts the image but keeps the hue. |

It combines both operations of Channel Inversion and Hue Inversion in order to avoid the rotation of the colour wheel.
