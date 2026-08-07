# VivreCard Design Book

> Un proyecto personal que busca preservar un recuerdo a través de una pieza diseñada y construida por mí.

---

## Estado

En desarrollo

---

# 1. El origen

Todo comenzó cuando empezó a interesarme la electrónica. Me gusta mucho hacer circuitos con muchos componentes o que no usen Arduino, como circuitos lógicos. Me empezó a fascinar cómo los electrones podían hacer muchas cosas. Antes de pensar en crear una VivreCard, estaba aprendiendo a construir circuitos sencillos. Uno de los primeros proyectos que realmente me marcó fue una compuerta lógica XOR hecha con transistores sobre una placa perforada. La compuerta XOR es mi compuerta favorita desde que empecé a diseñar un sumador-restador con compuertas lógicas.

Antes de eso, todos mis circuitos los armaba en protoboard y, con el paso del tiempo, luego de mirar y sentir que lo había hecho bien, los desarmaba para hacer otros o simplemente los guardaba para siempre. Aquella placa, llena de agujeros donde se conectaban los componentes, representó mi primer acercamiento a la construcción de una PCB. Fue un proceso difícil; se me hizo complicado unir las cosas porque era mi primera vez, pero cuando la terminé miré por primera vez algo que ya no dependía de un protoboard y que, aunque lo tuviera guardado, sería un recuerdo que siempre iba a servir. Me llenó de alegría en ese momento.

Aunque era un circuito simple, para mí significaba algo mucho más grande: el poder crear dispositivos desde cero.

En ese momento todavía no sabía diseñar PCB. Incluso evitaba hacerlo porque parecía complicado y pensaba que los programas para diseñarlas eran costosos o difíciles de utilizar. Siempre que miraba un video y luego explicaban cómo hacerlo en una PCB, me lo saltaba porque sentía que era inútil. Sin embargo, tenía mucha curiosidad por conocer cómo se creaban esas placas. Me salían videos de PCBs muy bonitas y poco a poco me fue gustando cómo se veían. Fue entonces cuando descubrí Proteus.

---

## El descubrimiento de las PCBs

Proteus fue un punto importante en mi aprendizaje. Cuando lo descargué sentí que había avanzado mucho, no por las PCBs, sino porque ahora podía simular y ver antes de hacer. Al comenzar a simular circuitos, descubrí que también podía crear mis propias placas de circuito impreso. Esto despertó en mí una nueva etapa de curiosidad. Comencé a investigar, ver tutoriales y aprender poco a poco cómo funcionaba el diseño de PCB. Me enganché mucho y pasaba horas haciendo componentes, sacando medidas y todo.

Mi primer diseño fue justamente aquella compuerta XOR con transistores que había construido anteriormente. Como ya la había diseñado en protoboard y en una placa perforada, quise que el siguiente paso simbólico fuera una PCB, para sentir que estaba evolucionando. Decidí convertirla en una pequeña PCB con forma de llavero para no solo guardarla en una caja, ya que tenía hecha, y por eso le agregué serigrafía representativa mía, como mi flor, Orión y mi firma.

Algo que debo admitir es que técnicamente solo copié el circuito y acomodé todos los componentes para que se viera bien, ya que utilicé el ruteo automático porque todavía no sabía cómo rutear las conexiones. Aun así, sentí mucha satisfacción al ver mi primera PCB creada, con mi diseño y como yo quería.

Cuando la terminé por completo, sentí algo diferente: ya no era solamente un circuito funcionando, sino un objeto que yo había imaginado, diseñado y creado desde cero. Entonces comencé a ver muchas posibilidades e ideas sobre lo que podía hacer al tener una PCB. Empecé a imaginar muchas cosas, desde proyectos comunes como fuentes de voltaje, hasta dar un regalo usando la PCB como medio para mostrar lo nuevo que había aprendido.

---

## Nacimiento de la VivreCard

