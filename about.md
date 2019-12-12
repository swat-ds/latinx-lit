---
layout: archive
permalink: /about/
title: About
image:
    banner: ../images/torres-el-pez.jpg
---

![group photo of class](../images/class.jpg)

*Introduction to Latinx Literature and Culture Seminar, 2017*


<hr/>

## Contributors

*Fall 2019*

<div class="bios">
{% for member in site.data.members %}
	{% if member.year == 2019 %}
	{% include bioimg.html %}
	<div class="col-wide"><div id="title">{{ member.name }}</div> - {{ member.bio }}</div>
	{% endif %}
{% endfor %}
</div>

<hr/>

*Fall 2017*
<div class="bios">
{% for member in site.data.members %}
	{% if member.year == 2017 %}
	{% include bioimg.html %}
	<div class="col-wide"><div id="title">{{ member.name }}</div> - {{ member.bio }}</div>
	{% endif %}
{% endfor %}
</div>



<div class="col-wide">
	<p><strong>Desiree Diaz</strong>, Assistant Professor, Spanish Department</p>
	<p><strong>Roberto Vargas</strong>, Research Librarian for Humanities and Interdisciplinary Studies</p>
	<p><strong>Header Image</strong>: El Pez, by Joaquín Torres García - <a href="https://en.wikipedia.org/wiki/es:Museo_Torres_Garc%C3%ADa" class="extiw" title="w:es:Museo Torres García">Museo Torres García</a> (fotografías propias de cuadros expuestos), <a href="https://commons.wikimedia.org/w/index.php?curid=79731261">Public Domain</a></p>
	<hr/>
	<img src="../images/logo-mccabe-web.png" class="logo" alt="">
</div>

<hr/>