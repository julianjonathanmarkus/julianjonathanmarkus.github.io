---
layout: archive
title: "Conference Papers and Presentations"
permalink: /conference-papers-presentations/
author_profile: true
---

{% include base_path %}

## Conference Papers (from Publications)
_Add `category: conferences` to relevant items in `_publications/` to show them here._

{% assign conf_pubs = site.publications | where: "category", "conferences" %}
{% if conf_pubs and conf_pubs.size > 0 %}
  {% for post in conf_pubs reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
<p><em>No conference papers listed yet.</em></p>
{% endif %}

---

## Presentations (Talks)
_Items from `_talks/` appear here._

{% if site.talks and site.talks.size > 0 %}
  {% for talk in site.talks reversed %}
    {% include archive-single.html post=talk %}
  {% endfor %}
{% else %}
<p><em>No talks added yet.</em></p>
{% endif %}
