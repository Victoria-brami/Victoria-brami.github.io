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
<p>Halò/Hi there, 
My name is Victoria (ビクトリア), I work as a Vision-LLM engineer in <b>Woven by Toyota</b>, and I am based in Tokyo. I am part of the Perception Team led by Wadim Kehl. I am mainly interested in studying and solving ML problems on interdiscplinary domains: these problems involve among others <b>Multimodal Learning (Vision-Audio-Language)</b> and <b>Cognitive Science</b>.<br><br>

I spent one year as a Visiting Student then a research assistant in Cognitive Science and Natural Language Processing at the University of Edinburgh, in <b><a href="https://homepages.inf.ed.ac.uk/keller/" style="text-decoration:none;">Frank Keller's Group</a></b>. My research focused on exploring <b>diffusion models</b> capabilities to decode non-invasive brain signals to text and representation learning of those brain signals.
I graduated from the ENS (Ecole Normale Supérieure) Paris-Saclay and Ecole des Ponts ParisTech with an MSc. in Applied Mathematics, Deep Learning and Computer Vision (<b>Master MVA</b>).<br><br>
Before that, I did various research internships in Computer Vision. The latest one was in Valeo.ai where I was supervised by <a href="http://ptrckprz.github.io">Patrick Perez</a>: my research focused on developping Driver Monitoring Sytems through the analysis of the driver with 3D Pose Estimation.
You can also find in details the courses I followed during my master <a href="https://victoria-brami.github.io/courses/">here</a> and my <a href="https://victoria-brami.github.io/cv/">resume</a>.<br><br>

Alongside my work, I develop with a friend <b><a href="#" style="text-decoration:none;">Nepthune</a></b>. Nepthune an online platform which draws up a list of all the scholarships accessible to students in France and shortlists automatically the best candidates to those fellowships. Through Nepthune, our goal is to tackle the ineauqlity of opportunities in Higher Education!
</p>


Feel free to reach out or drop me an email if you would like to chat!<br><br>

<img src="{{base_path}}/files/gym_video.gif" alt="Computer man" style="margint-left:auto;margin-right:;auto;align:center;width:800px;">


<h1>News</h1>
<ul style="list-style-type:none;">
    <li><span class="badge secondary">2024.11</span> After a wonderful year spent a the University of Edinburgh, I finally decided to go to the industry in Woven by Toyota in Tokyo, as an LLM engineer to develop the next generation of smart cars. </li>
    <li><span class="badge primary">2023.07</span> Nepthune was awarded an <a href="https://www.fondationdesponts.fr/prix-dencouragement-a-lentrepreneuriat-2023/">Entrepreneurship Prize</a> of 3k euros!</li>
    <li><span class="badge secondary">2023.07</span> Starting a research internship at the University of Edinburgh!</li>
    <li><span class="badge">2022.11</span> Graduated from the MVA master</li>
    <li><span class="badge secondary">2022.04</span> Starting an internship in Valeo AI Paris team.</li>
    <li><span class="badge primary">2022.04</span> Launch of Nepthune Project </li>
</ul><br><br>

<h1>Selected Projects</h1>
<date_title><b>2024</b></date_title>
<hr style="border:1px solid #d3d3d3;text-align:left;margin-left:0">
{% for post in site.portfolio reversed %}
  {% include archive-single-internship.html %}<br>
{% endfor %}
<p align=justify></p>
<br>
<date_title><b>2022</b></date_title>
<hr style="border:1px solid #d3d3d3;text-align:left;margin-left:0">
{% for post in site.projects reversed %}
  {% include archive-single-internship.html %}<br><br>
{% endfor %}
<p align=justify></p>
<br>
<date_title><b>2021</b></date_title>
<hr style="border:1px solid #d3d3d3;text-align:left;margin-left:0">
{% for post in site.publications reversed %}
  {% include archive-single-internship.html %}
{% endfor %}

</div>

