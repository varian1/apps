---
title: Contador de Palabras y Texto
name: Text Toolkit
tagline: Cuenta palabras, cambia mayúsculas, limpia y compara texto sin internet.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## Qué hace

Text Toolkit es una sola pantalla con nueve herramientas de texto. Escribe o pega texto en el cuadro de arriba, elige una herramienta y copia o comparte el resultado. Cuenta palabras, cambia entre mayúsculas y minúsculas, limpia espacios, ordena líneas, busca y reemplaza, invierte, codifica, da formato a JSON y compara dos textos.

- Todas las herramientas funcionan en tu dispositivo y no necesitan internet.
- Sin cuenta. Tu texto nunca se sube a ningún servidor, y la app no usa tu cámara, tus fotos, tus contactos ni tu ubicación.
- Tu texto no se guarda. Desaparece al cerrar la app.
- Gratis. Puede aparecer un anuncio de banner en la parte inferior de la pantalla.

## Primeros pasos

1. Abre Text Toolkit. El cuadro **YOUR TEXT** trae un texto de ejemplo para que pruebes cada herramienta.
2. Toca **Clear** y escribe tu propio texto, o toca **Paste** para reemplazar el texto por lo que copiaste en otra app. **Sample** vuelve a poner el texto de ejemplo.
3. Elige una herramienta en la fila bajo el cuadro: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format** o **Diff**. Desliza la fila hacia los lados para verlas todas.

![Pantalla principal: el cuadro YOUR TEXT con Paste, Sample y Clear, la fila de herramientas y los números de Counter](shots/01-home.png)

La app usa el idioma de tu teléfono. Está disponible en 11 idiomas: inglés, español, portugués, alemán, francés, hindi, indonesio, árabe, italiano, ruso y turco.

## Contar palabras y caracteres

1. Toca **Counter**.
2. Lee los números: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines** y **Reading time**.
3. Mira **TOP WORDS** más abajo para ver las palabras que más usaste, hasta ocho, cada una con su cantidad.

Los números cambian mientras escribes. El tiempo de lectura se calcula con 200 palabras por minuto.

## Cambiar mayúsculas y minúsculas

1. Toca **Case**.
2. Recorre las tarjetas. Cada una muestra tu texto en otro estilo: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE** y **URL slug**.
3. Toca **Copy** en la tarjeta que quieras.

![Herramienta Case: tarjetas de UPPERCASE, lowercase y Title Case, cada una con Use input, Share y Copy](shots/02-case.png)

## Limpiar texto

1. Toca **Clean**.
2. Toca una acción:
   - **Clean all**: quita tabulaciones, espacios repetidos, espacios al final de las líneas, líneas vacías y líneas repetidas de una vez.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates** o **Remove tabs**: hace solo esa tarea.
   - La acción de saltos de línea: quita los saltos de línea de tu texto.
3. Lee el resultado en **CLEANED RESULT**. Tu texto en el cuadro se queda como estaba.

![Herramienta Clean: los botones de limpieza y la tarjeta CLEANED RESULT](shots/03-clean.png)

## Ordenar o invertir

1. Toca **Lines** para trabajar con líneas completas: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates** o **Reverse characters**. Al ordenar no se tienen en cuenta las mayúsculas ni los espacios al inicio de la línea.
2. Toca **Reverse** para dar la vuelta al texto: **Entire text**, **Each word**, **Word order**, **Line order** o **Characters per line**.
3. El resultado aparece en la tarjeta bajo los botones.

## Buscar y reemplazar

1. Toca **Replace**.
2. Escribe el texto que buscas en **Find** y el texto nuevo en **Replace with**.
3. Toca las opciones para activarlas o desactivarlas: **Replace all** (desactivada, cambia solo la primera coincidencia), **Case sensitive** y **Whole word**.
4. Revisa el número de reemplazos y **REPLACEMENT PREVIEW**. Ambos se actualizan mientras escribes.

![Herramienta Replace: los campos Find y Replace with, los tres botones de opciones, el número de reemplazos y la vista previa](shots/04-replace.png)

La búsqueda encuentra exactamente lo que escribes. No usa patrones ni comodines.

## Codificar, decodificar y dar formato

1. Toca **Encode**, elige **URL**, **Base64** o **HTML Entities** y luego toca **Encode** o **Decode**.
2. Toca **Format** y elige **Format JSON** para sangrar el JSON con dos espacios, **Minify JSON** para dejarlo en una sola línea, o **Strip Markdown** para convertir Markdown en texto sin formato.
3. Si el JSON tiene un error, una línea cerca de la parte superior de la pantalla empieza con "Invalid JSON" y explica qué falla.

## Comparar dos textos

1. Pon la primera versión en **YOUR TEXT** y toca **Diff**.
2. Escribe o pega la segunda versión en **COMPARE WITH**.
3. Lee **DIFF COMPARISON**. Las líneas que solo están en la segunda versión van en verde con un **+**. Las que solo están en la primera van en rojo con un **-**. Las líneas iguales no llevan marca.
4. Toca **Copy Diff** para copiar la comparación con sus marcas + y -.

![Herramienta Diff: el cuadro COMPARE WITH y la tarjeta DIFF COMPARISON con una línea añadida en verde y una eliminada en rojo](shots/05-diff.png)

## Copiar, compartir o seguir trabajando

1. Toca **Copy** en una tarjeta de resultado para ponerlo en el portapapeles.
2. Toca **Share** para enviarlo a otra app.
3. Toca **Use input** para pasar el resultado a **YOUR TEXT** y así usar otra herramienta con él.

## Premium

Todas las herramientas son gratis. Hay una compra opcional de pago único que quita los anuncios. Pagas una sola vez; no es una suscripción.

## Preguntas

**¿Funciona sin internet?**
Sí. Las nueve herramientas funcionan en tu teléfono. Solo los anuncios y la compra para quitarlos usan conexión a internet.

**¿Se guarda mi texto?**
No. La app conserva tu texto solo mientras está abierta. Copia o comparte el resultado que quieras conservar.

**¿Por qué el resultado está vacío después de cambiar de herramienta?**
Clean, Lines, Reverse, Encode y Format comparten una tarjeta de resultado, y se vacía al cambiar de herramienta. Toca la acción otra vez. Haz lo mismo después de editar tu texto. Counter, Case, Replace y Diff se actualizan solos.

**¿Sigue el modo oscuro?**
Sí. La app usa el tema claro u oscuro que tengas en el teléfono.

**¿Dónde están las licencias?**
Baja hasta el final y toca **Open-source licenses**. **Privacy policy** está justo al lado.

## Privacidad

Tu texto se procesa en tu teléfono y nunca se sube ni se guarda. La app puede mostrar anuncios de Google AdMob; cuando la ley lo exige, primero se te pide tu elección y puedes cambiarla con **Ad privacy choices** en la pantalla principal. Lee la [política de privacidad](https://varian1.github.io/text-toolkit/privacy.html) completa.
