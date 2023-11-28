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
 - Computadora con el prototipo de la aplicación abierto: https://www.figma.com/file/WxkTPx8zGQiWg8UpDYWTxF/Dise%C3%B1o-modificado-(WorkFlash)?type=design&node-id=54702%3A25212&mode=design&t=xLKaaMpvV5pZPDRM-1
 - Cronómetro o celular. 
 - Celular o computadora con el Cuestionario de satisfacción abierto: https://elika234.questionpro.com/t/AY8KjZ0ocM


Para aplicar la prueba realizar lo siguiente: 
1. Acudir a la cita con la persona. 
2. Salude a la persona y agradezca su participación. 
3. Solicitar los datos del participante y anotarlos en el formato 1 o 2: género, edad, ocupación (si se conocen los datos del participante llenar éste apartado previo a la aplicación de la prueba). 
4. Explicar brevemente en qué consistirá la prueba (la persona responsable de aplicar la prueba deberá proporcionar el prototipo a la persona). 
**Guion**
A continuación te presentaré el prototipo de la aplicación para celular llamada WorkFlash. 
Podrás interactuar con el prototipo y realizar actividades específicas que te indicaré en su momento. En la medida de lo posible, completa las actividades sin solicitar ayuda, en su lugar, intenta descubrir cómo utilizar la aplicación. 
5. Es importante mencionar que para interactuar con los campos para escribir, como la contraseña, es necesario realizar clic sobre el rectángulo hasta que aparezca el texto deseado, una contraseña en este ejemplo. 
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
1. Los usuarios pueden registrarse como trabajadores e iniciar sesión. 
2.  Los trabajadores pueden aceptar, rechazar y cancelar un trabajo/contrato.
3.  Los trabajadores pueden visualizar calificaciones y comentarios de clientes. 
4. Los trabajadores pueden comunicarse con sus clientes mediante un chat y eliminarlo si así desean.
5. Los trabajadores pueden calificar a sus clientes.
6. Los trabajadores pueden  editar su perfil y cancelar su membresía.
7. La aplicación es intuitiva y agradable para los usuarios (aplica para clientes y trabajadores).

**Correspondencia entre los objetivos, indicadores y  requisitos**

