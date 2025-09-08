---
layout: archive
title: "Practice Work & Media Coverage"
permalink: /practice-work-and-media/
author_profile: true
---

{% include base_path %}

## Practice Work (Projects / Collaborations)
_You can also use the built-in `portfolio` collection in `_portfolio/`._

{% if site.portfolio and site.portfolio.size > 0 %}
  {% for item in site.portfolio reversed %}
    {% include archive-single.html post=item %}
  {% endfor %}
{% else %}
<p><em>No portfolio items yet. Add Markdown files to <code>_portfolio/</code>.</em></p>
{% endif %}

---

## Media Coverage
- _Outlet_ (Year). “Title.” <a href="https://example.com" target="_blank" rel="noopener">Link</a>
- _Podcast / Webinar_ (Year). “Title.” <a href="https://example.com" target="_blank" rel="noopener">Link</a>
