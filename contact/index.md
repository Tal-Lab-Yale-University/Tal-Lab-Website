---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

<div class="contact-intro">
  <p class="contact-kicker">Yale School of Medicine</p>
  <p class="contact-lead">
    Our lab is located in the Laboratory for Surgery, Obstetrics, and Gynecology
    at the Yale School of Medicine. We welcome inquiries from prospective
    collaborators, trainees, and anyone interested in learning more about our
    research.
  </p>
</div>

<div class="contact-actions">

{%
  include button.html
  type="email"
  text="reshef.tal@yale.edu"
  link="reshef.tal@yale.edu"
%}
{%
  include button.html
  type="address"
  text="375 Congress Ave, New Haven, CT 06519"
  tooltip="Tal Lab location"
  link="https://maps.google.com/?q=375+Congress+Ave,+New+Haven,+CT+06519"
%}

</div>

{% include section.html %}

{% capture col1 %}
<div class="contact-panel">
  <p class="contact-kicker">Visit Us</p>
  <h2>Tal Lab at Yale</h2>
  <p class="contact-copy">
    Our lab is based in the Laboratory for Surgery, Obstetrics, and Gynecology,
    School of Medicine, Yale University.
  </p>
  <div class="contact-detail">
    <strong>Address</strong><br>
    375 Congress Ave<br>
    New Haven, CT 06519
  </div>
  <div class="contact-detail">
    <strong>Research Inquiries</strong><br>
    Please contact the PI, Dr. Reshef Tal, at
    <a href="mailto:reshef.tal@yale.edu">reshef.tal@yale.edu</a>.
  </div>
</div>
{% endcapture %}

{% capture col2 %}
<div class="contact-map">
  <iframe
    title="Tal Lab location map"
    src="https://www.google.com/maps?q=375%20Congress%20Ave%2C%20New%20Haven%2C%20CT%2006519&z=15&output=embed"
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade"
  ></iframe>
</div>
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}

## Get In Touch

Interested in learning about our research? Please contact the PI, **Dr. Reshef Tal**, at [reshef.tal@yale.edu](mailto:reshef.tal@yale.edu). We would be glad to hear from prospective students, collaborators, and colleagues interested in the lab's work.
