<h1>REQUISITOS</h1>


## Requerimientos funcionales
RF-1. **Perfiles:** El sistema permitirá al usuario seleccionar un perfil (cliente o trabajador), con el cuál iniciará su registro a la aplicación.

RF-2. **Registro del cliente:** Si el usuario ha seleccionado el perfil de cliente, solicitará al usuario nombre(s) y apellido(s), una identificación oficial con fotografía (credencial para votar o cartilla de servicio militar), una fotografía actual (imagen), un correo electrónico y aceptación de términos y condiciones.

RF-3. **Registro del trabajador:** Si el usuario ha seleccionado el perfil de trabajador, el sistema mostrará un aviso en pantalla informándole del cobro mensual de una membresía por $75, teniendo un primer mes de prueba gratis con su registro en la aplicación. El sistema solicitará al usuario nombre(s) y apellido(s), una identificación oficial con fotografía (credencial para votar o cartilla de servicio militar), una fotografía actual (imagen), un número telefónico, un correo electrónico, zona de trabajo (seleccionar municipio de una lista presentada por el sistema), su oficio (seleccionar de una lista presentada por el sistema), descripción breve (255 caracteres) de los trabajos que realiza (por ejemplo: frenos ABS, alineación y balanceo), un número de tarjeta de crédito, fecha (mes, año) de vencimiento de la tarjeta (seleccionar de una lista presentada por el sistema), CVV, y aceptación a de términos y condiciones.

RF-4. **Cobro de membresía:**  Cumplido el mes de prueba gratis en la aplicación, el sistema cobrará mensualmente de la tarjeta proporcionada por el trabajador $75 correspondientes a la membresía hasta la cancelación de la cuenta.

RF-5. **Creación de contraseña:** El sistema creará una contraseña y para el cliente o trabajador que será enviada al correo electrónico proporcionado. 

RF-6. **Comentarios:** El sistema permitirá al cliente comentar sobre la calidad del servicio en el perfil del trabajador.

RF-7. **Calificaciones:** Basado en una escala de cinco estrellas, el sistema permitirá al usuario (cliente o trabajador) calificar la calidad de su experiencia (una estrella es la calificación más baja, cinco estrellas la máxima). Su calificación será el promedio de todas las calificaciones recibidas.

RF-8. **Creación del perfil de cliente:** El sistema creará el perfil del cliente, el cual contendrá: fotografía del usuario, nombre(s) y apellido(s) calificación, correo y número telefónico  (los últimos dos elementos serán únicamente visibles para el cliente). 

RF-9. **Creación del perfil de trabajador:** El sistema creará el perfil del trabajador, el cual contendrá: fotografía del usuario, nombre(s) y apellido(s), oficio, descripción de los trabajos que realiza, zona de trabajo, calificación, comentarios de clientes, número telefónico, correo, número de tarjeta, CVV y fecha de vencimiento de la tarjeta (los últimos cuatro elementos serán únicamente visibles para el trabajador). 
 
RF-10. **Inicio de sesión:**  El usuario podrá iniciar sesión proporcionando el correo con el que se registró la y la contraseña asignada. Al entrar, el sistema solicitará su ubicación. 

RF-11. **Búsqueda:** El sistema mostrará al cliente una barra de búsqueda en la que podrá ingresar un oficio, por ejemplo: “mecánico”.

RF-12. **Filtro:** El sistema filtrará los perfiles de los trabajadores con base a la búsqueda del cliente. Mostrará en pantalla un listado de trabajadores, filtrados con base en en el oficio de búsqueda y ubicación (municipio más cercano al cliente). El listado será al azar en cuanto a calificaciones,

RF-13. **Elección del trabajador:** El cliente podrá seleccionar el trabajador que prefiera de la lista desplegada, visualizar su perfil, elegir activar el chat con el trabajador y contratar su servicio.

RF-14. **Chat:** El sistema contará con una opción de chat, el cual será activado por el cliente, por el medio del cual, trabajador y cliente podrán acordar precios, trabajos específicos, agendar citas y subir imágenes.

RF-15. **Contratación del servicio:** El sistema mostrará al cliente una opción para contratar el servicio. Cuando el cliente elija esta opción, se hará llegar una notificación al trabajador preguntando si desea o no aceptar el trabajo. La notificación irá acompañada con una opción para visualizar el perfil y la ubicación del cliente. El sistema reconocerá la contratación del servicio cuando el trabajador lo acepte.

