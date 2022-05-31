---
permalink: /
title: "Welcome to the Web of Trust"
layout: home
classes:
  - wide
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/splash-image-1.jpg
---

{% include nextevent.md %}

**4/7/22:** [Save the Date for RWOT11 in September](https://shannona.github.io/newwebsite/rwot%20workshop/RWOT11-SaveDate/)<br>
**2/1/22:** [Coming Soon: RWOT Salon 2 Output](https://shannona.github.io/newwebsite/rwot%20virtual%20salon/RWOT-VSalon2/)

![image-right]({{ site.url }}{{ site.baseurl }}/assets/images/image-alignment-300x200.jpg){: .align-right}

***What is RWOT?*** It's a new take on the classic model of a web of trust that was first suggested by PGP. Our goal is to support our community in creating decentralized models of identity and information, to ensure that we can remain in control of our assets, our accounts, and ourselves online!

***What Does RWOT Do?*** RWOT consists of virtual salons and in-person design workshops. They allow us to germinate new ideas and produce finalized content that present those ideas to the larger community. Virtual salons crowdsource inspiration and deliver statements, while design workshops produce at least five white papers on topics decided by the group to have the greatest impact on the future.

{% capture notice-2 %}

 {% for post in site.posts limit: 2 %}
  <b>{{ post.date }}: <a href="{{ post.url }}">{{ post.title }}</a></b><br>
  {% endfor %}
  
{% endcapture %}

<div class="notice--info">{{ notice-2 | markdownify }}</div>
