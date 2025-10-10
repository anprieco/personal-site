---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Interested in collaborating or exchanging ideas around neuroscience, oncology, or translational innovation?
I’d love to connect with others working to turn science into impact.

{%
  include button.html
  type="email"
  text="Email Anna"
  link="anprieco@gmail.com"
%}
{%
  include button.html
  type="website"
  text="Find me at the Institute"
  link="https://www.google.com/maps/place/Instituto+de+Neurociencias+CSIC-UMH/@38.3889106,-0.4386145,17z/data=!3m1!4b1!4m6!3m5!1s0xd623a1e781744b9:0x2ee8ac39090678d1!8m2!3d38.3889064!4d-0.4360396!16s%2Fg%2F121qgcnr?entry=ttu&g_ep=EgoyMDI1MTAwNy4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

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
