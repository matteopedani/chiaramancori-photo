---
layout: page
show_meta: false
title: "Style your photo!"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "giovanna_mancori_occhi.jpg"
permalink: "/foto/"
---
Test gio mancori occhi
<ul>
    {% for post in site.categories.foto %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>