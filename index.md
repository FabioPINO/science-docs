---
title: Main page
layout: default
---
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

# Science Docs

### Motivation

> À force de croire en ses rêves, l’homme en fait une réalité.  
__*Hergé*__

### Idea

This site is a collection of **projects**, **tutorials** and **study notes** aimed for explorers and experimenters who are willing to study scientific or engineering subjects with what Richard Feynman called: *"the pleasure of finding things out"*.

# Projects

### Objectif Morse

In the **Objectif Morse** project you will learn basics of `Arduino` and `C++` while transmitting messages in Morse alphabet between computers.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/objectif_morse/raw/master/Documentation/Objectif_Morse.pdf"> PDF tutorial</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/objectif_morse"> GitHub repository</a></span>

# Study notes

### Short Training Programme at the von Karman Institute for Fluid Dynamics

As a stagiaire at the von Karman Institute I studied two data decomposition methods: **Proper Orthogonal Decomposition** and **Dynamic Mode Decomposition**. Using POD and DMD within `Matlab` scripts, I approximated velocity profile in the pulsating Poiseuille flow and the velocity field in the flow behind a cylinder. I developed GUI to perform data decomposition.

I wrote my final report with the aim that it will be an educational tool, collecting the knowledge I gained for future students.

<span class="fa fa-file-pdf-o"><a href="https://github.com/camillejr/vki_short_training/raw/master/final_report/stagiaire_report_kzdybal.pdf"> PDF final report</a></span>

<span class="fa fa-github"><a href="https://github.com/camillejr/vki_short_training"> GitHub repository</a></span>

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
