# Juego de Preguntas

**Juego de Preguntas** es una aplicación web interactiva desarrollada por el Área de Nuevas Tecnologías de Incolmotos Yamaha. Permite cargar un archivo Excel (.xlsx) con preguntas y respuestas (dos columnas sin celdas combinadas), seleccionar una pregunta al azar, iniciar un temporizador y mostrar la respuesta al agotarse el tiempo o al marcarla como correcta/incorrecta.

## Requisitos
- Navegador web (Google Chrome, Mozilla Firefox, etc.).
- Descargar los archivos necesarios desde el siguiente enlace:  
  [Descargar archivos del juego]

## Instrucciones de Uso
1. Descarga los archivos `juego.html` y `juego.xlsx` y colócalos en la misma carpeta.
2. Abre el archivo `juego.html` en tu navegador.
3. Ingresa el tiempo para responder en el campo correspondiente.
4. Selecciona el archivo Excel (`juego.xlsx`) usando el botón "Choose File".
5. Haz clic en "Lanzar Dado". Se mostrará una pregunta aleatoria y se iniciará el temporizador.
6. Al agotarse el tiempo o al hacer clic en "Correcto" o "Incorrecto", se mostrará la respuesta.

## Desbloqueo de Lectura de Archivos Locales
Si tu navegador bloquea la lectura de archivos locales:
- **Google Chrome:**  
  Cierra Chrome y ejecútalo con el parámetro `--allow-file-access-from-files`.
- **Mozilla Firefox:**  
  Abre `about:config`, busca `security.fileuri.strict_origin_policy` y cambia su valor a `false`.

## Notas
- Asegúrate de que el archivo Excel tenga únicamente dos columnas y no contenga celdas combinadas.
- Prueba el juego con unas pocas preguntas para verificar su funcionamiento.

## Licencia
Proyecto interno de Incolmotos Yamaha.
