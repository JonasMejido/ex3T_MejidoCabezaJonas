# ex3T_MejidoCabezaJonas
1º Diagrama de Clase:

Primero creamos al cliente con todos sus datos, este tendrá un metodo para obtener el historial médico y solicitar la consulta, segundo creamos a su mascota que además de sus datos tendra el método para asignar su dueño, continuamos con que el cliente solicita una consulta que tendrá un método para asignar a su veterinario responsable, este luego tendrá sus datos además de los métodos para registrar la consulta además de para asignar el tratamiento, finalmente el tratamiento tiene sus datos y luego las medicinas que entran dentro de este.

2º Diagrama de Actividad:

Básicamente todo lo que va a ocurrir desde el principio, el cliente entra, se registra a sí mismo y a su mascota, solicita la consulta, se le asigna un veterinario, este hace su diagnóstico, receta un tratamiento y registra la consulta para posteriormente actualizar el historial del animal. Además de registrarse dentro de este los tratamientos aplicados, el diagnóstico, la fecha y el tipo de consulta.

3º Diagnóstico de Secuencia:

Este ha sido el mas lioso de los tres, he tenido que añadir cosas que no se incluían dentro de los dos anteriores como el apartado "Sistema", osea que lo he hecho casi de manera independiente a los dos anteriores. Aunque funciona de manera similar, en el sistema se agrega al cliente con sus datos y se confirma, luego a su mascota y se confirma, el sistema le asigna al veterinario una consulta (o lo que es lo mismo se le asigna un veterinario a al consulta) y este crea la consulta, se confirma su creación y se crean y registran diagnóstico y tratamiento para posteriormente confirmar estas acciones,  dentro del tratamiento se asigna la dosis de medicina y se registra, finalmente se registra el precio final y se registra la consulta para añadirla al historial médico del animal.
