# Pruebas
## Pruebas informales[^1]
### Protocolo
Para las pruebas se reclutarán a 12 personas en total. 6 con el perfil de cliente y 6 con el perfil de trabajador. 

**Reclutamiento (presencial o mediante un mensaje de texto o llamada telefónica)** 

 1. Localizar a la persona que cumpla con el perfil de cliente primario: <a href="https://github.com/KarenCampos842/Equipo-4/blob/Tercera-Entrega/Producto.md#usuarios">Usuarios</a> 


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
      <td>Máximo 2 errores por tarea (por participante). En total, máximo 12 errores por tarea.</td>
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

**Tiempo esperado**

El promedio de los tiempos de cada tarea no excede el doble del tiempo de la tabla a continuación:

| Tarea |Tiempo base| Tiempo esperado (t)|
|--|--|--|
| 1 | 67.8s | t≤135.6s |
| 2 | 16.28s |t≤32.56s |
| 3 | 10.73s |t≤21.46s |
| 4 | 30.64s |t≤61.28s |
| 5 | 10.24s |t≤20.48s |
| 6 | 7.84s |t≤15.68s |
| 7 | 16.77s |t≤33.54s |
| 8 | 11.46s |t≤22.92s |
| 9 | 11.05s |t≤22.1s |


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
      <td>Máximo 2 errores por tarea (por participante). En total, máximo 12 errores por tarea.</td>
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

**Tiempo esperado**

El promedio de los tiempos de cada tarea no excede el doble del tiempo de la tabla a continuación:

