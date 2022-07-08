---
layout: default
title: papers
permalink: /papers/
---


</select>
{% for paper in site.categories.papers %}
{% capture prev_year %}{{ this_year }}{% endcapture %}
{% capture this_year %}{{ paper.year }}{% endcapture %}


{% if forloop.first %}
    {% assign counter = 0 %}
  <div class="row">
    <div class="col-md-12">
      <h1>{{ this_year }}</h1>
<hr style="height:3px;border:none;color:#808088;background-color:#808088;" />    </div>
  </div>
  <div class="row">
  {% elsif this_year != prev_year %}
    {% assign counter = 0 %}
  </div>
  <div class="row">
    <div class="col-md-12">
      <h1>{{ this_year }}</h1>
      <hr style="height:3px;border:none;color:#808088;background-color:#808088;" />

    </div>
  </div>
  <div class="row">
  {% else %}
    {% assign counter = counter | plus: 1 %}
    {% assign mod = counter | modulo: 3 %}
    {% if mod == 0 %}

  </div>
  <div class="row">

    {% endif %}
  {% endif %}
  <div class="col-lg-4 paperbox">
    <div class="media">
      <div class="media-body">
        <div class="smallhead mb-1"><a href="{{ paper.pdf }}" class="off">{{ paper.title }}</a></div>
        <p class="note">{{ paper.ref }}</p>
      </div>
      <a href="{{ paper.pdf }}">
        <img class="ml-3" width=100 class="media-object" src="{{ paper.image }}">
      </a>
    </div>
    <div class="bigspacer"></div>
    <div class="spacer"></div>
      </div>
{% endfor %}
  </div>
