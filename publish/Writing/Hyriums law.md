**

Cuando “Funciona” no es suficiente

Cuando trabajas con otras personas es necesario pensar cuando tu si codigo "funciona" y "es mantenible" o solo "funciona". Esta es la base de la Ley de Hyrum:

"Con un número suficiente de usuarios de una API, no importa lo que prometas en el contrato: todos los comportamientos observables de tu sistema serán dependientes para alguien."

  Está ley es similar a la entropía, aunque la entropía nunca disminuye, eso no significa que no debamos esforzarnos por ser eficientes. De la misma manera el codigo no escalable, se puede mitigar, pero sabemos que nunca se erradica por completo ,lo que no significa que no podamos planificar o intentar comprenderlo mejor. 

La Ley de Hyrum representa el conocimiento práctico de que, incluso con las mejores intenciones, ingenieros destacados y prácticas sólidas de revisión de código, no podemos asumir una adherencia perfecta a contratos o mejores prácticas publicadas. Por eso es necesario qué nuestro código sea flexible a los cambios y desligado de la mayor cantidad de dependencias.

Está ley también tiene una relación con las reglas SOLID las relaciones más sólidas qué encuentro son:  
  

- Responsabilidad Única (SRP - Single Responsibility Principle):
    

  

El SRP aboga por que una clase debe tener solo una razón para cambiar. Ambos se centran en la claridad y en minimizar las áreas de cambio potencial.

- Abierto/Cerrado (OCP - Open/Closed Principle):
    

La Ley de Hyrum aborda la dificultad en realizar cambios, enfatizando que incluso modificaciones inofensivas pueden tener impactos no previstos. El OCP sugiere que las clases deben ser abiertas para extensión pero cerradas para modificación, fomentando el diseño de software que pueda adaptarse sin modificar su código existente.

Obviamente todo esto es muy lindo, pero si vas a construir una aplicación de 0 no tiene mucho sentido qué pienses en mantenibilidad, son dos situaciones bastante diferentes. Por eso es esencial tener en cuenta cual es el objetivo de tu aplicación antes de hacer nada.
![[hyrum-s-law-1200x675 (1).jpg]]
**![[hyrum-s-law-1200x675 (1).jpg]]