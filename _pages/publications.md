---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my work on [Google Scholar]({{ site.author.googlescholar }}).

{% include base_path %}

## Peer-reviewed journal articles

{% for post in site.publications reversed %}
  {% if post.section == "peer-reviewed" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Submitted and working papers

{% for post in site.publications reversed %}
  {% if post.section == "submitted-working" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
