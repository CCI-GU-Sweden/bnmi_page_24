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
  - name: Thermo Fisher
    logo: /assets/ThermoFisher.png
    link: https://thermofisher.com/volumeEM
  - name: Webknossos
    logo: /assets/webknossos.png
    link: https://webknossos.org
  - name: Micromedic
    logo: /assets/micromedic_logo.png
    link: https://micromedic.se
  - name: Hamamatsu
    logo: /assets/hamamatsu.png
    link: https://www.hamamatsu.com
  - name: Agendo Science
    logo: /assets/agendoscience.svg
    link: https://www.agendoscience.com/
  - name: Leica Systems
    logo: /assets/leica.jpg
    link: "https://www.leica-microsystems.com/c/em/apm/microscopy-solutions-industry/?nlc=20250312-SFDC-022809&utm_source=google&utm_medium=cpc&utm_campaign=25-EM-APM-L3-APPO-AAPM-SE-Google-Ads-Applied-First-Time-Brand-Search-EMEA&utm_content=text_ad&utm_term=leica-microsystems&gad_source=1&gad_campaignid=420819857"
  - name: Oxford Instruments
    logo: /assets/oxford.png
    link: https://andor.oxinst.com/
  
    
    

    

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
        <a href="https://www.nordforsk.org/" target="blank">
          <img src="/assets/nordforsk.png" alt="Nordforsk">
        </a>
    </figure>
    <figure>
        <a href="https://www.scilifelab.se/" target="blank">
          <img src="/assets/scilifelab.png" alt="scilifelab">
        </a>
    </figure>
</div>
<br>


<h4>
Media Partner:
</h4>
<br>

<p>
Microscopy and Analysis (M&A) is renowned for its authoritative scientific content, tailored for both users and developers of microscopy. We provide hands-on information about novel techniques and applications in Light Microscopy, Electron Microscopy, Scanning Probe Microscopy, Image Processing, and X-Ray Analysis. In addition to the latest news and updates from various societies, M&A also keeps you informed about upcoming meetings, conferences, and cutting-edge products for scientific research.
</p>
<br>


<figure class="center">
  <a href="https://analyticalscience.wiley.com/publication/microscopy-and-analysis" target="_blank">
    <img src="/assets/maem_logo.jpg" alt="Microscopy and Analysis" style="width:70%">
  </a>
</figure>
<br>
<p>
Methods in Microscopy (MiM) serves as your gateway to cutting-edge microscopic and nanoscopic techniques. In an era of rapid scientific advancement, our editorial team fully recognizes the importance of methodological innovation, which is often overlooked in research. Methods in Microscopy provides an Open-Access platform for the peer-reviewed publication of these methodologies. The mission is to make these techniques accessible to a broad audience, fostering understanding and accelerating scientific progress among experts and users alike. The journal publishes Research Articles, Review Articles, Letters, Tutorials, Editorials, News, and Views.
</p>
<br>


<figure class="center">
  <a href="https://www.degruyter.com/journal/key/mim/html" target="_blank">
    <img src="/assets/MiM-Logo_original.png" alt="methods in Microscopy" style="width:55%">
  </a>
</figure>
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
