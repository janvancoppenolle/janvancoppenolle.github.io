---
layout: post
title: "Black & White Converters"
categories: lab
mathjax: yes
---

A collection of 3D LUTs for colour-to-greyscale conversion in 64x64x64 HALD and x65 CUBE format.

<!--more-->

[https://github.com/janvancoppenolle/LUT/tree/main/BW%20Conversion](https://github.com/janvancoppenolle/LUT/tree/main/BW%20Conversion)


| <img src="/img/Neutral-512.png" width="256"/> |
| :---: |
| Input |

## Brightness

$$ {r+ g + b \over 3} $$

| <img src="/img/bw-converters/Brightness.png" width="256"/> |
| :---: |
| Result |

## Luminance

$$ 0.2989 r + 0.587 g + 0.114 b $$

| <img src="/img/bw-converters/Luminance.png" width="256"/> |
| :---: |
| Result |

## Euclidean

$$ \sqrt{ r^2 + g^2 + b^2 \over 3} $$

| <img src="/img/bw-converters/Euclidean.png" width="256"/> |
| :---: |
| Result |

## sRGB Luma (Rec. 709)

$$ 0.2126r + 0.7152g + 0.0722b $$

| <img src="/img/bw-converters/Luma.png" width="256"/> |
| :---: |
| Result |

## Multiply

$$ (r+1) (g+1) (b+1) - 1 \over 7 $$

| <img src="/img/bw-converters/Multiply.png" width="256"/> |
| :---: |
| Result |

## Screen

$$ 8 - (2-r) (2-g) (2-b) \over 7 $$

| <img src="/img/bw-converters/Screen.png" width="256"/> |
| :---: |
| Result |

## Lightness

$$ min(r,g,b) + max(r,g,b) \over 2 $$

| <img src="/img/bw-converters/Lightness.png" width="256"/> |
| :---: |
| Result |

## Middle

$$ r+g+b-min(r,g,b)-max(r,g,b) $$

| <img src="/img/bw-converters/Middle.png" width="256"/> |
| :---: |
| Result |

## Minimum

$$ min(r,g,b) $$

| <img src="/img/bw-converters/Minimum.png" width="256"/> |
| :---: |
| Result |

## Maximum

$$ max(r,g,b) $$

| <img src="/img/bw-converters/Maximum.png" width="256"/> |
| :---: |
| Result |

## Orthochromatic (Cyan Filter)

$$ g + b \over 2 $$

| <img src="/img/bw-converters/OrthochromaticCyanFilter.png" width="256"/> |
| :---: |
| Result |

## Orthochromatic (Film Simulation)

$$ max(g,{b \over 2}) $$

| <img src="/img/bw-converters/OrthochromaticFilmSimulation.png" width="256"/> |
| :---: |
| Result |