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
<div class="speaker-container" style="text-align: left;">
  {{ speakers.title }}
</div>

<div class="image-container">
  {% for speaker in speakers.speakers %}
<figure>
<img src="{{ speaker.img }}" alt="{{ speaker.name }}" style="width: 200px; height: 70%">
<figcaption>{{ speaker.name }}</figcaption>
</figure>

<!-- <b>{{ speaker.name | escape }}</b>,
{{ speaker.institute }}, -->

<!-- <b>{{ speaker.country }}</b>: -->
{% endfor %}
</div>
{% endfor %}

<br/>
<h5>
Speakers
</h5>
<br>
{% for speakers in session_speakers %}
<div class="speaker-container">
  <b>{{ speakers.title }}</b>
</div>
<div class="image-container">
{% for speaker in speakers.speakers %}

<figure>
  <img src="{{ speaker.img }}" alt="{{ speaker.name }}" style="width: 200px; height: 70%">
  <figcaption>{{ speaker.name }}</figcaption>
</figure>

<!-- <b>{{ speaker.name | escape }}</b>,
{{ speaker.institute }},
<b>{{ speaker.country }}</b><br/> -->
{% endfor %}
</div>

<br/><br/>
{% endfor %}


