---
permalink: /
title: "Welcome!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
--- 

<p style="width:100%;text-align:justify;">Hi there, I am a Student in Machine Learning, just graduated from the ENS (Ecole Normale Supérieure) Paris-Saclay and Ecole des Ponts ParisTech with an MSc. in Applied Mathematics, Deep Learning and Computer Vision (<b>Master MVA</b>). 

Previously I have done various research internships in Computer Vision. The latest one was in Valeo.ai where I was supervised by <a href="http://ptrckprz.github.io" style="width:100%;text-align:justify;">Patrick Perez</a>: my research focused on developping Driver Monitoring Sytems throuch the analysis of the driver with 3D Pose Estimation.</p>

<b style="width:100%;text-align:justify;">I am looking for a 4 to 5-6 months research internship in the field of Vision and Language/Speech models (Text-to-Image Video Generation, Visual QA, align text with videos, etc.). I am open to work in any place, especially in UK, Korea, Japan, Northern Europe, Canada and US.</b>



<p style="width:100%;text-align:justify;">You can also file in details the courses I followed during my master<a href="https://victoria-brami.github.io/courses/"> here</a> and my<a style="width:100%;text-align:justify;" href="https://victoria-brami.github.io/cv/"> resume</a>.</p>
<p style="width:100%;text-align:justify;"></p>

