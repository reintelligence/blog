Welcome to my new blog. Here, you'll find my thoughts on general intelligence, as well as my interpretation of the world. Stay tuned for the upcoming news!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}/blog/{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
