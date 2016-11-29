---
layout: page
show_meta: false
title: "Style your photo!"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "ritratti-bn/giovanna_mancori_occhi.jpg"
permalink: "/foto/"
---
<ul>
    {% for post in site.categories.foto %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>