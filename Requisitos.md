<h1>REQUISITOS</h1>


## Requisitos funcionales        

- El sistema permitirá el registro del usuario con un correo electrónico, Un número telefónico, una contraseña y una identificación oficial. 
- El sistema Permitirá elegir al usuario si se quiere registrar como empleador o trabajador. 
- El sistema contará con un chat para que el empleador pueda adquirir cotizaciones del servicio y así decidir si lo acepta o no. 
- Tendrá un ranking de los trabajadores mejor calificados. 
- Se podrá filtrar a los trabajadores por ubicación, calificaciones y por el servicio que se requiera. 
- Contará con una agenda con recordatorios y alarmas para los trabajadores para organizarse sin afectar a los usuarios. 
- Al finalizar cada servicio el sistema le permitirá al empleador calificar y/o comentar el desempeño del trabajador. 
- El sistema reflejará en los perfiles de cada trabajador detalles como sus servicios realizados, su experiencia, sus calificaciones, su fotografía, sus horarios disponibles, así como su rango de distancia en el que puede laborar.
- El sistema contará con un sistema de "Karma" en el que, si el empleador o el trabajador no asiste, no cumple con lo antes mencionado o si cancela sin previo aviso, se verá reflejado en los perfiles de cada empleador y trabajador y con ello afectar la experiencia con la aplicación. 
- Se contará con un sistema de reporte por estafas, robos o incongruencias en el servicio.

## Requisitos no funcionales

 - Solo funcionará en dispositivos móviles con Android 8 y IOS 11 (por los requisitos que manejaremos y las funciones del sistema).
 - El sistema debe asegurarse de que los trabajadores no cometan suplantación de identidad o estafa (Validando la identificación oficial proporcionada).
 - El sistema debe ser fácil de mantener y actualizar (Dándole mantenimiento).
 - El sistema debe estar disponible cuando se requiera (Darle mantenimiento solo en horarios de baja demanda).
 - El sistema debe ser intuitivo y amigable para la mayoría de usuarios (Colocar imágenes fáciles de entender y simbología básica).
 - El sistema debe ser confiable y cumplir con los requisitos del usuario (Asegurándonos de que los usuarios y trabajadores sean personas reales verificando los datos proporcionados asi como las identificaciones oficiales del trabajador).
 - Los servicios ofrecidos por los trabajadores deben estar dentro de lo legal (Verificando los servicios continuamente).

## Priorización
<center><h3>Historias de usuarios</h3></center>
//
<table>
<tr>
<td >Nombre:  selección de rol </td>
<tr>
<td >Prioridad: Alta </td>
 <tr>
<td >Descripción: 
Como herrero desde hace 1 año quiero poder 
brindar mis servicios como trabajador para 
 poder tener más clientes y aumentar mi experiencia </td>
 <tr>
<td >Validación: <br>
- dar de alta su trabajo en su perfil  </td>
</table>

<table>
<tr>
<td >Nombre: Perfil de trabajador </td>
<tr>
<td >Prioridad: Alta </td>
 <tr>
<td >Descripción: <br>
 Como Trabajador de WorkFlash quiero poder tener un perfil donde se refleje mi trabajo y mis horarios para  poder tener más clientes  </td>
 <tr>
<td >Validación: <br>
-el trabajador puede modificar sus horariosen cualquier momento<br>
-las calificaciones son estadísticas inmodificables </td>
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
-el trabajador puede modificar sus horarios en cualquier momento 
<br>-las calificaciones son estadísticas inmodificables </td>
</table>

<table>
<tr>
<td >Nombre:Reporte por estafa y penalización</td>
<tr>
<td >Prioridad: Alta </td>
 <tr>
<td >Descripción: <br>
 Como Usuario quiero poder reportar algún incidente con un cliente/trabajador para que esto no ocurra en mayor medida y se sancione al responsable.</td>
 <tr>
<td >Validación: <br>
-La sanción solo será puesta si se comprueba el incidente  </td>
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
<td >Nombre:  Pago con tarjeta </td>
<tr>
<td >Prioridad: Media </td>
 <tr>
<td >Descripción: <br>
 Como cliente de WorkFash quiero poder pagar con tarjeta para no tener que ir a sacar dinero del banco y para no cometer errores a la hora de pagar. </td>
 <tr>
<td >Validación: <br>
-dar de alta una cuenta de banco  </td>
</table>

<table>
<td >Nombre: calificar trabajadores </td>
<tr>
<td >Prioridad: Media </td>
 <tr>
<td >Descripción: <br>
 Como cliente de WorkFash quiero poder compartir mi opinión del servicio con otros clientes para recomendarlo si hizo un buen trabajo. </td>
 <tr>
<td >Validación: <br>
-al finalizar un servicio ingresa su calificación </td>
</table>

<table>
<td >Nombre:  Chat </td>
<tr>
<td >Prioridad: Baja </td>
 <tr>
<td >Descripción: <br>
 Como Usuario quiero poder comunicarme rápido con el Cliente/Trabajador para poder organizar bien el trabajo</td>
 <tr>
<td >Validación: <br>
-Solo se puede chatear cuando el servicio está contratado </td>
</table>

<table>
<td >Nombre: Ranking de trabajadores</td>
<tr>
<td >Prioridad: Baja </td>
 <tr>
<td >Descripción: <br>
Como Trabajador quiero poder destacar dentro de la aplicación de otros trabajadores con una competencia sana para poder demostrar mis habilidades y atraer más clientes</td>
 <tr>
<td >Validación: <br>
-serás tomado en cuenta en el ranking mientras completes trabajos sin inconvenientes   </td>
</table>

<table>
<td >Nombre: Agenda </td>
<tr>
<td >Prioridad: Baja </td>
 <tr>
<td >Descripción: <br>
Como Trabajador quiero poder tener una agenda para recordar los trabajos que tengo pendiente y no olvidar ninguno</td>
 <tr>
<td >Validación: <br>
-El trabajador inserta la información de la agenda </td>
</table>

## Artefactos

### DIgrama de casos de uso
![Casos de uso SF drawio](https://github.com/KarenCampos842/Equipo-4/assets/143464988/44b8ef75-3f81-433d-842f-5d51830bfb17)
<br>
<br>
### Mapa conceptual de dependencias 
![Mapa de dependencia](https://github.com/KarenCampos842/Equipo-4/assets/143464988/67b5eb22-929e-4acb-a404-ca18d35ccd49)

