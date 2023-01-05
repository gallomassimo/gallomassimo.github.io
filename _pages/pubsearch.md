---
title: "Publications"
layout: single
classes: wide
author_profile: true
permalink: /pubsearch/
---



##### 2022
{% bibliography --query @*[year=2022] %}
##### 2021
{% bibliography --query @*[year=2021] %}
##### 2020
{% bibliography --query @*[year=2020] %}
##### 2019
{% bibliography --query @*[year=2019] %}
##### 2018
{% bibliography --query @*[year=2018] %}
##### 2017
{% bibliography --query @*[year=2017] %}
##### 2016
{% bibliography --query @*[year=2016] %}
#### 2015
{% bibliography --query @*[year=2015] %}
##### 2014
{% bibliography --query @*[year=2014] %}
##### 2013
{% bibliography --query @*[year=2013] %}
##### 2012
{% bibliography --query @*[year=2012] %}
##### 2011
{% bibliography --query @*[year=2011] %}
##### 2009
{% bibliography --query @*[year=2009] %}




<script>
  dets=document.getElementsByName("det");
  console.log(5+1);
  for(let i = 0; i < dets.length; i++) {
    dets[i].addEventListener("toggle", (event) => {
      if (dets[i].open) {
        dets[i].style.display = "block";
      }
      else{
        dets[i].style.display = "inline-block"; 
      }
    });
   }
</script>