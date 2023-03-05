---
---

# Welcome to the Language and Intelligence Laboratory (LAILab)!

_“... to contribute to the prevention and cure of cancer.”_

{% include section.html %}

## Highlights

{% capture text %}

The Language and Intelligence Laboratory (LAILab) at the Machine Learning Department at Moffitt is a multidisciplinary research group that translates advances in natural language processing (NLP) and machine learning (ML) to solve low-resourced language understanding, language generation, and predictive medicine tasks in oncology and healthcare informatics. 

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

To accomplish multidimensional and multidisciplinary goals, we transfer and customize cutting edge methodologies in NLP and ML such as large language modeling, in-context inference, data augmentation, domain adaptation, etc. Our daily activities includes ultilization of fore-front deep neural network ecosystem and architectures on our Nvidia DGX server.

{%
  include button.html
  link="tools"
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

Our work involves: 
1) identification and standardization of functional status information in clinical notes of adult and senior cancer patients; 
2) information extraction and knowledge graph construction from clinical notes to assist cancer reristry and evidence-based predictive modeling; 
3) linking aging, comorbidities, and drugs to prostate cancer relapse and survival; 
4) predicting unplanned hospital readmission in the adult patients with gastrointestinal cancers initiating surgery; 
5) and other interdisciplinary projects as we expand our internal and external collobation networks.

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
