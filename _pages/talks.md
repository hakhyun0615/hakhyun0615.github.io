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
  .talks-list .talk-venue > h2 {
    margin: 0.1rem 0 0;
    font-size: 1rem;
    font-weight: 500;
    line-height: 1.5;
    color: var(--global-text-color-light);
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
  }
  .talks-list .talk-date {
    font-size: 0.82rem;
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
    margin: 0.5rem 0 0;
    font-size: 0.9rem;
    line-height: 1.6;
    color: var(--global-text-color);
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
  <section class="talk-venue" aria-labelledby="talks-rabobank">
    <h2 id="talks-rabobank">Rabobank</h2>
    <ul class="talk-entries">
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">Explaining multi-agent behavior</h3>
          <p class="talk-description">Gave a talk to Rabobank’s data science team on how to define explanations of multi-agent behavior.</p>
        </div>
        <time class="talk-date" datetime="2026-07">July 2026</time>
      </li>
    </ul>
  </section>
</div>
