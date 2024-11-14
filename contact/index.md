---
title: Contact
nav:
  order: 4
  tooltip: Inquiries and opportunities
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please do not hesitate to contact us regarding open positions!

{%
  include button.html
  type="email"
  text="fxj45@case.edu"
  link="fxj45@case.edu"
%}
{%
  include button.html
  type="phone"
  text="(216) 368-1811"
  link="+1-216-368-1811"
%}
{%
  include button.html
  type="address"
  tooltip="Biomedical Research Building, Room 621, 2109 Adelbert Road, Cleveland, Ohio 44106-4955"
  link="https://maps.app.goo.gl/ckvQA2CJMUUAbAr66"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_contact/contact_v1.jpeg"
  caption="Sunrise on Biomedical Research Building"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_contact/contact_v2.jpeg"
  caption="Sunset at CWRU campus"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

For website maintenance, please email [Jiachen Sun](mailto:jxs2269@case.edu).
