<ul>
  {% for post in site.posts %}
    <li>
      <h1>
      	<a href="{{ post.url }}">
      		{{ post.title }}
      	</a>
      	<small>{{ post.date | date: "%-d %B %Y" }} by {{ post.author }}</small>
  		</h1>
      <p>{{ post.excerpt }} <a href="{{ post.url }}">&rarr; read the full article</a></p>
    </li>
  {% endfor %}
</ul>