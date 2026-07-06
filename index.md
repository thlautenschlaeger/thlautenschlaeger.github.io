---
layout: default
title: Thomas Lautenschläger
sitemap:
  priority: 0.9
---

<section class="hero">
  <img src="{{ '/assets/img/t.jpg' | relative_url }}" alt="Portrait of Thomas Lautenschläger" class="hero__photo">
  <p class="hero__eyebrow">Senior ML Engineer · Freelance</p>
  <h1 class="hero__title">Production ML, end to end.</h1>
  <p class="hero__lead">
    I'm Thomas. I develop, deploy, and operate ML models. From training, serving,
    inference, monitoring to established QA standards, including on critical
    infrastructure. MSc in Computer Science (AI), TU Darmstadt.
  </p>
  <ul class="tags">
    <li class="tag">Model Serving</li>
    <li class="tag">MLOps</li>
    <li class="tag">Kubernetes</li>
    <li class="tag">Critical Infrastructure</li>
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
    <strong>Serving &amp; inference</strong>
    <p>Scalable inference services on Kubernetes; from single-model APIs to
    fleets of models in live operation, including systems running today in a
    control center for the German high-voltage grid.</p>
  </div>
  <div class="work-item">
    <strong>Training &amp; lifecycle</strong>
    <p>Automated training pipelines, CI/CD from model code to deployment,
    monitoring and alerting; operated against established QA requirements,
    so models stay auditable and dependable.</p>
  </div>
  <div class="work-item">
    <strong>From model to product</strong>
    <p>Models generate value only through the software around them. I build the
    services and integrations that turn models into working products: including
    sovereign AI, where models, data, and infrastructure stay under your
    control.</p>
  </div>
</section>

{% include page/about.html %}
