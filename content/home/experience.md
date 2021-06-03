---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: Tsinghua University, THUNLP
    company_url: 'https://nlp.csai.tsinghua.edu.cn/'
    location: Beijing, China
    date_start: '2019-10-01'
    date_end: ''
    description: |2-
        Project: Sentence-Level Pretraining for Document-Level RE (2020.07 ~ 2021.03)

        * Designed Sentence-Level ELECTRA pretraining task to learn better sentence representation from large corpus.
        * Disigned Entity Context Prediction pretraining task to learn better entity representation from large corpus.
        * Improved F1 score on DocRED comparing to BERT-based baseline by fine-tuning with above.

        Project: Joint Extraction of Evidence and Relation for Document-Level RE (2019.11 ~ 2020.07)

        * Jointly extract evidence and relation to help both evidence extraction and relation extraction.
        * Devised a bilinear based entity feature extraction module to improve the relation extraction performance.
        * Improved relation extraction F1 score on DocRED using a novel evidence-guided-attention mechanism.

  - title: Computer Vision Algorithm Engineer
    company: YITU Tech
    company_url: 'https://www.yitutech.com/en'
    location: Beijing, China
    date_start: '2020-09-07'
    date_end: '2020-12-15'
    description: Design and implement algorithm for RE-ID.

  - title: Research Assistant
    company: Beihang University
    company_url: 'https://ev.buaa.edu.cn/'
    location: Beijing, China
    date_start: '2019-10-01'
    date_end: '2020-07-01'
    description: |2-
        Project: Cross-Modal Omni Interaction Modeling for Phrase Grounding

        * Adressed the phrase grounding accuracy problem as the primary researcher.
        * Devised a novel model to capture complex spatial and semantic relationship among image regions and phrases through multi-level multi-modal interactin.
        * THe new method improved the grounding accuracy for 6.15% on Flickr30K Entities and 21.25% on ReferItGame.

design:
  columns: '2'
---
