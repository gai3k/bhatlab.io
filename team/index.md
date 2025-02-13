---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We have been able to profile the myeloid cell population in the GBM primary and recurrent patients. We have been able to identify myeloid cell types and functional states in the GBM patients indicating the cell population that can be targeted for treatment.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background_mayo.jpg" dark=true %}

We want to expand our team of multi-disciplinary researchers dedicated to improving patient care and GBM treatment outcomes!
{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
