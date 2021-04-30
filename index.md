---
title: Science Docs
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

<ul id="intro"></ul>

### Hello, welcome to Science Docs!

**Science Docs** is a collection of tutorials, articles, coding projects and study notes that are the product of most of my passion that I have for life, Universe and everything else. Many of the materials gathered here are related to my research work and I have hopes that by sharing them you might find pursuing science fascinating! I have a dream that the PDFs will now enrich your journey through learning and experimenting.

<sup>This site is always alive. The documents and the associated repositories get updated from time to time. Even though a document is completed, it does not mean that its content will not change in the future. Any corrections or update proposals are welcome. Feel free to drop me a line at: *kamilazdybal at gmail dot com*.</sup>

<sup>Reach out to the <a href="/science-docs/#about">About</a> section for a bit more info, or to the <a href="/science-docs/#blog">Science blog & thoughts</a> section for more fun science stuff.</sup>

-----------------------

<ul id="pcafold"></ul>

# **PCAfold** - Low-dimensional PCA-derived manifolds and everything in between!

Check out **PCAfold**, our Python software for generating, analyzing and improving low-dimensional manifolds.
It can be used for data clustering and sampling, dimensionality reduction, nonlinear regression and assessing the quality of low-dimensional manifolds.

Reach out to the documentation for many illustrative tutorials! Now also available in [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.multiscale.utah.edu%2Fcommon%2FPCAfold/master?filepath=docs%2Ftutorials%2F).

<sup>**PCAfold** is published in the SoftwareX journal. You can cite the software as:</sup>
<sup>K. Zdybał, E. Armstrong, A. Parente, J. C. Sutherland, *PCAfold: Python software to generate, analyze and improve PCA-derived low-dimensional manifolds*, SoftwareX 12, 2020</sup>

<sup>This work has been produced during my PhD at Université libre de Bruxelles and my research stay at the University of Utah.</sup>

<div class="row">
  <div class="column">
    <a><img src="https://gitlab.multiscale.utah.edu/common/PCAfold/-/raw/docs-cleanup/docs/images/PCAfold-logo.svg" alt="PCAfold" style="width:150px"></a>
  </div>
  <div class="column">
    <h4><span class="fa fa-file-pdf-o"></span><a href="https://www.sciencedirect.com/science/article/pii/S2352711020303435" target="_blank"> Publication</a></h4>
    <h4><span class="fa fa-book"></span><a href="https://pcafold.readthedocs.io/" target="_blank"> Documentation</a></h4>
    <h4><span class="fa fa-github"></span><a href="https://gitlab.multiscale.utah.edu/common/PCAfold" target="_blank"> Repository</a></h4>
  </div>
</div>

<ul id="heatconduction"></ul>

# Steady-state heat conduction

A computational example of steady-state heat conduction in a lengthwise-insulated rod with internal heat production spiced up with a bit of Python!

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/fluid-dynamics-and-transport-phenomena/blob/master/transport-phenomena-with-Python/figures/steady-state-heat-conduction.png?raw=true" alt="Heat-transfer" style="width:150px"></a>
  </div>
  <div class="column">
    <h4><span class="fa fa-file-pdf-o"></span><a href="https://github.com/kamilazdybal/fluid-dynamics-and-transport-phenomena/raw/master/transport-phenomena-with-Python/example-heat-transfer-in-a-rod.pdf" target="_blank"> Tutorial</a></h4>
    <h4><span class="fa fa-code"></span><a href="https://nbviewer.jupyter.org/github/kamilazdybal/fluid-dynamics-and-transport-phenomena/blob/master/transport-phenomena-with-Python/code/01-heat-conduction.ipynb" target="_blank"> Jupyter notebook</a></h4>
  </div>
</div>

<ul id="tensornecessity"></ul>

# The tensor necessity - a short story about momentum transport in fluids

At first encounter, tensors can seem like strange mathematical objects. It can be challenging to grasp their meaning and their relevance might not be immediately obvious. At the same time, tensors are indispensable when studying fluid dynamics. So what's with the tensors and why do we need them?

*This is a beta version of an article. You can help me make it better by spotting errors or suggesting improvements!*

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/fluid-dynamics-and-transport-phenomena/blob/master/tensor-necessity/plots/thumbnail.png?raw=true" alt="Tensor-necessity" style="width:150px"></a>
  </div>
  <div class="column">
    <h4><span class="fa fa-file-pdf-o"></span><a href="https://github.com/kamilazdybal/fluid-dynamics-and-transport-phenomena/raw/master/tensor-necessity/tensor-necessity.pdf" target="_blank"> Article</a></h4>
  </div>