Desde hace tiempo tengo la costumbre de crear regalos hechos por mí. En diferentes momentos he realizado detalles como origamis para amigos o acuarelas para personas importantes. Los origamis los doy en fechas que creo importantes o en cumpleaños; las acuarelas, solo en cumpleaños. Me gusta dar regalos que me toman tiempo de hacer, porque mientras los hago estoy pensando en dicha persona y, sin lugar a duda, eso genera un gran valor sentimental para mí, porque no hay nada más valioso que decidir darle un espacio de mi tiempo a esa persona.

Siempre me ha gustado que un regalo tenga una parte de quien lo crea. Después de diseñar mi primera PCB surgió una pregunta: ¿Y si pudiera crear un regalo electrónico completamente personalizado? Así nació el primer concepto de la VivreCard. Tenía muchas ideas, pero tenía un diseño en mente y todavía no le daba identidad ni había creado el nombre.

---

## Primer diseño

La primera VivreCard fue creada pensando en mi mamá. Quería que fuera ella quien se llevara mi primer diseño, puesto que gracias a ella tengo todo y, técnicamente, gracias a ella pude conocer el mundo de la electrónica al entrar a una preparatoria que impartía dicha carrera.

En ese tiempo había visto muchos videos de proyectos electrónicos con corazones formados por LEDs parpadeantes y letras iluminadas. Se me hicieron muy bonitos, pero todos eran hechos a mano, con cables y soldadura, lo que no permitía que se vieran completamente bien o que fueran algo feos, así que tomé esa idea como inspiración.

El diseño inicial era mucho más sencillo que el actual. Consistía en una sola PCB alimentada mediante un puerto USB tipo C. No sabía cómo se iba a alimentar; una idea vaga era que solo se conectara a un cuadrito de cargador y se conectara directo a un enchufe, como la Alexa o un aromatizador. El principal desafío fue encontrar cómo alimentarla de forma adecuada.

La tarjeta tenía dos circuitos: uno para controlar los LEDs que formaban una letra y otro para controlar unos LEDs que realizaban un patrón definido. Ambos circuitos se encontraban en la misma PCB, lo que terminaba saturando la placa.

Aunque la idea era entregársela a mi mamá por su cumpleaños, todavía faltaba mucho tiempo para esa fecha. Mientras tanto, surgió la oportunidad de regalarle la primera versión a una persona cercana. Esa fue la primera VivreCard que regalé.

Después de ver varias formas, simplemente decidí hacer una base diseñada en 3D que sostenía la placa y permitía alimentarla. Iba a ser algo decorativo, pero me apresuré mucho haciéndolo y, por alguna que otra procrastinación, terminé haciendo algunas cosas apurado.

Aquí fue donde decidí darle el nombre de VivreCard, basándome en mi anime favorito, One Piece. En la historia, una Vivre Card es un papel especial creado a partir de una parte de una persona, que puede utilizarse para establecer un vínculo con ella. Una característica que me pareció muy simbólica es que, si la Vivre Card se aleja de su dueño, siempre tiende a señalar hacia él. Lo relacioné mucho con la idea que yo quería para este proyecto, especialmente por algunos acontecimientos de la historia de One Piece, y creí que era un buen nombre.

Aunque hoy considero que es muy diferente de lo que representa actualmente el proyecto, en ese momento era algo especial. Era mi primer intento de transformar la electrónica en un recuerdo personal.

Cuando terminé dicha VivreCard, pedí que fabricaran las PCBs en JLCPCB, y ahí fue donde me enganché por completo. Fueron las dos primeras PCBs que hice y, sin lugar a duda, sentirlas y tenerlas en mis manos se sintió muy bien. Nada se asemeja a la emoción que sentí cuando soldé todos los componentes de la VivreCard y le di voltaje: mirar que los LEDs hacían exactamente lo que yo pensaba y que iluminaban de forma hermosa me emocionó.