| Tarea |Tiempo base| Tiempo esperado (t)|
|--|--|--|
| 1 | 28.61s | t≤57.22s |
| 2 | 16.28s |t≤32.56s |
| 3 | 18.19s |t≤36.38s |
| 4 | 18.84s |t≤37.68s |
| 5 | 23.32s |t≤46.64s |
| 6 | 8.47s |t≤16.94s |
| 7 | 20.39s |t≤40.78s |
| 8 | 19.63s |t≤39.26s |
| 9 | 13.88s |t≤27.76s |

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
      <td colspan=4>Rubén Moisés Loria Pech</td>  
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
       <td colspan=5>"Normalmente los adultos se guían más por las primeras 3 letras, no terminan de leer las cosas y no se molestan en intentarlo, creo que lo mejor es poner dibujitos para mas intuitivo". </td> 
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
      <td colspan=4>Rubén Moisés Loria Pech</td>  
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
       <td colspan=5> Oprimió la foto de perfil del mecánico en lugar de dar clic en el ícono (tarea 3).<br> No vio que al bajar podia contratarlo (tarea 5).
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
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>9s</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
         <td>13s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>2</td>
       <td>Completada</td>
       <td>3</td>
       <td>120s</td>                       
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
       <td>0</td>
       <td>Completada</td>
       <td>4</td>
        <td>60s</td>                    
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
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
     <td>30s</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>0</td>
       <td>Completada</td>
       <td>4</td>
       <td>46s</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Oprimió el botón de recuperación de contraseña en vez de registrarse (tarea1). <br> Le picó a las pestañas de arriba antes del botón de editar (tarea 2). <br> Le picó a los botones de abajo antes del icono de notificación (tarea 4).</td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5> "La aplicación es fácil de usar, pero podrían ser más claros los iconos."</td> 
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
<br>
<br>
<table align=center>  
   <tr>  
      <th colspan=4>Nombre del responsable de la aplicación</th>  
      <th colspan=2>Fecha de aplicación</th> 
   </tr> 
    <tr>  
      <td colspan=4>Carlos Emmanuel Romero Poot</td>  
       <td colspan=2>28/11/2023</td> 
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
       <td>43</td>
      <td>Plomero</td>
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
       <td>4</td>
        <td>154 s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td> 42 s</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
         <td>11 s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
       <td>16 s</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
       <td>10 s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>12 s</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
        <td>20 s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>0</td>
       <td>Completada/No completada</td>
       <td>5</td>
     <td>17 s</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>0</td>
       <td>Completada/No completada</td>
       <td>5</td>
       <td>23 s</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>No cometio errores</td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>Tiene un buen diseño</td> 
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
      <td colspan=4>Carlos Emmanuel Romero Poot</td>  
       <td colspan=2>29/11/2023</td> 
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
       <td>18</td>
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
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>60  s</td>                    
   </tr>
   <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>40 s</td>              
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>21 s</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>1</td>
       <td>Completada</td>
        <td>4</td>
       <td>72 s</td>              
   </tr>
    <tr>  
      <td>5</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>0</td>
       <td>Completada/No completada</td>
        <td>5</td>
       <td>17 s</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>10 s</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>3</td>
       <td>16 s</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>23 s</td>              
   </tr>
   <tr>  
      <td>9</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con la manicurista Cintia Acosta López y cierra cesión.  </td>
       <td>0</td>
       <td>Completada</td>
         <td>5</td>
       <td>19 s</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5> No encontraba la barra de búsqueda y se fue a la parte de contratos (tarea 4). </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>"Deberían tener una barra de búsqueda más visible". </td> 
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
      <td colspan=4>Kendrick Asaf Cardenas Rojas</td>  
       <td colspan=2>28/11/2023</td> 
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
       <td>63</td>
      <td>Herrero</td>
      <td colspan=3> trabajador </td>  
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
       <td>Completada </td>
       <td>5</td>
        <td>4s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
        <td>6s</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
         <td>6s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>5</td>
       <td>Completada</td>
       <td>3</td>
       <td>15s</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>2</td>
       <td>Completada</td>
       <td>5</td>
       <td>8s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>1</td>
       <td>Completada</td>
       <td>4</td>
        <td>10s</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>2</td>
       <td>Completada</td>
       <td>5</td>
        <td>6s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>1</td>
       <td>Completada</td>
       <td>5</td>
     <td> 11s</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>3</td>
       <td>Completada</td>
       <td>4</td>
       <td> 10s</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Ejemplo:  No supo donde presionar para eliminar el chat (tarea 8) No supo como salir de la aplicacion (tarea 9)</td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5></td> 
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
      <td colspan=4>Kendrick Asaf Cardenas Rojas</td>  
       <td colspan=2>28/11/2023</td> 
   </tr> 
   <tr>  
      <th colspan=6>Datos del participante</td> 
   </tr> 
    <tr>  
      <th>Femenino</th>  
      <th>34</th>
      <th>Oficinista</th>     
      <th colspan=3>Tipo de usuario</th>           
   </tr> 
    <tr>  
      <td>x</td>  
       <td>x</td>
      <td>x</td>
      <td colspan=3>Cliente</td>  
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
       <td>8s</td>                    
   </tr>
   <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>6s</td>              
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>10s</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>12s</td>              
   </tr>
    <tr>  
      <td>5</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>25s</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>10s</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>15s</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>11s</td>              
   </tr>
   <tr>  
      <td>9</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con la manicurista Cintia Acosta López y cierra cesión.  </td>
       <td>0</td>
       <td>Completada</td>
         <td>5</td>
       <td>25s</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>No cometió errores.</td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>x</td> 
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
      <td colspan=4>Maldonado Medina Hansony de Jesús</td>  
       <td colspan=2>29/11/2023</td> 
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
       <td>56</td>
      <td>Gerente</td>
      <td colspan=3>Primario (Trabajador)</td>  
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
       <td>3</td>
        <td>189 s</td>            
   </tr>
    <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión.</td>
       <td>0</td>
       <td>Completada</td>
       <td>4</td>
        <td>51 s</td>                          
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres saber que opinan tus clientes de tí. Lee sus comentarios y calificaciones.</td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
         <td>25 s</td>                       
   </tr>
    <tr>  
      <td>4</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>0</td>
       <td>Completada</td>
       <td>4</td>
       <td>23 s</td>                       
   </tr>
    <tr>  
      <td>5</td> 
      <td>Se te ha notificado de nuevos trabajos, revisa tus notificaciones, acepta a Victoria Robertson y rechaza a Greg Anderson. </td>
       <td>0</td>
       <td>Completada</td>
       <td>5</td>
       <td>41.19 s</td>                   
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Victoria Robertson. </td>
       <td>0</td>
       <td>Completada</td>
       <td>4</td>
        <td>27 s</td>                    
   </tr>
   <tr>  
      <td>7</td> 
      <td>Ha finalizado tu contrato con Victoria Robertson, califícala.  </td>
       <td>0</td>
       <td>Completada</td>
       <td>4</td>
        <td>53 s</td>                 
   </tr>
   <tr>  
      <td>8</td> 
      <td>Uno de tus clientes no asistió a la reunión que habían programado. Cancela tu contrato con Luis Pérez Medina y elimina su chat. </td>
       <td>0</td>
       <td>Completada</td>
       <td>3</td>
     <td>25 s</td>                        
   </tr>
    <tr>  
      <td>9</td> 
      <td>Cancela tu membresía y sal de la aplicación. </td>
       <td>2</td>
       <td>No Completada</td>
       <td>1</td>
       <td>46 s</td>                
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Cometió 2 errores, se equivocó al querer cancelar la suscripción y salió de la aplicación sin cancelarla. (Tarea 9) </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>"Me gustó el diseño de la aplicación. Estuvo bien la experiencia, me recordó a varias aplicaciones que tengo, aunque en algunas partes si me confundían". </td> 
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
      <td colspan=4> Maldonado Medina Hansony de Jesús</td>  
       <td colspan=2>28/11/2023</td> 
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
       <td>55</td>
      <td>Maestra</td>
      <td colspan=3>Primario (Cliente)</td>  
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
        <td>4</td>
       <td>49 s</td>              
   </tr>
   <tr>  
      <td>2</td> 
      <td>Olvidaste tu contraseña. Recupera tu contraseña e inicia sesión. </td>
       <td>0</td>
       <td>Completada</td>
        <td>5</td>
       <td>29 s</td>              
   </tr>
   <tr>  
      <td>3</td> 
      <td>Quieres cambiar datos de tu perfil, edítalo.</td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>38 s</td>              
   </tr>
    <tr>  
      <td>4</td> 
      <td>Tu carro marca un error desconocido en el tablero, necesitas un mecánico. Busca al mecánico Juan Campos Romero, observa su perfil, calificaciones y comentarios.</td>
       <td>1</td>
       <td>Completada</td>
        <td>2</td>
       <td>109 s</td>              
   </tr>
    <tr>  
      <td>5</td> 
      <td>Inicia un chat con el mecánico Juan Campos Romero, contrata su servicio y regresa a tu perfil. </td>
       <td>1</td>
       <td>No Completada</td>
        <td>5</td>
       <td>56 s</td>              
   </tr>
   <tr>  
      <td>6</td> 
      <td>Revisa tu última conversación con Juan Campos Romero.</td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>17 s</td>              
   </tr>
   <tr>  
      <td>7</td> 
      <td>Juan Campos Romero ha terminado su trabajo. Finaliza tu contrato con él, realiza un comentario y califícalo. </td>
       <td>1</td>
       <td>Completada</td>
        <td>3</td>
       <td>48 s</td>              
   </tr>
   <tr>  
      <td>8</td> 
      <td>Luis Pérez Medina, plomero, no asistió a la reunión que habían programado. Elimina tu chat con él y repórtalo. </td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
         <td>72 s</td>                         
   </tr>
   <tr>  
      <td>9</td> 
      <td>Ha surgido un inconveniente y debes de cancelar uno de tus contratos. Cancela tu contrato con la manicurista Cintia Acosta López y cierra sesión.  </td>
       <td>0</td>
       <td>Completada</td>
        <td>4</td>
       <td>38 s</td>              
   </tr>
   <tr>  
      <th>Descripción de errores</th>
       <td colspan=5>Cometió 3 errores, No pudo regresar a su perfil después de haber contratado el servicio (Tarea 5), Seleccionó un icono erróneo al tratar de buscar al trabajador (Tarea 4) y se le complicó buscar como finalizar el contrato (Tarea 7). </td> 
   </tr>  
    <tr>  
      <th>Comentarios/Observaciones</th>
       <td colspan=5>"Hay que implementar un icono de búsqueda como una lupa o una barra y cuando trataba de regresar a mi perfil, solo iba al del trabajador y salía como si no se hubiera contratado, pero el diseño estaba bonito".</td> 
   </tr>
 </table>
 <br>
 <br>
 
