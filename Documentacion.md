# Documentación

## Unidad 2

> **Tema:** *Reflexiona sobre 3 habilidades técnicas asociadas a la fase de Requerimientos. Indica su importancia dentro del ciclo de Ingeniería de Requerimientos. Incluye argumentos de tu selección. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando.*

### Información

Los requisitos son una parte muy importante en el proceso de desarrollo de software porque son la base de los acuerdos entre los involucrados.

En un proyecto de desarrollo de software, la parte de la obtención de requisitos se ha convertido en toda una disciplina  que recibe el nombre de ingeniería de requerimientos, pues desempeñarse en ella implica de un amplio conocimiento y habilidades técnicas y sociales, pues gran parte de este proceso implica la interacción con muchas partes con conocimientos distintos en el área de las tecnologías de la información. Lo que demanda una capacidad para poder interpretar de la mejor manera la información.
Podemos destacar tres habilidades en la parte técnica que son indispensables para esta disciplina, las cuales son el análisis, 

Análisis: Antes de cualquier cosa se deben cimentar las bases del proyecto y es aquí donde la capacidad de extraer información, comprenderla y traducirla en  información técnica, son indispensables para el desarrollo del proyecto, pues el analista se enfrentara a diversos perfiles de clientes con necesidades distintas, y a partir de la información que ellos proporcionen se debe de hacer una evaluación de los alcances y restricciones que se implican.

Modelización: Adoptar un modelo de desarrollo no es una tarea fácil, pues esto implica tener un amplio conocimiento en gestión de proyectos ya habilidades distintas, para conseguir los mejores resultados es necesario que se adopten las técnicas y prácticas más adecuadas para el proyecto, pues de esta manera se garantizará la creación de un producto de calidad con un estructura adecuada, para ello es necesario aplicar técnicas como la estimación que requieren de habilidades matemáticas.

Desarrollo de Software: Es evidente que para poder dimensionar los desafíos y oportunidad es en el proceso de ingeniería de software es necesario tener un amplio conocimiento en tecnologías de la información poder realizar estimaciones basadas en fórmulas matemáticas y el expertiz del propio ingeniero, harán posible tener un mejor control sobre las implicaciones que tiene el proceso de desarrollo del software.

Además de lo antes mencionado, podemos ejemplificar en nuestro equipo de trabajo la primera habilidad que es el análisis, para definir los alcances y limitaciones de nuestro producto de software hemos hecho una amplia tarea de análisis basados en nuestra experiencia y la forma en la que traducir funciones prácticas de un software en especificaciones técnicas que luego usamos para la generación de requisitos, a pesar de no haber tenido una amplia formación en este aspecto, haciendo énfasis en el usuario final pudimos extraer esta información.

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
      <th>Historia de usuario #2</th>  
      <th>Registro de cliente</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>Usuario</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td> Poder registrarme en WorkFlash como cliente</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td> Encontrar trabajadores de forma rápida.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
           <li>Comprobar que se ha seleccionado el perfil "cliente".</li>
           <li>Comprobar que existen mínimo un nombre y un apellido.</li>
                 <li>Comprobar que existe texto antes y después de @ para el correo.</li>
                  <li>Comprobar que existe un elemento (imagen o PDF) como identificación oficial con fotografía.</li>
                  <li>Comprobar que existe un elemento (imagen) en el apartado de fotografía actual.</li>
                <li>Comprobar la aceptación de términos y condiciones.</li>
           <li>Comprobar el envío de contraseña al correo proporcionado.</li>
           </ul>
     </td> 
   </tr>
 </table>      


---

> **Tema:** *Selecciona un producto resultante de la etapa de diseño (Arquitectura, Base de Datos, Interfaz de Usuario, Procedimientos). Explica de forma clara y sintética algún método asociado al producto resultante. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando*

### Información

---

> **Tema:** *Investiga sobre un método o técnica que permita incluir pruebas de forma efectiva en el proceso de desarrollo. ¿A partir de qué etapa pueden ser consideradas las pruebas?. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando*

### Información

Las pruebas son una de las partes más importantes nos ayudan a reorganizarnos, reconocer errores y reducir los gastos. 

El inicio de las pruebas depende mucho del proyecto y la metodología usada. En las metodologías tradicionales las pruebas se hacen después de la etapa de desarrollo. 

Una buena forma de agregar pruebas es con un plan de pruebas el cual permite identificar las pruebas necesarias. 

