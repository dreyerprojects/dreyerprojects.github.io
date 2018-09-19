---
layout: page
title: Writing
position: down
permalink: /writing/
published: true
---

![writing by jacob dreyer](/images/writing.jpg)

For 5 years, Jacob Dreyer has been tracing paths through the modern Chinese cities (Shanghai, Beijing, Chongqing, Suzhou, Haerbin), in search of a new form of collective life. In writing, photography and film, individually and with collaborators, in and outside of academic institutions, this itinerary could continue for a lifetime. 

Recent projects include &lsquo;The Nocturnal Wanderer&rsquo;, a book forthcoming from Eros Press, and a film project with the working title &lsquo;Harbin: Anti-Capital,&rsquo; in collaboration with Wang Bo. A new manuscript is in progress. Jacob is a frequent contributor to [COBO Social](https://www.cobosocial.com/user/jacobdreyer/), and his work has appeared in The Guardian, The New York Times, the Calvert Journal, and many other well-known media outlets. 

<html>
  <ul class="post-list">
    {% for post in site.categories.writing %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %Y" }}</span>
        <h2>
          <a class="post-link" href="{% if post.layout == "link" %}{{ post.hyperlink }}{% else %}{{ post.url | prepend: site.baseurl }}{% endif %}">{{ post.title }}</a>
        </h2>
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
  </ul>

  </html>
