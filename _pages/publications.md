---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 1
research_topics:
  - id: interpretability-training
    title: Mechanistic Interpretability & Training Dynamics
    subtopics:
      - id: sparse-autoencoders
        title: Sparse Autoencoders
      - id: multilingual
        title: Multilingual Models
      - id: interventions
        title: Interventions
      - id: training-dynamics
        title: Training Dynamics
      - id: vision-language
        title: Vision–Language Models
      - id: world-models
        title: World Models
      - id: situational-awareness
        title: Situational Awareness
      - id: interpretable-architectures
        title: Interpretable Architectures
      - id: interpretability-evaluation
        title: Interpretability Evaluation
  - id: multi-agent
    title: Multi-Agent Systems
  - id: systems
    title: AI Systems
  - id: applied
    title: Applied Machine Learning
---

<style>
  /* Match Experience's quiet headings and ruled entries. */
  .publications .publication-section + .publication-section {
    margin-top: 2.5rem;
  }
  .publications .publication-section > h2 {
    margin: 0 0 1rem;
    font-size: 1.2rem;
    font-weight: 600;
    line-height: 1.5;
    color: var(--global-text-color-light);
  }
  .publications .publication-subsection + .publication-subsection {
    margin-top: 1rem;
  }
  .publications .publication-subsection > h3 {
    margin: 0 0 0.4rem;
    font-size: 0.85rem;
    font-weight: 500;
    line-height: 1.5;
    color: var(--global-text-color-light);
  }
  .publications ol.bibliography {
    margin: 0;
  }
  .publications ol.bibliography > li {
    margin: 0;
    padding: 1.1rem 0 1.5rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .publications .publication-subsection ol.bibliography > li {
    padding: 0.8rem 0 1rem;
  }

  /* Use the full content width; each venue is already written below its title. */
  .publications ol.bibliography li .row {
    display: block;
    margin-left: 0;
    margin-right: 0;
  }
  .publications ol.bibliography li .col.col-sm-2.abbr {
    display: none;
  }
  .publications ol.bibliography li .col-sm-8 {
    width: 100%;
    max-width: none;
    padding: 0;
    display: flex;
    flex-direction: column;
  }
  .publications ol.bibliography li .col-sm-8 > .title { order: 1; }
  .publications ol.bibliography li .col-sm-8 > .author { order: 2; }
  .publications ol.bibliography li .col-sm-8 > .periodical:not(:has(.rq)) { order: 3; }
  .publications ol.bibliography li .col-sm-8 > .periodical:has(.rq) { order: 4; }
  .publications ol.bibliography li .col-sm-8 > .links { order: 5; }

  .publications ol.bibliography li .title {
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.45;
  }
  .publications ol.bibliography li .author {
    margin-top: 0.35rem;
    font-size: 0.9rem;
    line-height: 1.6;
    color: var(--global-text-color-light);
  }
  .publications ol.bibliography li .periodical:not(:has(.rq)) {
    font-size: 0.85rem;
    font-weight: 300;
    line-height: 1.6;
    color: var(--global-text-color-light);
  }
  .publications ol.bibliography li .periodical:not(:has(.rq)) em {
    color: inherit;
    font-weight: inherit;
    font-style: normal;
  }
  /* Preserve original-paper links and the expandable research answers. */
  .publications ol.bibliography li .title a {
    color: inherit;
    text-decoration: none;
  }
  .publications ol.bibliography li .title a:hover {
    text-decoration: underline;
    text-underline-offset: 3px;
  }

  .publications ol.bibliography li .rq {
    display: block;
    margin-top: 0.6rem;
    padding: 0.6rem 0.8rem;
    border: 1px solid color-mix(in srgb, var(--global-text-color) 18%, transparent);
    border-radius: 6px;
    background-color: var(--global-bg-color);
    transition: border-color 0.15s ease;
  }
  .publications ol.bibliography li details.rq:hover {
    border-color: color-mix(in srgb, var(--global-text-color) 35%, transparent);
  }

  .publications ol.bibliography li .rq > summary {
    cursor: pointer;
    color: var(--global-text-color);
    list-style: none;
  }
  .publications ol.bibliography li .rq > summary::-webkit-details-marker {
    display: none;
  }

  .publications ol.bibliography li .rq > .rq-answer {
    margin: 0.55rem 0 0 0;
    opacity: 0.9;
  }

  @media (max-width: 575px) {
    .publications ol.bibliography li .title {
      font-size: 1rem;
    }
  }
</style>

{% include bib_search.liquid %}

<div class="publications">
  {% for topic in page.research_topics %}
    <section class="publication-section" aria-labelledby="topic-{{ topic.id }}">
      <h2 id="topic-{{ topic.id }}">{{ topic.title }}</h2>
      {% if topic.subtopics %}
        {% for subtopic in topic.subtopics %}
          <section class="publication-subsection" aria-labelledby="topic-{{ topic.id }}-{{ subtopic.id }}">
            <h3 id="topic-{{ topic.id }}-{{ subtopic.id }}">{{ subtopic.title }}</h3>
            {% bibliography --query @*[research_topic={{subtopic.id}}] %}
          </section>
        {% endfor %}
      {% else %}
        {% bibliography --query @*[research_area={{topic.id}}] %}
      {% endif %}
    </section>
  {% endfor %}
</div>
