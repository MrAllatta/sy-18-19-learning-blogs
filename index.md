---
layout: default
title: Mr. Allatta's Learning Blog
---

# Welcome!

Welcome to Mr. Allatta's Learning Blog! This will be my home base for sharing learning reflections with my students through out the year. 

In 2018-2019 my students are 9th and 10th graders at the Academy for Software Engineering. They are the "Lower Academy" of a comprehensive public high school in NYC. The two year lower academy sequence is required of all students and culminates in the AP Computer Science Principles exam.

# Learning Reflections
<div class="blurb">
	<h1>Hi there, I'm Eric Allatta</h1>
	<p>I teach 9th and 10th grade computer science at the Academy for Software Engineering <a href="/about">Read more about my life...</a></p>
</div><!-- /.blurb -->

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
