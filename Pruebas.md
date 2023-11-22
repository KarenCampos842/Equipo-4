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
**Guion**
Como parte de un proyecto en la universidad, junto a mi equipo, estoy realizando el diseño de una aplicación y requiero probar el prototipo. 

**Materiales** 

 - Formato 1 o 2 localizados al final del apartado de Protocolo (impreso o digital). 
 - Computadora con el prototipo de la aplicación abierto. 
 - Cronómetro o celular. 
 - Celular o computadora con el Cuestionario de satisfacción abierto: https://www.questionpro.com/a/SurveyPreview


Para aplicar la prueba realizar lo siguiente: 
5. Acudir a la cita con la persona. 
6. Salude a la persona y agradezca su participación. 
7. Explicar brevemente en qué consistirá la prueba (la persona responsable de aplicar la prueba deberá proporcionar el prototipo a la persona). 
**Guion**
A continuación te presentaré el prototipo de la aplicación para celular llamada WorkFlash. 
Podrás interactuar con el prototipo y realizar actividades específicas que te indicaré en su momento. En la medida de lo posible, completa las actividades sin solicitar ayuda, en su lugar, intenta descubrir cómo utilizar la aplicación. 
8. Realizar una demostración con el log in (es importante mencionar que para interactuar con los campos para escribir, como la contraseña, es necesario realizar clic sobre el rectángulo hasta que aparezca el texto deseado, una contraseña en este ejemplo). 
9.  Proporcionar un escenario en el que se utilizará la aplicación: 
**Para el perfil de trabajador** 
El contexto es el siguiente: Imagina que tu nombre es Juan Campos Romero, eres mecánico y quieres usar WorkFlash para darte a conocer y atraer más clientes. 
10. Aplicar la prueba utilizando el formato 1 (trabajador) o el formato 2 (cliente). 
- Solicitar al participante realizar la primera tarea.
-  Activar el cronómetro (detener el cronómetro cuando el participante haya finalizado la tarea) y anotar el tiempo. En caso de que el participante no haya logrado completar la tarea, el tiempo se detendrá hasta que el participante externe no poder realizar la actividad. 
- Contar y anotar el número de errores que cometió el participante durante la tarea. Igualmente, anotar en el formato cual fue el error. 
- Marcar como Completada la tarea o No completada, según sea el caso. 
- Realizar la siguiente pregunta al participante y anotar la respuesta: Del 1 al 5, siendo 1 muy difícil y 5 muy fácil, ¿Qué calificación le otorga a ésta tarea?
- Repetir el proceso hasta terminar con las tareas. 
11.  Anotar comentarios/observaciones del participante sobre la aplicación (preguntar directamente si es necesario). 
12. Proporcionar el ***Cuestionario de satisfacción*** al participante para su resolución. 
13. Agradecer a la persona su participación y despedirse. 

***Nota:*** Al finalizar con la prueba, el formato que se haya utilizado (1 o 2), ya resuelto, deberá localizarse en el apartado <a href="https://github.com/KarenCampos842/Equipo-4/blob/Tercera-Entrega/Pruebas.md#aplicaci%C3%B3n-de-las-pruebas">Aplicación de las pruebas</a>


### Pruebas
**Objetivos** 
1.  Los trabajadores pueden aceptar, rechazar o cancelar un trabajo/contrato.
2. Los trabajadores pueden comunicarse con sus clientes.
3. Los trabajadores pueden visualizar calificaciones y comentarios de clientes. 
4. Los trabajadores pueden  cancelar su membresía.
5. La aplicación es intuitiva. 

**Correspondencia entre los objetivos, indicadores y  requisitos**



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
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Elimina tu chat con Luis Pérez Medina y repórtalo. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Ha surgido un inconveniente y debes de cancelar un trabajo. Cancela tu contrato con Cintia Acosta López.  </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x min</td>              
   </tr>
    <tr>  
      <td>9</td> 
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
eyJoaXN0b3J5IjpbLTE4MTk4NjQ4NTMsMTQwNTg2MDU4OCwtMT
I4MTgyNzkzMiwxNDI2Mzk1OTQxLC0zODU3Njk4MjksMTU4Mzk5
NTc1LC0xMDE3NzIxODE5LC03MjI3NjIxNDAsLTE3NjA1ODI0Mj
gsLTI1Nzc5OTg1NywtMTY0NjY4MTgyNCw0ODU2MTA3ODYsNDU2
NTc4ODQ5LC0xNzEzNjI2ODIwLDg2NjMwMzUyNiwxNjM0NTU3Mj
c4LDEwNzg5MDQ3OTUsMTA3ODg4MzA0OCw5ODE5MTUyNzcsMTEz
NzA0MTU1Nl19
-->