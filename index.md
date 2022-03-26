---
layout: default
title: Home
nav_order: 1
description: "Responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# About the project

\<REPLACE primary business case + main features & benefits\>

[View it on GitHub](https://github.com/the-tatanka/github-pages-jekyll-template){: .btn .fs-5 .mb-4 .mb-md-0 }

\<REPLACE project name\> is &copy; 2017-{{ "now" | date: "%Y" }} by [the-tatanka](https://github.com/the-tatanka/github-pages-jekyll-template).

# License

\<REPLACE project name\> is distributed by an [MIT license](https://github.com/the-tatanka/github-pages-jekyll-template/blob/master/LICENSE).

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change. :)

#### Thank you to the contributors!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
