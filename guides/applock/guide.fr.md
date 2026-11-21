---
title: Verrouillage d'appli par PIN
name: AppLock
tagline: Verrouillez vos applis par PIN, schéma, mot de passe ou empreinte. Hors ligne.
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.0
updated: 2026-11-10
privacy: https://varian1.github.io/privacy.html
---

## Ce que fait l'appli

AppLock place un écran de verrouillage devant les applis que vous choisissez. Quand quelqu'un ouvre une appli verrouillée, il doit saisir votre PIN, votre schéma ou votre mot de passe, ou utiliser votre empreinte, avant de pouvoir la voir. Dans l'appli, le nom s'écrit « App Lock ».

- Aucun compte. Votre PIN, votre liste d'applis verrouillées, le journal de sécurité et les photos d'intrus restent sur votre téléphone et ne sont jamais envoyés.
- L'appli peut photographier une personne qui saisit sans cesse un mauvais code.
- Un code de récupération vous permet de revenir si vous oubliez votre PIN.
- Gratuite avec publicités. Le verrouillage des applis est toujours gratuit. Un achat Premium unique supprime les publicités et ajoute des extras.

## Prise en main

1. Ouvrez AppLock et appuyez sur **Get started**.
2. Sous **How do you want to unlock?**, choisissez **PIN**, **Pattern** ou **Password**.
3. Saisissez-le, puis saisissez-le une seconde fois pour confirmer. Un PIN compte 6 chiffres. Un schéma relie au moins 4 points. Un mot de passe compte au moins 4 caractères. Pour un schéma ou un mot de passe, appuyez sur **Continue** après chaque saisie.
4. Sur l'écran **Save your recovery code**, notez le code à 8 chiffres et conservez-le en lieu sûr. Vous ne le voyez qu'une seule fois, et c'est le seul moyen de revenir si vous oubliez votre PIN, votre schéma ou votre mot de passe.
5. Cochez **I’ve saved this code somewhere safe** et appuyez sur **Continue**.

Vous êtes maintenant sur l'écran d'accueil. Il affiche **Protection off** tant que vous n'avez pas accordé les autorisations et verrouillé votre première appli.

## Accorder les autorisations

AppLock ne peut verrouiller une appli que si Android lui permet de remarquer l'ouverture de cette appli et d'afficher l'écran de verrouillage par-dessus. Il faut pour cela deux autorisations : **Accessibility** et **Display over other apps**. Les autres autorisations sont facultatives.

1. Sur l'écran d'accueil, appuyez sur **Finish setup** ou sur **Permissions**.
2. Appuyez sur **Accessibility**. AppLock affiche d'abord une page intitulée **What Accessibility access does**. Lisez-la.
3. Appuyez sur **I understand — open settings**. Si vous n'êtes pas d'accord, appuyez sur **Not now** : rien n'est modifié et aucun réglage ne s'ouvre.
4. Dans l'écran de réglages Android qui s'ouvre, activez le service pour AppLock, puis revenez dans AppLock.
5. Appuyez sur **Display over other apps** et autorisez-le dans l'écran de réglages Android.
6. Appuyez sur toute autre ligne que vous souhaitez autoriser. Une ligne affiche **Granted** lorsque c'est fait.

