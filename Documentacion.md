# Documentación

## Unidad 2

> **Tema:** *Reflexiona sobre 3 habilidades técnicas asociadas a la fase de Requerimientos. Indica su importancia dentro del ciclo de Ingeniería de Requerimientos. Incluye argumentos de tu selección. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando.*

### Información

Los requisitos son una parte muy importante en el proceso de desarrollo de software porque son la base de los acuerdos entre los involucrados.

En un proyecto de desarrollo de software, la parte de la obtención de requisitos se ha convertido en toda una disciplina que recibe el nombre de Ingeniería de Requerimientos, desempeñarse en ella requiere de un amplio conocimiento y habilidades técnicas y sociales, pues gran parte de este proceso implica la interacción con personas que tienen conocimientos distintos en el área de las tecnologías de la información. Lo que demanda una alta capacidad para interpretar la información.

Podemos destacar tres habilidades en la parte técnica que son indispensables para esta disciplina, las cuales son: el análisis, la modelización y el desarrollo de Software. 

Análisis: Antes de cualquier cosa se deben cimentar las bases del proyecto y es aquí donde la capacidad de extraer información, comprenderla y traducirla en información técnica, son indispensables para el desarrollo del proyecto, pues el analista se enfrentará a diversos perfiles de clientes con necesidades distintas, y a partir de la información que ellos proporcionen se debe de hacer una evaluación de los alcances y restricciones que implica.

Modelización: Adoptar un modelo de desarrollo no es una tarea fácil, pues esto implica tener un amplio conocimiento en gestión de proyectos y habilidades distintas, para conseguir los mejores resultados es necesario que se adopten las técnicas y prácticas más adecuadas para el proyecto, pues de esta manera se garantizará la creación de un producto de calidad con un estructura adecuada, para ello es necesario aplicar técnicas como la estimación que requieren de ciertas habilidades matemáticas.

Desarrollo de Software: Es evidente que para poder dimensionar los desafíos y oportunidades en el proceso de Ingeniería de Requerimientos, es necesario tener un amplio conocimiento en tecnologías de la información, que permitan realizar estimaciones basadas en fórmulas matemáticas y el expertiz del propio profesional, todo esto hará posible tener un mejor control sobre las implicaciones que tiene el proceso de desarrollo del software.

Además de lo antes mencionado, podemos ejemplificar en nuestro equipo de trabajo la primera habilidad que es el análisis, para definir los alcances y limitaciones de nuestro producto de software hemos hecho una amplia tarea de análisis basado en nuestra experiencia y en la traducción de funciones prácticas de un software en especificaciones técnicas que luego usamos para la generación de requisitos, a pesar de no haber tenido una amplia formación en este aspecto, haciendo énfasis en el usuario final pudimos extraer lo que necesitabamos.

---


> **Tema:** *Explica de forma clara la diferencia entre Especificación de Casos de Uso vs Historias de Usuario. Adicionalmente indica en qué casos se recomiendan el uso de cada una de estas herramientas. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando*

### Información

Ambas herramientas son útiles para la extracción y organización de requerimientos por lo que a primera instancia podrían parecer iguales, aunque no es el caso. 

**Diferencias**
<table align=center> 
 <tr>  
 <th>Historias de usuario</th>  
 <th>Casos de uso</th>  
</tr>  
<tr>  
<td>Se suelen elaborar antes de los casos de uso. </td>  
<td>Se suelen elaborar después de las historias de usuario.</td>  
</tr> 
 <tr> 
  <td>Comunes en las metodologías ágiles. </td> 
   <td>No se suelen ver en metodologías ágiles.</td> 
  </tr>  
  <tr>  
  <td>Propósito: Describir brevemente una característica del software desde la perspectiva, generalmente, del usuario o cliente.</td>  
  <td>Propósito: Describir la secuencia de interacciones entre el sistema y un agente externo (por ejemplo, el usuario final) para una funcionalidad específica.</td> 
  </tr> 
  <tr> 
  <td>Enfoque en encontrar la necesidad de una funcionalidad para el usuario (para qué).</td> 
   <td>Enfoque en describir detalladamente las interacciones software-agente externo para suplir una necesidad.</td> 
  </tr>
  <tr> 
  <td>No contienen lenguaje técnico, son fáciles de leer, y comprensibles para personas fuera del proyecto. </td> 
   <td>Suelen contener lenguaje técnico y ser más complejas de leer.</td> 
  </tr>
   <tr> 
  <td>Son breves.</td> 
   <td>Son más largos.</td> 
  </tr> 
    <tr> 
  <td>
