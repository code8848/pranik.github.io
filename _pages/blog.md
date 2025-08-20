---

title: "Blog"
permalink: /blog/
excerpt: ""
layout: single

---
<p>
Here you will find content from my newsletter where I intend to Think, Learn and Build in Public mostly around mobility, urban planning, cities, safety, AI and the future. <br/><br/>

I also sometimes post other personal blogs here. <b>Enjoy!!! </b>
</P>
## From Pranik's Newsletter:
<ul>
  {% assign newsletter_posts = site.posts | where: "category", "newsletter" | sort: "date" %}
  {% for post in newsletter_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Other Blogs:
<ul>
  {% assign blog_posts = site.posts | where: "category", "blog" | sort: "date" %}
  {% for post in blog_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




