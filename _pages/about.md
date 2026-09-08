---
layout: about
title: about
permalink: /
subtitle: M.S. in Computer Science, <a href='https://home.dartmouth.edu/'>Dartmouth College</a>

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* Keep the portrait compact and preserve its natural proportions. */
  .profile {
    width: min(70%, 240px);
    margin: 0 auto 1.5rem;
  }

  .profile figure {
    margin: 0;
  }

  .profile picture,
  .profile img {
    display: block;
    width: 100%;
    height: auto;
  }

  @media (max-width: 575.98px) {
    .post article {
      display: flex;
      flex-direction: column;
    }

    .post article > .profile {
      margin-left: 0;
      margin-right: auto;
    }
  }

  @media (min-width: 576px) {
    .profile {
      width: 19%;
      margin: 0 1rem 1rem 0;
    }
  }

  /* Keep the social links compact. */
  .social .contact-icons {
    font-size: 2.2rem;
  }
</style>

I am an M.S. student in Computer Science at Dartmouth College, advised by [Soroush Vosoughi](https://www.cs.dartmouth.edu/~soroush/) and [Peter Chin](https://sites.dartmouth.edu/lisplab/). Before Dartmouth, I received my B.S. in Electronic and Electrical Engineering from Sungkyunkwan University, where I was advised by [Hayoung Oh](https://sites.google.com/site/hyoh79/).

My research focuses on **AI safety**. I combine controlled experiments and mathematical analysis to study how internal representations shape behavior and to evaluate the reliability of AI systems.

My research spans mechanistic interpretability, training dynamics and generalization, multilingual and multimodal AI, model merging, world models, situational awareness, AI systems, and multi-agent systems. (See [Publications]({{ '/publications/' | relative_url }}) for research questions.)

**My goal is to design AI models that circumvent the need for post-hoc reverse-engineering and post-training alignment interventions. My research investigates how to construct inherently interpretable architectures with legible world models, and how pretraining paradigms dictate the internal computations that naturally drive aligned behavior.**
