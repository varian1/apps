---
title: AppLock: Bloquear apps con PIN
name: AppLock
tagline: Bloquea cualquier app con PIN, patrón, contraseña o huella. Funciona sin conexión.
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.0
updated: 2026-11-10
privacy: https://varian1.github.io/privacy.html
---

## Qué hace

AppLock pone una pantalla de bloqueo delante de las apps que elijas. Cuando alguien abre una app bloqueada, debe introducir tu PIN, patrón o contraseña, o usar tu huella, antes de poder verla. Dentro de la app el nombre se escribe "App Lock".

- Sin cuenta. Tu PIN, la lista de apps bloqueadas, el registro de seguridad y las fotos de intrusos se quedan en tu teléfono y nunca se suben.
- Puede hacer una foto a quien siga introduciendo un código incorrecto.
- Un código de recuperación te permite volver a entrar si olvidas tu PIN.
- Gratis con anuncios. Bloquear apps es siempre gratis. Una compra única de Premium quita los anuncios y añade extras.

## Primeros pasos

1. Abre AppLock y toca **Get started**.
2. En **How do you want to unlock?**, elige **PIN**, **Pattern** o **Password**.
3. Introdúcelo y vuelve a introducirlo para confirmar. Un PIN tiene 6 dígitos. Un patrón une al menos 4 puntos. Una contraseña tiene al menos 4 caracteres. Con patrón o contraseña, toca **Continue** después de cada entrada.
4. En **Save your recovery code**, anota el código de 8 dígitos y guárdalo en un lugar seguro. Solo lo ves una vez y es la única forma de volver a entrar si olvidas tu PIN, patrón o contraseña.
5. Marca **I’ve saved this code somewhere safe** y toca **Continue**.

Ya estás en la pantalla de inicio. Muestra **Protection off** hasta que concedas los permisos y bloquees tu primera app.

## Conceder los permisos

AppLock solo puede bloquear una app si Android le permite detectar que se ha abierto y le deja mostrar la pantalla de bloqueo encima. Para eso necesita dos permisos: **Accessibility** y **Display over other apps**. Los demás permisos son opcionales.

1. En la pantalla de inicio, toca **Finish setup** o **Permissions**.
2. Toca **Accessibility**. Primero, AppLock muestra una página llamada **What Accessibility access does**. Léela.
3. Toca **I understand — open settings**. Si no estás de acuerdo, toca **Not now**: no se cambia nada y no se abre ningún ajuste.
4. En la pantalla de ajustes de Android que se abre, activa el servicio para AppLock y vuelve a AppLock.
5. Toca **Display over other apps** y permítelo en la pantalla de ajustes de Android.
6. Toca cualquier otra fila que quieras permitir. Cuando está hecho, la fila muestra **Granted**.

![La página "What Accessibility access does", que se muestra antes de abrir los ajustes de Android](shots/05-accessibility-disclosure.png)

**Por qué AppLock pide Accessibility.** AppLock usa el servicio de accesibilidad de Android con un único fin: detectar qué app acaba de pasar al primer plano, para mostrar la pantalla de bloqueo sobre las apps que elegiste proteger.

- Qué hace: vigila el nombre de la app que acaba de abrirse, y nada más. Cuando se desbloquea una app bloqueada o se introduce un código incorrecto, el nombre de esa app se guarda en el **Security log** de tu teléfono para que puedas revisarlo.
- Qué nunca hace: nunca lee el contenido de la pantalla, las pulsaciones de teclas, las contraseñas, los mensajes ni ningún otro dato en pantalla, ni en AppLock ni en otras apps. No se envía nada fuera de tu dispositivo.
- Puedes desactivarlo en cualquier momento en los Ajustes de Android. Entonces AppLock simplemente ya no podrá mostrar la pantalla de bloqueo.

**Para qué sirven los demás permisos.**

- **Display over other apps**: permite que la pantalla de bloqueo aparezca encima de una app bloqueada.
- **Usage access**: ayuda a confirmar que la protección funciona de forma fiable.
- **Notifications**: te avisa de las peticiones de bloqueo y de los intentos de intrusión.
- **Camera** (opcional): hace una foto a quien falla al desbloquear.
- **Notification access**: oculta el contenido de las notificaciones de las apps bloqueadas.
- **Ignore battery optimization**: mantiene la protección activa en segundo plano.

Todos los permisos se usan solo en tu teléfono.

![Pantalla de permisos: cada permiso con su motivo y una etiqueta verde Granted](shots/03-permissions.png)

## Elegir las apps que bloquear

1. En la pantalla de inicio, toca **Lock apps**.
2. Busca la app. Escribe su nombre en **Search apps** o cambia entre las pestañas **User**, **System** y **Recent**. **Recent** muestra primero las instalaciones más nuevas.
3. Activa el interruptor junto a cada app que quieras bloquear.
4. Vuelve atrás. La pantalla de inicio muestra **Protected** y el número de apps bloqueadas.

![La lista Lock apps con un campo de búsqueda, pestañas y un interruptor para cada app](shots/06-lock-apps.png)

Para desbloquear una app de forma definitiva, abre **Lock apps** otra vez y desactiva su interruptor.

![Pantalla de inicio con Protected, 6 apps bloqueadas, y Lock apps, Permissions, Security log, Intruder photos y Settings](shots/01-home.png)

