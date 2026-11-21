---
title: Scanner OCR : image en texte
name: OCRScanner
tagline: Numérisez des documents en texte modifiable, sur l'appareil. Recherche et PDF.
project: OCRScanner
package: io.github.varian1.ocrscanner
version: 1.2.0
updated: 2026-11-21
privacy: https://varian1.github.io/ocrscanner/privacy.html
---

## Ce que fait l'appli

OCRScanner photographie une page papier, la redresse et lit son texte directement sur votre téléphone. Vous pouvez modifier et copier le texte, chercher dans tous vos scans, et partager un scan en PDF avec texte recherchable, en fichier texte ou en image.

- La reconnaissance du texte se fait sur votre appareil et fonctionne sans internet.
- Aucun compte. Vos scans restent sur votre téléphone et ne sont jamais envoyés en ligne.
- Importez un PDF, ou partagez des images depuis d'autres applis sur Android.
- Gratuit avec publicités. Un achat unique Premium supprime les publicités et ajoute des langues.

## Premiers pas

1. Ouvrez OCRScanner. La liste **Scans** est vide au premier lancement.
2. Touchez **Scan** pour utiliser l'appareil photo, ou **Import** pour choisir des photos que vous avez déjà.
3. Autorisez l'appareil photo quand Android vous le demande. L'import n'a pas besoin d'accéder à toute votre photothèque.

![La liste Scans avec les boutons Scan et Import](shots/01-home.png)

## Scanner une page

1. Touchez **Scan** et dirigez l'appareil photo vers la page. Touchez le bouton de prise de vue pour prendre la photo.
2. Sur **Review**, les bords de la page sont détectés pour vous. Faites glisser un coin bleu si un bord est mal placé, ou touchez **Full page** pour garder toute la photo.
3. Choisissez un filtre pour nettoyer la page : **Original**, **Magic**, **Gray** ou **B&W**.
4. Touchez **Rotate 90°** si la page est de côté, ou **Retake** pour la photographier à nouveau.
5. Touchez **Recognize text**.

