---
permalink: /
title: "Welcome !"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
header-img : /images/iceland_travel.JPG
--- 

<head>
<style>
.buttons {
  background-color: #04AA6D;
  border: none;
  color: white;
  width: 3.7em;
  padding: 0 0em;
  height: 1.5em;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  cursor: pointer;
  margin: 4px 6px;
  color: white;
}
.buttonsRed1 { width: 4.2em; cursor: pointer; border-radius: 4px; background-color: #9A132A;}
.buttonsGreen1 { width: 4.2em; border-radius: 4px; background-color: #228844;}
.buttonsBlue1 { width: 4.2em; border-radius: 4px; background-color: #008CBA;}
.buttonsOrange1 { width: 4.2em; border-radius: 4px; background-color: #BBA333;}
table, th, td {
  border: 0px solid black;
  border-collapse: collapse;
}
date_title {
      font-family: 'Lato', Verdana, Helvetica, sans-serif;
      font-size: 24px;
      text-align: left;
      color: #069;
  }
strong {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 18px;
    }
heading {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 22px;
}
papertitle {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 18px;
    font-weight: bold;
}
name {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 32px;
    }
.one
    {
    width: 160px;
    height: 160px;
    position: relative;
    }
.two
    {
    width: 160px;
    height: 160px;
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
    }
.fade {
     transition: opacity .2s ease-in-out;
     -moz-transition: opacity .2s ease-in-out;
     -webkit-transition: opacity .2s ease-in-out;
    }
span.highlight {
        background-color: #ffffd0;
    }

.list-work {
        width: 120%;
    }

.list-work img {
        -webkit-transition: -webkit-transform 0.35s;
        transition: -webkit-transform 0.35s;
        -o-transition: transform 0.35s;
        vertical-align: middle;
        transition: transform 0.35s;
        transition: transform 0.35s, -webkit-transform 0.35s;
        object-fit: contain;
        background-color: white;
        width: 300px;
        height: 225px;
        margin: 10px;
        vertical-align: middle;
        float: left;
    }

.list-work img:hover {
        -webkit-transform: scale3d(0.9, 0.9, 1);
                transform: scale3d(0.9, 0.9, 1);
    }
</style>
</head>

<p style="width:120%;text-align:justify;">Hi there, I am a Student in Machine Learning, just graduated from the ENS (Ecole Normale Supérieure) Paris-Saclay and Ecole des Ponts ParisTech with an MSc. in Applied Mathematics, Deep Learning and Computer Vision (<b>Master MVA</b>).</p>

<p style="width:120%;text-align:justify;">Previously I have done various research internships in Computer Vision. The latest one was in Valeo.ai where I was supervised by <a href="http://ptrckprz.github.io" style="width:120%;text-align:justify;">Patrick Perez</a>: my research focused on developping Driver Monitoring Sytems through the analysis of the driver with 3D Pose Estimation.</p>

<p style="width:120%;text-align:justify;"><b>I am looking for a 4 to 5-6 months research internship in the field of Vision and Language/Speech models (Text-to-Image Video Generation, Visual QA, align text with videos, etc.). I am open to work in any place, especially in UK, Korea, Japan, Northern Europe, Canada and US.</b></p>



<p style="width:120%;text-align:justify;">You can also find in details the courses I followed during my master<a href="https://victoria-brami.github.io/courses/"> here</a> and my<a style="width:120%;text-align:justify;" href="https://victoria-brami.github.io/cv/"> resume</a>.</p>
<p style="width:120%;text-align:justify;"></p>

<h1 style="width:120%;text-align:justify;">Selected Projects</h1>
<hr style="border:1px solid #d3d3d3;width:120%;text-align:left;margin-left:0">
<p style="width:120%;text-align:justify;">Here are some examples of the projects I have carried out, do not hesitate to click [on this link](https://victoria-brami.github.io/hobbies/) for more!
There are more to come of course ;).</p>


<hr style="border:1px solid #d3d3d3;width:120%;text-align:left;margin-left:0">
<br>
<date_title><b>2022</b></date_title>
<hr style="border:1px solid #d3d3d3;width:120%;text-align:left;margin-left:0">
{% for post in site.projects reversed %}
  {% include archive-single-internship.html %}
 <!-- {% include archive-single-project.html %} -->
{% endfor %}
<p align=justify></p>
<p align=justify></p>
<br>
<date_title><b>2021</b></date_title>
<hr style="border:1px solid #d3d3d3;width:120%;text-align:left;margin-left:0">
{% for post in site.publications reversed %}
  {% include archive-single-internship.html %}
 <!-- {% include archive-single-project.html %} -->
{% endfor %}

