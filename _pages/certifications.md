---
layout: page
permalink: /certifications/
title: certifications
description:
nav: true
nav_order: 3
---

<style>
  .certifications-list {
    margin-top: 2rem;
  }
  .certifications-list .certification-category {
    display: grid;
    grid-template-columns: 8rem minmax(0, 1fr);
    gap: 1.75rem;
    margin-top: 1.8rem;
    padding-top: 1.1rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .certifications-list .certification-category:first-child {
    margin-top: 0;
  }
  .certifications-list .certification-category > h2 {
    margin: 0.1rem 0 0;
    font-size: 1.1rem;
    line-height: 1.5;
    font-weight: 500;
    color: var(--global-text-color-light);
  }
  .certifications-list .credential-list {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  .certifications-list .credential {
    padding: 0 0 1rem;
  }
  .certifications-list .credential + .credential {
    padding-top: 1rem;
    border-top: 1px solid color-mix(in srgb, var(--global-text-color) 7%, transparent);
  }
  .certifications-list .credential:last-child {
    padding-bottom: 0;
  }
  .certifications-list .credential-heading {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    align-items: baseline;
    gap: 1rem;
  }
  .certifications-list .credential-heading h3 {
    margin: 0;
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.45;
    color: var(--global-text-color);
  }
  .certifications-list time {
    font-size: 0.82rem;
    font-weight: 300;
    line-height: 1.5;
    color: var(--global-text-color-light);
    white-space: nowrap;
  }
  .certifications-list .credential-issuer {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 0.4rem 0.7rem;
    margin: 0.3rem 0 0;
    font-size: 0.9rem;
    font-weight: 300;
    line-height: 1.5;
    color: var(--global-text-color-light);
  }
  .certifications-list .credential-id {
    margin: 0.3rem 0 0;
    font-size: 0.73rem;
    line-height: 1.5;
    color: var(--global-text-color-light);
    overflow-wrap: anywhere;
  }
  .certifications-list .credential-id code {
    margin-left: 0.25rem;
    padding: 0;
    font-size: inherit;
    color: inherit;
    background: none;
  }
  @media (max-width: 575px) {
    .certifications-list .certification-category {
      grid-template-columns: minmax(0, 1fr);
      gap: 0.85rem;
      margin-top: 1.5rem;
    }
    .certifications-list .credential-heading {
      gap: 0.75rem;
    }
    .certifications-list .credential-heading h3 {
      font-size: 1rem;
    }
    .certifications-list time {
      font-size: 0.75rem;
    }
  }
</style>

<div class="certifications-list">
  <section class="certification-category" aria-labelledby="certifications-ai-data">
    <h2 id="certifications-ai-data">AI &amp; Data</h2>
    <ul class="credential-list">
      <li class="credential">
        <div class="credential-heading">
          <h3>TensorFlow Developer</h3>
          <time datetime="2024-04" aria-label="April 2024">Apr 2024</time>
        </div>
        <p class="credential-issuer">TensorFlow Certificate Program</p>
        <p class="credential-id">Credential ID <code>102450054</code></p>
      </li>
      <li class="credential">
        <div class="credential-heading">
          <h3>Machine Learning Specialization</h3>
          <time datetime="2024-03" aria-label="March 2024">Mar 2024</time>
        </div>
        <p class="credential-issuer">Stanford University</p>
        <p class="credential-id">Credential ID <code>RMNSTYNLRLX5</code></p>
      </li>
      <li class="credential">
        <div class="credential-heading">
          <h3>Deep Learning Specialization</h3>
          <time datetime="2023-10" aria-label="October 2023">Oct 2023</time>
        </div>
        <p class="credential-issuer">DeepLearning.AI</p>
        <p class="credential-id">Credential ID <code>8Y3XRDQA6HDB</code></p>
      </li>
      <li class="credential">
        <div class="credential-heading">
          <h3>Big Data Analysis Engineer</h3>
          <time datetime="2022-07" aria-label="July 2022">Jul 2022</time>
        </div>
        <p class="credential-issuer">Korea Data Agency</p>
      </li>
    </ul>
  </section>
  <section class="certification-category" aria-labelledby="certifications-project-management">
    <h2 id="certifications-project-management">Project Management</h2>
    <ul class="credential-list">
      <li class="credential">
        <div class="credential-heading">
          <h3>Certified ScrumMaster (CSM)</h3>
          <time datetime="2025-10" aria-label="October 2025">Oct 2025</time>
        </div>
        <p class="credential-issuer">Scrum Alliance</p>
        <p class="credential-id">Credential ID <code>2130286</code></p>
      </li>
      <li class="credential">
        <div class="credential-heading">
          <h3>Google Project Management</h3>
          <time datetime="2025-10" aria-label="October 2025">Oct 2025</time>
        </div>
        <p class="credential-issuer">Google</p>
        <p class="credential-id">Credential ID <code>E7XHI3POS6XR</code></p>
      </li>
    </ul>
  </section>
  <section class="certification-category" aria-labelledby="certifications-cloud">
    <h2 id="certifications-cloud">Cloud</h2>
    <ul class="credential-list">
      <li class="credential">
        <div class="credential-heading">
          <h3>Cloud Digital Leader</h3>
          <time datetime="2025-10" aria-label="October 2025">Oct 2025</time>
        </div>
        <p class="credential-issuer">Google</p>
        <p class="credential-id">Credential ID <code>110519</code></p>
      </li>
    </ul>
  </section>
  <section class="certification-category" aria-labelledby="certifications-wine">
    <h2 id="certifications-wine">Wine</h2>
    <ul class="credential-list">
      <li class="credential">
        <div class="credential-heading">
          <h3>WSET Level 2 Award in Wines (Passed with Merit)</h3>
          <time datetime="2023-12" aria-label="December 2023">Dec 2023</time>
        </div>
        <p class="credential-issuer">WSET</p>
      </li>
      <li class="credential">
        <div class="credential-heading">
          <h3>WSET Level 1 Award in Wines</h3>
          <time datetime="2023-01" aria-label="January 2023">Jan 2023</time>
        </div>
        <p class="credential-issuer">WSET</p>
      </li>
    </ul>
  </section>
</div>
