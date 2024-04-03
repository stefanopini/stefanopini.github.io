---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
no_h1_title: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Selected Publications

{% for post in site.publications reversed %}
  {% if post.selected == true %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

{% raw %} 
<br/><br/><br/>
{% endraw %}

# Other publications

{% for post in site.publications reversed %}
  {% if post.selected != true %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
