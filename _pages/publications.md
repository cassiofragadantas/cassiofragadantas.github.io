---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
excerpt: False
---

{% include base_path %}

{% if site.author.googlescholar %}
You can find a complete list of my publications at <a href="{{site.author.googlescholar}}">my Google Scholar profile</a> and open-access at <a href="{{https://cv.hal.science/cassio-dantas}}">my HAL profile</a>.
{% endif %}



## Journal articles

{% for post in site.publications reversed %}
  {% if post.venuetype == 'journal' %}
    {% include archive-single.html %}
  {% endif%}
{% endfor %}

## Conference papers

{% for post in site.publications reversed %}
  {% if post.venuetype == 'proceeding' %}
    {% include archive-single.html %}
  {% endif%}
{% endfor %}

## Master's and PhD thesis

{% for post in site.publications reversed %}
  {% if post.venuetype == 'thesis' %}
    {% include archive-single.html %}
  {% endif%}
{% endfor %}

## Other communications

{% for post in site.publications reversed %}
  {% if post.venuetype == 'misc' or post.venuetype == 'repport'%}
    {% include archive-single.html %}
  {% endif%}
{% endfor %}