Suelen tener un id, un título que represente el objetivo, una descripción, criterios de aceptación, prioridad y estimación.
<br><br>Estructura usual de la descripción:
  <ul>
  <li> Como <b>Usuario</b></li>
  <li> Quiero <b>objetivo</b></li>
  <li> Para que <b>motivo</b></li>
   </ul>
  Existen historias de usuario que representan el happy flow y el unhappy flow. 
  </td> 
   <td>En general se componen de un identificador , un título el objetivo, las precondiciones ha satisfacer previo a iniciar, descripción breve del propósito del caso, una lista de pasos que muestren las interacciones entre los agentes externos y el sistema (happy flow), las postcondiciones (estado del sistema después de ejecutarse el caso de uso) y excepciones (unhappy flow).</td> 
  </tr>                 
  </table>

**Cuándo usarlos**

Historias de usuario

 - Durante la planificación: Las historias de usuario se realizan con base en los requerimientos y con ellas se puede dividir el trabajo a los diferentes miembros del equipo. 
 - Al elaborar el product backlog.
 - Durante reuniones con el cliente.
 - Cuando los requerimientos no son claros.

**Casos de uso**

 - Previo a realizar el diseño de interfaces y entrar en la fase de implementación. 
 - Como guía al realizar pruebas. 

Son posibles formas de usar éstas herramientas, aunque no es una regla. Habrá equipos que opten únicamente por utilizar historias de usuario, casos de uso o ambos. 
Generalmente, las historias de usuario al ser más breves, permiten iniciar antes el proyecto y refinarlas después. 

**Ejemplo**
Para nuestro proyecto elaboramos historias de usuario  para tener una idea general de lo que se buscaba lograr y cómo herramienta para la asignación de actividades. Posterior a las historias de usuario, realizamos casos de uso para ver a detalle las interacciones entre el software  y los agentes externos y así avanzar con algo más claro al diseño de interfaces. 

Ejemplo de historia de usuario: 

<table align=center>  
   <tr>  
      <th>Historia de usuario #3</th>  
      <th>Autenticación</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td> usuario de WorkFlash</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td> poder autenticarme en la aplicación</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td> acceder a los beneficios de WorkFlash.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el correo y contraseña introducidos existan en la base de datos.</li>
                  <li>Comprobar que la contraseña corresponda al correo introducido.</li>
                <li>Comprobar que el usuario ha aceptado compartir su ubicación con WorkFlash.</li>
           </ul>
     </td> 
   </tr>
 </table>      
 
<br>
Ejemplo de caso de uso

<br>

<table  align=center>
<tr>
<th>CU-06</th>
<th  colspan="2">Búsqueda y filtro </th></tr>
<tr>
<td><b>Versión</b></td>
<td  colspan="2">1.0 (29/10/2023)</td>
</tr>
<tr>
<td><b>Precondición</b></td>
<td  colspan="2">El cliente se ha registrado como cliente. </td>
</tr>
<tr>
<td><b>Descripción</b></td>
<td  colspan="2">El sistema mostrará al cliente una barra de búsqueda en la que podrá ingresar un oficio y filtrará las opciones con criterios de calificación y ubicació</td>
</tr>
<tr>
<td  rowspan="5"><b>Secuencia normal</b></td>
<td><b>Paso</b></td>
<td><b>Acción</b></td>
</tr>
<tr>
<td>1</td>
<td>El cliente ingresa el nombre de un oficio </td>
</tr>
<tr>
<td>2</td>
<td>El sistema despliega una lista de oficios </td>
</tr>
<tr>
<td>3</td>
<td>El cliente selecciona el trabajo que desea contratar</td>
</tr>
<tr>
<td>4</td>
<td>El sistema organiza los resultados de búsqueda y crea una <br> lista de trabajadores con algunos de sus datos</td>
</tr>
<tr>
<td><b>Postcondición</b></td>
<td  colspan="2">El usuario es libre de seleccionar con quien quiere trabajar </td>
</tr>
<tr>
<td  rowspan="3"><b>Excepciones</b></td>
<td><b>Paso</b></td>
<td><b>Acción</b></td>
</tr>
<tr>
<td> 1 </td>
<td>Si el oficio buscado no está dado de alta  en la base de datos, el sistema notifica al usuario que no encuentra el oficio buscado.</td>
</tr>
</table>

