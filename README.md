# CustomWordlist

CustomWordlist es una herramienta para generar diccionarios de contraseñas personalizadas a partir de datos específicos de una persona.
Permite crear combinaciones de contraseñas basadas en información clave, con la opción de generar listas más extensas y avanzadas.

## Características
* Generación de diccionarios personalizados con datos reales.
* Combinaciones con nombres, fechas y otros datos clave.
* Soporte para caracteres especiales y números.
* Dos modos de ejecución:
  * Modo normal: Genera una lista básica de contraseñas.
  * Modo extendido (--pro): Genera combinaciones más avanzadas y variadas.
* Permite guardar las contraseñas en un archivo personalizado.
* Posibilidad de ejecutarlo como comando desde cualquier ubicación.

## Instalación y Uso

### Ejecutar desde la misma carpeta

Si solo deseas ejecutar el script sin instalarlo en el sistema:
    1- Otorgar permisos de ejecución:
          chmod +x CustomWordlist.py
    2- Ejecutar el script:
        ./CustomWordlist.py

### Instalar para Ejecutarlo desde Cualquier Ubicación

#### Si deseas ejecutarlo como un comando en cualquier parte del sistema:
  1- Mover el archivo a /usr/local/bin/:
    sudo mv CustomWordlist.py /usr/local/bin/customwordlist

  2- Ejecutarlo desde cualquier ubicación:
    customwordlist

  3 -Para usar el modo extendido:
    customwordlist --pro

## Funcionamiento
El programa solicita información sobre la persona objetivo y, con esas respuestas, genera combinaciones de contraseñas que incluyen variaciones con números y caracteres especiales.

El usuario debe ingresar información como:

* Nombre y apellido
* Fecha de nacimiento
* Nombre de su pareja
* Año de nacimiento de la pareja
* Nombre de su mascota
* Ciudad de residencia
* Color favorito
* Apodo o alias

Posteriormente el programa nos preguntara que nombre queremos darle al archivo, cuando respondamos podremos visualizar con cat nuevo archivo txt.

## Requisitos
Para ejecutar CustomWordlist, solo necesitas tener Python 3 instalado.
