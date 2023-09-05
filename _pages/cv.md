---
layout: archive
title: "CV"
#excerpt: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[//]: # [Please click to download my Curriculum Vitae [PDF]](https://salarmohtaj.github.io/files/paper1.pdf)


<br/><br/>

## Education

* Ph.D in Computer Science, [Technische Universität Berlin](https://www.tu-berlin.de/), 2023.
* M.S. in Computer Science, [International Institute of Information Technology Hyderabad (IIIT-H)](https://www.iiit.ac.in/), 2019



## Work Experience

* January 2018 - June 2018: Research Intern
  * Electrical and Computer Engineering Department at [National University of Singapore (NUS)](https://nus.edu.sg/).
  * Duties included: Speech researcher responsible for building a framework for Cross-lingual Voice Conversion.
  * Supervisor: [Haizhou Li](https://cde.nus.edu.sg/ece/haizhou-li/)
  
 * May 2015 - July 2015: Research Assistant
   * [International Institute of Information Technology Hyderabad (IIIT-H)](https://www.iiit.ac.in/)
   * Speech Processing Laboratory in [Language Technologies Research Center (LTRC)](https://ltrc.iiit.ac.in/)
   * Duties included: Development of an Android app for speech-based activation and control of mobile devices.
   * Supervisor: Suryakanth V Gangashetty


## Technical Skills

* Programming
  * Python (numpy, Pandas, Scipy)
    
* Machine Learning
  * Pytorch
  * scikit-learn
 
## Languages known

* English: Fluent
* Deutsch: A2
* Telugu: Mother Tongue
* Hindi: Fluent


## Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
[//]: # Talks
[//]: # ======
{% comment %}
<ul>{% for post in site.talks %}
{% include archive-single-talk-cv.html %}
{% endfor %}</ul>
{% endcomment %}


## Teaching

  <ul>{% for post in site.teaching reversed %}
  {% if forloop.first %}
    {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  

