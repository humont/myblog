---
layout: default
---

<div class="row col s3of4 pt3">

  <p class="">Hi, <a href="{{ site.github.url }}/about">I'm Hugo.</a></p>

  <p class="">A while ago I made a decision that my life would be <a href="{{ site.github.url }}/projects">project</a> based. Each project gives me the opportunity to learn new skills. This here is a partial record of these skills as I learn them.</p>

  <p class="pb4">I also keep a record of the <a href="{{ site.github.url }}/readings">books I read</a>... for posterity</p>

</div>

<h3>2017</h3>
{% for post in site.posts %}

<a href="{{ site.github.url }}{{ post.url }}" class="no-underline">{{ post.title }}</a>

{% endfor %}
