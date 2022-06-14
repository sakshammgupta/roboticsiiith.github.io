---
layout: faculty-page
title: "Harikumar Kandath"
permalink: /faculty_hkandath
id: hkandath
---


--- 
### Research Threads
### Apply
### Current Students

### Featured Publications
<div class='pubscroll'>

{% for year_hash in site.data.pubs %}
{% assign year = year_hash[1] %}

<!-- <h1> {{year}} </h1> -->
{% for publi in year %}
{% if publi.id == page.id and publi.featured == 1 %}
<b> {{ publi.title }} <br /> </b>
<em>{{ publi.authors }} </em><br />
Published at {{ publi.venue }} &nbsp; [<a href="{{ site.url }}{{ site.baseurl }}{{ publi.link.url }}">{{ publi.link.display }}</a>]
{% endif %}
{% endfor %}
{% endfor %}
</div>
