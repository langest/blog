---
layout: default
---
<body>
	{% for post in site.posts %}
	<a href="{{ post.url }}">
		<div>
			<h1>
				{{ post.title }}
			</h1>
			<p>
				{{ post.description }}
			</p>
		</div>
	</a>
	{% endfor %}
</body>
