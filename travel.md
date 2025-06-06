---
layout: page
permalink: /travel/
feature_image: "/assets/hero.png"
---
<h4>
Travel:
</h4>

<h5>Quick access to the different parts of this page:</h5>
<div class="bullet-div" markdown="1">
* <a href="#getting_to">Getting to Gothenburg</a>
* <a href="#getting_around">Getting around in Gothenburg</a>
* <a href="#staying_in">Staying in Gothenburg</a>
</div>

<h5 id="getting_to">Getting to Gothenburg</h5>

<h6>By air</h6>
<b>Göteborg Landvetter Airport</b> is an international airport serving the Gothenburg region in Sweden. It is located 20 Km south-east of the city centre and you can travel directly from various destinations in Europa and the world. For general information, please click <a href="http://www.swedavia.com/landvetter/">here</a>.

<figure class="center">
<!-- <img src="/assets/swedavia.jpg" style="width: 35%; height:auto;"/> -->
<img src="/assets/swedavia.jpg"/>
</figure>

<h6>Airport transfer</h6>
It’s easy to get to and from the airport with the shuttle bus service <a href="http://www.flygbussarna.se/en">Flygbussarna</a> and the journey time is between 25 and 30 minutes. Buses leave from right outside the terminal building and the final stop is the main bus station <b>Nils Ericssonterminalen</b> in central Gothenburg. <a href="http://www.swedavia.com/landvetter/to-from/taxi/">Taxi</a> or rental cars are also available at the airport.

<figure class="center">
<img src="/assets/flygbuss.jpg" width="35%" height="auto"/>
</figure>

<h6>By train</h6>
<a href="https://www.sj.se/?a=b&gclsrc=aw.ds&gad_source=1&gclid=Cj0KCQiA_qG5BhDTARIsAA0UHSLT3O09pk3zQGWNacoG_vcDBOoYzAmhs_c6t1cJYn2R4cTVfrYWcOUaAvu7EALw_wcB">SJ</a>, <a href="http://www.vasttrafik.se/#!/en/">Västtrafik</a>, <a href="http://www.tagakeriet.se/">Tågab</a>, and  are running frequent services to and from the <b>Central Station in Gothenburg</b>, connecting the city with the Scandinavian capitals Stockholm, Oslo and Copenhagen. The journey times are just under 4 hours from Oslo, around 3 hours from Stockholm and 3,5 hours from Copenhagen. The trains from Denmark stop at Copenhagen international airport, making it a convenient option to fly there and catch the train to Gothenburg.

<figure class="center">
<img src="/assets/centralstation.jpg" width="35%" height="auto"/>
</figure>

<h6>By bus</h6>
The bus terminal <b>Nils Ericsson terminalen</b> is serviced by long distance and express bus companies like <a href="http://www.swebus.se/SwebusExpress_com/">Swebus</a>, <a href="https://www.bus4you.se">bus4you</a> (in Swedish). You can easily travel to Gothenburg from the major cities in Sweden and Scandinavia. The journey time is around 3,5 hours from Oslo, 6,5 hours from Stockholm, 3,5 hours from Malmö and 5 hours from Copenhagen.

<h6>By car</h6>
The meeting venue is at the <b>Conference Centre Wallenberg</b>, Medicinaregatan 20A in Gothenburg. The largest parking area is located between the tram stop ‘Medicinaregatan’ and the conference center. A smaller parking lot is available on the right side of the conference centre, next to the small cottages. Parking directly in front of the Wallenberg center is not allowed for visitors.
 
<h6 id="getting_around">Getting around in Gothenburg</h6>
<h6>Venue</h6>
The meeting venue is at the <b>Conference Centre Wallenberg</b>, Medicinaregatan 20A. The closest tram stop is called Medicinaregatan. The Gothenburg city public transportation system can be found <a href="http://reseplanerare.vasttrafik.se/bin/query.exe/en?L=vs_vasttrafik&HWAI=JS!ajax=yes!&">here</a>.

<div class="bullet-div" markdown="1">
* **From the Göteborg Landvetter airport to the Venue**  
Take the airport bus, Flygbussarna, in front of the arrivals terminal. The bus runs every 15-20 minutes, and it is only 20 minutes ride to the city centre. You can find the time tables and how to buy tickets <a href="http://www.flygbussarna.se/en">here</a>.  
Get off at Korsvägen stop and take tram number 6  with direction ‘Länsmansgården via Sahlgrenska’, tram number 8 with direction ‘Frölunda’ or tram 13 with direction ‘Sahlgrenska’. Get off at Medicinaregatan stop.
</div>

<div class="bullet-div" markdown="1">
* **From Nils Ericsson terminal (bus terminal) to the Venue**  
Take a tram number 6 or 7 or 13 from the bus terminal, Nils Ericsson terminal (Drottningtorget), to Medicinaregatan stop. 
</div>

<div class="bullet-div" markdown="1">
* **From city centre to the Venue**  
From stop valand tram number 7 and bus 753 will take you to Medicinaregatan.
</div>

<h6>Sightseeing in Gothenburg</h6>
Please, visit the <a href="http://www.goteborg.com/en/">Göteborg tourist information</a> page for the <a href="https://www.goteborg.com/en/guides/10-must-dos-in-gothenburg">10-must-dos</a> 

<h6 id="staying_in">Staying in Gothenburg</h6>
<h6>Hotels</h6>

Below you can find a selection of hotels available in Gothenburg for your stay.<br>
Please contact them directly regarding price and availability.

{% assign hotels = site.hotels[0].hotels %}

{% for hotel in hotels %}
<div class="bullet-div" markdown="1">
<a href="{{ hotel.webpage }}">
* **{{ hotel.name }}**<br>
**Address:** {{ hotel.address }} <a href="https://www.google.com/maps/search/?api=1&query={{hotel.address}}" target="_blank">(Google maps)</a><br>
<a href="{{ hotel.webpage }}" target="_blank">Webpage and information</a>
</div>
{% endfor %}
