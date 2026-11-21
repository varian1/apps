---
title: AppLock: Apps vergrendelen
name: AppLock
tagline: Vergrendel apps met pincode, patroon, wachtwoord of vingerafdruk. Werkt offline.
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.0
updated: 2026-11-10
privacy: https://varian1.github.io/privacy.html
---

## Wat de app doet

AppLock zet een vergrendelscherm voor de apps die u kiest. Wie een vergrendelde app opent, moet eerst uw pincode, patroon of wachtwoord invoeren, of uw vingerafdruk gebruiken, voordat de app zichtbaar wordt. In de app staat de naam geschreven als "App Lock".

- Geen account. Uw pincode, uw lijst met vergrendelde apps, het beveiligingslogboek en de foto's van indringers blijven op uw telefoon en worden nooit geüpload.
- De app kan een foto maken van iemand die steeds een verkeerde code invoert.
- Met een herstelcode komt u weer binnen als u uw pincode vergeet.
- Gratis met advertenties. Apps vergrendelen is altijd gratis. Met een eenmalige Premium-aankoop verdwijnen de advertenties en krijgt u extra functies.

## Aan de slag

1. Open AppLock en tik op **Get started**.
2. Kies onder **How do you want to unlock?** voor **PIN**, **Pattern** of **Password**.
3. Voer de code in en voer hem daarna nog een keer in ter bevestiging. Een pincode bestaat uit 6 cijfers. Een patroon verbindt minstens 4 stippen. Een wachtwoord heeft minstens 4 tekens. Tik bij een patroon of wachtwoord na elke invoer op **Continue**.
4. Schrijf op **Save your recovery code** de code van 8 cijfers op en bewaar hem op een veilige plek. U ziet hem maar één keer. Het is de enige manier om weer binnen te komen als u uw pincode, patroon of wachtwoord vergeet.
5. Vink **I’ve saved this code somewhere safe** aan en tik op **Continue**.

Nu bent u op het beginscherm. Daar staat **Protection off** totdat u de rechten toestaat en uw eerste app vergrendelt.

## De rechten toestaan

AppLock kan een app alleen vergrendelen als Android toestaat dat de app merkt dat een andere app wordt geopend en het vergrendelscherm er bovenop mag tonen. Daarvoor zijn twee rechten nodig: **Accessibility** en **Display over other apps**. De andere rechten zijn optioneel.

1. Tik op het beginscherm op **Finish setup** of **Permissions**.
2. Tik op **Accessibility**. AppLock toont eerst een pagina met de titel **What Accessibility access does**. Lees die goed door.
3. Tik op **I understand — open settings**. Bent u het er niet mee eens, tik dan op **Not now**: er verandert niets en er worden geen instellingen geopend.
4. Zet in het Android-instellingenscherm dat opent de service voor AppLock aan en ga terug naar AppLock.
5. Tik op **Display over other apps** en sta dit toe in het Android-instellingenscherm.
6. Tik op andere rijen die u wilt toestaan. Bij een rij staat **Granted** als het gelukt is.

![De pagina "What Accessibility access does", die verschijnt voordat de Android-instellingen openen](shots/05-accessibility-disclosure.png)

**Waarom AppLock om Accessibility vraagt.** AppLock gebruikt de Accessibility-service van Android voor maar één doel: merken welke app er net naar voren is gekomen, zodat het vergrendelscherm kan verschijnen boven de apps die u wilt beschermen.

- Wat de app doet: ze let alleen op de naam van de app die net is geopend, en niets anders. Wordt een vergrendelde app ontgrendeld of wordt een verkeerde code ingevoerd, dan wordt de naam van die app opgeslagen in het **Security log** op uw telefoon, zodat u het kunt nakijken.
- Wat de app nooit doet: ze leest nooit de inhoud van het scherm, toetsaanslagen, wachtwoorden, berichten of andere gegevens op het scherm, niet in AppLock en niet in andere apps. Er wordt niets van uw apparaat verstuurd.
- U kunt dit op elk moment uitzetten in de Android-instellingen. AppLock kan dan geen vergrendelscherm meer tonen.

**Waarvoor de andere rechten dienen.**

- **Display over other apps**: laat het vergrendelscherm boven een vergrendelde app verschijnen.
- **Usage access**: helpt te controleren of de beveiliging betrouwbaar werkt.
- **Notifications**: waarschuwt u bij vergrendelmeldingen en inbraakpogingen.
- **Camera** (optioneel): maakt een foto van wie niet kan ontgrendelen.
- **Notification access**: verbergt de inhoud van meldingen van vergrendelde apps.
- **Ignore battery optimization**: houdt de beveiliging op de achtergrond actief.

Elk recht wordt alleen op uw telefoon gebruikt.

![Scherm met rechten: elk recht met uitleg en een groen label Granted](shots/03-permissions.png)

## Kies de apps die u wilt vergrendelen

1. Tik op het beginscherm op **Lock apps**.
2. Zoek de app. Typ de naam in **Search apps**, of wissel tussen de tabbladen **User**, **System** en **Recent**. Bij **Recent** staan de nieuwste installaties bovenaan.
3. Zet de schakelaar aan naast elke app die u wilt vergrendelen.
4. Ga terug. Het beginscherm toont **Protected** en het aantal vergrendelde apps.

![De lijst Lock apps met een zoekveld, tabbladen en een schakelaar bij elke app](shots/06-lock-apps.png)

Wilt u een app voorgoed ontgrendelen, open dan **Lock apps** opnieuw en zet de schakelaar uit.

![Beginscherm met Protected, 6 apps vergrendeld, met Lock apps, Permissions, Security log, Intruder photos en Settings](shots/01-home.png)

