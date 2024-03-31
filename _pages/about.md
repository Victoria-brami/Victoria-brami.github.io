---
permalink: /
title: "Victoria Brami"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
header-img : /images/iceland_travel.JPG
--- 

{% include about_style.html %}




<div class="justified-text">
<p>Hi there, I am a Visiting Student in Cognitive Science and Natural Language Processing at the University of Edinburgh, in <b><a href="https://homepages.inf.ed.ac.uk/keller/" style="text-decoration:none;">Frank Keller's Group</a></b>. I work there on brain decoding using <b>diffusion models</b>.
I just graduated from the ENS (Ecole Normale Supérieure) Paris-Saclay and Ecole des Ponts ParisTech with an MSc. in Applied Mathematics, Deep Learning and Computer Vision (<b>Master MVA</b>).<br>
Previously I have done various research internships in Computer Vision. The latest one was in Valeo.ai where I was supervised by <a href="http://ptrckprz.github.io">Patrick Perez</a>: my research focused on developping Driver Monitoring Sytems through the analysis of the driver with 3D Pose Estimation.
You can also find in details the courses I followed during my master <a href="https://victoria-brami.github.io/courses/">here</a> and my <a href="https://victoria-brami.github.io/cv/">resume</a>.<br>

I am looking for a PhD starting in Spring-Summer 2024, with a deep interest in <b>Multimodal Learning (Vision-Audio-Language)</b> and <b>Cognitive Science</b>. Feel free to reach out or drop me an email if you would like to chat!<br><br>
Alongside my work, I develop with a friend <b><a href="#" style="text-decoration:none;">Nepthune</a></b>. Nepthune an online platform which draws up a list of all the scholarships accessible to students in France and shortlists automatically the best candidates to those fellowships. Through Nepthune, our goal is to tackle the inequality of opportunities in Higher Education!
<br><br>
Outside of work, I love practicing all kinds of sports, especially gymnastics, climbing, basketball, hip hop, and skateboarding. I also enjoy long hikes in Scottish highlands.


</p>

<figure>
<img src="{{base_path}}/files/gym_video.gif" alt="Computer man" style="margint-left:auto;margin-right:;auto;align:center;width:800px;">
<figcaption style="text-align:center;">Random Gymnastics session, generated with MotionBERT</figcaption>
</figure>



<h1>News</h1>
<ul style="list-style-type:none;">
    <li><span class="badge secondary">2024.02</span> Extending my stay in the wonderful city of Edinburgh!</li>
    <li><span class="badge">2023.12</span> Finally graduated from my second master at Ecole des Ponts ParisTech</li>
    <li><span class="badge primary">2023.07</span> Nepthune was awarded an <a href="https://www.fondationdesponts.fr/prix-dencouragement-a-lentrepreneuriat-2023/">Entrepreneurship Prize</a> of 3k euros!</li>
    <li><span class="badge secondary">2023.07</span> Starting a research internship at the University of Edinburgh!</li>
    <li><span class="badge">2022.11</span> Graduated from the MVA master</li>
    <li><span class="badge secondary">2022.04</span> Starting an internship in Valeo AI Paris team.</li>
    <li><span class="badge primary">2022.04</span> Launch of Nepthune Project </li>
</ul><br><br>

<h1>Selected Projects</h1>
<date_title><b>2022</b></date_title>
<hr style="border:1px solid #d3d3d3;text-align:left;margin-left:0">
{% for post in site.projects reversed %}
  {% include archive-single-internship.html %}<br>
{% endfor %}
<p align=justify></p>
<br>
<date_title><b>2021</b></date_title>
<hr style="border:1px solid #d3d3d3;text-align:left;margin-left:0">
{% for post in site.publications reversed %}
  {% include archive-single-internship.html %}
{% endfor %}

</div>

