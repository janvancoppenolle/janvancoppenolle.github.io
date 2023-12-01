---
layout: post
title: "Blend Modes"
categories: lab
mathjax: yes
---

| ![](/img/blend-modes/a.png) | ![](/img/blend-modes/b.png) |
| :---: | :---: |
| $$ a $$ | $$ b $$ |

### &#9681; Average

| ![](/img/blend-modes/Average.png) |
| :---: |
| $$ f(a,b) = {a + b \over 2} $$ |

### &#9681; Interpolation (Pegtop)

| ![](/img/blend-modes/Interpolation.png) |
| :---: |
| $$ f(a,b) = {2-cos(a\pi)-cos(b\pi) \over 4} $$ |

### &#9675; Multiply

| ![](/img/blend-modes/Multiply.png) |
| :---: |
| $$ f(a,b) = ab $$ |

### &#9679; Screen

| ![](/img/blend-modes/Screen.png) |
| :---: |
| $$ f(a,b) = 1-(1-a)(1-b) $$ |

### &#9675; Geometric Mean

| ![](/img/blend-modes/Geometric.png) |
| :---: |
| $$ f(a,b) = \sqrt {ab} $$ |

### &#9679; Geometric<sup>-1</sup>

| ![](/img/blend-modes/GeometricInv.png) |
| :---: |
| $$ f(a,b) = 1 - \sqrt {(1-a)(1-b)} $$ |

### &#9675; Heronian

| ![](/img/blend-modes/Heronian.png) |
| :---: |
| $$ f(a,b) = {a + \sqrt {ab} +b \over 3} $$ |

### &#9679; Heronian<sup>-1</sup>

| ![](/img/blend-modes/HeronianInv.png) |
| :---: |
| $$ f(a,b) = 1 - {2 - a + \sqrt {(1-a)(1-b)} - b \over 3} $$ |

### &#9675; Pythagorean<sup>-1</sup>

| ![](/img/blend-modes/PythagoreanInv.png) |
| :---: |
| $$ f(a,b) = 1 - \sqrt {(1-a)^2+(1-b)^2 \over 2} $$ |

### &#9679; Pythagorean

| ![](/img/blend-modes/Pythagorean.png) |
| :---: |
| $$ f(a,b) = \sqrt {a^2+b^2 \over 2} $$ |

### &#9675; Haze (Glare<sup>-1</sup>)

| ![](/img/blend-modes/Haze.png) |
| :---: |
| $$ f(a,b) = a + b + ab - a^2 - b^2 $$ |

### &#9679; Glare

| ![](/img/blend-modes/Glare.png) |
| :---: |
| $$ f(a,b) = a^2 + b^2 - ab $$ |

### &#9675; Absorb

| ![](/img/blend-modes/Absorb.png) |
| :---: |
| $$ f(a,b) = \begin{cases} a, & if\ a = b \\ \| {1-b \over 1-a} - (1-b) \% (1-a) \|, & if\ a < b  \\ \| {1-a \over 1-b} - (1-a) \% (1-b) \|, & otherwise \end{cases} $$ |

### &#9679; Emit

| ![](/img/blend-modes/Emit.png) |
| :---: |
| $$ f(a,b) = \begin{cases} a, & if\ a = b \\ 1 - \| {a \over b} - a \% b \|, & if\ a < b  \\ 1 - \| {b \over a} - b \% a \|, & otherwise \end{cases} $$ |

### &#9675; Darken

| ![](/img/blend-modes/Darken.png) |
| :---: |
| $$ f(a,b) = \begin{cases} a, & if\ a < b \\ b, & otherwise \end{cases} $$ |

### &#9679; Lighten

| ![](/img/blend-modes/Lighten.png) |
| :---: |
| $$ f(a,b) = \begin{cases} a, & if\ a > b \\ b, & otherwise \end{cases} $$ |

### &#9675; Root<sup>-1</sup>

| ![](/img/blend-modes/RootInv.png) |
| :---: |
| $$ f(a,b) = 1 - \sqrt {2-a-b \over 2} $$ |

### &#9679; Root

| ![](/img/blend-modes/Root.png) |
| :---: |
| $$ f(a,b) = \sqrt {a+b \over 2} $$ |

### &#9675; Linear Burn

| ![](/img/blend-modes/LinearBurn.png) |
| :---: |
| $$ f(a,b) = a + b - 1 $$ |

### &#9679; Linear Dodge (Add)

| ![](/img/blend-modes/Add.png) |
| :---: |
| $$ f(a,b) = a + b $$ |

### &#9675; Color Burn

| ![](/img/blend-modes/Burn.png) |
| :---: |
| $$ f(a,b) =  \begin{cases} 0, & if\ b = 0 \\ 1 - {(1 - a)\over b}, & otherwise \end{cases} $$ |

### &#9679; Color Dodge

| ![](/img/blend-modes/Dodge.png) |
| :---: |
| $$ f(a,b) = \begin{cases} 1, & if\ b = 1 \\ {a\over(1 - b)}, & otherwise \end{cases} $$ |

### &#9675; Soft Burn

| ![](/img/blend-modes/SoftBurn.png) |
| :---: |
| $$ f(a,b) = 1-{1-a \over \| 1-a+b \| } $$ |

### &#9679; Soft Dodge

| ![](/img/blend-modes/SoftDodge.png) |
| :---: |
| $$ f(a,b) = {a \over \| 1+a-b \| } $$ |

### &#9675; Gamma Dark

| ![](/img/blend-modes/GammaDark.png) |
| :---: |
| $$ f(a,b) = a^{1 \over b} $$ |

### &#9679; Gamma Light

| ![](/img/blend-modes/GammaLight.png) |
| :---: |
| $$ f(a,b) = 1-(1-a)^{1 \over 1-b} $$ |

