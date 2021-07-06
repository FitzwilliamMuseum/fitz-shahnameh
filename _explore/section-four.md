---
layout: default
title: 'Section 4: Old and New Ways of Seeing: 16th – 19th centuries'
order: 4
permalink: /explore/section-four
---

The sixteenth century saw the advent of the Safavids (1501–1722), Iran’s longest-lived and most successful dynasty since the pre-Islamic period. Their first move was to proclaim shi‘ism as the official state religion, venerating the family of the Prophet Mohammad. Under Safavid patronage, Ferdowsi’s epic became a vehicle for expressing Persian political and cultural superiority vis-à-vis the Ottoman Turks, who were consolidating their rule in Anatolia and the Arab world. After the fall of the Safavids and the bloody career of Nader Shah (1736–1747), the Qajars established their power in the 1790s and laid the foundations of the dynasty that ruled Iran until 1924. They considered themselves the heirs of the Safavids and promoted an image of Persian kingship in which the Shahnameh played a central role.

During this time, the capital shifted from Tabriz to Qazvin and Esfahan, then to Mashhad and finally Tehran. Princely copies of the Shahnameh were made at all of these regional courts, and more modest ones were produced in large numbers for the middle classes. By the sixteenth century, the Shahnameh had ‘conquered’ the empires west and east of Iran, and fine manuscripts were exported to and produced in Ottoman Istanbul and Mughal India.

The most magnificent Persian manuscript ever produced was made for Shah Tahmasp (1524–1576) by a team of artists from former Timurid Herat and the Turkman courts in the west. Another royal copy was made for his successor, Esma‘il II (1576–1577).

If the subject matter remained largely the same, by the end of the period European influence was making itself felt in the use of perspective and the arrangement of the picture space.


_The following is a selection of manuscripts included in this section of the exhibition. The numbers correspond to the order of the display and the entries in the catalogue._
{: .text-danger }

<div class="row">
{% assign sorted-posts = site.objects | where: "section","4" | sort:'order'  %}
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
