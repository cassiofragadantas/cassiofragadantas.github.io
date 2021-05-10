---
title: "SuKro"
excerpt: "Learning dictionaries as a sum of Kronecker products. (MATLAB)<br/><img src='/images/500x300.png'>"
collection: portfolio
code: 'https://github.com/cassiofragadantas/SuKro-DL'
---

Learning dictionaries as a sum of Kronecker products. 
A rearrangement operation[^1] transforms a (sum of R) Kronecker product(s) into a rank-1 (rank-R) matrix.
Inducing a Sum of Kronecker products (SuKro) structure thus becomes a low-rank approximation problem.

<img src='/images/portfolio/2017_SuKro.png'>

This code corresponds to the following paper:

> C. F. Dantas, M. N. da Costa, R. R. Lopes, "Learning Dictionaries as a Sum of Kronecker Products." In IEEE Signal Processing Letters, 2017.

{% comment %} 
{% for post in site.publications %}
  {% if post.title == 'Learning Dictionaries as a Sum of Kronecker Products' %}
    {% include archive-single.html %}
  {% endif%}
{% endfor %}
{% endcomment %}

It contains an image denoising demo.

Related slides [here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2017_SuKro_SPARS.pdf) and [here](https://www.dropbox.com/sh/5f1qnrk3gu9asg6/AABv5uZ5lasmcnLASuGwpVM4a?preview=2016_Master_Unicamp.pdf) (from slide 14).


[^1]: C.F. Van Loan, n. Pitsianis "Approximation with Kronecker Products", 1993.


