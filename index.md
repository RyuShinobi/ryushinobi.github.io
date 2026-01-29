---
layout: single
title: "Hello"
---

Hello! I’m **Maine Aguilar**.

I work as **Atlassian Administrator**, also working with Automations, DevOps and System Administrations.
This site is a collection of notes, write-ups, and things I want to remember.

You’ll find posts about:
- Atlassian
- Automation (UI Path / Selenium / .Net Core)
- Linux and Windows, self-hosting
- Notes, links, and weeknotes

---

## Latest posts
{% assign posts = site.posts | slice: 0, 10 %}
{% for post in posts %}
- **[{{ post.title }}]({{ post.url }})**  
  <small>{{ post.date | date: "%b %d, %Y" }} · {{ post.read_time }} min read</small>
{% endfor %}
