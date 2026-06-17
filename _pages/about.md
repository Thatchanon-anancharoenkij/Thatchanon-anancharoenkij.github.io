---
layout: about
title: about
permalink: /
subtitle: PhD Student in Applied Statistics

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  # การลบ more_info ออกจะทำให้คำบรรยายใต้ภาพหายไป
  
news: true # เปิดใช้งานส่วน News
selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5
---

# News
{% if site.news != empty %}
  {%- assign news_size = site.news | size -%}
  <div class="news">
    {% if news_size != 0 %}
      {% for item in site.news limit: 5 %}
        <div class="row">
          <div class="col-sm-2">
            <span class="badge">{{ item.date | date: "%b %-d, %Y" }}</span>
          </div>
          <div class="col-sm-8">
            {% if item.inline %}
              {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
            {% else %}
              <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
            {% endif %}
          </div>
        </div>
      {% endfor %}
    {% else %}
      <p>No news so far...</p>
    {% endif %}
  </div>
{% endif %}

I am currently a PhD student in Applied Statistics at Chiang Mai University.

My research focuses on Causal Inference and Statistical Learning.
