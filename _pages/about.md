---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<img class="img-responsive" style="float: left; margin: 0px 20px 0px 0px;" src="/images/profile.png" width="250"> I am an Economics Ph.D. student at the University of California, Berkeley. My interests are Public and Labor Economics. Prior to coming to Berkeley, I worked in New York City, where I moved after graduating from the University of North Carolina at Chapel Hill.

If you'd like to contact me, you can email ekrose at econ.berkeley.edu. You can find a recent version of my CV [here](/files/ekr_cv_06-06-17.pdf).

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

<p><br></p>
{% if author.location %}
  <i class="fa fa-fw fa-map-marker" aria-hidden="true"></i> {{ author.location }}
{% endif %}


