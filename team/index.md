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

Shanshan Zhang, Ph.D.
 
Xiaoxiao Liu, Bioinformatician
 
Saixian Zhang, Visiting graduate student
 
Chen Weng, Ph.D.
 
Jiajia Xi, Ph.D. 
 
Konstantin Leskov, Ph.D.
 
Liu Wang, Ph.D. 
 
Zhou Fang, Ph.D. 
 
Haiyan Li, Ph.D.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
