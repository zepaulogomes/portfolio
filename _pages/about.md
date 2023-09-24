---
permalink: /sobre/
title: "Sobre mim"
resume_pt: "/assets/documents/CV_Jose_Paulo_de_Mello_Gomes_pt_BR.pdf"
resume_en: "/assets/documents/CV_Jose_Paulo_de_Mello_Gomes_en_US.pdf"
---
{{ site.data.ui-text[site.locale].about_me_intro | default: "Lorem ipsum" }}
{{ site.data.ui-text[site.locale].about_me_education | default: "Lorem ipsum" }}
{{ site.data.ui-text[site.locale].about_me_work_experience | default: "Lorem ipsum" }}

## Arquivos

Para baixar o PDF, [clique aqui][1] para pt-BR ou [clique aqui][2] para en-US.

[1]:{{ site.url }}{{ page.resume_pt }}
[2]:{{ site.url }}{{ page.resume_en }}
