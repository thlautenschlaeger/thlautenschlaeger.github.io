---
layout: page
title: Selected work
subtitle: Four production systems, from first commit to live operation
sitemap:
  priority: 0.8
---

<script>
(function () {
  if (!('IntersectionObserver' in window)) return;
  if (window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches) return;
  document.documentElement.classList.add('js-viz');
})();
</script>

<p class="projects-intro">
  A selection of systems I designed and built end to end: model, service, infrastructure and operations.
  Each diagram is a schematic of the system &mdash; not client data.
</p>

<article class="project">
  <div class="project__meta">
    <span class="project__client">50Hertz</span>
    <span class="project__sector">Energy · transmission grid</span>
  </div>
  <h2 class="project__title">Wind &amp; solar forecasting for the high-voltage grid</h2>
  <p class="project__lead">A scalable ML platform that trains, serves and monitors renewable forecasting models &mdash; running today in a control centre for the German high-voltage grid.</p>
  <div class="viz-wrap">
    <svg class="viz" viewBox="0 0 720 156" role="img" aria-label="Forecast chart: measured generation, forecast and widening uncertainty band beyond the current time">
  <g class="v-grid">
    <line x1="14" y1="24" x2="706" y2="24"/><line x1="14" y1="51" x2="706" y2="51"/>
    <line x1="14" y1="78" x2="706" y2="78"/><line x1="14" y1="105" x2="706" y2="105"/>
    <line x1="14" y1="132" x2="706" y2="132"/>
  </g>
  <g class="fade" style="--d:.55s"><path class="v-band" d="M 402.3 31.2 L 407.3 31.7 L 412.3 33.4 L 417.3 35.6 L 422.2 37.7 L 427.2 40.8 L 432.2 46.7 L 437.2 49.7 L 442.1 51.7 L 447.1 51.2 L 452.1 49.3 L 457.1 47.8 L 462.1 45.5 L 467.0 42.9 L 472.0 39.1 L 477.0 34.3 L 482.0 31.3 L 486.9 30.1 L 491.9 29.1 L 496.9 28.0 L 501.9 24.2 L 506.9 21.5 L 511.8 19.4 L 516.8 19.0 L 521.8 18.0 L 526.8 18.0 L 531.8 18.0 L 536.7 18.0 L 541.7 19.7 L 546.7 24.1 L 551.7 28.7 L 556.6 35.5 L 561.6 40.2 L 566.6 45.2 L 571.6 47.3 L 576.6 48.8 L 581.5 47.5 L 586.5 44.4 L 591.5 40.4 L 596.5 35.7 L 601.5 30.0 L 606.4 23.7 L 611.4 18.5 L 616.4 18.0 L 621.4 18.0 L 626.3 18.0 L 631.3 18.0 L 636.3 18.0 L 641.3 18.0 L 646.3 21.8 L 651.2 27.3 L 656.2 30.9 L 661.2 35.1 L 666.2 36.8 L 671.2 39.0 L 676.1 40.2 L 681.1 41.4 L 686.1 41.3 L 691.1 40.9 L 696.0 41.2 L 701.0 43.8 L 706.0 45.2 L 706.0 101.2 L 701.0 99.1 L 696.0 95.9 L 691.1 95.0 L 686.1 94.7 L 681.1 94.1 L 676.1 92.3 L 671.2 90.5 L 666.2 87.6 L 661.2 85.3 L 656.2 80.4 L 651.2 76.1 L 646.3 69.9 L 641.3 64.8 L 636.3 59.5 L 631.3 57.7 L 626.3 57.6 L 621.4 59.8 L 616.4 59.8 L 611.4 61.8 L 606.4 66.3 L 601.5 71.9 L 596.5 76.9 L 591.5 80.9 L 586.5 84.1 L 581.5 86.5 L 576.6 87.0 L 571.6 84.8 L 566.6 82.0 L 561.6 76.3 L 556.6 70.8 L 551.7 63.3 L 546.7 57.8 L 541.7 52.7 L 536.7 49.0 L 531.8 45.7 L 526.8 46.8 L 521.8 47.2 L 516.8 48.0 L 511.8 47.6 L 506.9 48.9 L 501.9 50.8 L 496.9 53.7 L 491.9 53.9 L 486.9 54.1 L 482.0 54.4 L 477.0 56.5 L 472.0 60.3 L 467.0 63.2 L 462.1 64.8 L 457.1 66.2 L 452.1 66.7 L 447.1 67.6 L 442.1 67.0 L 437.2 63.9 L 432.2 59.8 L 427.2 52.8 L 422.2 48.4 L 417.3 45.1 L 412.3 41.4 L 407.3 38.1 L 402.3 35.2 Z"/></g>
  <path class="v-line v-actual draw" style="--len:1800" d="M 14.0 96.0 L 19.0 88.7 L 24.0 73.8 L 28.9 77.0 L 33.9 74.8 L 38.9 75.2 L 43.9 78.7 L 48.8 69.7 L 53.8 65.3 L 58.8 61.4 L 63.8 72.8 L 68.8 74.3 L 73.7 71.7 L 78.7 61.6 L 83.7 54.7 L 88.7 51.2 L 93.7 49.5 L 98.6 48.5 L 103.6 36.8 L 108.6 42.4 L 113.6 41.9 L 118.5 36.3 L 123.5 48.1 L 128.5 51.7 L 133.5 44.0 L 138.5 39.5 L 143.4 41.2 L 148.4 47.0 L 153.4 59.5 L 158.4 52.5 L 163.4 61.9 L 168.3 65.4 L 173.3 61.9 L 178.3 62.3 L 183.3 67.0 L 188.2 72.4 L 193.2 75.2 L 198.2 60.6 L 203.2 58.1 L 208.2 48.9 L 213.1 38.9 L 218.1 34.2 L 223.1 38.4 L 228.1 40.4 L 233.1 31.6 L 238.0 28.3 L 243.0 28.8 L 248.0 39.6 L 253.0 41.9 L 257.9 55.3 L 262.9 57.1 L 267.9 53.2 L 272.9 56.6 L 277.9 59.0 L 282.8 66.6 L 287.8 61.4 L 292.8 67.5 L 297.8 73.2 L 302.7 56.6 L 307.7 54.0 L 312.7 67.4 L 317.7 61.4 L 322.7 59.9 L 327.6 57.9 L 332.6 53.6 L 337.6 49.2 L 342.6 42.6 L 347.6 51.5 L 352.5 50.2 L 357.5 39.3 L 362.5 38.6 L 367.5 49.1 L 372.4 37.4 L 377.4 41.7 L 382.4 31.8 L 387.4 27.9 L 392.4 24.0 L 397.3 31.3 L 402.3 35.4"/>
  <g class="fade" style="--d:.85s">
    <path class="v-line v-fc" d="M 402.3 33.2 L 407.3 34.9 L 412.3 37.4 L 417.3 40.3 L 422.2 43.1 L 427.2 46.8 L 432.2 53.3 L 437.2 56.8 L 442.1 59.4 L 447.1 59.4 L 452.1 58.0 L 457.1 57.0 L 462.1 55.2 L 467.0 53.1 L 472.0 49.7 L 477.0 45.4 L 482.0 42.9 L 486.9 42.1 L 491.9 41.5 L 496.9 40.9 L 501.9 37.5 L 506.9 35.2 L 511.8 33.5 L 516.8 33.5 L 521.8 32.3 L 526.8 31.5 L 531.8 30.0 L 536.7 32.9 L 541.7 36.2 L 546.7 40.9 L 551.7 46.0 L 556.6 53.2 L 561.6 58.2 L 566.6 63.6 L 571.6 66.1 L 576.6 67.9 L 581.5 67.0 L 586.5 64.3 L 591.5 60.7 L 596.5 56.3 L 601.5 51.0 L 606.4 45.0 L 611.4 40.2 L 616.4 37.8 L 621.4 37.5 L 626.3 34.9 L 631.3 34.6 L 636.3 36.1 L 641.3 41.0 L 646.3 45.9 L 651.2 51.7 L 656.2 55.7 L 661.2 60.2 L 666.2 62.2 L 671.2 64.8 L 676.1 66.2 L 681.1 67.8 L 686.1 68.0 L 691.1 68.0 L 696.0 68.6 L 701.0 71.4 L 706.0 73.2"/>
    <line class="v-now" x1="402.3" y1="16" x2="402.3" y2="140"/>
    <circle class="v-query" cx="402.3" cy="34.4" r="3.6"/>
  </g>
  <g class="fade" style="--d:1.1s">
    <circle class="v-halo v-halo--accent pulse" cx="706.0" cy="73.2" r="9"/>
    <circle class="v-node" cx="706.0" cy="73.2" r="3.4"/>
  </g>
