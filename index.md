---
layout: default
title: Welcome to Saurabh's Site
---

# Hello, I'm Saurabh 👋

Welcome to my **first GitHub Page**! I'm so excited you're here.

## 🚀 About Me
- Software enthusiast and lifelong learner.
- Passionate about building useful things with code.

## 📝 Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

## 🔥 Projects
- **Awesome App** – _Coming Soon!_
- **Open Source Contributions** – _Coming Soon!_

## 📫 Let's Connect
- [GitHub](https://github.com/saurabhusername)
- [LinkedIn](https://www.linkedin.com/in/saurabhns/)
- [Twitter](https://twitter.com/saurabhtwitter)

---

_Thanks for stopping by! 🌟_
