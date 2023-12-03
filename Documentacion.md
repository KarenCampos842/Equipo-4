# Documentación

## Métodos de estimación

### Estimación

> **Tema:** *Con respecto al proyecto que estás llevando a cabo, realiza una estimación que abarque el esfuerzo requerido, los costes asociados (incluyendo la asignación de salarios acorde a las funciones y experiencia de cada miembro del equipo, indique la referencia utilizada para el cálculo de los salarios ) y el tiempo necesario. Para ello, emplea la técnica de puntos de función basada en el método COSMIC y aplícala a un sprint de tu elección.*


**Perfil de trabajador**

***Proceso funcional:*** Registrarse como trabajador en la aplicación.

 Entrada: Seleccionar la opción para registrarse. 
 
 Salida: Mostrar en pantalla las opciones para registrarse como trabajador o cliente.
 
 Entrada: Seleccionar la opción para registrarse como trabajador. 

Salida: Mostrar en pantalla los campos nombre(s), apellido materno, apellido paterno,  apellido materno, correo y la opción para guardar cambios y continuar. 

Entrada: Ingresar nombre(s). 

Entrada: Ingresar apellido paterno. 

Entrada: Ingresar apellido materno. 

Entrada: Ingresar correo. 

Entrada: Seleccionar guardar datos y continuar. 

Escritura: Crear un registro en la base de datos de los nombre(s)  del usuario con perfil de trabajador. 

Escritura: Crear un registro en la base de datos del apellido paterno  del usuario con perfil de trabajador. 

Escritura: Crear un registro en la base de datos del apellido materno del usuario con perfil de trabajador. 

Escritura: Crear un registro en la base de datos del correo  del usuario de perfil de trabajador (llave). 

Salida: Mostrar en pantalla la opción para seleccionar una identificación oficial de registro (Cartilla Militar o INE), el espacio para cargar una fotografía actual y la opción para guardar cambios y continuar. 

Entrada: Seleccionar una opción de identificación oficial (Cartilla Militar/INE). 

Entrada: Cargar un documento de identificación oficial  (Cartilla Militar/INE).
 
Entrada: Cargar una fotografía actual.

Entrada: Seleccionar guardar datos y continuar. 

Escritura: Crear un registro en la base de datos del documento de identificación oficial del usuario (Cartilla Militar/INE). 

Escritura: Crear un registro en la base de datos de la fotografía actual del usuario. 

Salida: Mostrar en pantalla las opciones para seleccionar un oficio/ocupación, una zona de trabajo, los campos de teléfono y de descripción sobre los servicios que ofrece el usuario como trabajador,  y la opción para guardar cambios y continuar. 

Entrada: Seleccionar la opción para elegir un oficio/ocupación. 

Salida: Mostrar en pantalla una lista de todos los oficios/ocupaciones disponibles. 

Entrada: Seleccionar una opción de la lista desplegada.  

Entrada: Seleccionar la opción para elegir una zona de trabajo. 

Salida: Mostrar en pantalla una lista de todos las zonas de trabajo disponibles (municipios de Yucatán). 

Entrada: Seleccionar una opción de la lista desplegada.  

Entrada: Ingresar un teléfono. 

Entrada: Ingresar una descripción sobre los servicios que ofrece el usuario como trabajador. 

Entrada: Seleccionar la opción de guardar cambios y continuar. 

Escritura: Crear un registro en la base de datos del trabajo/ocupación que el usuario halla seleccionado. 

Escritura: Crear un registro en la base de datos de la zona de trabajo que el usuario halla seleccionado. 

Escritura: Crear un registro en la base de datos del teléfono del usuario. 

Escritura: Crear un registro en la base de datos de la descripción sobre los servicios que ofrece el usuario como trabajador. 

Salida: Mostrar en pantalla los campos de número de tarjeta y CVV,  las opciones para seleccionar mes y año de expiración de la tarjeta y la opción para guardar cambios y continuar.

Entrada: Ingresar un número de tarjeta. 

