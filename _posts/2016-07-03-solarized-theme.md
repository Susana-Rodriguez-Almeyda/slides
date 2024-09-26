---
title: Solarized Theme
layout: post
permalink: /solarized/
theme: solarized
 
slides:
 - title: Actuadores
   slide-data: 
     "Un actuador es un dispositivo que convierte una señal de control en movimiento mecánico. Dependiendo de la fuente de energía, se clasifican en eléctricos, mecánicos e hidráulicos."

 - title: Actuadores Eléctricos
   slide-data: 
    " Los actuadores eléctricos convierten la energía eléctrica en movimiento mecánico. Son altamente precisos y controlables, aunque requieren electricidad. Se utilizan en aplicaciones que demandan control exacto y bajo nivel de ruido."

 - title: <h2>Actuadores Eléctricos</h2>
   slide-data: "<h4> <strong> Tipos </strong></h4>
     - Motores eléctricos (AC y DC)<br>
     - Actuadores lineales<br>
     - Solenoides 
   <h4> <br><strong>Funcionamiento </strong><br></h4>
     Los actuadores eléctricos convierten la energía eléctrica en movimiento mediante campos magnéticos o sistemas de engranajes.      Pueden generar movimiento rotativo o lineal."

 - title:  <h2>Actuadores Eléctricos</h2>
   slide-data: "
  <h4> <strong> Características</strong></h4>
     - Alta precisión y control<br>
     - Requieren una fuente de energía eléctrica<br>
     - Bajo nivel de ruido<br>
     - Capacidad de carga moderada<br>
     <br><h4> <strong>Modo de Comunicación </strong> </h4>
     Los actuadores eléctricos se controlan mediante señales analógicas o digitales, como 0-10V o 4-20mA. Se conectan a PLCs o sistemas de automatización."

 - title: Actuadores Mecánicos
   slide-data: 
     "Los actuadores mecánicos convierten la energía en movimiento mecánico utilizando engranajes, palancas o tornillos. Son altamente duraderos y se pueden controlar manual o automáticamente."

 - title: <h2>Actuadores Mecánicos</h2>
   slide-data: "
   <h4> <strong> Tipos </strong></h4>
     - Actuadores de leva y seguidor <br>
     - Actuadores de tornillo <br>
     - Actuadores de cremallera y piñón <br>
    <br> <h4> <strong> Funcionamiento </strong></h4>
      Usan engranajes, tornillos o levas para convertir el movimiento, logrando así un control preciso sobre el movimiento rotatorio o lineal."
      
 - title: <h2>Actuadores Mecánicos</h2>
   slide-data: "
   <h4> <strong>  Características </strong></h4>
     - Alta durabilidad <br>
     - No siempre requieren electricidad <br>
     - Mantenimiento regular en algunos casos <br>
     - Ofrecen control preciso del movimiento <br>
     <br><h4> <strong>  Modo de Comunicación </strong></h4>
     Los actuadores mecánicos pueden operar manualmente o estar conectados a sistemas automáticos mediante sensores o motores. También pueden depender de conexiones mecánicas entre dispositivos."

 - title: Actuadores Hidráulicos
   slide-data: 
     "Los actuadores hidráulicos convierten la presión del fluido en movimiento mecánico. Son ideales para aplicaciones de alta potencia donde se requieren fuerzas elevadas."

 - title: <h2>Actuadores Hidráulicos</h2>
   slide-data: "
   <h4> <strong> Tipos </strong></h4>
     - Cilindros hidráulicos (movimiento lineal)<br>
     - Motores hidráulicos (movimiento rotatorio)<br>
   <br><h4> <strong> Funcionamiento</strong></h4>
     Funcionan mediante la presión de un líquido, como el aceite, que actúa sobre un pistón dentro de un cilindro. Esto permite la generación de grandes fuerzas para mover cargas pesadas."

 - title: <h2>Actuadores Hidráulicos</h2>
   slide-data: "
   <h4> <strong> Características</strong></h4>
     - Alta potencia y capacidad de carga<br>
     - Precisión moderada<br>
     - Requiere mantenimiento regular<br>
     - Pueden trabajar en ambientes extremos<br>
   <br><h4> <strong>  Modo de Comunicación</strong></h4>
     Se controlan mediante válvulas y sensores que regulan la presión y el flujo del fluido. Pueden conectarse a sistemas de control como PLCs mediante señales analógicas o digitales."
  
    title: GRACIAS:)
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}">
  <h1>{{slide.title}}</h1>
  <p>{{ slide.slide-data }}</p>
</section>
                    
{% endfor %}
