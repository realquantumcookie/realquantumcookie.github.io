---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About 

<div class="jumbotron">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ site.data.about.photo }}" width="50%" style="max-width:250px;min-width:100px"/>
<h3>{{ site.data.about.name }}</h3>
<h4><i>{{ site.data.about.info }}</i></h4>
{% if site.data.about.email %}<a href="mailto:{{ site.data.about.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
{% if site.data.about.cv %} <a href="{{ site.url }}{{ site.baseurl }}/{{ site.data.about.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
{% if site.data.about.scholar %} <a href="{{ site.data.about.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
{% if site.data.about.github %} <a href="{{ site.data.about.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
</div>

{% if site.data.grants %}
<div class="jumbotron">
### Grants
<ul>
{% for grant in site.data.grants %}
 <li> {{ grant.name }} </li>
{% endfor %}
</ul>
</div>
{% endif %}

{% if site.data.awards %}
<div class="jumbotron">
### Awards
<ul>
{% for award in site.data.awards %}
 <li> {{ award.name | replace: "-","&#8211;"}} </li>
{% endfor %}
</ul>
</div>
{% endif %}
