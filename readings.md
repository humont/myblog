---
title: Reading List
permalink: "/readings/"
layout: default
---

<div class="row pt3">
<p class=" ">A list of books that I've read and hopefully enjoyed. Click through for thoughts. Each book is rated out of 20.</p>
<p class=" pb4">I rate out of 20 because I am not amazon.</p>
</div>

<h3>2017</h3>
<div class="row pb3">
{% for book in site.readings %}
<a href="{{ site.github.url }}{{ book.url }}">{{ book.title }}</a>
{% endfor %}
</div>
