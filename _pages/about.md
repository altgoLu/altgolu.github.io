---
layout: about
title: about
permalink: /
subtitle:

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<div class="homepage-academic">
  <aside class="homepage-sidebar">
    <h1>Taiye Lu</h1>
    <p class="homepage-affiliation">Nanjing University</p>
    <p>Undergraduate student in Artificial Intelligence.</p>
    <p>Nanjing, China</p>
    <ul class="homepage-links">
      <li><a href="https://github.com/altgoLu">GitHub</a></li>
      <li><a href="{{ '/assets/rendercv/rendercv_output/Taiye_Lu_CV.pdf' | relative_url }}">CV (PDF)</a></li>
    </ul>
  </aside>

  <div class="homepage-content">
    <p>Hi, I am Taiye Lu. I study Artificial Intelligence at Nanjing University and am currently working on the infrastructure behind embodied-AI research: simulation environments, task definitions, and evaluation pipelines.</p>

    <p>My interest is in making general-purpose robot agents easier to test, compare, and improve under clear, repeatable conditions.</p>

    <h2 id="research">🔬 Research</h2>
    <p>I am building and validating simulated benchmark tasks with Blender, Isaac Sim, and Isaac Lab. The work connects environment design, data generation, and evaluation for embodied agents.</p>
    <p><a href="{{ '/projects/#research' | relative_url }}">Embodied AI Systems</a> · <a href="{{ '/projects/#systems' | relative_url }}">Agent Systems</a></p>

    <h2 id="honors">🎖 Honors and Awards</h2>
    <ul>
      <li><em>2025.</em> Gold Medal, ICPC Chengdu Regional Contest.</li>
      <li><em>2025.</em> Gold Medal, CCSP.</li>
    </ul>

    <h2 id="education">🎓 Education</h2>
    <ul>
      <li><em>Present.</em> Undergraduate in Artificial Intelligence, Nanjing University.</li>
      <li><em>Academic record.</em> GPA 4.63 / 5.00, ranked 1st out of 104 students.</li>
    </ul>

    <h2 id="notes">✍️ Notes</h2>
    <p>I keep short technical notes and research reflections while the work is in progress. <a href="{{ '/blog/' | relative_url }}">Read the notes</a>.</p>
  </div>
</div>

<style>
  .post-header {
    display: none;
  }

  .homepage-academic {
    display: grid;
    grid-template-columns: minmax(11rem, 15rem) minmax(0, 1fr);
    gap: 3.5rem;
    max-width: 66rem;
    margin: 2.5rem auto 0;
  }

  .homepage-sidebar {
    align-self: start;
    position: sticky;
    top: 5.5rem;
    color: var(--global-text-color-light, #555);
    font-size: 0.94rem;
    line-height: 1.55;
  }

  .homepage-sidebar h1 {
    margin: 0 0 0.25rem;
    color: var(--global-text-color);
    font-size: 1.65rem;
    font-weight: 650;
    letter-spacing: 0;
  }

  .homepage-sidebar p {
    margin: 0 0 0.35rem;
  }

  .homepage-sidebar .homepage-affiliation {
    color: var(--global-text-color);
    font-weight: 600;
  }

  .homepage-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.2rem 0.85rem;
    margin: 1rem 0 0;
    padding: 0;
    list-style: none;
  }

  .homepage-content {
    max-width: 46rem;
    font-size: 1rem;
    line-height: 1.72;
  }

  .homepage-content p {
    margin: 0 0 1rem;
  }

  .homepage-content h2 {
    margin: 2rem 0 0.65rem;
    padding-top: 0.65rem;
    border-top: 1px solid var(--global-divider-color, #d9d9d9);
    font-size: 1.2rem;
    font-weight: 650;
    letter-spacing: 0;
  }

  .homepage-content ul {
    margin: 0 0 1rem;
    padding-left: 1.15rem;
  }

  .homepage-content li {
    margin-bottom: 0.38rem;
    padding-left: 0.1rem;
  }

  .homepage-content em {
    color: var(--global-text-color-light, #666);
    font-style: normal;
    font-weight: 600;
  }

  @media (max-width: 700px) {
    .homepage-academic {
      grid-template-columns: 1fr;
      gap: 1.6rem;
      margin-top: 1.5rem;
    }

    .homepage-sidebar {
      position: static;
      padding-bottom: 1.25rem;
      border-bottom: 1px solid var(--global-divider-color, #d9d9d9);
    }

    .homepage-content h2:first-of-type {
      margin-top: 0.6rem;
    }
  }
</style>
