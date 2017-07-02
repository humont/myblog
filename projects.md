---
permalink: "/projects/"
layout: default
---

<div class="row pt3">
  Here's a collection of things I've worked on. Some are business, some are personal.
</div>

<div class="row pv3">
{% for project in site.projects %}
<a href="{{ site.github.url }}{{ project.url }}" class="mh-auto project__card pr1 no-underline dark dark_hovered">
<div class="col s1of2 pa2  brdr_brand-green bg_brand-green_light_hovered">
  <div class="">
    <div class="row">
      <img src="{{ site.github.url }}{{ project.image }}" alt="" class="project__icon_thumbnail mv3 mh-auto">
    </div>
    <div class="row">
      <span class="mh-auto ">{{ project.title }}</span>
    </div>
  </div>
</div>
</a>

{% endfor %}
</div>
