---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

<div style="text-align: center;">
### Principal Investigator
</div>

<style>
.pi-portrait {
  transform: scale(1.5);
  margin: 2em 0;
}
.pi-portrait .portrait-image {
  width: 300px;
  height: 300px;
  object-fit: cover;
}
.pi-portrait .portrait-name {
  font-size: 1.5em;
  font-weight: bold;
}
.pi-portrait .portrait-description {
  font-size: 1.2em;
}
</style>

<div class="pi-portrait">
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
</div>

<div style="text-align: center;">
### Faculty Member
</div>

{% include list.html data="members" component="portrait" filter="role == 'faculty'" %}

<div style="text-align: center;">
### Student Members
</div>

{% include list.html data="members" component="portrait" filter="role == 'student'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Join us

If you are interested in our research directions, we warmly welcome you to join our team! We offer strong funding support and excellent hardware resources.
1. Ph.D. student recruitment
2. Master's student recruitment
3. Internships (on-site / remote)
4. Postdoctoral positions



{% include section.html background="images/background.jpg" dark=true %}


{% include grid.html style="square" content=content %}
