<h1>REQUISITOS</h1>


## Requisitos funcionales        
1. Registro: El sistema permitirá el registro de usuario (cliente o trabajador) con un correo electrónico, un número telefónico, una contraseña y una identificación oficial.

2. Perfiles: El sistema creará perfiles para los trabajadores y clientes. En el perfil de cada trabajador se podrán reflejar detalles como sus servicios realizados, su experiencia, sus calificaciones, su fotografía, sus horarios disponibles (son modificables), así como su rango de distancia en el que puede laborar.

3. Filtro de trabajadores: Se podrá filtrar a los trabajadores por ubicación, calificaciones y por el servicio que se requiera. 

4. Elección de trabajos: El sistema reconocerá la contratación del servicio cuando el trabajador lo acepte (El trabajador puede no aceptar el trabajo). 

5. Chat: El sistema contará con un chat para que el empleador pueda adquirir cotizaciones del servicio y así decidir si lo acepta o no. 

6. Calificaciones: Al finalizar cada servicio el sistema le permitirá al empleador calificar y/o comentar el desempeño del trabajador. 

7. Ranking:Tendrá un ranking de los trabajadores mejor calificados. 

8. Reportes: Se contará con un sistema de reporte por estafas, robos o incongruencias en el servicio.

9. Penalizacion: El sistema contará con un sistema de "Karma" en el que, si el empleador o el trabajador no asiste, no cumple con lo antes mencionado o si cancela sin previo aviso, se verá reflejado en los perfiles de cada empleador y trabajador y con ello afectar la experiencia con la aplicación. 

10. Agenda: Contará con una agenda con recordatorios y alarmas para los trabajadores para organizarse sin afectar a los usuarios. 

## Requisitos no funcionales

11. Solo funcionará en dispositivos móviles con Android 8 y IOS 11 (por los requisitos que manejaremos y las funciones del sistema).

12.  El sistema debe asegurarse de que los trabajadores no cometan suplantación de identidad o estafa (validando la identificación oficial proporcionada).
 
13.  El sistema debe ser fácil de mantener y actualizar (dándole mantenimiento).
 
14.  El sistema debe estar disponible cuando se requiera (darle mantenimiento solo en horarios de baja demanda).

15.  El sistema debe ser intuitivo y amigable para la mayoría de usuarios (colocar imágenes fáciles de entender y simbología básica).

16.  El sistema debe ser confiable y cumplir con los requisitos del usuario (asegurándonos de que los usuarios y trabajadores sean personas reales verificando los datos proporcionados asi como las identificaciones oficiales del trabajador).

17.  Los servicios ofrecidos por los trabajadores deben estar dentro de lo legal (verificando los servicios continuamente).

## Priorización
###  Tabla MosCow[^1]

| Must Have| Should Have | Could Have |Won't Have|
|---------|---------|---------|---------|
|1|5|6|10|
|2|8|7||
|3|9|||
|4||||



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


