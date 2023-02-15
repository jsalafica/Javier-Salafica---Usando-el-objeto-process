# Javier-Salafica---Usando-el-objeto-process

Consigna:

Agregar una ruta '/info' que presente en una vista sencilla los siguientes datos:
- Argumentos de entrada                                       - Path de ejecución
- Nombre de la plataforma (sistema operativo)       - Process id
- Versión de node.js                                               - Carpeta del proyecto
- Memoria total reservada (rss)

Agregar otra ruta '/api/randoms' que permita calcular un cantidad de números aleatorios en el rango del 1 al 1000 especificada por parámetros de consulta (query).
Por ej: /randoms?cant=20000.
Si dicho parámetro no se ingresa, calcular 100.000.000 números.
El dato devuelto al frontend será un objeto que contendrá como claves los números random generados junto a la cantidad de veces que salió cada uno. Esta ruta no será bloqueante (utilizar el método fork de child process). Comprobar el no bloqueo con una cantidad de 500.000.000 de randoms.

Observación: utilizar routers y apis separadas para esta funcionalidad.