## Een vergrendelde app openen

1. Open een app die u hebt vergrendeld. Het vergrendelscherm verschijnt meteen.
2. Voer uw pincode, patroon of wachtwoord in. Als u **Unlock with biometrics** hebt aangezet, kunt u in plaats daarvan uw vingerafdruk gebruiken.
3. Na een foute invoer kunt u het opnieuw proberen. Na te veel foute pogingen moet u even wachten.

AppLock zelf is op dezelfde manier vergrendeld, zodat niemand anders uw instellingen kan wijzigen.

![Vergrendelscherm met "Enter your PIN" en het cijferpaneel](shots/02-lock-screen.png)

## De vergrendeling aanpassen

1. Tik op het beginscherm op **Settings**.
2. Kies onder **Appearance** voor **System**, **Light** of **Dark**.
3. Kies onder **Re-lock** wanneer een ontgrendelde app weer wordt vergrendeld: **Immediately** zodra u de app verlaat, **On screen off**, of **After 5 min**.
4. Zet onder **Security** **Unlock with biometrics** aan. U bevestigt eerst uw pincode, patroon of wachtwoord. Hiervoor moet er al een vingerafdruk of gezicht op uw telefoon zijn ingesteld.
5. Zet onder **Protection** **Scramble the PIN pad** aan om de cijfertoetsen door elkaar te husselen, zodat niemand uw pincode kan raden aan de plek waar u tikt.
6. Zet **Hide notification content for locked apps** aan om berichten van vergrendelde apps privé te houden. Hiervoor is **Notification access** nodig bij **Permissions**.
7. Zet onder **Disguise** **Hide from Recents** aan om AppLock uit de lijst met recente apps te houden.

![Instellingen: de Premium-kaart, Appearance, Re-lock en Security](shots/04-settings.png)

## Zien wie erin probeerde te komen

1. Open **Settings** en zet **Intruder photo after failed attempts** aan.
2. Open **Permissions** en sta **Camera** toe.
3. Vanaf nu maakt de voorste camera een foto na drie foute invoeren achter elkaar op het vergrendelscherm.
4. Tik op het beginscherm op **Intruder photos** om de foto's te bekijken, elk met de app die werd geopend.
5. Tik op **Security log** om ontgrendelingen, mislukte pogingen en gewijzigde instellingen te zien.

![Scherm Intruder photos met foto's die zijn gemaakt na mislukte ontgrendelpogingen](shots/07-intruder-photos.png)

## Weer binnenkomen als u uw pincode vergeten bent

1. Open AppLock. Tik op het ontgrendelscherm op **Can’t get in?**
2. Voer de herstelcode van 8 cijfers in die u hebt bewaard en tik op **Continue**.
3. Stel een nieuwe pincode, een nieuw patroon of wachtwoord in. Daarna krijgt u een nieuwe herstelcode; de oude werkt dan niet meer.

Wilt u een nieuwe herstelcode terwijl u uw pincode nog weet, open dan **Settings** en tik op **Replace recovery code**.

## Premium

Premium is een eenmalige betaling, geen abonnement. Open **Settings** en tik op **Unlock Premium**. Apps vergrendelen blijft ook zonder Premium gratis. Premium geeft u:

- Geen advertenties.
- **Fake crash screen (long-press to unlock)**: een vergrendelde app lijkt gecrasht in plaats van het vergrendelscherm te tonen.
- Vermomde pictogrammen: verander het pictogram en de naam van AppLock op uw startscherm in **Calculator**, **Notes** of **Weather**. Bij **Calculator** kunt u **Open a real calculator instead** aanzetten en een **Secret code** instellen: typ de code en druk op = om AppLock te openen. Uw pincode werkt altijd ook.
- De volledige geschiedenis van foto's van indringers. De gratis versie toont de nieuwste 5.
- **Export backup**: een versleutelde kopie van uw instellingen en vergrendelde apps, beveiligd met een wachtwoord dat u zelf kiest. **Restore backup** is gratis.

Hebt u Premium al eerder gekocht, tik dan in **Settings** op **Restore purchases**.

## Veelgestelde vragen

**Waarom heeft AppLock het recht Accessibility nodig?**
Alleen om te merken welke app er net is geopend, zodat het vergrendelscherm boven uw vergrendelde apps kan verschijnen. AppLock leest nooit wat er op uw scherm staat of wat u typt. Zie "De rechten toestaan" hierboven.

**Op het beginscherm staat "Protection off". Wat is er mis?**
Of **Accessibility** of **Display over other apps** is niet toegestaan, of er is nog geen app vergrendeld. Tik op **Finish setup** om de lijst met rechten te openen en controleer daarna **Lock apps**.

**Kan ik AppLock helemaal verbergen?**
Nee. Android houdt altijd een pictogram van een geïnstalleerde app. Met Premium kunt u het pictogram en de naam wel vervangen door een vermomming.

**Ik ben mijn pincode vergeten en ben de herstelcode kwijt. Kunnen jullie die resetten?**
Nee. AppLock werkt offline en zonder account, dus er is geen reset per e-mail. De herstelcode is de enige manier om weer binnen te komen. Bewaar hem op een veilige plek.

**Bevat een back-up mijn pincode of de foto's van indringers?**
Nee. Nadat u een back-up hebt hersteld, vraagt de app u eerst een nieuwe pincode, een nieuw patroon of wachtwoord in te stellen.

## Privacy

Uw pincode, uw vergrendelde apps, het beveiligingslogboek en de foto's van indringers blijven op uw apparaat en worden nooit geüpload. De gratis versie toont advertenties van Google AdMob. Lees het volledige [privacybeleid](https://varian1.github.io/privacy.html).
