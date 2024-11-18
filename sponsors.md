---
layout: page
permalink: /sponsors/
feature_image: "/assets/hero.png"

sponsors:
  - name: Zeiss
    logo: /assets/zeiss.png
    link: https://www.zeiss.com/microscopy
  - name: Bergman Labora
    logo: /assets/BergmanLabora.png
    link: https://www.bergmanlabora.se/
  - name: Nikon
    logo: /assets/Nikon.png
    link: https://www.microscope.healthcare.nikon.com/
  - name: Miltenyi Biotec
    logo: ""
    link: https://www.miltenyibiotec.com/DK-en/products/macs-imaging-and-spatial-biology.html?query=:relevance:allCategoriesOR:10000646

columns: 3
---

<h4>
Sponsors:
</h4>
<br>


The BNMI 2025 Symposium presents an excellent opportunity for your company to showcase your products and innovations, particularly considering the ongoing advancements in imaging technologies and cutting-edge developments in microscopy instrumentation, sources, optics, detectors, and accessories. We warmly invite you to take full advantage of this unique gathering of influential professionals in the rapidly expanding field of imaging, allowing you to introduce and demonstrate your latest products and innovations to decision-makers in the industry. On the first day of the symposium, August 19th, a special session has been dedicated for exhibitors to deliver a brief presentation about their company and products.


For detailed information on how to become a sponsor for BNMI 2025 and to explore the various sponsorship opportunities available, please download [this document.](/assets/BNMI2025_Sponsors_2025.pdf)

<br/>
<br/>
<br/>
<br/>

<h4>
A huge thanks to our sponsors:
</h4>
<br/>

<div class="logo-container">
  {% for logo in page.sponsors %}
    <div class="logo-item">
      <img src="{{ logo.logo }}" alt="{{ logo.name }}">
    </div>
  {% endfor %}
</div>



<!-- <ul class="logo-container">
{% for item in page.sponsors %}
    <li class="logo-item">
        <a href="{{ item.link }}">
        <img src="{{ item.logo }}" alt="{{item.name }}"/>
        </a>
    </li>
{% endfor %}
</ul> -->


<!-- <table class="image-table">
{% for item in page.sponsors %}
    {% assign mod = forloop.index0 | modulo: page.columns %}
    {% if mod == 0 or forloop.first %}
        <tr>
    {% endif %}
    <td class="image-cell">
        <!-- {{ item.name }} 
        <a href="{{ item.link }}">
        {% if item.logo == "" %}
            <h4>{{ item.name }}</h4>
        {% else %}
           <img src="{{ item.logo }}"/>
        {% endif %}
        </a>
    </td>
    {% assign modend = forloop.index | modulo: page.columns %}
    {% if modend == 0 or forloop.last %}
        </tr>
    {% endif %}
{% endfor %}
</table> -->
<!-- CARL ZEISS

MILTENYI BIOTEC -->