### &#9675; Freeze

| ![](/img/blend-modes/Freeze.png) |
| :---: |
| $$ f(a,b) = 1 - {(1-a)^2 \over b} $$ |
| $$ f_{Freeze}(a,b) = f_{Heat}(b,a) $$ |

### &#9679; Reflect

| ![](/img/blend-modes/Reflect.png) |
| :---: |
| $$ f(a,b) = {a^2 \over (1-b)} $$ |
| $$ f_{Reflect}(a,b) = f_{Glow}(b,a) $$ |

### &#9675; Heat

| ![](/img/blend-modes/Heat.png) |
| :---: |
| $$ f(a,b) = 1 - {(1-b)^2 \over a} $$ |
| $$ f_{Heat}(a,b) = f_{Freeze}(b,a) $$ |

### &#9679; Glow

| ![](/img/blend-modes/Glow.png) |
| :---: |
| $$ f(a,b) = {b^2 \over (1-a)} $$ |
| $$ f_{Glow}(a,b) = f_{Reflect}(b,a) $$ |

### &#9681; Overlay

| ![](/img/blend-modes/Overlay.png) |
| :---: |
| $$ f_{Overlay}(a,b) = f_{Hard Light}(b,a) $$ |

### &#9681; Hard Light

| ![](/img/blend-modes/HardLight.png) |
| :---: |
| $$ f(a,b) = \begin{cases} 2ab, & if\ b \lt 0.5 \\ 1 - 2(1 - a)(1 - b), & otherwise \end{cases} $$ |
| $$ f(a,b) = \begin{cases} f_{Multiply}(a,2b), & if\ b \lt 0.5 \\ f_{Screen}(a,2b-1), & otherwise \end{cases} $$ |

### &#9681; Soft Light (Photoshop)

| ![](/img/blend-modes/SoftLightPhotoshop.png) |
| :---: |
| $$ f(a,b) = \begin{cases} 2ab+a^2(1-2b), & if\ b \lt 0.5 \\ 2a(1-b)+ \sqrt a (2b-1), & otherwise \end{cases} $$ |

### &#9681; Soft Light

| ![](/img/blend-modes/SoftLight.png) |
| :---: |
| $$ f(a,b) = 2ab + a^2(1 - 2b) $$ |
| $$ f(a,b) = (1-a)\times f_{Multiply}(a,b) + a\times f_{Screen}(a,b) $$ |

### &#9681; Pin Light

| ![](/img/blend-modes/PinLight.png) |
| :---: |
| $$ f(a,b) = \begin{cases} f_{Darken}(a,2b), & if\ b \lt 0.5 \\ f_{Lighten}(a,2b-1), & otherwise \end{cases} $$ |

### &#9681; Extrapolate (Kai's Power Tools)

| ![](/img/blend-modes/KPTExtrapolate.png) |
| :---: |
| $$ f(a,b) = 2a-b $$ |

### &#9681; Vivid Light

| ![](/img/blend-modes/PinLight.png) |
| :---: |
| $$ f(a,b) =  \begin{cases} f_{Burn}(a,2b), & if\ b \lt 0.5 \\ f_{Dodge}(a,2b-1), & otherwise \end{cases} $$ |

### &#9681; Linear Light

| ![](/img/blend-modes/LinearLight.png) |
| :---: |
| $$ f(a,b) = \begin{cases} f_{LinearBurn}(a,ab), & if\ b \lt 0.5 \\ f_{LinearDodge}(a,2b-1), & otherwise \end{cases} $$ |
| $$ f(a,b) = a+2b-1 $$ |

### &#9681; Quadratic Light

| ![](/img/blend-modes/QuadraticLight.png) |
| :---: |
| $$ f(a,b) = (1-b)\times f_{Freeze}(a,b)+b\times f_{Reflect}(a,b) $$ |

### &#9681; Modulated Light

| ![](/img/blend-modes/ModulatedLight.png) |
| :---: |
| $$ f(a,b) = \begin{cases} a, & if\ a=1-b \\ \|{b \over 1-a} - b\% (1-a) \|, & if\ a\lt 1-b \\1-\|{1-b \over a} - (1-b)\%a\|, & otherwise \end{cases} $$ |

### &#9681; Hard Mix

| ![](/img/blend-modes/HardMix.png) |
| :---: |
| $$ f(a,b) = \begin{cases} 0, & if\ {a+b \over 2} \lt 0.5 \\ 1, & otherwise \end{cases} $$ |

### &#9680; Difference

| ![](/img/blend-modes/Difference.png) |
| :---: |
| $$ f(a,b) = \| a-b \| $$ |

### &#9680; Exclusion

| ![](/img/blend-modes/Exclusion.png) |
| :---: |
| $$ f(a,b) = a+b-2ab $$ |

### &#9680; Erosion

| ![](/img/blend-modes/Erosion.png) |
| :---: |
| $$ f(a,b) = (a-b)^2 $$ |

### &#9680; Solarization

| ![](/img/blend-modes/Solarize.png) |
| :---: |
| $$ f(a,b) = 1 - \sqrt {(2a-1)^2+(2b-1)^2 \over 2} $$ |

### &#9680; Phoenix

| ![](/img/blend-modes/Phoenix.png) |
| :---: |
| $$ f(a,b) = 1-\|a-b\|$$ |

### &#9680; Negation

| ![](/img/blend-modes/Negation.png) |
| :---: |
| $$ f(a,b) = 1-\|1-a-b\| $$ |

### &#9675; Subtract

| ![](/img/blend-modes/Subtract.png) |
| :---: |
| $$ f(a,b) = a - b $$ |

### &#9679; Divide

| ![](/img/blend-modes/Divide.png) |
| :---: |
| $$ f(a,b) = {a \over b} $$ |

