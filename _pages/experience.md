---
layout: page
permalink: /experience/
title: experience
description:
nav: true
nav_order: 2
---

<style>
  .experience-list {
    margin-top: 2rem;
  }
  .experience-list .experience-section {
    display: grid;
    grid-template-columns: 8rem minmax(0, 1fr);
    gap: 1.75rem;
    padding-top: 1.1rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .experience-list .experience-section + .experience-section {
    margin-top: 1.8rem;
  }
  .experience-list .experience-section > h2 {
    margin: 0.1rem 0 0;
    font-size: 1.1rem;
    font-weight: 500;
    line-height: 1.5;
    color: var(--global-text-color-light);
  }
  .experience-list .experience-entry {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    align-items: baseline;
    column-gap: 1.5rem;
    padding: 0 0 1.2rem;
  }
  .experience-list .experience-entry + .experience-entry {
    padding-top: 1.2rem;
    border-top: 1px solid color-mix(in srgb, var(--global-text-color) 7%, transparent);
  }
  .experience-list .experience-entry:last-child {
    padding-bottom: 0;
  }
  .experience-list .experience-title {
    margin: 0;
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.45;
    color: var(--global-text-color);
  }
  .experience-list .experience-role {
    margin: 0.35rem 0 0;
    font-size: 0.9rem;
    line-height: 1.6;
    color: var(--global-text-color-light);
  }
  .experience-list .experience-date {
    font-size: 0.82rem;
    line-height: 1.5;
    white-space: nowrap;
    color: var(--global-text-color-light);
  }
  @media (max-width: 575px) {
    .experience-list .experience-section {
      grid-template-columns: minmax(0, 1fr);
      gap: 0.85rem;
    }
    .experience-list .experience-entry {
      grid-template-columns: minmax(0, 1fr);
      row-gap: 0.35rem;
    }
    .experience-list .experience-title {
      font-size: 1rem;
    }
    .experience-list .experience-date {
      grid-row: 2;
      font-size: 0.75rem;
    }
  }
</style>

<div class="experience-list">
  <section class="experience-section" aria-labelledby="research-programs">
    <h2 id="research-programs">Research Programs</h2>
    <div class="experience-entries">
      <article class="experience-entry" aria-labelledby="experience-iliad">
        <div>
          <h3 class="experience-title" id="experience-iliad">Iliad Intensive</h3>
          <p class="experience-role">Berkeley, California</p>
        </div>
        <time class="experience-date" datetime="2026-08">Aug 2026</time>
      </article>
      <article class="experience-entry" aria-labelledby="experience-bluedot">
        <div>
          <h3 class="experience-title" id="experience-bluedot">BlueDot Impact Technical AI Safety Project</h3>
          <p class="experience-role">Remote</p>
        </div>
        <span class="experience-date"><time datetime="2026-07">Jul 2026</time> – <time datetime="2026-08-17">Aug 2026</time></span>
      </article>
      <article class="experience-entry" aria-labelledby="experience-google">
        <div>
          <h3 class="experience-title" id="experience-google">Google Machine Learning Bootcamp</h3>
          <p class="experience-role">Seoul, South Korea</p>
        </div>
        <span class="experience-date"><time datetime="2023-09">Sep 2023</time> – <time datetime="2023-12">Dec 2023</time></span>
      </article>
    </div>
  </section>
  <section class="experience-section" aria-labelledby="work-experience">
    <h2 id="work-experience">Work Experience</h2>
    <div class="experience-entries">
      <article class="experience-entry" aria-labelledby="experience-release">
        <div>
          <h3 class="experience-title" id="experience-release">ReLease Agent</h3>
          <p class="experience-role">Founder · Seoul, South Korea</p>
        </div>
        <span class="experience-date"><time datetime="2025-01">Jan 2025</time> – Present</span>
      </article>
      <article class="experience-entry" aria-labelledby="experience-wonbuilding">
        <div>
          <h3 class="experience-title" id="experience-wonbuilding">Wonbuilding Real Estate Consulting</h3>
          <p class="experience-role">Technical Product Manager (TPM) &amp; Lead Software Engineer · Seoul, South Korea</p>
        </div>
        <span class="experience-date"><time datetime="2023-04">Apr 2023</time> – <time datetime="2024-12">Dec 2024</time></span>
      </article>
    </div>
  </section>
  <section class="experience-section" aria-labelledby="leadership">
    <h2 id="leadership">Leadership</h2>
    <div class="experience-entries">
      <article class="experience-entry" aria-labelledby="experience-consulting">
        <div>
          <h3 class="experience-title" id="experience-consulting">Dartmouth Graduate Consulting Group</h3>
          <p class="experience-role">Vice President</p>
        </div>
        <span class="experience-date"><time datetime="2025-11">Nov 2025</time> – Present</span>
      </article>
    </div>
  </section>
</div>
