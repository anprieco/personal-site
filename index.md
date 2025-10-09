---
---

Welcome! I’m a biomedical scientist fascinated by how the same developmental programs that sculpt the brain’s incredible complexity can, when disrupted, give rise to childhood cancers.

During my PhD at the Institute of Neuroscience (CSIC-UMH), I focused on Embryonal Tumors with Multilayered Rosettes (ETMR)—one of the rarest and most aggressive pediatric brain tumors. Using genetically engineered mouse models and multi-omics approaches, I explored how these tumors emerge from early neurodevelopmental processes, aiming to bridge fundamental biology with clinical insight. I’m passionate about connecting basic neurodevelopment with translational oncology, and I’m driven by the belief that understanding how we are built, cell by cell, gene by gene, is the key to revealing how diseases like cancer begin. 

Beyond the lab, I love staying active, whether through running or working out, and I find balance in reading, cooking, and exploring new recipes. I also enjoy sharing science creatively—through outreach, visual design, and conversations that connect researchers, clinicians, and the wider community.

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