Entrada: Ingresar CVV. 

Entrada: Seleccionar la opción para elegir el mes de expiración de la tarjeta. 

Salida: Mostrar en pantalla una lista con los 12 meses del año. 

Entrada: Seleccionar una opción de la lista desplegada.  

Entrada: Seleccionar la opción para elegir el años de expiración de la tarjeta. 

Salida. Mostrar en pantalla una lista con los años disponibles.

Entrada: Seleccionar una opción de la lista desplegada. 

Entrada: Seleccionar la opción de guardar cambios y continuar. 

Escritura: Crear un registro en la base de datos del número de tarjeta del usuario. 

Escritura: Crear un registro en la base de datos del CVV de la tarjeta del usuario. 

Escritura: Crear un registro en la base de datos del mes de expiración de la tarjeta del usuario. 

Escritura: Crear un registro en la base de datos del año de expiración de la tarjeta del usuario. 

Salida: Mostrar en pantalla los términos y condiciones, la opción para aceptarlos y la opción para continuar. 

Entrada: Seleccionar la opción de aceptar términos y condiciones.

Entrada: Seleccionar la opción de continuar. 

***Proceso funcional:*** Creación de contraseña.

Lectura: Leer el correo del usuario guardado en base de datos. 

Salida: Enviar al correo del usuario una contraseña generada automáticamente.  

***Proceso funcional:*** Iniciar sesión.

Salida: Mostrar en pantalla el correo al que se ha enviado la contraseña del usuario y la opción para iniciar sesión. 

Entrada: Seleccionar la opción de iniciar sesión.

Salida: Mostrar en pantalla la ventana del log in.

Entrada:








### WBS

> **Tema:** *Aplica el WBS para las historias de usuario o casos de uso en un sprint de tu elección y contempla que los paquetes de trabajo contengan : idWBS, nombre, duración, costo estimado*


### Diagrama Grantt
> **Tema:** *Presenta un diagrama de Gantt de la planeación y calendarización de las actividades llevadas a cabo en un sprint de tu elección (considera hitos, fecha iniciales y finales para las actividades, así como los responsables de cada actividad)*

## Calidad

###  Comparación

> **Tema:** *Compara los modelos de calidad propuestos por McCall y Boehm, identifica y lista sus características escenciales y reflexiona sobr e cuál de estos dos modelos sería más adecuado para aplicar en tu proy ecto de desarrollo de software. Justifica tu elección.*

## Configuración

###  Auditoría

> **Tema:** *Elige dos artefactos que se generaron como parte del proceso de tu proyecto y realiza una audit oría de la gestión de la configuración del software, indicando si se llevó a cabo su configuración y versionamiento. A continuación, presenta un informe detallado al respecto. Nota:el objetivo es que realicen la actividad de auditoria a través de preguntas tipo checklist, en el cual vean la importancia de la gestión de la configuración.*

#### Artefacto 1: Lista de requerimientos funcionales y no funcionales

 - [x] Se estableció una línea base. 
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#l%C3%ADnea-base">Evidencia</a>
 - [x] Las solicitudes de cambio de los requerimientos funcionales y no funcionales se encuentran documentadas.
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#solicitudes-de-cambioresponsable-de-aceptar-los-cambios">Evidencia</a>
 - [x] Existe un responsable de aceptar o rechazar los cambios en la lista de requerimientos funcionales y no funcionales. 
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#solicitudes-de-cambioresponsable-de-aceptar-los-cambios">Evidencia</a>
 - [ ] La razón de cada uno de los cambios en los requerimientos y/o el rechazo de ellos se encuentra documentada. 
 - [x] El estado de todas las solicitudes de cambio se encuentra documentada.
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#estado-de-solicitudes-e-implementaci%C3%B3n">Evidencia</a>
 - [x] El estado de la implementación de los cambios aprobados se encuentra documentada.
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#estado-de-solicitudes-e-implementaci%C3%B3n">Evidencia</a>
 - [x] Los cambios realizados en la lista de requerimientos funcionales y no funcionales  se encuentran documentados. 
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#cambios-realizados">Evidencia</a>
 - [x] La fecha y el responsable de cada uno de los cambios en los requerimientos se encuentra documentada. 
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#fecha-y-responsable-de-los-cambios">Evidencia</a>
 - [x] La lista de requerimientos se encuentra versionada. 
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#versionescambios-reflejadosentregas-versiones-actualizadas">Evidencia</a>
 - [x] Únicamente los cambios aprobados están reflejados en la línea base. 
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#versionescambios-reflejadosentregas-versiones-actualizadas">Evidencia</a>
 - [x] Únicamente se han entregado las versiones actualizadas de los requerimientos. 
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#versionescambios-reflejadosentregas-versiones-actualizadas">Evidencia</a>
 - [x] Actualmente se está trabajando sobre la versión actualizada de la lista de requerimientos. 
