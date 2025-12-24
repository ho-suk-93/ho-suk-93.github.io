---
layout: default
title: "Home"
permalink: /
description: "Ho Suk personal website"
---

<section id="about" class="section">
  <div class="hero">
    <div class="hero-inner">
      <!-- 사진 파일을 assets/img/headshot.jpg로 넣으면 표시됩니다 -->
      <img class="avatar" src="{{ '/assets/img/headshot.jpg' | relative_url }}" alt="Headshot" />

      <div>
        <h1 class="hero-title">Ho Suk</h1>
        <p class="hero-sub">
          (한두 문장 소개를 여기에 넣으세요. 예: Trustworthy AI for autonomous driving under uncertainty.)
        </p>

        <div class="pills">
          <span class="pill">Uncertainty Quantification</span>
          <span class="pill">Risk Modeling</span>
          <span class="pill">Reinforcement Learning</span>
          <span class="pill">Autonomous Driving</span>
          <span class="pill">LLM Optimization</span>
        </div>

        <div class="actions">
          <a class="btn primary" href="mailto:{{ site.social.email }}">Email</a>
          <a class="btn" href="https://github.com/{{ site.social.github }}">GitHub</a>
          <a class="btn" href="{{ site.social.scholar }}">Google Scholar</a>
          <a class="btn" href="{{ '/assets/cv/CV.pdf' | relative_url }}">CV (PDF)</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="research" class="section">
  <div class="card">
    <div class="h2">Research</div>
    <p class="muted">(Research narrative 1–2 paragraphs)</p>
  </div>

  <div class="grid cols-3" style="margin-top:14px;">
    <div class="card">
      <div class="h2">Theme A</div>
      <p class="muted">(핵심 주제/기여 요약)</p>
    </div>
    <div class="card">
      <div class="h2">Theme B</div>
      <p class="muted">(핵심 주제/기여 요약)</p>
    </div>
    <div class="card">
      <div class="h2">Theme C</div>
      <p class="muted">(핵심 주제/기여 요약)</p>
    </div>
  </div>
</section>

<section id="publications" class="section">
  <div class="card">
    <div class="h2">Publications</div>
    <p class="muted">
      Full list: <a href="{{ site.social.scholar }}">Google Scholar</a>
    </p>

    <div class="item">
      <p class="item-title">(Paper Title 1)</p>
      <p class="item-meta">(Venue, Year) · (Links: PDF / Code / Project)</p>
    </div>

    <div class="item">
      <p class="item-title">(Paper Title 2)</p>
      <p class="item-meta">(Venue, Year) · (Links: PDF / Code / Project)</p>
    </div>

    <div class="item">
      <p class="item-title">(Paper Title 3)</p>
      <p class="item-meta">(Venue, Year) · (Links: PDF / Code / Project)</p>
    </div>
  </div>
</section>

<section id="projects" class="section">
  <div class="card">
    <div class="h2">Projects</div>
    <p class="muted">(대표 프로젝트 6–10개를 짧게 요약)</p>
  </div>

  <div class="grid cols-2" style="margin-top:14px;">
    <div class="card">
      <div class="h2">Project A</div>
      <p class="muted">(Role / Outcome / Tech)</p>
    </div>
    <div class="card">
      <div class="h2">Project B</div>
      <p class="muted">(Role / Outcome / Tech)</p>
    </div>
    <div class="card">
      <div class="h2">Project C</div>
      <p class="muted">(Role / Outcome / Tech)</p>
    </div>
    <div class="card">
      <div class="h2">Project D</div>
      <p class="muted">(Role / Outcome / Tech)</p>
    </div>
  </div>
</section>

<section id="service" class="section">
  <div class="card">
    <div class="h2">Service</div>

    <div class="item">
      <p class="item-title">(Reviewer / PC / Workshop role 1)</p>
      <p class="item-meta">(Year / Venue)</p>
    </div>

    <div class="item">
      <p class="item-title">(Reviewer / PC / Workshop role 2)</p>
      <p class="item-meta">(Year / Venue)</p>
    </div>
  </div>
</section>

<section id="contact" class="section">
  <div class="card">
    <div class="h2">Contact</div>
    <p class="muted">
      Email: <a href="mailto:{{ site.social.email }}">{{ site.social.email }}</a>
      {% if site.social.github and site.social.github != "" %}
        · GitHub: <a href="https://github.com/{{ site.social.github }}">{{ site.social.github }}</a>
      {% endif %}
    </p>
  </div>
</section>
