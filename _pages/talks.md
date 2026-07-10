---
layout: page
title: Talks
permalink: /talks/
---

{% for t in site.data.talks %}
<article class="talk">
  <h3 class="talk__title">{{ t.title }}</h3>
  <div class="talk__cols">
    {% if t.slides_embed and t.slides_embed != "" %}
    <div class="talk__media">
      <iframe src="{{ t.slides_embed }}/embed?style=light&byline=hidden&share=hidden" loading="lazy" scrolling="no" allowfullscreen title="Slides — {{ t.title }}"></iframe>
      <a class="talk__slideslink" href="{{ t.slides_embed }}" target="_blank" rel="noopener">Open on slides.com ↗</a>
    </div>
    {% endif %}
    <div class="talk__venues-col">
      <ul class="talk__venues">
        {% for v in t.venues %}
        <li>
          <span class="talk__venue">{{ v.name }}</span>
          {% if v.video and v.video != "" %}<a class="yt-btn" href="{{ v.video }}" target="_blank" rel="noopener" aria-label="Watch on YouTube"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M8 5v14l11-7z"/></svg>Watch</a>{% endif %}
          <span class="talk__year">{{ v.year }}</span>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</article>
{% endfor %}
