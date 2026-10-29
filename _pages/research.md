---
permalink: /research/
title: "Research"

header:
  overlay_color: "#4e2a84"
  overlay_filter: "0.0"

classes:
  - solid-header-formatting
  - item-list

project1:
  - image_path: /assets/images/c3-placeholder.png
    alt: "satyrn placeholder image"
    title: "Satyrn"
    excerpt: 'A conversational system for interacting with your data.'
    contact: "Cameron Barrie, Marko Sterbentz"
project2:
  - image_path: /assets/images/projects/tytan.png
    alt: "Tytan logo"
    logo: true
    title: "Tytan"
    excerpt: 'Data analysis tools like natural-language query interfaces and automated report generators need a semantic description of the data they sit on: what real-world entities it contains, which columns are measures or identifiers, and how tables connect into units of analysis. That layer is usually written by hand, slow, error-prone, and a standing dependency on experts. Tytan builds it automatically from a relational database and, when available, a short user-provided description. It pairs symbolic analysis of the database with LLM-based semantic inference to propose entities, assign roles, and name them, and when the evidence leaves a decision ambiguous, it asks the user a targeted question rather than guessing.'
    contact: "Donna Hooshmand"
project3:
  - image_path: /assets/images/c3-placeholder.png
    alt: "mentora placeholder image"
    title: "Erasmus"
    excerpt: 'A student companion that operationalizes individual tutoring based on goals and instructions of the course and student understanding. Grounded in the learning sciences, Erasmus helps in building intellectual agency through productive engagement, thinking to have the best possible interaction to help the student to learn instead of being focused on answering questions correctly.'
    contact: "Shubham Shahi"
project4:
  - image_path: /assets/images/c3-placeholder.png
    alt: "Retina painter image"
    title: "RetinaPainter"
    excerpt: 'Emerging retinal biomarkers are subtle, rare, and annotatable only by specialists working slice by slice through OCT volumes, leaving datasets far too small for conventional supervised training. RetinaPainter is an interactive annotation and training platform that lets a clinician load a new OCT dataset and build a working detection model from a few dozen images. It replaces the train-from-scratch U-Net of earlier machine-teaching tools with a retinal foundation model backbone that updates in near real time as the expert brushes corrections onto its predictions, and stages training as a curriculum: synthetic lesions, then clear real cases, then faint or ambiguous ones.'
    contact: "Donna Hooshmand"
project5:
  - image_path: /assets/images/c3-placeholder.png
    alt: "curriculum learning placeholder image"
    title: "Curriculum Learning for Efficient 3D Radiology Report Generation"
    excerpt: 'Training vision-language models on full 3D scans paired with radiology text is expensive and hard to scale. This project develops a curriculum-learning framework for training a 3D vision-language model that generates chest CT reports from paired volumetric scans and reports. Rather than training on full reports from the start, the model learns in stages: first the clinical impression, then selected high-yield findings, then fuller report content. The framework combines volumetric CT encoding, long-range sequence modeling, and clinically pretrained language components to ease early optimization, stabilize training, and make better use of limited compute, lowering the barrier for groups without large-scale infrastructure to build and adapt radiology AI.'
    contact: "Aryan Dwivedi, Donna Hooshmand"
---

{% include project_row.html id="project1" type="left" %}

{% include project_row.html id="project2" type="left" %}

{% include project_row.html id="project3" type="left" %}

{% include project_row.html id="project4" type="left" %}

{% include project_row.html id="project5" type="left" %}

[Past Projects](/past_projects/)
