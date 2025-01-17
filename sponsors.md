---
layout: page
permalink: /sponsors/
feature_image: "/assets/hero.png"

sponsors:
  - name: Zeiss
    logo: /assets/zeiss_scaled.png
    link: https://www.zeiss.com/microscopy
  - name: Bergman Labora
    logo: /assets/BergmanLabora.png
    link: https://www.bergmanlabora.se/
  - name: Nikon
    logo: /assets/Nikon.png
    link: https://www.microscope.healthcare.nikon.com/
  - name: Miltenyi Biotec
    logo: /assets/Logo_MiltenyiBiotec_RGB.png
    link: https://www.miltenyibiotec.com/DK-en/products/macs-imaging-and-spatial-biology.html?query=:relevance:allCategoriesOR:10000646
  - name: Abberior Instruments GmbH
    logo: /assets/abberior.png
    link: https://abberior.rocks/superresolution-and-confocal-systems/
  - name: Oxxius
    logo: /assets/Logo-oxxius.jpg
    link: https://www.oxxius.com
  - name: Evidente
    logo: /assets/Evident_Logo_Color_2023_Aug.jpg
    link: https://EvidentScientific.com

    

columns: 3
---
<h4>
Partners:
</h4>
<br>

<p>
We are deeply grateful to NordForsk and SciLifeLab for their generous support of the 4th Bridging Nordic Microscopy Infrastructure (BNMI) Symposium, taking place in Gothenburg, Sweden.
 
The BNMI 2025 symposium serves as a vital platform to unite Nordic imaging infrastructures and life scientists, fostering stronger collaborations across the region. These gatherings are designed to encourage meaningful interactions among Nordic imaging facilities, while building dynamic and interconnected networks in the field of life science imaging. Together, we are advancing innovation and collaboration in microscopy and imaging science.
</p>
<br>

<div class="image-container" style="width: 100%; height: auto; object-fit: scale-down;">
    <figure>
        <a href="https://www.nordforsk.org/">
          <img src="/assets/nordforsk.png" alt="Nordforsk">
        </a>
    </figure>
    <figure>
        <a href="https://www.scilifelab.se/">
          <img src="/assets/scilifelab.png" alt="scilifelab">
        </a>
    </figure>
</div>
<br>

<h4>
Sponsors:
</h4>
<br>

<p>
The BNMI 2025 Symposium presents an excellent opportunity for your company to showcase your products and innovations, particularly considering the ongoing advancements in imaging technologies and cutting-edge developments in microscopy instrumentation, sources, optics, detectors, and accessories. We warmly invite you to take full advantage of this unique gathering of influential professionals in the rapidly expanding field of imaging, allowing you to introduce and demonstrate your latest products and innovations to decision-makers in the industry. On the first day of the symposium, August 19th, a special session has been dedicated for exhibitors to deliver a brief presentation about their company and products.
</p>

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
      <a href="{{ logo.link }}" target="blank">
      <img src="{{ logo.logo }}" alt="{{ logo.name }}">
      </a>
    </div>
  {% endfor %}
</div>
