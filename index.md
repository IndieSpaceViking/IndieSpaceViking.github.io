---
layout: default
title: "Welcome to Planet Viking"
description: "Planet Viking – a hub for CTF write-ups, electronics projects, tool reviews, and embedded systems tutorials."
---

<div style="text-align: center;">
  <h1>🚀 Welcome to Planet Viking</h1>
  <p><strong>CTF strategies, embedded systems, cybersecurity adventures, and more.</strong></p>
</div>

---

## ✨ About This Site

Welcome to **Planet Viking** 
This is the official archive and active blog space for:

- 🧠 Cybersecurity & CTF write-ups  
- ⚡ Electronics & embedded systems projects  
- 🛠️ Tools reviews and experiments  
- 📚 Tutorials on tech topics I love  

💬 _"Learning by doing and hacking by curiosity."_

---

## 🔥 Latest Write-ups

{% assign latest_posts = site.posts | slice: 0, 5 %}
<ul>
  {% for post in latest_posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%b %d, %Y" }})</small></li>
  {% endfor %}
</ul>

[🔎 View All Write-ups](/writeups)

---

## 🗺️ Explore the Site

### 🛡️ Capture The Flag (CTF)

- [TryHackMe (THM)](/ctf/tryhackme)

### ⚡ Projects & Tutorials

- [Wireless Hacks](/projects/wireless)

### 🛠️ Tool Reviews

- [Hacking Tools](/reviews/tools)
- [My Favorite Exploits](/reviews/exploits)

---

## 👨‍🚀 About Me

I'm an

---

### ☕ Support the Mission

If you like what I do and want to support more content like this:

[🪙 Donate a Coffee](/donate)

---

<div style="text-align: center; font-size: 0.9rem; margin-top: 2rem;">
  Made with 💻 and ☕ on Earth by <strong>IndieSpaceViking</strong>
</div>
