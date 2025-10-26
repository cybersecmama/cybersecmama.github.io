---
layout: default
title: Home
---

# Welcome to CyberSecMama

Family focused online safety awareness. CyberSecurity for the whole family!

Coming soon... 
<p>CyberSecMama with CyberSecCritters<br>
  
Check out <a href="https://linktr.ee/CyberSecMama" target="_blank" rel="noopener">CyberSecMama Linktree</a></p>

<nav class="post-menu" aria-label="Recent posts">
  <h2>Recent posts</h2>
  <ul>
    {% for post in site.posts limit:10 %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <small class="post-date">{{ post.date | date: "%b %-d, %Y" }}</small>
      </li>
    {% endfor %}
  </ul>
  <p class="all-posts"><a href="{{ '/archives' | relative_url }}">See all posts</a></p>
</nav>