<br>
    
---

> **Tema:** *Selecciona un producto resultante de la etapa de diseño (Arquitectura, Base de Datos, Interfaz de Usuario, Procedimientos). Explica de forma clara y sintética algún método asociado al producto resultante. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando*

### Información

---

> **Tema:** *Investiga sobre un método o técnica que permita incluir pruebas de forma efectiva en el proceso de desarrollo. ¿A partir de qué etapa pueden ser consideradas las pruebas?. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando*

### Información

El inicio de las pruebas depende mucho del proyecto y la metodología usada. En las metodologías tradicionales las pruebas se hacen después de la etapa de desarrollo. 
existen 2 tipos de pruevas las dinamicas y las estaticas.
las pruebas dinamicas son las que se hacen mientras el codigo esta en ejecucion esta se realiza en una etapa mas avanzada del ciclo de vida  y las estaticas se centran en la prevencion de errores sometiendo a revicion la documentacion y los artefactos.
Las técnicas estáticas son técnicas que nos ayudan a la prevención de errores desde una etapa temprana del ciclo de vida por medio de las revisiones, reduciendo el tiempo y el coste del proyecto 

Existen varios tipos de revisiones entre ellas: 
La inspeccion o revisión técnica formal (RTF), esta es una actividad de control de calidad 	basada en examinar documentos de forma visual para detectar defectos. 

- El primer paso es seleccionar a los participantes, distribuir los roles, agendar la reunión o las reuniones y repartir los documentos a revisar. 

	Roles: 

	- Revisor: el encargado de detectar las anomalías. 

	- Escriba: registra por escrito los acontecimientos más importantes de la revisión e incorporar todos los defectos en una lista. 

	- Moderador: este es el responsable de la revisión y se encarga de mediar entre los diferentes puntos de vista. 

	- Autor: la persona responsable de crear el material revisado. 

- El siguiente paso es la lectura del material se realiza de manera individual, cada integrante del equipo analiza el material para comprenderlo y encontrar y anotar posibles defectos. 

- Lo siguiente es la reunión, donde el autor hace una introducción del material para después recorrer el material y que cada revisor comente sus observaciones.                                                   Al final de la reunión se deberá decidir si se acepta el material sin modificar o se rechaza y se manda a corrección, cuando se llegue a un acuerdo se firma el registro del escriba para 	indicar la 
  participación del miembro y confirmar el acuerdo. 

- El registro del escriba se agrega como parte del registro histórico del proyecto y también se agrega un reporte sobre las conclusiones de la reunión.

Esta no es la unica forma de hacer reviciones pero si la mas formal y recomendada en el caso de nuestro equipo usamos otra tecnica de revicion llamada revicion informal en la cual no se documenta el proceso y es  usada en las metodologias agiles, esta se basa en someter a revicion el matarial en una reunion con el autor y los demas integrantes del equipo para encontrar errores y coregirlos de forma rapida.
aunque debido a la falta de documentacion es dificil saber que tan efectivo es y es mas recomendable hacer reviciones formales.

---
> **Tema:** *Utilizando fuentes confiables, establece las habilidades/conocimientos/competencias mínimas indispensables que un Ingeniero de Software debe incluir en su formación académica para el desarrollo de Aplicaciones de Software Seguras*

### Información
Existen 2 tipos de habilidades esenciales: 

Las “soft skills” que en realidad son subjetivas por que no existe una clasificación para ellas, pero más que nada se refieren a las habilidades de sociales y de comunicación. 

soft skills importantes: 

- Trabajo en equipo 

- Adaptabilidad al cambio 

- pensamiento critico  

- resolución de problemas 

Las “hard skills” se refieren a habilidades técnicas basadas en la formación académica y experiencia profesional. 

 Algunas de las hard skills más importantes para un ingeniero en software  

