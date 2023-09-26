---
title: Team
nav:
  order: 3
  tooltip: Our team menbers
---

# {% include icon.html icon="fa-solid fa-users" %}Team



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: prof" %}

{% include list.html data="members" component="portrait" filters="role: postdoc" %}

{% include list.html data="members" component="portrait" filters="role: phd" %}

{% include list.html data="members" component="portrait" filters="role: mas" %}

# {% include icon.html icon="fa-solid fa-users" %}Visitors

{% include list.html data="members" component="portrait" filters="role: vsdpro" %}

{% include list.html data="members" component="portrait" filters="role: vsch" %}

{% include list.html data="members" component="portrait" filters="role: vss" %}

{% include section.html background="images/sustech.jpg" dark=true %}


{% include grid.html style="square" content=content %}
