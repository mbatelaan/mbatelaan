---
layout: home
---

## Posts

I will post writings about my PhD research here


## List of posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


## List of tags:

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}


<h2>{{ site.data.navigation.list_title }}</h2>
<ul>
   {% for item in site.data.navigation.main %}
      <li>
	<a href="{{ item.url }}">{{ item.title }}</a>
      </li>
   {% endfor %}
</ul>


