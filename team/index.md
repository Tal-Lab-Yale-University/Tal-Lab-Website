---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the people behind Tal Lab. Team profiles below currently use placeholder images and can be updated with full bios and headshots as they become available.

{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html %}

## Team

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}
