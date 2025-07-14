---
layout: default
title: ""
description: ""
---

<div style="text-align: center;">
  <h1>Coffee Meets code!</h1>
  <p><strong>Development strategies, embedded systems, cybersecurity adventures, and more.</strong></p>
</div>

<hr>

## About This Site

<div style="max-width: 700px; margin: 0 auto; text-align: center;">

Welcome to **Planet Viking** – the official archive and blog space for:

- 🧠 Cybersecurity & CTF write-ups  
- ⚡ Electronics & embedded systems projects  
- 🛠️ Tool reviews and experiments  
- 📚 Tutorials on tech topics I love  

💬 _"Learning by doing and hacking by curiosity."_

</div>

---

## 🔥 Latest Write-ups

<div style="max-width: 700px; margin: 0 auto;">
{% assign latest_posts = site.posts | slice: 0, 5 %}
<ul>
  {% for post in latest_posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%b %d, %Y" }})</small></li>
  {% endfor %}
</ul>

<p style="text-align: center;"><a href="/writeups">🔎 View All Write-ups</a></p>
</div>


---

## 👨‍🚀 About Me

<div style="max-width: 700px; margin: 0 auto; text-align: center;">
I'm an electronics tinkerer and cybersecurity enthusiast who enjoys combining hardware projects with hands-on hacking. I believe in learning by doing and love sharing the ride.
</div>

---

### ☕ Support the Mission

<div style="text-align: center;">
If you like what I do and want to support more content like this:

[🪙 Donate a Coffee](/donate)
</div>

---

<div style="text-align: center; font-size: 0.9rem; margin-top: 2rem;">
  Made with 💻 and ☕ on Earth by <strong>IndieSpaceViking</strong>
</div>
