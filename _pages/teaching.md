---
layout: page
title: Teaching
permalink: /teaching/
---

<!-- shared SVG icons -->
{% capture github_icon %}<svg height="16" width="16" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>{% endcapture %}
{% capture book_icon %}<svg height="20" width="20" viewBox="0 0 16 16" fill="currentColor" style="opacity:0.6;flex-shrink:0;"><path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25l-2-1.5-2 1.5Z"/></svg>{% endcapture %}
{% capture link_icon %}<svg height="16" width="16" viewBox="0 0 16 16" fill="currentColor"><path d="M7.775 3.275a.75.75 0 0 0 1.06 1.06l1.25-1.25a2 2 0 1 1 2.83 2.83l-2.5 2.5a2 2 0 0 1-2.83 0 .75.75 0 0 0-1.06 1.06 3.5 3.5 0 0 0 4.95 0l2.5-2.5a3.5 3.5 0 0 0-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 0 1 0-2.83l2.5-2.5a2 2 0 0 1 2.83 0 .75.75 0 0 0 1.06-1.06 3.5 3.5 0 0 0-4.95 0l-2.5 2.5a3.5 3.5 0 0 0 4.95 4.95l1.25-1.25a.75.75 0 0 0-1.06-1.06l-1.25 1.25a2 2 0 0 1-2.83 0z"/></svg>{% endcapture %}

<style>
.teaching-section { margin-bottom: 2.5rem; }
.teaching-section h3 { margin-bottom: 1rem; }
.course-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; }
.course-card { border: 1px solid #e0e0e0; border-radius: 8px; padding: 1.5rem; box-shadow: 0 2px 8px rgba(0,0,0,0.07); display: flex; flex-direction: column; }
.course-card__meta { display: flex; align-items: center; gap: 0.6rem; margin-bottom: 0.75rem; }
.course-card__label { font-size: 0.78rem; font-weight: 600; letter-spacing: 0.05em; text-transform: uppercase; opacity: 0.5; }
.course-card h4 { margin: 0 0 0.5rem 0; font-size: 1.05rem; line-height: 1.4; }
.course-card p { margin: 0 0 1rem 0; font-size: 0.91rem; line-height: 1.6; opacity: 0.75; flex-grow: 1; }
.course-card__tags { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-bottom: 1.2rem; }
.course-card__tag { font-size: 0.75rem; padding: 0.2rem 0.55rem; border-radius: 20px; background: rgba(128,128,128,0.12); font-weight: 500; }
.course-card__link { display: inline-flex; align-items: center; gap: 0.4rem; font-size: 0.88rem; font-weight: 600; text-decoration: none; padding: 0.45rem 0.9rem; border-radius: 6px; border: 1px solid currentColor; opacity: 0.8; align-self: flex-start; }
.teaching-divider { border: none; border-top: 1px solid #e0e0e0; margin: 2rem 0; }
</style>

---

<div class="teaching-section">
<h3>University of Konstanz &middot; Summer Semester 2026</h3>
<div class="course-grid">

  <div class="course-card">
    <div class="course-card__meta">
      {{ book_icon }}<span class="course-card__label">Seminar &middot; 7 ECTS</span>
    </div>
    <h4>Fairness and Collective Decision-Making in AI</h4>
    <p>Introduces fairness metrics and datasets for AI, explores social choice theory for AI alignment, and examines current ethics debates regarding AI's impact on democracy.</p>
    <div class="course-card__tags">
      <span class="course-card__tag">fairness metrics</span>
      <span class="course-card__tag">social choice</span>
      <span class="course-card__tag">AI alignment</span>
      <span class="course-card__tag">democracy</span>
    </div>
    <a href="https://github.com/carinahausladen/konstanz-fairness-collective-ai" target="_blank" class="course-card__link">
      {{ github_icon }} View on GitHub
    </a>
  </div>

  <div class="course-card">
    <div class="course-card__meta">
      {{ book_icon }}<span class="course-card__label">Seminar &middot; 7 ECTS</span>
    </div>
    <h4>Dynamic Social Behavior</h4>
    <p>Introduces computational methods for modelling social dilemmas and dynamic social behavior, with a focus on learning dynamics, simulation, and behavioral time series analysis.</p>
    <div class="course-card__tags">
      <span class="course-card__tag">game theory</span>
      <span class="course-card__tag">reinforcement learning</span>
      <span class="course-card__tag">agent-based modeling</span>
      <span class="course-card__tag">LLMs</span>
    </div>
    <a href="https://github.com/carinahausladen/konstanz-dynamic-social-behavior" target="_blank" class="course-card__link">
      {{ github_icon }} View on GitHub
    </a>
  </div>

</div>
</div>

<hr class="teaching-divider">

<div class="teaching-section">
<h3>University of Konstanz &middot; Winter Semester 2025/26</h3>
<div class="course-grid">

  <div class="course-card">
    <div class="course-card__meta">
      {{ book_icon }}<span class="course-card__label">Seminar &middot; 2 SWS</span>
    </div>
    <h4>AI, Society, and Human Behavior: Research Methods in Context</h4>
    <p>Explores AI ethics, bias and fairness, social choice and alignment, reinforcement learning for social dilemmas, and computational methods for behavioral analysis. Part of M.A. Politics and Public Administration.</p>
    <div class="course-card__tags">
      <span class="course-card__tag">AI ethics</span>
      <span class="course-card__tag">bias &amp; fairness</span>
      <span class="course-card__tag">reinforcement learning</span>
      <span class="course-card__tag">computational social science</span>
    </div>
    <a href="https://github.com/carinahausladen/konstanz-ai-behavior-2026" target="_blank" class="course-card__link">
      {{ github_icon }} View on GitHub
    </a>
  </div>

</div>
</div>

<hr class="teaching-divider">

<div class="teaching-section">
<h3>ETH Zürich &middot; 2020–2025</h3>
<div class="course-grid">

  <div class="course-card">
    <div class="course-card__meta">
      {{ book_icon }}<span class="course-card__label">Seminar</span>
    </div>
    <h4>Digital Society: Ethical, Societal and Economic Challenges</h4>
    <p>Addresses ethical challenges arising from digital technologies including AI, Big Data, machine learning, IoT, and blockchain, from a social science and economics perspective.</p>
    <div class="course-card__tags">
      <span class="course-card__tag">digital ethics</span>
      <span class="course-card__tag">AI &amp; society</span>
      <span class="course-card__tag">Big Data</span>
      <span class="course-card__tag">economics</span>
    </div>
    <a href="https://coss.ethz.ch/education/DS.html" target="_blank" class="course-card__link">
      {{ link_icon }} Course page
    </a>
  </div>

  <div class="course-card">
    <div class="course-card__meta">
      {{ book_icon }}<span class="course-card__label">Summer School &middot; 2021</span>
    </div>
    <h4>Machine Learning for Behavioral Economics</h4>
    <p>Intensive five-day course at JGU Mainz covering NLP, text classification, word embeddings, deep learning, and time series clustering applied to social science research problems.</p>
    <div class="course-card__tags">
      <span class="course-card__tag">NLP</span>
      <span class="course-card__tag">text classification</span>
      <span class="course-card__tag">deep learning</span>
      <span class="course-card__tag">behavioral economics</span>
    </div>
    <a href="https://github.com/carinahausladen/SS_JGU_21_ML" target="_blank" class="course-card__link">
      {{ github_icon }} View on GitHub
    </a>
  </div>

</div>
</div>
