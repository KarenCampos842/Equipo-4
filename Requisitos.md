<h1>REQUISITOS</h1>


## Requerimientos funcionales
1. **Perfiles:** El sistema permitirá al usuario seleccionar un perfil (cliente o trabajador), con el cuál iniciará su registro a la aplicación.

2. **Registro del cliente:** Si el usuario ha seleccionado el perfil de cliente, solicitará al usuario nombre(s) y apellido(s), una identificación oficial con fotografía (credencial para votar o cartilla de servicio militar), una fotografía actual (imagen), un correo electrónico y aceptación de términos y condiciones.

3. **Registro del trabajador:** Si el usuario ha seleccionado el perfil de trabajador, el sistema mostrará un aviso en pantalla informándole del cobro mensual de una membresía por $75, teniendo un primer mes de prueba gratis con su registro en la aplicación. El sistema solicitará al usuario nombre(s) y apellido(s), una identificación oficial con fotografía (credencial para votar o cartilla de servicio militar), una fotografía actual (imagen), un número telefónico, un correo electrónico, zona de trabajo (seleccionar municipio de una lista presentada por el sistema), su oficio (seleccionar de una lista presentada por el sistema), descripción breve (255 caracteres) de los trabajos que realiza (por ejemplo: frenos ABS, alineación y balanceo), un número de tarjeta de crédito, fecha (mes, año) de vencimiento de la tarjeta (seleccionar de una lista presentada por el sistema), CVV, y aceptación a de términos y condiciones.

4. **Cobro de membresía:**  Cumplido el mes de prueba gratis en la aplicación, el sistema cobrará mensualmente de la tarjeta proporcionada por el trabajador $75 correspondientes a la membresía hasta la cancelación de la cuenta.

5. **Creación de contraseña:** El sistema creará una contraseña y para el cliente o trabajador que será enviada al correo electrónico proporcionado. 

6. **Comentarios:** El sistema permitirá al cliente comentar sobre la calidad del servicio en el perfil del trabajador.

7. **Calificaciones:** Basado en una escala de cinco estrellas, el sistema permitirá al usuario (cliente o trabajador) calificar la calidad de su experiencia (una estrella es la calificación más baja, cinco estrellas la máxima). Su calificación será el promedio de todas las calificaciones recibidas.

8. **Creación del perfil de cliente:** El sistema creará el perfil del cliente, el cual contendrá: fotografía del usuario, nombre(s) y apellido(s) calificación, correo y número telefónico  (los últimos dos elementos serán únicamente visibles para el cliente). 

9. **Creación del perfil de trabajador:** El sistema creará el perfil del trabajador, el cual contendrá: fotografía del usuario, nombre(s) y apellido(s), oficio, descripción de los trabajos que realiza, zona de trabajo, calificación, comentarios de clientes, número telefónico, correo, número de tarjeta, CVV y fecha de vencimiento de la tarjeta (los últimos cuatro elementos serán únicamente visibles para el trabajador). 
 
10. **Inicio de sesión:**  El usuario podrá iniciar sesión proporcionando el correo con el que se registró la y la contraseña asignada. Al entrar, el sistema solicitará su ubicación. 

11. **Búsqueda:** El sistema mostrará al cliente una barra de búsqueda en la que podrá ingresar un oficio, por ejemplo: “mecánico”.

12. **Filtro:** El sistema filtrará los perfiles de los trabajadores con base a la búsqueda del cliente. Mostrará en pantalla un listado de trabajadores, filtrados con base en en el oficio de búsqueda y ubicación (municipio más cercano al cliente). El listado será al azar en cuanto a calificaciones,

13. **Elección del trabajador:** El cliente podrá seleccionar el trabajador que prefiera de la lista desplegada, visualizar su perfil, elegir activar el chat con el trabajador y contratar su servicio.

14. **Chat:** El sistema contará con una opción de chat, el cual será activado por el cliente, por el medio del cual, trabajador y cliente podrán acordar precios, trabajos específicos, agendar citas y subir imágenes.

