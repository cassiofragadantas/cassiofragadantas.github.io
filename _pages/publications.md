---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
excerpt: False
---


<!-- {% if author.googlescholar %} -->
<!-- {% endif %} -->

You can also find my articles on <a href="https://scholar.google.com/citations?user=YgcZQpgAAAAJ">my Google Scholar profile</a>.


{% include base_path %}

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

## Other publications
{% for post in site.publications reversed %}
  {% if post.venuetype == 'misc' %}
    {% include archive-single.html %}
  {% endif%}
{% endfor %}

