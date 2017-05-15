# wp-base
Instalador automatizado para la instalación de la plantilla de Wordpress 4.3 (https://github.com/iuandalucia/plantillawp)

1º Crear una base de datos

En primer lugar, debemos crear una base de datos en nuestro servidor, y guardar la siguiente información, ya que tendremos que usarla posteriormente.

Nombre de usuario
Nombre de la base de datos
Contraseña

2º Instalar Wordpress y el Tema

Para realizar la instalación de Wordpress y del tema, en primer lugar, copiamos en el directorio de nuestro servidor los archivos installer.php y el .zip que encontramos en el repositorio.

Entramos en tudominio.com/installer.php y aparecerá una pantalla, en la que todos los test deben estar en Pass. Si fallara alguno, podemos conocer el motivo seleccionándolo, tras lo que tendremos que proceder a solucionarlo. Tras confirmar que todos los test son correctos, configuramos los parámetros de la base de datos creada anteriormente

A continuación, nos aparecerá una pantalla donde podremos configurar diferentes parámetros. En primer lugar podremos configurar la URL, la ruta y el título, por lo que no tenemos más que comprobar que los datos son correctos. A través de Options podremos configurar un nuevo usuario administrador.

Por último, nos aparecerá una última pantalla donde podremos realizar diversas validaciones así como configurar los enlaces (permalinks) si quisiéramos darles otro formato.


Tras realizar estos pasos, podemos acceder de nuevo a tudominio.com y automáticamente se abrirá la plantilla con los datos por defecto. Para acceder al administrador de WordPress no hay más que abrir tudominio.com/wp-admin.
