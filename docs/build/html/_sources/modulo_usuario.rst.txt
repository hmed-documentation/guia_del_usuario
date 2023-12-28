******************
Módulo Usuario
******************

En el módulo usuario se ingresan datos del paciente utilizando el 
formulario para el ingreso de pacientes.

En este módulo se crea un usuario y se despliegan los usuarios 
registrados.
 
Utilice la opción **Crear** para crear un nuevo usuario o paciente.

Al precionar el boton crear se despliega el formulario con los campos
que deben ser llenados con los datos del usuario.

**Descripción de los campos del formulario de registro de usuario**

*NUMERO DE CEDULA*

APELLIDO PATERNO

APELLIDO MATERNO

NOMBRES

BARRIO

PARROQUIA

ZONA

DIRECCION CALLE PRINCIPAL

NUMERO DE CALLE PRINCIPAL

DIRECCION CALLE SECUNDARIA

REFERENCIAS CONOCIDAS DE LA ZONA

NUMERO DE TELEFONO

DIRECCION DE CORREO ELECTRONICO

LATITUD

LONGITUD

FECHA DE NACIMIENTO

LUGAR DE NACIMIENTO

NACIONALIDAD

GRUPO CULTURAL

GENERO

ESTADO CIVIL

NIVEL DE INSTRUCCION

FECHA DE ADIMISION

ACTIVIDAD ECONOMICA HABITUAL

EMPRESA DONDE TRABAJA

PUESTO DE TRABAJO

TIPO DE SEGURO DE SALUD

ESTABLECIMIENTO QUE REFIERE

ESTABLECIMIENTO QUE CONTRA-REFIERE

REGISTRO DE UN FAMILIAR, PERSONA DE CONTACTO O PERSONA
CONOCIDA:

NUMERO DE CEDULA DE CIUDADANIA

APELLIDO PATERNO

APELLIDO MATERNO

NOMBRES

BARRIO

PARROQUIA

ZONA

DIRECCION CALLE PRINCIPAL

NUMERO DE CALLE PRINCIPAL

DIRECCION CALLE SECUNDARIA

REFERENCIAS CONOCIDAS DE LA ZONA

NUMERO DE TELEFONO

DIRECCION DE CORREO ELECTRONICO

LATITUD 0.0-90.0

LONGITUD 0.0-180.0

ADMISIONISTA

Boton Crear usuario





















Utilizar la opción **Desplegar** para desplegar los usuarios registrados.

Con la opcion Desplegar se despliegan los usuarios registrados en la
base de datos. 

Reporte de usuarios PDF: Utilize esta opcion para obtener un listado
de los usuarios registrados en el sistema. El listado es creado por el
sistema en formato PDF.

.. Warning:: 
   La historia clínica única solo puede ser creada si existe un usuario registrado en el sistema. No se puede crear una historia clínica única para un paciente si el paciente no ha sido registrado previamente en el sistema. El sistema realiza la validación de la existencia del usuario durante la creación de la historia clínica única. Para crear un nuevo usuario se debe utilizar la opción crear un usuario.
