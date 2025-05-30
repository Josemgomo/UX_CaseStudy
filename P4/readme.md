# DIU - Practica 4, entregables

>>> Se publicará la [Asignacion_ABtesting](https://github.com/mgea/DIU/blob/master/P4/Asignacion_ABtesting.pdf)
>>> Se publicará la lista de grupos y los respectivos GitHub

- Users. Elección y características de los usuarios reclutados
- Diseño de las pruebas
- Realización del Cuestionario SUS para usuarios y casos A y B.
- Tabla A/B Testing con resultados para A y B
- Eye Tracking para B
- Usability Report del Caso B, con toda la información recabada del caso B

Se dispone del Template de usability.gob (https://www.usability.gov/how-to-and-tools/resources/templates/report-template-usability-test.html) 
- Conclusiones

>>>> Este fichero se debe editar para que cada evidencia quede enlazada con el recurso subido a la carpeta de la practica. Se pide más detalle técnico en las descripciones de lo que sería el README principal del repositorio y que corresponde a la descripcion del Case Study.
>>>> Termine con la seccion de Conclusiones para aportar una valoración final del equipo sobre la propia realización de la práctica

# 1. Reclutamiento de usuarios 

El caso que tenemos que analizar es el proyecto [DIU3-Chapuzas](https://github.com/DIU3-Chapuzas/UX_CaseStudy). 
Se encargan de  mejorar la experiencia y aumentar la participación en los diferentes eventos y talleres sobre productos ecológicos y sostenibles.
Tabla y asignación de personas para las pruebas.

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| Usuario 1  | H / 22   | Estudiante  | Alta       | Introvertido | Móvil       | A 
| Usuario 2  | H / 42   | Taxista  | Alta       | Ambicioso       | Móvil        | A 
| Usuario 3  | M / 35   | Cajera     | Media        | Empática    | Móvil      | A
| Usuario 4  | H / 53   | Empresario  | Alta       | Seguro     | Móvil        | B 
| Usuario 5  | M / 18   | Estudiante     | Media        | Simpática    | Móvil      | B
| Usuario 6  | H / 67   | Jubilado  | Baja       | Extrovertido     | Móvil        | B 


# 2. Diseño de las pruebas 

Para evaluar la usabilidad y la experiencia de usuario tanto de nuestra aplicación como de la propuesta de "Re-Made in Granada", hemos diseñado un protocolo de pruebas que combina observación, cuestionarios específicos y el uso del estándar System Usability Scale (SUS).

En primer lugar solicitaremos a los usuarios que se registren en una actividad en el caso de ser la propuesta A y en el caso de la propuesta B que se registren en un taller para que sean acciones similares. Luego realizaremos una serie de preguntas para obtener una valoracion global de ambas propuestas.

En segundo lugar, se llevara a cabo una prueba de eye tracking únicamente sobre la propuesta "Re-Made in Granada", con el objetivo de analizar visualmente qué elementos captan más la atención del usuario y detectar posibles puntos de confusión o distracción en su diseño.

En tercer lugar, realizaremos un cuestionario SUS formado por diez preguntas para ambas propuestas, este apartado evalúa distintos aspectos del uso de la aplicación y una valoración general que permite obtener una calificacion cuantitativa. Las preguntas se valoraran en un rango desde 1 (no estoy nada de acuerdo) hasta 5 (estoy muy de acuerdo), lo que facilitará una comparación clara de las fortalezas y debilidades de cada propuesta.

# 3. Cuestionario SUS

Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante hemos usamos la calculadora que dejaremos en el siguiente enlace:[Calculadora SUS](https://stuart-cunningham.github.io/sus/). 

Para cada usuario de los que mencionamos en los apartados anteriores, le hemos formulado las mismas 10 preguntas a todos, y los resultados que hemos obtenido para cada uno de ellos ha sido:
- Usuario 1 (A1):
![image](https://github.com/Josemgomo/UX_CaseStudy/blob/master/P4/Puntuaciones_SUS/A_1.png)

- Usuario 2 (A2):
![image](https://github.com/Josemgomo/UX_CaseStudy/blob/master/P4/Puntuaciones_SUS/A_2.png)

- Usuario 3 (A3):
![image](https://github.com/Josemgomo/UX_CaseStudy/blob/master/P4/Puntuaciones_SUS/A_3.png)

- Usuario 4 (B1):
![image](https://github.com/Josemgomo/UX_CaseStudy/blob/master/P4/Puntuaciones_SUS/B_1.png)

- Usuario 5 (B2):
![image](https://github.com/Josemgomo/UX_CaseStudy/blob/master/P4/Puntuaciones_SUS/B_2.png)

- Usuario 6 (B3):
![image](https://github.com/Josemgomo/UX_CaseStudy/blob/master/P4/Puntuaciones_SUS/B_3.png)

En resumen, los resultados obtenidos (SUS SCORE) han sido:
- Para el prototipo A (SUPERLÓGICO):
 - Usuario 1 (A1): 72.5, C
 - Usuario 2 (A2): 85, B
 - Usuario 3 (A3): 52.5, F
 - Suma total: 210

- Para el prototipo B (Re-Chapuzeando Re-Made in Granada):
 - Usuario 4 (B1): 85, B
 - Usuario 5 (B2): 55, F
 - Usuario 6 (B1): 35, F
 - Suma total: 175

Como podemos observar, el prototipo A ha sido mejor que el prototipo B, con una diferencia de 35 puntos. El principal problema que han tenido los usuarios en el prototipo B, como podemos observar en las imágenes que muestran los resultados de los tests es que enceuntran el sistema un poco difícil de usar ya que venían con unas espectativas más altas en cuanto a su fácil manejo y se han encontrado con una realidad que es totalmente distinta.
