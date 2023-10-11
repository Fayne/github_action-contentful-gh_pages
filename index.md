---
layout: default
---
<main class="page-content" aria-label="Content">
    <div class="wrapper">
        {% for product in site.data.contentful.spaces.data.product %}
            <p>{{ product.name }}</p>
        {% endfor %}
    </div>
</main>