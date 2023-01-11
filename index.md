---
layout: default
title: ESTML 2023
---

## About ESTML 2023

The **ESTQML 2023** conference is organized by 

- the University of Luxembourg (Prof. Alexandre Tkatchenko, Dr. Carolin Müller, and Adil Kabylda), 
- Aalto University (Prof. Patrick Rinke, Dr. Hilda Sandström), and
- the University of Turku (Ass. Prof. Milica Todorovic, and Dr. Ransell D'Souza).

The workshop takes place in XXX at the YYY Hotel from 17<sup>th</sup> to 21<sup>st/sup> of April 2023.


<div class="home" id="home">
  <h1 class="pageTitle">Recent Information</h1>
  <div class="posts noList">
    {%- for post in paginator.posts -%}
      <article>
        <span class="date">{{ post.date | date: '%B %d, %Y' }}</span>
        <h3><a class="post-link" href="{{ post.url }}">{{ post.title }}</a></h3>
        <p>{%- if post.description -%}{{ post.description }}{%- else -%}{{ post.excerpt | strip_html }}{%- endif -%}</p>
      </article>
    {%- endfor -%}
  </div>
  
</div>
  

_________________
*The website and logo has been created by Carolin Müller. *
