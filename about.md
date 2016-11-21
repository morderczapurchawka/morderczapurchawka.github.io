---
layout: home
title: About
permalink: /about/
---

## Nagłówek
<ul>
{% for item in site.data.dane %}
  <li>
    <strong>{{ item['klucz'] }}</strong>:
    {% for anotherItem in item['innyklucz'] %}
      {{ anotherItem }}
    {% endfor %}
  </li>
{% endfor %}
</ul>

### Mniejszy nagłówek

![Odnośnik](http://comps.canstockphoto.pl/can-stock-photo_csp5841197.jpg)

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor

<!--bzdura do zakomentowania-->

<div id="bzdura" style="color:red">
  Treść.
</div>

Lorem ipsum **dolor sit amet**, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, ~~quis nostrud~~ exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

1. cxzdsa
99. cxzdasda
12. cxzdasd sdasd as
70. cxzdasdasd

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
