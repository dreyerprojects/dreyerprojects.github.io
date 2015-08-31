---
layout: page
title: Writing
position: down
permalink: /writing/
---

![writing by jacob dreyer](/images/writing.jpg)

For 5 years, Jacob Dreyer has been tracing paths through the modern Chinese cities (Shanghai, Beijing, Chongqing, Suzhou, Haerbin), in search of a new form of collective life. In writing, photography and film, individually and with collaborators, in and outside of academic institutions, this itinerary could continue for a lifetime. 

Recent projects include &lsquo;The Nocturnal Wanderer&rsquo;, a book forthcoming from Eros Press, and a film project with the working title &lsquo;Harbin: Anti-Capital,&rsquo; in collaboration with Wang Bo. A new manuscript is in progress. 

<html>
  <ul class="post-list">
    {% for post in site.categories.writing %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %Y" }}</span>
        <h2>
          <a class="post-link" href="{% if post.hyperlink != "" %}{{ post.hyperlink }}{% else %}{{ post.permalink | prepend: site.baseurl }}{% endif %}">{{ post.title }}</a>
        </h2>
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
  </ul>

  </html>