![L'écran Review avec les coins de la page, les filtres et le bouton Recognize text](shots/02-review.png)

Pour scanner plusieurs pages dans un seul document, ouvrez le scan plus tard, touchez **⋯** et choisissez **Add pages**.

## Importer un PDF

OCRScanner lit jusqu'à 20 pages d'un même PDF, ou 50 avec Premium. Chaque page est lue comme une image : le texte déjà présent dans le PDF n'est donc pas utilisé.

1. Choisissez un PDF dans le sélecteur de fichiers de votre téléphone. Aucune autorisation de stockage n'est nécessaire.
2. Sur **Review**, vérifiez les pages. Si le PDF dépasse la limite, Review vous indique combien de pages ont été écartées.
3. Touchez **Recognize text**.

## Partager des images depuis d'autres applis

Cette fonction est disponible sur Android.

1. Dans votre galerie ou une autre appli, sélectionnez jusqu'à 20 images et touchez partager.
2. Choisissez OCRScanner.
3. Déverrouillez l'appli si **App lock** est activé. Les images s'ouvrent sur **Review** comme un nouveau scan.

Si des pages non enregistrées sont ouvertes, l'appli vous demande confirmation avant de les remplacer.

## Lire, modifier et copier le texte

1. Après la reconnaissance, **Result** affiche la page en haut et son texte en dessous.
2. Touchez une ligne de texte pour voir où elle se trouve sur la page. Touchez un mot sur la page pour aller à sa ligne.
3. Les lignes dont l'appli n'est pas sûre sont surlignées, pour que vous sachiez quoi vérifier.
4. Touchez **Edit** pour corriger le texte, **Copy** pour le copier, ou **Share** pour l'envoyer.
5. Touchez **Save** pour garder le scan dans votre liste.

![L'écran Result : la page en haut, le texte reconnu en dessous, avec Edit, Copy, Share et Save](shots/03-result.png)

## Retrouver un scan grâce à son texte

1. Sur **Scans**, touchez **Search text in your scans**.
2. Tapez un mot. Tous les scans qui le contiennent s'affichent, avec le mot trouvé en gras.
3. Touchez un résultat pour ouvrir le scan à cet endroit.

![La recherche du mot « lighting » trouve le scan qui le contient](shots/04-search.png)

Pour ne voir que les scans portant une étiquette, touchez cette étiquette sous le champ de recherche. La recherche se fait alors uniquement dans ces scans. Touchez à nouveau l'étiquette pour revoir tous les scans.

## Partager ou exporter

1. Ouvrez un scan et touchez le bouton de partage.
2. Choisissez un format :
   - **PDF** : les images des pages avec le texte recherchable derrière.
   - **Text file** : texte brut (.txt).
   - **Page image** : à enregistrer dans vos photos ou à envoyer.
3. Choisissez l'appli à laquelle l'envoyer.

![La feuille de partage ou d'export avec PDF, Text file et Page image](shots/05-share.png)

## Renommer, étiqueter et supprimer

1. Ouvrez un scan et touchez **⋯**.
2. Choisissez **Rename** pour changer le titre, ou **Edit tags** pour ajouter des étiquettes séparées par des virgules.
3. Choisissez **Recognize text again** pour relire les pages dans une autre langue de texte. Le texte que vous aviez modifié est remplacé.
4. Choisissez **Delete scan** pour le supprimer de votre téléphone.

## Sauvegarder et restaurer vos scans

1. Sur **Scans**, touchez l'icône des réglages en haut à droite.
2. Sous **Storage**, touchez **Back up scans**. Tous vos scans sont regroupés dans un seul fichier.
3. Choisissez où enregistrer ou envoyer le fichier. Il n'est pas chiffré : gardez-le dans un endroit sûr.
4. Sur un nouveau téléphone, touchez **Restore from backup** et choisissez le fichier. L'appli demande confirmation avant de remplacer tous les scans du téléphone par ceux de la sauvegarde.

## Verrouiller l'appli et modifier les réglages

1. Sur **Scans**, touchez l'icône des réglages en haut à droite.
2. Activez **App lock** pour exiger votre empreinte, votre visage ou le verrouillage de l'écran avant d'ouvrir vos scans.
3. Sous **Text language (OCR)**, choisissez l'écriture de vos documents. **Latin** couvre l'anglais, l'espagnol, le français, l'allemand, l'indonésien et d'autres. L'appli propose celle qui correspond à la langue de votre téléphone.
4. Touchez **App language** pour utiliser l'appli dans une autre langue que celle de votre téléphone.
5. Choisissez **Image quality** (Balanced ou Full) et le **Theme** (System, Light ou Dark).

![Les réglages : Premium, App lock, Text language (OCR) et Image quality](shots/06-settings.png)

## Premium

Premium est un paiement unique, pas un abonnement. Ouvrez **Settings** et touchez **See Premium**. Il vous apporte :

- Aucune publicité.
- Le texte chinois, japonais et coréen, ainsi que l'hindi et d'autres textes en devanagari sur Android.
- La fusion de plusieurs scans en un seul PDF ou fichier texte.
- L'import de PDF plus longs : jusqu'à 50 pages au lieu de 20.

Si vous avez déjà acheté Premium, touchez **Restore purchase** sur l'écran Premium.

## Questions

**Est-ce que ça marche hors ligne ?**
Oui. La numérisation, la reconnaissance du texte, la recherche et l'export se font tous sur votre téléphone.

**Où sont conservés mes scans ?**
Uniquement sur votre appareil. Si vous désinstallez l'appli, les scans sont supprimés avec elle : touchez d'abord **Back up scans** dans Settings pour les conserver.

**Le texte contient des erreurs. Que faire ?**
Reprenez la photo avec une bonne lumière et la page bien à plat, essayez le filtre **Magic** ou **B&W**, et vérifiez que **Text language (OCR)** correspond au document. Vous pouvez aussi corriger des mots isolés avec **Edit**.

**Peut-elle lire l'écriture manuscrite ?**
Elle est conçue pour le texte imprimé. L'écriture manuscrite est souvent mal lue.

## Confidentialité

Vos documents ne sont jamais envoyés en ligne. La version gratuite affiche des publicités de Google AdMob. Lisez la [politique de confidentialité](https://varian1.github.io/ocrscanner/privacy.html) complète.
