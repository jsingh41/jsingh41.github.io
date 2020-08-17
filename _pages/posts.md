---
layout: page
title: All Posts
permalink: /posts
---

<section class="recent-posts">

  <div class="section-title">

    <h2><span>All Stories</span></h2>

  </div>

  <div class="row listrecent">

    {% for post in paginator.posts %}

    {% include postbox.html %}

    {% endfor %}

  </div>

</section>
