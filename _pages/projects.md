---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
---

{% if site.talkmap_link == true %}
<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>
{% endif %}

{% include base_path %}

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

<hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
<date_title>2022</date_title>
    <hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
{% for post in site.projects reversed %}
  {% include archive-single-internship.html %}
 <!-- {% include archive-single-project.html %} -->
{% endfor %}

<br><br>

<date_title>2021</date_title>
    <hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
{% for post in site.publications reversed %}
  {% include archive-single-internship.html %}
 <!-- {% include archive-single-project.html %} -->
{% endfor %}
