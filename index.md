---
title: Main page
layout: default
---
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

# Science Docs

Hello explorer and experimenter, welcome to **Science Docs**! Or as Python would say:

{% highlight python %}
print("Howdy, Universe!")
{% endhighlight %}

### I have a dream...

> À force de croire en ses rêves, l’homme en fait une réalité.  
__*Hergé*__

**Science Docs** is a collection of **projects**, **tutorials** and **study notes** that are the product of most of my passion that I have for life, Universe and everything else. They are aimed for explorers and experimenters who are willing to study scientific or engineering subjects with what Richard Feynman called: *"the pleasure of finding things out"*.

I have a dream that the PDFs will enrich your journey through learning.

(For (a bit) less scientific works, check out the watercolours section if you feel like!)

# Projects

### Objectif Morse

In the **Objectif Morse** project you will learn the basics of `Arduino` and `C++` while transmitting messages in Morse alphabet between computers.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/objectif_morse/raw/master/Documentation/Objectif_Morse.pdf"> PDF tutorial</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/objectif_morse"> GitHub repository</a></span>

### Cooking water

This small home experiment was for deriving the temperature vs. time curve for cooking water on three types of stoves: electrical, induction and gas.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/home_experiments/raw/master/stoves/Stoves.pdf"> PDF tutorial</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/home_experiments/tree/master/stoves"> GitHub repository</a></span>

# Tutorials

### Computational examples in transport phenomena with Python

I have recently completed two amazing courses offered through edX by Delft University: **The Basics of Transport Phenomena** and **Advanced Transport Phenomena**. I have decided to collect the most interesting computational examples in a form of a tutorial and create a set of Python codes to accompany a better understanding of the results.

This tutorial is still under construction.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/fluid_mechanics/raw/master/Transport_Phenomena/computational_examples.pdf"> PDF tutorial</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/fluid_mechanics/tree/master/Transport_Phenomena"> GitHub repository</a></span>

# Study notes

### POD and DMD decomposition of numerical and experimental data

In the summer of 2016 I was a stagiaire at the von Karman Institute for Fluid Dynamics in Belgium. I studied two data decomposition methods: **Proper Orthogonal Decomposition** and **Dynamic Mode Decomposition**. Using concepts from linear algebra and dynamical systems within `Matlab` scripts I approximated velocity profile in the pulsating Poiseuille flow and the velocity field in the flow behind a cylinder.

I wrote my final report with the aim that it will be an educational tool, collecting the knowledge I gained for future students.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/vki_short_training/raw/master/final_report/stagiaire_report_kzdybal.pdf"> PDF final report</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/vki_short_training"> GitHub repository</a></span>

# Watercolours

### Thought process in watercolours

In this document I present how I apply the thought process to improve my watercolour paintings.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/learning_to_draw_and_paint/raw/master/self_feedback.pdf"> PDF tutorial</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/learning_to_draw_and_paint"> GitHub Watercolour repository</a></span>

# Posts

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
