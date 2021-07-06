---
layout: default
title: 'Section 1: Ferdowsi’s Shahnameh: A Persian Classic'
order: 1
permalink: /explore/section-one
---
The Persian ‘Book of Kings’ — the Shahnameh — is the national epic of the Iranian people. It traces the history of the Iranian world from its creation to the fall of the Sasanian Empire in the seventh century. The Arab conquest brought fundamental changes, replacing the Zoroastrian religion with Islam and the Middle Persian (Pahlavi) language with Arabic.

<div class="row">
{% assign sorted-posts = site.objects | where: "section","1" | sort:'order'  %}
{% for author in sorted-posts  %}
<div class="col-md-4 mb-3">
  <div class="card h-100" >
    <a href="{{site.url}}{{site.baseurl}}{{ author.permalink }}" class="stretched-link">
      <img class="card-img-top" src="{{site.url}}{{site.baseurl}}/images/thumbnails/{{author.order}}.jpeg" alt="Card image cap" width="300" height="300"/>
    </a>
    <div class="card-body">
      <h3 class="lead mt-2">
        <a href="{{site.url}}{{site.baseurl}}{{ author.permalink }}" class="stretched-link">{{author.title}}</a>
      </h3>
    </div>
  </div>
</div>
{% endfor %}
</div>