RF-16. **Calificación del cliente:** Una vez que se ha contratado el servicio, el sistema mostrará al trabajador un apartado para calificar al cliente.

RF-17. **Finalización del contrato:** Una vez que se ha contratado el servicio, el sistema mostrará al cliente una opción para indicar cuando el trabajo se haya realizado. Al seleccionarla, se mostrará una ventana que le permitirá al cliente calificar al trabajador, levantar un reporte y/o publicar un comentario. 

RF-18. **Reportes:** Cuando el cliente levante un reporte, el sistema notificará al trabajador. Si el trabajador acumula 5 reportes, su cuenta será cancelada.

RF-19. **Cancelación del servicio:** Una vez contratado el servicio, el sistema mostrará al cliente y trabajador una opción para cancelarlo. Si el usuario selecciona la opción, el sistema solicitará la razón de la cancelación. Si el usuario realiza 3 cancelaciones consecutivas, su cuenta será cancelada.

RF-20. **Cancelación de la cuenta por parte del trabajador:** El sistema permitirá al usuario la cancelación de su cuenta en cualquier momento.

RF-21. . **Recuperación de contraseña:**  El usuario podrá recuperar su contraseña. El sistema solicitará al usuario un correo al que enviará la contraseña. 

RF-22. **Modificación de perfil:** Como cliente, el usuario podrá modificar nombre(s) y apellido(s) y su fotografía. Como trabajador, el usuario podrá modificar nombre(s) y apellido(s), su fotografía, zona de trabajo, número de tarjeta, CVV y fecha de vencimiento de la tarjeta.


## Requerimientos no funcionales

RNF-23. Solo funcionará en dispositivos móviles con Android 8 y IOS 11 en adelante (por los requisitos que manejaremos y las funciones del sistema).

RNF-24.  El sistema debe asegurarse de que los trabajadores no cometan suplantación de identidad o estafa (solicitando una identificación oficial con fotografía y tomar una fotografía actual del trabajador para tenerla de foto de perfil y verificando que sean la misma persona).
 
RNF-25.  Los datos modificados en los perfiles de los trabajadores, en la base de datos deben ser actualizados para todos los usuarios que ingresen a los perfiles en menos de 10 segundos de haber sido actualizados.
 
RNF-26.  El sistema debe estar disponible cuando se requiera (darle mantenimiento solo en horarios de baja demanda).

RNF-27.  El sistema debe ser intuitivo, gráfico y agradable para la mayoría de usuarios (colocando imágenes fáciles de entender y simbología básica).

RNF-28.  El sistema no deberá de ocupar más de 500 MB de almacenamiento interno de cada usuario.

RNF-29.  Los servicios ofrecidos por los trabajadores deben ser legales (estar dentro de los servicios permitidos por las leyes y lo podremos resolver verificando los servicios ofrecidos continuamente).

RNF-30. El sistema deberá manejar correcta y extensamente los idiomas del Español e Inglés.

RNF-31. Se debe de contar en todo momento un respaldo ante desastres en la nube para el sistema en desarrollo.

RNF-32. Cada 2 semanas se deberán de producir reportes gerenciales en los que se mostrará el esfuerzo invertido en cada uno de los componentes del nuevo sistema.

RNF-33. El sistema no mostrará datos personales entre usuarios y trabajadores que no estén incluidos en los perfiles públicos y con previa autorización de ellos.





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

