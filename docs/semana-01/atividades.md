---
layout: page
title: Atividades
parent: Semana 01
permalink: semana/01/atividades
nav_order: 2
---



# Atividades

A seguir você verá todas as aulas da semana 01.
{: .fs-6 .fw-300 }

---



{% assign prazo = "Novembro 1, 2020" | date: "%d/%m/%Y"  %}
{% assign hoje = "now" | date: "%d/%m/%Y"  %}

{% if prazo > hoje %}
## Atividade 01
{: .text-red-200 }
  Prazo encerrado
  {: .label .label-red }
{% elsif prazo < hoje %}
## Atividade 01
{: .text-green-200 }
  Entrega para {{prazo}}
  {: .label .label-green }
{% else %}
## Atividade 01
{: .text-yellow-200 }
   Entrega para Hoje
  {: .label .label-yellow }
{% endif %}


<div class="iframe-container" style="max-width: 680px; height: 680px;">
  <iframe src="https://drive.google.com/file/d/1HC3G6rcK2sVCHJmSC8H7xtIaJT77JvjH/preview" width= "100%"  height= "50%"></iframe>
</div>





