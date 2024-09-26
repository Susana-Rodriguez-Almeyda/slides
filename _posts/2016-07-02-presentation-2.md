---
title: Presentation 2
layout: post
permalink: /presentation-2/

slides:
 - title:  "Sensores <br> <br>"
   background: "#e74c3c"
     
 - title: "Ópticos <br> <br> "
   slide-data: " 1.1.1 Tipos: Sensores de luz, cámaras, fotodiodos, fototransistores, infrarrojos <br>
               1.1.2 Funcionamiento: Detectan cambios en la luz o usan la luz para medir propiedades físicas <br>
               1.1.3 Características: Alta precisión, sin contacto físico, rápidos, versátiles <br>
               1.1.4 Modo de comunicación: Señales eléctricas o digitales <br>"
   background: '#f1c40f'
   
 - title: Slide 3
   slide-data: "Temperatura <br> <br> 
               1.2.1 Tipos: Termopares, termistores, RTD, sensores infrarrojos <br>
               1.2.2 Funcionamiento: Miden cambios en propiedades como resistencia eléctrica o radiación térmica <br>
               1.2.3 Características: Amplio rango de temperaturas, precisión variable según el tipo de sensor <br>
               1.2.4 Modo de comunicación: Señales analógicas o digitales <br>"
   background: '#9b59b6'
   
 - title: Slide 4
   slide-data: "Presión <br> <br> 
               1.3.1 Tipos: Piezorresistivos, capacitivos, piezoeléctricos, de resonancia <br>
               1.3.2 Funcionamiento: Detectan la presión y la convierten en una señal eléctrica proporcional <br>
               1.3.3 Características: Alta precisión, adaptables para varios rangos de presión <br>
               1.3.4 Modo de comunicación: Señales analógicas o digitales <br>"
   background: '#3498db'
   
 - title: Slide 5
   slide-data: "Proximidad <br> <br> 
               1.4.1 Tipos: Inductivos, capacitivos, ópticos, ultrasónicos <br>
               1.4.2 Funcionamiento: Detectan objetos sin contacto físico usando ondas electromagnéticas o ultrasónicas <br>
               1.4.3 Características: Sin contacto, duraderos, rápidos en la detección <br>
               1.4.4 Modo de comunicación: Señales digitales, analógicas o inalámbricas <br>"
   background: '#2ecc71'
   
 - title: Slide 6
   slide-data: "Slide adicional <br> <br> 
               Agrega más contenido aquí si es necesario"
   background: '#1abc9c'

 - title: Slide 7
   slide-data: "Slide adicional <br> <br> 
               Agrega más contenido aquí si es necesario"
   background: '#e67e22'
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
