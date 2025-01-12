# Relaciones-de-Recurrencia
Instrucciones
Objetivo:

Implementar un programa en lenguaje ANSI C que utilice funciones recursivas para resolver problemas comunes y refuerce el conocimiento sobre modularización mediante el uso de archivos de cabecera (.h).

Descripción de la actividad:

En esta actividad, los estudiantes deberán diseñar un programa que cumpla los siguientes requisitos:

Menú interactivo:
El programa debe presentar un menú en el que el usuario pueda seleccionar entre tres opciones para ejecutar diferentes funciones recursivas.
Funciones recursivas requeridas:
Opción 1: Invertir una cadena ingresada por el usuario. Esta función ya fue vista en clase.
Opción 2: Calcular el factorial de un número entero positivo ingresado por el usuario.
Opción 3: Generar la sucesión de Fibonacci hasta un número dado ingresado por el usuario.
Modularización del programa:
Todas las funciones recursivas deben estar implementadas en un archivo de cabecera con extensión .h.
Este archivo de cabecera debe ser incluido y llamado desde el programa principal.

Detalles técnicos:
El programa principal debe encargarse de manejar el menú, recibir entradas del usuario y mostrar los resultados correspondientes.
Asegúrese de que el código sea claro y esté bien documentado.
Entrega:

Subir los siguientes archivos:
El archivo principal del programa (main.c).
El archivo de cabecera con las funciones recursivas (funciones.h).

Evaluación:
Se calificará:

La correcta implementación de las funciones recursivas.
El uso de modularización mediante el archivo .h.
La claridad y el diseño del menú interactivo.
La documentación y comentarios en el código.



##Invertir
 while (in < fin)
    { temp = cadena[in]; 
    cadena[in] = cadena[fin];
    cadena[fin] = temp; 
    fin --; in ++; } 