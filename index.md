---
layout: splash
title: "Marcelo Lares"
permalink: /
excerpt: "Data scientist, astronomer, and teacher in Córdoba, Argentina. Explore my work and learn through interactive experiments."
author_profile: false
classes:
  - welcome-page
header:
  og_image: /assets/images/banner.jpeg
---

<section class="welcome-intro" aria-labelledby="welcome-title">
  <div>
    <p class="welcome-eyebrow">Data science · Astronomy · Teaching</p>
    <h1 id="welcome-title">Hi, I’m Marcelo.</h1>
    <p class="welcome-lead">I explore complex systems through data—and help people understand what we find.</p>
    <p>I’m a data scientist, astronomer, and teacher based in Córdoba, Argentina. My work spans galaxies, machine-learning systems, and the classroom.</p>
    <div class="welcome-actions">
      <a class="btn btn--primary" href="{{ '/projects/' | relative_url }}">Explore my work</a>
      <a class="btn welcome-button-secondary" href="{{ '/contact/' | relative_url }}">Get in touch</a>
    </div>
    <a class="welcome-resume" href="{{ '/documents/RESUME.pdf' | relative_url }}">Download my résumé (PDF)</a>
  </div>
  <figure class="welcome-portrait">
    <img src="{{ '/assets/images/face.png' | relative_url }}" alt="Marcelo Lares" width="223" height="256">
    <figcaption>Córdoba, Argentina</figcaption>
  </figure>
</section>

<section class="welcome-section" aria-labelledby="work-heading">
  <p class="welcome-eyebrow">A few things I’ve worked on</p>
  <h2 id="work-heading">From questions to useful tools.</h2>
  <div class="welcome-projects">
    <article>
      <div class="welcome-diagram" aria-label="Recommendation workflow: data, model, recommendations"><span>Data</span><span aria-hidden="true">→</span><span>Model</span><span aria-hidden="true">→</span><span>Recommendations</span></div>
      <p class="welcome-eyebrow">Machine learning in practice</p>
      <h3>Better recommendations</h3>
      <p>At Mercado Libre, I worked on ranking models serving millions of people across three countries, and tripled training-data capacity.</p>
      <a href="{{ '/projects/' | relative_url }}#recommendations">Explore the recommendation work <span aria-hidden="true">→</span></a>
    </article>
    <article>
      <div class="welcome-diagram" aria-label="TOROS workflow: alert, images, candidates"><span>Alert</span><span aria-hidden="true">→</span><span>Images</span><span aria-hidden="true">→</span><span>Candidates</span></div>
      <p class="welcome-eyebrow">Astronomy meets software</p>
      <h3>Looking for rare cosmic signals</h3>
      <p>With TOROS, I developed software and machine-learning workflows to search telescope images for light associated with gravitational-wave events.</p>
      <a href="{{ '/projects/' | relative_url }}#toros">Explore the TOROS project <span aria-hidden="true">→</span></a>
    </article>
    <article>
      <div class="welcome-diagram" aria-label="Corral workflow: ingest, process, validate"><span>Ingest</span><span aria-hidden="true">→</span><span>Process</span><span aria-hidden="true">→</span><span>Validate</span></div>
      <p class="welcome-eyebrow">Open scientific software</p>
      <h3>Making data workflows repeatable</h3>
      <p>I contributed to Corral, a Python framework that helps researchers organize data processing, check quality, and build reproducible pipelines.</p>
      <a href="{{ '/projects/' | relative_url }}#corral">Explore the Corral framework <span aria-hidden="true">→</span></a>
    </article>
  </div>
</section>

<section class="welcome-lab" aria-labelledby="lab-heading">
  <div>
    <p class="welcome-eyebrow">Try something</p>
    <h2 id="lab-heading">What happens when a model gets too complicated?</h2>
    <p>Change a model’s complexity and explore the balance between fitting the data and learning patterns that generalize. My interactive lab makes ideas from data science easier to explore.</p>
    <a class="btn btn--primary" href="{{ '/lab/bias-variance/' | relative_url }}">Try the bias–variance explorer</a>
    <a class="welcome-text-link" href="{{ '/lab/' | relative_url }}">Browse all experiments <span aria-hidden="true">→</span></a>
  </div>
  <aside class="welcome-lab-note" aria-label="Suggested experiment">
    <strong>Start with a question</strong>
    <p>Does a closer fit to the training data always mean better predictions?</p>
    <span>No installation needed. Open the explorer and experiment.</span>
  </aside>
</section>

<section class="welcome-about welcome-section" aria-labelledby="about-heading">
  <div>
    <p class="welcome-eyebrow">A little background</p>
    <h2 id="about-heading">From studying galaxies to building with data.</h2>
  </div>
  <div>
    <p>I trained as an astronomer at Universidad Nacional de Córdoba and spent years using statistics and software to study the universe. That foundation now informs my work in applied machine learning.</p>
    <p>Teaching is another thread through that journey: I’ve taught for twenty years, mentored researchers, and led data-science teams.</p>
    <a href="{{ '/about/' | relative_url }}">More about me <span aria-hidden="true">→</span></a>
  </div>
</section>

<section class="welcome-contact welcome-section" aria-labelledby="contact-heading">
  <p class="welcome-eyebrow">Let’s connect</p>
  <h2 id="contact-heading">Have a question or a project in mind?</h2>
  <p>Get in touch about applied AI, research, teaching, or a possible collaboration.</p>
  <a class="btn btn--primary" href="mailto:marcelo.lares@gmail.com">Email me</a>
  <a class="welcome-text-link" href="https://calendly.com/marcelo-lares/30min">Book a conversation</a>
  <p class="welcome-assistant">Curious about my background? <a href="https://askml-b2d6wau7ua-rj.a.run.app">Ask my AI assistant</a> to explore my work.</p>
</section>
