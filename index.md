---
title: Main page
layout: default
---
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

<style>
img {
    border: 1px solid #ddd;
    border-radius: 4px;  
    padding: 5px;
    width: 150px;
}

{
    box-sizing: border-box;
}

.column {
    float: left;
    width: 20%;
    padding: 0px;
}

.row::after {
    content: "";
    clear: both;
    display: table;
}
</style>

# Hello explorer and experimenter, welcome to **Science Docs**!

### I have a dream...

> À force de croire en ses rêves, l’homme en fait une réalité.  
__*Hergé*__

**Science Docs** is a collection of **projects**, **tutorials** and **study notes** that are the product of most of my passion that I have for life, Universe and everything else. They are aimed for explorers and experimenters who are willing to study scientific or engineering subjects with what Richard Feynman called: *"the pleasure of finding things out"*.

I have a dream that the PDFs will now enrich your journey through learning.

# PDFs

## Completed

### Objectif Morse

In the **Objectif Morse** project you will make an interesting use of Arduino, electronic circuits and C++ while transmitting messages in Morse alphabet between computers.

<div class="row">
  <div class="column">
    <a><img src="https://github.com/camillejr/objectif_morse/blob/master/Documentation/DWGs/scheme.png?raw=true" alt="cooking_water" style="width:150px"></a>
  </div>
  <div class="column">
    <p><span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/objectif_morse/raw/master/Documentation/Objectif_Morse.pdf"> PDF tutorial</a></span></p>
    <p><span class="fa fa-github"><a href="https://github.com/camillejr/objectif_morse"> GitHub repository</a></span></p>
  </div>
</div>

### Cooking water

This small home experiment is for deriving the temperature vs. time curve for cooking water on three types of stoves: electrical, induction and gas.

<div class="row">
  <div class="column">
    <a><img src="https://github.com/camillejr/home_experiments/blob/master/stoves/DWGs/all_stoves.png?raw=true" alt="cooking_water" style="width:150px"></a>
  </div>
  <div class="column">
    <p><span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/home_experiments/raw/master/stoves/Stoves.pdf"> PDF tutorial</a></span></p>
    <p><span class="fa fa-github"><a href="https://github.com/camillejr/home_experiments/tree/master/stoves"> GitHub repository</a></span></p>
  </div>
</div>


### POD and DMD decomposition of numerical and experimental data

Using two data decomposition methods: **Proper Orthogonal Decomposition** and **Dynamic Mode Decomposition**, as well as concepts from linear algebra and dynamical systems within Matlab scripts, I searched for low-rank structures in the pulsating Poiseuille flow and in the velocity field of the flow behind a cylinder.

This work has been produced as part of the Short Training Programme at the von Karman Institute for Fluid Dynamics.

<div class="row">
  <div class="column">
    <a><img src="https://github.com/camillejr/vki_short_training/blob/master/DWGs/GIF_2D_POD_r3.gif?raw=true" alt="POD_DMD" style="width:150px"></a>
  </div>
  <div class="column">
    <p><span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/vki_short_training/raw/master/final_report/stagiaire_report_kzdybal.pdf"> PDF final report</a></span></p>
    <p><span class="fa fa-github"><a href="https://github.com/camillejr/vki_short_training"> GitHub repository</a></span></p>
  </div>
</div>

### Proof of associative law for matrices

This is a proof of the associative law for matrices inspired by one of the MIT lectures from a course on Linear Algebra by professor Gilbert Strang.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/numerical_methods/raw/master/associative_law/associative_law_proof.pdf"> PDF note</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/numerical_methods/tree/master/associative_law"> GitHub repository</a></span>

## Under construction

### Computational examples in transport phenomena with Python

I collected the most interesting computational examples in various transport phenomena in a form of a tutorial and created a set of Python codes to accompany a better understanding of the results.

This tutorial has been produced during two edX courses offered by Delft University: The Basics of Transport Phenomena and Advanced Transport Phenomena.

<sup>This tutorial is still under construction...</sup>

<div class="row">
  <div class="column">
    <a><img src="https://github.com/camillejr/fluid_mechanics/blob/master/Transport_Phenomena/DWGs/lumped_system.gif?raw=true" alt="transport_phenomena" style="width:150px"></a>
  </div>
  <div class="column">
    <p><span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/fluid_mechanics/raw/master/Transport_Phenomena/computational_examples.pdf"> PDF tutorial</a></span></p>
    <p><span class="fa fa-github"><a href="https://github.com/camillejr/fluid_mechanics/tree/master/Transport_Phenomena"> GitHub repository</a></span></p>
  </div>
</div>

# A (bit) less scientific section

### Thought process in watercolours

In this document I present how I apply the thought process to improve my watercolour paintings.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/learning_to_draw_and_paint/raw/master/self_feedback.pdf"> PDF tutorial</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/learning_to_draw_and_paint"> GitHub Watercolour repository</a></span>

# Science blog & thoughts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<footer class="site-footer">

  <span class="site-footer-credits">This site uses: <a href="https://github.com/lorepirri/cayman-blog">Cayman Blog Theme</a>  by Lorenzo Pirritano (@lorepirri)  | <a href="https://github.com/lorepirri/cayman-blog/blob/master/LICENSE">Licence</a>: Creative Commons Attribution 1.0 International </span>
</footer>
