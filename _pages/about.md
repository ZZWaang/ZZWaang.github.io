---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .page__content {
    font-size: 0.9em;
  }
</style>

<h3 style="padding-top: 0; margin-top: 0; 0; margin-bottom: 0.5em; font-size: 1.1em; color: #094480">About Me</h3>

I am a Postdoctoral Researcher at the [Courant Institute of Mathematical Sciences](https://cims.nyu.edu/) at [New York University](https://nyu.edu/), working with [Prof. Yann LeCun](http://yann.lecun.com/) on world models for music. I also hold a visiting affiliation with the Computer Science Department at [MBZUAI](https://mbzuai.ac.ae/). 

Prior to that, I received my PhD in Computer Science from New York University, where I worked on the intersection of music and machine learning under the guidance of [Prof. Gus Xia](http://www.musicxlab.com/members/gus/) in [Music X Lab](http://www.musicxlab.com). During my PhD, I was also a visiting researcher at the Machine Learning Department at MBZUAI and affiliated with [NYU Shanghai](https://shanghai.nyu.edu/). In 2019, I earned my undergraduate degree in Mathematics from [Fudan University](https://www.fudan.edu.cn/en/). Beyond my academic pursuits, I am a passionate conductor, pianist, and Erhu (a traditional Chinese string instrument) player. I have previously served as the conductor of the NYU Shanghai Jazz Ensemble and as the director of the Fudan Musical Club.

<div style="margin: 1.5em 0; color: #c62828; font-family: Verdana, Geneva, sans-serif; font-weight: 400; font-style: italic; line-height: 1.35;">
  <p style="margin: 0 0 0.3em;"><strong>News:</strong> I will join MBZUAI as an Assistant Professor in January 2027! I am recruiting <strong>talented PhD and MSc students</strong> interested in Music AI and broader questions around building human-level intelligence.</p>
  <p style="margin: 0;">Prospective students at MBZUAI (and potentially NYU) and collaborators worldwide are welcome to reach out!</p>
</div>

<h3 style="padding-top: 0; margin-top: 0; 0; margin-bottom: 0.5em; font-size: 1.1em; color: #094480">Research Interest</h3>

People often imagine an emotional and human-like AI. In my research, I translate this vision into the music domain as the challenge of building _machine musicianship_. Music is one of the most subtle forms of human expression, full of nuanced intentions that are deeply felt yet often difficult to articulate. If a machine, rigorous by nature, were to express such intentions, what would that process look like? Could it perceive rather than process? Could it compose rather than imitate? Could it formalize what we ourselves find vague, to reveal something that makes music resonate more deeply across the world? 

In response to these questions, my research explores _how intelligent systems can analyze and create music in more human-like ways_. I focus on the emergence of musical concepts and hierarchical structures from data, and how such representations can support automatic composition and enable interactive creation. My work spans self-supervised learning, hierarchical modeling, large language models (LLMs), representation learning, disentanglement, style transfer, computer music, and human–computer interaction (HCI).

Here is a brief overview of my research, organized by topic:

<h3 style="text-align: center;">Hierarchical Music Generation & Arrangement</h3>
<div class="project">
  <div class="project-image">
    <img src="assets/img/whole-song.png" alt="Project Image">
  </div>
  <div class="project-content">
    <!-- <h3>Hierarchical Music Generation & Arrangement</h3> -->
    <ul>
    <li>Whole-song generation via <strong>compositional hierarchy</strong></li>
    <li style="list-style-type: none;">
      [<a href="https://openreview.net/forum?id=sn7CYWyavh" target="_blank">WholeSongGen</a>]
    </li>
    <li>Modeling long-term context dependency</li>
      <li style="list-style-type: none;">
      [<a href="https://nips.cc/virtual/2024/poster/95545" target="_blank">AccomontageIII</a>][<a href="https://ieeexplore.ieee.org/document/10096446" target="_blank">Mixed-level Inpainting</a>]
    </li>
    <li>Dataset</li>
      <li style="list-style-type: none;">
      [<a href="https://archives.ismir.net/ismir2020/paper/000089.pdf" target="_blank">POP909</a>]
    </li>
    </ul>
  </div>
</div>


<h3 style="text-align: center;">Representation Learning</h3>
<div class="project">
  <div class="project-image">
    <img src="assets/img/repr-dis1.png" alt="Project Image">
  </div>
  <div class="project-content">
    <!-- <h3>Representation Learning</h3> -->
    <ul>
    <li>Representation Disentanglement: monophonic & polyphonic</li>
    <li style="list-style-type: none;">
      [<a href="https://archives.ismir.net/ismir2019/paper/000072.pdf" target="_blank">EC2-VAE</a>][<a href="https://archives.ismir.net/ismir2020/paper/000094.pdf" target="_blank">Poly-Dis</a>]
    </li>
    <li>Cross-modality representation: audio & text</li>
      <li style="list-style-type: none;">
      [<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9747884" target="_blank">Audio2Midi</a>][<a href="https://aclanthology.org/2020.nlp4musa-1.11.pdf" target="_blank">BUTTER</a>]
    </li>
    </ul>
  </div>
</div>


<h3 style="text-align: center;">Unsupervised Concept Emergence</h3>
<div class="project">
  <div class="project-image">
    <img src="assets/img/v3.png" alt="Project Image">
  </div>
  <div class="project-content">
    <!-- <h3>Unsupervised Concept Emergence</h3> -->
    <ul>
    <li>Learning content & style via variability constraints</li>
    <li style="list-style-type: none;">
      [<a href="https://arxiv.org/abs/2407.03824" target="_blank">V3</a>]
    </li>
    <li>Unsupervised modeling of music structure</li>
      <li style="list-style-type: none;">
      [<a href="https://github.com/ZZWaang/PianoTree-VAE" target="_blank">PianoTree-VAE</a>][<a href="https://archives.ismir.net/ismir2021/paper/000090.pdf" target="_blank">MuseBERT</a>]
    </li>
    </ul>
  </div>
</div>


<h3 style="text-align: center;">Music Co-creation & Education</h3>
<div class="project">
  <div class="project-image">
    <img style="width: 100%;  margin-left: 0%;  margin-right: 0%;" src="assets/img/me-and-teo.png" alt="Project Image">
  </div>
  <div class="project-content">
    <!-- <h3>Music Co-creation & Education</h3> -->
    <ul>
    <li>Controllable Music Generation</li>
    <li style="list-style-type: none;">
      [<a href="https://www.youtube.com/watch?v=jjr2gDgzrMg" target="_blank">Teo1</a>][<a href="https://youtu.be/YmGdjIdHEQ4" target="_blank">Teo2</a>][<a href="https://youtu.be/bteuPnpHNx8" target="_blank">Teo3</a>][<a href="https://www.youtube.com/watch?v=Ahfk0hvpCzM&t=3316s" target="_blank">Live</a>]
    </li>
    <li>Music Education Interface</li>
      <li style="list-style-type: none;">
      [<a href="https://www.youtube.com/watch?v=Ahfk0hvpCzM&t=3163s" target="_blank">Live</a>][<a href="https://youtu.be/NN4bKA8f3v4" target="_blank">StyleWheel</a>]
    </li>
    </ul>
  </div>
</div>
