---
layout: page
permalink: /teaching/
title: teaching
description:
nav: true
nav_order: 4
---

<style>
  .teaching-list {
    margin-top: 2rem;
  }
  .teaching-list .teaching-institution {
    display: grid;
    grid-template-columns: 8rem minmax(0, 1fr);
    gap: 1.75rem;
    padding-top: 1.1rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .teaching-list .teaching-institution > h2 {
    margin: 0.1rem 0 0;
    font-size: 1.1rem;
    font-weight: 500;
    line-height: 1.5;
    color: var(--global-theme-color);
  }
  .teaching-list .teaching-term {
    font-size: 0.82rem;
    font-weight: 300;
    line-height: 1.5;
    white-space: nowrap;
    color: var(--global-text-color-light);
  }
  .teaching-list .teaching-courses {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  .teaching-list .teaching-courses li {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    align-items: baseline;
    gap: 1rem;
    padding: 1rem 0;
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.45;
    color: var(--global-text-color);
  }
  .teaching-list .teaching-courses li:first-child {
    padding-top: 0;
  }
  .teaching-list .teaching-courses li + li {
    border-top: 1px solid color-mix(in srgb, var(--global-text-color) 7%, transparent);
  }
  .teaching-list .teaching-courses li:last-child {
    padding-bottom: 0;
  }
  @media (max-width: 575px) {
    .teaching-list .teaching-institution {
      grid-template-columns: minmax(0, 1fr);
      gap: 0.85rem;
    }
    .teaching-list .teaching-courses li {
      gap: 0.75rem;
      font-size: 1rem;
    }
    .teaching-list .teaching-term {
      font-size: 0.75rem;
    }
  }
</style>

<div class="teaching-list">
  <section class="teaching-institution" aria-labelledby="teaching-dartmouth">
    <h2 id="teaching-dartmouth">Dartmouth College</h2>
    <ul class="teaching-courses" aria-label="Courses">
      <li>
        <span>Applied Computer Science</span>
        <span class="teaching-term">Fall 2025</span>
      </li>
      <li>
        <span>Artificial Intelligence</span>
        <span class="teaching-term">Fall 2025</span>
      </li>
      <li>
        <span>Advanced Natural Language Processing</span>
        <span class="teaching-term">Winter 2025</span>
      </li>
      <li>
        <span>Machine Learning and Statistical Data Analysis</span>
        <span class="teaching-term">Spring 2026</span>
      </li>
    </ul>
  </section>
</div>
