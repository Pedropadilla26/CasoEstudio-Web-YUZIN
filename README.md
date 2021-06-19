# Caso de estudio de Yuzin
Caso de estudio de la web Yuzin (https://yuzin.com/) realizado por Pedro Padilla Reyes para el trabajo final de la asignatura Diseño de Interfaces de Usuario, parte de la rama de Ingeniería del Software en el grado de Ingeniería Informática en la Universidad de Granada.

# Persona y journey map
Realizaré una posible experiencia de usuario de una persona imaginaria para ver los posibles problemas que tenga la web.
He elegido a una versión editada de una de las personas que tenía en prácticas, busca realizar un viaje con su familia en el que quiere hacer distintas actividades y usará la web para buscarlas, esta es su ficha personal:
![imagen](https://user-images.githubusercontent.com/79611016/122656254-0c161380-d159-11eb-81bc-678deb626919.png)

Una descripción del journey map, que nos muesstra su posible experiencia con la web, sería: quiere ver eventos y actividades culturales en la web, probablemente para viajar a Sevilla, se da cuenta de que la web está un poco desordenada pero hay un buscador de qué quieres ver en la pantalla de inicio, intenta buscar eventos en julio en Sevilla, entonces ve que no hay ninguno, busca en agosto y no hay ninguno, cada vez que busca se le reinician y se agobia, y prueba a buscar con todos los eventos y todas las fechas en Sevilla y tampoco hay. Intenta descargarse la revista pero no funciona para Sevilla, le lleva a una de hace mas de medio año.  Prueba a pinchar en espacios culturales y ahí aparecen sitios pero no eventos, entonces pincha en agenda cultural y ahí aparecen eventos. 
Hace click en un evento, aunque sea en Granada está harta y le da igual, ve que aparecen dos precios diferentes y no sabe por qué y encima dice que hay que contactar por whatsapp una vez reservada. Se cansa y cierra la web, buscará de otra manera actvidades en su viaje.

Está claro que hemos detectado problemas de la web con este journey map que mencionaremos en el análisis de usabilidad.

# Ausencia de landing page
He visto que, aparte de los demás problemas detectados obviamente en el apartado anterior, la página inicial tiene una sobrecarga de información y es visualmente muy poco atractiva en cuanto a saber donde están las cosas, aunque está muy bien el buscador, pero especialmente para los usuarios poco experimentados en tecnología puede resultar dificil. Por eso he hecho una propuesta de, no una landing page en sí pero sí una página inicial que creo que, siguiendo el diseño de la web y con pocos cambios, mejora esa primera impresión:
![imagen](https://user-images.githubusercontent.com/79611016/122657531-8f893200-d164-11eb-9a9b-c5f6a4d74e11.png)

# Análisis de accesibilidad
Haré varias pruebas de accesibilidad en la web, dependiendo de distintas posibles necesidades.

Persona sin visión: necesita un modelo text-to-speech, no hay en la web.

Persona con poca visión: necesita acercar la web para ver más grande el texto, no es posible acercarlo sin destrozar la visión de la web.

Persona con dislexia: no ve bien la web, hay palabras que cree que está equivocándose pero resulta que tienen faltas en la propia web.

Persona con problemas de movilidad: aunque tiene dificultad para moverse por toda la WWW, esta web no supone un problema especial.

En la pantalla principal hay un banner que va cambiando, y uno de los mensajes al pasar por encima tiene demasiado poco contraste, casi no se ve.

Opciones de accesibilidad: no disponibles.

Opciones de ayuda y contacto: sí están disponibles y a la vista.

Pruebas con [WAVE](https://wave.webaim.org/): 
- Vemos que hay 22 errores de contraste
- 5 errores de etiquetas, texto alternativo y un botón vacío
- Varios textos redundantes, imágenes sin descripción y botones sin etiquetas (este apartado es muy importante para la función de texto hablado para las personas ciegas, porque aunque usen una aplicación propia para eso no podrán leer la web)
- La estructura está ordenada
- No hay más idiomas

En general vemos que la accesibilidad no es algo que se haya tenido especialmente en cuenta a la hora de hacer el re-diseño web.

# Reporte y análisis de usabilidad
### Resumen
  
  He realizado un cuestionario SUS yo mismo y otra persona sobre la web, veremos la evaluación definitiva que recibe con ello,  más tarde expondré los problemas principales que veo que tiene la web en los criterios de usabilidad y la conclusión sobre la usabilidad.
  
### Metodología de cuestionario SUS

  Los participantes son el mismo estudiante que hace el análisis y otra persona, con la intención de darle algo más de objetividad aunque lo óptimo sería que fueran muchos más.
  Después de que los participantes sean informados de la encuesta y acepten realizarla, prueban la web haciendo clicks en más o menos todo lo que vean y entonces proceden a realizar la encuesta.
  La encuesta que se les manda para realizar anónimamente a continuación es una copia modificada de la proporcionada por los profesores, incluyendo una pregunta de estudios y un resumen de en qué consiste la encuesta.

  En ese momento el participante se dispone a realizar la encuesta, que consiste en algunas preguntas generales sobre el usuario y, posteriormente, 10 preguntas con afirmaciones sobre su sensación con respecto a la aplicación valorables de 1 a 5, las cuales son las preguntas normales de cuestionarios SUS, que aparecen más abajo en este documento.

  El cálculo de la puntuación SUS se ha obtenido mediante la tabla excel para calcular proporcionada por el [GitHub mgea/DIU21](https://github.com/mgea/DIU21).

### Usuarios de testeo para cuestionario SUS
| #id. usuario | Sexo/edad      | Ocupación   | Estudios | Experiencia internet | Plataforma                          | Prototipo elegido | SUS score |
|--------------|----------------|-------------|----------------------------------------------------------------|----------------------|-------------------------------------|-------------------|-----------|
|            1 | Hombre (16-30) | Estudiante  |          Bachillerato                | Intermedio           | Windows, Android          | Yuzin            |  (95)    |
|            2 | Mujer (45-60)  | Enfermera |           Universitarios                   | Intermedio             | Window, IOS, Tablet | Yuzin             | (47,5)|
  


### Resultado del cuestionario SUS
|    | PREGUNTAS                                                                                |  1 | 2 |
|----|------------------------------------------------------------------------------------------|:--:|:--:|
|  1 | Creo que me gustará visitar con frecuencia este website                                  | 1 |  4 |
|  2 | Encontré el website innecesariamente complejo                                            | 4 |  4 |
|  3 | Pensé que era fácil utilizar este website                                                | 4 |  4 |
|  4 | Creo que necesitaría del apoyo de un experto para recorrer el website                    | 1 |  1 |
|  5 | Encontré las funciones del website bastante bien integradas                              | 1 |  4 | 
|  6 | Pensé que había demasiada inconsistencia en el website                                   | 5 |  1 |
|  7 | Imagino que la mayoría de las personas aprenderían muy rápidamente a utilizar el website | 2 |  4 |
|  8 | Encontré el website muy grande al recorrerlo                                             | 2 |  4 |
|  9 | Me sentí muy confiado en el manejo del website                                           | 3 |  4 | 
| 10 | Necesito aprender muchas cosas antes de manejarse en el website                          | 2 |  4 |
|    |                                                             Valoración final (SUS Score) | 45 | 47.5 |

  Los resultados de los usuarios que han probado la web son bastante parecidos, y en general no son especialmente buenos, aunque el usuario 2 no probó toda la aplicación, ya que no usó el buscador de eventos ni la revista. 

### Criterios de usabilidad
1. Visibilidad estado: Wayfinding (dónde estoy, dónde puedo ir..): el buscador inicial hace que este apartado sea bastante positivo, sin embargo no sabes donde te llevará el menú ni a que apartado corresponden los artículos marcados por "opinión".
2. ¿Diseño responsivo? ¿Se adapta bien a distintas resoluciones y dispositivos móviles: se adapta bien a los tamaños y a móvil, pero no tiene versión específica móvil lo que hace que tarde mas en cargar
3. Opciones en menú principal (suficientes /excesivas)?: el problema que presenta la web en este apartado son opciones en el menú principal que no son suficientemente descriptivas por sí mismas, y no sabes donde te van a llevar.
4. Navegación por menú secundario (sencillo y legible?): no tiene desplegables, si asumimos que es el de debajo tiene un link a descargar revista que está bien, un número para contactar con whatsapp que se ilumina como botón pero no lleva a ningún lado, y el botón de acceder no tiene registro y no facilita el entendimiento del sistema de cuentas de la página.
5. ¿Tiene información de ayuda? estructura del sitemap, asistentes, cambio idioma, contacto..: tiene varios lugares de contacto, aunque uno de ellos es un número de teléfono lo que no proporciona confianza, si no una sensación de falta de cuidado de la empresa y la web. El resto de cosas no están.

6. ¿Se pueden descargar lasrevistas?: solo la de Granada, lo pone en pequeño y si intentas descargar las otras te lleva a antiguas, no hay historial de anteriores revistas.
7. ¿Puedes buscar eventos culturales?: sí, pero no aparecen casi y falta feedback.
8. ¿Se puede buscar información sobre un espacio cultural concreto y acceder a más información?: sí, tiene descripción, información de contacto y enlace a la página web.
9. ¿Es útil la barra de búsqueda y el selector de búsquedas?: Sí, funcionan sin problemas.

Es necesario destacar también que la página en general tiene problemas de formato: hay textos que se salen de sus contenedores y se esconden debajo de botones u otros sitios, no se sabe a que opinión pertenece cada foto de cada artículo ni a qué apartado pertenecen los artículos. Hay palabras mayúsculas que deberían estar en minúscula y viceversa, lo que da un aspecto descuidado al sitio.

La retroalimentación por las búsquedas fallidas y las revistas también causa frustración, y el sistema de sesiones es difícil de entender hasta que, dandole al apartado de asóciate ves que es de pago y por eso no hay registro. No queda claro donde tendría que ir un nuevo usuario desde el principio.

  
### Conclusiones de usabilidad

  Los resultados de los usuarios que han probado MeetUs son bastante consistentes y parecen divididos en dos grupos, reflejan que la aplicación es funcional y adecuada para varias edades, pero para algunos usuarios resulta demasiado grande al recorrerla y pensaban que iba a ser más fácil navegar por ella, tal vez debido a un gran número de páginas u opciones que pueden resultar contraproducentes al hacer el sitio complejo y agobiar al usuario.
  
  La valoración media es favorable y denota una usabilidad aceptable, pero hay que tener en cuenta esos problemas que denotan los resultados del cuestionario menos favorables que pueden ayudar a ver las posibles mejoras de la aplicación.

