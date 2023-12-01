---
layout: post
title: "Blend Mode Characteristics"
categories: lab
mathjax: yes
---

<!--more-->

| | $$ f(a,b)\over $$ | $$ Commutative\over $$ | $$ b? \to f(a,b) = a\over $$ | |
| :--- | :---: | :---: | :---: | :---: |
| &#9681; Average | <img src="/img/blend-modes/Average.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Average_Graph.png" width="32"/> |
| &#9681; Interpolation (Pegtop) | <img src="/img/blend-modes/Interpolation.png" width="32"/> | &#10003; | | <img src="/img/blend-modes/Interpolation_Graph.png" width="32"/> |
| &#9675; Multiply | <img src="/img/blend-modes/Multiply.png" width="32"/> | &#10003; | $$ 1 $$ | <img src="/img/blend-modes/Multiply_Graph.png" width="32"/> |
| &#9679; Screen | <img src="/img/blend-modes/Screen.png" width="32"/> | &#10003; | $$ 0 $$ | <img src="/img/blend-modes/Screen_Graph.png" width="32"/> |
| &#9675; Geometric Mean | <img src="/img/blend-modes/Geometric.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Geometric_Graph.png" width="32"/> |
| &#9679; Geometric<sup>-1</sup> | <img src="/img/blend-modes/GeometricInv.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/GeometricInv_Graph.png" width="32"/> |
| &#9675; Heronian | <img src="/img/blend-modes/Heronian.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Heronian_Graph.png" width="32"/> |
| &#9679; Heronian<sup>-1</sup> | <img src="/img/blend-modes/HeronianInv.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/HeronianInv_Graph.png" width="32"/> |
| &#9675; Pythagorean<sup>-1</sup> | <img src="/img/blend-modes/PythagoreanInv.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/PythagoreanInv_Graph.png" width="32"/> |
| &#9679; Pythagorean | <img src="/img/blend-modes/Pythagorean.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Pythagorean_Graph.png" width="32"/> |
| &#9675; Haze (Glare<sup>-1</sup>) | <img src="/img/blend-modes/Haze.png" width="32"/> | &#10003; | | <img src="/img/blend-modes/Haze_Graph.png" width="32"/> |
| &#9679; Glare | <img src="/img/blend-modes/Glare.png" width="32"/> | &#10003; | |  <img src="/img/blend-modes/Glare_Graph.png" width="32"/> |
| &#9675; Absorb | <img src="/img/blend-modes/Absorb.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Absorb_Graph.png" width="32"/> |
| &#9679; Emit | <img src="/img/blend-modes/Emit.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Emit_Graph.png" width="32"/> |
| &#9675; Darken | <img src="/img/blend-modes/Darken.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Darken_Graph.png" width="32"/> |
| &#9679; Lighten | <img src="/img/blend-modes/Lighten.png" width="32"/> | &#10003; | $$ a $$ | <img src="/img/blend-modes/Lighten_Graph.png" width="32"/> |
| &#9675; Root<sup>-1</sup> | <img src="/img/blend-modes/RootInv.png" width="32"/> | &#10003; | | <img src="/img/blend-modes/RootInv_Graph.png" width="32"/> |
| &#9679; Root | <img src="/img/blend-modes/Root.png" width="32"/> | &#10003; | | <img src="/img/blend-modes/Root_Graph.png" width="32"/> |
| &#9675; Linear Burn | <img src="/img/blend-modes/LinearBurn.png" width="32"/> | &#10003; | $$ 1 $$ | <img src="/img/blend-modes/LinearBurn_Graph.png" width="32"/> |
| &#9679; Linear Dodge (Add) | <img src="/img/blend-modes/Add.png" width="32"/> | &#10003; | $$ 0 $$ | <img src="/img/blend-modes/Add_Graph.png" width="32"/> |
| &#9675; Color Burn | <img src="/img/blend-modes/Burn.png" width="32"/> | | $$ 1 $$ | <img src="/img/blend-modes/Burn_Graph.png" width="32"/> |
| &#9679; Color Dodge | <img src="/img/blend-modes/Dodge.png" width="32"/> | | $$ 0 $$ | <img src="/img/blend-modes/Dodge_Graph.png" width="32"/> |
| &#9675; Soft Burn | <img src="/img/blend-modes/SoftBurn.png" width="32"/> | | $$ a $$ | <img src="/img/blend-modes/SoftBurn_Graph.png" width="32"/> |
| &#9679; Soft Dodge | <img src="/img/blend-modes/SoftDodge.png" width="32"/> | | $$ a $$ | <img src="/img/blend-modes/SoftDodge_Graph.png" width="32"/> |
| &#9675; Gamma Dark | <img src="/img/blend-modes/GammaDark.png" width="32"/> | | $$ 1 $$ | <img src="/img/blend-modes/GammaDark_Graph.png" width="32"/> |
| &#9679; Gamma Light | <img src="/img/blend-modes/GammaLight.png" width="32"/> | | $$ 0 $$ | <img src="/img/blend-modes/GammaLight_Graph.png" width="32"/> |
| &#9675; Freeze | <img src="/img/blend-modes/Freeze.png" width="32"/> | | | <img src="/img/blend-modes/Freeze_Graph.png" width="32"/> |
| &#9679; Reflect | <img src="/img/blend-modes/Reflect.png" width="32"/> | | | <img src="/img/blend-modes/Reflect_Graph.png" width="32"/> |
| &#9675; Heat | <img src="/img/blend-modes/Heat.png" width="32"/> | | | <img src="/img/blend-modes/Heat_Graph.png" width="32"/> |
| &#9679; Glow | <img src="/img/blend-modes/Glow.png" width="32"/> | | | <img src="/img/blend-modes/Glow_Graph.png" width="32"/> |
| &#9681; Overlay | <img src="/img/blend-modes/Overlay.png" width="32"/> | | $$ 0.5 $$ | <img src="/img/blend-modes/Overlay_Graph.png" width="32"/> |
| &#9681; Hard Light | <img src="/img/blend-modes/HardLight.png" width="32"/> | | $$ 0.5 $$ | <img src="/img/blend-modes/HardLight_Graph.png" width="32"/> |
| &#9681; Soft Light (Photoshop) | <img src="/img/blend-modes/SoftLightPhotoshop.png" width="32"/> | | $$ 0.5 $$ | <img src="/img/blend-modes/SoftLightPhotoshop_Graph.png" width="32"/> |
| &#9681; Soft Light | <img src="/img/blend-modes/SoftLight.png" width="32"/> | | $$ 0.5 $$ | <img src="/img/blend-modes/SoftLight_Graph.png" width="32"/> |
| &#9681; Pin Light | <img src="/img/blend-modes/PinLight.png" width="32"/> | | $$ a $$ | <img src="/img/blend-modes/PinLight_Graph.png" width="32"/> |
| &#9681; Extrapolate (Kai's Power Tools) | <img src="/img/blend-modes/KPTExtrapolate.png" width="32"/> | | $$ a $$ | <img src="/img/blend-modes/KPTExtrapolate_Graph.png" width="32"/> |
| &#9681; Vivid Light | <img src="/img/blend-modes/VividLight.png" width="32"/> | | $$ 0.5 $$ | <img src="/img/blend-modes/VividLight_Graph.png" width="32"/> |
| &#9681; Linear Light | <img src="/img/blend-modes/LinearLight.png" width="32"/> | | $$ 0.5 $$ | <img src="/img/blend-modes/LinearLight_Graph.png" width="32"/> |
| &#9681; Quadratic Light | <img src="/img/blend-modes/QuadraticLight.png" width="32"/> | | | <img src="/img/blend-modes/QuadraticLight_Graph.png" width="32"/> |
| &#9681; Modulated Light | <img src="/img/blend-modes/ModulatedLight.png" width="32"/> | | | <img src="/img/blend-modes/ModulatedLight_Graph.png" width="32"/> |
| &#9681; Hard Mix | <img src="/img/blend-modes/HardMix.png" width="32"/> | &#10003; | | <img src="/img/blend-modes/HardMix_Graph.png" width="32"/> |
| &#9680; Difference | <img src="/img/blend-modes/Difference.png" width="32"/> | &#10003; | $$ 0 $$ | <img src="/img/blend-modes/Difference_Graph.png" width="32"/> |
| &#9680; Exclusion | <img src="/img/blend-modes/Exclusion.png" width="32"/> | &#10003; | $$ 0 $$ | <img src="/img/blend-modes/Exclusion_Graph.png" width="32"/> |
| &#9680; Erosion | <img src="/img/blend-modes/Erosion.png" width="32"/> | &#10003; | | <img src="/img/blend-modes/Erosion_Graph.png" width="32"/> |
| &#9680; Solarization | <img src="/img/blend-modes/Solarize.png" width="32"/> | &#10003; | | <img src="/img/blend-modes/Solarize_Graph.png" width="32"/> |
| &#9680; Phoenix | <img src="/img/blend-modes/Phoenix.png" width="32"/> | &#10003; | $$ 1 $$ | <img src="/img/blend-modes/Phoenix_Graph.png" width="32"/> |
| &#9680; Negation | <img src="/img/blend-modes/Negation.png" width="32"/> | &#10003; |$$ 0 $$ | <img src="/img/blend-modes/Negation_Graph.png" width="32"/> |
| &#9675; Subtract | <img src="/img/blend-modes/Subtract.png" width="32"/> | | $$ 0 $$ | <img src="/img/blend-modes/Subtract_Graph.png" width="32"/> |
| &#9679; Divide | <img src="/img/blend-modes/Divide.png" width="32"/> | | $$ 1 $$ | <img src="/img/blend-modes/Divide_Graph.png" width="32"/> |