- gestión de proyectos: garantiza que los proyectos se entreguen a tiempo. 

- conocimiento de arquitectura de software: habilidad de diseñar sistemas escalables y eficientes. 

- Análisis de datos: para mejorar procesos y la toma de decisiones. 

- conocimiento de lenguajes de programación 

También es necesario contar con conocimientos sobre el desarrollo de software seguro como conocer el marco de desarrollo seguro de software (SSDF). 

SSDF organiza las prácticas para el desarrollo seguro en 4: 

 - Preparar la organización.  

 - Proteger el software. 

 - Producir software bien protegido. 

 - Responder a las vulnerabilidades. 
 
---

## Unidad 3

> **Tema:** *Asumiendo que los valores descritos en el acuerdo del "Manifiesto para el desarrollo ágil de software", causan conflicto en el proceso de desarrollo reflexione y describa de manera clara posibles soluciones utilizando como base el proyecto que están desarrollando en equipo.*

### Información

**Valor:** *"Valoramos más a los individuos y su interacción que a los procesos y las herramientas."*

En metodologías ágiles, especialmente en Scrum, es común el realizar reuniones continuas en las que los individuos pueden interactuar y tratar disantos asuntos de forma rápida como actualizaciones o consultas. 

En teoría esto debería agilizar el proceso de desarrollo, no obstante, en ocasiones puede terminar siendo más un obstáculo que una ayuda, especialmente cuando recién se intenta implementar una metodología ágil. 

Uno de los problemas que tuvimos como equipo al realizar las reuniones (daily scrum), fue la falta de practicidad. En lugar de resumir, se extendía la participación y se quería solucionar los problemas en ese momento, lo que terminaba por alargar la reunión y por desperdiciar tiempo que pudo ser utilizado para avanzar en el proyecto. 

**Solución:** 

El scrum master debería preguntar directamente a cada integrante lo siguiente: 
-   ¿Qué lograste ayer?
-   ¿En qué trabajarás hoy?
-   ¿Hay algo que esté obstaculizando el trabajo que estás realizando?

Si la respuesta a la última pregunta es afirmativa, el scrum master debería preguntar a los miembros del equipo si alguien pudiera ayudar y pedir a ambos integrantes agendar una reunión para tratar el tema. De esta forma, el flujo de la reunión puede continuar y el obstáculo será tratado solo con los involucrados, ahorrando el tiempo de los demás integrantes y permitiéndoles continuar con el proyecto. 

Otro problema, fue el lograr que todos estuvieran en las reuniones diarias. Al principio, se había propuesto realizarlas en la mañana en horas libres o inmediatamente después de la última clase, sin embargo, se descartó porque el antiguo líder no asistía todos los días a la universidad. 
En aras de mantener la interacción entre los miembros del equipo, no establecimos un horario fijo para las reuniones y cambiábamos los horarios, siempre después de clase, para que todos pudieran estar, lo cuál no funcionó, porque siempre había alguno que no podía asistir. 

**Solución:** 
Establecer un horario fijo para las reuniones diarias. 
Posibles horarios: 
 - Después de clases (lunes: 11:40, martes: 11:10, miércoles: 9:10, jueves:  11:40). 
 - Durante horas libres (viernes: 9:40).

Todos excepto un integrante pueden asistir en éstos horarios. Como caso especial, el scrum master se reuniría únicamente con éste integrante en particular para mantenerlo actualizado, escuchar los posibles obstáculos que esté enfrentando y ayudarlo a buscar con el equipo una solución. 

Por otra parte, hubo ocasiones en las que se convocaba a todo el equipo cuando no era realmente necesario. Y se trataban asuntos que para algunos integrantes no eran necesarios para avanzar con sus asignaciones y solo se les hacía desperdiciar tiempo. 

**Solución:**
Solo convocar a los que requieran estar en la reunión para continuar trabajando. 

**Valor:** *"Valoramos el software que funciona, por encima de la documentación exhaustiva."*

