---
layout: default
---
<html lang="{{ page.lang | default: site.lang | default: "en" }}">
  <body>
		{% for post in site.posts %}
			<a href="{{ post.url }}">{{ post.title }}</a>
			{{ post.title }}
			{{ post.description }}
			<br>
		{% endfor %}
  </body>
</html>
