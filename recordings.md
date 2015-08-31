---
layout: page
title: Recordings
position: down
permalink: /recordings/
published: true
---


![compositions by max dreyer](/images/music.jpg)

A collection of recordings by Max Dreyer, also known as The Dirt Eater.

<html>
  <ul class="post-list">
    {% for post in site.categories.recordings %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %Y" }}</span>
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
  </ul>

  </html>
