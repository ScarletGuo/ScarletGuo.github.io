---
layout: base
permalink: /
title: "About"
description: "Zhihan (Scarlet) Guo — database engineer at Salesforce, Ph.D. UW–Madison."
redirect_from:
  - /about/
  - /about.html
---

<section>
  <div class="prose">
    <p>My interests lie at the intersection of database systems, distributed systems, and AI-native infrastructure. I am especially drawn to applications in healthcare, where I ultimately hope to see this infrastructure make a meaningful difference.</p>
  </div>
</section>

<section>
  <p class="label">Education</p>
  <ul class="education-list">
    <li>
      <strong>Ph.D. in Computer Sciences, University of Wisconsin–Madison</strong>
      <p class="award"><strong>Microsoft Research PhD Fellowship</strong><span class="education-meta">2021–22 · US &amp; Canada</span></p>
      <p>2019 - 2023 Advised by <a href="https://pages.cs.wisc.edu/~yxy/">Prof. Xiangyao Yu</a>.</p>
      <p>Focused on transaction processing and cloud-native databases, leading to publications at SIGMOD, VLDB, and FAST.</p>
      <p>2018 - 2019 Advised by <a href="https://thodrek.github.io/">Prof. Theodoros Rekatsinas</a></p>
      <p>Focused on ML-driven data integration and data cleaning.</p>
    </li>
    <li>
      <strong>B.S. in Computer Sciences, University of Wisconsin–Madison</strong>
    </li>
  </ul>
</section>

{% assign selected_pubs = site.data.publications | where: "selected", true %}
<section>
  <p class="label">Selected Publications</p>
  {% include publication-list.html items=selected_pubs %}
  <a class="more" href="{{ '/publications/' | relative_url }}">All publications →</a>
</section>
