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

<!---
{% include_relative _posts/2024-01-01-brainhack-productivity.md %}

{% include_relative _posts/2024-01-02-bodyhack-omega3.md %}

{% include_relative _posts/2024-01-03-bodyhack-microworkouts.md %}

{% include_relative _posts/2024-01-04-brainhack-neurogenese.md %}

{% include_relative _posts/2024-01-05-brainhack-smart-goals.md %}

{% include_relative _posts/2024-01-06-brain-hack-pause-the-movie.md %}

{% include_relative _posts/2024-01-07-magnesium-calm.md %}

{% include_relative _posts/2024-01-08-kluge-entscheidung.md %}

{% include_relative _posts/2024-01-09-bodyhack-exercise-snacking.md %}
-->

