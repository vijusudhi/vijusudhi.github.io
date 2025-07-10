---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Master of Science** - Digital Engineering, Otto von Guericke Universität, Magdeburg, Germany, 2022
* **Bachelor of Technology** - Electronics and Communication Engineering, Sree Chitra Thirunal College of Engineering, Trivandrum, India, 2016

Work experience
======
* *07/2022 - Present:* **Research Associate / PhD Student**, Bielefeld University, Bielefeled, Germany
  * LLM4KMU

* *05/2022 - 07/2025:* **Research Engineer**, Fraunhofer IAIS, Dresden, Germany
    * Developed text embedding models from decoder-only LLMs using contrastive learning. Resultant models significantly outperformed the base models and were replaced as retriever models in the In-House Conversational QA system. 
    * Conducted research on the applicability of LLMs to address classification and regression tasks with tabular data from ERP systems.
    * Built Conversational QA systems exploring conventional and advanced RAG approaches. Fine-tuned and evaluated both retriever and reader models. Extended the system by incorporating model-agnostic explanations to help users understand the model responses better. 
    * Explored modular and end-to-end approaches for task-oriented dialog systems, focusing on LLMs as customer service agents. Conducted comprehensive evaluation of open-source LLMs fine tuned with different PEFT techniques. 

* *04/2021 - 12/2021:* **Master Thesis**, AUDI AG, Ingolstadt, Germany
  * Developed "BiTe-REx", a bilingual text retrieval system (English - German) with model-agnostic explanations specifically designed for the automotive domain. This system facilitates competitor analysis tasks for users working in both English and German.

* *08/2019 - 04/2021:* **Student Research Assistant**, ifak - Institut für Automation und Kommunikation, Magdeburg, Germany
  * Developed "ReForm", an algorithm for the automated formalization of natural language industrial requirements into test cases. The system utilizes dependency rules like Part-of-Speech (POS) and Named Entity Recognition (NER) alongside semantic role labels (SRL).

* *11/2016 - 03/2019:* **Senior Engineer**, Tata Elxsi Limited, Trivandrum, India
  * Maintained and updated MCAL Driver code for diverse Renesas micro-controllers in accordance with AUTOSAR standards on different communication protocols.

[//]: # (Skills)

[//]: # (======)

[//]: # (* Python)

[//]: # ()
[//]: # (* GenAI)

[//]: # ()
[//]: # (* NLP)

[//]: # ()
[//]: # (* PyTorch)

[//]: # ()
[//]: # (* Sub-skill 2.3)

[//]: # ()
[//]: # (* Skill 3)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!---
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
