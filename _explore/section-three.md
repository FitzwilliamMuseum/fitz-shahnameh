---
layout: default
title: 'Section 3: Princely Patronage and Beyond: 15th century'
order: 3
permalink: /explore/section-three
---

The rule of the Timurids (1405–1507) inaugurated the first great period of Persian painting, with the Shahnameh at its core. Muslims of Turko-Mongol origin, the descendants of Timur (Tamerlane, 1336–1405) controlled an empire stretching at its peak from India to Anatolia. They saw their sponsorship of the ‘national epic’ as a way of establishing their Iranian credentials.

Three of Timur’s grandsons, Ebrahim Soltan, Baysonghor, and Mohammad Juki, commissioned outstanding copies of the Shahnameh from the leading artists working in Shiraz and Herat during the 1430s and 1440s. They were written in the elegant nasta‘liq script, which was by then the norm for fine manuscripts in verse.

In the second half of the fifteenth century under rulers of the Turkman ‘White Sheep’ dynasty Shiraz became the home of a painting style derived from that of Herat. Competent, but less than princely, this style is known as ‘Commercial Turkman’. It facilitated the production of numerous, illustrated copies and brought the Shahnameh within the reach of less exalted patrons.


_The following is a selection of manuscripts included in this section of the exhibition. The numbers correspond to the order of the display and the entries in the catalogue._
<div class="row">
{% assign sorted-posts = site.objects | where: "section","3" | sort:'order'  %}
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
