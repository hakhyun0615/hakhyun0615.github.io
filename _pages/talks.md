---
layout: page
permalink: /talks/
title: talks
description:
nav: true
nav_order: 5
---

<style>
  .talks-list {
    margin-top: 2rem;
  }
  .talks-list .talk-venue {
    display: grid;
    grid-template-columns: 8rem minmax(0, 1fr);
    gap: 1.75rem;
    padding-top: 1.1rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .talks-list .talk-venue + .talk-venue {
    margin-top: 1.8rem;
  }
  .talks-list .talk-venue > h2 {
    margin: 0.1rem 0 0;
    font-size: 1.1rem;
    font-weight: 500;
    line-height: 1.5;
    color: var(--global-theme-color);
  }
  .talks-list .talk-entries {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  .talks-list .talk-entry {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    align-items: baseline;
    column-gap: 1.5rem;
    padding: 0 0 1.2rem;
  }
  .talks-list .talk-entry + .talk-entry {
    padding-top: 1.2rem;
    border-top: 1px solid color-mix(in srgb, var(--global-text-color) 7%, transparent);
  }
  .talks-list .talk-entry:last-child {
    padding-bottom: 0;
  }
  .talks-list .talk-date {
    font-size: 0.82rem;
    font-weight: 300;
    line-height: 1.5;
    white-space: nowrap;
    color: var(--global-text-color-light);
  }
  .talks-list .talk-title {
    margin: 0;
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.45;
    color: var(--global-text-color);
  }
  .talks-list .talk-description {
    margin: 0.3rem 0 0;
    font-size: 0.9rem;
    font-weight: 300;
    line-height: 1.5;
    color: var(--global-text-color-light);
  }
  @media (max-width: 575px) {
    .talks-list .talk-venue {
      grid-template-columns: minmax(0, 1fr);
      gap: 0.85rem;
    }
    .talks-list .talk-title {
      font-size: 1rem;
    }
    .talks-list .talk-entry {
      column-gap: 0.75rem;
    }
    .talks-list .talk-date {
      font-size: 0.75rem;
    }
  }
</style>

<div class="talks-list">
  <section class="talk-venue" aria-labelledby="talks-conferences">
    <h2 id="talks-conferences">Conferences</h2>
    <ul class="talk-entries">
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">ICML 2026</h3>
          <p class="talk-description">Poster presentations on multi-agent explainability, LLM routing, and runtime governance.</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">ACL 2026</h3>
          <p class="talk-description">Poster presentations on cross-lingual bias evaluation and stereotype editing in LLMs.</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
    </ul>
  </section>
  <section class="talk-venue" aria-labelledby="talks-industry">
    <h2 id="talks-industry">Industry</h2>
    <ul class="talk-entries">
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">Rabobank</h3>
          <p class="talk-description">A talk on explaining multi-agent behavior for the data science team.</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
    </ul>
  </section>
</div>
