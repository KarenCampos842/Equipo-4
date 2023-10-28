<h1>REQUISITOS</h1>


## Requisitos funcionales
1. **Perfiles:** El sistema permitirá al usuario seleccionar un perfil (cliente o trabajador), con el cuál iniciará su registro a la aplicación.

2. **Registro del cliente:** Si el usuario ha seleccionado el perfil de cliente, solicitará al usuario nombre(s) y apellido(s), una identificación oficial con fotografía (credencial para votar o cartilla de servicio militar), una fotografía actual (imagen), un número telefónico, un correo electrónico y aceptación de términos y condiciones.

3. **Registro del trabajador:** Si el usuario ha seleccionado el perfil de trabajador, el sistema mostrará un aviso en pantalla informándole del cobro mensual de una membresía por $75, teniendo un primer mes de prueba gratis con su registro en la aplicación. El sistema solicitará al usuario nombre(s) y apellido(s), una identificación oficial con fotografía (credencial para votar o cartilla de servicio militar), una fotografía actual (imagen), un número telefónico, un correo electrónico, zona de trabajo (seleccionar municipio de una lista presentada por el sistema), su oficio (seleccionar de una lista presentada por el sistema), descripción breve (255 caracteres) de los trabajos que realiza (por ejemplo: frenos ABS, alineación y balanceo), un número de tarjeta de crédito, fecha (mes, año) de vencimiento de la tarjeta (seleccionar de una lista presentada por el sistema), CVV, y aceptación a de términos y condiciones.

4. **Cobro de membresía:**  Cumplido el mes de prueba gratis en la aplicación, el sistema cobrará mensualmente de la tarjeta proporcionada por el trabajador $75 correspondientes a la membresía hasta la cancelación de la cuenta.

5. **Creación de contraseña:** El sistema creará una contraseña y para el cliente o trabajador que será enviada al correo electrónico proporcionado. 

6. **Comentarios:** El sistema permitirá al cliente comentar sobre la calidad del servicio en el perfil del trabajador.

7. **Calificaciones:** Basado en una escala de cinco estrellas, el sistema permitirá al usuario (cliente o trabajador) calificar la calidad de su experiencia (una estrella es la calificación más baja, cinco estrellas la máxima). Su calificación será el promedio de todas las calificaciones recibidas.

8. **Creación del perfil de cliente:** El sistema creará el perfil del cliente, el cual contendrá: fotografía del usuario, nombre y calificación.

9. **Creación del perfil de trabajador:** El sistema creará el perfil del trabajador, el cual contendrá: fotografía del usuario, nombre, oficio, descripción de los trabajos que realiza, dirección de su local (opcional), zona de trabajo, calificaciones y comentarios de clientes.
 
11. **Inicio de sesión:**  El usuario podrá iniciar sesión proporcionando el correo con el que se registró la y la contraseña asignada. Al entrar, el sistema solicitará su ubicación (en caso del cliente). 

12. **Búsqueda:** El sistema mostrará al cliente una barra de búsqueda en la que podrá ingresar un oficio, por ejemplo: “mecánico”.

13. **Filtro:** El sistema filtrará los perfiles de los trabajadores con base a la búsqueda del cliente. Mostrará en pantalla al cliente un listado de trabajadores según su oficio, calificación(de mayor a menor promedio) y ubicación (municipio más cercano).

14. **Elección del trabajador:** El cliente podrá seleccionar el trabajador que prefiera de la lista desplegada, visualizar su perfil, elegir activar el chat con el trabajador y contratar su servicio.

15. **Chat:** El sistema contará con una opción de chat, el cual será activado por el cliente, por el medio del cual, trabajador y cliente podrán acordar precios, trabajos específicos, agendar citas y subir imágenes.

16. **Contratación del servicio:** El sistema mostrará al cliente una opción para contratar el servicio. Cuando el cliente elija esta opción, se hará llegar una notificación al trabajador preguntando si desea o no aceptar el trabajo. La notificación irá acompañada con una opción para visualizar el perfil y la ubicación del cliente. El sistema reconocerá la contratación del servicio cuando el trabajador lo acepte.

