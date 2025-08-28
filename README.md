# Módulo Interactivo de Python — README

Este repositorio contiene una página HTML interactiva para un módulo de Python dirigido a jóvenes programadores.

Resumen rápido
- Archivo principal: `index.html` (contenido interactivo, editores y ejemplos).
- Librería usada para ejecutar Python en el navegador: Skulpt (archivos incluidos: `skulpt.min.js`, `skulpt-stdlib.js`).

Cómo probar localmente
Abre el archivo `index.html` en tu navegador (doble clic o "Abrir con...").

Cómo utilizarlo online
Abre el siguiente link en tu navegador: santiagodeniz.github.io/Programacion-en-Python

Notas técnicas
- La ejecución de código en el navegador se realiza con Skulpt.
- `input()` se implementa usando el `prompt()` del navegador (aparecerá una ventana emergente para introducir texto).
- El botón de descarga crea un `Blob` y utiliza un enlace temporal para forzar la descarga del archivo `.txt`.

Contacto / Autor
- Creado y mantenido por Prof. Santiago Deniz (proyecto educativo).