---
permalink: /
title: " "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome ! I am a Student in Machine Learning, just graduated from the ENS (Ecole Normale Supérieure) Paris-Saclay and Ecole des Ponts ParisTech with an MSc. in Applied Mathematics, Deep Learning and Computer Vision (**Master MVA**). 

Previously I have done various research internships in Computer Vision. The latest one was in Valeo.ai where I was supervised by [Patrick Perez](http://ptrckprz.github.io): my research focused on developping Driver Monitoring Sytems throuch the analysis of the driver with 3D Pose Estimation.

**I am looking for a 4 to 5-6 months research internship in the field of Vision and Language/Speech models. I am open to work in any place, especially in the UK, Kroea, Japan, Northern Europ, Canada and the US**.

Main Research Interests
======



Courses at MVA Master
======
Here is a list of the different courses I followed during the master:
1. Convex Optimization (A. D'Aspremont, [ Inria PARIS, Sierra team](https://www.di.ens.fr/sierra/)).
2. 3D Computer Vision (P. Monasse and M. Aubry, [Imagine ENPC-LIGM](https://imagine-lab.enpc.fr/)).
3. Object Recognition and Computer Vision (J. Ponce, C. Schmid, I. Laptev, G. Varöl, J. Sivic [Inria PARIS, Willow team](https://www.di.ens.fr/willow/)).
4. Computational Statistics (S. Allassonière).
5. Digital Imaging (Y. Gousseau and J. Delon).
6. Speech and Natural Language Processing (E. Dupoux from FAIR/[Inria PARIS, CoML team]() and B. Sagot [Inria PARIS, Almanach team](http://almanach.inria.fr/)).
7. Deep Learning in Practice (G. Charpiat).
8. Deep Reinforcement Learning (F. Strub, C. from [Deepmind]()).
9. Audio Signal Processing (E. Bacry).
10. Computational Optimal Transport (G.Peyré).



Selected Projects
======
Here are some examples of the projects I have carried out, don't hesitate to click [here](http://victoria-brami.github.io/hobbies/) for more!
There are more to come of course ;)

{% for year in site.data.projects %}
### {{year[0]}}
--------------
{% for paper in year[1] %}
  <div class="row">
    <div class="paper-img">
      <img src="{{ paper.img }}" class="thumbnail" width="200" height="200" />
    </div>
    <div class="paper-text">
      <a href="{{ paper.link }}"><b>{{ paper.title }}</b></a> <span style="font-size:16px;"><i>{{ paper.where }}</i></span><br> 
      <span style="font-size:15px;"><i>{{ paper.authors }}</i></span> <br> 
      <a class="label label-info"> Abstract <span class="abstract">{{ paper.abstract }}</span> </a> &nbsp; 
      {% if paper.code and paper.code != '' %}
        <a href="{{ paper.code }}" class="label label-success">Code</a>
      {% endif %}
      {% if paper.blog and paper.blog != '' %}
        <a href="{{ paper.blog }}" class="label label-danger">Blog</a> 
      {% endif %}
      {% if paper.demo and paper.demo != '' %}
        <a href="{{ paper.demo }}" class="label label-warning">Demo</a>
      {% endif %}
    </div>
  </div>
{% endfor %}
{% endfor %}

<br>
\* Equal contribution as first authors.