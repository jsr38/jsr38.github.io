---
layout: page
title: Jeremy Reeve
tagline: home
---
{% include JB/setup %}

    
## Posted notes

Here's a list of notes in reverse chronological order.  The posts were created from html exporting Emacs org-mode files and are currently very much under construction.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


## Publications


## Links to various resources




