---
layout: single
title: Interactive Data Science Lab
permalink: /lab/
classes:
  - cv-modern
author_profile: false
---

<section class="cv-page-hero">
  <p class="cv-kicker">Interactive technical notes</p>
  <h1>Data science ideas you can manipulate.</h1>
  <p>
    Small interactive demonstrations that expose the mechanics behind statistical learning: thresholds, trade-offs, projections, uncertainty, and model behavior. They are compact technical notes for people who want to see how the concepts work.
  </p>
</section>

<section class="cv-section">
  <h2>Interactive Lab</h2>
  <div class="project-card-grid">
    {% for applet in site.data.applets %}
    <article class="project-card">
      <div class="project-card__header">
        <div>
          <p class="cv-kicker">{{ applet.category }}</p>
          <h3><a href="/lab/{{ applet.slug }}/">{{ applet.title }}</a></h3>
          <p class="project-card__subtitle">{{ applet.subtitle }}</p>
        </div>
        <div class="project-card__visual">{{ applet.visual }}</div>
      </div>
      <p>{{ applet.description }}</p>
      <div class="project-badges">
        {% for skill in applet.skills %}
          <span>{{ skill }}</span>
        {% endfor %}
      </div>
      <details>
        <summary>Read more</summary>
        <ul>
          <li><strong>Technical challenge:</strong> {{ applet.challenge }}</li>
          <li><strong>My contribution:</strong> {{ applet.contribution }}</li>
          <li><strong>Industry transfer:</strong> {{ applet.transferable }}</li>
          <li><strong>Connected work:</strong> {{ applet.related }}</li>
        </ul>
      </details>
    </article>
    {% endfor %}
  </div>
</section>

<section class="cv-section">
  <h2>Why This Lab Exists</h2>
  <div class="cv-grid">
    <article>
      <h3>Explainability</h3>
      <p>Interactive models make assumptions, thresholds, and failure modes visible instead of hiding them behind summary metrics.</p>
    </article>
    <article>
      <h3>Technical judgment</h3>
      <p>The applets focus on decisions practitioners actually make: which metric to trust, what to compress, and what uncertainty remains.</p>
    </article>
    <article>
      <h3>Technical communication</h3>
      <p>They demonstrate the ability to mentor, document, and communicate complex ideas to technical teams and stakeholders.</p>
    </article>
  </div>
</section>
