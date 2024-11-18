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
<div class="speaker-container">
  {{ speakers.title }}
</div>

  {% for speaker in speakers.speakers %}
<b>{{ speaker.name | escape }}</b>,
{{ speaker.institute }},
<b>{{ speaker.country }}</b>:
  {% endfor %}
{% endfor %}

<br/>
<h5>
Sessions:  
</h5>
<br>
{% for speakers in session_speakers %}
<div class="speaker-container">
  {{ speakers.title }}
</div>
  {%- for speaker in speakers.speakers -%}
<b>{{ speaker.name | escape }}</b>,
{{ speaker.institute }},
<b>{{ speaker.country }}</b><br/>
  {% endfor %}
<br/><br/>
{% endfor %}


