---
layout: home
---

<div class="row">
  {% for post in site.posts %}
    <div class="col s6">
      <div class="card">
        <div class="card-image waves-effect waves-block waves-light">
          <img class="activator" src="http://comps.canstockphoto.pl/can-stock-photo_csp5841197.jpg">
        </div>
        <div class="card-content">
          <span class="card-title activator grey-text text-darken-4">{{ post.title }}<i class="material-icons right">more_vert</i></span>
          <p><a href="#">This is a link</a></p>
        </div>
        <div class="card-reveal">
          <span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">close</i></span>
          {{ post.content }}
        </div>
      </div>
    </div>
  {% endfor %}
</div>
