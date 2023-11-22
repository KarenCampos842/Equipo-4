# Pruebas
## Pruebas informales[^1]
### Protocolo
Para las pruebas se reclutarán a 12 personas en total. 6 con el perfil de cliente y 6 con el perfil de trabajador. 

**Reclutamiento (presencial o mediante un mensaje de texto o llamada telefónica)** 

 1. Localizar a la persona que cumpla con el perfil: 

| Trabajador |  Cliente|
|--|--|
| x | x |


2. Presentarse como estudiantes de la Licenciatura en Ingeniería de Software (en caso de conocer al participante, es suficiente con un saludo). 
3. Solicitar la ayuda de la persona:
**Guion (ejemplo)**
Como parte de un proyecto en la universidad, junto a mi equipo, estoy realizando el diseño de una aplicación y requiero probar el prototipo, por lo que quisiera solicitar tu ayuda. 
La aplicación se llama Workflash, una aplicación para celular que pone en contacto a las personas registradas con trabajadores de distintos oficios y ocupaciones cercanos a su ubicación para solicitar su servicio. 
La prueba consiste en que el participante realice algunas actividades en la aplicación, responda algunas preguntas respecto a la dificultad de las actividades y conteste un cuestionario de satisfacción. Es una prueba de aproximadamente 15 minutos.
Los datos recabados serán utilizados con propósitos escolares. Nos servirán para saber lo que estamos haciendo bien y lo que podemos mejorar.
¿Puedo contar con tu participación?

4. Si acepta participar, se deberá agendar una cita para aplicar la prueba de forma presencial. De lo contrario, se buscará otra persona que cumpla el perfil. 

**Materiales** 

 - Formato 1 o 2 localizados al final del apartado de Protocolo (impreso o digital). 
 - Computadora con el prototipo de la aplicación abierto. 
 - Cronómetro o celular. 
 - Celular o computadora con el Cuestionario de satisfacción abierto: https://www.questionpro.com/a/SurveyPreview


Para aplicar la prueba realizar lo siguiente: 
1. Acudir a la cita con la persona. 
2. Salude a la persona y agradezca su participación. 
3. Solicitar los datos del participante y anotarlos en el formato 1 o 2: género, edad, ocupación (si se conocen los datos del participante llenar éste apartado previo a la aplicación de la prueba). 
4. Explicar brevemente en qué consistirá la prueba (la persona responsable de aplicar la prueba deberá proporcionar el prototipo a la persona). 
**Guion**
A continuación te presentaré el prototipo de la aplicación para celular llamada WorkFlash. 
Podrás interactuar con el prototipo y realizar actividades específicas que te indicaré en su momento. En la medida de lo posible, completa las actividades sin solicitar ayuda, en su lugar, intenta descubrir cómo utilizar la aplicación. 
5. Realizar una demostración con el log in (es importante mencionar que para interactuar con los campos para escribir, como la contraseña, es necesario realizar clic sobre el rectángulo hasta que aparezca el texto deseado, una contraseña en este ejemplo). 
6.  Proporcionar un escenario en el que se utilizará la aplicación: 
**Para el perfil de trabajador** 
El contexto es el siguiente: Imagina que tu nombre es Juan Campos Romero, eres mecánico y quieres usar WorkFlash para darte a conocer y atraer más clientes. 
7. Aplicar la prueba utilizando el formato 1 (trabajador) o el formato 2 (cliente). 
- Solicitar al participante realizar la primera tarea.
-  Activar el cronómetro (detener el cronómetro cuando el participante haya finalizado la tarea) y anotar el tiempo. En caso de que el participante no haya logrado completar la tarea, el tiempo se detendrá hasta que el participante externe no poder realizar la actividad. 
- Contar y anotar el número de errores que cometió el participante durante la tarea. Igualmente, anotar en el formato cual fue el error. 
- Marcar como Completada la tarea o No completada, según sea el caso. 
- Realizar la siguiente pregunta al participante y anotar la respuesta: Del 1 al 5, siendo 1 muy difícil y 5 muy fácil, ¿Qué calificación le otorga a ésta tarea?
- Repetir el proceso hasta terminar con las tareas. 
8.  Anotar comentarios/observaciones del participante sobre la aplicación (preguntar directamente si es necesario). 
9. Proporcionar el ***Cuestionario de satisfacción*** al participante para su resolución. 
10. Agradecer a la persona su participación y despedirse. 

