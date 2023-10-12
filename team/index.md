---
title: Team
nav:
  order: 3
  tooltip: Our team members
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

# {% include icon.html icon="fa-solid fa-users" %}Assistants

{% include list.html data="members" component="portrait" filters="role: ra" %}


{% include section.html background="images/sustech.jpg" dark=true %}
