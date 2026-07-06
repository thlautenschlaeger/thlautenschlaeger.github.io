---
layout: default
title: Thomas Lautenschläger
sitemap:
  priority: 0.9
---

<section class="hero">
  <img src="{{ '/assets/img/t.jpg' | relative_url }}" alt="Portrait of Thomas Lautenschläger" class="hero__photo">
  <p class="hero__eyebrow">Freelance ML Engineer · MLOps</p>
  <h1 class="hero__title">I develop, deploy, and operate machine learning models in production.</h1>
  <p class="hero__lead">
    I'm Thomas. I manage the full model lifecycle — training, serving,
    inference, monitoring — to established QA standards.
    MSc in Computer Science (AI), TU Darmstadt. Freelancing since 2022.
  </p>
  <ul class="tags">
    <li class="tag">Model Serving</li>
    <li class="tag">Kubernetes</li>
    <li class="tag">Training Pipelines</li>
    <li class="tag">MLOps</li>
    <li class="tag">Sovereign AI</li>
  </ul>
  <div class="btn-row">
    <a class="btn btn--primary" href="{{ '/resume' | relative_url }}">View resume</a>
    <a class="btn" href="{{ '/assets/resume_thomas_lautenschlaeger.pdf' | relative_url }}">Download PDF</a>
  </div>
</section>

<section class="section">
  <h3>What I do</h3>
  <div class="work-item">
    <strong>Model serving &amp; inference</strong>
    <p>Scalable, reliable inference services on Kubernetes — from single-model
    APIs to fleets of models in production, including real-time inference on
    streaming data.</p>
  </div>
  <div class="work-item">
    <strong>Training &amp; lifecycle management</strong>
    <p>Automated training pipelines, CI/CD from model code to deployment, and
    monitoring — operated against established QA requirements, so models stay
    auditable and dependable.</p>
  </div>
  <div class="work-item">
    <strong>ML software that delivers business value</strong>
    <p>Models alone don't generate value — the software around them does. I build
    the services and integrations that turn models into working products,
    including sovereign AI solutions where models, data, and infrastructure
    stay under your control.</p>
  </div>
</section>

{% include page/about.html %}
