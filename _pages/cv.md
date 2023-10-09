---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
<ul class="fa-ul timeline">
  <li>
    <i class="fa-li fas fa-graduation-cap"></i> MS in Advanced Computing, Morgan State University, MD, USA, Spring 2024 (expected)
  </li>
  <li>
    <i class="fa-li fas fa-graduation-cap"></i> M.Sc. in Computer Science and Engineering, Jahangirnagar University, Bangladesh, 2013
  </li>
  <li>
    <i class="fa-li fas fa-graduation-cap"></i> B.S. in Computer Science and Engineering, Jahangirnagar University, Bangladesh, 2012
  </li>
</ul>

Work experience
======
  <div class="row">
    <div class="col-md-12">
      <div id="content">
        <ul class="timeline-1 text-black">
          {% for post in site.experience reversed %}
          <li class="event experience-card" data-date="">
            {% include archive-single-experience-cv.html %}
          </li> 
          {% endfor %}
        </ul>
        </div>
    </div>
  </div>

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
