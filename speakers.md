---
layout: page
#title: ""
permalink: /speakers/
#aside: true
feature_image: "/assets/hero.png"
feature_text: "BNMI University of Gothenburg, 2024"
---

<h2>
Speakers:
</h2>


{% assign keynote_speakers = site.speakers | where: "type", "keynote" %}
{% assign session_speakers = site.speakers | where: "type", "session" %}

<h4>
Keynote speakers
</h4>

{% for speakers in keynote_speakers %}
  {% for speaker in speakers.speakers %}
<b>{{ speaker.name | escape }}</b>,
{{ speaker.institute }},
<b>{{ speaker.country }}</b>:
  {% endfor %}
<div class="speaker-container">
  {{ speakers.title }}
</div>
{% endfor %}

<br/>
<h4>
Sessions:
</h4>

{% for speakers in session_speakers %}
  {%- for speaker in speakers.speakers -%}
<b>{{ speaker.name | escape }}</b>,
{{ speaker.institute }},
<b>{{ speaker.country }}</b><br/>
  {% endfor %}
<div class="speaker-container">
  {{ speakers.title }}
</div>
<br/><br/>
{% endfor %}





Spread the word:
{% include nav-share.html %}

