## Cucharacha

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada



# 1 Datos 



**Titulo** : Cucharacha

**Web:**  [ (url github.io)](https://leogarru.itch.io/cucharacha)

**Autor:**  Leo Garzón Ruiz

**Resumen** : "Cucharacha" es un juego narrativo absurdo y divertido que también podría entrar sutilmente en la categoría detectivesca. La trama gira en torno a la muerte de un hombre llamado Felipe Lotas, ampliamente odiado en el pueblo por no ser demasiada buena persona. Su pareja, Lola Mento, se encuentra destrozada después de su muerte, no solo por la muerte en sí, sino sobretodo debido a que las antiguas parejas de Felipe decidieron robar pedazos de su cuerpo como venganza. Nuestro protagonista, el detective felino Don Gatún tendrá como misión hablar con estas ex parejas y hacerlas entrar en razón sobre la devolución del cuerpo.

**Estilo/género:**  Juego novela visual con minijuegos

**Logotipo** : 

![Logol](https://github.com/LeoGarru/Cucharacha/blob/master/Logo.png)

**Resolución:** 1350x890px tamaño fijo

**Probado en:**  Google Chrome, Firefox y Windows 10

**Tamaño proyecto:** 49,5 MB

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 28/05/2025

**Medios**:

- Github: LeoGarru
- Instagram: @leo.garru


# 2. Memoria del proyecto 

### 2.1 Storyboard: 
El diseño de los personajes fue un punto inicial determinante para el progreso del juego. Le quise dar importancia tanto a sus diseños como el cómo se verían en pantalla una vez se usara dialogic.

![Personajesl](https://github.com/LeoGarru/Cucharacha/blob/master/Personajes.PNG)

Por otro lado planteé cada uno de los minijuegos y el espacio donde se movería el personaje jugable.
![Storyboard](https://github.com/LeoGarru/Cucharacha/blob/master/Storyboard.PNG)




### 2.2. Esquema de navegación 


![Esquemal](https://github.com/LeoGarru/Cucharacha/blob/master/Esquema.png)







# 3. Metodología

Metodología de desarrollo de productos multimedia basado en una metodología de UX (User Experience)



### Etapa 1: Ideación de proyecto

**Investigación de campo** (propuestas inspiradoras para el proyecto)

- El videojuego Thank Goodness You're Here como mayor inspiración para la idea y la narrativa del juego.
- La serie Scott Pilgrim como inspiración para la trama.
- El videojuego Wii Party como inspiración para el mecanismo de los minijuegos.


**Motivación de la propuesta** 

Este  proyecto es interesante porque:
- Tiene una narrativa divertida ya que la historia contiene personajes con nombres y diálogos bastante absurdos.
- Es un juego que combina diálogos con minijuegos, por lo que nunca te aburres ni de leer ni de jugar.
- Tiene un ritmo basado en los mismos patrones, pero no deja de sorprender las nuevas vueltas de los personajes ni considerarás que tienen una plana personalidad.
- He gastado mucho tiempo en esforzarme en que el diseño se vea agradable y acogedor, por lo que considero que lo visual llama la atención del jugador.
- Está creado para aquellas personas que no sean demasiado jugadoras pero les llame la atención los videojuegos y quieran darle una pequeña oportunidad.



**Publico / audiencia**

Está orientado a un público que ronda de los 15 a los 30 años. Se hace mención a escenas sexuales no demasiado escandalosas.





### Etapa 2: Desarrollo / actividades realizadas

Diseño de guión, personajes, menú, etc: Antes de comenzar quería centrarme en la planificación y el diseño del proyecto. Para ello aboceté y escribí ideas distintas tanto de temática como de aspecto para mis personajes. Hice varios esquemas sobre la narración del juego y determiné que iba a crear 4 minijuegos sobre 4 exes del difunto. A cada uno de los personajes le asocié una personalidad peculiar y un aspecto exagerado y divertido que penaba que podía resultar interesante. Más tarde, escribí gran parte de los diálogos que tendría el juego y cerré todo lo relacionado a la historia. Para los dibujo utilicé la ténica de pintura digital cada uno de los personajes y según las necesidades que surgían en el momento añadía más dibujos.

Introducción y menú: Una vez desarrollada la historia que quería hacer y los personajes que lo iban a protagonizar me dispuse a crear una animación como método inicial de contar la historia detrás de la muerte del personaje. A pesar de ser un elemnto hecho fuera del programa Godot me ayudó a aprender el uso de los botones y me introdujo en el funcionamiento de las escenas. tras terminar con la intro todo este nuevo conocimiento me ayudó a agilizar el proceso de la creación del manú, con todos sus botones y redirecciones hacia una u otra escena.

Sistema de diálogo: Uno de los temás que me resultaron más complicados de abordar fueron los sistemas de diálogo. Finalmente di con dialogic, un sistema que me permitía ese formato de novela gráfica que a otros les faltaba. Utilizando Autoload conseguí crear una narrativa lineal con mis personajes y que la historia fluyera con soltura. Sobre los personajes me tomé el tiempo de añadirle al menos 4 expresiones a cada uno de ellos, entrando la expresión "normal", "feliz", "triste" y "enfadado".

Desarrollo de los minijuegos: Para los 4 minijuegos quería forzar toda la creatividad que mis escasos conocimientos de programación me permitiesen. Conseguí desarrollar juegos de con mecánicas distintas. Algunos eran juego de pulsar botones (unos que muestran imágenes y otros que activan animaciones), también juegos de arratrar elementos a cestas y juegos de apilar y verificar recetas de comida, siendo este último el más complicado de desarrollar. En cada uno de los minijuegos implementé una cuenta atrás con un "timer" que según ganaras o perdieses te dirijía a una escena u otra. Si ganabas tenías una conversación con el personaje que te había redirijido hacia su minijuego, si perdías volvías a intentarlo. En cualquier caso siempre era preciso ganar para continuar con el viaje. La programación ha sido un aspecto largo y desesperante en muchas ocasiones, pero también reconfortante al lograr que funcionase.Aunque he de admitir que me hubiese gustado dejarlo más estético visualmente añadiendole más animaciones, aunque debido a la falta de tiempo esto no se ha llegado a poder realizar.

Música y sonido: Finalmente, escogí diversas canciones que se adaptasen al ambiente de cada minijuego y de la escena principal, algunas siendo adaptaciones de canciones conocidas, factor que llegaría a cambiar en caso de monetizar mi trabajo en algún momento. Para la escena principal quise homenajear el juego Thank Goodness You're Here y le añadí uno de los temas que utilizan como música de fondo en su propio juego. Para los sonidos por otro lado he tenido una experiencia parecida al del aspecto visual, ya que tuve que recortar considerablemente los sonidos para ajustarme al tiempo de entrega.



### Etapa 3: Problemas identificados

Como ya he mencionado en el apartado anterior, me hubiese gustado disponer de más tiempo para trabajar en este proyecto. Conociendo que Godot es un programa tan complejo como es, resulta imposible adaptarse a todos sus mecanimos y técnicas y meno para trabajar con él con soltura, por lo que hacer un proyecto completo en unos cuantos meses es trabajoso y no quedan resultados perfectos. Para más ende muchos de los alumnos no contabamos con ningún conocimiendo de programación, así que ha sido un proyecto muy divertido pero tremendamente costoso de desarrollar. 

He querido hacer de mi trabajo un proyecto personal mucho más ambicioso de lo que me podía permitir, por lo que he tenido gran cantidad de problemas a lo largo de su desarrollo. Cualquier obstáculo requería mucho tiempo encima para encontrar una solución, y aunque muchos los he podido solucionar de alguna u otra manera, otros han quedado como soluciones forzadas para grandes problemas. Quitando este factor me parece que Godot para ser un programa tan grande es relativamente intuitivo para aquellos que entienden de la materia, y conforme más lo he ido usando más me he dado cuenta de ello. 

Otro extraño problema al que he tenido que hacer frente desde el primer momento fue el mero hecho de abrir el proyecto. Conforme má hacía más tardaba en abrirse y en modificar los elementos. En muchas ocasiones tenía que esperar durantes largos minutos a que el proyecto cargase cualquier cosa, se abriese o se guardase. Esto ha ha dificultado mucho mi ritmo de trabajo.
  




# 4. Conclusiones 

(explica brevemente tu valoración, problemas que has detectado y que te gustaría hacer o mejorar en el futuro )
Teniendo en cuenta que es la primera vez que creo un videojuego, creo que tiene unos mecanismos aceptables y una bonita estética. Además no considero que sea un juego aburrido ni pesado de jugar, que es el mayor problema en el que caen los creadores noveles, por lo que lo consideraría un pequeño éxito personal. Hace pocos meses no sabía nada del mundo del desarollo de videojuegos y ahora puedo orgullosamente decir que no solo he creado uno completto sino que también puedo llegar a entender conceptos básicos de su funcionamiento. Me ha alegrado mucho tocar este campo en la asignatura de Creación Multimedia interactiva, ya que era algo que pretendía aprender tarde o temprano y que siempre me ha llamado la atención desde la distancia. Los artistas de la era contemporanea tienen que saber un poco de todo para ganarse la vida, así que me ha parecido muy buena prática para mi yo del presente y mi yo del futuro.





# 5 Referencias 

-

**Recursos y materiales audiovisuales:**

* Música:  Le Festin - Ratatouille, RuPaul's drag race - Cover girl, Animal Crossing - 3 AM, Alan Jackson - Good time karaoke y Thank Goodness You're Here
* Sonidos: Pixabay
* Imágenes:  Dibujos míos
* Tipografía: Latte Machiatto, dafont.com

**Herramientas utilizadas**

- Godot 4.0
- Procreate
- YouCut

<p>Licencias: <a href="https://creativecommons.org/licenses/?lang=es" rel="nofollow">https://creativecommons.org/licenses/?lang=es</a></p>

Mayo 2025