15. **Contratación del servicio:** El sistema mostrará al cliente una opción para contratar el servicio. Cuando el cliente elija esta opción, se hará llegar una notificación al trabajador preguntando si desea o no aceptar el trabajo. La notificación irá acompañada con una opción para visualizar el perfil y la ubicación del cliente. El sistema reconocerá la contratación del servicio cuando el trabajador lo acepte.

16. **Calificación del cliente:** Una vez que se ha contratado el servicio, el sistema mostrará al trabajador un apartado para calificar al cliente.

17. **Finalización del contrato:** Una vez que se ha contratado el servicio, el sistema mostrará al cliente una opción para indicar cuando el trabajo se haya realizado. Al seleccionarla, se mostrará una ventana que le permitirá al cliente calificar al trabajador, levantar un reporte y/o publicar un comentario. 

18. **Reportes:** Cuando el cliente levante un reporte, el sistema notificará al trabajador. Si el trabajador acumula 5 reportes, su cuenta será cancelada.

19. **Cancelación del servicio:** Una vez contratado el servicio, el sistema mostrará al cliente y trabajador una opción para cancelarlo. Si el usuario selecciona la opción, el sistema solicitará la razón de la cancelación. Si el usuario realiza 3 cancelaciones consecutivas, su cuenta será cancelada.

20. **Cancelación de la cuenta por parte del trabajador:** El sistema permitirá al usuario la cancelación de su cuenta en cualquier momento.

21. . **Recuperación de contraseña:**  El usuario podrá recuperar su contraseña. El sistema solicitará al usuario un correo al que enviará la contraseña. 

22. **Modificación de perfil:** Como cliente, el usuario podrá modificar nombre(s) y apellido(s) y su fotografía. Como trabajador, el usuario podrá modificar nombre(s) y apellido(s), su fotografía, zona de trabajo, número de tarjeta, CVV y fecha de vencimiento de la tarjeta.


## Requerimientos no funcionales

23. Solo funcionará en dispositivos móviles con Android 8 y IOS 11 en adelante (por los requisitos que manejaremos y las funciones del sistema).

24.  El sistema debe asegurarse de que los trabajadores no cometan suplantación de identidad o estafa (solicitando una identificación oficial con fotografía y tomar una fotografía actual del trabajador para tenerla de foto de perfil y verificando que sean la misma persona).
 
25.  Los datos modificados en los perfiles de los trabajadores, en la base de datos deben ser actualizados para todos los usuarios que ingresen a los perfiles en menos de 10 segundos de haber sido actualizados.
 
26.  El sistema debe estar disponible cuando se requiera (darle mantenimiento solo en horarios de baja demanda).

27.  El sistema debe ser intuitivo, gráfico y agradable para la mayoría de usuarios (colocando imágenes fáciles de entender y simbología básica).

28.  El sistema no deberá de ocupar más de 500 MB de almacenamiento interno de cada usuario.

29.  Los servicios ofrecidos por los trabajadores deben ser legales (estar dentro de los servicios permitidos por las leyes y lo podremos resolver verificando los servicios ofrecidos continuamente).

30. El sistema deberá manejar correcta y extensamente los idiomas del Español e Inglés.

31. Se debe de contar en todo momento un respaldo ante desastres en la nube para el sistema en desarrollo.

32. Cada 2 semanas se deberán de producir reportes gerenciales en los que se mostrará el esfuerzo invertido en cada uno de los componentes del nuevo sistema.

33. El sistema no mostrará datos personales entre usuarios y trabajadores que no estén incluidos en los perfiles públicos y con previa autorización de ellos.





## Priorización
###  Tabla MosCow[^1]

| Must Have| Should Have | Could Have |Won't Have|
|---------|---------|---------|---------|
|1, 2, 3, 4, 5, 8, 9, 10, 11, 12, 13, 14, 15, 18, 19, 21, 22, 24, 25, 26, 27, 29, 31, 33|6, 7, 16, 17, 20, 28, 30, 32|23||




