---
layout: post
title: Product Experiments
---

<style>
    /* The flip box container - set the width and height to whatever you want. We have added the border property to demonstrate that the flip itself goes out of the box on hover (remove perspective if you don't want the 3D effect */
.flip-box {
  background-color: transparent;
  width: 300px;
  height: 200px;
  border: 1px solid #f1f1f1;
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
  text-align: center;
}

/* This container is needed to position the front and back side */
.flip-box-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

/* Do an horizontal flip when you move the mouse over the flip box container */
.flip-box:hover .flip-box-inner {
  transform: rotateX(180deg);
}

/* Position the front and back side */
.flip-box-front, .flip-box-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

/* Style the front side */
.flip-box-front {
  background-color: #ffe9b7;
  color: black;
}

/* Style the back side */
.flip-box-back {
  background-color: #6b98ff;
  color: white;
  transform: rotateX(180deg);
}



.project-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    padding: 20px;
}

.flip-box {
    flex: 0 1 300px;
    margin: 10px;
}

a, a:link, a:visited, a:hover, a:active {
    color: white;
    text-decoration: none;
    transition: color 0.3s ease;
}

a:hover {
    color: darkblue;
    text-decoration: underline;
}

</style>

<div class="project-container">


<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <h2>Zeke</h2>
      <h4> AI Powered Platform for Job Seekers </h4>
    </div>
    <div class="flip-box-back">
      <h3><a href="https://zeke.so/" target="_blank"> Visit </a></h3>
      <h3><a href="https://youtu.be/Xq8N4Jddtm0?si=TCaDzpbkSGcZq7AI" target="_blank"> View Demo </a></h3>
    </div>
  </div>
</div>


<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <h2>Zapplink</h2>
      <h4> Easier way to collect and share links. </h4>
    </div>
    <div class="flip-box-back">
      <h3><a href="https://www.zappl.ink/" target="_blank"> Visit </a></h3>
      <h3><a href="https://youtu.be/CpbARxf_WJ0" target="_blank"> View Demo </a></h3>
    </div>
  </div>
</div>


<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <h2>Udaivi</h2>
      <h4> Easier way to collect and share links. </h4>
    </div>
    <div class="flip-box-back">
      <h3><a href="https://udaivi.framer.website/" target="_blank"> Visit </a></h3>
      <h3><a href="https://youtu.be/C5k3jRC7JjM" target="_blank"> View Demo </a></h3>
    </div>
  </div>
</div>


<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <h2>Review Analyzer</h2>
      <h4> Analyze Product Reviews with AI.</h4>
    </div>
    <div class="flip-box-back">
     <h3><a href="https://citool.streamlit.app/" target="_blank"> Visit </a></h3> 
        <!--<h3><a href="https://youtu.be/C5k3jRC7JjM" target="_blank"> View Demo </a></h3> -->
    </div>
  </div>
</div>
