---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% if site.talkmap_link == true %}
<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>
{% endif %}



<head>
  <style>
    date_title {
      font-family: 'Lato', Verdana, Helvetica, sans-serif;
      font-size: 20px;
      text-align: left;
      color: #069;
  }
  </style>
</head>

<body>
<hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
<br>
<date_title><b>2022</b></date_title>
    <!-- <hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">-->
{% for post in site.talks reversed %}
  {% include archive-single-internship.html %}
 <!-- {% include archive-single-project.html %} -->
{% endfor %}
<p align=justify></p>
<p align=justify></p>
<br>
<date_title><b>2021</b></date_title>
    <hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
{% for post in site.publications reversed %}
  {% include archive-single-internship.html %}
 <!-- {% include archive-single-project.html %} -->
{% endfor %}

