---
layout: default
title: 首页
---

# 👋 欢迎来到我的博客

这里记录 AI、编程、自动化相关内容。

---

## 📚 最新文章

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
  - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
