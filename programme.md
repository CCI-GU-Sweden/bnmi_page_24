---
layout: page
permalink: /programme/
feature_image: "/assets/hero.png"
---

<h4>
Programme:
</h4>
<br/>

<h5>
Schedule:
</h5>
<a href="/assets/schedule.jpg" target="_blank">
![image](/assets/schedule.jpg)
</a>
(Click image for larger version)
<h5>Sessions:</h5>

<br>
<div class="sessions-list">
  {% for session in site.sessions %}
    <div class="session-item">
      <b>{{ forloop.index}}. {{ session.title }}:</b>
      <div class="bullet-div">
      {{ session.content }}
      </div>
      <br/>
      <!-- Add more fields as needed -->
    </div>
  {% endfor %}
</div>

<h5>Workshops:</h5>

<br/>
In advance of BNMI 2025 Symposium, we are pleased to offer a series of hands-on <b>pre-Symposium workshops</b> on August 18 and 19. These sessions will cover cutting-edge topics, including:
<div class="bullet-div">
    <ul>
    <li> Correlative Array Tomography</li>
    <li> Smart Microscopy </li>
    <li> Optical Tissue Clearing Techniques for 3D Lightsheet Imaging </li>
    </ul>

</div>
These workshops offer a valuable opportunity for participants to gain hands-on experience with advanced imaging techniques before the main symposium. Join us to deepen your technical expertise and expand your research toolkit! The pre-symposium workshops are free for those who register and attend the main event. Due to limited space, we request a brief motivation letter and a short biosketch from each applicant. The pre-symposium workshops are free of charge; however, registration is required. Due to limited availability, we kindly ask each applicant to submit a brief motivation letter and a short biosketch.

 Check out the **[workshops]({{site.baseurl}}/workshops)** page for more information and registration.



