---
title: Team
---

# <i class="fas fa-users"></i>Chantarachot Lab members

{% capture html %}
{% include team-list.html role="pi" %}
{% include team-list.html role="phd" %}
{% include team-list.html role="programmer" %}
{% endcapture %}

{% include centerer.html html=html %}
