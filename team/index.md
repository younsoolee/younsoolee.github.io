---
title: Members
description: Our team members
nav:
  order: 2
  tooltip: About our team
header: images/banner_ssu.jpg
footer: images/banner_ssu.jpg
footer-dark: true
---

# <i class="fas fa-users"></i>Members




{% include section.html %}

## Professor
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}

---
## Graduate Students
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
---

## Undergraduate Students
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{:.center}


<!--
{% include section.html background="images/banner_ssu.jpg" dark=true%}

-->

<!--
{% include section.html %}
## Join

#### Post Dogtoral Researcher


- 3+ (dog) years experience managing bone portfolios
- Strong desire to learn tricks and go on walkies
- Aptitude to sit and stay

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}
-->

<!--
{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

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
-->