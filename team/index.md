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
- **Dylan Plummer**, PhD
- **Wanying Xu**, PhD
- **Sisi Lai**, PhD
- **Anniya Gu**, PhD
- **Shanshan Zhang**, PhD
- **Xiaoxiao Liu**, Bioinformatician
- **Saixian Zhang**, Visiting Graduate Student
- **Chen Weng**, PhD
- **Jiajia Xi**, PhD
- **Konstantin Leskov**, PhD
- **Liu Wang**, PhD
- **Zhou Fang**, PhD
- **Haiyan Li**, PhD

{% include section.html %}

# Gallery

{% capture content %}

{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_h1.jpg" %}
{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_h2.jpg" %}
{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_h3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}


{% capture content %}

{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_h4.jpg" %}
{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_h5.jpg" %}
{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_h6.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}


{% capture content %}

{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_v1.jpg" %}
{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_v2.jpg" %}
{% include figure.html image="https://raw.githubusercontent.com/JinLabBioinfo/labwebsitedata/refs/heads/main/image_gallery/lab_v3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