</svg>
    <ul class="legend"><li class="legend__key" style="--k:var(--accent)">Measured</li><li class="legend__key legend__key--dash" style="--k:var(--accent)">Forecast</li><li class="legend__key legend__key--area" style="--k:var(--accent)">Uncertainty</li><li class="legend__key legend__key--dash" style="--k:var(--muted)">Forecast start</li></ul>
    <p class="viz-hint">Swipe the diagram to see it in full &rarr;</p>
  </div>
  <ul class="project__points"><li>Inference service for real-time execution and orchestration of a fleet of forecasting models.</li><li>Wind and solar models with automated training, validation, versioning and lifecycle management (Azure ML, MLflow).</li><li>Data-quality service that encodes domain expert knowledge and gates every downstream prediction.</li><li>Monitoring and alerting with Grafana and OpenTelemetry; operated against established QA standards.</li><li>Tech lead of a cross-functional Scrum team, owning architecture decisions and the rollout into grid operations.</li></ul>
  <div class="project__stack"><ul class="tags"><li class="tag">Python</li><li class="tag">PyTorch</li><li class="tag">scikit-learn</li><li class="tag">FastAPI</li><li class="tag">Kafka</li><li class="tag">MLflow</li><li class="tag">Azure ML</li><li class="tag">Kubernetes</li><li class="tag">Helm</li><li class="tag">ArgoCD</li><li class="tag">TimescaleDB</li><li class="tag">Grafana</li><li class="tag">OpenTelemetry</li></ul></div>
</article>

