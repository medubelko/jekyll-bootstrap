---
layout: default
---

<section id="posts" class="container">
    <div class="row">
        <div class="col">
            <h1 class="border-bottom">Posts</h1>
        </div>
    </div>
    {% for post in site.posts %}
        <div class="row">
            <div class="col">
                <h2><a class="text-dark" href="{{ post.url }}">{{ post.title }}</a></h2>
                {{ post.excerpt }}
            </div>
        </div>
     {% endfor %}
    <div class="row">
    </div>
</section>

