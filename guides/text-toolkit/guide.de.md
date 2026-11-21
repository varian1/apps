---
title: Wortzähler: Text Toolkit
name: Text Toolkit
tagline: Wörter zählen, Text umwandeln, bereinigen, sortieren und vergleichen – offline.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## Was die App kann

Text Toolkit ist ein einziger Bildschirm mit neun Text-Tools. Tippe oder füge oben im Feld einen Text ein, wähle ein Tool und kopiere oder teile das Ergebnis. Die App zählt Wörter, ändert die Groß- und Kleinschreibung, räumt Leerzeichen auf, sortiert Zeilen, sucht und ersetzt, kehrt Text um, kodiert, formatiert JSON und vergleicht zwei Texte.

- Jedes Tool läuft auf deinem Gerät und funktioniert ohne Internet.
- Kein Konto nötig. Dein Text wird nie hochgeladen, und die App nutzt weder Kamera, Fotos, Kontakte noch Standort.
- Dein Text wird nicht gespeichert. Er ist weg, sobald du die App schließt.
- Kostenlos. Unten auf dem Bildschirm kann ein Werbebanner erscheinen.

## Erste Schritte

1. Öffne Text Toolkit. Im Feld **YOUR TEXT** steht ein kurzer Beispieltext, mit dem du jedes Tool ausprobieren kannst.
2. Tippe auf **Clear** und gib deinen eigenen Text ein. Oder tippe auf **Paste**, um den Text durch das zu ersetzen, was du in einer anderen App kopiert hast. **Sample** bringt den Beispieltext zurück.
3. Wähle in der Reihe unter dem Feld ein Tool: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format** oder **Diff**. Wische seitlich über die Reihe, um alle zu sehen.

![Hauptbildschirm: das Feld YOUR TEXT mit Paste, Sample und Clear, die Reihe der Tools und die Zahlen von Counter](shots/01-home.png)

Die App verwendet die Sprache deines Handys. Sie gibt es in 11 Sprachen: Englisch, Spanisch, Portugiesisch, Deutsch, Französisch, Hindi, Indonesisch, Arabisch, Italienisch, Russisch und Türkisch.

## Wörter und Zeichen zählen

1. Tippe auf **Counter**.
2. Lies die Zahlen ab: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines** und **Reading time**.
3. Unter **TOP WORDS** siehst du die Wörter, die du am häufigsten benutzt hast, bis zu acht, jeweils mit ihrer Anzahl.

Die Zahlen ändern sich, während du tippst. Die Lesezeit basiert auf 200 Wörtern pro Minute.

## Groß- und Kleinschreibung ändern

1. Tippe auf **Case**.
2. Scrolle durch die Karten. Jede zeigt deinen Text in einem anderen Stil: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE** und **URL slug**.
3. Tippe bei der gewünschten Karte auf **Copy**.

![Case-Tool: Karten für UPPERCASE, lowercase und Title Case, jeweils mit Use input, Share und Copy](shots/02-case.png)

## Text bereinigen

1. Tippe auf **Clean**.
2. Tippe auf eine Aktion:
   - **Clean all**: entfernt Tabs, doppelte Leerzeichen, Leerzeichen am Zeilenende, leere Zeilen und doppelte Zeilen in einem Schritt.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates** oder **Remove tabs**: erledigt nur diese eine Sache.
   - Die Aktion für Zeilenumbrüche: entfernt die Zeilenumbrüche aus deinem Text.
3. Das Ergebnis siehst du unter **CLEANED RESULT**. Dein eigener Text im Feld bleibt unverändert.

![Clean-Tool: die Buttons zum Bereinigen und die Karte CLEANED RESULT](shots/03-clean.png)

## Sortieren oder umkehren

1. Tippe auf **Lines**, um ganze Zeilen zu bearbeiten: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates** oder **Reverse characters**. Beim Sortieren werden Großbuchstaben und Leerzeichen am Zeilenanfang ignoriert.
2. Tippe auf **Reverse**, um Text umzudrehen: **Entire text**, **Each word**, **Word order**, **Line order** oder **Characters per line**.
3. Das Ergebnis erscheint in der Karte unter den Buttons.

## Suchen und ersetzen

