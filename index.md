---
permalink: /
title: "Massimo Gallo"
layout: single
header:
  overlay_image: /assets/images/cloud.png
author_profile: true
classes: wide
search: true
---
### <i class="fas fa-newspaper" style="color: #0760e6"> News </i>

<ul  style="list-style-type:none;">
{% for post in site.posts limit:5 %}
  <li> <a href="{{ post.url }}"><b>{{ post.date | date: "%Y-%m" }}:</b> {{ post.title }}</a> </li>
{% endfor %}
</ul>

### <i class="fas fa-address-card" style="color: #0760e6"> Bio </i>

Massimo Gallo is a Principal Engineer at Huawei Technologies Co.,Ltd in Paris since 2019. He obtained the Ph.D. in Networks and computer science from Telecom ParisTech, Paris, France in 2012, performing his graduate research at Orange Labs, France Telecom, Paris, France. He spent six years as a researcher at BellLabs, Nokia working on Information Centric Networking and High-speed packet processing. His work has been published in several top tier international conferences (e.g., IEEE ICNP, Usenix ATC, ACM CoNEXT) and journals (e.g., Transaction on Networking) and led to several patents. 

His main research interests are on the performance evaluation, simulation, design and experimentation on networked systems with particular focus on Programmable networks, Traffic generation, and Network Monitoring.

### <i class="fas fa-briefcase" style="color: #0760e6"> Experience </i>

* **2019 to \- Principal researcher, Huawei, Paris (FR).** Network monitoring (team leader since 2021); 
* **2013 to 2019 Research Engineer, Nokia Bell Labs, Villarceaux (FR).** Network Protocol and system research (2017-2019); Secure Cloud Networking (2015-2017); Novel Networking Protocols and Paradigms (2013-2015)
* **2013 Post-Doc Researcher,INRIA - Alcatel-Lucent Bell Labs, Villarceaux (FR).** Topic: Information Centric Networking (ICN) Supervisor: Dr. Giovanna Carofiglio
* **2009 to 2012 Research Engineer, France Telecom R&D, Paris (FR).** Topic: Information Centric Networking (ICN) Supervisor: Dr. Luca Muscariello
* **2008 to 2009 Research Intern, France Telecom R&D, Paris (FR).** Topic: peer-to-peer (P2P) Supervisor: Dr. Luca Muscariello
* **2008 Research Intern, Istituto Superiore Mario Boella, Turin (IT).** Topic: peer-to-peer (P2P) Supervisor: Prof. Marco Mellia
* **2006 Research Intern, CSP Piemonte, Turin (IT).** Topic: Mesh networks Supervisor: Prof. Claudio Casetti

### <i class="fas fa-user-graduate" style="color: #0760e6"> Education </i>

* **2009 to 2012 Ph.D., Telecom ParisTech, France, Networks and Computer Science.** Industrial - Ph.D through a CIFRE contract between Telecom ParisTech and Orange Labs. Advisor: Prof. Dario Rossi , Industrial Supervisor: Dr. Luca Muscariello. Dissertation: Trafficc and Resource Management in Content-Centric Networks:
Design and Evaluation"
* **2006 to 2008 M.Sc., Politecnico di Torino, Italy, Computer and Communication networks** Advisor: Dr. Marco Mellia. Thesis: P2P-TV systems measurements
* **2003 to 2006 B.Sc., Politecnico di Torino, Italy, Computer and Communication networks**


### <i class="fas fa-newspaper" style="color: #0760e6"> Publications </i>

{% bibliography %}

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