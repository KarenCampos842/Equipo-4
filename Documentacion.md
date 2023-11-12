# Documentación

## Unidad 2

> **Tema:** *Reflexiona sobre 3 habilidades técnicas asociadas a la fase de Requerimientos. Indica su importancia dentro del ciclo de Ingeniería de Requerimientos. Incluye argumentos de tu selección. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando.*

### Información

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
<td>Soleado</td>  
<td>Mayormente soleado</td>  
</tr> 
 <tr> 
  <td>19°C</td> 
   <td>17°C</td> 
  </tr>  
  <tr>  
  <td>E 13 km/h</td>  
  <td>E 11 km/h</td> 
  </tr>  
  </table>





|Historias de usuario  | Casos de uso |
|--|--|
|Se suelen elaborar antes de los casos de uso.  | Se suelen elaborar después de las historias de usuario. |
|Comunes en las metodologías ágiles.  | No se suelen ver en metodologías ágiles.|
|Propósito: Describir brevemente una característica del software desde la perspectiva, generalmente, del usuario o cliente.| Propósito: Describir la secuencia de interacciones entre el sistema y un agente externo (por ejemplo, el usuario final) para una funcionalidad específica. |
|Enfoque en encontrar la necesidad de una funcionalidad para el usuario (para qué).|Enfoque en describir detalladamente las interacciones software-agente externo para suplir una necesidad.|
|No contienen lenguaje técnico, son fáciles de leer, y comprensibles para personas fuera del proyecto. |Suelen contener lenguaje técnico y ser más complejas de leer.|
|Son breves.|Son más largos.|
|En general siguen la estructura:

<Usuario>**
Quiero **<algún objetivo>**
Para que **<motivo>** | En general se componen de un identificador único, un título que represente cual es el objetivo, las precondiciones ha satisfacer previo a iniciar, descripción breve del propósito del caso, una lista de pasos que muestren las interacciones entre los agentes externos y el sistema (happy flow), las postcondiciones (estado del sistema después de ejecutarse el caso de uso) y excepciones (unhappy flow). 


---
> **Tema:** *Selecciona un producto resultante de la etapa de diseño (Arquitectura, Base de Datos, Interfaz de Usuario, Procedimientos). Explica de forma clara y sintética algún método asociado al producto resultante. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando*

### Información

---

> **Tema:** *Investiga sobre un método o técnica que permita incluir pruebas de forma efectiva en el proceso de desarrollo. ¿A partir de qué etapa pueden ser consideradas las pruebas?. Proporciona un ejemplo basado en la experiencia del proyecto en equipo que están desarrollando*

### Información

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
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcyOTQ1MDc2Miw0ODU0Njg5MTIsLTE1Mj
g0ODkzMzgsMjAxNDAxMzU0MywxNjYxMDAxNjE2LC03Mjg4NzM1
NzksLTE1NDU0Mjc0ODMsODM4NDMyOTEyLC05Mzk1NTgzMDAsNz
EyMTAzNTkwLC05MzUwNDk5MDAsLTEwNjIyMTgxMDQsLTE0NTk5
NjYzNDIsNjQ2OTU5NjEzLDM0NzI5ODg1OSwxNjMxMjM3MTAxLD
c2NzA5OTM0MywtMjEzMjc4NTk1NiwtNjM0MjcyNzU0XX0=
-->