<a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#versi%C3%B3n-actualizada">Evidencia</a>

#### Artefacto 2: Casos de uso

 - [x] Se estableció una línea base. 
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#l%C3%ADnea-base-1">Evidencia</a>
 - [x] Las solicitudes de cambio de los casos de uso se encuentran documentadas.
   <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#solicitudes-de-cambioresponsable-de-aceptar-los-cambios-1">Evidencia</a>
 - [x] Existe un responsable de aceptar o rechazar los cambios en los casos de uso.
   <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#solicitudes-de-cambioresponsable-de-aceptar-los-cambios-1">Evidencia</a> 
 - [ ] La razón de cada uno de los cambios en los casos de uso y/o el rechazo de ellos se encuentra documentada. 
 - [x] El estado de todas las solicitudes de cambio se encuentra documentada.
   <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#estado-de-solicitudes-e-implementaci%C3%B3n-1">Evidencia</a>
 - [x] El estado de la implementación de los cambios aprobados se encuentra documentada.
    <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#estado-de-solicitudes-e-implementaci%C3%B3n-1">Evidencia</a>
 - [x] Los cambios realizados en los casos de uso se encuentran documentados. 
    <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#cambios-realizados-1">Evidencia</a>
 - [x] La fecha y el responsable de cada uno de los cambios en los casos de uso se encuentra documentada. 
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#fecha-y-responsable-de-los-cambios-1">Evidencia</a>
 - [x] Los casos de uso se encuentran versionados. 
 <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#versionescambios-reflejadosentregas-versiones-actualizadas-1">Evidencia</a>
 - [x] Únicamente los cambios aprobados están reflejados en la línea base. 
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#versionescambios-reflejadosentregas-versiones-actualizadas-1">Evidencia</a>
 - [x] Únicamente se han entregado las versiones actualizadas de los los casos de uso. 
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evidencias.md#versionescambios-reflejadosentregas-versiones-actualizadas-1">Evidencia</a>
 - [x] Existe una correspondencia entre los requerimientos y los casos de uso entregados.
 - [x] Actualmente se está trabajando sobre la versión actualizada de los casos de uso.
  <a href="https://github.com/KarenCampos842/Equipo-4/blob/PD-3/Evid">Evidencia</a>
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MjI2MDI5MDksMTA5MjMzMjkwMywyOT
k2NjMyMzQsLTE0MDQ0NzE1MjcsMTkzMjYyMDE5MSwtMTcxMDcz
NDU3OSw1NzQ1OTUyNzYsMTc2OTQyNDAxMSw1ODE1ODY2MTksMT
MzODM2MTUzMiwtMzY4MDE0ODc1LC05MTU4NTc5MTUsLTI4MTky
ODA4NSwxOTIwNjYzMzM3LDE4ODg0MjcwMjIsMTA2NTA4NTE5Ni
wtMTQ1NzE4MDIzLC01MTI5NDY0MjMsNTQ1MTE0Mzk3LDIwMDc5
NjYwNDhdfQ==
-->