</table>
 <br>    

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
                <li>Comprobar que el trabajador pueda visualizar nombre(s) y apellido(s).</li>
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
                <li>Comprobar que el cliente pueda visualizar nombre(s) y apellido(s).</li>
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
        <li>Confirmar correo electrónico y asegurase de que exista en la base de datos.
                </li>
                 <li>Comprobar que el sistema envíe un correo electrónico con el enlace de restablecimiento de contraseña a la dirección registrada del usuario.</li>
                 <li>Comprobar que se ha enviado el enlace de restablecimiento de contraseña al correo proporcionado.</li>
 </table>      
 
  ### Casos de uso
  <table align=center>  
   <tr>
     <th>CU-01</th>  
      <th colspan="2">Registro del trabajador</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (29/10/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El trabajador deberá de contar con una tarjeta de débito o crédito con fondos para comprobar que se pueda cobrar en los próximos meses, y también no haberse registrado antes</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema deberá registrar a todo trabajador con éxito, siendo rápido y eficiente.</td> 
   </tr> 
     <tr>  
      <td rowspan="15"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El trabajador debe seleccionar el icono de registrarse para comenzar su registro</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>Debe seleccionar en el icono de trabajador</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>Se le llevará a una ventana para llenar con sus datos correspondientes como: Su nombre completo, un correo electrónico y un número de teléfono. Una vez llenado los datos correctos, le da en el botón de "Continuar"</td> 
   </tr> 
   </tr> 
  <tr>  
  <td>4</td> 
   <td> Posteriormente se le llevará a una ventana en la que deberá elegir una opción de identificación oficial como: Cartilla milita o INE. Subir una foto o un archivo de la seleccionada o poder tomar una foto al momento de la identificación </td> 
   </tr> 
    </tr> 
  <tr>  
  <td>5</td> 
   <td> Deberá tomarse una foto en el momento que será usada para su foto de perfil del trabajador, una vez ya tomada le dará en el botón "continuar"</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>6</td> 
   <td> Se le llevará a otra ventana en la que completará su registro llenando los datos que aparecerán en su perfil como: Los municipios o colonias en los que le gustaría trabajar más, asi como su profesión y de los servicios o habilidades que puede ofrecer, una vez concluido le dará en "continuar" </td> 
   </tr> 
    </tr> 
  <tr>  
  <td>7</td> 
   <td> Tendrá que registrar una tarjeta de crédito o débito en la siguiente ventana para obtener el primer mes gratis y se le cobre periódicamente los 75 pesos mensuales de la membresía, tendrá que llenar los datos de la tarjeta como el número, su fecha de caducidad y el cvv. Una vez comprobado que la tarjeta cuenta con los fondos suficientes, se le devolverá el dinero y el usuario le dará en "continuar"</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>8</td> 
   <td>Le aparecerán los términos y condiciones que el trabajador deberá leer y aceptar para poder concluir su registro, posteriormente le saldrá una ventana en la que se le mostrará que su usuario y contraseña han sido enviados al correo electrónico proporcionados.</td> 
   </tr> 
  <tr>  
      <td><b>Postcondición</b></td>  
       <td colspan="2">Para poder ser registro válido deberán tener fondos en su tarjeta, y que las fotos de su perfil y de su identificación coincidan y así comprobar que sea una persona real
       </tr> 
       </td> 
    </tr> 
     <tr>  
      <td rowspan="4"><b>Excepciones</b></td>
     <tr>  
   <td>

- Si la identificación oficial y la fotografía no coinciden no podrá proceder el registro.
 - Si la tarjeta no contiene fondos suficientes, tendrá que ingresar otra o meterle fondos a la tarjeta.
 - Si el correo o el número de teléfono ya están registrados en el sistema no se podrá proceder.
 - Tendrá que llenar todos los campos solicitados en su llenado de datos, de lo contrario, no se podrá avanzar de ventana.
 - Si no acepta los términos y condiciones no podrá avanzar
 
 </table>                
  <br>    
<table align=center>  
   <tr>
     <th>CU-02</th>  
      <th colspan="2">Registro del usuario</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (29/10/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El usuario deberá de contar con un correo electrónico, una contraseña y también no haberse registrado antes</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema deberá registrar a todo usuario con éxito, siendo rápido y eficiente.</td> 
   </tr> 
     <tr>  
      <td rowspan="9"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El usuario debe seleccionar el icono de registrarse para comenzar su registro</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>Debe seleccionar en el icono de cliente</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>Se le llevará a una ventana para llenar con sus datos correspondientes como: Su nombre completo, un correo electrónico y un número de teléfono. Una vez llenado los datos correctos, le da en el botón de "Continuar"</td> 
   </tr> 
   </tr> 
  <tr>  
  <td>4</td> 
   <td> Posteriormente se le mostrarán los términos y condiciones que debe aceptar y dar en continuar para seguir concluir con su registro</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>5</td> 
   <td> Ya concluido su registro se le llevará a una ventana en la que se le mostrará que su usuario y contraseña han sido enviados al correo electrónico proporcionado.</td>

<br>

<table align=center>  
   <tr>
     <th>CU-3</th>  
      <th colspan="2">Auntentificación</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (30/10/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El usuario deberá de contar con un usuario y contraseña registrados previamente.</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema deberá autentificar rápidamente al usuario en caso de que sus datos sean correctos.</td> 
   </tr> 
     <tr>  
      <td rowspan="15"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El usuario debe rellenar el campo de usuario.</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>El usuario debe rellenar el campo de contraseña.</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>El usuario deberá presionar le botón de iniciar sesión para posteriormente ser dirigido al menu principal.</td> 
   </tr> 
   </tr> 
  <tr>
  <tr>  
      <td><b>Postcondición</b></td>  
       <td colspan="2">No será posible cambiar ni el nombre, ni el correo electrónico.
       </tr> 
       </td> 
    </tr> 
     <tr>  
      <td rowspan="4"><b>Excepciones</b></td>
     <tr>  
   <td>

-  Introducir un usuario inexistence impedirá el inicio de sesión.
- La contraseña introducida deberá ser correcta para el usuario introducido, en caso de escribirla incorrectamente no se podrá iniciar sesión.
- Si no se introducen caracteres válidos el sistema no no permitirá realizar el inicio de sesión.
 </table>
<br>

<table align=center>  
   <tr>
     <th>CU-4</th>  
      <th colspan="2">Perfil de trabajador</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (04/11/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El usuario deberá disponer de una cuenta de trabajador previamente registrada con la información correspondiente.</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema debe permitir al usuario trabajador visualizar su perfil y realizar ciertas modificar ciertos parámetros del mismo.</td> 
   </tr> 
     <tr>  
      <td rowspan="15"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El usuario accede al menu de su perfil a través de un botón en la pantalla principal</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>El usuario observa la información de su perfil y elige modificar su fotografía.</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>El usuario hace click en el icono de su fotografía y elige la opción cambiar imagen de perfil.</td> 
   </tr> 
   </tr> 
  <tr>  
  <td>4</td> 
   <td>El usuario puede elige entre sus imágenes de su galería o bien, se toma una.</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>5</td> 
   <td>El usuario presiona confirmar y regresa a su perfil.</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>6</td> 
   <td>El usuario observa su correo electrónico, oficio, calificación debajo de la imagen de perfil.</td> 
</tr>
<td>7</td> 
   <td>El usuario presiona el botón de número telefónico, presiona en editar el número y le da a confirmar.</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>8</td> 
   <td>El usuario presiona el botón de zona de trabajo, presiona en editar zona de trabajo, ingresa una nueva dirección y le da a confirmar.</td> 
   </tr> 
  <tr>
  <td>9</td> 
   <td>El usuario presiona el botón de trabajos, presiona en ingresar más trabajos, ingresa uno o más trabajos y le da a confirmar.</td> 
   </tr> 
  <tr>
<td>10</td> 
   <td>El usuario presiona el botón de editar número de tarjeta de crédito, presiona en editar número de tarjeta de crédito, ingresa un nuevo número y le da a confirmar.</td> 
   </tr> 
  <tr>  
  <td>11</td> 
   <td> El usuario puede presiona el botón de editar CVV, cambia los parámetros y le da a confirmar.</td> 
   </tr> 
  <tr>  
  <td>12</td> 
   <td>El usuario presiona el botón de editar la fecha de vencimiento (mes, año) de la tarjeta de crédito, cambia los valores y le da a confirmar.</td> 
   </tr> 
  <tr>  
      <td><b>Postcondición</b></td>  
       <td colspan="2">El usuario no podrá modíficar la información de su perfil consecutivamente por más de 2 veces.
       </tr> 
       </td> 
    </tr> 
     <tr>  
      <td rowspan="4"><b>Excepciones</b></td>
     <tr>  
   <td>

- El usuario no podrá editar ni el correo, ni su nombre de usuario, ni su oficio.
- El usuario no puede cambiar su imagen de perfil múltiples veces.
 </table>
 

<br>

<table align=center>  
   <tr>
     <th>CU-5</th>  
      <th colspan="2">Perfil de cliente</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (03/11/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El usuario deberá disponer de una cuenta de cliente previamente registrada.</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema debe permitir al usuario visualizar su perfil y realizar ciertas modificar ciertos parámetros del mismo.</td> 
   </tr> 
     <tr>  
      <td rowspan="15"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El usuario accede al menu de su perfil a través de un botón en la pantalla principal</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>El usuario observa la información de su perfil y elige modificar su fotografía.</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>El usuario hace click en el icono de su fotografía y elige la opción cambiar imagen de perfil.</td> 
   </tr> 
   </tr> 
  <tr>  
  <td>4</td> 
   <td>El usuario puede elige entre sus imágenes de su galería o bien, se toma una.</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>5</td> 
   <td>El usuario presiona confirmar y regresa a su perfil.</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>6</td> 
   <td>El usuario observa su correo electrónico y calificación debajo de la imagen de perfil.</td> 
</tr> 
  <tr>  
      <td><b>Postcondición</b></td>  
       <td colspan="2">No será posible cambiar ni el nombre, ni el correo electrónico.
       </tr> 
       </td> 
    </tr> 
     <tr>  
      <td rowspan="4"><b>Excepciones</b></td>
     <tr>  
   <td>

- Solo se le permite al usuario seleccionar una única imagen de su galería.
- El usuario no puede cambiar su imagen de perfil múltiples veces.
 </table>
 
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
<td> d </td>
<td>s</td>
</tr>
</table>

<br>

<table align=center>
<tr>
<th>CU-07</th>
<th  colspan="2">Elección de trabajador </th>
</tr>
<tr>
<td><b>Versión</b></td>
<td  colspan="2">1.0 (29/10/2023)</td>
</tr>
<tr>
<td><b>Precondición</b></td>
<td  colspan="2">El usuario ha realizado una búsqueda </td>
</tr>
<tr>
<td><b>Descripción</b></td>
<td  colspan="2">El cliente podrá seleccionar el trabajador que prefiera de la lista desplegada, visualizar su perfil, elegir activar el chat con el trabajador y contratar su servicio. </td>
</tr>
<tr>
<td  rowspan="3"><b>Secuencia normal</b></td>
<td><b>Paso</b></td>
<td><b>Acción</b></td>
</tr>
<tr>
<td>1</td>
<td>El cliente selecciona un trabajador </td>
</tr>
<tr>
<td>2</td>
<td>El sistema abre el perfil del trabajador y despliegan las opciones de chat y contratar servicio </td>
</tr>
<tr>
<td><b>Postcondición</b></td>
<td  colspan="2">El trabajador y el usuario se ponen en contacto </td>
</tr>
<tr>
<td  rowspan="2"><b>Excepciones</b></td>
<td><b>Paso</b></td>
<td><b>Acción</b></td>
</tr>
<tr>
<td  rowspan="3">  </td>
<td  >  </td>
</tr>
</table>

<br>

<table align=center>  
   <tr>
     <th>CU-08</th>  
      <th colspan="2">Chat</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (29/10/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El usuario y el trabajador deben estar ya registrados y aprobar por ambos el chat</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema deberá rcontar con un chat entre usuarios y trabajadores para agendar fechas, horarios y costos del servicio.</td> 
   </tr> 
     <tr>  
      <td rowspan="9"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El usuario debe realizar buscar el servicio que desea obtener</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>Ver entre la lista de trabajadores, seleccionar el perfil del que mejor le parezca y solicitar abrir el chat con el trabajador</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>Si es el trabajador le llegarán las solicitudes de mensajes de los clientes y el decide si los acepta o no</td> 
   </tr> 
   </tr> 
  <tr>  
  <td>4</td> 
   <td> Una vez haya sido aceptado por ambos, se abrirá un chat en el que se podrá enviar tanto mensajes de texto, como imágenes por parte del trabajador para mostrar algunos de sus trabajos</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>5</td> 
   <td> Una vez hayan acordado todos los términos podrán seleccionar "adquirir el servicio" para asi oficializar el contrato, el chat quedará habilitado por cualquier situación y si no se llega a adquirir el servicio, quedará guardado para futuros servicios o para algún tipo de reporte..</td> 
  <tr>  
      <td><b>Postcondición</b></td>  
       <td colspan="2">Para poder abrir el chat este debe ser aceptado por ambos y para ser cerrado, debe ser cerrado por ambos.
       </tr> 
       </td> 
       </tr> 
     <tr>  
      <td rowspan="4"><b>Excepciones</b></td>
   <tr>  
   <td>

 - Si el trabajador no acepta el chat, no se podrán enviar ni recibir mensajes por parte de ese cliente

 <br>
 
 </table> 
<table align=center>  
   <tr>
     <th>CU-15</th>  
      <th colspan="2">Cobro de membresía</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (29/10/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El trabajador deberá de tener al menos $75 MXN en su tarjeta de débito o crédito registrada</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema deberá cobrar la membresía de los trabajadores después del mes gratis y después de cada mes hasta su cancelación</td> 
   </tr> 
     <tr>  
      <td rowspan="9"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El trabajador al registrarse deberá tener en todo momento una tarjeta de débito o crédito enlazada a su cuenta</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>Se guardará la fecha de registro y se cobrarán $75 MXN cada mismo día de los meses siguientes.</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>Una vez autorizado el pago, le llegará un correo electrónico al trabajador de su pago exitoso, asi como la fecha de su próximo pago.</td> 
   <tr>  
      <td><b>Postcondición</b></td>  
       <td colspan="2">Se dará como "Pago exitoso" solo si se llega a cubrir la cuota total de la membresía
       </tr> 
       </td> 
        </tr> 
     <tr>  
      <td rowspan="4"><b>Excepciones</b></td>
     </tr>  

 - Si la tarjeta no llega a tener los fondos suficientes entonces el pago no será valido y no podrá seguir usando la aplicación como trabajador y su perfil sufrirá un "Shadowban" de la aplicación
 - Si llega haber una cancelación previa de la facturación periódica, entonces no se le cobrará y podrá usar la aplicación hasta que su membrecía haya caducado.      
 </table>

 <br>
 <table align=center>  
   <tr>
     <th>CU-16</th>  
      <th colspan="2">Recuperación de contraseña</th>  
   </tr> 
    <tr>  
      <td><b>Versión</b></td>  
       <td colspan="2">1.0 (03/11/2023)</td> 
   </tr> 
   <tr>  
      <td><b>Precondición</b></td>  
       <td colspan="2">El usuario deberá disponer de una cuenta de cliente o trabajador existente, mediante la cual disponga de un correo electrónico previamente registrado.</td> 
   </tr> 
    <tr>  
      <td><b>Descripción</b></td>  
       <td colspan="2">El sistema deberá permitir al dueño legítimo de una cuenta de WorkFlash, recuperar su contraseña en caso de olvido.</td> 
   </tr> 
     <tr>  
      <td rowspan="15"><b>Secuencia normal</b></td>
       <td><b>Paso</b></td> 
        <td><b>Acción</b></td> 
    </tr> 
  <tr>  
  <td>1</td> 
   <td>El usuario deberá seleccionar el enlace de recuperación de contraseña en el menú de inicio de sesión.</td> 
  </tr>     
  <tr>  
  <td>2</td> 
   <td>El usuario deberá confirmar el envío del enlace de recuperación de contraseña al correo asociado a su cuenta.</td> 
  </tr>
  </tr> 
  <tr>  
  <td>3</td> 
   <td>Se le pedirá al usuario ingresar al enlace enviado a su bandeja de entrada para poder cambiar su contraseña.</td> 
   </tr> 
   </tr> 
  <tr>  
  <td>4</td> 
   <td>Después de presionar al enlace enviado a su correo electrónico el usuario será redirigido a una ventana en donde podrá crear una nueva contraseña.</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>5</td> 
   <td>El usuario deberá confirmar su nueva contraseña.</td> 
   </tr> 
    </tr> 
  <tr>  
  <td>6</td> 
   <td>Se le redirigirá al usuario nuevamente al menú de inicio de sesión.</td> 
</tr> 
  <tr>  
      <td><b>Postcondición</b></td>  
       <td colspan="2">El enlace de reestablecimiento de contraseña solo puede ser usado una vez.
       </tr> 
       </td> 
    </tr> 
     <tr>  
      <td rowspan="4"><b>Excepciones</b></td>
     <tr>  
   <td>

- Solo se le permite al usuario enviar el enlace de restablecimiento de contraseña a un correo electrónico, que será aquel con el que intente el inicio de sesión.
- Si el correo electrónico al que se le intenta enviar el enlace de restablecimiento de contraseña no existe en la base de datos como previamente registrado, se le avisará al usuario que dicho correo electrónico no está registrado.
- No se podrá aceptar una nueva contraseña idéntica a la anterior.
 </table>
 
   ### Diagrama de caso de uso

   ### Sprint backlog
https://github.com/KarenCampos842/Equipo-4/blob/Segunda-Entrega/Gestion_del_Proceso.md#sprint-backlog

[^1]:Simões, C. (14 de julio de 2020). MoSCoW. ¿Qué es y cómo priorizar en el desarrollo de tu aplicación? *ITDO*. https://www.itdo.com/blog/moscow-que-es-y-como-priorizar-en-el-desarrollo-de-tu-aplicacion/

[^2]:Scrum Manager®. (2018). *Historias de Usuario.* https://www.scrummanager.com/files/historias_usuario_scrum_manager.pdf
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2NjMwNDA2NjFdfQ==
-->