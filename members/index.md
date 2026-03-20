---
title: Members
description: Members
nav:
  order: 2
  tooltip: Members
footer: images/banner_ssu.jpg
header: images/banner_ssu.jpg
footer-dark: true
---

## <i class="fas fa-microscope"></i> Professor

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: prof"
%}

{% include section.html %}

## <i class="fas fa-users"></i> Graduate students

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: grad"
%}

---

## <i class="fas fa-users"></i> Undergraduate students

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ug"
%}
{:.center}

{% include section.html %}

## <i class="fas fa-users"></i> Past Members (Undergraduate Students)

- (**2023.07 - 2024.12**) 강민규, 이보성, 민동욱
- (**2025.01 - 2025.12**) 이혁진, 최민영, 조정운, 손성은

  {% include section.html %}

<!--{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alum_ug"
%}
{:.center} -->

<!--

## <i class="fas fa-users"></i> Students

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: grad"
%}
-->

<!--
{% include section.html %}

## Funding


Our work is made possible by funding from several organizations.
{:.center}
 {%
  include gallery.html
  style="square"

  image1="images/members/felix.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

%} -->