No existe una forma específica de hacer un plan de pruebas, pero si varias plantillas y las partes más importantes son: 

-Objetivo, en esta parte se detalla la finalidad del documento dentro del proyecto 

-descripción del proyecto 

-Referencias, se refiere a los elementos que se van a poner a prueba y también los que no se pondrán a prueba incluyendo las razones de su exclusión. 

-estrategias, aquí s 

---
> **Tema:** *Utilizando fuentes confiables, establece las habilidades/conocimientos/competencias mínimas indispensables que un Ingeniero de Software debe incluir en su formación académica para el desarrollo de Aplicaciones de Software Seguras*

### Información

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
Surgió algo inesperado y uno de nuestros compañeros no pudo realizar todas sus actividades. Nos intentamos adaptar a la situación y reasignamos actividades. Lamentablemente, os desviamos mucho del plan y las fechas se extendieron, por lo que no terminamos todo a tiempo. 

**Solución:** 
Para el siguiente sprint programar las actividades de tal forma que se tengan algunos días de margen en caso de algún evento que retrase el trabajo. 

---
> **Tema:** *De las metodologías ágiles (Scrum, XP, Kanban, Design sprint, etc.), selecciona dos de ellas e identifica al menos tres de los principios de agilidad de software presentes en dichas metodologías. Explique también de qué manera pueden integrarse esos principios de agilidad en su proyecto de equipo, suponiendo que sigue una metodología ágil*

### Información

---
## Referencias

Chaves, M. A. (2005). _La ingeniería de requerimientos y su importancia en el desarrollo de proyectos de software_. Redalyc.org. https://www.redalyc.org/articulo.oa?id=66612870011
 
Arrizabalaga, I. (5 de octubre de 2021). _Problemas de Agile por los que esta metodología sigue fallando (y sus soluciones)._ axiateam. https://www.axiateam.com/problemas-de-agile-por-los-que-esta-metodologia-sigue-fallando-y-sus-soluciones/

Arthur Mauricio. (s.f). Casos de uso y Historias de usuario. _Ouracademy._ https://our-academy.org/posts/casos-de-uso-y-historias-de-usuario.

EBF. (11 de septiembre de 2019). _Ventajas y desventajas de las metodologías Agile (ágiles)._ EBF. https://ebf.com.es/blog/ventajas-y-desventajas-de-las-metodologias-agiles-y-su-aplicacion-en-el-tra

Gonzalez, F. (30 de septiembre de 2019). Casos de Uso: La alternativa a historia de usuario. _Somospnt_. https://somospnt.com/blog/104-casos-de-uso-una-alternativa-diferente#:~:text=Mientras%20que%20en%20una%20historia,y%20respuestas%20de%20nuestro%20sistema.

Laoyan, S. (26 de septiembre de 2022). _Cómo organizar tu stand up meeting o daily Scrum_. asana. [https://asana.com/es/resources/stand-up-meeting](https://asana.com/es/resources/stand-up-meeting)

Marco de Desarrollo de la Junta de Andalucía. (s. f). _Guía para la redacción de casos de uso. Junta de Andalucía._ https://www.juntadeandalucia.es/servicios/madeja/contenido/recurso/416

Oliveros, A. (2002). _Herramienta para implementar LEL y escenarios (TILS)_. http://sedici.unlp.edu.ar/handle/10915/4057

Scrum Manager®. (2018). _Historias de Usuario._ https://www.scrummanager.com/files/historias_usuario_scrum_manager.pdf

Scrum Mexico. (2 de agosto de 2018). _Escribiendo Historias de Usuario_. Scrum Mexico. https://scrum.mx/informate/historias-de-usuario
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA2NjkzMjM1OSwtMTA3MjM4NDYxNywtNj
MyMTk4OCwxOTc3NTYyNTk2LC0xNTQwNTMxMzMsOTUxNjA5Mjkx
LDYwMDIzMzYzMywtMTY5MTQxODg0MywtMTQ5Mjk5Mjk5OSw0OD
U0Njg5MTIsLTE1Mjg0ODkzMzgsMjAxNDAxMzU0MywxNjYxMDAx
NjE2LC03Mjg4NzM1NzksLTE1NDU0Mjc0ODMsODM4NDMyOTEyLC
05Mzk1NTgzMDAsNzEyMTAzNTkwLC05MzUwNDk5MDAsLTEwNjIy
MTgxMDRdfQ==
-->
