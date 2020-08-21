---
layout: page
title: All Posts
permalink: /posts
---

<div class="row listrecent">

  {% for post in site.posts %}

  {% include postbox.html %}

  {% endfor %}

</div>