<table align=center> 
     <tr>  
      <th>Indicador</th>
      <th>Requisito</th>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 1</th>  
     </tr>
     <tr>  
      <td>Tarea 1 (mínimo 4 de 6 participantes completaron la tarea). </td>
      <td>
       <li>RF-1. Perfiles. </li>
      <li>RF-3. Registro del trabajador.</li>
      <li>RF-5. Creación de contraseña.</li>
      </td>    
     </tr>
     <tr>  
      <td>Tarea 2 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-9. Creación del perfil de trabajador.</li>
      <li>RF-10. Inicio de sesión.</li>
    <li> RF-21. Recuperación de contraseña.</li>
      </td>    
     </tr>
     <tr>  
      <th colspan=2>Objetivo 2</th>  
     </tr>
     <tr>
     <td>Tarea 5 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-15. Contratación del servicio.</li>
      </td>    
     </tr>
      <tr>
     <td>Tarea 8 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-19. Cancelación del servicio.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 3</th>  
     </tr>
     <tr>  
      <td>Tarea 3 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-9. Creación del perfil de trabajador. </li>
      </td>    
     </tr>
     <tr>  
      <th colspan=2>Objetivo 4</th>  
     </tr>
     <tr>  
      <td>Tarea 6 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-14. Chat.</li>
      </td>    
     </tr>
      <tr>  
      <td>Tarea 8 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-14. Chat.</li>
      </td>    
     </tr>
       <tr>  
      <th colspan=2>Objetivo 5</th>  
     </tr>
     <tr>  
      <td>Tarea 7 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-16. Calificación del cliente.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 6</th>  
     </tr>
     <tr>  
      <td>Tarea 4 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-22. Modificación de perfil.</li>
      </td>    
     </tr>
      <tr>  
      <td>Tarea 9 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-20. Cancelación de la cuenta por parte del trabajador.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 7</th>  
     </tr>
     <tr>  
      <td>Máximo 2 errores por tarea (por participante).</td>
      <td rowspan=4>
    RNF-27. El sistema debe ser intuitivo, gráfico y agradable para la mayoría de usuarios.
      </td>    
     </tr>
      <tr>  
      <td>Tareas 1 al 9 completadas en el tiempo esperado.</td>
     </tr>
      <tr>  
      <td>Un promedio de mínimo 3 para la pregunta:  Del 1 al 5, siendo 1 muy difícil y 5 muy fácil, ¿Qué calificación le otorga a ésta tarea?</td>
     </tr>
      <tr>  
      <td><b>Cuestionario de satisfacción</b><br>
      <em>El promedio de la opción Totalmente de acuerdo o de acuerdo es el mayor:</em>
      <li>"Me gustaría utilizar este sistema más a menudo". </li>
      <li>"Creo que el sistema es sencillo y fácil de usar".</li>
      <li>"Creo que el sistema funciona bien y está bien integrado".</li>
      <li> "Creo que la mayoría de la gente puede aprender este sistema rápidamente".</li>
       <li>"Me siento seguro al utilizar este sistema".</li>
       <br>
       <em>El promedio de la opción En desacuerdo o Muy en desacuerdo es el mayor:</em>
          <li>"Me parece que este sistema es más complicado de lo que debería ser". </li>
           <li>"Necesito apoyo técnico para utilizar este sistema.". </li>
           <li>"Creo que hay muchas irregularidades en el sistema".</li>
          <li>"Creo que este sistema requiere mucho tiempo".</li>
          <li>"Creo que hay muchas cosas que aprender antes de poder empezar a utilizar este sistema".</li>
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
      <td>Regístrate como trabajador en la aplicación.<br>
      Nota: (Zona de trabajo: Mérida, Expiración de tarjeta: mes 11, año 2025).  </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
        <td>x s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
        <td>x s</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
         <td>x s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x s</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
        <td>x s</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
        <td>x s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
     <td>x s</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>x</td>
       <td>Completada/No completada</td>
       <td>x</td>
       <td>x s</td>                
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
 
 **Objetivos** 
1.  Los usuarios pueden registrarse como clientes e iniciar sesión. 
2. Los clientes pueden buscar un oficio/ocupación, visualizar una lista de trabajadores, su perfil, calificaciones y comentarios. 
3. Los clientes pueden contratar y cancelar un trabajo.
4. Los clientes pueden finalizar su contrato, calificar, comentar y reportar a los trabajadores.
5. Los clientes pueden comunicarse con los trabajadores mediante un chat y eliminarlo si así desean.
6. Los clientes pueden  editar su perfil.
7. La aplicación es intuitiva y agradable para los usuarios (aplica para clientes y trabajadores).

**Correspondencia entre los objetivos, indicadores y  requisitos**

