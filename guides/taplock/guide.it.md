---
title: Blocca Schermo con un Tocco
name: TapLock
tagline: Blocca il telefono con un tocco. Impronta e volto continuano a funzionare.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## Cosa fa

TapLock mette un grande pulsante **Lock** sullo schermo. Toccalo e il telefono si blocca subito, proprio come premendo il tasto di accensione. È comodo quando il tasto di accensione è difficile da raggiungere, consumato o rotto.

- Con il blocco Accessibility sblocchi come sempre, con impronta, volto, PIN o sequenza.
- Il blocco Device Admin è un secondo modo di bloccare che funziona senza Accessibility.
- Una schermata, un pulsante. Nessun account e nessun accesso.
- Gratis, con pubblicità.

## Per iniziare

1. Apri TapLock. La prima volta, la riga sotto il pulsante **Lock** dice "One-time setup needed (about a minute)."
2. Tocca **Set up TapLock**. Si apre la schermata **Lock setup**.
3. Scegli uno dei due modi per bloccare:
   - **Accessibility lock** (consigliato, da Android 9 in su): blocca come il tasto di accensione e lo sblocco con impronta e volto continua a funzionare.
   - **Device Admin lock**: funziona senza Accessibility. Alla prossima sbloccatura Android ti chiede PIN, sequenza o password.
4. Segui qui sotto i passaggi per la tua scelta.

Puoi riaprire **Lock setup** quando vuoi con l'icona delle impostazioni in alto a destra nella schermata iniziale.

## Attivare il blocco Accessibility

1. In **Lock setup**, nella scheda **Accessibility lock**, tocca **Turn on Accessibility lock**.
2. Una finestra chiede **Allow TapLock to use Accessibility?** Leggi come TapLock usa questa funzione.
3. Tocca **Agree** per continuare. Se tocchi **Decline**, non cambia nulla e il blocco Accessibility resta disattivato.
4. Si aprono le impostazioni di accessibilità di Android. Cerca TapLock, spesso sotto "Downloaded apps".
5. Attiva "Use TapLock", tocca **Allow**, poi torna a TapLock.
6. Ora la scheda mostra **On** e in alto compare **You're all set**. Tocca **Back to Lock**.

![La finestra "Allow TapLock to use Accessibility?" con i pulsanti Decline e Agree](shots/04-accessibility-consent.png)

**Perché TapLock chiede l'accessibilità.** TapLock usa l'API del servizio di accessibilità solo per bloccare lo schermo quando tocchi il pulsante **Lock**, come premendo il tasto di accensione. Per questo lo sblocco con impronta e volto continua a funzionare. TapLock non legge lo schermo, non vede cosa scrivi e non raccoglie, conserva o condivide dati personali tramite questa autorizzazione. Scegli **Agree** o **Decline** prima che si aprano le impostazioni di Android e puoi disattivarla di nuovo in qualsiasi momento.

Se la scheda mostra **Starting** per più di qualche secondo, disattiva e riattiva TapLock nelle impostazioni di accessibilità. Se l'interruttore nelle impostazioni di Android è grigio, tocca **Switch greyed out?** in **Lock setup** e segui il suggerimento.

## Usare invece il blocco Device Admin

1. In **Lock setup**, nella scheda **Device Admin lock**, tocca **Enable Device Admin**.
2. Android ti chiede di confermare. TapLock usa questa autorizzazione solo per bloccare lo schermo quando tocchi il pulsante **Lock**.
3. Ora la scheda mostra **On**.

![La schermata Lock setup: la scheda Accessibility lock mostra On e la scheda Device Admin lock ha il pulsante Enable Device Admin](shots/02-setup.png)

Con questo modo di bloccare, alla prossima sbloccatura Android chiede PIN, sequenza o password invece di impronta o volto. Se entrambi i modi sono attivi, TapLock usa il blocco Accessibility.

## Bloccare lo schermo

1. Apri TapLock. La riga sotto il pulsante inizia con "Ready."
2. Tocca **Lock**. Lo schermo si blocca subito.
3. Sblocca il telefono come fai di solito.

![La schermata iniziale con il pulsante rotondo Lock e la riga "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## Usare la modalità scura

1. Attiva il tema scuro nelle impostazioni Android del telefono.
2. Apri TapLock. Segue il telefono e passa da solo al tema scuro. Nell'app non c'è un'impostazione separata.

![La schermata iniziale di TapLock in modalità scura](shots/03-dark-mode.png)

## Cambiare lingua

1. Nella schermata iniziale, tocca l'icona delle impostazioni per aprire **Lock setup**.
2. Apri il selettore della lingua.
3. Scegli una delle 31 lingue, oppure lascia l'impostazione di sistema così TapLock segue la lingua del telefono.

![Il selettore della lingua con l'elenco delle lingue](shots/06-language.png)

Arabo, urdu ed ebraico sono mostrati da destra a sinistra. Da Android 13 in su puoi cambiare la lingua di TapLock anche nelle impostazioni di lingua delle app di Android.

## Disattivare un metodo di blocco o disinstallare

1. Nella schermata iniziale, tocca l'icona delle impostazioni per aprire **Lock setup**.
2. Per disattivare il blocco Accessibility, tocca **Manage in Accessibility settings** e disattiva TapLock da lì.
3. Per disattivare il blocco Device Admin, tocca **Turn off Device Admin**.
4. Disattiva Device Admin prima di disinstallare TapLock. Android non permette di disinstallare un'app che è un amministratore del dispositivo attivo.

![Lock setup con la scheda "You're all set" e il pulsante per disattivare Device Admin](shots/05-device-admin-on.png)

## Domande

**Perché TapLock ha bisogno dell'autorizzazione Accessibility?**
Solo per bloccare lo schermo quando tocchi **Lock**, come premendo il tasto di accensione. Non legge lo schermo e non vede cosa scrivi. Se preferisci non concederla, usa il blocco Device Admin.

**Dopo il blocco con TapLock l'impronta non funziona. Perché?**
Stai usando il blocco Device Admin, che fa chiedere ad Android PIN, sequenza o password una volta. Attiva il blocco Accessibility per continuare a usare impronta e volto.

**Non riesco a disinstallare TapLock. Cosa posso fare?**
Apri **Lock setup**, tocca **Turn off Device Admin**, poi disinstalla.

**Quale versione di Android serve?**
Il blocco Accessibility richiede Android 9 o successivo. Sulle versioni precedenti usa il blocco Device Admin.

**Posso usare TapLock in italiano?**
Sì. TapLock è disponibile in 31 lingue. Scegli la tua in **Lock setup**, oppure lascia l'impostazione di sistema.

## Privacy

TapLock usa le autorizzazioni Accessibility e Device Admin solo per bloccare lo schermo e non raccoglie dati personali tramite esse. L'app mostra annunci di Google AdMob; dove richiesto, puoi modificare le tue scelte sugli annunci con **Privacy settings** in **Lock setup**. Leggi l'[informativa sulla privacy](https://varian1.github.io/LockAppOnlyWeb/privacy.html) completa.
