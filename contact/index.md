---
title: "Contact"
layout: page
nav:
  order: 5
  tooltip: "Email, address, and location"
---

# {% include icon.html icon="fa-regular fa-envelope" %} Contact

Interested in collaborating or exchanging ideas around neuroscience, oncology, or translational innovation?
I’d love to connect with others working to turn science into impact.

{% include button.html type="email" text="anprieco@gmail.com" link="mailto:anprieco@gmail.com" %}

{% include button.html type="website" text="Institute map (Google)" link="https://www.google.com/maps/place/Instituto+de+Neurociencias+CSIC-UMH/@38.3889106,-0.4386145,17z" %}

{% include section.html %}

{% capture col1 %}
{% include figure.html image="images/photo.jpg" caption="Lorem ipsum" %}
{% endcapture %}

{% capture col2 %}
{% include figure.html image="images/photo.jpg" caption="Lorem ipsum" %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