<article class="project">
  <div class="project__meta">
    <span class="project__client">Pharma &amp; medical technology</span>
    <span class="project__sector">Regulatory &middot; GenAI platform</span>
  </div>
  <h2 class="project__title">RAG and agentic AI for regulatory content</h2>
  <p class="project__lead">Production retrieval and agent systems that track regulatory change and automate business processes, served on self-hosted GPUs.</p>
  <div class="viz-wrap">
    <svg class="viz" viewBox="0 0 720 156" role="img" aria-label="Vector search: a query point retrieves its nearest neighbours from an embedding space, which are passed as context to a GPU-served language model">
  <g class="fade" style="--d:.1s"><g class="v-dot"><circle cx="110.9" cy="55.9" r="2.6"/><circle cx="44.8" cy="40.6" r="2.6"/><circle cx="62.5" cy="81.8" r="2.6"/><circle cx="45.5" cy="66.0" r="2.6"/><circle cx="73.2" cy="60.3" r="2.6"/><circle cx="69.9" cy="50.3" r="2.6"/><circle cx="82.8" cy="45.8" r="2.6"/><circle cx="86.9" cy="49.6" r="2.6"/><circle cx="102.1" cy="72.9" r="2.6"/><circle cx="67.7" cy="41.0" r="2.6"/><circle cx="78.0" cy="35.6" r="2.6"/><circle cx="199.7" cy="44.2" r="2.6"/><circle cx="225.8" cy="24.4" r="2.6"/><circle cx="230.0" cy="44.1" r="2.6"/><circle cx="230.4" cy="44.4" r="2.6"/><circle cx="240.2" cy="25.0" r="2.6"/><circle cx="256.2" cy="59.2" r="2.6"/><circle cx="194.4" cy="50.6" r="2.6"/><circle cx="225.5" cy="30.6" r="2.6"/><circle cx="203.5" cy="30.4" r="2.6"/><circle cx="198.9" cy="41.1" r="2.6"/><circle cx="101.6" cy="136.0" r="2.6"/><circle cx="77.3" cy="134.4" r="2.6"/><circle cx="61.1" cy="94.7" r="2.6"/><circle cx="121.6" cy="131.6" r="2.6"/><circle cx="24.3" cy="107.1" r="2.6"/><circle cx="61.9" cy="129.5" r="2.6"/><circle cx="112.5" cy="128.9" r="2.6"/><circle cx="66.7" cy="131.5" r="2.6"/><circle cx="72.2" cy="126.9" r="2.6"/><circle cx="60.7" cy="104.7" r="2.6"/><circle cx="111.4" cy="118.9" r="2.6"/><circle cx="81.1" cy="114.4" r="2.6"/><circle cx="228.4" cy="111.0" r="2.6"/><circle cx="233.3" cy="120.7" r="2.6"/><circle cx="177.2" cy="136.0" r="2.6"/><circle cx="215.5" cy="129.9" r="2.6"/><circle cx="265.8" cy="124.3" r="2.6"/><circle cx="190.1" cy="109.1" r="2.6"/><circle cx="244.4" cy="96.7" r="2.6"/><circle cx="224.9" cy="126.0" r="2.6"/><circle cx="188.1" cy="122.7" r="2.6"/><circle cx="232.5" cy="107.6" r="2.6"/><circle cx="205.5" cy="128.7" r="2.6"/><circle cx="184.2" cy="105.9" r="2.6"/><circle cx="237.5" cy="91.6" r="2.6"/></g></g>
  <g class="fade" style="--d:.45s">
    <circle class="v-radius" cx="150" cy="80" r="28.0"/>
    <g class="v-link"><line x1="150.0" y1="80.0" x2="152.0" y2="88.7"/><line x1="150.0" y1="80.0" x2="156.6" y2="69.8"/><line x1="150.0" y1="80.0" x2="171.9" y2="77.8"/><line x1="150.0" y1="80.0" x2="148.6" y2="56.8"/><line x1="150.0" y1="80.0" x2="170.9" y2="91.8"/></g>
    <g class="v-near"><circle cx="152.0" cy="88.7" r="3.6"/><circle cx="156.6" cy="69.8" r="3.6"/><circle cx="171.9" cy="77.8" r="3.6"/><circle cx="148.6" cy="56.8" r="3.6"/><circle cx="170.9" cy="91.8" r="3.6"/></g>
  </g>
  <g class="fade" style="--d:.3s">
    <circle class="v-halo v-halo--accent pulse" cx="150" cy="80" r="12"/>
    <circle class="v-query" cx="150" cy="80" r="5"/>
  </g>
  <line class="v-arrow" x1="296" y1="80" x2="334" y2="80"/>
  <circle class="v-flow flow-dot" cx="298" cy="80" r="2.6" style="--fx:32px;--d:0.00s;animation-duration:2.2s"/><circle class="v-flow flow-dot" cx="298" cy="80" r="2.6" style="--fx:32px;--d:0.75s;animation-duration:2.2s"/>
  <g class="fade" style="--d:0.70s"><rect class="v-box" x="340" y="40" width="98" height="22" rx="4"/><rect class="v-boxline" x="350" y="47" width="60" height="3" rx="1.5"/><rect class="v-boxline" x="350" y="53" width="44" height="3" rx="1.5"/></g><g class="fade" style="--d:0.85s"><rect class="v-box" x="340" y="68" width="98" height="22" rx="4"/><rect class="v-boxline" x="350" y="75" width="60" height="3" rx="1.5"/><rect class="v-boxline" x="350" y="81" width="44" height="3" rx="1.5"/></g><g class="fade" style="--d:1.00s"><rect class="v-box" x="340" y="96" width="98" height="22" rx="4"/><rect class="v-boxline" x="350" y="103" width="60" height="3" rx="1.5"/><rect class="v-boxline" x="350" y="109" width="44" height="3" rx="1.5"/></g>
  <line class="v-arrow" x1="446" y1="80" x2="486" y2="80"/>
  <circle class="v-flow flow-dot" cx="448" cy="80" r="2.6" style="--fx:34px;--d:0.00s;animation-duration:2.2s"/><circle class="v-flow flow-dot" cx="448" cy="80" r="2.6" style="--fx:34px;--d:0.75s;animation-duration:2.2s"/>
  <g class="fade" style="--d:1.15s">
    <rect class="v-llm" x="492" y="42" width="104" height="76" rx="12"/>
    <circle class="v-node" cx="510" cy="62" r="2.6" opacity=".55"/><circle class="v-node" cx="531" cy="62" r="2.6" opacity=".55"/><circle class="v-node" cx="552" cy="62" r="2.6" opacity=".55"/><circle class="v-node" cx="573" cy="62" r="2.6" opacity=".55"/><circle class="v-node" cx="510" cy="79" r="2.6" opacity=".55"/><circle class="v-node" cx="531" cy="79" r="2.6" opacity=".55"/><circle class="v-node" cx="552" cy="79" r="2.6" opacity=".55"/><circle class="v-node" cx="573" cy="79" r="2.6" opacity=".55"/><circle class="v-node" cx="510" cy="96" r="2.6" opacity=".55"/><circle class="v-node" cx="531" cy="96" r="2.6" opacity=".55"/><circle class="v-node" cx="552" cy="96" r="2.6" opacity=".55"/><circle class="v-node" cx="573" cy="96" r="2.6" opacity=".55"/>
  </g>
  <line class="v-arrow" x1="604" y1="80" x2="628" y2="80"/>
  <g class="fade" style="--d:1.5s"><rect class="v-boxline" x="634" y="52" width="72" height="6" rx="3"/><rect class="v-boxline" x="634" y="66" width="60" height="6" rx="3"/><rect class="v-boxline" x="634" y="80" width="70" height="6" rx="3"/><rect class="v-boxline" x="634" y="94" width="44" height="6" rx="3"/></g>
