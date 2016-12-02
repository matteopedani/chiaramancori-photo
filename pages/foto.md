---
layout: page
show_meta: false
title: "Style your photo!"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "Federica_Lorusso_7_testata.jpg"
permalink: "/foto/"
---
Test gio mancori occhi
<ul>
    {% for post in site.categories.foto %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>