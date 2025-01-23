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
    {% if speaker.weblink" %}
<a href="{{ speaker.weblink }}" target="blank">
    {% endif %}
<img src="{{ speaker.img }}" alt="{{ speaker.name }}" style="width: 200px; height: 70%">
    {% if speaker.weblink %}
</a>
    {% endif %}

<figcaption>{{ speaker.name }}</figcaption>
</figure>

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
    {% if speaker.weblink %}
<a href="{{ speaker.weblink }}" target="blank">
    {% endif %}
  <img src="{{ speaker.img }}" alt="{{ speaker.name }}" style="width: 200px; height: 70%">
   {% if speaker.weblink %}
</a>
    {% endif %}
  <figcaption>{{ speaker.name }}</figcaption>
</figure>

{% endfor %}
</div>

<br/><br/>
{% endfor %}