<table align=center>  
     <tr>  
      <th>Indicador</th>
      <th>Requisito</th>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 1</th>  
     </tr>
     <tr>  
      <td>Tarea 1 (mínimo 4 de 6 participantes completaron la tarea)</td>
      <td>
      <li>RF-1. Perfiles. </li>
      <li>RF-2. Registro del cliente.</li>
      <li>RF-5. Creación de contraseña.</li>
      </td>    
     </tr>
      <tr>  
      <td>Tarea 2 (mínimo 4 de 6 participantes completaron la tarea)</td>
      <td>
      <li>RF-5. Creación de contraseña.</li>
      <li>RF-8. Creación del perfil de cliente.</li>
      <li>RF-10. Inicio de sesión.</li>
       <li>RF-21. Recuperación de contraseña.</li>
      </td>    
     </tr>
       <tr>  
      <th colspan=2>Objetivo 2</th>  
     </tr>
     <tr>
     <td>Tarea 4 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
       <li>RF-11. Búsqueda.</li>
       <li>RF-12. Filtro.</li>
       <li> RF-13. Elección del trabajador.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 3</th>  
     </tr>
     <tr>  
      <td>Tarea 5 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
       <li>RF-8. Creación del perfil de cliente.</li>
       <li>RF-15. Contratación del servicio.</li>
      </td>    
     </tr>
      <tr>  
      <td>Tarea 9 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
       <li>RF-19. Cancelación del servicio.</li>
      </td>    
     </tr>
     <tr>  
      <th colspan=2>Objetivo 4</th>  
     </tr>
     <tr>  
      <td>Tarea 7 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-6. Comentarios.</li>
       <li>RF-7. Calificaciones.</li>
      <li>RF-17. Finalización del contrato.</li>
      </td>    
     </tr>
       <tr>  
      <th colspan=2>Objetivo 5</th>  
     </tr>
     <tr>  
      <td>Tarea 5 (mínimo 4 de 6 participantes completaron la tarea)</td>
      <td rowspan=3>
      <li>RF-14. Chat.</li></td>    
     </tr>
      <tr>  
      <td>Tarea 6 (mínimo 4 de 6 participantes completaron la tarea)</td>
      <td>
      </td>    
     </tr>
      <tr>  
      <td>Tarea 8 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 6</th>  
     </tr>
     <tr>  
      <td>Tarea 3 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
      <li>RF-22. Modificación de perfil.</li>
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 7</th>  
     </tr>
     <tr>  
      <td>Máximo 2 errores por tarea (por participante).</td>
      <td rowspan=4>
    RNF-27. El sistema debe ser intuitivo, gráfico y agradable para la mayoría de usuarios.</td>    
     </tr>
      <tr>  
      <td>Tareas 1 al 9 completadas en el tiempo esperado</td>
     </tr>
      <tr>  
      <td>Un promedio de mínimo 3  para la pregunta:  Del 1 al 5, siendo 1 muy difícil y 5 muy fácil, ¿Qué calificación le otorga a ésta tarea?</td>
     </tr>
      <tr>  
      <td><b>Cuestionario de satisfacción</b><br>
      <em>El promedio de la opción Totalmente de acuerdo o de acuerdo es el mayor:</em>
      <li>"Me gustaría utilizar este sistema más a menudo". </li>
      <li>"Creo que el sistema es sencillo y fácil de usar".</li>
      <li>"Creo que el sistema funciona bien y está bien integrado".</li>
      <li> "Creo que la mayoría de la gente puede aprender este sistema rápidamente".</li>
       <li>"Me siento seguro al utilizar este sistema".</li>
       <br>
       <em>El promedio de la opción En desacuerdo o Muy en desacuerdo es el mayor:</em>
          <li>"Me parece que este sistema es más complicado de lo que debería ser". </li>
           <li>"Necesito apoyo técnico para utilizar este sistema.". </li>
           <li>"Creo que hay muchas irregularidades en el sistema".</li>
          <li>"Creo que este sistema requiere mucho tiempo".</li>
          <li>"Creo que hay muchas cosas que aprender antes de poder empezar a utilizar este sistema".</li>
      </td>
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
      <td>Regístrate como cliente en la aplicación. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>                    
   </tr>
   <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>              
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>              
   </tr>
    <tr>  
      <td>5</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>x</td>
       <td>Completada/No completada</td>
        <td>x</td>
       <td>x s</td>              
   </tr>
   <tr>  
      <td>9</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con la manicurista Cintia Acosta López y cierra cesión.  </td>
       <td>x</td>
       <td>Completada/No completada</td>
         <td>x</td>
       <td>x s</td>              
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
<br>
 

### Aplicación de las pruebas
 
 <table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Campos García Karen Elizabeth</td>  
       <td colspan=2>27/11/2023</td> 
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
      <td>Masculino</td>  
       <td>48</td>
      <td>Mecánico</td>
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
      <td>Regístrate como trabajador en la aplicación.<br>
      Nota: (Zona de trabajo: Mérida, Expiración de tarjeta: mes 11, año 2025).  </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>141 s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>33.89 s</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
         <td>13.30 s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
       <td>13.72 s</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
       <td>33.26 s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>13 s</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>63 s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
     <td>25 s</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
       <td>27.84 s</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>No cometió errores. </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>"Me gustó el diseño de la aplicación, "Creo que una vez familiarizándote con la aplicación es muy sencillo". </td> 
   </tr>
 </table>
