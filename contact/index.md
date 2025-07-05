---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html dark=true %}

# Join Us

We are recruiting new members! Please refer to general directions below if you are interested and feel free to reach out to us directly.

### Postdoctoral fellows

Please email me a copy of your CV along with a summary of your research interests and most relevant research projects.

### Graduate students

Graduate students must be admitted through existing MIT programs (BE, CSB, EECS, HST MEMP, etc.). For incoming graduate students, please email me to set up a time to discuss potential rotations in the lab.

### Undergraduates

Please email me or apply to relevant UROP activities.

### Research assistants

We are not actively recruiting at this position currently, but please reach out if you have strong interest.

### Lab manager

We are not actively recruiting at this position currently, but please reach out if you have strong interest.

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/ragon.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/ragon_outdoor_joinus.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
