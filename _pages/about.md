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
<div itemscope itemtype="http://schema.org/Person">
   <ul class="author__urls social-icons">
      {% if author.location %}
        <li><i class="fa fa-fw fa-map-marker" aria-hidden="true"></i> {{ author.location }}</li>
      {% endif %}
      {% if author.employer %}
        <li><i class="fa fa-fw fa-map-marker" aria-hidden="true"></i> {{ author.employer }}</li>
      {% endif %}
      {% if author.uri %}
        <li><a href="{{ author.uri }}"><i class="fa fa-fw fa-chain" aria-hidden="true"></i> {{ site.data.ui-text[site.locale].website_label | default: "Website" }}</a></li>
      {% endif %}
      {% if author.email %}
        <li><a href="mailto:{{ author.email }}"><i class="fa fa-fw fa-envelope-square" aria-hidden="true"></i> {{ site.data.ui-text[site.locale].email_label | default: "Email" }}</a></li>
      {% endif %}
      {% if author.keybase %}
        <li><a href="https://keybase.io/{{ author.keybase }}"><i class="fa fa-fw fa-key" aria-hidden="true"></i> Keybase</a></li>
      {% endif %}
      {% if author.twitter %}
        <li><a href="https://twitter.com/{{ author.twitter }}"><i class="fa fa-fw fa-twitter-square" aria-hidden="true"></i> Twitter</a></li>
      {% endif %}
      {% if author.facebook %}
        <li><a href="https://www.facebook.com/{{ author.facebook }}"><i class="fa fa-fw fa-facebook-square" aria-hidden="true"></i> Facebook</a></li>
      {% endif %}
      {% if author.google_plus %}
        <li><a href="https://plus.google.com/+{{ author.google_plus }}"><i class="fa fa-fw fa-google-plus-square" aria-hidden="true"></i> Google+</a></li>
      {% endif %}
      {% if author.linkedin %}
        <li><a href="https://www.linkedin.com/in/{{ author.linkedin }}"><i class="fa fa-fw fa-linkedin-square" aria-hidden="true"></i> LinkedIn</a></li>
      {% endif %}
      {% if author.xing %}
        <li><a href="https://www.xing.com/profile/{{ author.xing }}"><i class="fa fa-fw fa-xing-square" aria-hidden="true"></i> XING</a></li>
      {% endif %}
      {% if author.instagram %}
        <li><a href="https://instagram.com/{{ author.instagram }}"><i class="fa fa-fw fa-instagram" aria-hidden="true"></i> Instagram</a></li>
      {% endif %}
      {% if author.tumblr %}
        <li><a href="https://{{ author.tumblr }}.tumblr.com"><i class="fa fa-fw fa-tumblr-square" aria-hidden="true"></i> Tumblr</a></li>
      {% endif %}
      {% if author.bitbucket %}
        <li><a href="https://bitbucket.org/{{ author.bitbucket }}"><i class="fa fa-fw fa-bitbucket" aria-hidden="true"></i> Bitbucket</a></li>
      {% endif %}
      {% if author.github %}
        <li><a href="https://github.com/{{ author.github }}"><i class="fa fa-fw fa-github" aria-hidden="true"></i> Github</a></li>
      {% endif %}
      {% if author.stackoverflow %}
        <li><a href="https://www.stackoverflow.com/users/{{ author.stackoverflow }}"><i class="fa fa-fw fa-stack-overflow" aria-hidden="true"></i> Stackoverflow</a></li>
      {% endif %}
      {% if author.lastfm %}
        <li><a href="https://lastfm.com/user/{{ author.lastfm }}"><i class="fa fa-fw fa-lastfm-square" aria-hidden="true"></i> Last.fm</a></li>
      {% endif %}
      {% if author.dribbble %}
        <li><a href="https://dribbble.com/{{ author.dribbble }}"><i class="fa fa-fw fa-dribbble" aria-hidden="true"></i> Dribbble</a></li>
      {% endif %}
      {% if author.pinterest %}
        <li><a href="https://www.pinterest.com/{{ author.pinterest }}"><i class="fa fa-fw fa-pinterest" aria-hidden="true"></i> Pinterest</a></li>
      {% endif %}
      {% if author.foursquare %}
        <li><a href="https://foursquare.com/{{ author.foursquare }}"><i class="fa fa-fw fa-foursquare" aria-hidden="true"></i> Foursquare</a></li>
      {% endif %}
      {% if author.steam %}
        <li><a href="https://steamcommunity.com/id/{{ author.steam }}"><i class="fa fa-fw fa-steam-square" aria-hidden="true"></i> Steam</a></li>
      {% endif %}
      {% if author.youtube %}
        <li><a href="https://www.youtube.com/user/{{ author.youtube }}"><i class="fa fa-fw fa-youtube-square" aria-hidden="true"></i> YouTube</a></li>
      {% endif %}
      {% if author.soundcloud %}
        <li><a href="https://soundcloud.com/{{ author.soundcloud }}"><i class="fa fa-fw fa-soundcloud" aria-hidden="true"></i> Soundcloud</a></li>
      {% endif %}
      {% if author.weibo %}
        <li><a href="https://www.weibo.com/{{ author.weibo }}"><i class="fa fa-fw fa-weibo" aria-hidden="true"></i> Weibo</a></li>
      {% endif %}
      {% if author.flickr %}
        <li><a href="https://www.flickr.com/{{ author.flickr }}"><i class="fa fa-fw fa-flickr" aria-hidden="true"></i> Flickr</a></li>
      {% endif %}
      {% if author.codepen %}
        <li><a href="https://codepen.io/{{ author.codepen }}"><i class="fa fa-fw fa-codepen" aria-hidden="true"></i> CodePen</a></li>
      {% endif %}
      {% if author.vine %}
        <li><a href="https://vine.co/u/{{ author.vine }}"><i class="fa fa-fw fa-vine" aria-hidden="true"></i> Vine</a></li>
      {% endif %}
      {% if author.googlescholar %}
        <li><a href="{{ author.googlescholar }}"><i class="ai ai-google-scholar-square ai-fw"></i> Google Scholar</a></li>
      {% endif %}
      {% if author.orcid %}
        <li><a href="{{ author.orcid }}"><i class="ai ai-orcid-square ai-fw"></i> ORCID</a></li>
      {% endif %}
      {% if author.wikipedia %}
        <li><a href="https://en.wikipedia.org/wiki/User:{{ author.wikipedia }}"><i class="fa fa-fw fa-chain" aria-hidden="true"></i> Wikipedia</a></li>
      {% endif %}
    </ul>
</div>