<h1>Selected Projects</h1>
<hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
Here are some examples of the projects I have carried out, do not hesitate to click [on this link](https://victoria-brami.github.io/hobbies/) for more!
There are more to come of course ;).


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
.buttonsRed1 {cursor: pointer; border-radius: 4px; background-color: #DC143C;}
.buttonsGreen1 {border-radius: 4px; background-color: #4CAF50;}
.buttonsBlue1 { width: 4.2em; border-radius: 4px; background-color: #008CBA;}
.buttonsOrange1 { width: 4.2em; border-radius: 4px; background-color: #DC8C14;}
table, th, td {
  border: 0px solid black;
  border-collapse: collapse;
}
date_title {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 22px;
    text-align: left;
}
strong {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
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
/* Publications post css */

.list-work{
  width: 100%;
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


<body>
<date_title><b style="color:#069;">2022</b></date_title>
  <hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
<div class="list-work">
      <a href="">
        <img src="../images/vp11_3_test_visual_single.gif"> <!-- Image is mandatory for publications -->
      </a>
      <span>
      <p><a href="https://victoria-brami.github.io">
      <papertitle>3D Pose Estimation for Driver Monitoring</papertitle></a><br>
      Victoria Brami,  <strong>Patrick Pérez</strong>, Renaud Marlet and Souhaiel Khalfaoui.<br>
      <em>Valeo AI Research Internship Project</em>, April-September 2022 <strong>(Oral).</strong><br>
      <p align=justify> 
      </p>
<div class="buttons buttonsBlue1">
<buttons id="toDemoButton" class="float-left submit-button" title="Each year, almost 20 000 people die in Europe's roads in car accidents. Driver's distraction accounts for 20% of them. We propose to investigate the best 3D Driver Realtime Pose Estimation for action recognition purpose and understand car passengers needs. This is an opportunity for the automotive industry since driver and interior monitoring systems (DMS and IMS), which require the detailed understanding of a car’s passengers typically with a single camera, are gaining more importance every day. Systems that detect driver’s drowsiness or distraction are already deployed in numerous vehicles, and will continue to expand as new laws make them mandatory.">Abstract</buttons>
</div>
<div class="buttons buttonsRed1">
<buttons id="toPdfButton" class="float-left submit-button" >Report</buttons>
</div>
<script type="text/javascript">
    document.getElementById("toPdfButton").onclick = function () {
        location.href = "../files/reports/report_mva_valeo.pdf";
    };
</script>
<div class="buttons buttonsGreen1">
<buttons id="toCodeButton" class="float-left submit-button" >Code</buttons>
</div>
<script type="text/javascript">
    document.getElementById("toCodeButton").onclick = function () {
        location.href = "https://github.com/victoria-brami/pose_estimation_benchmark.git";
    };
</script>
<div class="buttons buttonsOrange1">
    <buttons id="toSlidesButton" class="float-left submit-button" >Slides</buttons>
    </div>
    <script type="text/javascript">
        document.getElementById("toCodeButton").onclick = function () {
            location.href = "../files/slides/valeoai_presentation.pdf";
        };
  </script> <p align=justify> 
      </p><br><br><br>
<div class="list-work">
      <a href="">
        <img src="../images/celebA_inpainting.gif"> <!-- Image is mandatory for publications -->
      </a>
      <span>
      <p><a href="https://victoria-brami.github.io">
      <papertitle>Face Inpainting with GANs: An ablation study</papertitle></a><br>
      Victoria Brami, Claring Vongpaseut, <i>Supervised by Yann Gousseau</i>.<br>
      <em>MSc. Research Project</em>, Jan.-Feb. 2022 <strong>(Oral).</strong><br>
       <div class="buttons buttonsRed1">
    <buttons id="toPdfButton" class="float-left submit-button" >Report</buttons>
    </div>
    <script type="text/javascript">
        document.getElementById("toPdfButton").onclick = function () {
            location.href = "../files/reports/Inpainting_project.pdf";
        };
    </script>
    <div class="buttons buttonsGreen1">
    <buttons id="toCodeButton" class="float-left submit-button" >Code</buttons>
    </div>
    <script type="text/javascript">
        document.getElementById("toCodeButton").onclick = function () {
            location.href = "https://github.com/victoria-brami/mva_inpainting_project.git";
        };
  </script>
  <div class="buttons buttonsOrange1">
    <buttons id="toSlidesButton" class="float-left submit-button" >Slides</buttons>
    </div>
    <script type="text/javascript">
        document.getElementById("toCodeButton").onclick = function () {
            location.href = "../slides/Inpainting_presentation.pdf";
        };
  </script>
      <p align=justify> 
      </p><br><br>
<date_title><b style="color:#069;">2021</b></date_title>
  <hr style="border:1px solid #d3d3d3;width:100%;text-align:left;margin-left:0">
  <div class="list-work">
      <a href="">
        <img src="../images/speech_evaluation_pipeline.JPG">
      </a>
      <span>
      <p><a href="https://victoria-brami.github.io">
      <papertitle>Comparing Speech Models to Human Perception</papertitle></a><br>
       Victoria Brami,  <strong>Juliette Millet</strong>, Ewan Dunbar and Emmanuel Dupoux<br>
      <em>CoML research project</em>, March-July 2021 <strong>(Oral)</strong><br>
      <p align=justify> 
      </p>
  <div class="buttons buttonsBlue1">
  <buttons id="toDemoButton" class="float-left submit-button" title="What happens in the brain when humans perceive speech? We lay the ground for a new and expansive field of research aimed at reproducing human speech perception behaviour, by developing easy-to-use reference data and evaluation tools. In short, just as the past half-century has developed and tested thousands of speech perception experiments on human listeners, we develop a set of 'speech perception experiments for machines,' in order to find and close the gap between human and machine.">Abstract</buttons>
  </div>
  <div class="buttons buttonsRed1">
  <buttons id="toPdfButton" class="float-left submit-button" >PDF</buttons>
  </div>
  <script type="text/javascript">
      document.getElementById("toPdfButton").onclick = function () {
          location.href = "https://victoria-brami.github.io";
      };
  </script>
  <div class="buttons buttonsGreen1">
  <buttons id="toCodeButton" class="float-left submit-button">Code</buttons>
  </div>
  <script type="text/javascript">
      document.getElementById("toCodeButton").onclick = function () {
          location.href = "https://github.com/victoria-brami/pose_estimation_benchmark.git";
      };
  </script><br><br>
    <p align=justify> 
      </p><br><br>
  <a style="text-align:center;font-size:22;" href="https://victoria-brami.github.io/projects/">Click here to see more projects</a>
