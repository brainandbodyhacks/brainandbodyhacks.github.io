---
layout: page
title: ebook
---
<div id="banner" style="overflow: hidden; display: inline-block;">
   <div class="image" style="max-width: 100%; max-height: 100%;">
       <img src ="assets/images/ebook-title-page.üdf" align="center">
   </div>
</div>
    
# Inhaltsverzeichnis
 {% for post in site.posts %}
      {{ post.title }}
 {% endfor %}

{% include_relative _faqs/faq-what-is-smart-brain-user.md %}

{% include_relative _faqs/faq-dumb-under-stress.md %}

<div class="posts">
  {% for post in site.posts %}
  <div class="post">
    <h1 class="post-title">
      {{ post.title }}
    </h1>
      {{ post.content }}
    <hr>
  </div>
  {% endfor %}
</div>