## Artefactos

### Product Backlog

### Historias de usuario[^2]

<table align=center>  
   <tr>  
      <th>Historia de usuario #1</th>  
      <th>Registro de trabajador</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td> usuario </td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td> poder registrarme en WorkFlash como trabajador</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td> promocionar mi trabajo y conseguir más clientes.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
            <li>Comprobar que se ha seleccionado el perfil ""trabajador".</li>
                <li>Comprobar que existen mínimo un nombre y un apellido.</li>
                 <li>Comprobar que existen 10 dígitos para el número telefónico. </li>
                 <li>Comprobar que existe texto antes y después de @ para el correo.</li>
                  <li>Comprobar que existe un elemento (imagen o PDF) como identificación oficial con fotografía.</li>
                  <li>Comprobar que existe un elemento (imagen) en el apartado de fotografía actual.</li>
                 <li>Comprobar que se ha seleccionado un municipio (zona de trabajo) de la lista proporcionada.</li>
                 <li>Comprobar que se ha seleccionado un oficio de la lista proporcionada.</li>
                <li>Comprobar la longitud de la descripción de los trabajos que realiza el trabajador (máximo 255 caracteres) </li>
                <li>Comprobar la longitud del número de tarjeta de crédito (de 13 a 18 dígitos).</li>
                <li>Comprobar la longitud del CVV (de 3 a 4 dígitos).</li>
                <li>Comprobar que se ha seleccionado una fecha de vencimiento (mes, año) de la tarjeta de crédito.</li>
                <li>Comprobar la aceptación de términos y condiciones.</li>
                <li>Comprobar el envío de contraseña al correo proporcionado.</li>
           </ul>
     </td> 
   </tr>
 </table>      
 
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #2</th>  
      <th>Registro de cliente</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>usuario</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td> poder registrarme en WorkFlash como cliente</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td> encontrar trabajadores de forma rápida.</td> 
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
 
<br>

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

