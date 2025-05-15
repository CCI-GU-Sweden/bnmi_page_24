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
      eur: 300
    - name: Student (PhD)
      price: 1500
      eur: 150
    - name: Facility staff *
      price: 1850 
      eur: 185
    - name: Non-Academic
      price: 4500
      eur: 450
  - category: Regular
    items:
    - name: Academic
      price: 4000
      eur: 400
    - name: Student (PhD)
      price: 2500
      eur: 250
    - name: Facility staff *
      price: 2850 
      eur: 285
    - name: Non-Academic
      price: 5500
      eur: 550
  # - category: Dinner
  #   items:
  #   - name: "dinner"
  #   - price: 350
    
       
dinner:
  name: Dinner
  price: 350
  eur: 35
---


<h4>Registration:</h4>

<p>
All participants must register for the symposium. The deadline for early online registration is May 1st, 2025. While all attendees are encouraged to submit a scientific abstract upon registration, this is mandatory for PhD students and postdocs. Priority will be given to participants based in Nordic countries.
</p>

<h5>Important dates</h5>


<div class="bullet-div" markdown="1" style="padding-left: 15px;">
<br>
Online registration opening **15th November 2024**

Abstract submission opening **15th November 2024**

Exhibition registration deadline **15th April 2025**

Abstract submission deadline **25th May 2025**

Early online registration deadline **25th May 2025**

Notice of acceptation **25th May 2025**


</div>  

<h5>
Registration Fees</h5>

<br>
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
                SEK {{ item.price }} (or € {{ item.eur }})
              </div>
            </div>
          {% endfor %}
        </div>    
        <br>
  {% endfor %}

  <div class="row">
    <div class="column">
        {{ page.dinner.name }}
    </div>
    <div class="column" style="flex: 45%;">
    SEK {{ page.dinner.price }} (or € {{ page.dinner.eur }})
    </div>
  </div> 

</div> 
<br/>

<i>* With non-Managerial responsibilities</i>

<b>Note: PhD students and Postdocs</b> are eligible to apply for a fellowship to cover the symposium fee, as well as travel and accommodation expenses, up to a maximum of 5,000 Norwegian Kroner. To apply, applicants must provide proof of their PhD status, submit an abstract for a presentation (poster or oral), and include a motivation letter.<br/>
Applications should be sent to the following address: <b>bnmi-2025@ibv.uio.no</b>

Included in Delegate registration:  
<div class="bullet-div" markdown="1">
* Welcome Reception
* Access to all symposium 
* Company Presentations
* Lunches 
* Coffee-breaks
* Poster sessions
</div>  

Travel and accommodation arrangements are the responsibility of the individual delegate.

Registration for the symposium can be done through the website <b>[here]({{ site.symposium_registration_link }}){:target="_blank"}</b>

Please note that the pre-symposium workshops are not included in the registration fee for this symposium. Check out the **[workshops]({{site.baseurl}}/workshops)** page for more information about that.

All symposium communications, including program updates, speaker lists, abstracts, and reminders, will be shared via email and on this website. Please be sure to add the symposium to your calendar and check the website regularly for the latest information.
