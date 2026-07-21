---
layout: about
title: about
permalink: /
subtitle: Undergraduate student in Artificial Intelligence at Nanjing University.

profile:
  align: right

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<div class="home-focus">
  <p class="home-eyebrow">Embodied AI · Evaluation Infrastructure</p>
  <p class="home-lede">I build simulation environments, task definitions, and evaluation pipelines for embodied AI. My current goal is to make general-purpose robot agents easier to test, compare, and improve.</p>

  <dl class="home-record" aria-label="Academic record">
    <div>
      <dt>4.63 / 5.00</dt>
      <dd>GPA</dd>
    </div>
    <div>
      <dt>1 / 104</dt>
      <dd>Class rank</dd>
    </div>
    <div>
      <dt>ICPC Gold</dt>
      <dd>Chengdu Regional, 2025</dd>
    </div>
    <div>
      <dt>CCSP Gold</dt>
      <dd>2025</dd>
    </div>
  </dl>

  <section class="home-section">
    <h2>Current work</h2>
    <p>In an embodied-AI research project, I am building and validating simulated benchmark tasks with Blender, Isaac Sim, and Isaac Lab.</p>
    <p><a href="{{ '/projects/#research' | relative_url }}">Explore the research direction</a> <span aria-hidden="true">→</span></p>
  </section>

  <section class="home-section home-section-compact">
    <h2>Writing</h2>
    <p>I use this site to keep concise technical notes and research reflections while the work is in progress. <a href="{{ '/blog/' | relative_url }}">Read the notes</a> or <a href="{{ '/assets/rendercv/rendercv_output/Taiye_Lu_CV.pdf' | relative_url }}">download my CV</a>.</p>
  </section>
</div>

<style>
  .home-focus {
    margin-top: 1.5rem;
  }

  .home-eyebrow {
    margin: 0 0 0.55rem;
    color: var(--global-theme-color);
    font-size: 0.86rem;
    font-weight: 600;
    letter-spacing: 0;
    text-transform: uppercase;
  }

  .home-lede {
    max-width: 44rem;
    margin: 0;
    font-size: 1.12rem;
    line-height: 1.65;
  }

  .home-record {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 1rem;
    margin: 1.75rem 0;
    padding: 1rem 0;
    border-top: 1px solid var(--global-divider-color, #d9d9d9);
    border-bottom: 1px solid var(--global-divider-color, #d9d9d9);
  }

  .home-record dt {
    font-size: 1.1rem;
    font-weight: 650;
    line-height: 1.25;
  }

  .home-record dd {
    margin: 0.2rem 0 0;
    color: var(--global-text-color-light, #666);
    font-size: 0.82rem;
    line-height: 1.35;
  }

  .home-section {
    max-width: 44rem;
    padding: 0.25rem 0 0.4rem;
  }

  .home-section h2 {
    margin: 0 0 0.35rem;
    font-size: 1.1rem;
  }

  .home-section p {
    margin: 0 0 0.7rem;
    line-height: 1.6;
  }

  .home-section-compact {
    margin-top: 0.35rem;
  }

  @media (max-width: 600px) {
    .home-record {
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.9rem 1rem;
    }

    .home-lede {
      font-size: 1.05rem;
    }
  }
</style>
