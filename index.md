---
---

{%
  include button.html
  type="pdf"
  text="Take a look at my CV"
  link="/files/2025_CV_APC_Eng_Colorful.pdf"
%}

{% capture col1 %}
Welcome! I’m a **biomedical scientist** fascinated by how the same developmental programs that sculpt the brain’s incredible complexity can, when disrupted, give rise to childhood cancers.

During my PhD at the **Institute of Neuroscience (CSIC-UMH)**, I focused on **Embryonal Tumors with Multilayered Rosettes (ETMR)**, one of the rarest and most aggressive pediatric brain tumors. Using genetically **engineered mouse models** and **multi-omics approaches**, I explored how these tumors emerge from early neurodevelopmental processes, aiming to bridge fundamental biology with clinical insight. I’m passionate about **connecting basic neurodevelopment with translational oncology**, and I’m driven by the belief that *understanding how we are built, cell by cell, gene by gene, is the key to revealing how diseases like cancer begin*. 

Beyond the lab, I love staying active, whether through running or working out, and I find balance in reading, cooking, and exploring new recipes. I also enjoy sharing science creatively—through **outreach**, visual design, and conversations that connect researchers, clinicians, and the wider community.
{% endcapture %}

{% capture col2 %}
{% include figure.html image="/images/Lab pic.jpg" %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}

## Highlights

{% capture text %}

Highlights from my research and scientific experiences, spanning regeneration, neurodegeneration, glioblastoma, neurodevelopment and embryonal brain tumors.

{%
  include button.html
  link="experience"
  text="Discover my experience"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Happy minibrain.webp"
  link="experience"
  title="Experience"
  text=text
%}

{% capture text %}

A glimpse into the studies that shaped my research in neuroscience and pediatric oncology.

{%
  include button.html
  link="publications"
  text="Browse my publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/GraphicalAbstract.webp"
  link="publications"
  title="Publications"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Technical and analytical skills that shape my approach to neuroscience and cancer research.

{%
  include button.html
  link="skills"
  text="Check out my skills"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Organoid 16d.webp"
  link="skills"
  title="Skills"
  text=text
%}