Uno de los conflictos con este valor, es que, dado a que la documentación que tenemos no es tan detallada como se haría fuera de una metodología ágil, en ocasiones, distintos integrantes llegaban a presentar dudas respecto a cómo proceder en sus actividades y no lo externaban hasta tiempo después. 
Al inicio de cada sprint, durante una reunión se hablaba de lo que cada uno iba a realizar. Si bien se documentaba, no se escribía todo lo que se trataba durante la reunión, simplemente los puntos principales de cada actividad por realizar. Así que, al momento de iniciar con las actividades, si alguien olvidaba algo respecto a su actividad que no formaba parte de la documentación no avanzaba con su parte, o realizaba algo incompleto, de cualquier forma, el proceso de desarrollo se veía perjudicado. 

**Solución:**
Como líder, incentivar al equipo a externar sus dudas, comunicarse con otros integrantes y buscar apoyo. Así mismo, incentivarlos a tomar notas personales, ya sean escritas o grabadas para no olvidar lo acordado.  

**Valor:** *"Valoramos más la colaboración con el cliente que la negociación contractual."*

Para que exista una colaboración, el cliente debe acompañar al equipo durante el proceso, lo que implica que el cliente este disponible. 
En nuestro caso, no tenemos un cliente, pero el profesor Luis Basto es lo más cercano, puesto que es a quién le entregaremos el producto final y quien nos ofrece feedback durante las reuniones semanales y al final de cada sprint. 

Un reto que presentamos es pasar de un sprint a otro. Mientras no recibamos feedback por parte del cliente, caminamos a ciegas y avanzar se vuelve complicado. 

**Solución:** 
Verificar el trabajo realizado hasta el momento, analizar si independientemente del feedback se cambiará algo y hacerlo. Avanzar en aquello que no se vea afectado o gravemente afectado por el feedback del cliente. De esta forma, se evitará perder tiempo entre un sprint y otro. 

**Valor:** *"Valoramos más la respuesta al cambio que el seguimiento de un plan."*

Cuando algo inesperado sucede, la metodología ágil valora la adaptación por sobre el seguimiento de un plan. Desafortunadamente, esto puede causar que el equipo de desarrollo se desvíe demasiado del plan y las fechas se extiendan (es una posibilidad, no una certeza). 
En nuestro caso, sucedió algo similar con la última entrega.
Surgió algo inesperado y uno de nuestros compañeros no pudo realizar todas sus actividades. Nos intentamos adaptar a la situación y reasignamos actividades. Lamentablemente, nos desviamos mucho del plan y las fechas se extendieron, por lo que no terminamos todo a tiempo. 

**Solución:** 
Para el siguiente sprint programar las actividades de tal forma que se tengan algunos días de margen en caso de algún evento que retrase el trabajo. 

---
> **Tema:** *De las metodologías ágiles (Scrum, XP, Kanban, Design sprint, etc.), selecciona dos de ellas e identifica al menos tres de los principios de agilidad de software presentes en dichas metodologías. Explique también de qué manera pueden integrarse esos principios de agilidad en su proyecto de equipo, suponiendo que sigue una metodología ágil*

### Información


## Scrum  

Scrum es un marco de trabajo ágil utilizado en el desarrollo de software y en proyectos que requieren flexibilidad y adaptabilidad a los cambios.

  

**1. Roles:**

- Product Owner: Representa los intereses del cliente y define las funcionalidades del producto.

- Scrum Master: Facilita el proceso y elimina obstáculos para el equipo.

- Equipo de Desarrollo: Profesionales encargados de entregar el producto al final de cada iteración.

  

**2. Eventos:**

- Sprint: Período de tiempo (generalmente 2-4 semanas) durante el cual se realiza el trabajo y se entrega un incremento del producto.

- Reunión de Planificación del Sprint: Define qué se va a hacer durante el Sprint.

- Reunión Diaria: Breve encuentro diario para sincronizar actividades.

- Revisión del Sprint: Revisión del trabajo completado y adaptación del backlog del producto.

- Retrospectiva del Sprint: Reflexión sobre el rendimiento del equipo y mejora continua.

  

**3. Artefactos:**

- Product Backlog: Lista priorizada de funcionalidades pendientes.

- Sprint Backlog: Conjunto de elementos seleccionados para el Sprint.

- Incremento: Producto potencialmente entregable al final de cada Sprint.

  

**4. Principios:**

- Transparencia: La información clave está disponible para todos.

- Inspección: Se realizan inspecciones frecuentes para detectar variaciones.

