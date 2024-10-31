---
title: Members
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Members

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}

## Alumni

Shanshan Zhang, PhD
 
Xiaoxiao Liu (bioinformatician)
 
Saixian Zhang (visiting graduate student)
 
Chen Weng, PhD
 
Jiajia Xi, PhD 
 
Konstantin Leskov, PhD
 
Liu Wang, PhD 
 
Zhou Fang, PhD 
 
Haiyan Li, PhD

{% include section.html %}

# Gallery

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
