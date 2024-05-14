Nombre de función: get_next_line
Prototipo: char *get_next_line(int fd);
Archivos a entregar: get_next_line.c, get_next_line_utils.c, get_next_line.h
Parámetros: fd) File descriptor del que leer
Valor devuelto Si todo va bien: la línea leída
En caso de fallo o si la lectura termina: NULL
Funciones autorizadas: read, malloc, free
Descripción: Escribe una función que devuelva la línea leída de un file descriptor
• Llamar a tu función get_next_line de manera repetida (por ejemplo, usando un
bucle) te permitirá leer el contenido del archivo hacia el que apunta el file descriptor,
línea a línea, hasta el final.
• Tu función deberá devolver la línea que se acaba de leer.
Si no hay nada más que leer o si ha ocurrido un error, deberá devolver NULL.
• Asegúrate de que tu función se comporta adecuadamente cuando lea de un archivo
y cuando lea de stdin.
• Ten en cuenta que la línea devuelta debe terminar con el caracter
n, excepto si se ha llegado al final del archivo y esté no termina con un caracter
n.
• En el header get_next_line.h deberás tener como mínimo el prototipo de la función get_next_line.
• Añade todas las funciones de ayuda que necesites en el archivo get_next_line_utils.c