<br> 
<br> 
 <table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4> Campos García Karen Elizabeth</td>  
       <td colspan=2>25/11/2023</td> 
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
      <td>Femenino</td>  
       <td>47</td>
      <td>Administradora</td>
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
      <td>Regístrate como cliente en la aplicación. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>0.44 s</td>              
   </tr>
   <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>0.23 s</td>              
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>0.23 s</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>1</td>
       <td>Completada</td>
        <td>4</td>
       <td>67.8 s</td>              
   </tr>
    <tr>  
      <td>5</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>0.23 s</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>0.06 s</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>0.26 s</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>1</td>
       <td>Completada</td>
        <td>5</td>
         <td>0.48 s</td>                         
   </tr>
   <tr>  
      <td>9</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con la manicurista Cintia Acosta López y cierra cesión.  </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>0.21 s</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Oprimió el texto "Busca un oficio/ocupación" en lugar de dar clic cobre el ícono de búsqueda (tarea 4). <br>Oprimió la barra de búsqueda en lugar de quedarse en la pestaña de contratos para levantar el reporte (tarea 8). </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>"Cambiar el signo + por otro símbolo para hacer más comprensible que al dar clic se desplegarán las opciones de contratar, reportar y cancelar. El signo + hace pensar que al dar clic se agregará otro contrato". <br>"El diseño me gustó".</td> 
   </tr>
 </table>
 <br>
 <br>

<table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Ruben Moises Loria Pech</td>  
       <td colspan=2>26/11/23</td> 
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
      <td>Masculino</td>  
       <td>58</td>
      <td>plomero</td>
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
      <td>Regístrate como trabajador en la aplicación.<br>
      Nota: (Zona de trabajo: Mérida, Expiración de tarjeta: mes 11, año 2025).  </td>
       <td>3</td>
       <td>Completada</td>
       <td>3</td>
        <td>60s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>5</td>
       <td>Completada</td>
       <td>2</td>
        <td>5 min</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
         <td>30s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
       <td>5 min</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
       <td>30s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
        <td>5 min</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>10s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
     <td>3 min</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>3</td>
       <td>Completada</td>
       <td>3</td>
       <td>1 min</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Ejemplo: Oprimió el botón de contratos en lugar de notificaciones (tarea 4).
       Hice el mismo experimento con alguien mas joven y se adapto mas rapido el trabajor con quien hice el experimento se desespero, en la de eliminar chat fue el que mas tuvo mas errores    </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>normalmente los adultos se guian mas por las primeras 3 letras no terminar de leer las cosas y no se molestan en intentarlo creo que lo mejor es poner dibujitos para mas intuitivo </td> 
   </tr>
 </table>
 <br>
 <br>
 
<table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Ruben Moises Loria Pech</td>  
       <td colspan=2>26/11/23</td> 
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
      <td>Femenino</td>  
       <td>28</td>
      <td>Abogada</td>
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
      <td>Regístrate como cliente en la aplicación. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>10s</td>                    
   </tr>
   <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión. </td>
       <td>0</td>
       <td>Completada</td>
        <td>3</td>
       <td>10s</td>              
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>1</td>
       <td>Completada</td>
        <td>4</td>
       <td>10s</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>30s</td>              
   </tr>
    <tr>  
      <td>5</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>2</td>
       <td>Completada</td>
        <td>4</td>
       <td>60s</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>45s</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>60s</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>60s</td>              
   </tr>
   <tr>  
      <td>9</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con la manicurista Cintia Acosta López y cierra cesión.</td>
       <td>4</td>
       <td>Completada</td>
         <td>3</td>
       <td>300 s</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5> Oprimió la foto de perfil del mecánico en lugar de dar clic en el ícono (tarea 3).<br> No vio que al bajar podia contratarlo(tarea 5).
       <br>Cancelar el contrato fue una de las que se dificultó porque no sabia si al eliminar se cancelaba el contrato en automático(tarea 9) </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>Se le facilitó al cliente porque está acostumbrada a la tecnología y a éste tipo de interfaces.</td> 
   </tr>
 </table>
