---
layout: default
---
<div class="home">
  <ul class="post-list">
    {% for map in site.maps %}
      <div class="content" style="margin: 20px;">
        <a href="{{ map.url }}">{{ map.title }}</a>
      </div>
    {% endfor %}
  </ul>
</div>
