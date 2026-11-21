---
title: Compteur de mots Text Toolkit
name: Text Toolkit
tagline: Comptez les mots, changez la casse, triez et comparez vos textes hors ligne.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## Ce que fait l'appli

Text Toolkit tient en un seul écran avec neuf outils pour le texte. Saisissez ou collez votre texte dans la zone du haut, choisissez un outil, puis copiez ou partagez le résultat. L'appli compte les mots, change la casse, nettoie les espaces, trie les lignes, cherche et remplace, inverse, encode, met en forme le JSON et compare deux textes.

- Chaque outil fonctionne sur votre appareil, sans connexion internet.
- Aucun compte. Votre texte n'est jamais envoyé, et l'appli n'utilise ni votre appareil photo, ni vos photos, ni vos contacts, ni votre position.
- Votre texte n'est pas enregistré. Il disparaît quand vous fermez l'appli.
- Gratuite. Une bannière publicitaire peut s'afficher en bas de l'écran.

## Pour commencer

1. Ouvrez Text Toolkit. La zone **YOUR TEXT** contient un court exemple pour essayer chaque outil.
2. Appuyez sur **Clear** et saisissez votre propre texte, ou appuyez sur **Paste** pour remplacer le texte par ce que vous avez copié dans une autre appli. **Sample** remet le texte d'exemple.
3. Choisissez un outil dans la rangée sous la zone : **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format** ou **Diff**. Faites glisser la rangée sur le côté pour les voir tous.

![Écran principal : la zone YOUR TEXT avec Paste, Sample et Clear, la rangée d'outils et les chiffres de Counter](shots/01-home.png)

L'appli utilise la langue de votre téléphone. Elle est disponible en 11 langues : anglais, espagnol, portugais, allemand, français, hindi, indonésien, arabe, italien, russe et turc.

## Compter les mots et les caractères

1. Appuyez sur **Counter**.
2. Lisez les chiffres : **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines** et **Reading time**.
3. Regardez **TOP WORDS** en dessous pour voir les mots que vous avez le plus utilisés, jusqu'à huit, chacun avec son nombre d'occurrences.

Les chiffres changent pendant que vous saisissez. Le temps de lecture est calculé sur la base de 200 mots par minute.

## Changer la casse

1. Appuyez sur **Case**.
2. Faites défiler les cartes. Chacune montre votre texte dans un autre style : **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE** et **URL slug**.
3. Appuyez sur **Copy** sur la carte de votre choix.

![Outil Case : cartes UPPERCASE, lowercase et Title Case, chacune avec Use input, Share et Copy](shots/02-case.png)

## Nettoyer un texte

1. Appuyez sur **Clean**.
2. Appuyez sur une action :
   - **Clean all** : supprime d'un coup les tabulations, les espaces en double, les espaces en fin de ligne, les lignes vides et les lignes répétées.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates** ou **Remove tabs** : ne fait que cette action.
   - L'action sur les retours à la ligne : supprime les retours à la ligne de votre texte.
3. Lisez le résultat sous **CLEANED RESULT**. Votre texte dans la zone reste tel quel.

![Outil Clean : les boutons de nettoyage et la carte CLEANED RESULT](shots/03-clean.png)

## Trier ou inverser

1. Appuyez sur **Lines** pour travailler sur des lignes entières : **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates** ou **Reverse characters**. Le tri ignore les majuscules et les espaces en début de ligne.
2. Appuyez sur **Reverse** pour retourner le texte : **Entire text**, **Each word**, **Word order**, **Line order** ou **Characters per line**.
3. Le résultat s'affiche dans la carte sous les boutons.

## Chercher et remplacer

1. Appuyez sur **Replace**.
2. Saisissez le texte à chercher dans **Find** et le nouveau texte dans **Replace with**.
3. Appuyez sur les options pour les activer ou les désactiver : **Replace all** (désactivée, seule la première occurrence change), **Case sensitive** et **Whole word**.
4. Vérifiez le nombre de remplacements et le **REPLACEMENT PREVIEW**. Les deux se mettent à jour pendant que vous saisissez.

![Outil Replace : les champs Find et Replace with, les trois boutons d'option, le nombre de remplacements et l'aperçu](shots/04-replace.png)

La recherche porte exactement sur ce que vous saisissez. Elle n'utilise ni motifs ni jokers.

## Encoder, décoder et mettre en forme

1. Appuyez sur **Encode**, choisissez **URL**, **Base64** ou **HTML Entities**, puis appuyez sur **Encode** ou **Decode**.
2. Appuyez sur **Format** et choisissez **Format JSON** pour indenter le JSON avec deux espaces, **Minify JSON** pour le mettre sur une seule ligne, ou **Strip Markdown** pour transformer du Markdown en texte brut.
3. Si le JSON contient une erreur, une ligne en haut de l'écran commence par "Invalid JSON" et indique ce qui ne va pas.

## Comparer deux textes

1. Mettez la première version dans **YOUR TEXT** et appuyez sur **Diff**.
2. Saisissez ou collez la seconde version dans **COMPARE WITH**.
3. Lisez **DIFF COMPARISON**. Les lignes présentes seulement dans la seconde version sont en vert avec un **+**. Les lignes présentes seulement dans la première version sont en rouge avec un **-**. Les lignes identiques n'ont aucun signe.
4. Appuyez sur **Copy Diff** pour copier la comparaison avec ses signes + et -.

![Outil Diff : la zone COMPARE WITH et la carte DIFF COMPARISON avec une ligne ajoutée en vert et une ligne supprimée en rouge](shots/05-diff.png)

## Copier, partager ou continuer

1. Appuyez sur **Copy** sur une carte de résultat pour la placer dans le presse-papiers.
2. Appuyez sur **Share** pour l'envoyer à une autre appli.
3. Appuyez sur **Use input** pour déplacer le résultat dans **YOUR TEXT**, afin de lui appliquer un autre outil.

## Premium

Tous les outils sont gratuits. Un achat unique facultatif supprime les publicités. Vous payez une seule fois ; ce n'est pas un abonnement.

## Questions

**L'appli fonctionne-t-elle hors ligne ?**
Oui. Les neuf outils fonctionnent sur votre téléphone. Seules les publicités et l'achat pour les supprimer utilisent une connexion réseau.

**Mon texte est-il enregistré ?**
Non. L'appli ne garde votre texte que tant qu'elle est ouverte. Copiez ou partagez un résultat que vous voulez conserver.

**Pourquoi le résultat est-il vide après un changement d'outil ?**
Clean, Lines, Reverse, Encode et Format partagent une même carte de résultat, qui est vidée quand vous changez d'outil. Appuyez de nouveau sur l'action. Faites de même après avoir modifié votre texte. Counter, Case, Replace et Diff se mettent à jour tout seuls.

**L'appli suit-elle le mode sombre ?**
Oui. L'appli utilise le thème clair ou sombre réglé sur votre téléphone.

**Où trouver les licences ?**
Faites défiler jusqu'en bas et appuyez sur **Open-source licenses**. **Privacy policy** se trouve à côté.

## Confidentialité

Votre texte est traité sur votre téléphone et n'est jamais envoyé ni enregistré. L'appli peut afficher des publicités de Google AdMob ; lorsque la loi l'exige, on vous demande d'abord votre choix, que vous pouvez modifier avec **Ad privacy choices** sur l'écran principal. Lisez la [politique de confidentialité](https://varian1.github.io/text-toolkit/privacy.html) complète.
