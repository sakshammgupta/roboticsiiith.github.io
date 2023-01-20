---
layout: faculty-page
title: "Nagamanikandan Govindan"
permalink: /faculty_ngovindan/
id: ngovindan
---


--- 
<br>
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

<br>
### Research Threads
Robot design- Mobile manipulation - Hybrid robots – Grasper - Redundant and Underactuated robots - Optimal control - Mechatronic system design.

- `Robot design` - Robotic design is the process of creating a robot or a robotic system. This includes mechanism design, operation process, and circuitry. This integrates functional elements from mechanical, electronics and software disciplines.
- `Mobile manipulation` - Mobile manipulation refers to a robotic system in which a manipulator is attached to a mobile base. This has advantages of mobile platforms and robotic manipulators by overcoming disadvantages.
- `Hybrid robots` - These are the robots that are equipped with both legs and wheels (or tracks) which are used in different configurations to perform different kinds of locomotions.
- `Grasper` - Grasper is a device used for handling, tightening, sliding, holding and releasing objects. It is usually equipped as an end effector to a robotic manipulator.
- `Redundant and Underactuated robots` - Redundant robot is a robot which has more degrees of freedom than the number of independent control inputs or the number of variables governing its configuration. In contrast, underactuated robots are the complete opposite of redundant robots, they have fewer degrees of freedom than the number of independent control inputs.
- `Optimal control` - This is a type of mathematical optimization that deals with finding the optimal controls for a controlled dynamic system in a period of time such that an objective function is optimized. 
<br>


### Apply

<br>
### Current Students
<div class='pubscroll'>
{% assign number_printed = 0 %}
{% for member in site.data.students %}
{% if member.supervisorid == page.id %}
{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
<img src="https://github.com/{{member.github}}.png" class="img-responsive" width="25%" style="float: left;" />
<h4> {{ member.name }} </h4>
<i>{{ member.email }} </i>
<ul style="overflow: hidden">
<li> Joined: {{ member.year }} </li>
<li> Supervisor: {{ member.supervisor }} </li>
<li> Areas: {{ member.areas }} </li>
<li><a href="{{ member.web }}"> Personal Page </a> </li>
</ul>
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
<!-- -->
</div>

