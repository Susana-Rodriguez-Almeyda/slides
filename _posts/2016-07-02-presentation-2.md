---
title: Presentation 2
layout: post
permalink: /presentation-2/

slides:
 - title: Sensores
   slide-data: "Los sensores son dispositivos que detectan cambios en el entorno físico y generan una señal de respuesta que puede ser analógica o digital. Se utilizan en una amplia variedad de aplicaciones industriales, científicas y tecnológicas para medir diferentes variables como luz, temperatura, presión, proximidad, entre otras. <br> <br>"
   background: "#e74c3c"
     
 - title: Sensores Ópticos
   slide-data: "<br> 
               <strong>1.1.1 Tipos:</strong> Sensores de luz, cámaras, fotodiodos, fototransistores, infrarrojos <br> <br>
               <strong>1.1.2 Funcionamiento:</strong> Detectan cambios en la luz o utilizan la luz para medir propiedades físicas como la distancia, la presencia o la velocidad. <br> <br>
               <strong>1.1.3 Características:</strong> Alta precisión, sin contacto físico, rápidos, versátiles, aplicables en varias industrias. <br> <br>
               <strong>1.1.4 Modo de comunicación:</strong> Señales eléctricas o digitales que transportan la información captada. <br>"
   background: '#f1c40f'
   
 - title: Sensores de Temperatura
   slide-data: "<br> 
               <strong>1.2.1 Tipos:</strong> Termopares, termistores, sensores de resistencia (RTD), sensores infrarrojos. <br> <br>
               <strong>1.2.2 Funcionamiento:</strong> Miden la temperatura detectando cambios en la resistencia eléctrica, la emisión de radiación térmica, o la termoelectricidad. <br> <br>
               <strong>1.2.3 Características:</strong> Amplio rango de temperaturas, precisión variable según el tipo de sensor, adecuados para múltiples aplicaciones industriales y científicas. <br> <br>
               <strong>1.2.4 Modo de comunicación:</strong> Utilizan señales analógicas o digitales para transmitir lecturas. <br>"
   background: '#9b59b6'
   
 - title: Sensores de Presión
   slide-data: "<br> 
               <strong>1.3.1 Tipos:</strong> Piezorresistivos, capacitivos, piezoeléctricos, de resonancia. <br> <br>
               <strong>1.3.2 Funcionamiento:</strong> Detectan la presión física aplicada y la convierten en una señal eléctrica proporcional. <br> <br>
               <strong>1.3.3 Características:</strong> Alta precisión, disponibles para varios rangos de presión, resistentes y fiables para mediciones industriales. <br> <br>
               <strong>1.3.4 Modo de comunicación:</strong> Señales analógicas o digitales según el tipo de sensor y aplicación. <br>"
   background: '#3498db'
   
 - title: Sensores de Proximidad
   slide-data: "<br> 
               <strong>1.4.1 Tipos:</strong> Inductivos, capacitivos, ópticos, ultrasónicos. <br> <br>
               <strong>1.4.2 Funcionamiento:</strong> Detectan la presencia o cercanía de objetos sin contacto físico, utilizando diferentes principios como electromagnetismo o ultrasonido. <br> <br>
               <strong>1.4.3 Características:</strong> Sin contacto físico, resistentes, rápidos en la detección, duraderos en condiciones industriales. <br> <br>
               <strong>1.4.4 Modo de comunicación:</strong> Señales digitales, analógicas o inalámbricas según el sistema de uso. <br>"
   background: '#2ecc71'
   
 - title: Conclusión
   slide-data: "En conclusión, los sensores juegan un papel fundamental en la automatización y el control en la industria moderna. Su capacidad para medir con precisión y transmitir datos en tiempo real permite mejorar la eficiencia, seguridad y calidad en una amplia gama de procesos. El uso de sensores continuará expandiéndose con el avance de nuevas tecnologías. <br> <br>"
   background: '#1abc9c'

 - title: Gracias
   background: '#e67e22'
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