- Adaptación: Se ajusta el proceso según sea necesario.

  

Scrum se basa en la iteración y la colaboración constante, permitiendo la entrega incremental y continua del producto, lo que lo hace especialmente efectivo en entornos en los que los requisitos pueden cambiar o evolucionar con el tiempo.

Estos principios pueden implementarse en nuestro proyecto de diferentes formas como:

-   Todos los requerimientos están disponibles para todo el equipo de trabajo y para el cliente, por lo que si un requerimiento es ambiguo o necesita ser modificado todos podrán estar enterados y opinar.
    
-   El código y los requerimientos podrán ser vistos por todos los integrantes del equipo de trabajo en el repositorio de Github.
    
-   Estaremos verificando los errores de forma frecuente entre todos y solo añadir al repositorio los trabajos en la aplicación que ya estén verificados con anterioridad.
    
-   Las ventanas tendrán que ser aprobadas por la mayoría del equipo de trabajo para poder ser implementadas.
    
-   Si alguna ventana o trabajo necesita ser reutilizada o necesita usar algún método distinto, será aceptado si influye en el correcto proceso de la aplicación.

## Kanban

Kanban es una metodología ágil que se originó en el ámbito de la fabricación y se ha adaptado con éxito al desarrollo de software y a diversos proyectos. A continuación, se describen los principios básicos de la metodología ágil Kanban:

**1. Visualización del Trabajo:**

- Los elementos de trabajo se representan visualmente en un tablero Kanban, divididos en columnas que representan diferentes etapas del proceso.

**2. Límites de Trabajo en Proceso (WIP):**

- Se establece un límite en la cantidad de elementos que pueden estar en curso en cada columna. Esto ayuda a evitar la sobrecarga y a mantener un flujo constante.

**3. Gestión del Flujo:**

- El énfasis está en mantener un flujo de trabajo continuo, evitando cuellos de botella y optimizando la eficiencia.

**4. Feedback Continuo:**

- Se fomenta el feedback constante para mejorar el proceso. La retroalimentación se utiliza para realizar ajustes y mejoras continuas.

**5. Priorización Basada en Valor:**

- Los elementos en el tablero Kanban se priorizan según su valor, y se trabaja en aquellos que tienen mayor prioridad.

**6. Flexibilidad y Adaptabilidad:**

- Kanban se adapta a cambios en los requisitos o prioridades de manera fluida. No hay iteraciones fijas (como en Scrum), lo que permite una mayor flexibilidad.

**7. Enfoque en la Eficiencia:**

- Kanban busca mejorar constantemente la eficiencia y la calidad del trabajo entregado.

8. Roles Flexibles:

- A diferencia de Scrum, Kanban no define roles específicos. Las responsabilidades pueden variar según las necesidades del equipo.  

Kanban es especialmente adecuado para equipos que trabajan en entornos con demanda variable y flujos de trabajo no predecibles. La visualización del trabajo y la limitación de WIP son características clave que ayudan a mantener un flujo constante y a identificar áreas de mejora. Cabe destacar que, si bien Kanban comparte principios ágiles, es diferente de Scrum en términos de roles, eventos y artefactos.

Estos principios pueden implementarse en nuestro proyecto de diferentes formas como:

-   Los elementos del trabajo podrán ser visualizados por todo el equipo en el repositorio de Github.
    
-   Cada tarea o issue tendrá una fecha límite, para que así todos los integrantes vayan a un ritmo constante y similar y poder ser eficaces.
    
-   Entre los del equipo podremos corregir algunos errores de otros integrantes y así conseguir un mejor proyecto y fomentando la retroalimentación y el aprendizaje continuo.
    
-   Tenemos una tabla para trabajar (Product backlog) según la prioridad de cada historia de usuario, y así enfocarnos primero en lo más importante.
    
-   Podremos cambiar los requisitos en cualquier instante ya que no contaremos con iteraciones fijas en la elaboración del proyecto.
    
-   Todos podremos trabajar en distintas áreas sin tener que tener roles específicos y así que cada integrante del equipo obtenga experiencia tanto para redactar, codificar, la elaboración de las ventanas, de testearlas, etc.

---
## Referencias