<table align=center>  
   <tr>  
      <th>Historia de usuario #4</th>  
      <th>Perfil de trabajador</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>trabajador</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td> visualizar y modificar mi perfil</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td> verificar mi información o actualizar datos.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el trabajador pueda visualizar y editar nombre(s) y apellido(s).</li>
         <li>Comprobar que el trabajador pueda visualizar su correo, pero no editarlo.</li>
          <li>Comprobar que el trabajador pueda visualizar su fotografía y reemplazarla.</li>         
          <li>Comprobar que el trabajador pueda visualizar y editar su número telefónico. </li>
           <li>Comprobar  que el trabajador pueda visualizar y editar su zona de trabajo</li>
            <li>Comprobar que el trabajador pueda visualizar su oficio, pero no editarlo.</li>
            <li>Comprobar que el trabajador pueda visualizar y editar la descripción de los trabajos que realiza</li>
           <li>Comprobar que el trabajador pueda visualizar y editar el número de tarjeta de crédito.</li>
            <li>Comprobar que el trabajador pueda visualizar y editar el CVV.</li>
            <li>Comprobar que el trabajador pueda visualizar y editar la fecha de vencimiento (mes, año) de la tarjeta de crédito.</li>
           <li>Comprobar que el trabajador pueda visualizar su calificación, pero no editarla.</li>
         <li>Comprobar que el trabajador pueda visualizar los comentarios de sus clientes, pero no editarlos.</li>    
         <li>Comprobar que los cambios realizados en el perfil se vean reflejados en la base de datos (sean reemplazados y guardados). </li>                   
     </td> 
   </tr>
   </table>      
    
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #5</th>  
      <th>Perfil de cliente</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>cliente</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td> visualizar y modificar mi perfil</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td> verificar mi información o actualizar datos.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el cliente pueda visualizar  y editar nombre(s) y apellido(s).</li>
         <li>Comprobar que el cliente pueda visualizar su correo, pero no editarlo.</li>
          <li>Comprobar que el cliente pueda visualizar y reemplazar su fotografía.</li>          
           <li>Comprobar que el cliente pueda visualizar su calificación, pero no editarla.</li>
       <li>Comprobar que los cambios realizados en el perfil se vean reflejados en la base de datos (sean reemplazados y guardados). </li>
     </td> 
   </tr>
    </table>      
    
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #6</th>  
      <th>Barra de búsqueda y filtro</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>cliente</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder buscar a trabajadores de un oficio en específico y visualizar aquellos cercanos a mí </td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>identificar todas las opciones disponibles.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el cliente pueda visualizar una lista de oficios al seleccionar la barra de búsqueda.</li>
                <li>Comprobar que el cliente pueda seleccionar un oficio de la lista desplegada.</li>
               <li>Comprobar que el cliente pueda visualizar una lista de trabajadores del oficio que seleccionó cercanos a su ubicación (municipios cercanos).</li>          
           <li>Comprobar que el cliente pueda visualizar los nombre(s) y apellido(s), municipio (zona de trabajo) y calificación de cada trabajador en la lista.</li>
     </td> 
   </tr>
 <tr>  
      <td><b>Pasos</b></td>  
       <td> 
           <ul>
                <li>abrir la app.</li>
                <li>buscar la profesion que requiera</li>
     </td> 
   </tr>
 <tr>  
      <td><b>expciones</b></td>  
       <td> 
           <ul>
                <li>si el usuario escribe mal el nombre ponerle un mensaje de que esta profesión no esta</li>
                <li>si el excede el numero de caracter  ponemos un mensaje de que esa profesion no se encuentra</li>
                 <li>si el usuario pone una profesion que no este  ponerle un mensaje de que esta profesión no esta</li>
     </td> 
   </tr>
 <tr>  
      <td><b>Comentario</b></td>  
       <td> 
           <ul>
                <li>el numero maximo de caracteres sera de 150 </li>
     </td> 
   </tr>

   </table>      
    
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #7</th>  
      <th>Elección del trabajador</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>cliente</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder visualizar los perfiles de los trabajadores  </td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>identificar la opción que más se ajuste a mis necesidades.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el cliente pueda visualizar el perfil del trabajador al seleccionar uno de la lista desplegada (resultado de la búsqueda y filtro de trabajadores).</li>
                <li>Comprobar que el cliente pueda visualizar del perfil del trabajador: nombre(s) y apellido(s), fotografía, oficio, descripción de los trabajos que realiza, zona de trabajo, calificación, comentarios de clientes y  número telefónico. 
                </li>
               <li>Comprobar que el cliente no pueda visualizar del perfil del trabajador: correo, número de tarjeta, CVV y fecha de vencimiento de la tarjeta. </li>          
            </tr>
            <td><b>Pasos</b></td>
            <td><ul>
            <li>entrar a la app</li>
			<li>poner en el buscador el oficio que requieres</li>
			<li>filtrar por las diferentes opciones de busqueda o recomendacion</li>
			<li>elegir uno</li>
