---
layout: page
title: ebook
---
<div id="banner" style="overflow: hidden; display: inline-block;">
   <div class="image" style="max-width: 100%; max-height: 100%;">
       <img src ="assets/images/ebook-title-page.pdf" align="center">
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


<iframe src="https://onedrive.live.com/embed?resid=F04595E7901D39B9%21116&authkey=!ADI_fBaCgboPC1E" width="320" height="320" frameborder="0" scrolling="no" allowfullscreen></iframe>#


<iframe width="560" height="315" src="https://www.youtube.com/embed/1CHGiid6N9Q?si=O8MQoHvzzGeK13RF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



<iframe width="560" height="315" src="https://onedrive.live.com/embed?resid=F04595E7901D39B9%21116&authkey=!ADI_fBaCgboPC1E" title="Marias video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
