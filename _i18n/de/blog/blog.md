<h1>{% t blog.latest_posts %}</h1>
<hr>
<ul class="list-unstyled">
	{% include list-posts.html posts=site.posts %}
</ul>