---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are looking forward to expanding our team of cross-disciplinary researchers. If our lab's research goals and projects are interesting to you or you would like to gain expertise in these areas do get in touch!

{%
  include button.html
  type="email"
  text="bhat.krishna@mayo.edu"
  link="bhatlab.com"
%}
{%
  include button.html
  type="phone"
  text="+1-(480)301-6360"
  link="+1-(480)301-6360"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/zwAUa4eNP7o8HhL19"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Bhat.jpg"
  caption="Dr Bhat"
%}

{% endcapture %}

{% include section.html dark=true %}

{% capture col1 %}
Additional text to be added
{% endcapture %}


{% include cols.html col1=col1 %}
