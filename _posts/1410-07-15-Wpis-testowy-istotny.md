---
layout: post
title: "NOWA, ŚWIETNA NAZWA"
permalink: /important/
image: http://comps.canstockphoto.pl/can-stock-photo_csp5841197.jpg
table: ['Raz','dwa','pięć']
---
# {{ page.image }}
# {{ site.title }}

{% for item in page.table %}
  {{ item }}
{% endfor %}

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

![Ilustracja]({{ page.image }})
