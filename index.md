---
layout: default
title: Mr. Allatta's Learning Blog
---

<div class="blurb">
<h1>Welcome to Mr. Allatta's Learning Blog!</h1>
<p>This will be my home base for sharing learning reflections with my students throughout the year. Much thanks to [Jonathan Mcglone](http://jmcglone.com/guides/github-pages/) for the great tutorial getting us up to speed with GitHub Pages.</p>

<p>In the 2018-2019 school year my students are 9th and 10th graders at the Academy for Software Engineering. They are the "Lower Academy" of a comprehensive public high school in NYC, which is also the first comprehensive high school in the city with a core computer science sequence. The two year lower academy sequence is required of all students and culminates in the AP Computer Science Principles exam.</p>

<p>I teach 9th and 10th grade computer science at the Academy for Software Engineering. <a href="/about">Read more about my life...</a></p>

</div><!-- /.blurb -->

<h1> My Learning Reflections</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# My Student's Blogs

You can read my students learning blogs by finding the links below.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTkBkjq86c_cVULPqP0ak4kkwHh45cWs89lRLd_DtSUFDQcfbCtGRRyVFxVqwjEAZC6YT6ltdDcolw0/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
