## Welcome to my blog pages

I will post writings about my PhD research here


## List of posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="https://pages.github.cs.adelaide.edu.au/a1688714/a1688714/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


## List of tags:

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
