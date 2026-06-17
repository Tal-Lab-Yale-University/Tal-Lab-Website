---
---

# Tal Lab

Tal Lab is a home for our research, collaborators, and lab updates. This site is being prepared as a clean public-facing hub, with space for publications, active projects, and team information as those sections are finalized.

{% include section.html %}

## Highlights

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

Browse tools, datasets, prototypes, and other lab efforts in one place. As project pages are added, this section can become the main landing area for reusable work.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Projects"
  flip=true
  style="bare"
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
  image="images/photo.jpg"
  link="team"
  title="Team"
  text=text
%}
