---
layout: default
title: News & Announcements
---

# News & Announcements

{% assign all_news = site.news | sort: "date" | reverse %}

{% for news in all_news %}

## [{{ news.title }}]({{ news.url | relative_url }})

<small>{{ news.date | date: "%d %B %Y" }}</small>

{{ news.content | markdownify | strip_html | strip_newlines | truncatewords: 35 }}

[Read more →]({{ news.url | relative_url }})

{% endfor %}
