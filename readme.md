¿Para qué sirve la validación de formularios?

    Sirve para validar que los datos ingresados por el usuario se ingrese de forma correcta; es decir el navegador verifica que los datos ingresados cumplan con el formato adecuado y dentro de las restricciones establecidas antes de enviar los datos en el servidor, sirve para garantizar que los datos que se envían al servidor coincidan con los requisitos establecidos en los diversos controles de formulario y evitar conflictos.

¿Cuáles son los problemas al no validar un formulario?

    Si no validamos los formularios, se generaría conflicto al momento de enviar la información del usuario al servidor, por ejemplo, si la base de datos del servidor donde vamos a almacenar los datos esperar un dato tipo string y le enviamos un numero; al momento de almacenar esos datos en el servidor entraría en un conflicto.

¿Cuáles son los beneficios?
    - Asegurar que los usuarios ingresen los datos solicitados en el formato correcto de acuerdo a los formtos y dentro de las restricciones correspondientes por cada tipo de dato
    > formato correcto: El dato ingresado sea de acuerdo al campo que va a recibir el servicos es decir si es un nombre que sea string si es una fecha que esté en formato fecha y etc.
    > Restricción: caracteristicas especificias que tiene que tener el dato ingresado como: minimo y maximo de caracteres, etc.