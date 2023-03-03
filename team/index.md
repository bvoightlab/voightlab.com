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

{% include section.html %}

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

  image1="images/team/alfred-p-sloan-foundation.png"
  link1="https://sloan.org/"
  tooltip6="Alfred P. Sloan Foundation"

  image2="images/team/national-institute-diabetes-digestive-kidney-diseases.png"
  link2="https://www.niddk.nih.gov/"
  tooltip2="National Institute of Diabetes and Digestive and Kidney Diseases"

  image3="images/team/american-heart-association.png"
  link3="https://www.heart.org/"
  tooltip3="American Heart Association"

  image4="images/team/ww-smith-charitable-trust.png"
  link4="http://www.wwsmithcharitabletrust.org/"
  tooltip4="W.W. Smith Charitable Trust"

  image5="images/team/us-department-of-veterans-affairs.png"
  link5="https://www.va.gov/"
  tooltip5="U.S. Department of Veterans Affairs"

%}

{% include section.html %}
