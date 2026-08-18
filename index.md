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
### <i class="fas fa-newspaper" style="color: #0760e6">  News </i>

<ul  style="list-style-type:none;">
{% for post in site.posts limit:5 %}
  <li> <a href="{{ post.url }}"><b>{{ post.date | date: "%Y-%m" }}:</b> {{ post.title }}</a> </li>
{% endfor %}
</ul>

### <i class="fas fa-address-card" style="color: #0760e6">  Bio</i>

Next-generation computing and Artificial Intelligence create the greatest value when supported by robust, highly adaptable network infrastructure. Throughout my career, I have focused on building that foundation, working at the frontier of networking and computer science to design scalable systems that accelerate discovery and solve real-world bottlenecks. That mission drives my work in high-speed packet processing, distributed tracing, and optimizing the massive data-transfer demands of modern AI architectures.

I am currently a Principal Researcher and Team Leader at Huawei in Paris, where I lead research initiatives focused on distributed systems and network monitoring. We work on advanced network observability, the scalability challenges of large language models, and lightweight AI models for in-network deployments.

Across my career in research and engineering, my main goals have always been to build efficient systems, drive industrial innovation, and translate frontier networking research into real-world deployments. My work has resulted in numerous patents and publications across top-tier international venues, including USENIX ATC, IEEE ICNP, and ACM CoNEXT, as well as open-source software.

### <i class="fas fa-briefcase" style="color: #0760e6">  Experience</i>

* **2019 to \- Principal researcher and Team Leader, Huawei, Paris (FR).** Network monitoring (team leader since 2021); 
* **2013 to 2019 Research Engineer, Nokia Bell Labs, Villarceaux (FR).** Network Protocol and system research (2017-2019); Secure Cloud Networking (2015-2017); Novel Networking Protocols and Paradigms (2013-2015)
* **2013 Post-Doc Researcher,INRIA - Alcatel-Lucent Bell Labs, Villarceaux (FR).** Topic: Information Centric Networking (ICN) Supervisor: Dr. Giovanna Carofiglio
* **2009 to 2012 Research Engineer, France Telecom R&D, Paris (FR).** Topic: Information Centric Networking (ICN) Supervisor: Dr. Luca Muscariello
* **2008 to 2009 Research Intern, France Telecom R&D, Paris (FR).** Topic: peer-to-peer (P2P) Supervisor: Dr. Luca Muscariello
* **2008 Research Intern, Istituto Superiore Mario Boella, Turin (IT).** Topic: peer-to-peer (P2P) Supervisor: Prof. Marco Mellia
* **2006 Research Intern, CSP Piemonte, Turin (IT).** Topic: Mesh networks Supervisor: Prof. Claudio Casetti

### <i class="fas fa-code" style="color: #0760e6">  Software</i>
* **[SimAI fork](https://github.com/NetMeasurements-Team/SimAI)** (C/C++) *Contributor, supervisor.* Distributed AI training/inference simulation. 
* **[DUMBO](https://github.com/cpt-harlock/DUMBO)** (Rust) *Supervisor.* In-network ML classification for downstream task enhancement.
* **[SPADA](https://github.com/cpt-harlock/SPADA)** (Rust) *Supervisor.* Telemetry data structure for sparse data.
* **[FloWatcher-DPDK](https://github.com/ztz1989/FloWatcher-DPDK)** (C) *Supervisor.* Software traffic monitor for DPDK.
* **[ClickNF](https://github.com/nokia/ClickNF)** (C/C++) *Contributor, supervisor.* Modular TCP implementation for click router.
 

### <i class="fas fa-hand-holding" style="color: #0760e6">  Professional service</i>

* **Program Committees**
  * **Usenix ATC** - Annual Technical Conference (2025, 2024)
  * **PACMNET** - Proceedings of the ACM on Networking - PACMNET, CoNEXT (2026)
  * **IEEE/IFIP TMA** - Network Traffic Measurement and Analysis Conference (2026, 2024)
  * **ACM CoNEXT INET4AI** Workshop (2026, 2025) 
* **Journal Reviews**
  * **IEEE Transaction on Networking**
  * **IEEE Transactions on Network and Service Management**
  * **Elsevier Computer Networks**

### <i class="fas fa-user-graduate" style="color: #0760e6">  Education</i>

* **2009 to 2012 Ph.D., Telecom ParisTech, France, Networks and Computer Science.** Industrial - Ph.D through a CIFRE contract between Telecom ParisTech and Orange Labs. Advisor: Prof. Dario Rossi , Industrial Supervisor: Dr. Luca Muscariello. Dissertation: Trafficc and Resource Management in Content-Centric Networks:
Design and Evaluation"
* **2006 to 2008 M.Sc., Politecnico di Torino, Italy, Computer and Communication networks** Advisor: Dr. Marco Mellia. Thesis: P2P-TV systems measurements
* **2003 to 2006 B.Sc., Politecnico di Torino, Italy, Computer and Communication networks**

### <i class="fas fa-newspaper" style="color: #0760e6">  Publications</i>

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