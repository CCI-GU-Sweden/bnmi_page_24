---
layout: page
#title: ""
permalink: /speakers/
#aside: true
feature_image: "/assets/hero.png"
---

<h4>
Speakers:
</h4>


{% assign keynote_speakers = site.speakers | where: "type", "keynote" %}
{% assign session_speakers = site.speakers | where: "type", "session" %}

<h5>
Keynote speakers
</h5>
<br>
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
<h5>
Sessions:  
</h5>
<br>
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


