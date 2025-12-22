---
layout: default
title: "Home"
permalink: /
show_title: false
description: "Personal website"
---

<div class="grid cols-2">
  <div class="card">
    <h2>About</h2>
    <p>
      <!-- 여기에 2~3문장 소개를 넣으세요 -->
      I work on trustworthy AI systems for autonomous driving under uncertainty.
    </p>
    <p class="muted">
      <!-- 키워드/관심사 요약 -->
      Uncertainty Quantification · Risk Modeling · Reinforcement Learning · Autonomous Driving · LLM Optimization
    </p>
    <p>
      <!-- 링크는 _config.yml의 social을 참고해서 수정 -->
      <a href="https://github.com/{{ site.social.github }}">GitHub</a> ·
      <a href="{{ site.social.scholar }}">Google Scholar</a> ·
      <a href="mailto:{{ site.social.email }}">Email</a> ·
      <a href="{{ '/pages/cv/' | relative_url }}">CV</a>
    </p>
  </div>

  <div class="card">
    <h2>News</h2>
    <p class="muted">
      <!-- 최근 소식 2~4줄 정도 -->
      (Add your latest update here: paper, talk, open-source release, etc.)
    </p>
  </div>
</div>

<div class="card">
  <h2>Selected Publications</h2>
  <!-- 아래는 예시 골격: 채워 넣고, publications 페이지에서 전체 목록을 관리 -->
  <p>(Add 5–8 representative papers here, and link to the full list.)</p>
  <p><a href="{{ '/pages/publications/' | relative_url }}">View all publications →</a></p>
</div>

<div class="card">
  <h2>Selected Projects</h2>
  <p>(Add 6–10 representative projects here, and link to the full list.)</p>
  <p><a href="{{ '/pages/projects/' | relative_url }}">View all projects →</a></p>
</div>
