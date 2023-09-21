---
title: Team
nav:
  order: 3
  tooltip: Our team menbers
---

# {% include icon.html icon="fa-solid fa-users" %}Team



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: prof" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!prof$)" %}

{% include section.html background="images/background.jpg" dark=true %}



{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