</ul></td>
  <tr>  
      <td><b>expeciones</b></td>  
       <td> 
           <ul>
                <li>si el cliente ya contrato a uno no puede contratar a otro</li>
                <li>el cliente a la hora de checar el perfil de trabajo solo pueda checar su oficio, nombre y algunas de sus obras que ha echo
                </li>
                </tr>
  <tr>  
      <td><b>comentarios</b></td>  
       <td> 
           <ul>
                <li>el campo de visiualizacion del trabajor dependera de el, que tanto deseara a conocerce y sus trabajos o datos</li>
               
  </tr>
   </table>      
             
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #8</th>  
      <th>Chat</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>cliente</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder conversar con el trabajador que elija</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>hacer cotizaciones, llegar a acuerdos, agendar citas. </td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que cuando el cliente seleccione la opción de chat, la función se habilite. </li>
                <li>Comprobar que el receptor reciba los mensajes del emisor.
                </li>
               <li>Comprobar que el chat permita compartir imágenes. </li>          
            </tr>
 </table>      
 
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #9</th>  
      <th>Contratación del servicio</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>cliente</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder contratar al trabajador de mi elección</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>que me pueda realizar algún servicio. </td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el cliente ha seleccionado la opción de "contratar servicio" </li>
                <li>Comprobar que el trabajador ha recibido una notificación de un nuevo trabajo.
                </li>
               <li>Comprobar que el trabajador ha aceptado el trabajo. </li> 
         <li>Comprobar que el cliente ha sido notificado sobre el estado de la contratación del servicio (exitosa o rechazada). </li>           
            </tr>
             <tr>  
      <td><b>Pasos</b></td>  
       <td> 
           <ul>
                <li>Cuando encuentre al trabajador de mi agardo selecionarlo </li>
                <li>ponerle confirmar
                </li>
               <li>esperar que el trabajor acepte el trabajo </li> 
         <li>esperar la notificacion de su llegada </li>           
            </tr>
                <tr>  
      <td><b>Excepciones</b></td>  
       <td> 
           <ul>
                <li>si elegio mal o cometió error poner botón de cancelación y a la causa </li>
                <li>si el trabajador acepto el trabajo arrojar un pop pap de la notificacion en cuanto tiempo llegara
                </li>
               <li>si no llega la notificacion reportarlo en soporte </li> 
         <li>si el trabajor  acepto por equivocación poner un boton de cancelar de 5 minutos después de ese tiempo desaparecerá el boton </li>           
            </tr>
                       <tr>  
      <td><b>Comentario</b></td>  
       <td> 
           <ul>
                <li>si elegio mal o cometió error poner botón de cancelación y a la causa </li>
         
            </tr>
         </table>      
             
  <br>
            
<table align=center>  
   <tr>  
      <th>Historia de usuario #10</th>  
      <th>Aceptación del trabajo</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>trabajador</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder elegir aceptar o rechazar un trabajo</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>proteger mis intereses.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el trabajador ha recibido una notificación de un nuevo trabajo.
                </li>
               <li>Comprobar que el trabajador puede visualizar nombre(s) y apellido(s), ubicación y calificación del cliente. </li> 
         <li>Comprobar que el trabajador ha seleccionado aceptar o rechazar el trabajo. </li>
         <li>Comprobar que el cliente ha sido notificado sobre el estado de la contratación del servicio (exitosa o rechazada). </li>             
            </tr>
             </table>      
             
  <br>
           
<table align=center>  
   <tr>  
      <th>Historia de usuario #11</th>  
      <th>Calificación del cliente</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>trabajador</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder calificar a mi cliente</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>evaluar su formalidad y buen trato.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el espacio para calificar al cliente ha aparecido después de la contratación exitosa del servicio.
                </li>
         <li>Comprobar que el trabajador ha seleccionado una determinada cantidad de estrellas (mínimo una, máximo cinco) para calificar al cliente. </li>
         <li>Comprobar que la asignación de estrellas ha sido registrada en la base de datos y promediada con las calificaciones preexistentes. </li>             
            </tr>
        </table> 
                  
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #12</th>  
      <th>Finalización del contrato</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>cliente</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder indicar que el servicio que contraté se concluyó satisfactoriamente</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>terminar el proceso de contratación y evaluar al trabajador.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que la opción para finalizar el contrato ha aparecido después de la contratación exitosa del servicio.
                </li>
                <li>Comprobar que el cliente ha seleccionado la opción de finalizar contrato. </li>
        <li>Comprobar que los espacios para calificar, comentar y reportar se han habilitado al seleccionar la opción de finalizar contrato.</li>
         <li>Comprobar que el cliente ha seleccionado una determinada cantidad de estrellas (mínimo una, máximo cinco) para calificar al cliente. </li>
     <li>Comprobar que la asignación de estrellas ha sido registrada en la base de datos y promediada con las calificaciones preexistentes. </li>      
         <li>Comprobar que el comentario y reporte se han guardado en la base de datos (de ser el caso). </li> 
       <li>Comprobar que el trabajador ha sido notificado sobre el reporte (de ser el caso) </li>                 
            </tr>
 </table>      