## Cuestionarios de satisfacción
###  Cuestionario
![Captura de pantalla 2023-12-06 162907.png](https://raw.githubusercontent.com/KarenCampos842/EGIT/main/encuesta1.png)
![Captura de pantalla 2023-12-06 162907.png](https://raw.githubusercontent.com/KarenCampos842/EGIT/main/encuesta2.png)

### Aplicación del cuestionario
![Captura de pantalla 2023-12-06 162907.png](https://raw.githubusercontent.com/KarenCampos842/EGIT/main/Captura%20de%20pantalla%202023-12-06%20162907.png)
## Resultados
### Métricas[^2]

**Métrica de satisfacción**
![Captura de pantalla 2023-12-06 162907.png](https://raw.githubusercontent.com/KarenCampos842/EGIT/main/Captura%20de%20pantalla%202023-12-06%20162907.png)

**Cantidad de tareas Completadas/No completadas como trabajador**
**![](https://lh7-us.googleusercontent.com/gDEv2NbJj0B3UNyd3NvRe3ZkM5K_vDszD5pz_zZ32SHkNpiExRihVk6pDIFZLDDkKj212UzQpT1cDEuw4Kgudg63K4kXOOxj1kWE7mWyVcLtmOlKw4PuRvdGVU4nf4U9gxhW2qOh9kZdIRcuHYhOW_4 )**
<br>
**Cantidad de tareas Completadas/No completadas como cliente**
**![](https://lh7-us.googleusercontent.com/dZNXFFR1pweQ68acJ6-h79mEkF4vRoI5gRiVvHv6tfUY8DAY62UMHWYF7N0bx1kjN3eloqral66uR22RxQ2P6qSMOVDQI_fIyQ6baBQBtFKmYKB2_lq2Qx006kpFa73KKbOy9L0M7Hm79uAHj5zHETA )**
<br>
**Tiempo promedio en segundos de las pruebas por tarea como trabajadores**
**![](https://lh7-us.googleusercontent.com/oJxMYOVCAUNCjPPlt52O6pQxSmpAHXudeMCBGce1DI3gPFoE3Nct_oO_D57NuHsbs1AapzqwBn0K_1a0wB0sRZRxoaMaRtjw8YK1Z_KznD92Fkd0tVUZdlnLJhMB3mfywpWkLzSCGaSCQfT05hr7yxk )**
<br>
**Tiempo promedio en segundos de las pruebas por tarea como clientes**
**![](https://lh7-us.googleusercontent.com/QmDojE-JcXPL8mqm3vU1rGRtDjB3aCxYQC6OW_CTIzSbb6TNoufL7sapGAL8gOtgA1PTBIMBuGnwEHplMzsQjsBWeK7anhvcoihC8eg-D67ilbtx0Kzceu9SIvTylJu4zcZOOPrIilhqXLEQFpNUYUE)**
<br>
**Cantidad de errores cometidos como trabajadores**
**![](https://lh7-us.googleusercontent.com/9hPYXb7LvUUGYm4-VkZeBVDaHm81Qng-aIJ81kRu197LZ66QGNZ9OdkEHiftxbg_kVHkUz4F0WNnlo7Ed3NnO0SMu0J-9aF-BDAcuxaB7_eAMF3hqUGkyNAEX4345_dP5iju_QweD6Kaa6PwIn6gn5Q)**
<br>
**Cantidad de errores cometidos como clientes**
**![](https://lh7-us.googleusercontent.com/KBqPWKmToFTVY3HrAQD8HMSZHqoyDFVPkMOaGedPfq0pq5mQs8-RE45unNr0DZMO91ZU_PaT5b1G-Lx0FRh9ZvohUu-rWqat6PZwi9JIzC5AtXiE0CrmBJPoFb8D6pdHK93tqfO1heUZumOBLSxuyJM)**

<br>
<table align=center>  
     <tr>  
      <th>Indicador</th>
      <th>Requisito</th>    
      <th>Alcance/cumplimiento de los requisitos</th>
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
      <td>6/6 personas cumplieron la tarea por lo que los requisitos 1, 2 y 5 fueron exitosos</td>
      <td>  
     </tr>
      <tr>  
      <td>Tarea 2 (mínimo 4 de 6 participantes completaron la tarea)</td>
      <td>
      <li>RF-5. Creación de contraseña.</li>
      <li>RF-8. Creación del perfil de cliente.</li>
      <li>RF-10. Inicio de sesión.</li>
       <li>RF-21. Recuperación de contraseña.</li>
      </td>  
      <td>6/6 personas cumplieron la tarea por lo que los requisitos 5, 8, 10 y 21 fueron exitosos..</td>
      <td>    
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
       <td>6/6 personas cumplieron la tarea por lo que los requisitos 11, 12 y 13 fueron exitosos</td>
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
       <td>6/6 personas cumplieron la tarea por lo que los requisitos 8 y 15 fueron exitosos</td>   
     </tr>
      <tr>  
      <td>Tarea 9 (mínimo 4 de 6 participantes completaron la tarea).</td>
      <td>
       <li>RF-19. Cancelación del servicio.</li>
      </td>    
       <td>5/6 personas cumplieron la tarea por lo que el requisito 19 fue exitoso</td>
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
       <td>6/6 personas cumplieron la tarea por lo que los requisitos 6, 7 y 17 fueron exitosos</td>   
     </tr>
       <tr>  
      <th colspan=2>Objetivo 5</th>  
     </tr>
     <tr>  
      <td>Tarea 5 (mínimo 4 de 6 participantes completaron la tarea)</td>
      <td rowspan=3>
      <li>RF-14. Chat.</li>
      </td>   
      <td rowspan=3>
      <li>6/6 personas cumplieron la tarea por lo que el requisito 14 fue exitoso.</li>
      </td>   
      <td></td> 
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
      <td>6/6 personas cumplieron la tarea por lo que el requisito 22 fue exitoso</td>   
      </td>    
     </tr>
      <tr>  
      <th colspan=2>Objetivo 7</th>  
     </tr>
     <tr>  
      <td>Máximo 2 errores por tarea (por participante). En total, máximo 12 errores por tarea.</td>
      <td rowspan=4>
    RNF-27. El sistema debe ser intuitivo, gráfico y agradable para la mayoría de usuarios.</td>   
    <td rowspan=4>
    El promedio de calificación fue superior a 4  y el promedio de la opción Totalmente de acuerdo y de acuerdo es el mayor por lo que el objetivo 7 fue exitoso.</td>   
    <td></td>    
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


### Mejoras a las interfaces 

<table border="1">
  <tr>
    <th>Nombre de la ventana </th>
    <th>Cambio</th>
    <th>Descripción </th>
  </tr>
  <tr>
    <td> 1_registro </td>
    <td> Sin cambios.  </td>
    <td> Ventana de inicio de sesión con la opción de crear una cuenta o recuperar tu contraseña. </td>
  </tr>
  <tr>
    <td> 2_registro </td>
    <td> Sin cambios.  </td>
    <td> Ventana donde se selecciona el tipo de perfil para crear una cuenta (cliente o trabajador).  </td>
  </tr>
   <tr>
    <td>0</td>
    <td> El botón de WorkFlash se vuelve funcional.  </td>
    <td> Venta que simula la pantalla de aplicaciones de un teléfono. </td>
  </tr>
   <tr>
    <td>1_registro_trabajador </td>
    <td> Sin cambios  </td>
    <td>Se solicitan datos generales (nombres, apellidos y correo electrónico).   </td>
  </tr>
   <tr>
    <td>2_registro_trabajador </td>
    <td> Sin cambios.  </td>
    <td>Se solicita una identificación (INE o cartilla militar) y una fotografía para continuar el proceso.  </td>
  </tr>
   <tr>
    <td>3_registro_trabajador </td>
    <td> Sin cambios.  </td>
    <td>Ventana de configuración de cuenta donde el trabajador establece su oficio, zona de trabajo, número telefónico y algún trabajo que su oficio ofrezca.  </td>
  </tr>
   <tr>
    <td>4_registro_trabajador </td>
    <td> Sin cambios.  </td>
    <td>Se solicitan los datos bancarios para el Pago de la membresía. </td>
  </tr>
   <tr>
    <td>5_registro_trabajador </td>
    <td> Sin cambios.  </td>
    <td>Ventana de donde se exponen los términos y condiciones que tienen que ser aceptados para completar el registro.  </td>
  </tr>
   <tr>
    <td>6_registro_trabajador </td>
    <td> Sin cambios.  </td>
    <td>Ventana donde se finaliza el registro del trabajador y se da aviso para que el trabajador revise su correo.  </td>
  </tr> 
   <tr>
    <td>Inicio_trabajador </td>
    <td> Nueva ventana.   </td>
    <td>Ventana de inicio específico para el trabajador con datos predeterminados. </td>
  </tr>
   <tr>
    <td>Recuperacion_contraseña_trabajador  </td>
    <td> Nueva ventana.   </td>
    <td> Ventana de recuperación de contraseña específica para el trabajador.  </td>
  </tr>
   <tr>
    <td>Permiso de ubicación_trabajador  </td>
    <td> Nueva ventana.</td>
    <td> Ventana específica del trabajador para permitir que la aplicación tenga acceso a la ubicación.  </td>
  </tr>
   <tr>
    <td>1_trabajador </td>
    <td>Se cambia el botón de "Review" por "reseñas". </td>
    <td> Ventana principal del perfil del trabajador donde se encuentran datos de su trabajo y de contacto. </td>
  </tr>
   <tr>
    <td>1_trabajador_e </td>
    <td>Se cambia el nombre de “1_trabajador” a “1_trabajador_e”.  </td>
    <td> Ventana con una notificación de cancelación de contrato. </td>
  </tr>
   <tr>
    <td>1_trabajador_e (2)</td>
    <td>Se cambia el nombre de “1_trabajador” a “1_trabajador_e”.  </td>
    <td>variación de la ventana "1_trabajador_e" con la notificación de un reporte al trabajador.  </td>
  </tr>
   <tr>
    <td>2_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana del perfil del trabajador donde se encuentran las reseñas. </td>
  </tr>
   <tr>
    <td>3_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana del perfil del trabajador donde se encuentran los datos de la tarjeta de crédito ligada a la membresía y un botón de cancelación. </td>
  </tr>
   <tr>
    <td>3.5_trabajador</td>
    <td>Nueva ventana. </td>
    <td>Ventana que aparece después de cancelar la membresía. </td>
  </tr>
   <tr>
    <td>4_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana de notificaciones donde aparecen nuevas ofertas de trabajo. </td>
  </tr>
   <tr>
    <td>5_trabajador</td>
    <td>Se cambia el símbolo de más por tres puntos. </td>
    <td>Ventana de contratos del trabajador donde se puede calificar o cancelar un trabajo. </td>
  </tr>
   <tr>
    <td>6_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana donde se puede acceder a un chat privado con los clientes.  </td>
  </tr>
   <tr>
    <td>7_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana para eliminar chats.   </td>
  </tr>
   <tr>
    <td>8_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana de chat con Victoria Robertson. </td>
  </tr>
   <tr>
    <td>9_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana para editar los datos del trabajador en su perfil </td>
  </tr>
   <tr>
    <td>9_trabajador_e</td>
    <td>Se elimina la foto del trabajador y se cambia el nombre de la ventana de “9_trabajador” a”9_trabajador_e”.  </td>
    <td>Ventana de advertencia para llenar los campos faltantes de la ventana "9_trabajador" </td>
  </tr>
   <tr>
    <td>9_trabajador_e (2)</td>
    <td>Se elimina la foto del trabajador y se cambia el nombre de la ventana de “9_trabajador” a”9_trabajador_e”.  </td>
    <td>variación de la ventana "9_trabajador_e" con la advertencia de ingresar un número de teléfono válido.  </td>
  </tr>
   <tr>
    <td>10_trabajador</td>
    <td>Sin cambios. </td>
    <td>Ventana para editar los datos de la tarjeta de crédito ligada a la membresía </td>
  </tr>
   <tr>
    <td>10_trabajador_e</td>
    <td>Se cambia el nombre de "10_trabajador" a "10_trabajador_e". </td>
    <td>Ventana de advertencia al no llenar rodos los campos de la tarjeta de crédito.  </td>
  </tr>
   <tr>
    <td>10_trabajador_e (2)</td>
    <td>Se cambia el nombre de "10_trabajador" a "10_trabajador_e". </td>
    <td>Variación de la ventana "10_trabajador_e" con una advertencia al no ingresar datos válidos.  </td>
  </tr>
  <tr>
    <td> 1_registro_cliente </td>
    <td> Se agrega la opción para agregar el número de teléfono del cliente. </td>
    <td> Se solicitan datos generales (nombres, apellidos, teléfono y correo electrónico). y </td>
  </tr>
  <tr>
    <td> 2_registro_cliente </td>
    <td> Sin cambios.  </td>
    <td> Se solicita una identificación (INE o cartilla militar) y una fotografía para continuar el proceso. </td>
  </tr>
  <tr>
    <td> 3_registro_cliente </td>
    <td> Sin cambios.  </td>
    <td> Ventana de donde se exponen los términos y condiciones que tienen que ser aceptados para completar el registro.  </td>
  </tr>
  <tr>
    <td> 4_registro_cliente </td>
    <td> Sin cambios.  </td>
    <td> Ventana donde se finaliza el registro del trabajador y se da aviso para que el trabajador revise su correo. </td>
  </tr>
  <tr>
    <td>Inicio_cliente </td>
    <td> Nueva ventana.  </td>
    <td> Ventana de inicio específico para el cliente con datos predeterminados.  </td>
  </tr>
  <tr>
    <td>Recuperación_contraseña_cliente  </td>
    <td> Nueva ventana.  </td>
    <td> Ventana de recuperación de contraseña específica para el cliente.  </td>
  </tr>
  <tr>
    <td>Permiso de ubicación_cliente  </td>
    <td> Nueva ventana  </td>
    <td> Ventana específica del cliente para permitir que la aplicación tenga acceso a la ubicación.  </td>
  </tr>
  <tr>
    <td>1_cliente  </td>
    <td> Se agrega el icono de una lupa en la parte superior para buscar trabajadores y se agrega el número de teléfono del cliente en su perfil.  </td>
    <td> Ventana principal del cliente donde se encuentran datos de contacto, calificación y el buscador de trabajadores. </td>
  </tr>
  <tr>
    <td>2_cliente  </td>
    <td> Sin cambios.  </td>
    <td> Buscador de trabajadores. </td>
  </tr>
  <tr>
    <td>2_cliente (2) </td>
    <td> Sin cambios.  </td>
    <td> Variación de la ventana "2_cliente" sin número de teléfono. </td>
  </tr>
  <tr>
    <td>3_cliente  </td>
    <td> El clic a la fotografía, al ícono de perfil, al nombre o a las estrellas llevan al perfil del trabajador.  </td>
    <td>Ventana de resultados de una búsqueda.  </td>
  </tr>
  <tr>
    <td>4_cliente  </td>
    <td> Se cambia el botón de "Review" por "reseñas".  </td>
    <td>Perfil del trabajador desde el punto de vista de un cliente con la opción de contratar.  </td>
  </tr>
  <tr>
    <td>5_cliente  </td>
    <td> Se cambia el botón de "Review" por "reseñas".  </td>
    <td>Ventana de reseña del trabajador desde el punto de vista del cliente.  </td>
  </tr>
  <tr>
    <td>6_cliente  </td>
    <td>Sin cambios</td>
    <td>Ventana de chat con un trabajador.  </td>
  </tr>
  <tr>
    <td>7_cliente  </td>
    <td>Sin cambios</td>
    <td>Ventana con un aviso emergente después de contratar a un trabajador.  </td>
  </tr>
  <tr>
    <td>8_cliente  </td>
    <td>Se agrega el icono de una lupa en la parte superior para buscar trabajadores y se agrega el número de teléfono del cliente en su perfil. </td>
    <td>Aviso de la confirmación de la contratación.  </td>
  </tr>
   <tr>
    <td>8_cliente (2)  </td>
    <td>Se agrega el icono de una lupa en la parte superior para buscar trabajadores y se agrega el número de teléfono del cliente en su perfil.  </td>
    <td>Variación de la ventana "8_cliente" con la notificación del rechazo del trabajo. </td>
  </tr>
   <tr>
    <td>8_cliente (3)  </td>
    <td>Se agrega el icono de una lupa en la parte superior para buscar trabajadores y se agrega el número de teléfono del cliente en su perfil. </td>
    <td>variación de la ventana "8_cliente" con la notificación de la cancelación del trabajo. </td>
  </tr>
   <tr>
    <td>9_cliente  </td>
    <td>Se cambia el símbolo de más por tres puntos.  </td>
    <td>Ventana de contratos activos donde se puede finalizar o cancelar un trabajo y reportar a un trabajador.  </td>
  </tr>
   <tr>
    <td>10_cliente  </td>
    <td>Sin cambios.  </td>
    <td>Ventana de chats con los trabajadores  </td>
  </tr>
   <tr>
    <td>11_cliente  </td>
    <td>Sin cambios.  </td>
    <td>Ventana para eliminar chats.  </td>
  </tr>
   <tr>
    <td>12_cliente  </td>
    <td>Sin cambios. </td>
    <td>Ventana de chat con un trabajador.  </td>
  </tr>
   <tr>
    <td>13_cliente  </td>
    <td>Sin cambios. </td>
    <td>Ventana de contratos activos vacía  </td>
  </tr>
   <tr>
    <td>14_cliente  </td>
    <td>Sin cambios. </td>
    <td>Ventana de chats vacía.  </td>
  </tr>
   <tr>
    <td>15_cliente  </td>
    <td>Sin cambios. </td>
    <td>Ventana de eliminación de chats vacía.  </td>
  </tr>
   <tr>
    <td>16_cliente  </td>
    <td>Se agrega la opción de cambiar el número de teléfono.</td>
    <td>Ventana para cambiar los datos del cliente. </td>
  </tr>
   <tr>
    <td>16_cliente (2) </td>
    <td>Se elimina la foto del cliente.</td>
    <td>Variación de la ventana "16_cliente" con una advertencia para que llene los campos faltantes. </td>
  </tr>
   <tr>
    <td>1_registro_trabajador/cliente_e </td>
    <td>Se cambia el nombre de "1_registro" a"1_registro_trabajador/cliente_e". </td>
    <td>Ventana con una advertencia al ingresar datos erróneos en el inicio de sesión.</td>
  </tr>
   <tr>
<td>Recuperación_contraseña_trabajador/cliente_e </td>
    <td>Se cambia el nombre de "Recuperación_contraseña" a "Recuperación_contraseña_trabajador/cliente_e".  </td>
    <td> Ventana con una advertencia al ingresar un correo no registrado durante el proceso de recuperación de contraseña. </td>
  </tr>
   <tr>
    <td>1_registro_trabajador/cliente  </td>
    <td>Se cambia el nombre de "1_registro_trabajador/ciente" a "1_registro_trabajador/ciente_e". </td>
    <td>Ventana de advertencia al iniciar a configurar una cuenta cuando no se introduce un correo válido.  </td>
  </tr>
   <tr>
    <td>1_registro_trabajador/cliente (2)  </td>
    <td>Se cambia el nombre de "1_registro_trabajador/ciente" a "1_registro_trabajador/ciente_e". </td>
    <td>Ventana de advertencia al iniciar a configurar una cuenta cuando no llenan los campos correspondientes.  </td>
  </tr>
   <tr>
    <td>2_registro_trabajador/cliente_e  </td>
    <td>Se cambia el nombre de "2_registro_trabajador/cliente " a "2_registro_trabajador/cliente_e ". </td>
    <td>Ventana de advertencia al no ingresar los archivos de identificación y fotografía.  </td>
  </tr>
   <tr>
    <td>3_registro_trabajador_e </td>
    <td>Se cambia el nombre de "3_registro_trabajador" a "3_registro_trabajador_e ".  </td>
    <td>Ventana de advertencia al iniciar a configurar una cuenta de trabajador cuando no se llenan los campos correspondientes.  </td>
  </tr>
   <tr>
    <td>3_registro_trabajador_e (2) </td>
    <td>Se cambia el nombre de "3_registro_trabajador" a "3_registro_trabajador_e ".  </td>
    <td>Ventana de advertencia al iniciar a configurar una cuenta de trabajador cuando no se llenan todos los campos correspondientes. </td>
  </tr>
   <tr>
    <td>4_registro_trabajador_e </td>
    <td>Se cambia el nombre de "4_registro_trabajador " a "4_registro_trabajador_e". </td>
    <td>Ventana de advertencia al no llenar los datos correspondientes de la tarjeta de crédito al crear una cuenta de trabajador. </td>
  </tr>
   <tr>
    <td>4_registro_trabajador_e (2)</td>
    <td>Se cambia el nombre de "4_registro_trabajador " a "4_registro_trabajador_e". </td>
    <td>Ventana de advertencia al no llenar todos los datos correspondientes de la tarjeta de crédito al crear una cuenta de trabajador. </td>
  </tr>
   <tr>  <td>5_registro_trabajador/3_registro_cliente_e </td>
    <td>Se cambia el nombre de "5_registro_trabajador/3_registro_cliente" a "5_registro_trabajador/3_registro_cliente_e ". </td>
    <td>Ventana de advertencia al no aceptar los términos y condiciones para crear una cuenta. </td>
  </tr>
</table>



[^1]: FOCUX. (28 de marzo de 2022). Pruebas de usabilidad | Guía 2022 + Plantillas. *FOCOUX.* https://aprende-ux.focux.io/pruebas-de-usabilidad/
[^2]: Nacho Madrid. (28 de enero de 2020). *Métricas de usabilidad y experiencia de usuario.* Nacho Madrid. https://aprende-ux.focux.io/pruebas-de-usabilidad/