</svg>
    <ul class="legend"><li class="legend__key legend__key--dot" style="--k:var(--accent)">Query</li><li class="legend__key legend__key--dash" style="--k:var(--accent)">Retrieved chunks</li><li class="legend__key legend__key--dot" style="--k:var(--muted)">Embedding space</li><li class="legend__key legend__key--area" style="--k:var(--accent)">GPU-served LLM</li></ul>
    <p class="viz-hint">Swipe the diagram to see it in full &rarr;</p>
  </div>
  <ul class="project__points"><li>RAG systems that track changes in regulations and legal texts across large document bases.</li><li>Vector database (Milvus) for semantic search and retrieval, built and operated in production.</li><li>LLM serving with vLLM and Ray Serve on NVIDIA GPUs in Kubernetes, including GPU Operator integration and serving optimisation.</li><li>Agentic workflows for multi-step automation, for example automated quote generation.</li><li>Retrieval and generation integrated into chatbot and business systems, with end-to-end observability.</li></ul>
  <div class="project__stack"><ul class="tags"><li class="tag">Python</li><li class="tag">LangChain</li><li class="tag">LlamaIndex</li><li class="tag">Milvus</li><li class="tag">vLLM</li><li class="tag">Ray Serve</li><li class="tag">Hugging Face</li><li class="tag">NVIDIA CUDA</li><li class="tag">Kubernetes</li><li class="tag">Helm</li><li class="tag">Prometheus</li><li class="tag">Grafana</li><li class="tag">OpenTelemetry</li></ul></div>
</article>

