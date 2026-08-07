# VivreCard Design Book

> Un proyecto personal que busca preservar un recuerdo a través de una pieza diseñada y construida por mí.

---

## Estado

En desarrollo

---

# 1. Historia

## El origen

Todo comenzó cuando empezó a interesarme la electrónica. Antes de pensar en crear una VivreCard, estaba aprendiendo a construir circuitos sencillos. Uno de los primeros proyectos que realmente me marcó fue una compuerta lógica XOR hecha con transistores sobre una placa perforada.

Antes de eso, todos mis circuitos los armaba en protoboard. Aquella placa, llena de agujeros donde se conectaban los componentes, representó mi primer acercamiento a la construcción de una PCB. Aunque era un circuito simple, para mí significaba algo mucho más grande: el poder crear dispositivos desde cero.

En ese momento todavía no sabía diseñar PCB. Incluso evitaba hacerlo porque parecía complicado y pensaba que los programas para diseñarlas eran costosos o difíciles de utilizar. Sin embargo, tenía mucha curiosidad por conocer cómo se creaban esas placas. Fue entonces cuando descubrí a Proteus.

---

## El descubrimiento de las PCBs

Proteus fue un punto importante en mi aprendizaje. Al comenzar a simular circuitos, descubrí que también podía crear mis propias placas de circuito impreso. Esto despertó en mí una nueva etapa de curiosidad. Comencé a investigar, ver tutoriales y aprender poco a poco cómo funcionaba el diseño de PCB.

Mi primer diseño fue justamente aquella compuerta XOR con transistores que había construido anteriormente. Decidí convertirla en una pequeña PCB con forma de llavero. Aunque, en realidad, solo copié el circuito y acomodé todos los componentes para que se viera bien, ya que utilicé el ruteo automático porque todavía no sabía cómo rutear las conexiones.

Cuando la terminé por completo, sentí algo diferente: ya no era solamente un circuito funcionando, sino un objeto que yo había imaginado, diseñado y creado desde cero. Entonces comencé a ver muchas posibilidades e ideas sobre lo que podía hacer al tener una PCB.

---

## Nacimiento de la VivreCard

Desde hace tiempo tengo la costumbre de crear regalos hechos por mí. En diferentes momentos he realizado detalles como origamis para amigos o acuarelas para personas importantes. 

Siempre me ha gustado que un regalo tenga una parte de quien lo crea. Después de diseñar mi primera PCB surgió una pregunta: ¿Y si pudiera crear un regalo electrónico completamente personalizado? Así nació el primer concepto de la VivreCard.

---

## Primer diseño

La primera VivreCard fue creada pensando en mi mamá. En ese tiempo había visto muchos videos de proyectos electrónicos con corazones formados por LEDs parpadeantes y letras iluminadas, así que tomé esa idea como inspiración.

El diseño inicial era mucho más sencillo que el actual. Consistía en una sola PCB alimentada mediante un puerto USB tipo C, conectado a una base diseñada en 3D que sostenía la placa y permitía alimentarla. La tarjeta tenía dos circuitos: uno para controlar los LEDs que formaban una letra y otro para controlar unos LEDs que realizaban un patrón definido. Ambos circuitos se encontraban en la misma PCB.

Aunque la idea era entregársela a mi mamá por su cumpleaños, todavía faltaba tiempo para esa fecha. Mientras tanto, surgió la oportunidad de regalarle la primera versión a una persona cercana. Esa fue la primera VivreCard creada.

Aunque hoy considero que es muy diferente de lo que representa actualmente el proyecto, en ese momento era algo especial. Era mi primer intento de transformar la electrónica en un recuerdo personal. Cuando terminé dicha VivreCard, pedí que fabricaran las PCBs en JLCPCB, y ahí fue donde me enganché por completo. Fueron las dos primeras PCBs que hice y, sin lugar a duda, sentirlas y tenerlas en mis manos se sintió muy bien.

---

## La evolución hacia dos placas

El cambio más importante llegó cuando descubrí un proyecto de reloj de arena electrónico construido con dos PCBs conectadas mediante headers macho y hembra. Esa idea cambió por completo la dirección del proyecto, ya que me di cuenta de que separar la VivreCard en dos partes podía solucionar muchos de los problemas del diseño original.

Al dividirla, ya no necesitaba una base externa para sostenerla y podía convertirla en un objeto independiente. Así nació la idea de separar la VivreCard en dos piezas que, al unirse, formarían un solo recuerdo:
- PCB A.
- VivreCore (PCB B).

---

## Nacimiento de VivreCore

Con la división del proyecto comenzó una etapa mucho más avanzada. Descubrí las baterías LiPo, los módulos de carga, como el TP4056, y los elevadores de voltaje. Esto permitió que la VivreCard dejara de depender de una conexión externa y pudiera funcionar por sí misma.

La VivreCore se convirtió en el corazón del proyecto. Su función principal sería controlar la alimentación y generar los efectos electrónicos que dan vida a la tarjeta. Mientras que la PCB A representaría principalmente la parte visual y personalizada para la persona que recibe la VivreCard, la VivreCore representaría mi propia identidad dentro del proyecto.

---

## Diseño y construcción

Durante todo el desarrollo, cada parte de la VivreCard fue planeada y documentada en una libreta. No solo se diseñó el circuito, sino también la distribución física, las dimensiones, la posición de los componentes y la estética general.

Cada dibujo fue realizado considerando medidas reales y probado mediante circuitos armados en protoboard antes de llevarlo al diseño digital. El proyecto comenzó en Proteus, pero durante su desarrollo decidí cambiar a KiCad para aprender a utilizar una nueva herramienta y mejorar mis habilidades de diseño electrónico. Gracias a KiCad, aprendí a rutear las conexiones, por lo que ya no solo acomodé los componentes, sino que realicé todo el diseño por completo.

---
