---
title: Bloquear pantalla con un toque
name: TapLock
tagline: Bloquea el móvil con un toque. El desbloqueo con huella y rostro sigue igual.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## Qué hace

TapLock pone un gran botón **Lock** en tu pantalla. Tócalo y el móvil se bloquea al instante, igual que al pulsar el botón de encendido. Es útil cuando el botón de encendido queda lejos, está gastado o se ha roto.

- Con el bloqueo por Accesibilidad, desbloqueas como siempre: con huella, rostro, PIN o patrón.
- El bloqueo con Administrador de dispositivo es otra forma de bloquear que funciona sin Accesibilidad.
- Una pantalla, un botón. Sin cuenta ni inicio de sesión.
- Gratis con anuncios.

## Primeros pasos

1. Abre TapLock. La primera vez, la línea bajo el botón **Lock** dice "One-time setup needed (about a minute)."
2. Toca **Set up TapLock**. Se abre la pantalla **Lock setup**.
3. Elige una de las dos formas de bloquear:
   - **Accessibility lock** (recomendado, Android 9 o posterior): bloquea como el botón de encendido y el desbloqueo con huella y rostro sigue funcionando.
   - **Device Admin lock**: funciona sin Accesibilidad. Android te pide el PIN, el patrón o la contraseña la próxima vez que desbloquees.
4. Sigue los pasos de la opción elegida que aparecen a continuación.

Puedes volver a abrir **Lock setup** cuando quieras con el icono de ajustes, arriba a la derecha de la pantalla de inicio.

## Activar el bloqueo por Accesibilidad

1. En **Lock setup**, en la tarjeta **Accessibility lock**, toca **Turn on Accessibility lock**.
2. Un cuadro de diálogo pregunta **Allow TapLock to use Accessibility?** Lee cómo usa TapLock este permiso.
3. Toca **Agree** para continuar. Si tocas **Decline**, no cambia nada y el bloqueo por Accesibilidad sigue desactivado.
4. Se abren los ajustes de Accesibilidad de Android. Busca TapLock, a menudo en "Downloaded apps".
5. Activa "Use TapLock", toca **Allow** y vuelve a TapLock.
6. La tarjeta ahora muestra **On** y arriba aparece **You're all set**. Toca **Back to Lock**.

![El cuadro de diálogo "Allow TapLock to use Accessibility?" con los botones Decline y Agree](shots/04-accessibility-consent.png)

**Por qué TapLock pide Accesibilidad.** TapLock usa la API del servicio de Accesibilidad solo para bloquear la pantalla cuando tocas el botón **Lock**, igual que al pulsar el botón de encendido. Por eso el desbloqueo con huella y rostro sigue funcionando. TapLock no lee tu pantalla, no ve lo que escribes y no recopila, guarda ni comparte datos personales a través de este permiso. Eliges **Agree** o **Decline** antes de que se abran los ajustes de Android, y puedes desactivarlo de nuevo en cualquier momento.

Si la tarjeta muestra **Starting** durante más de unos segundos, desactiva TapLock y vuelve a activarlo en los ajustes de Accesibilidad. Si el interruptor en los ajustes de Android aparece atenuado, toca **Switch greyed out?** en **Lock setup** y sigue la indicación.

## Usar el bloqueo con Administrador de dispositivo

1. En **Lock setup**, en la tarjeta **Device Admin lock**, toca **Enable Device Admin**.
2. Android te pide confirmar. TapLock usa este permiso solo para bloquear la pantalla cuando tocas el botón **Lock**.
3. La tarjeta ahora muestra **On**.

![Pantalla Lock setup: la tarjeta Accessibility lock muestra On y la tarjeta Device Admin lock tiene el botón Enable Device Admin](shots/02-setup.png)

Con esta forma de bloquear, Android te pide el PIN, el patrón o la contraseña la próxima vez que desbloquees, en lugar de la huella o el rostro. Si ambas opciones están activadas, TapLock usa el bloqueo por Accesibilidad.

## Bloquear la pantalla

1. Abre TapLock. La línea bajo el botón empieza con "Ready."
2. Toca **Lock**. La pantalla se bloquea al instante.
3. Desbloquea el móvil como siempre.

![Pantalla de inicio con el botón redondo Lock y la línea "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## Usar el modo oscuro

1. Activa el tema oscuro en los ajustes de Android de tu móvil.
2. Abre TapLock. La app sigue al móvil y cambia sola al modo oscuro. No hay un ajuste aparte en la app.

![La pantalla de inicio de TapLock en modo oscuro](shots/03-dark-mode.png)

## Cambiar el idioma

1. En la pantalla de inicio, toca el icono de ajustes para abrir **Lock setup**.
2. Abre el selector de idioma.
3. Elige uno de los 31 idiomas, o deja el predeterminado del sistema para que TapLock use el idioma de tu móvil.

![El selector de idioma con la lista de idiomas](shots/06-language.png)

El árabe, el urdu y el hebreo se muestran de derecha a izquierda. En Android 13 o posterior, también puedes cambiar el idioma de TapLock en los ajustes de idioma de apps de Android.

## Desactivar un método de bloqueo o desinstalar

1. En la pantalla de inicio, toca el icono de ajustes para abrir **Lock setup**.
2. Para desactivar el bloqueo por Accesibilidad, toca **Manage in Accessibility settings** y desactiva allí TapLock.
3. Para desactivar el bloqueo con Administrador de dispositivo, toca **Turn off Device Admin**.
4. Desactiva Device Admin antes de desinstalar TapLock. Android no permite desinstalar una app mientras es administradora activa del dispositivo.

![Lock setup con la tarjeta "You're all set" y el botón para desactivar Device Admin](shots/05-device-admin-on.png)

## Preguntas

**¿Por qué TapLock necesita el permiso de Accesibilidad?**
Solo para bloquear la pantalla cuando tocas **Lock**, igual que al pulsar el botón de encendido. No lee tu pantalla ni ve lo que escribes. Si prefieres no permitirlo, usa el bloqueo con Administrador de dispositivo.

**Mi huella no funciona después de bloquear con TapLock. ¿Por qué?**
Estás usando el bloqueo con Administrador de dispositivo, que hace que Android te pida una vez el PIN, el patrón o la contraseña. Activa el bloqueo por Accesibilidad para que el desbloqueo con huella y rostro siga funcionando.

**No puedo desinstalar TapLock. ¿Qué hago?**
Abre **Lock setup**, toca **Turn off Device Admin** y después desinstala la app.

**¿Qué versión de Android necesito?**
El bloqueo por Accesibilidad necesita Android 9 o posterior. En versiones anteriores, usa el bloqueo con Administrador de dispositivo.

**¿Puedo usar TapLock en mi idioma?**
Sí. TapLock está disponible en 31 idiomas. Elige el tuyo en **Lock setup**, o deja el predeterminado del sistema.

## Privacidad

TapLock usa los permisos de Accesibilidad y de Administrador de dispositivo solo para bloquear la pantalla y no recopila datos personales a través de ellos. La app muestra anuncios de Google AdMob; donde sea obligatorio, puedes cambiar tus opciones de anuncios en **Privacy settings** dentro de **Lock setup**. Lee la [política de privacidad](https://varian1.github.io/LockAppOnlyWeb/privacy.html) completa.
