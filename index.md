---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: main
---



# About me

{% include about-content.md %}

# Recent posts

<ul>
  {% for post in site.posts %}
    <li>
    <a href="{{ post.url }}">{{ post.title }}</a> <b>{{ post.date | date: "%d %B %Y" }}</b> 
    </li>
  {% endfor %}
</ul>


{% include frog_jump.html %}
