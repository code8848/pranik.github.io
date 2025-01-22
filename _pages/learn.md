---

title: ""
permalink: /learn/
excerpt: ""
layout: single

---
## PE Exam Preparation
Explore posts that cover different chapters of the PE Exam preparation course:
<ul>
  {% assign pe_posts = site.posts | where: "category", "pe-exam-prep" % | sort: "date" %}
  {% for post in pe_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---

## Introduction to Open-Source Traffic Simulation
Explore posts about traffic simulation:
<ul>
  {% assign traffic_posts = site.posts | where: "category", "traffic-simulation" % | sort: "date" %}
  {% for post in traffic_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---

## Python in Transportation Analysis
Explore posts related to Python applications in transportation:
<ul>
  {% assign python_posts = site.posts | where: "category", "python-transport" % | sort: "date" %}
  {% for post in python_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>