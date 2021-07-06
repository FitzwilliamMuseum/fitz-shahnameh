---
layout: default
title: 'Section 5: The Shahnameh in India: 15th – 18th centuries'
order: 5
permalink: /explore/section-five
---

Copies of the Shahnameh illustrated in Persian style are attributed to India from as early as the 1420s, in the late ‘Sultanate’ period marked by political fragmentation of Muslim power after the sack of Delhi by Timur in 1398, and the influx of Afghan chiefs and their followers. Having lost control over Central Asia, the Timurids turned their attention to northern India where one of Timur’s descendants, Babur (1526–1530), from his base in Kabul, defeated the Lodi sultans and founded the Mughal dynasty (1526–1858).

The Mughal rulers were avid bibliophiles, Persian culture was dominant at their court and deluxe copies of the Shahnameh were preserved in their libraries. Following the loss and reconquest of northern India under Babur’s son Homayun, an astonishing production of illustrated manuscripts was undertaken for the third Mughal ruler, Akbar (1556–1605). The Akbari style combined major artistic traditions: Safavid from Tabriz, Hindu from Vijayanagar and European styles brought by Jesuit missions and diplomats to the Mughal courts. By the seventeenth century, the western presence was dominant, especially in the treatment of landscapes, and in the eighteenth century its influence extended to portraiture.

The Shahnameh endured as a princely manual on wise and just kingship. It offered splendid opportunities for the portrayal of Mughal rulers and courtiers engaged in hunting, fighting, diplomatic ceremonies, feasts and amorous affairs. It also continued to provide a topical commentary on contemporary events and individuals, extending its relevance to the recent past and the present. Above all, its lasting appeal points to a core of meaning — the eternal strife between good and evil — that transcends specific time and place.

_The following is a selection of manuscripts included in this section of the exhibition. The numbers correspond to the order of the display and the entries in the catalogue._
{: .text-danger }

<div class="row">
{% assign sorted-posts = site.objects | where: "section","5" | sort:'order'  %}
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
