---
layout: page
title:  "About"
parmalink: /about/
---

# This blog is where I will post writings related to my PhD research.




## Navigation

<h2>{{ site.data.navigation.list_title }}</h2>
<ul>
   {% for item in site.data.navigation.main %}
      <li>
	<a href="{{ item.url }}">{{ item.title }}</a>
      </li>
   {% endfor %}
</ul>