<article class="project">
  <div class="project__meta">
    <span class="project__client">E.ON</span>
    <span class="project__sector">Energy &middot; distribution grid</span>
  </div>
  <h2 class="project__title">Multi-tenant monitoring for low-voltage grids</h2>
  <p class="project__lead">Automated fault detection and analysis across low-voltage networks, designed multi-tenant for a group-wide rollout to several distribution grid operators.</p>
  <div class="viz-wrap">
    <svg class="viz" viewBox="0 0 720 156" role="img" aria-label="Low-voltage grid topology with one faulted branch, streaming into a voltage trace where a dip crosses the alert threshold">
  <g class="fade" style="--d:.15s"><path class="v-edge" d="M 28 78 C 62 78, 70 36, 104 36"/><path class="v-edge" d="M 28 78 C 62 78, 70 78, 104 78"/><path class="v-edge" d="M 28 78 C 62 78, 70 120, 104 120"/><path class="v-edge" d="M 104 36 C 134 36, 148 20, 178 20"/><path class="v-alert-edge" d="M 104 36 C 134 36, 148 36, 178 36"/><path class="v-edge" d="M 104 36 C 134 36, 148 52, 178 52"/><path class="v-edge" d="M 104 78 C 134 78, 148 62, 178 62"/><path class="v-edge" d="M 104 78 C 134 78, 148 78, 178 78"/><path class="v-edge" d="M 104 78 C 134 78, 148 94, 178 94"/><path class="v-edge" d="M 104 120 C 134 120, 148 104, 178 104"/><path class="v-edge" d="M 104 120 C 134 120, 148 120, 178 120"/><path class="v-edge" d="M 104 120 C 134 120, 148 136, 178 136"/></g>
  <g class="fade" style="--d:.35s">
    <circle class="v-node" cx="28" cy="78" r="6.5"/>
    <circle class="v-node" cx="104" cy="36" r="4.2"/><circle class="v-node" cx="104" cy="78" r="4.2"/><circle class="v-node" cx="104" cy="120" r="4.2"/><rect class="v-node" x="175" y="17" width="6" height="6" rx="1.5" opacity=".55"/><rect class="v-node" x="175" y="49" width="6" height="6" rx="1.5" opacity=".55"/><rect class="v-node" x="175" y="59" width="6" height="6" rx="1.5" opacity=".55"/><rect class="v-node" x="175" y="75" width="6" height="6" rx="1.5" opacity=".55"/><rect class="v-node" x="175" y="91" width="6" height="6" rx="1.5" opacity=".55"/><rect class="v-node" x="175" y="101" width="6" height="6" rx="1.5" opacity=".55"/><rect class="v-node" x="175" y="117" width="6" height="6" rx="1.5" opacity=".55"/><rect class="v-node" x="175" y="133" width="6" height="6" rx="1.5" opacity=".55"/>
  </g>
  <g class="fade" style="--d:.6s">
    <circle class="v-halo pulse" cx="178" cy="36" r="11"/>
    <circle class="v-alert" cx="178" cy="36" r="4.6"/>
  </g>
  <line class="v-arrow" x1="216" y1="78" x2="356" y2="78"/>
  <circle class="v-flow flow-dot" cx="222" cy="78" r="2.6" style="--fx:128px;--d:0.00s;animation-duration:2.8s"/><circle class="v-flow flow-dot" cx="222" cy="78" r="2.6" style="--fx:128px;--d:0.75s;animation-duration:2.8s"/><circle class="v-flow flow-dot" cx="222" cy="78" r="2.6" style="--fx:128px;--d:1.50s;animation-duration:2.8s"/>
  <g class="fade" style="--d:.5s">
    <rect class="v-panel" x="366" y="20" width="344" height="120" rx="8"/>
    <line class="v-thr" x1="372" y1="102.0" x2="706" y2="102.0"/>
    <rect class="v-zone" x="551.6" y="20" width="56.1" height="120"/>
  </g>
  <path class="v-sig draw" style="--len:1200" d="M 372.0 73.0 L 374.8 71.0 L 377.6 74.9 L 380.4 64.8 L 383.2 78.9 L 386.0 85.2 L 388.8 75.4 L 391.6 68.1 L 394.5 54.5 L 397.3 48.5 L 400.1 56.3 L 402.9 53.3 L 405.7 53.4 L 408.5 45.5 L 411.3 42.3 L 414.1 48.8 L 416.9 53.4 L 419.7 58.8 L 422.5 63.3 L 425.3 52.4 L 428.1 61.0 L 430.9 61.6 L 433.7 60.5 L 436.6 60.7 L 439.4 65.6 L 442.2 60.8 L 445.0 62.3 L 447.8 63.5 L 450.6 68.4 L 453.4 68.0 L 456.2 69.0 L 459.0 73.6 L 461.8 69.2 L 464.6 60.2 L 467.4 65.8 L 470.2 64.4 L 473.0 68.1 L 475.8 70.9 L 478.7 73.8 L 481.5 75.2 L 484.3 72.3 L 487.1 73.9 L 489.9 79.1 L 492.7 72.2 L 495.5 69.8 L 498.3 70.5 L 501.1 64.5 L 503.9 66.0 L 506.7 68.6 L 509.5 69.6 L 512.3 68.4 L 515.1 71.6 L 517.9 80.2 L 520.8 85.8 L 523.6 83.6 L 526.4 91.1 L 529.2 81.2 L 532.0 74.3 L 534.8 73.9 L 537.6 74.5 L 540.4 70.5 L 543.2 70.0 L 546.0 73.4 L 548.8 76.5 L 551.6 73.7 L 554.4 80.6 L 557.2 90.3 L 560.1 96.2 L 562.9 102.5 L 565.7 106.1 L 568.5 115.5 L 571.3 124.5 L 574.1 127.0 L 576.9 127.0 L 579.7 127.0 L 582.5 127.0 L 585.3 121.4 L 588.1 116.2 L 590.9 109.5 L 593.7 93.9 L 596.5 80.6 L 599.3 74.1 L 602.2 70.7 L 605.0 66.7 L 607.8 68.2 L 610.6 72.0 L 613.4 66.2 L 616.2 66.9 L 619.0 76.6 L 621.8 78.8 L 624.6 78.6 L 627.4 67.4 L 630.2 79.1 L 633.0 79.3 L 635.8 76.3 L 638.6 74.1 L 641.4 80.0 L 644.3 86.4 L 647.1 91.7 L 649.9 89.5 L 652.7 90.2 L 655.5 75.2 L 658.3 71.9 L 661.1 74.7 L 663.9 76.9 L 666.7 72.4 L 669.5 61.0 L 672.3 55.2 L 675.1 51.0 L 677.9 58.1 L 680.7 69.6 L 683.5 71.5 L 686.4 68.5 L 689.2 75.5 L 692.0 79.1 L 694.8 76.7 L 697.6 71.2 L 700.4 73.6 L 703.2 67.0 L 706.0 57.6"/>
  <g class="fade" style="--d:1.2s">
    <circle class="v-halo pulse" cx="579.7" cy="127.0" r="10"/>
    <circle class="v-alert" cx="579.7" cy="127.0" r="4"/>
  </g>
</svg>
    <ul class="legend"><li class="legend__key legend__key--dot" style="--k:var(--accent)">Grid topology</li><li class="legend__key" style="--k:var(--alert)">Faulted branch</li><li class="legend__key" style="--k:var(--accent)">Voltage signal</li><li class="legend__key legend__key--dash" style="--k:var(--alert)">Alert threshold</li></ul>
    <p class="viz-hint">Swipe the diagram to see it in full &rarr;</p>
  </div>
  <ul class="project__points"><li>Automated grid-monitoring system that detects and analyses network disturbances in real time.</li><li>Machine learning combined with rule-based methods for automated fault pre-detection.</li><li>Multi-tenant architecture for parallel operation across several grid companies and DSOs.</li><li>Scaled on Kubernetes and integrated with heterogeneous data sources and system landscapes.</li><li>Accompanied from development through CI/CD, quality gates and into productive operation.</li></ul>
  <div class="project__stack"><ul class="tags"><li class="tag">Python</li><li class="tag">PyTorch</li><li class="tag">scikit-learn</li><li class="tag">FastAPI</li><li class="tag">Kafka</li><li class="tag">PostgreSQL</li><li class="tag">Azure</li><li class="tag">Kubernetes</li><li class="tag">Docker</li><li class="tag">ArgoCD</li><li class="tag">Helm</li><li class="tag">Grafana</li><li class="tag">SonarQube</li></ul></div>
</article>

