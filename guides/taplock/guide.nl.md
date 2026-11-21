---
title: Scherm vergrendelen: één tik
name: TapLock
tagline: Vergrendel je telefoon met één tik. Vingerafdruk en gezicht werken gewoon door.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## Wat de app doet

TapLock zet één grote knop **Lock** op je scherm. Tik erop en je telefoon vergrendelt meteen, net als met de aan/uit-knop. Handig als die knop lastig te bereiken, versleten of kapot is.

- Met Accessibility lock ontgrendel je zoals altijd: met vingerafdruk, gezicht, pincode of patroon.
- Device Admin lock is een tweede manier om te vergrendelen, zonder Accessibility.
- Eén scherm, één knop. Geen account en geen inloggen.
- Gratis, met advertenties.

## Aan de slag

1. Open TapLock. De eerste keer staat onder de knop **Lock** de tekst "One-time setup needed (about a minute)."
2. Tik op **Set up TapLock**. Het scherm **Lock setup** opent.
3. Kies een van de twee manieren om te vergrendelen:
   - **Accessibility lock** (aanbevolen, Android 9 of nieuwer): vergrendelt als de aan/uit-knop, en ontgrendelen met vingerafdruk of gezicht blijft werken.
   - **Device Admin lock**: werkt zonder Accessibility. Android vraagt bij het volgende ontgrendelen om je pincode, patroon of wachtwoord.
4. Volg hieronder de stappen voor jouw keuze.

Je kunt **Lock setup** altijd weer openen met het instellingenicoon rechtsboven op het beginscherm.

## Accessibility lock aanzetten

1. Tik op **Lock setup** in de kaart **Accessibility lock** op **Turn on Accessibility lock**.
2. Een venster vraagt **Allow TapLock to use Accessibility?** Lees hoe TapLock dit gebruikt.
3. Tik op **Agree** om door te gaan. Tik je op **Decline**, dan verandert er niets en blijft Accessibility lock uit.
4. De toegankelijkheidsinstellingen van Android openen. Zoek TapLock, vaak onder "Downloaded apps".
5. Zet "Use TapLock" aan, tik op **Allow** en ga terug naar TapLock.
6. De kaart toont nu **On** en bovenaan staat **You're all set**. Tik op **Back to Lock**.

![Het venster "Allow TapLock to use Accessibility?" met de knoppen Decline en Agree](shots/04-accessibility-consent.png)

**Waarom TapLock om Accessibility vraagt.** TapLock gebruikt de Accessibility Service API alleen om je scherm te vergrendelen als je op de knop **Lock** tikt, net als met de aan/uit-knop. Daarom blijft ontgrendelen met vingerafdruk of gezicht werken. TapLock leest je scherm niet, ziet niet wat je typt en verzamelt, bewaart of deelt geen persoonlijke gegevens via deze toestemming. Je kiest **Agree** of **Decline** voordat de instellingen van Android openen, en je kunt de toestemming op elk moment weer uitzetten.

Staat de kaart langer dan een paar seconden op **Starting**? Zet TapLock dan uit en weer aan in de toegankelijkheidsinstellingen. Is de schakelaar in de instellingen van Android grijs? Tik dan op **Lock setup** op **Switch greyed out?** en volg de tip daar.

## Device Admin lock gebruiken

1. Tik op **Lock setup** in de kaart **Device Admin lock** op **Enable Device Admin**.
2. Android vraagt om bevestiging. TapLock gebruikt deze toestemming alleen om het scherm te vergrendelen als je op de knop **Lock** tikt.
3. De kaart toont nu **On**.

![Scherm Lock setup: de kaart Accessibility lock toont On en de kaart Device Admin lock heeft de knop Enable Device Admin](shots/02-setup.png)

Bij deze manier van vergrendelen vraagt Android bij het volgende ontgrendelen om je pincode, patroon of wachtwoord in plaats van vingerafdruk of gezicht. Staan beide manieren aan, dan gebruikt TapLock Accessibility lock.

## Je scherm vergrendelen

1. Open TapLock. De tekst onder de knop begint met "Ready."
2. Tik op **Lock**. Het scherm vergrendelt meteen.
3. Ontgrendel je telefoon zoals je gewend bent.

![Beginscherm met de ronde knop Lock en de tekst "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## Donkere modus gebruiken

1. Zet het donkere thema aan in de Android-instellingen van je telefoon.
2. Open TapLock. De app volgt je telefoon en schakelt vanzelf over op donker. Er is geen aparte instelling in de app.

![Het beginscherm van TapLock in donkere modus](shots/03-dark-mode.png)

## De taal wijzigen

1. Tik op het beginscherm op het instellingenicoon om **Lock setup** te openen.
2. Open de taalkeuze.
3. Kies een van de 31 talen, of houd de systeemstandaard aan, zodat TapLock de taal van je telefoon volgt.

![De taalkeuze met de lijst met talen](shots/06-language.png)

Arabisch, Urdu en Hebreeuws worden van rechts naar links getoond. Op Android 13 of nieuwer kun je de taal van TapLock ook wijzigen in de app-taalinstellingen van Android.

## Een vergrendelmethode uitzetten of de app verwijderen

1. Tik op het beginscherm op het instellingenicoon om **Lock setup** te openen.
2. Om Accessibility lock uit te zetten, tik je op **Manage in Accessibility settings** en zet je TapLock daar uit.
3. Om Device Admin lock uit te zetten, tik je op **Turn off Device Admin**.
4. Zet Device Admin uit voordat je TapLock verwijdert. Android staat niet toe dat je een app verwijdert zolang die actieve apparaatbeheerder is.

![Lock setup met de kaart "You're all set" en de knop om Device Admin uit te zetten](shots/05-device-admin-on.png)

## Vragen

**Waarom heeft TapLock de toestemming Accessibility nodig?**
Alleen om het scherm te vergrendelen als je op **Lock** tikt, net als met de aan/uit-knop. De app leest je scherm niet en ziet niet wat je typt. Wil je dit liever niet toestaan, gebruik dan Device Admin lock.

**Mijn vingerafdruk werkt niet na vergrendelen met TapLock. Waarom niet?**
Je gebruikt Device Admin lock. Daardoor vraagt Android één keer om je pincode, patroon of wachtwoord. Zet Accessibility lock aan om ontgrendelen met vingerafdruk of gezicht te houden.

**Ik kan TapLock niet verwijderen. Wat nu?**
Open **Lock setup**, tik op **Turn off Device Admin** en verwijder de app daarna.

**Welke Android-versie heb ik nodig?**
Accessibility lock vraagt Android 9 of nieuwer. Gebruik op oudere versies Device Admin lock.

**Kan ik TapLock in mijn eigen taal gebruiken?**
Ja. TapLock is er in 31 talen. Kies de jouwe op **Lock setup**, of houd de systeemstandaard aan.

## Privacy

TapLock gebruikt de toestemmingen Accessibility en Device Admin alleen om je scherm te vergrendelen en verzamelt hiermee geen persoonlijke gegevens. De app toont advertenties van Google AdMob. Waar dat verplicht is, kun je je advertentiekeuzes wijzigen met **Privacy settings** op **Lock setup**. Lees het volledige [privacybeleid](https://varian1.github.io/LockAppOnlyWeb/privacy.html).
