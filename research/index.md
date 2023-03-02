---
title: Publications
nav:
  order: 5
  tooltip: Published works
---

# <i class="fa-solid fa-book-skull"></i>Publications

Test edit! consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include four-col.html col1=col1content col2=col2content col3=col3content col4=col4content %}

{% capture col1content %}
{%
  include tags.html
  tags="PopGen"
  link="https://voightlab.com/research/"
%}
{%
  include tags.html
  tags="Methods"
  link="https://voightlab.com/research/"
%}
{% endcapture %}

{% capture col2content %}
{%
  include tags.html
  tags="Selected"
  link="https://voightlab.com/research/"
%}
{% endcapture %}

{% capture col3content %}
{%
  include tags.html
  tags="Collaborative"
  link="https://voightlab.com/research/"
%}
{% endcapture %}

{% capture col4content %}
{%
  include tags.html
  tags="Complex Traits"
  link="https://voightlab.com/research/"
%}
{% endcapture %}


{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