17. **Calificación del cliente:** Una vez que se ha contratado el servicio, el sistema mostrará al trabajador una opción para calificar al cliente.

18. **Finalización del servicio:** Una vez que se ha contratado el servicio, el sistema mostrará al cliente una opción para indicar cuando el trabajo se haya realizado. Al seleccionarla, se mostrará una ventana que le permitirá al cliente calificar al trabajador, publicar un comentario (opcional) y reportar al trabajador en caso de no haberse presentado.

19. **Reportes:** Cuando el cliente levante un reporte, el sistema notificará al trabajador. Si el trabajador acumula 5 reportes, su cuenta será cancelada.

20. **Cancelación del servicio:** Una vez contratado el servicio, el sistema mostrará al cliente y trabajador una opción para cancelarlo. Si el usuario selecciona la opción, el sistema solicitará la razón de la cancelación. Si el usuario realiza 3 cancelaciones consecutivas, su cuenta será cancelada.

21. **Cancelación de la cuenta por parte del trabajador:** El sistema permitirá al usuario la cancelación de su cuenta en cualquier momento.

## Requisitos no funcionales

20. Solo funcionará en dispositivos móviles con Android 8 y IOS 11 (por los requisitos que manejaremos y las funciones del sistema).

21.  El sistema debe asegurarse de que los trabajadores no cometan suplantación de identidad o estafa (validando la identificación oficial proporcionada).
 
22.  El sistema debe ser fácil de mantener y actualizar (dándole mantenimiento).
 
23.  El sistema debe estar disponible cuando se requiera (darle mantenimiento solo en horarios de baja demanda).

24.  El sistema debe ser intuitivo y amigable para la mayoría de usuarios (colocar imágenes fáciles de entender y simbología básica).

25.  El sistema debe ser confiable y cumplir con los requisitos del usuario (asegurándonos de que los usuarios y trabajadores sean personas reales verificando los datos proporcionados asi como las identificaciones oficiales del trabajador).

26.  Los servicios ofrecidos por los trabajadores deben estar dentro de lo legal (verificando los servicios continuamente).

27. Recuperación de contraseña:  El usuario podrá recuperar su contraseña. El sistema solicitará al usuario un correo al que enviará la contraseña. 

28. Modificación de perfil: Como cliente, el usuario podrá modificar el nombre y correo a

## Priorización
###  Tabla MosCow[^1]

| Must Have| Should Have | Could Have |Won't Have|
|---------|---------|---------|---------|
|1, 2, 3, 4, 5, 8, 9, 10, 11, 12, 14, 18, 19|6, 7, 13, 15, 16, 17,27|||




## Artefactos

