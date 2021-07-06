---
layout: default
title: 'Section 2: An explosion of images'
order: 2
permalink: /explore/section-two
---

The earliest surviving manuscripts of the Shahnameh dating to the thirteenth century were not illustrated, but by that time its stories were inspiring the decoration of ceramics and metalwork.
The Mongol conquests, beginning under the leadership of Chingiz Khan (1162–1227), brought Iran into the Mongol Empire, which stimulated dynamic cultural exchanges across Asia. The regeneration of Iran’s political identity under the Mongol Il-Khanid dynasty (1256–1353), within borders comparable to those of its pre-Islamic past, coincided with the promotion of the Shahnameh as the princely manual for Iran’s new rulers and with the emergence of Persian manuscript painting.

The earliest illustrated copies, the so-called ‘Small’ Shahnamehs with their numerous paintings, date to c.1300. Soon afterwards more majestic manuscripts were produced, including the 'Great Mongol' Shahnameh and copies made for the Inju rulers in Shiraz. Chinese influence is strong in the illustration of these manuscripts. Their text is written in the naskhi script, which remains legible when copied at speed. Kings and heroes are constantly engaged in feasting and fighting, the key elements of the warrior code and pastimes of the ruling elite.

They also find time for romance and women are central to many of the episodes. The conflicts between rulers and heroes inspire captivating stories and reflections on the timeless themes of power, loyalty and love.

_The following is a selection of manuscripts included in this section of the exhibition. The numbers correspond to the order of the display and the entries in the catalogue._
<div class="row">
{% assign sorted-posts = site.objects | where: "section","2" | sort:'order'  %}
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
