---
title: OCR Scanner: Imagen a Texto
name: OCRScanner
tagline: Escanea documentos a texto editable en tu móvil. Busca, copia y comparte en PDF.
project: OCRScanner
package: io.github.varian1.ocrscanner
version: 1.2.0
updated: 2026-11-21
privacy: https://varian1.github.io/ocrscanner/privacy.html
---

## Qué hace

OCRScanner fotografía una página en papel, la endereza y lee el texto en tu teléfono. Puedes editar y copiar el texto, buscar en todos los escaneos que hayas hecho y compartir un escaneo como PDF con texto buscable, como archivo de texto o como imagen.

- El reconocimiento de texto se hace en tu dispositivo y funciona sin internet.
- Sin cuenta. Tus escaneos se quedan en tu teléfono y nunca se suben a ningún servidor.
- Importa un PDF o comparte imágenes desde otras apps en Android.
- Gratis con anuncios. Una compra única de Premium quita los anuncios y añade más idiomas.

## Primeros pasos

1. Abre OCRScanner. La lista **Scans** está vacía la primera vez.
2. Toca **Scan** para usar la cámara, o **Import** para elegir fotos que ya tienes.
3. Permite el acceso a la cámara cuando Android te lo pida. Importar no necesita acceso a toda tu galería de fotos.

![La lista Scans con los botones Scan e Import](shots/01-home.png)

## Escanear una página

1. Toca **Scan** y apunta la cámara a la página. Toca el botón del obturador para hacer la foto.
2. En **Review**, los bordes de la página se detectan solos. Arrastra una esquina azul si algún borde no está bien, o toca **Full page** para conservar toda la foto.
3. Elige un filtro para limpiar la página: **Original**, **Magic**, **Gray** o **B&W**.
4. Toca **Rotate 90°** si la página está de lado, o **Retake** para fotografiarla de nuevo.
5. Toca **Recognize text**.

![Pantalla Review con las esquinas de la página, los filtros y el botón Recognize text](shots/02-review.png)

Para escanear varias páginas en un solo documento, abre el escaneo más tarde, toca **⋯** y elige **Add pages**.

## Importar un PDF

OCRScanner lee hasta 20 páginas de un PDF, o 50 con Premium. Cada página se lee como una imagen, así que el texto que ya esté dentro del PDF no se usa.

1. Elige un PDF en el selector de archivos de tu teléfono. No hace falta permiso de almacenamiento.
2. En **Review**, revisa las páginas. Si el PDF supera el límite, Review te indica cuántas páginas se han dejado fuera.
3. Toca **Recognize text**.

## Compartir imágenes desde otras apps

Esto funciona en Android.

1. En tu galería u otra app, selecciona hasta 20 imágenes y toca compartir.
2. Elige OCRScanner.
3. Desbloquea la app si **App lock** está activado. Las imágenes se abren en **Review** como un escaneo nuevo.

Si tienes páginas abiertas sin guardar, la app te pregunta antes de reemplazarlas.

## Leer, editar y copiar el texto

1. Tras el reconocimiento, **Result** muestra la página arriba y su texto debajo.
2. Toca una línea de texto para ver dónde está en la página. Toca una palabra en la página para ir a su línea.
3. Las líneas de las que la app no está segura aparecen resaltadas, para que sepas qué revisar.
4. Toca **Edit** para corregir el texto, **Copy** para copiarlo o **Share** para enviarlo.
5. Toca **Save** para guardar el escaneo en tu lista.

![Pantalla Result: la página arriba, el texto reconocido abajo, con Edit, Copy, Share y Save](shots/03-result.png)

## Encontrar un escaneo por su texto

1. En **Scans**, toca **Search text in your scans**.
2. Escribe una palabra. Se muestran todos los escaneos que la contienen, con la coincidencia en negrita.
3. Toca un resultado para abrir el escaneo en esa coincidencia.

![Al buscar la palabra "lighting" aparece el escaneo que la contiene](shots/04-search.png)

Para ver solo los escaneos con una etiqueta, toca esa etiqueta debajo del campo de búsqueda. La búsqueda se hará solo dentro de esos escaneos. Vuelve a tocar la etiqueta para ver todos los escaneos.

## Compartir o exportar

1. Abre un escaneo y toca el botón de compartir.
2. Elige un formato:
   - **PDF**: las imágenes de las páginas con el texto buscable detrás.
   - **Text file**: texto sin formato (.txt).
   - **Page image**: guárdala en Fotos o envíala.
3. Elige la app a la que enviarlo.

![Hoja de compartir o exportar con PDF, Text file y Page image](shots/05-share.png)

## Renombrar, etiquetar y eliminar

1. Abre un escaneo y toca **⋯**.
2. Elige **Rename** para cambiar el título, o **Edit tags** para añadir etiquetas separadas por comas.
3. Elige **Recognize text again** para volver a leer las páginas en otro idioma de texto. El texto que hayas editado se reemplaza.
4. Elige **Delete scan** para quitarlo de tu teléfono.

## Copia de seguridad y restauración de tus escaneos

1. En **Scans**, toca el icono de ajustes arriba a la derecha.
2. En **Storage**, toca **Back up scans**. Todos tus escaneos se empaquetan en un solo archivo.
3. Elige dónde guardar o enviar el archivo. El archivo no está cifrado, así que guárdalo en un lugar seguro.
4. En un teléfono nuevo, toca **Restore from backup** y elige el archivo. La app te pregunta antes de reemplazar todos los escaneos del teléfono por los de la copia.

## Bloquear la app y cambiar los ajustes

1. En **Scans**, toca el icono de ajustes arriba a la derecha.
2. Activa **App lock** para exigir tu huella, tu rostro o el bloqueo de pantalla antes de abrir tus escaneos.
3. En **Text language (OCR)**, elige el alfabeto de tus documentos. **Latin** incluye español, inglés, francés, alemán, indonesio y más. La app te sugiere el que usa el idioma de tu teléfono.
4. Toca **App language** para usar la app en un idioma distinto al de tu teléfono.
5. Elige **Image quality** (Balanced o Full) y el **Theme** (System, Light o Dark).

![Ajustes: Premium, App lock, Text language (OCR) e Image quality](shots/06-settings.png)

## Premium

Premium es un pago único, no una suscripción. Abre **Settings** y toca **See Premium**. Incluye:

- Sin anuncios.
- Texto en chino, japonés y coreano, además de hindi y otros textos devanagari en Android.
- Unir varios escaneos en un solo PDF o archivo de texto.
- Importar PDF más largos: hasta 50 páginas en lugar de 20.

Si ya compraste Premium antes, toca **Restore purchase** en la pantalla de Premium.

## Preguntas

**¿Funciona sin conexión?**
Sí. El escaneo, el reconocimiento de texto, la búsqueda y la exportación se hacen en tu teléfono.

**¿Dónde se guardan mis escaneos?**
Solo en tu dispositivo. Si desinstalas la app, los escaneos se eliminan con ella, así que toca antes **Back up scans** en Settings para conservarlos.

**El texto tiene errores. ¿Qué puedo hacer?**
Vuelve a hacer la foto con buena luz y la página bien plana, prueba el filtro **Magic** o **B&W**, y comprueba que **Text language (OCR)** coincida con el documento. También puedes corregir palabras sueltas con **Edit**.

**¿Puede leer letra manuscrita?**
Está pensada para texto impreso. La letra manuscrita suele leerse mal.

## Privacidad

Tus documentos nunca se suben. La versión gratuita muestra anuncios de Google AdMob. Lee la [política de privacidad](https://varian1.github.io/ocrscanner/privacy.html) completa.
