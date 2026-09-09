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
  <section class="talk-venue" aria-labelledby="talks-icml">
    <h2 id="talks-icml">ICML</h2>
    <ul class="talk-entries">
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">Position: Multi-Agent Explainability Needs Contracts Before Methods</h3>
          <p class="talk-description">Poster presentation · Position Paper Track</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">CLASP: Retrofitting Cost–Latency SLO Compliance onto Any LLM Router</h3>
          <p class="talk-description">Poster presentation · DEMO Workshop</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">PolicyLLM: Neuro-Symbolic Policy Extraction and Enforcement for Runtime AI Governance</h3>
          <p class="talk-description">Poster presentation · TAIGR Workshop</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
    </ul>
  </section>
  <section class="talk-venue" aria-labelledby="talks-acl">
    <h2 id="talks-acl">ACL</h2>
    <ul class="talk-entries">
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">Translation Is Not Representation: English-Hub Routing in Cross-Lingual Bias Benchmarks</h3>
          <p class="talk-description">Poster presentation · StereACuLT Workshop</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">Easy to Add, Hard to Erase: Causal Evidence on Stereotype Editing in LLMs</h3>
          <p class="talk-description">Poster presentation · StereACuLT Workshop</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
    </ul>
  </section>
  <section class="talk-venue" aria-labelledby="talks-rabobank">
    <h2 id="talks-rabobank">Rabobank</h2>
    <ul class="talk-entries">
      <li class="talk-entry">
        <div>
          <h3 class="talk-title">Explaining multi-agent behavior</h3>
          <p class="talk-description">Gave a talk to Rabobank’s data science team on how to define explanations of multi-agent behavior.</p>
        </div>
        <time class="talk-date" datetime="2026-07">Jul 2026</time>
      </li>
    </ul>
  </section>
</div>