</div>

<ul id="pca"></ul>

# The linear algebra of Principal Component Analysis (with Python examples)

These are notes on the linear algebra aspects of Principal Component Analysis (PCA) with a little bit more insight then you would typically get when reading about PCA from online tutorials. The notes are accompanied by several Python computational examples.

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/ulb-atm-phd/blob/master/PCA/plots/thumbnail.png?raw=true" alt="PCA sample" style="width:150px"></a>
  </div>
  <div class="column">
    <h4><span class="fa fa-file-pdf-o"></span><a href="https://github.com/kamilazdybal/ulb-atm-phd/raw/master/PCA/PCA.pdf" target="_blank"> Tutorial</a></h4>
    <h4><span class="fa fa-code"></span><a href="https://nbviewer.jupyter.org/github/kamilazdybal/ulb-atm-phd/blob/master/PCA/PCA-tutorial.ipynb" target="_blank"> Jupyter notebook</a></h4>
  </div>
</div>

<ul id="objectifmorse"></ul>

# Objectif Morse

Did you ever wonder what if there were two computers talking to each other using Morse code? One would send a message with light signals and the other would collect the light and understand the message? No cable connecting the computers. The information simply carried by light that travels through the air.

Well, here it is! In the Objectif Morse project you will make an interesting use of Arduino, electronic circuits and C++ while transmitting messages in Morse alphabet between computers.

<sup>This work has been produced as part of the *Arduino Study Group* meetings at the Jagiellonian University.</sup>

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/objectif-morse/blob/master/Documentation/cover_obj_morse.jpg?raw=true" alt="objectif_morse" style="width:150px"></a>
  </div>
  <div class="column">
    <h4><span class="fa fa-file-pdf-o"></span><a href="https://github.com/kamilazdybal/objectif-morse/raw/master/Documentation/Objectif_Morse.pdf" target="_blank"> Tutorial</a></h4>
    <h4><span class="fa fa-code"></span><a href="https://github.com/kamilazdybal/objectif-morse/tree/master/Code" target="_blank"> Code</a></h4>
    <h4><span class="fa fa-github"></span><a href="https://github.com/kamilazdybal/objectif-morse" target="_blank"> Repository</a></h4>
  </div>
</div>

<ul id="poddmd"></ul>

# POD and DMD decomposition of numerical and experimental data

Using two data decomposition methods: Proper Orthogonal Decomposition (POD) and Dynamic Mode Decomposition (DMD), as well as concepts from linear algebra and dynamical systems within Matlab scripts, I searched for low-rank structures in the pulsating Poiseuille flow and in the velocity field of the flow behind a cylinder.

<sup>This work has been produced as part of the Short Training Programme at the von Karman Institute for Fluid Dynamics, under supervision of Professor Miguel A. Mendez.</sup>

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/POD-DMD-decompositions/blob/master/DWGs/GIF_2D_POD_r3.gif?raw=true" alt="POD_DMD" style="width:150px"></a>
  </div>
  <div class="column">
    <h4><span class="fa fa-file-pdf-o"></span><a href="https://github.com/kamilazdybal/POD-DMD-decompositions/raw/master/final-report/stagiaire_report_kzdybal.pdf" target="_blank"> Report</a></h4>
    <h4><span class="fa fa-github"></span><a href="https://github.com/kamilazdybal/POD-DMD-decompositions" target="_blank"> Repository</a></h4>
  </div>
</div>

<ul id="associativelaw"></ul>

# Proof of the associative law for matrices

I was reviewing the amazing MIT 18.06 course on linear algebra. When the associative law appeared on the blackboard, Professor Strang said: *It’s not that easy to prove that this is correct. You have to go into the gory details of matrix multiplication, do it both ways and see that you come out the same.*

So I said: *let’s do it!*

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/linear-algebra/raw/master/proof-of-associative-law/proof-of-associative-law-thumbnail.png?raw=true" alt="MIT-G-Strang" style="width:150px"></a>
  </div>
  <div class="column">
    <h4><span class="fa fa-file-pdf-o"></span><a href="https://github.com/kamilazdybal/linear-algebra/raw/master/proof-of-associative-law/proof-of-associative-law.pdf" target="_blank"> Note</a></h4>
  </div>
</div>

<ul id="gpr"></ul>

# Notes on Gaussian Process Regression