### Digrama de casos de uso
![Casos de uso drawio](https://github.com/KarenCampos842/Equipo-4/assets/143464988/5344943e-7757-4bb1-a903-852bd88eb950)

<br>
<br>

### Mapa de dependencias 
![Mapa de dependencia](https://github.com/KarenCampos842/Equipo-4/assets/143464988/fd8a1ea0-d3c4-47a0-ba91-c184ca08e467)


### Historias de usuarios[^2]

<table>
<tr>
<td >Nombre: Perfiles </td>
<tr>
<td >Prioridad: Alta </td>
 <tr>
<td >Descripción: <br>
 Como Trabajador de WorkFlash quiero poder tener un perfil donde se refleje mi trabajo y mis horarios para  poder tener más clientes.  </td>
 <tr>
<td >Validación: <br>
-El trabajador puede modificar sus horariosen cualquier momento.<br>
-Las calificaciones son estadísticas inmodificables. </td>
</table>

<table>
<tr>
<td >Nombre: Elección trabajos </td>
<tr>
<td >Prioridad: Alta </td>
 <tr>
<td >Descripción: <br>
 Como Trabajador dentro de WorkFlash quiero poder rechazar por si alguno no se ajusta a mis horarios. </td>
 <tr>
<td >Validación: <br>
-El trabajador puede modificar sus horarios en cualquier momento. 
<br>-Las calificaciones son estadísticas inmodificables por el usuario. </td>
</table>


</table>
<table>
<td >Nombre:  Chat </td>
<tr>
<td >Prioridad: Alta </td>
 <tr>
<td >Descripción: <br>
Como usuario quiero poder ponerme de acuerdo con la otra parte(trabajador o usuarios) antes de contratar un servicio para poder cotizar y llegar a un acuerdo de pago y horarios.</td>
 <tr>
<td >Validación: <br>
-Llegar aun mutuo acuerdo. </td>
</table>

<table>
<tr>
<td >Nombre: Reporte por estafa y penalización</td>
<tr>
<td >Prioridad: Alta </td>
 <tr>
<td >Descripción: <br>
 Como Usuario quiero poder reportar algún incidente con un cliente/trabajador para que esto no ocurra en mayor medida y se sancione al responsable.</td>
 <tr>
<td >Validación: <br>
-La sanción solo será puesta si se comprueba el incidente.  </td>
</table>

<table>
<tr>
<td >Nombre:  Filtro de trabajadores </td>
<tr>
<td >Prioridad: Media </td>
 <tr>
<td >Descripción: <br>
  Cliente de WorkFlash quiero poder filtrar a los trabajadores por sus calificaciones anteriores y cercanía, para Tener la seguridad de contar con un buen servicio y una atención rápida. </td>
 <tr>
<td >Validación: <br>
-El cliente tiene que tener activada su ubicación </td>
</table>

<table>
<td >Nombre: Calificaciones </td>
<tr>
<td >Prioridad: Media </td>
 <tr>
<td >Descripción: <br>
 Como cliente de WorkFash quiero poder compartir mi opinión del servicio con otros clientes para recomendarlo si hizo un buen trabajo. </td>
 <tr>
<td >Validación: <br>
-Al finalizar un servicio ingresa su calificación. </td>
</table>


<table>
<td >Nombre: Ranking de trabajadores</td>
<tr>
<td >Prioridad: Baja </td>
 <tr>
<td >Descripción: <br>
Como Trabajador quiero poder destacar dentro de la aplicación de otros trabajadores con una competencia sana para poder demostrar mis habilidades y atraer más clientes.</td>
 <tr>
<td >Validación: <br>
-Serás tomado en cuenta en el ranking mientras completes trabajos sin inconvenientes.   </td>
</table>

<table>
<td >Nombre: Agenda </td>
<tr>
<td >Prioridad: Baja </td>
 <tr>
<td >Descripción: <br>
Como trabajador quiero poder tener una agenda para recordar los trabajos que tengo pendiente y no olvidar ninguno.</td>
 <tr>
<td >Validación: <br>
-El trabajador inserta la información de la agenda. </td>
</table>


  
[^1]:Simões, C. (14 de julio de 2020). MoSCoW. ¿Qué es y cómo priorizar en el desarrollo de tu aplicación? *ITDO*. https://www.itdo.com/blog/moscow-que-es-y-como-priorizar-en-el-desarrollo-de-tu-aplicacion/

[^2]:Scrum Manager®. (2018). *Historias de Usuario.* https://www.scrummanager.com/files/historias_usuario_scrum_manager.pdf


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNTUzNzczMzYsMTUzMDkzNjQ5OSwtMj
Y5NjcwMTIzLDE2OTIzMTMzODQsLTYwNTg4NjQ1MCwtMTgwOTQ4
MDExNywyMDgzODM1ODc4LDE1OTkxMzQyOTQsLTk5MjA0MTU2NC
wtMzU5MzAwNDMzLDk5NjUxMzA5MSwtNTgwNDUxNDc5LDUwODIy
NTY1MCw2OTU3ODM1MzQsLTY4MDMxOTc2NiwxMDEyMzI1MDE4XX
0=
-->