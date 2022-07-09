---
permalink: /events/
layout: single
classes:
  - wide
author_profile: true
title: "Events"
rwot_9:
  - image_path: "{{ site.url }}{{ site.baseurl }}/assets/images/events/rwot9b.jpeg"
    alt: "Silicon Salon Overview"
    title: "RWOT 9: Prague (2019)"
    excerpt: 'The final Prague before the global COVID pandemic was held in Prague of the Czech Republic in September 2019.'
    url: "https://github.com/WebOfTrustInfo/rwot9-prague/tree/master/final-documents#readme"
    btn_label: "Final Papers"
    btn_class: "btn--success"
    url2: "https://github.com/WebOfTrustInfo/rwot9-prague/tree/master/topics-and-advance-readings#topical-listing"
    btn_label2: "Advance Readings"
    btn_class2: "btn--info"
    url3: "https://github.com/WebOfTrustInfo/rwot9-prague/tree/master/topics-and-advance-readings"
    btn_label3: "Repo"
    btn_class3: "btn--info"
---

{% capture notice-1 %}
{% include nextevent.md %}
{% endcapture%}

<div class="notice--info">{{ notice-1 | markdownify }}</div>

{% include feature_row id="rwot_9" type="left" %}