Following a great [lecture](https://www.youtube.com/watch?v=UpsV1y6wMQ8) by Professor Anna Scaife I decided to reproduce her figures and write a small note on Gaussian Process Regression (GPR).

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/ulb-atm-phd/blob/master/GPR/DWGs/thumbnail.png?raw=true" alt="transport_phenomena" style="width:150px"></a>
  </div>
  <div class="column">
  <h4><span class="fa fa-file-pdf-o"></span><a href="https://github.com/kamilazdybal/ulb-atm-phd/raw/master/GPR/GPR.pdf" target="_blank"> Note</a></h4>
  </div>
</div>

-----------------------

## Under construction

<ul id="dmd"></ul>

# Notes on Dynamic Mode Decomposition

These are notes on Dynamic Mode Decomposition (DMD), a data-driven method for finding low-rank structures in high-dimensional data sets. These notes come mainly from two lectures by Prof. Nathan Kutz from the University of Washington but also from other sources and my own previous study of DMD.

<sup>This document is still under construction... Would you like to help in completing it?</sup>

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/ulb-atm-phd/blob/master/DMD/DWGs/DMD-science-docs.png?raw=true" alt="DMD-notes" style="width:150px"></a>
  </div>
</div>

<ul id="fluidtoolbox"></ul>

# Fluid Toolbox

Fluid Toolbox is a collection of human-readable, pseudo-random study notes. It contains descriptions and explanations of various fluid mechanics concepts. It is meant to be used complimentary to the regular textbook since it may provide additional insights but it will not substitute the thoroughness of the standard course in the subject. I believe that working side by side with the course, it can become a useful toolbox of concepts that are ready-to-use and ready-to-understand.

<sup>This document is still under construction... Would you like to help in completing it?</sup>

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/fluid-dynamics-and-transport-phenomena/blob/master/fluid-toolbox/cover-fluid-toolbox.png?raw=true" alt="transport_phenomena" style="width:150px"></a>
  </div>
</div>

<ul id="transportphenomena"></ul>

# Computational examples in transport phenomena with Python

I collected few interesting computational examples in transport phenomena in a form of a tutorial and created a set of Python codes to accompany a better understanding of the results.

<sup>This tutorial has been produced after taking two great courses offered by TU Delft: *The Basics of Transport Phenomena* and *Advanced Transport Phenomena*.</sup>

<sup>This document is still under construction... Would you like to help in completing it?</sup>

<div class="row">
  <div class="column">
    <a><img src="https://github.com/kamilazdybal/fluid-dynamics-and-transport-phenomena/blob/master/transport-phenomena-with-Python/figures/cover-trans-phen.jpg?raw=true" alt="transport_phenomena" style="width:150px"></a>
  </div>
</div>

-----------------------

<ul id="tools"></ul>

# Tools

## [Standard Atmosphere Calculator](https://kamilazdybal.github.io/standard-atmosphere-calculator/standard-atmosphere-calculator.html)

-----------------------

<ul id="about"></ul>

# About

Hi, I'm Kamila Zdybał and I'm currently a PhD student at Université libre de Bruxelles. Since childhood I loved science and enjoyed inventing my own ways of explaining and understanding things. **Science Docs** is pretty much an aftermath of that - a site that I always wanted to create. When it comes to learning, I believe in the quote of Einstein: *you do not really understand something unless you can explain it to your grandmother*. My aim is to implement that level of understanding into the documents I write - although many times I will assume certain prerequisites that your grandmother should have. Of course, if you wish to profit from the materials presented here you will need to incorporate them in your journey and make it your way. I have hopes that you will find doing science fascinating, rewarding and inspiring!

<img src="https://github.com/kamilazdybal/science-docs/blob/master/_posts/kamila.png?raw=true" alt="about-me" style="width:400px">

<h4><span class="fa fa-twitter"></span><a href="https://twitter.com/kamilazdybal" target="_blank">@kamilazdybal</a></h4>

-----------------------

# Science blog & thoughts

<ul id="blog">
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<sup><a href="/science-docs/#intro">Jump to the top of the page ^</a></sup>

<footer class="site-footer">

  <span class="site-footer-credits">This site uses: <a href="https://github.com/lorepirri/cayman-blog">Cayman Blog Theme</a>  by Lorenzo Pirritano (@lorepirri)  | <a href="https://github.com/lorepirri/cayman-blog/blob/master/LICENSE">Licence</a>: Creative Commons Attribution 1.0 International </span>
</footer>
