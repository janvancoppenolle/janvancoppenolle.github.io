---
layout: post
title: "Curve Shapers"
categories: lab
mathjax: yes
---

A collection of 1D LUTs in CUBE and Photoshop Arbitrary Map (.amp Curves Preset) format for image shaping.

<!--more-->

[https://github.com/janvancoppenolle/LUT/tree/main/Shapers](https://github.com/janvancoppenolle/LUT/tree/main/Shapers)

| <img src="/img/Curve.png" height="240"/> | <img src="/img/TestWheel.png" height="240"/> |
| :---: | :---: | :---: |
| Curve | Result |

## Soft S-Curve

The result is equal to blending the image with itself using the simplified Soft Light blend mode.

$$ f(x) = 3x^2-2\sqrt[3]{x} $$

| <img src="/img/curve-shapers/SoftSCurve.png" height="240"/> | <img src="/img/curve-shapers/SoftSCurveTestWheel.png" height="240"/> |
| :---: | :---: | :---: |
| Curve | Result |

## Sigmoid S-Curve

Very strong contrast S-Curve.

$$ f(x)={1\over{1+e^{(6-12x)}}} $$

| <img src="/img/curve-shapers/SigmoidCurve.png" height="240"/> | <img src="/img/curve-shapers/SigmoidTestWheel.png" height="240"/> |
| :---: | :---: | :---: |
| Curve | Result |

## Sharpen Contrast

There used to be a Kai Krause filter for Photoshop part of the KPT bundle with this name.
It clips 25% black and 25% white.

$$ f(x)={4x-1 \over 2} $$

| <img src="/img/curve-shapers/SharpenContrastCurve.png" height="240"/> | <img src="/img/curve-shapers/SharpenContrastTestWheel.png" height="240"/> |
| :---: | :---: | :---: |
| Curve | Result |

## Cubic

This softens the contrast instead of enhancing it.

$$ f(x)=2x^3-3x^2+2x $$

| <img src="/img/curve-shapers/CubicCurve.png" height="240"/> | <img src="/img/curve-shapers/CubicTestWheel.png" height="240"/> |
| :---: | :---: | :---: |
| Curve | Result |

## Gamma Correction

$$ f(x)=x^{1/\gamma} $$

| <img src="/img/curve-shapers/Gamma_1.6Curve.png" height="240"/> | <img src="/img/curve-shapers/Gamma_1.6TestWheel.png" height="240"/> |
| :---: | :---: | :---: |
| Curve | Result |

$$ Gamma\ 1.6\ (γ = 0.625) $$