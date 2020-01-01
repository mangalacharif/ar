---
layout: page
stylesheet: /resources/book.css
---

<div class="book_preview_block">
  <div class="right_half">
    <h1>{{ page.title }}</h1>
    <h2>{{ page.subtitle }}</h2>
    <p>{{ page.description }}</p>
  </div>
  <img class="book_cover" src="{{ page.cover_url }}" alt="Book Cover">
</div>

{{ content }}
