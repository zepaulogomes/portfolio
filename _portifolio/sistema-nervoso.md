---
layout: archive
title: "Sistema Nervoso"
excerpt: "Um poderoso mini-computador"
header:
  image: /assets/images/sistema-nervoso/case-sistema-nervoso.jpg
  teaser: assets/images/sistema-nervoso/case-sistema-nervoso-th.jpg
sidebar:
  - title: "Papel"
    text: "Gerente de produto"
  - title: "Responsibilities"
    text: "Entregar novas versões, definir e acompanhar métricas de sucesso e indicadores-chave de desempenho, desenvolver materiais para os usuários, identificar problemas e ajudar a resolvê-los. Além disso, eu também fui responsável por alinhar as partes interessadas, como diertoria executiva, outras times de Tecnologia, Vendas, Operações, Sucesso do Cliente e Jurídico."
gallery:
  - url: /assets/images/sistema-nervoso/historico-02.png
    image_path: assets/images/sistema-nervoso/historico-02.png
    alt: "Posicionamento de câmeras"
  - url: /assets/images/sistema-nervoso/historico-03.png
    image_path: assets/images/sistema-nervoso/historico-03.png
    alt: "Infraestrutura utilizada"
  - url: /assets/images/sistema-nervoso/historico-04.png
    image_path: assets/images/sistema-nervoso/historico-04.png
    alt: "Infraestrutura utilizada"  
---

{{ site.data.ui-text[site.locale].sistema_nervoso_intro | default: "Lorem ipsum" }}

{% include gallery caption="Instalações antigas" %}

{{ site.data.ui-text[site.locale].sistema_nervoso_develpment | default: "Lorem ipsum" }}

{% capture fig_img %}
![Foo]({{ "/assets/images/sistema-nervoso/before-after.png" | relative_url }})
{% endcapture %}
<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Antes e depois</figcaption>
</figure>


{{ site.data.ui-text[site.locale].sistema_nervoso_results | default: "Lorem ipsum" }}

---
{{ site.data.ui-text[site.locale].sistema_nervoso_artifacts | default: "Lorem ipsum" }}