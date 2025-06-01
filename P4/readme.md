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

# 4. Eye Tracking

Para realizar el experimento hemos pedido al usuario que se intente inscribir en un taller para realizar un seguimiento y ver cuales son los puntos clave del diseño de la pagina.

![image](https://github.com/user-attachments/assets/6b264eec-7583-4bb7-a911-d3141a733b88)
![image](https://github.com/user-attachments/assets/5d12e84f-8e0b-46b2-9855-b1c9a49a3e46)
![image](https://github.com/user-attachments/assets/97a5de68-10d4-45f7-b47c-40aee0c2c67e)
![image](https://github.com/user-attachments/assets/7f0def79-791e-463b-8c21-dbebaf52c989)

Respecto a la herramienta hemos utilizado Gaze Recorder.

# 4. A/B Testing

Para realizar el A/B Testing no hemos basaado en los resultados del cuestionario SUS que som bastante utilies para realizar una comparativa.
Prototipo A:
Los usuarios que han evaluado la App 1 han mostrado una percepción generalmente positiva respecto a su uso. Coinciden en que se trata de un sistema que usarían con frecuencia y que resulta fácil de utilizar, aunque algunos han expresado ciertas dudas sobre aspectos como la complejidad o la consistencia del sistema. Por ejemplo, si bien las funciones están bien integradas según la mayoría, hay cierta sensación de que podría haber alguna inconsistencia en el diseño o en los flujos de interacción, lo cual puede generar momentos de duda.

En cuanto al aprendizaje, la mayoría considera que no sería necesario apoyo técnico para utilizar la app, lo cual indica una curva de aprendizaje razonablemente baja. Aun así, un usuario indicó que tal vez necesitaría ayuda, lo que podría señalar que la interfaz tiene áreas que no son del todo intuitivas para todos los perfiles.

Protoripo B:
Las opiniones de los usuarios son algo más variadas, con una mayor dispersión en las respuestas, lo que refleja una experiencia de usuario más desigual. Algunos usuarios han valorado muy positivamente la facilidad de uso y han señalado que no necesitaron ayuda externa para aprender a utilizar el sistema, lo que es un punto fuerte. También se destaca la impresión de que el sistema es funcional y podría ser adoptado rápidamente por otros usuarios.

Sin embargo, hay también señales claras de que la experiencia no ha sido completamente uniforme. Uno de los usuarios indicó que el sistema era inconsistente y que necesitaba aprender muchas cosas antes de poder usarlo correctamente. Además, la percepción de seguridad al usar el sistema fue un poco baja, lo cual puede influir negativamente en la confianza del usuario.

El prototipo resulta más robusto en cuanto a percepción de usabilidad global, mientras que el B tiene potencial, pero necesita ajustes para mejorar la coherencia y confianza de uso percibida por todos los perfiles de usuario.