1. Tippe auf **Replace**.
2. Gib den gesuchten Text bei **Find** ein und den neuen Text bei **Replace with**.
3. Tippe auf die Optionen, um sie ein- oder auszuschalten: **Replace all** (aus: nur der erste Treffer wird geändert), **Case sensitive** und **Whole word**.
4. Prüfe die Anzahl der Ersetzungen und die **REPLACEMENT PREVIEW**. Beide aktualisieren sich, während du tippst.

![Replace-Tool: die Felder Find und Replace with, die drei Optionen, die Anzahl der Ersetzungen und die Vorschau](shots/04-replace.png)

Die Suche sucht genau das, was du eingibst. Muster oder Platzhalter werden nicht unterstützt.

## Kodieren, dekodieren und formatieren

1. Tippe auf **Encode**, wähle **URL**, **Base64** oder **HTML Entities** und tippe dann auf **Encode** oder **Decode**.
2. Tippe auf **Format** und wähle **Format JSON**, um JSON mit zwei Leerzeichen einzurücken, **Minify JSON**, um es in eine Zeile zu setzen, oder **Strip Markdown**, um Markdown in einfachen Text umzuwandeln.
3. Wenn das JSON einen Fehler enthält, beginnt oben auf dem Bildschirm eine Zeile mit "Invalid JSON" und nennt das Problem.

## Zwei Texte vergleichen

1. Füge die erste Version in **YOUR TEXT** ein und tippe auf **Diff**.
2. Tippe oder füge die zweite Version in **COMPARE WITH** ein.
3. Lies **DIFF COMPARISON**. Zeilen, die nur in der zweiten Version stehen, sind grün und mit einem **+** markiert. Zeilen, die nur in der ersten Version stehen, sind rot und mit einem **-** markiert. Gleiche Zeilen haben keine Markierung.
4. Tippe auf **Copy Diff**, um den Vergleich mit seinen Zeichen + und - zu kopieren.

![Diff-Tool: das Feld COMPARE WITH und die Karte DIFF COMPARISON mit einer grünen hinzugefügten und einer roten entfernten Zeile](shots/05-diff.png)

## Kopieren, teilen oder weiterarbeiten

1. Tippe bei einer Ergebniskarte auf **Copy**, um das Ergebnis in die Zwischenablage zu legen.
2. Tippe auf **Share**, um es an eine andere App zu senden.
3. Tippe auf **Use input**, um das Ergebnis nach **YOUR TEXT** zu übernehmen. So kannst du gleich ein weiteres Tool darauf anwenden.

## Premium

Alle Tools sind kostenlos. Ein optionaler Einmalkauf entfernt die Werbung. Du zahlst nur einmal; es ist kein Abo.

## Fragen

**Funktioniert die App offline?**
Ja. Alle neun Tools laufen auf deinem Handy. Nur die Werbung und der Kauf zum Entfernen der Werbung brauchen eine Internetverbindung.

**Wird mein Text gespeichert?**
Nein. Die App behält deinen Text nur, solange sie geöffnet ist. Kopiere oder teile ein Ergebnis, das du behalten möchtest.

**Warum ist das Ergebnis leer, nachdem ich das Tool gewechselt habe?**
Clean, Lines, Reverse, Encode und Format teilen sich eine Ergebniskarte, die beim Wechsel des Tools geleert wird. Tippe die Aktion noch einmal an. Mach das auch, nachdem du deinen Text bearbeitet hast. Counter, Case, Replace und Diff aktualisieren sich von selbst.

**Unterstützt die App den Dunkelmodus?**
Ja. Die App verwendet das helle oder dunkle Design, das auf deinem Handy eingestellt ist.

**Wo finde ich die Lizenzen?**
Scrolle ganz nach unten und tippe auf **Open-source licenses**. Daneben steht **Privacy policy**.

## Datenschutz

Dein Text wird auf deinem Handy verarbeitet und nie hochgeladen oder gespeichert. Die App kann Werbung von Google AdMob anzeigen. Wo das Gesetz es verlangt, wirst du vorher nach deiner Auswahl gefragt und kannst sie auf dem Hauptbildschirm mit **Ad privacy choices** ändern. Lies die vollständige [Datenschutzerklärung](https://varian1.github.io/text-toolkit/privacy.html).
