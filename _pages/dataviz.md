---
permalink: /dataviz
author_profile: true
---
<style>

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 3px;
}

/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 33%; /* IE10 */
  flex: 33%;
  max-width: 33%;
  padding: 0 3px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}

.container {
  position: relative;
  width: 100%;
}



.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color: #008CBA;
}

.container:hover .overlay {
  opacity: 1;
}

.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
}

.container .articleLink {
    opacity: 0;
    position: absolute;
    top:50%;
    bottom: 50%;
    left: 50%
    right: 50%;
    color: #c85299;
    background: #ffffff;
    text-decoration: none;
    text-align: center;
    -webkit-transition: opacity 500ms;
    -moz-transition: opacity 500ms;
    -o-transition: opacity 500ms;
    transition: opacity 500ms;

}
.container:hover .articleLink {
    opacity: 0.8;
}
.container .codeLink {
    opacity: 0; 
    position: absolute;
    top:60%;
    bottom: 40%;
    left: 50%
    right: 50%;
    color: #171516;
    background: #ffffff;
    text-decoration: none;
    text-align: center;
    -webkit-transition: opacity 500ms;
    -moz-transition: opacity 500ms;
    -o-transition: opacity 500ms;
    transition: opacity 500ms;

}
.container:hover .codeLink {
    opacity: 0.8;
}
</style>

<body>
**Data visualization portfolio**

<div class = "row">

<div class = "column">
<div class="container">
  <img src="https://zmeers.github.io/images/agtech_all.gif">
      <a href="https://www.ussc.edu.au/analysis/isolated-agtech-in-Australia-a-social-network-analysis-of-an-innovative-sector" class="articleLink" style="font-weight:bold;font-size:15">Isolated Agtech in Australia: a social network analysis</a>
      <a href="https://github.com/USStudiesCentre/linkedin_analysis" class="codeLink">View code here</a>
</div>
</div>

<div class = "column">
<div class="container">
  <img src="https://zmeers.github.io/images/midterms_all.gif">
      <a href="https://www.ussc.edu.au/analysis/explainer-midterm-election-seats-in-play" class="articleLink" style="font-weight:bold;font-size:15">Midterm election seats in play</a>
      <a href="https://github.com/USStudiesCentre/midterms-analysis/tree/master/seats_in_play" class="codeLink">View code here</a>
</div>
</div>

<div class = "column">
<div class="container">
  <img src="https://zmeers.github.io/images/women_candidates_all.gif">
      <a href="https://www.ussc.edu.au/analysis/women-candidates-in-the-midterm-elections" class="articleLink" style="font-weight:bold;font-size:15">Women candidates in the midterm elections</a>
      <a href="https://github.com/USStudiesCentre/midterms-analysis/tree/master/women_candidates" class="codeLink">View code here</a>
</div>
</div>



</div>


</body>

