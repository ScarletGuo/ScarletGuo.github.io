---
layout: base
permalink: /experience/
title: "Experience"
show_title: true
description: "Work, research and teaching experience of Zhihan (Scarlet) Guo."
---

<section>
  <p class="label">Work &amp; Research</p>
  {% include job-list.html items=site.data.experience.work %}

  <p class="label sub-label">Earlier</p>
  {% include job-list.html items=site.data.experience.earlier %}
</section>

<section>
  <p class="label">Education</p>
  {% include job-list.html items=site.data.experience.education %}
</section>

<section>
  <p class="label">Teaching</p>
  {% include job-list.html items=site.data.experience.teaching %}
</section>
