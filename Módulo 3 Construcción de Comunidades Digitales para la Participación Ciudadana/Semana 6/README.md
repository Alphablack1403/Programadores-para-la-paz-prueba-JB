# Programadores para la Paz

## Datos del Estudiante
* **Nombre:** Jesus Barrios
* **Correo:** jbarriosm2@unicartagena.edu.co

## Información del Curso
* **Programa:** Programadores para la Paz
* **Módulo:** Módulo 3: Construcción de Comunidades Digitales para la Participación Ciudadana
* **Semana:** Semana 6

## Glosario de Conceptos Técnicos
* **JSON (JavaScript Object Notation):** Formato ligero de intercambio de datos, estructurado y basado en texto plano, utilizado ampliamente para transferir información entre un servidor y un cliente.
* **req.body:** Propiedad en Express que contiene los datos enviados por el cliente en el cuerpo de una petición HTTP (usualmente peticiones POST o PUT), lo que permite al servidor leer y procesar la información estructurada.
* **POST (Método HTTP):** Método utilizado para enviar datos o registrar información en el servidor para que este los procese, usualmente en formatos estructurados como JSON o formularios codificados.
* **express.json():** Middleware integrado en Express que analiza (parsea) de manera automática las peticiones entrantes con cuerpos en formato JSON, haciéndolos legibles a través de la propiedad `req.body`.

## Listado Explicativo de Archivos
A continuación se detallan los archivos incluidos en la carpeta `Semana 6` de este módulo, con sus respectivos enlaces locales:

* [preguntas-semana6.txt](preguntas-semana6.txt): Respuestas de selección múltiple (preguntas 1 a 4) sobre conceptos fundamentales de JSON, middleware en Express y el uso de `req.body`.
* [server.js](server.js): Código del servidor Express con rutas POST para registrar usuarios en `/registro` y reportar incidentes comunitarios en `/incidencia`.
* [prueba-api.txt](prueba-api.txt): Explicación y ejemplo de la respuesta del servidor en formato JSON tras realizar una petición HTTP POST a la ruta `/registro`.
* [ejemplo-incidencia.txt](ejemplo-incidencia.txt): Estructura de un archivo JSON modelo que representa el reporte de una incidencia en la vía pública por parte de un ciudadano.
* [reflexion-semana6.txt](reflexion-semana6.txt): Texto reflexivo de exactamente 9 líneas donde se analiza el valor técnico e institucional de procesar reportes ciudadanos de forma estructurada en lugar de texto libre.
* [package.json](package.json): Configuración del proyecto Node.js e indexación de las dependencias requeridas (Express).
