---
title: "RRC - Publications"
layout: gridlay-pubs
excerpt: "RRC -- Publications."
sitemap: false
permalink: /publications/
---

# Publications



Our research focus is on Multi-Robotic systems, Mobile Robotics, Robot Vision, Robot Mechanism and Control. To read more about our what problems we try to solve,, please check out the [research]() page. For some of our group highlights and representative work, you can see them on the [highlights]() page. 

### 2021

{% for publi in site.data.pubs.2021 %}
  
  <b> {{ publi.title }} <br /> </b>
  <em>{{ publi.authors }} </em><br />
  Published at {{ publi.venue }} &nbsp; [<a href="{{ publi.link.url }}">{{ publi.link.display }}</a>]

{% endfor %}

***


### 2020

{% for publi in site.data.pubs.2020 %}
	
  <b> {{ publi.title }} <br /> </b>
  <em>{{ publi.authors }} </em><br />
  Published at {{ publi.venue }} &nbsp; [<a href="{{ publi.link.url }}">{{ publi.link.display }}</a>]

{% endfor %}

***

### 2019

{% for publi in site.data.pubs.2019 %}
  
  <b> {{ publi.title }} <br /> </b>
  <em>{{ publi.authors }} </em><br />
  Published at {{ publi.venue }} &nbsp; [<a href="{{ publi.link.url }}">{{ publi.link.display }}</a>]

{% endfor %}

***

<!-- ## Group highlights -->

{% assign number_printed = 0 %}
{% for publi in site.data.pubs.highlights %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


<!-- ## Patents -->
<!-- <em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a> -->