***Nota:*** Al finalizar con la prueba, el formato que se haya utilizado (1 o 2), ya resuelto, deberá colocarse en el apartado <a href="https://github.com/KarenCampos842/Equipo-4/blob/Tercera-Entrega/Pruebas.md#aplicaci%C3%B3n-de-las-pruebas">Aplicación de las pruebas</a> 


### Pruebas
**Objetivos** 
1.  Los trabajadores pueden aceptar, rechazar y cancelar un trabajo/contrato.
2.  Los trabajadores pueden visualizar calificaciones y comentarios de clientes. 
3. Los trabajadores pueden comunicarse con sus clientes mediante un chat y eliminarlo si así desean.
4. Los trabajadores pueden calificar a sus clientes.
5. Los trabajadores pueden  editar su perfil y cancelar su membresía.
6. La aplicación es intuitiva y agradable para los usuarios.

**Correspondencia entre los objetivos, indicadores y  requisitos**

<table align=center>  
   <tr>  
      <th colspan=2>Objetivo 1</th>  
     </tr>
     <tr>  
      <th>Indicador</th>
      <th>Requisito</th>    
     </tr>
     <tr>  
      <td>Tarea 1 Completada</td>
      <td>
      <li>RF-1. Perfiles. </li>
      <li>RF-3. Registro del trabajador.</li>
      <li>RF-5. Creación de contraseña.</li>
      <li>RF-9. Creación del perfil de trabajador.</li>
      <li>RF-10. Inicio de sesión.</li>
      </td>    
     </tr>
     <tr>
     <td>Tarea 4 Completada</td>
      <td>
      <li>RF-15. Contratación del servicio.</li>
      </td>    
     </tr>
      <tr>
     <td>Tarea 7 Completada</td>
      <td>
      <li>RF-19. Cancelación del servicio.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 2</th>  
     </tr>
     <tr>  
      <td>Tarea 2 Completada</td>
      <td>
      <li>RF-9. Creación del perfil de trabajador. </li>
      </td>    
     </tr>
     <tr>  
      <th colspan=2>Objetivo 3</th>  
     </tr>
     <tr>  
      <td>Tarea 5 Completada</td>
      <td>
      <li>RF-14. Chat.</li>
      </td>    
     </tr>
      <tr>  
      <td>Tarea 7 Completada</td>
      <td>
      <li>RF-14. Chat.</li>
      </td>    
     </tr>
       <tr>  
      <th colspan=2>Objetivo 4</th>  
     </tr>
     <tr>  
      <td>Tarea 6 Completada</td>
      <td>
      <li>RF-16. Calificación del cliente.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 5</th>  
     </tr>
     <tr>  
      <td>Tarea 3 Completada</td>
      <td>
      <li>RF-22. Modificación de perfil.</li>
      </td>    
     </tr>
      <tr>  
      <td>Tarea 8 Completada</td>
      <td>
      <li>RF-20. Cancelación de la cuenta por parte del trabajador.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 6</th>  
     </tr>
     <tr>  
      <td>Máximo 1 error por tarea.</td>
      <td rowspan=4>
    RNF-27. El sistema debe ser intuitivo, gráfico y agradable para la mayoría de usuarios.
      </td>    
     </tr>
      <tr>  
      <td>Tareas 1 al 8 completadas en el tiempo esperado</td>
     </tr>
      <tr>  
      <td>Un promedio de máximo 2 para la pregunta:  Del 1 al 5, siendo 1 muy difícil y 5 muy fácil, ¿Qué calificación le otorga a ésta tarea?</td>
     </tr>
      <tr>  
      <td>Cuestionario de satisfacción
      <li></li>
      </td>
     </tr>
     
 </table>     

<br>
<br>

***Formato 1: Perfil de trabajador***

