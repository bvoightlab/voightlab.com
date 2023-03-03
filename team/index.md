---
title: Team
nav:
  order: 2
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /staff
  - /trainees
---

# <i class="fa-solid fa-users"></i>Team

{% include list.html data="members" component="portrait" filters="role: pi, group: member" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: member" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: member" %}

{% include section.html background="images/banner.jpg" dark=true%}

{% include section.html %}

## Alumni

Our former lab members who have moved on to new places and activities!  

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/team/alfred-p-sloan-foundation.png"
  link1="https://sloan.org/"
  tooltip6="Alfred P. Sloan Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/photo.jpg"
  link4="https://nasa.gov/"
  tooltip4="Cool Foundation"

  image5="images/photo.jpg"
  link5="https://nasa.gov/"
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6="https://nasa.gov/"
  tooltip6="Cool Initiative"
%}
