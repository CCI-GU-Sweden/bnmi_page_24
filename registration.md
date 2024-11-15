---
layout: page
#title: ""
#aside: true
permalink: /registration/
feature_image: /assets/hero.png
#feature_text: "BNMI University of Gothenburg, 2024"
prices:
  - category: Early bird
    items:
    - name: Academic
      price: 3000
    - name: Student (PhD)
      price: 1500
    - name: Non-Academic
      price: 4500
  - category: Regular
    items:
    - name: Academic
      price: 4000
    - name: Student (PhD)
      price: 2500
    - name: Non-Academic
      price: 5500
  # - category: Dinner
  #   items:
  #   - name: "dinner"
  #   - price: 350
    
       
dinner:
  name: Dinner
  price: 350
---


<h4>Registration:</h4>


All participants must register for the symposium. The deadline for early online registration is May 1st, 2025. While all attendees are encouraged to submit a scientific abstract upon registration, this is mandatory for PhD students and postdocs. Priority will be given to participants based in Nordic countries.

<h5>
Registration Fees</h5>


<div class="pricing-container">
  {% for category in page.prices %}
      <span class="word-text">
          {{ category.category }}
      </span>
      <div class="bullet-div">
          {% for item in category.items %}

            <div class="row">
              <div class="column">
                  {{ item.name }}
              </div>
              <div class="column">
                {{ item.price }}
              </div>
            </div>
          {% endfor %}
        </div>    
  {% endfor %}

  <br/>

  <div class="row">
    <div class="column">
        {{ page.dinner.name }}
    </div>
    <div class="column" style="flex: 43%;">
      {{ page.dinner.price }}
    </div>
  </div> 

</div> 
<br/>


Included in Delegate registration:  
<div class="bullet-div" markdown="1">
* Welcome Reception
* Access to all symposium 
* Company Workshops
* Lunches 
* Coffee-breaks
* Poster sessions
</div>  

Travel and accommodation arrangements are the responsibility of the individual delegate.

Registrations will open soon!
<!-- Registration for the symposium can be done through the website <b>[here](https://www.lyyti.fi/reg/BNMI_2025_Symposium_9129){:target="_blank"}</b> -->

All symposium communications, including program updates, speaker lists, abstracts, and reminders, will be shared via email and on this website. Please be sure to add the symposium to your calendar and check the website regularly for the latest information.
