---
layout: page
title: Colleagues
position: up
permalink: /colleagues/
---

In our line of work, the Dreyer Brothers have come across many allies and colleagues. Some of them we have worked with intimately, some professionally, some not at all. 

![colleagues](/images/colleagues.jpg)

<html>
  <ul class="post-list">
    {% for colleague in site.data.colleagues %}
      <li>
        <h2>
          <a class="post-link" href="{{ colleague.url }}">{{ colleague.name }}</a>
        </h2>
        <p>{{ colleague.description }}</p>
      </li>
    {% endfor %}
  </ul>  
</html>