---
layout: page
#title: ""
permalink: /talks/
#aside: true
feature_image: "/assets/header-bio.jpg"
feature_text: "BNMI University of Gothenburg, 2024"
---


Abstracts:

{% for abstract in site.abstracts %}
  <h4>
    <a href="{{ abstract.content }}">
      {{ abstract.author }}
    </a>
  </h4>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}

Spread the word:
{% include nav-share.html %}

