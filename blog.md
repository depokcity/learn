---
layout: page
title: Materi Terbaru
permalink: /materi/
---
_Monggo_, silahkan menikmati tulisan di blog saya...

<h3>SMA Kelas 10</h3>
{% for post in site.categories.kelas-10 %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