<article class="project">
  <div class="project__meta">
    <span class="project__client">Quantitative finance</span>
    <span class="project__sector">Investment strategy &middot; research platform</span>
  </div>
  <h2 class="project__title">Research and backtesting platform for investment strategies</h2>
  <p class="project__lead">Software to design, test and operate quantitative investment strategies &mdash; from the market data lake to live performance monitoring.</p>
  <div class="viz-wrap">
    <svg class="viz" viewBox="0 0 720 156" role="img" aria-label="Backtest results: strategy equity curve against a benchmark with drawdown shading, next to a bar chart of monthly returns">
  <g class="v-grid">
    <line x1="14" y1="22" x2="430" y2="22"/><line x1="14" y1="71" x2="430" y2="71"/>
    <line x1="14" y1="120" x2="430" y2="120"/>
  </g>
  <g class="fade" style="--d:.7s"><path class="v-dd" d="M 14.0 116.3 L 17.2 116.3 L 20.4 116.3 L 23.7 116.3 L 26.9 111.3 L 30.1 109.6 L 33.3 109.6 L 36.6 109.6 L 39.8 107.9 L 43.0 100.3 L 46.2 97.8 L 49.5 97.8 L 52.7 97.8 L 55.9 96.2 L 59.1 93.9 L 62.4 93.9 L 65.6 93.9 L 68.8 93.9 L 72.0 93.9 L 75.3 93.9 L 78.5 93.9 L 81.7 93.9 L 84.9 93.9 L 88.2 93.9 L 91.4 93.9 L 94.6 93.7 L 97.8 93.7 L 101.1 93.7 L 104.3 93.7 L 107.5 93.7 L 110.7 93.7 L 114.0 93.7 L 117.2 93.7 L 120.4 93.7 L 123.6 93.7 L 126.9 93.7 L 130.1 93.7 L 133.3 93.7 L 136.5 93.7 L 139.8 93.7 L 143.0 93.7 L 146.2 93.7 L 149.4 93.7 L 152.7 93.7 L 155.9 93.7 L 159.1 93.7 L 162.3 93.7 L 165.6 93.7 L 168.8 93.7 L 172.0 93.7 L 175.2 93.7 L 178.5 93.7 L 181.7 93.7 L 184.9 93.7 L 188.1 93.7 L 191.4 93.7 L 194.6 93.7 L 197.8 93.7 L 201.0 89.5 L 204.3 85.4 L 207.5 80.4 L 210.7 75.3 L 213.9 75.3 L 217.2 75.3 L 220.4 67.8 L 223.6 67.8 L 226.8 65.6 L 230.1 64.2 L 233.3 59.8 L 236.5 59.8 L 239.7 59.0 L 243.0 56.3 L 246.2 54.2 L 249.4 54.2 L 252.6 50.8 L 255.9 50.8 L 259.1 50.8 L 262.3 50.8 L 265.5 50.8 L 268.8 50.8 L 272.0 50.8 L 275.2 50.8 L 278.4 50.8 L 281.7 50.8 L 284.9 50.8 L 288.1 50.8 L 291.3 50.8 L 294.6 50.8 L 297.8 50.8 L 301.0 50.8 L 304.2 50.8 L 307.5 50.8 L 310.7 50.8 L 313.9 50.8 L 317.1 50.8 L 320.4 50.8 L 323.6 50.8 L 326.8 50.8 L 330.0 50.8 L 333.3 50.8 L 336.5 50.8 L 339.7 50.8 L 342.9 50.8 L 346.2 50.8 L 349.4 50.8 L 352.6 50.8 L 355.8 50.8 L 359.1 50.8 L 362.3 48.3 L 365.5 44.9 L 368.7 44.9 L 372.0 41.8 L 375.2 40.0 L 378.4 40.0 L 381.6 40.0 L 384.9 40.0 L 388.1 40.0 L 391.3 37.2 L 394.5 37.1 L 397.8 33.2 L 401.0 22.0 L 404.2 22.0 L 407.4 22.0 L 410.7 22.0 L 413.9 22.0 L 417.1 22.0 L 420.3 22.0 L 423.6 22.0 L 426.8 22.0 L 430.0 22.0 L 430.0 23.8 L 426.8 25.8 L 423.6 24.9 L 420.3 28.9 L 417.1 30.5 L 413.9 27.0 L 410.7 23.3 L 407.4 23.5 L 404.2 26.6 L 401.0 22.0 L 397.8 33.2 L 394.5 37.1 L 391.3 37.2 L 388.1 44.1 L 384.9 46.0 L 381.6 42.8 L 378.4 41.4 L 375.2 40.0 L 372.0 41.8 L 368.7 47.8 L 365.5 44.9 L 362.3 48.3 L 359.1 58.0 L 355.8 52.1 L 352.6 56.0 L 349.4 66.2 L 346.2 68.2 L 342.9 68.0 L 339.7 70.3 L 336.5 69.5 L 333.3 67.8 L 330.0 67.2 L 326.8 66.6 L 323.6 69.3 L 320.4 69.3 L 317.1 69.9 L 313.9 63.1 L 310.7 58.8 L 307.5 58.0 L 304.2 65.7 L 301.0 67.0 L 297.8 66.5 L 294.6 68.0 L 291.3 68.1 L 288.1 64.2 L 284.9 68.5 L 281.7 64.3 L 278.4 61.0 L 275.2 64.5 L 272.0 60.8 L 268.8 57.9 L 265.5 57.8 L 262.3 63.8 L 259.1 59.5 L 255.9 55.4 L 252.6 50.8 L 249.4 56.7 L 246.2 54.2 L 243.0 56.3 L 239.7 59.0 L 236.5 59.9 L 233.3 59.8 L 230.1 64.2 L 226.8 65.6 L 223.6 68.0 L 220.4 67.8 L 217.2 75.3 L 213.9 76.4 L 210.7 75.3 L 207.5 80.4 L 204.3 85.4 L 201.0 89.5 L 197.8 100.6 L 194.6 104.2 L 191.4 111.1 L 188.1 109.1 L 184.9 109.2 L 181.7 106.2 L 178.5 110.4 L 175.2 107.1 L 172.0 112.1 L 168.8 112.4 L 165.6 112.9 L 162.3 106.5 L 159.1 108.0 L 155.9 109.4 L 152.7 106.4 L 149.4 108.8 L 146.2 102.3 L 143.0 106.4 L 139.8 112.2 L 136.5 109.2 L 133.3 111.4 L 130.1 107.5 L 126.9 104.5 L 123.6 104.3 L 120.4 101.5 L 117.2 101.7 L 114.0 102.9 L 110.7 104.3 L 107.5 100.5 L 104.3 101.2 L 101.1 98.7 L 97.8 99.0 L 94.6 93.7 L 91.4 98.4 L 88.2 101.4 L 84.9 100.4 L 81.7 101.5 L 78.5 105.1 L 75.3 103.6 L 72.0 103.0 L 68.8 101.9 L 65.6 98.6 L 62.4 99.6 L 59.1 93.9 L 55.9 96.2 L 52.7 103.8 L 49.5 101.4 L 46.2 97.8 L 43.0 100.3 L 39.8 107.9 L 36.6 112.1 L 33.3 110.4 L 30.1 109.6 L 26.9 111.3 L 23.7 116.8 L 20.4 119.6 L 17.2 120.0 L 14.0 116.3 Z"/></g>
  <g class="fade" style="--d:.35s"><path class="v-bench" d="M 14.0 116.5 L 17.2 115.3 L 20.4 119.8 L 23.7 117.4 L 26.9 113.4 L 30.1 114.3 L 33.3 112.4 L 36.6 111.1 L 39.8 111.8 L 43.0 114.0 L 46.2 119.7 L 49.5 115.0 L 52.7 114.6 L 55.9 106.4 L 59.1 103.2 L 62.4 101.8 L 65.6 103.3 L 68.8 98.3 L 72.0 99.4 L 75.3 93.8 L 78.5 94.5 L 81.7 93.4 L 84.9 97.9 L 88.2 89.6 L 91.4 89.4 L 94.6 90.1 L 97.8 86.8 L 101.1 89.3 L 104.3 86.1 L 107.5 89.5 L 110.7 87.1 L 114.0 90.1 L 117.2 95.7 L 120.4 97.1 L 123.6 101.4 L 126.9 99.1 L 130.1 98.4 L 133.3 96.2 L 136.5 95.4 L 139.8 96.0 L 143.0 95.3 L 146.2 91.3 L 149.4 91.3 L 152.7 93.3 L 155.9 96.0 L 159.1 96.2 L 162.3 98.1 L 165.6 91.4 L 168.8 94.8 L 172.0 97.8 L 175.2 98.2 L 178.5 95.6 L 181.7 95.9 L 184.9 98.5 L 188.1 100.6 L 191.4 101.2 L 194.6 97.5 L 197.8 100.1 L 201.0 99.9 L 204.3 101.3 L 207.5 99.7 L 210.7 97.9 L 213.9 102.1 L 217.2 93.9 L 220.4 92.7 L 223.6 93.8 L 226.8 96.2 L 230.1 96.5 L 233.3 95.9 L 236.5 93.3 L 239.7 92.8 L 243.0 90.6 L 246.2 95.4 L 249.4 97.4 L 252.6 100.1 L 255.9 99.0 L 259.1 97.0 L 262.3 101.3 L 265.5 101.3 L 268.8 98.4 L 272.0 94.8 L 275.2 97.9 L 278.4 95.5 L 281.7 93.9 L 284.9 94.8 L 288.1 87.7 L 291.3 90.9 L 294.6 91.3 L 297.8 89.2 L 301.0 87.8 L 304.2 87.8 L 307.5 82.5 L 310.7 76.9 L 313.9 73.1 L 317.1 68.9 L 320.4 68.4 L 323.6 72.1 L 326.8 63.6 L 330.0 66.5 L 333.3 57.7 L 336.5 57.5 L 339.7 56.0 L 342.9 56.0 L 346.2 51.7 L 349.4 53.0 L 352.6 45.2 L 355.8 42.4 L 359.1 41.0 L 362.3 42.7 L 365.5 40.9 L 368.7 40.2 L 372.0 31.9 L 375.2 27.3 L 378.4 33.1 L 381.6 26.1 L 384.9 35.4 L 388.1 28.4 L 391.3 35.6 L 394.5 34.9 L 397.8 30.9 L 401.0 30.2 L 404.2 34.1 L 407.4 28.3 L 410.7 35.0 L 413.9 40.3 L 417.1 34.1 L 420.3 36.9 L 423.6 35.2 L 426.8 31.2 L 430.0 31.0"/></g>
  <path class="v-line v-actual draw" style="--len:1400" d="M 14.0 116.3 L 17.2 120.0 L 20.4 119.6 L 23.7 116.8 L 26.9 111.3 L 30.1 109.6 L 33.3 110.4 L 36.6 112.1 L 39.8 107.9 L 43.0 100.3 L 46.2 97.8 L 49.5 101.4 L 52.7 103.8 L 55.9 96.2 L 59.1 93.9 L 62.4 99.6 L 65.6 98.6 L 68.8 101.9 L 72.0 103.0 L 75.3 103.6 L 78.5 105.1 L 81.7 101.5 L 84.9 100.4 L 88.2 101.4 L 91.4 98.4 L 94.6 93.7 L 97.8 99.0 L 101.1 98.7 L 104.3 101.2 L 107.5 100.5 L 110.7 104.3 L 114.0 102.9 L 117.2 101.7 L 120.4 101.5 L 123.6 104.3 L 126.9 104.5 L 130.1 107.5 L 133.3 111.4 L 136.5 109.2 L 139.8 112.2 L 143.0 106.4 L 146.2 102.3 L 149.4 108.8 L 152.7 106.4 L 155.9 109.4 L 159.1 108.0 L 162.3 106.5 L 165.6 112.9 L 168.8 112.4 L 172.0 112.1 L 175.2 107.1 L 178.5 110.4 L 181.7 106.2 L 184.9 109.2 L 188.1 109.1 L 191.4 111.1 L 194.6 104.2 L 197.8 100.6 L 201.0 89.5 L 204.3 85.4 L 207.5 80.4 L 210.7 75.3 L 213.9 76.4 L 217.2 75.3 L 220.4 67.8 L 223.6 68.0 L 226.8 65.6 L 230.1 64.2 L 233.3 59.8 L 236.5 59.9 L 239.7 59.0 L 243.0 56.3 L 246.2 54.2 L 249.4 56.7 L 252.6 50.8 L 255.9 55.4 L 259.1 59.5 L 262.3 63.8 L 265.5 57.8 L 268.8 57.9 L 272.0 60.8 L 275.2 64.5 L 278.4 61.0 L 281.7 64.3 L 284.9 68.5 L 288.1 64.2 L 291.3 68.1 L 294.6 68.0 L 297.8 66.5 L 301.0 67.0 L 304.2 65.7 L 307.5 58.0 L 310.7 58.8 L 313.9 63.1 L 317.1 69.9 L 320.4 69.3 L 323.6 69.3 L 326.8 66.6 L 330.0 67.2 L 333.3 67.8 L 336.5 69.5 L 339.7 70.3 L 342.9 68.0 L 346.2 68.2 L 349.4 66.2 L 352.6 56.0 L 355.8 52.1 L 359.1 58.0 L 362.3 48.3 L 365.5 44.9 L 368.7 47.8 L 372.0 41.8 L 375.2 40.0 L 378.4 41.4 L 381.6 42.8 L 384.9 46.0 L 388.1 44.1 L 391.3 37.2 L 394.5 37.1 L 397.8 33.2 L 401.0 22.0 L 404.2 26.6 L 407.4 23.5 L 410.7 23.3 L 413.9 27.0 L 417.1 30.5 L 420.3 28.9 L 423.6 24.9 L 426.8 25.8 L 430.0 23.8"/>
  <line class="v-now" x1="450" y1="16" x2="450" y2="140"/>
  <g class="fade" style="--d:.9s">
    <line class="v-axis" x1="464" y1="76.0" x2="710" y2="76.0"/>
    <g class="v-bars"><rect class="up" x="470.0" y="50.2" width="9.0" height="25.8" rx="1.5"/><rect class="up" x="483.5" y="63.8" width="9.0" height="12.2" rx="1.5"/><rect class="dn" x="497.0" y="76.0" width="9.0" height="3.5" rx="1.5"/><rect class="dn" x="510.5" y="76.0" width="9.0" height="16.4" rx="1.5"/><rect class="dn" x="524.0" y="76.0" width="9.0" height="27.8" rx="1.5"/><rect class="up" x="537.5" y="69.5" width="9.0" height="6.5" rx="1.5"/><rect class="dn" x="551.0" y="76.0" width="9.0" height="8.4" rx="1.5"/><rect class="dn" x="564.5" y="76.0" width="9.0" height="9.5" rx="1.5"/><rect class="up" x="578.0" y="73.8" width="9.0" height="2.2" rx="1.5"/><rect class="up" x="591.5" y="70.8" width="9.0" height="5.2" rx="1.5"/><rect class="dn" x="605.0" y="76.0" width="9.0" height="34.6" rx="1.5"/><rect class="up" x="618.5" y="53.3" width="9.0" height="22.7" rx="1.5"/><rect class="dn" x="632.0" y="76.0" width="9.0" height="30.1" rx="1.5"/><rect class="up" x="645.5" y="36.6" width="9.0" height="39.4" rx="1.5"/><rect class="up" x="659.0" y="59.3" width="9.0" height="16.7" rx="1.5"/><rect class="dn" x="672.5" y="76.0" width="9.0" height="2.3" rx="1.5"/><rect class="up" x="686.0" y="45.8" width="9.0" height="30.2" rx="1.5"/><rect class="up" x="699.5" y="69.5" width="9.0" height="6.5" rx="1.5"/></g>
  </g>