## Abrir una app bloqueada

1. Abre una app que hayas bloqueado. La pantalla de bloqueo la cubre al instante.
2. Introduce tu PIN, patrón o contraseña. Si activaste **Unlock with biometrics**, puedes usar tu huella en su lugar.
3. Tras una entrada incorrecta puedes intentarlo de nuevo. Tras demasiadas entradas incorrectas tendrás que esperar un momento.

AppLock también se bloquea de la misma manera, así que nadie más puede cambiar tus ajustes.

![Pantalla de bloqueo con "Enter your PIN" y el teclado numérico](shots/02-lock-screen.png)

## Cambiar cómo funciona el bloqueo

1. En la pantalla de inicio, toca **Settings**.
2. En **Appearance**, elige **System**, **Light** o **Dark**.
3. En **Re-lock**, elige cuándo se vuelve a bloquear una app que desbloqueaste: **Immediately** al salir de ella, **On screen off** o **After 5 min**.
4. En **Security**, activa **Unlock with biometrics**. Primero confirmas tu PIN, patrón o contraseña. Para esto necesitas una huella o un rostro ya configurados en tu teléfono.
5. En **Protection**, activa **Scramble the PIN pad** para mezclar las teclas numéricas, de modo que nadie pueda adivinar tu PIN por el lugar donde tocas.
6. Activa **Hide notification content for locked apps** para mantener privados los mensajes de las apps bloqueadas. Para esto necesitas **Notification access** en **Permissions**.
7. En **Disguise**, activa **Hide from Recents** para que AppLock no aparezca en la lista de apps recientes.

![Settings: la tarjeta Premium, Appearance, Re-lock y Security](shots/04-settings.png)

## Ver quién intentó entrar

1. Abre **Settings** y activa **Intruder photo after failed attempts**.
2. Abre **Permissions** y permite **Camera**.
3. A partir de ahora, tras tres entradas incorrectas seguidas en la pantalla de bloqueo, la cámara frontal hace una foto.
4. En la pantalla de inicio, toca **Intruder photos** para ver las fotos, cada una con la app que se abrió.
5. Toca **Security log** para ver los desbloqueos, los intentos fallidos y los cambios de ajustes.

![Pantalla Intruder photos con fotos hechas tras intentos fallidos de desbloqueo](shots/07-intruder-photos.png)

## Volver a entrar si olvidaste tu PIN

1. Abre AppLock. En la pantalla de desbloqueo, toca **Can’t get in?**
2. Introduce el código de recuperación de 8 dígitos que guardaste y toca **Continue**.
3. Define un nuevo PIN, patrón o contraseña. Después recibes un nuevo código de recuperación; el anterior deja de funcionar.

Para obtener un nuevo código de recuperación mientras aún recuerdas tu PIN, abre **Settings** y toca **Replace recovery code**.

## Premium

Premium es un pago único, no una suscripción. Abre **Settings** y toca **Unlock Premium**. Bloquear apps sigue siendo gratis sin él. Premium te da:

- Sin anuncios.
- **Fake crash screen (long-press to unlock)**: una app bloqueada parece haberse cerrado por un error, en lugar de mostrar la pantalla de bloqueo.
- Iconos de disfraz: cambia el icono y el nombre de AppLock en tu pantalla de inicio por **Calculator**, **Notes** o **Weather**. Con **Calculator** puedes activar **Open a real calculator instead** y definir un **Secret code**: escribe el código y pulsa = para abrir AppLock. Tu PIN también funciona siempre.
- El historial completo de fotos de intrusos. La versión gratuita muestra las 5 más recientes.
- **Export backup**: una copia cifrada de tus ajustes y de la lista de apps bloqueadas, protegida con una contraseña que tú eliges. **Restore backup** es gratis.

Si ya compraste Premium, toca **Restore purchases** en **Settings**.

## Preguntas

**¿Por qué AppLock necesita el permiso de Accessibility?**
Solo para detectar qué app se acaba de abrir y así mostrar la pantalla de bloqueo sobre las apps que bloqueaste. Nunca lee lo que hay en tu pantalla ni lo que escribes. Consulta "Conceder los permisos" más arriba.

**La pantalla de inicio dice "Protection off". ¿Qué pasa?**
Falta permitir **Accessibility** o **Display over other apps**, o todavía no hay ninguna app bloqueada. Toca **Finish setup** para abrir la lista de permisos y después revisa **Lock apps**.

**¿Puedo ocultar AppLock por completo?**
No. Android siempre conserva un icono de cada app instalada. Con Premium puedes cambiar el icono y el nombre por un disfraz.

**Olvidé mi PIN y perdí el código de recuperación. ¿Pueden restablecerlo?**
No. AppLock funciona sin conexión y sin cuenta, así que no hay restablecimiento por correo. El código de recuperación es la única forma de volver a entrar. Guárdalo en un lugar seguro.

**¿Una copia de seguridad incluye mi PIN o las fotos de intrusos?**
No. Después de restaurar una copia, la app te pide primero definir un nuevo PIN, patrón o contraseña.

## Privacidad

Tu PIN, tus apps bloqueadas, el registro de seguridad y las fotos de intrusos se quedan en tu dispositivo y nunca se suben. La versión gratuita muestra anuncios de Google AdMob. Lee la [política de privacidad](https://varian1.github.io/privacy.html) completa.