Arrizabalaga, I. (5 de octubre de 2021). _Problemas de Agile por los que esta metodología sigue fallando (y sus soluciones)._ axiateam. https://www.axiateam.com/problemas-de-agile-por-los-que-esta-metodologia-sigue-fallando-y-sus-soluciones/

Arthur Mauricio. (s.f). Casos de uso y Historias de usuario. _Ouracademy._ https://our-academy.org/posts/casos-de-uso-y-historias-de-usuario.

Cano, A., F.(2013)_Tecnicas estaticas.https://es.slideshare.net/juanestebanpuertacano/tcnicas-estticas

Chaves, M. A. (2005). _La ingeniería de requerimientos y su importancia en el desarrollo de proyectos de software_. Redalyc.org. https://www.redalyc.org/articulo.oa?id=66612870011

EBF. (11 de septiembre de 2019). _Ventajas y desventajas de las metodologías Agile (ágiles)._ EBF. https://ebf.com.es/blog/ventajas-y-desventajas-de-las-metodologias-agiles-y-su-aplicacion-en-el-tra

Gonzalez, F. (30 de septiembre de 2019). Casos de Uso: La alternativa a historia de usuario. _Somospnt_. https://somospnt.com/blog/104-casos-de-uso-una-alternativa-diferente#:~:text=Mientras%20que%20en%20una%20historia,y%20respuestas%20de%20nuestro%20sistema.

Laoyan, S. (26 de septiembre de 2022). _Cómo organizar tu stand up meeting o daily Scrum_. asana. [https://asana.com/es/resources/stand-up-meeting](https://asana.com/es/resources/stand-up-meeting)

Marco de Desarrollo de la Junta de Andalucía. (s. f). _Guía para la redacción de casos de uso. Junta de Andalucía._ https://www.juntadeandalucia.es/servicios/madeja/contenido/recurso/416

Oliveros, A. (2002). _Herramienta para implementar LEL y escenarios (TILS)_. http://sedici.unlp.edu.ar/handle/10915/4057

Sanchez J., M.(2015)._Pruebas de sofware. Fundamentos y técnicas. https://oa.upm.es/40012/1/PFC_JOSE_MANUEL_SANCHEZ_PENO_3.pdf

Scrum Manager®. (2018). _Historias de Usuario._ https://www.scrummanager.com/files/historias_usuario_scrum_manager.pdf

Scrum Mexico. (2 de agosto de 2018). _Escribiendo Historias de Usuario_. Scrum Mexico. https://scrum.mx/informate/historias-de-usuario

Yepply.(2023). ¿Cuáles son las Habilidades más demandadas de los Desarrolladores de Software? <br>https://www.linkedin.com/pulse/cu%C3%A1les-son-las-habilidades-m%C3%A1s-demandadas-de-los-desarrolladores-1e/?originalSubdomain=es 

Santander. (2021).Soft skills <br>https://www.santander.com/es/stories/soft-skills-el-concepto-que-revoluciona-los-perfiles-profesionales 

NIST.(2020).Mitigating the Risk of Software Vulnerabilities by Adopting a Secure Software Development Framework (SSDF)<br>https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.04232020.pdf 

   De Catalunya, U. O. (2012, 18 junio). Metodología Scrum. http://hdl.handle.net/10609/17885
    
 Martins, J. (2023, 19 junio). Scrum: conceptos clave y cómo se aplica en la gestión de proyectos [2023] • Asana. Asana. https://asana.com/es/resources/what-is-scrum
    
 Apd, R. (2022, 13 enero). Cómo aplicar la metodología Scrum y qué es el método Scrum. APD España. https://www.apd.es/metodologia-scrum-que-es/
    
Martins, J. (2022, 10 octubre). ¿Qué es la metodología Kanban y cómo funciona? [2022] • Asana. Asana. https://asana.com/es/resources/what-is-kanban
    
Gilibets, L. (2023, 12 enero). Qué es Kanban y cómo utilizarlo en el desarrollo de proyectos. Thinking for Innovation. https://www.iebschool.com/blog/metodologia-kanban-agile-scrum/
    
Apd, R. (2021, 24 junio). ¿En qué consiste la metodología Kanban y cómo utilizarla? APD España. https://www.apd.es/metodologia-kanban/
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTAyMjcxOTIyLDE0MTUwNTk2MjddfQ==
-->