<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #13</th>  
      <th>Reportes</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>administrador del sistema</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>saber el número de reportes que tiene un trabajador </td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>determinar su permanencia en la aplicación. </td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el sistema lleve la cuenta de los reportes levantados contra cada trabajador.
                </li>
                <li>Comprobar que el sistema cancele la cuenta de un trabajador cuando el número de reportes sea igual a cinco.</li>
         <li>Comprobar que el perfil del trabajador ha sido eliminado de la base de datos. </li>             
            </tr>
 </table>     
   
<br>

<table align=center>  
   <tr>  
      <th>Historia de usuario #14</th>  
      <th>Cancelación de la cuenta (trabajador)</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>trabajador</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder cancelar mi cuenta en el momento en que lo desee</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>dejar de utilizar el servicio que brinda WorkFlash</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el sistema tenga una opción para cancelar la cuenta.
                </li>
                <li>Comprobar que el trabajador seleccione la opción de cancelar cuenta.</li>
         <li>Comprobar que el sistema pare de cobrar la membresía.</li>
    <li>Comprobar que el perfil del trabajador ha sido eliminado de la base de datos al seleccionar  la opción de cancelar cuenta.</li>                    
            </tr>
 </table>   
      
 <br>    
<table align=center>  
   <tr>  
      <th>Historia de usuario #15</th>  
      <th>Cobro de membresía</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>administrador de la aplicación</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>saber cuando se cumple el periodo de un mes de prueba gratis </td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>comenzar el cobro mensual por el servicio.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el sistema detecte correctamente el mes de prueba gratis.
                </li>
                 <li>Comprobar que el sistema realice el cobro automático de la membresía de $75 finalizado el mes de prueba gratis hasta que el trabajador cancele su cuenta.
                </li>
 </table>
 <br>    
<table align=center>  
   <tr>  
      <th>Historia de usuario #16</th>  
      <th>Recuperación de contraseña</th> 
   </tr> 
    <tr>  
      <td><b>Como</b></td>  
       <td>usuario de WorkFlash</td> 
   </tr> 
    <tr>  
      <td><b>Quiero</b></td>  
       <td>poder recuperar mi contraseña</td> 
   </tr> 
     <tr>  
      <td><b>Para</b></td>  
       <td>volver a acceder a los beneficios de WorkFlash.</td> 
   </tr> 
  <tr>  
      <td><b>Criterios de aceptación</b></td>  
       <td> 
           <ul>
                <li>Comprobar que el usuario seleccione la opción de recuperar contraseña.
                </li>
        <li>Comprobar que el sistema solicite un correo para recuperación de contraseña.
                </li>
                 <li>Comprobar que existe texto antes y después de @ para el correo.</li>
                 <li>Comprobar que se ha enviado la contraseña al correo proporcionado.</li>
 </table>      
 
  ### Casos de uso
  
   ### Diagrama de caso de uso

   ### Sprint backlog
https://github.com/KarenCampos842/Equipo-4/blob/Segunda-Entrega/Gestion_del_Proceso.md#sprint-backlog

[^1]:Simões, C. (14 de julio de 2020). MoSCoW. ¿Qué es y cómo priorizar en el desarrollo de tu aplicación? *ITDO*. https://www.itdo.com/blog/moscow-que-es-y-como-priorizar-en-el-desarrollo-de-tu-aplicacion/

[^2]:Scrum Manager®. (2018). *Historias de Usuario.* https://www.scrummanager.com/files/historias_usuario_scrum_manager.pdf

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4ODU5NTI3MjEsLTUwOTc1MzQ0NiwtNz
UzOTM0Mzg2LC0xMjAwOTE0MDU4XX0=
-->