![La page « What Accessibility access does », affichée avant l'ouverture des réglages Android](shots/05-accessibility-disclosure.png)

**Pourquoi AppLock demande l'accès Accessibility.** AppLock utilise le service d'accessibilité d'Android dans un seul but : repérer quelle appli vient de passer au premier plan, afin d'afficher l'écran de verrouillage sur les applis que vous avez choisi de protéger.

- Ce qu'il fait : il surveille uniquement le nom de l'appli qui vient de s'ouvrir. Quand une appli verrouillée est déverrouillée ou qu'un mauvais code est saisi, le nom de cette appli est enregistré dans le **Security log** sur votre téléphone, pour que vous puissiez le consulter.
- Ce qu'il ne fait jamais : il ne lit jamais le contenu de l'écran, les touches saisies, les mots de passe, les messages ni aucune autre donnée affichée, ni dans AppLock ni dans une autre appli. Rien n'est envoyé hors de votre appareil.
- Vous pouvez le désactiver à tout moment dans les réglages d'Android. AppLock ne peut alors plus afficher l'écran de verrouillage.

**À quoi servent les autres autorisations.**

- **Display over other apps** : permet à l'écran de verrouillage de s'afficher par-dessus une appli verrouillée.
- **Usage access** : aide à vérifier que la protection fonctionne de façon fiable.
- **Notifications** : vous avertit des demandes de déverrouillage et des tentatives d'intrusion.
- **Camera** (facultatif) : photographie la personne qui échoue à déverrouiller.
- **Notification access** : masque le contenu des notifications des applis verrouillées.
- **Ignore battery optimization** : maintient la protection active en arrière-plan.

Chaque autorisation est utilisée uniquement sur votre téléphone.

![Écran des autorisations : chaque autorisation avec sa raison et une mention verte Granted](shots/03-permissions.png)

## Choisir les applis à verrouiller

1. Sur l'écran d'accueil, appuyez sur **Lock apps**.
2. Trouvez l'appli. Saisissez son nom dans **Search apps**, ou passez d'un onglet à l'autre : **User**, **System** et **Recent**. **Recent** affiche d'abord les installations les plus récentes.
3. Activez l'interrupteur à côté de chaque appli à verrouiller.
4. Revenez en arrière. L'écran d'accueil affiche **Protected** et le nombre d'applis verrouillées.

![La liste Lock apps avec un champ de recherche, des onglets et un interrupteur pour chaque appli](shots/06-lock-apps.png)

Pour déverrouiller une appli définitivement, rouvrez **Lock apps** et désactivez son interrupteur.

![Écran d'accueil affichant Protected, 6 apps locked, avec Lock apps, Permissions, Security log, Intruder photos et Settings](shots/01-home.png)

## Ouvrir une appli verrouillée

1. Ouvrez une appli que vous avez verrouillée. L'écran de verrouillage la recouvre aussitôt.
2. Saisissez votre PIN, votre schéma ou votre mot de passe. Si vous avez activé **Unlock with biometrics**, vous pouvez utiliser votre empreinte à la place.
3. Après une saisie erronée, vous pouvez réessayer. Après trop d'erreurs, vous devez attendre un moment.

AppLock est lui-même verrouillé de la même façon, donc personne d'autre ne peut modifier vos réglages.

![Écran de verrouillage avec « Enter your PIN » et le pavé numérique](shots/02-lock-screen.png)

## Modifier le fonctionnement du verrouillage

1. Sur l'écran d'accueil, appuyez sur **Settings**.
2. Sous **Appearance**, choisissez **System**, **Light** ou **Dark**.
3. Sous **Re-lock**, choisissez quand une appli déverrouillée se verrouille de nouveau : **Immediately** dès que vous la quittez, **On screen off** ou **After 5 min**.
4. Sous **Security**, activez **Unlock with biometrics**. Vous confirmez d'abord votre PIN, votre schéma ou votre mot de passe. Il faut pour cela une empreinte ou un visage déjà configuré sur votre téléphone.
5. Sous **Protection**, activez **Scramble the PIN pad** pour mélanger les touches numériques : personne ne pourra deviner votre PIN d'après l'endroit où vous appuyez.
6. Activez **Hide notification content for locked apps** pour garder privés les messages des applis verrouillées. Cela demande **Notification access** dans **Permissions**.
7. Sous **Disguise**, activez **Hide from Recents** pour que AppLock n'apparaisse pas dans la liste des applis récentes.

![Settings : la carte Premium, Appearance, Re-lock et Security](shots/04-settings.png)

## Voir qui a tenté d'entrer

1. Ouvrez **Settings** et activez **Intruder photo after failed attempts**.
2. Ouvrez **Permissions** et autorisez **Camera**.
3. Désormais, après trois saisies erronées d'affilée sur l'écran de verrouillage, la caméra frontale prend une photo.
4. Sur l'écran d'accueil, appuyez sur **Intruder photos** pour voir les photos, chacune avec l'appli qui a été ouverte.
5. Appuyez sur **Security log** pour voir les déverrouillages, les échecs et les modifications de réglages.

![Écran Intruder photos avec des photos prises après des échecs de déverrouillage](shots/07-intruder-photos.png)

## Revenir si vous avez oublié votre PIN

1. Ouvrez AppLock. Sur l'écran de déverrouillage, appuyez sur **Can’t get in?**
2. Saisissez le code de récupération à 8 chiffres que vous avez noté, puis appuyez sur **Continue**.
3. Définissez un nouveau PIN, schéma ou mot de passe. Vous recevez alors un nouveau code de récupération ; l'ancien ne fonctionne plus.

Pour obtenir un nouveau code de récupération alors que vous connaissez encore votre PIN, ouvrez **Settings** et appuyez sur **Replace recovery code**.

## Premium

Premium est un paiement unique, pas un abonnement. Ouvrez **Settings** et appuyez sur **Unlock Premium**. Le verrouillage des applis reste gratuit sans Premium. Premium vous apporte :

- Aucune publicité.
- **Fake crash screen (long-press to unlock)** : une appli verrouillée semble avoir planté au lieu d'afficher l'écran de verrouillage.
- Icônes de camouflage : changez l'icône et le nom de AppLock sur votre écran d'accueil en **Calculator**, **Notes** ou **Weather**. Avec **Calculator**, vous pouvez activer **Open a real calculator instead** et définir un **Secret code** : saisissez le code puis appuyez sur = pour ouvrir AppLock. Votre PIN fonctionne toujours aussi.
- L'historique complet des photos d'intrus. La version gratuite montre les 5 plus récentes.
- **Export backup** : une copie chiffrée de vos réglages et de votre liste d'applis verrouillées, protégée par un mot de passe de votre choix. **Restore backup** est gratuit.

Si vous avez déjà acheté Premium, appuyez sur **Restore purchases** dans **Settings**.

## Questions

**Pourquoi AppLock a-t-il besoin de l'autorisation Accessibility ?**
Uniquement pour repérer quelle appli vient d'être ouverte, afin d'afficher l'écran de verrouillage sur les applis que vous avez verrouillées. Il ne lit jamais ce qui s'affiche à l'écran ni ce que vous saisissez. Voir « Accorder les autorisations » plus haut.

**L'écran d'accueil affiche « Protection off ». Que se passe-t-il ?**
Soit **Accessibility**, soit **Display over other apps** n'est pas autorisé, soit aucune appli n'est encore verrouillée. Appuyez sur **Finish setup** pour ouvrir la liste des autorisations, puis vérifiez **Lock apps**.

**Puis-je cacher complètement AppLock ?**
Non. Android garde toujours une icône pour une appli installée. Avec Premium, vous pouvez remplacer l'icône et le nom par un camouflage.

**J'ai oublié mon PIN et perdu le code de récupération. Pouvez-vous le réinitialiser ?**
Non. AppLock fonctionne hors ligne et sans compte, il n'existe donc pas de réinitialisation par e-mail. Le code de récupération est le seul moyen de revenir. Conservez-le en lieu sûr.

**Une sauvegarde contient-elle mon PIN ou les photos d'intrus ?**
Non. Après la restauration d'une sauvegarde, l'appli vous demande d'abord de définir un nouveau PIN, schéma ou mot de passe.

## Confidentialité

Votre PIN, vos applis verrouillées, le journal de sécurité et les photos d'intrus restent sur votre appareil et ne sont jamais envoyés. La version gratuite affiche des publicités de Google AdMob. Lisez la [politique de confidentialité](https://varian1.github.io/privacy.html) complète.
