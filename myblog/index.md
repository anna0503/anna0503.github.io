---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
<h1> my blog </h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ https://anna0503.github.io/myblog/_post/2018-01-06 test.md }}">{{ test }}</a>
    </li>
  {% endfor %}
</ul>