</svg>
    <ul class="legend"><li class="legend__key" style="--k:var(--accent)">Strategy</li><li class="legend__key legend__key--dash" style="--k:var(--muted)">Benchmark</li><li class="legend__key legend__key--area" style="--k:var(--alert)">Drawdown</li><li class="legend__key legend__key--area" style="--k:var(--accent)">Monthly returns</li></ul>
    <p class="viz-hint">Swipe the diagram to see it in full &rarr;</p>
  </div>
  <ul class="project__points"><li>Backtesting and analysis framework for hypothesis testing on market behaviour and investments.</li><li>Development and optimisation of quantitative strategies, with performance and risk analysis.</li><li>Data lake for fundamental company data and prices, exposed through a REST API; evaluated and selected data providers.</li><li>Live performance monitoring of investments with rebalancing proposals.</li></ul>
  <div class="project__stack"><ul class="tags"><li class="tag">Python</li><li class="tag">NumPy</li><li class="tag">pandas</li><li class="tag">scikit-learn</li><li class="tag">Statsmodels</li><li class="tag">PostgreSQL</li><li class="tag">REST API</li><li class="tag">Docker</li><li class="tag">Terraform</li><li class="tag">Google Cloud</li></ul></div>
</article>

<p class="projects-outro">
  Longer history and education on the <a href="{{ '/resume' | relative_url }}">resume</a>.
</p>

<script>
(function () {
  if (!document.documentElement.classList.contains('js-viz')) return;
  var io = new IntersectionObserver(function (entries) {
    entries.forEach(function (e) {
      if (e.isIntersecting) { e.target.classList.add('viz--armed'); io.unobserve(e.target); }
    });
  }, { threshold: 0.2 });
  document.querySelectorAll('.viz').forEach(function (el) { io.observe(el); });
})();
</script>