<table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Nombre</td>  
       <td colspan=2>d/m/a</td> 
   </tr> 
   <tr>  
      <th colspan=6>Datos del participante</td> 
   </tr> 
    <tr>  
      <th>Género</th>  
      <th>Edad</th>
      <th>Ocupación</th>     
      <th colspan=3>Tipo de usuario</th>           
   </tr> 
    <tr>  
      <td>x</td>  
       <td>x</td>
      <td>x</td>
      <td colspan=3>primario (trabajador)</td>  
   </tr> 
     <tr>  
      <th>Número de tarea</th> 
     <th>Descripción</th>
     <th>Número de errores</th>
     <th>Éxito de tarea</th>
    <th>Del 1 al 5, siendo 1 muy difícil y 5 muy fácil, ¿Qué calificación le otorga a ésta tarea?</th>
     <th>Tiempo</th>   
   </tr> 
    <tr>  
      <td>1</td> 
      <td>Regístrate como trabajador en la aplicación e inicia sesión. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>2</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
    <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, rechaza a Greg Anderson y  acepta a Victoria Robertson. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>5</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Elimina tu chat con Luis Pérez Medina y cancela su contrato. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
    <tr>  
      <td>8</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Ejemplo: Oprimió el botón de contratos en lugar de notificaciones (tarea 4)</td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>x</td> 
   </tr>
 </table>
 <br>
  <br>
 
  ***Formato 2: Perfil de cliente***

 <table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Nombre</td>  
       <td colspan=2>d/m/a</td> 
   </tr> 
   <tr>  
      <th colspan=6>Datos del participante</td> 
   </tr> 
    <tr>  
      <th>Género</th>  
      <th>Edad</th>
      <th>Ocupación</th>     
      <th colspan=3>Tipo de usuario</th>           
   </tr> 
    <tr>  
      <td>x</td>  
       <td>x</td>
      <td>x</td>
      <td colspan=3>primario (cliente)</td>  
   </tr> 
     <tr>  
      <th>Número de tarea</th> 
     <th>Descripción</th>
     <th>Número de errores</th>
     <th>Éxito de tarea</th>
      <th>Del 1 al 5, siendo 1 muy difícil y 5 muy fácil, ¿Qué calificación le otorga a ésta tarea?</th>   
     <th>Tiempo</th>   
   </tr> 
    <tr>  
      <td>1</td> 
      <td>Regístrate como cliente e inicia sesión. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>2</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
    <tr>  
      <td>3</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>5</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con Cintia Acosta López, manicurista.  </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x min</td>              
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cierra sesión.</td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Ejemplo: Oprimió la foto de perfil del mecánico en lugar de dar clic en el ícono (tarea 3). </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>x</td> 
   </tr>
 </table>



### Aplicación de las pruebas
## Cuestionarios de satisfacción
###  Cuestionario
### Aplicación del cuestionario
## Resultados
### Métricas[^2]
### Mejoras a las interfaces 
| Nombre de la ventana | Cambio | Descripción|
|--|--|--|
| x | x |x|

[^1]: FOCUX. (28 de marzo de 2022). Pruebas de usabilidad | Guía 2022 + Plantillas. *FOCOUX.* https://aprende-ux.focux.io/pruebas-de-usabilidad/
[^2]: Nacho Madrid. (28 de enero de 2020). *Métricas de usabilidad y experiencia de usuario.* Nacho Madrid. https://aprende-ux.focux.io/pruebas-de-usabilidad/
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkzNzAzODYxNCw2MzUyNDEwMzcsLTE0NT
UxNDQ4MDksMTAwNTY5MjMyNCwtNjU2MTA3NTA4LDIzMTc2NTk0
NiwxNDA1ODYwNTg4LC0xMjgxODI3OTMyLDE0MjYzOTU5NDEsLT
M4NTc2OTgyOSwxNTgzOTk1NzUsLTEwMTc3MjE4MTksLTcyMjc2
MjE0MCwtMTc2MDU4MjQyOCwtMjU3Nzk5ODU3LC0xNjQ2NjgxOD
I0LDQ4NTYxMDc4Niw0NTY1Nzg4NDksLTE3MTM2MjY4MjAsODY2
MzAzNTI2XX0=
-->