<br>
<br>
<table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Ruben Moises Loria Pech</td>  
       <td colspan=2>26/11/23</td> 
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
      <td>Masculino</td>  
       <td>58</td>
      <td>plomero</td>
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
      <td>Regístrate como trabajador en la aplicación.<br>
      Nota: (Zona de trabajo: Mérida, Expiración de tarjeta: mes 11, año 2025).  </td>
       <td>3</td>
       <td>Completada</td>
       <td>3</td>
        <td>60s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>5</td>
       <td>Completada</td>
       <td>2</td>
        <td>5 min</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
         <td>30s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
       <td>5 min</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
       <td>30s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
        <td>5 min</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>10s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
     <td>3 min</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>3</td>
       <td>Completada</td>
       <td>3</td>
       <td>1 min</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Ejemplo: Oprimió el botón de contratos en lugar de notificaciones (tarea 4).
       Hice el mismo experimento con alguien mas joven y se adapto mas rapido el trabajor con quien hice el experimento se desespero, en la de eliminar chat fue el que mas tuvo mas errores    </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>normalmente los adultos se guian mas por las primeras 3 letras no terminar de leer las cosas y no se molestan en intentarlo creo que lo mejor es poner dibujitos para mas intuitivo </td> 
   </tr>
 </table>
 <br>
 <br>
 <table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Brandon Emmanuel Suárez Balam</td>  
       <td colspan=2>26/11/23</td> 
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
      <td>Masculino</td>  
       <td>38</td>
      <td>Mecánico</td>
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
      <td>Regístrate como trabajador en la aplicación.<br>
      Nota: (Zona de trabajo: Mérida, Expiración de tarjeta: mes 11, año 2025).  </td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
        <td>78s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>5</td>
       <td>Completada</td>
       <td>2</td>
        <td>5 min</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
         <td>30s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
       <td>5 min</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
       <td>30s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
        <td>5 min</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>10s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
     <td>3 min</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>3</td>
       <td>Completada</td>
       <td>3</td>
       <td>1 min</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Ejemplo: Oprimió el botón de contratos en lugar de notificaciones (tarea 4).
       Hice el mismo experimento con alguien mas joven y se adapto mas rapido el trabajor con quien hice el experimento se desespero, en la de eliminar chat fue el que mas tuvo mas errores    </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>normalmente los adultos se guian mas por las primeras 3 letras no terminar de leer las cosas y no se molestan en intentarlo creo que lo mejor es poner dibujitos para mas intuitivo </td> 
   </tr>
 </table>
 <br>
 <br>
<table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Brandon Emmanuel Suárez Balam</td>  
       <td colspan=2>26/11/23</td> 
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
      <td>Masculino</td>  
       <td>22</td>
      <td>Estudiante</td>
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
      <td>Regístrate como cliente en la aplicación. </td>
       <td>1</td>
       <td>Completada</td>
        <td>4</td>
       <td>75s</td>                    
   </tr>
   <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>20s</td>              
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>1</td>
       <td>Completada</td>
        <td>4</td>
       <td>30s</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>1</td>
       <td>Completada</td>
        <td>4</td>
       <td>92s</td>              
   </tr>
    <tr>  
      <td>5</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>22s</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>31s</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>1</td>
       <td>Completada</td>
        <td>4</td>
       <td>58s</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>36s</td>              
   </tr>
   <tr>  
      <td>9</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con la manicurista Cintia Acosta López y cierra cesión.</td>
       <td>0</td>
       <td>Completada</td>
         <td>5</td>
       <td>15s</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5> Intento iniciar sesión sin antes haberse registrado (tarea 1). <br> Abrio el menú de búsqueda (tarea 3). <br> Le picó a la imagen de perfil de usuario en vez del icono de perfil (tarea 4). <br> Le picó al icono de mensajes en vez de la opción de finalizar contrato (tarea 7). </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>"Cuando iba a eliminar el contrato y lo seleccionaba, creo que la opción debería ser directa y no en la pesataña de arriba, mejor dónde está el nombre de la persona."</td> 
   </tr>
 </table>


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
eyJoaXN0b3J5IjpbMTYzMzQ5NTIxMiwtODEwMDY0MjU5LDU4OD
IwNzk5MSwtMTY4NTg3MjgzNSwtOTA3NTU0NTI2XX0=
-->