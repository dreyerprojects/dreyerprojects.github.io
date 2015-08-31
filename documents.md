---
layout: page
title: Documents
position: up
permalink: /documents/
description: "Aside from the Dreyer Brothers, some other Dreyers"
published: true
---


<html>
  <ul class="post-list">
    {% for documents in site.documents %}
      <li>
        <h2>
          <a class="post-link" href="{% if post.layout == 'link' %}{{ post.hyperlink }}{% else %}{{ documents.url | prepend: site.baseurl }}">{{ documents.title }}</a>
        </h2>
        <p>{{ documents.description }}</p>
      </li>
    {% endfor %}
  </ul>  
</html>