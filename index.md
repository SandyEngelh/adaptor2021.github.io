<a href="url"><img src="resources/AdaptOR.png" align="left" height="200" width="200" ></a>

<ul>
   {% for item in site.data.navbar.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
