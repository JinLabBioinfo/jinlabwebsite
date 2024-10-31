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
  image="images/cwru1.jpeg"
  caption="Sunset at CWRU campus"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/cwru2.jpeg"
  caption="Sunrise on Biomedical Research Building"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

**For experimental (wet lab) inqueries, please visit [Li Lab](https://yanlilab.com) website.**

For website maintenance, please email [Jiachen Sun](mailto:jxs2269@case.edu).
