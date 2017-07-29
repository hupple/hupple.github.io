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

<br>
{% if page.author_profile or layout.author_profile or page.sidebar %}
  {% if page.author_profile or layout.author_profile %}{% include author-profile.html %}{% endif %}
  {% if page.sidebar %}
    {% for s in page.sidebar %}
      {% if s.image %}
        <img src=
        {% if s.image contains "://" %}
          "{{ s.image }}"
        {% else %}
          "{{ s.image | prepend: "/images/" | prepend: base_path }}"
        {% endif %}
        alt="{% if s.image_alt %}{{ s.image_alt }}{% endif %}">
      {% endif %}
      {% if s.title %}<h3>{{ s.title }}</h3>{% endif %}
      {% if s.text %}{{ s.text | markdownify }}{% endif %}
    {% endfor %}
    {% if page.sidebar.nav %}
      {% include nav_list nav=page.sidebar.nav %}
    {% endif %}
  {% endif %}
{% endif %}


