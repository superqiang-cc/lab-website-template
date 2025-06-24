---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team includes members from diverse educational and cultural backgrounds. If you are interested in joining us as a Master’s student, Ph.D. student, or postdoctoral researcher, please visit the “JOIN US” page for more information.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}
