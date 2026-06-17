---
---

# Tal Lab

Tal Lab studies questions in obstetrics, gynecology, and reproductive sciences. This site highlights the lab's research interests, publications, and team.

{% include section.html %}

## Explore

{% capture text %}

Explore the questions, methods, and publication record that shape the lab's work. This section is set up to grow with papers, talks, and other research outputs.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Research"
  text=text
%}

{% capture text %}

Meet the people behind the lab. Team profiles can be expanded here with roles, bios, and ways to connect.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Lab Meeting.jpeg"
  link="team"
  title="Team"
  flip=true
  style="bare"
  text=text
%}
