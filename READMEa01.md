# Actividad: Tipos de Datos y Direcciones de Memoria
# Descripción

Programa en C que declara variables de distintos tipos de datos primitivos para mostrar en consola sus respectivos valores y direcciones de memoria.
# Temas Aplicados

    Tipos de datos primitivos: Uso de char, short, int, long, float, double y modificadores como signed, unsigned y long.

    Direcciones de memoria: Utilización del operador & para referenciar la ubicación de una variable en la memoria.

    Formateo de salida (I/O): Uso de la función printf y comprensión de sus especificadores de formato (%c, %d, %f, %lf).

# Requisitos

    Compilador de C (como gcc).

    Terminal o línea de comandos.

# Compilación

Para compilar el código fuente, abre tu terminal en el directorio del proyecto y ejecuta el siguiente comando:
Bash

gcc main.c -o programa

    Nota de desarrollo: Al compilar, el compilador podría arrojar algunas advertencias (warnings). Esto se debe a que se está utilizando %d para imprimir direcciones de memoria (el estándar recomendado es %p) y por la asignación de múltiples caracteres en la variable char chr = 'chr';. El programa compilará y ejecutará de todas formas.

# Ejecución

Una vez compilado, puedes iniciar el programa con:
Bash

./programa