Pero todavía estaba lejos de ser un regalo perfecto. Tal vez nunca pueda hacer una PCB 100 % eficiente o perfecta sin cambiar completamente el diseño, pero después de regalarla me di cuenta de muchos inconvenientes que me hicieron pensar que todo lo que hice fue muy poco para lo que pude haber entregado con más tiempo. No me culpo; no tenía todo el tiempo libre y literalmente era la segunda PCB que hacía, pero decidí mejorarla completamente para darle una mejor versión a mi mamá y a mis demás amigos, algo más independiente.

---

## La evolución hacia dos placas

El cambio más importante llegó cuando descubrí un proyecto de reloj de arena electrónico construido con dos PCBs conectadas mediante headers macho y hembra. Me llamó mucho la atención; parecía algo increíble. Esa idea cambió por completo la dirección del proyecto, ya que me di cuenta de que separar la VivreCard en dos partes podía solucionar muchos de los problemas del diseño original.

Al dividirla, ya no necesitaba una base externa para sostenerla y podía convertirla en un objeto independiente. Así nació la idea de separar la VivreCard en dos piezas que, al unirse, formarían un solo recuerdo:

 - PCB A.
 - VivreCore (PCB B).

---

## Nacimiento de VivreCore

Con la división del proyecto comenzó una etapa mucho más avanzada. En un principio no sabía qué iba a poner en la segunda PCB. Se me hacía muy costoso hacer dos PCBs distintas para cada persona y no lo miré para nada eficiente. Entonces decidí poner el circuito de control de la inicial como algo que todas iban a tener, pero aún sobraba mucho espacio.

Ahí fue cuando descubrí las baterías LiPo, los módulos de carga, como el TP4056, y los elevadores de voltaje, al buscar nuevas formas de alimentar mis proyectos, ya que todas las ideas que tenía usaban un conector USB y dependían de un cargador. Esto permitió que la VivreCard dejara de depender de una conexión externa y pudiera funcionar por sí misma.

La VivreCore, como decidí llamar a esa PCB, se convirtió en el corazón del proyecto. Su función principal sería controlar la alimentación y generar los efectos electrónicos que dan vida a la tarjeta y, poco a poco, se fue transformando en algo que me representaba, al diseñarla y agregarle cosas que todos saben que me gustan o me representan.

Mientras que la PCB A representaría principalmente la parte visual y personalizada para la persona que recibe la VivreCard, la VivreCore representaría mi propia identidad dentro del proyecto.

---

## Diseño y construcción

Durante todo el desarrollo, cada parte de la VivreCore fue planeada y documentada en una libreta. No solo se diseñó el circuito, sino también la distribución física, las dimensiones, la posición de los componentes y la estética general.

Me gusta pensar que si en un futuro miro dicho diseño, podré decir que no solo puse los componentes o la serigrafía donde mejor se miraba, como antes lo hacía, sino que cada componente, cada pad o cada línea fue planeada en dicha posición y tamaño desde antes de que abriera un programa. Me hace sentir que tengo dominio completo de mi proyecto y que lo conozco perfectamente.

Cada dibujo fue realizado considerando medidas reales y probado mediante circuitos armados en protoboard antes de llevarlo al diseño digital. El proyecto comenzó en Proteus, pero durante su desarrollo decidí cambiar a KiCad para aprender a utilizar una nueva herramienta y mejorar mis habilidades de diseño electrónico.

Gracias a KiCad, aprendí a rutear las conexiones, por lo que ya no solo acomodé los componentes, sino que realicé todo el diseño por completo. Ahora, aunque todavía estoy aprendiendo cosas, puedo decir que el diseño en PCB que he realizado hasta ahora ha sido el más pensado, desarrollado y complejo que he hecho. No porque use muchas conexiones o demasiados componentes, sino porque he hecho lo posible para hacerlo lo mejor que se pueda.

---
