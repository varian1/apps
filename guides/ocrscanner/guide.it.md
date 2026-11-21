---
title: Scanner OCR: Foto in Testo PDF
name: OCRScanner
tagline: Da carta a testo modificabile sul telefono. Cerca, copia e condividi in PDF.
project: OCRScanner
package: io.github.varian1.ocrscanner
version: 1.2.0
updated: 2026-11-21
privacy: https://varian1.github.io/ocrscanner/privacy.html
---

## Cosa fa

OCRScanner fotografa una pagina di carta, la raddrizza e legge il testo direttamente sul telefono. Puoi modificare e copiare il testo, cercare in tutte le scansioni che hai fatto e condividere una scansione come PDF ricercabile, file di testo o immagine.

- Il riconoscimento del testo avviene sul dispositivo e funziona senza internet.
- Nessun account. Le scansioni restano sul telefono e non vengono mai caricate online.
- Importa un PDF, oppure condividi immagini da altre app su Android.
- Gratis con pubblicità. Un acquisto Premium una tantum toglie gli annunci e aggiunge altre lingue.

## Per iniziare

1. Apri OCRScanner. La prima volta l'elenco **Scans** è vuoto.
2. Tocca **Scan** per usare la fotocamera, oppure **Import** per scegliere foto che hai già.
3. Consenti l'uso della fotocamera quando Android lo chiede. Per importare non serve l'accesso a tutta la libreria foto.

![L'elenco Scans con i pulsanti Scan e Import](shots/01-home.png)

## Scansionare una pagina

1. Tocca **Scan** e inquadra la pagina. Tocca il pulsante di scatto per fare la foto.
2. In **Review** i bordi della pagina vengono trovati in automatico. Trascina un angolo blu se un bordo non è giusto, oppure tocca **Full page** per tenere tutta la foto.
3. Scegli un filtro per pulire la pagina: **Original**, **Magic**, **Gray** o **B&W**.
4. Tocca **Rotate 90°** se la pagina è di lato, oppure **Retake** per fotografarla di nuovo.
5. Tocca **Recognize text**.

![Schermata Review con gli angoli della pagina, i filtri e il pulsante Recognize text](shots/02-review.png)

Per scansionare più pagine in un solo documento, apri la scansione più tardi, tocca **⋯** e scegli **Add pages**.

## Importare un PDF

OCRScanner legge fino a 20 pagine di un PDF, oppure 50 con Premium. Ogni pagina viene letta come immagine, quindi il testo già presente nel PDF non viene usato.

1. Scegli un PDF nel selettore file del telefono. Non serve alcun permesso di archiviazione.
2. In **Review** controlla le pagine. Se il PDF supera il limite, Review ti dice quante pagine sono rimaste fuori.
3. Tocca **Recognize text**.

## Condividere immagini da altre app

Funziona su Android.

1. Nella galleria o in un'altra app, seleziona fino a 20 immagini e tocca condividi.
2. Scegli OCRScanner.
3. Sblocca l'app se **App lock** è attivo. Le immagini si aprono in **Review** come nuova scansione.

Se hai pagine aperte non salvate, l'app ti chiede conferma prima di sostituirle.

## Leggere, modificare e copiare il testo

1. Dopo il riconoscimento, **Result** mostra la pagina in alto e il suo testo sotto.
2. Tocca una riga di testo per vedere dove si trova sulla pagina. Tocca una parola sulla pagina per passare alla sua riga.
3. Le righe di cui l'app non è sicura sono evidenziate, così sai cosa controllare.
4. Tocca **Edit** per correggere il testo, **Copy** per copiarlo o **Share** per inviarlo.
5. Tocca **Save** per conservare la scansione nell'elenco.

![Schermata Result: la pagina sopra, il testo riconosciuto sotto, con Edit, Copy, Share e Save](shots/03-result.png)

## Trovare una scansione dal testo

1. In **Scans**, tocca **Search text in your scans**.
2. Scrivi una parola. Vengono elencate tutte le scansioni che la contengono, con la corrispondenza in grassetto.
3. Tocca un risultato per aprire la scansione proprio a quel punto.

![Cercando la parola "lighting" si trova la scansione che la contiene](shots/04-search.png)

Per vedere solo le scansioni con un certo tag, tocca quel tag sotto il campo di ricerca. La ricerca cerca poi solo in quelle scansioni. Tocca di nuovo il tag per vederle tutte.

## Condividere o esportare

1. Apri una scansione e tocca il pulsante di condivisione.
2. Scegli un formato:
   - **PDF**: le immagini delle pagine con il testo ricercabile sotto.
   - **Text file**: testo semplice (.txt).
   - **Page image**: salva nella galleria o invia.
3. Scegli l'app a cui inviarlo.

![Pannello di condivisione o esportazione con PDF, Text file e Page image](shots/05-share.png)

## Rinominare, aggiungere tag ed eliminare

1. Apri una scansione e tocca **⋯**.
2. Scegli **Rename** per cambiare il titolo, oppure **Edit tags** per aggiungere tag separati da virgole.
3. Scegli **Recognize text again** per rileggere le pagine in un'altra lingua del testo. Il testo che hai modificato viene sostituito.
4. Scegli **Delete scan** per rimuoverla dal telefono.

## Salvare e ripristinare le scansioni

1. In **Scans**, tocca l'icona delle impostazioni in alto a destra.
2. In **Storage**, tocca **Back up scans**. Tutte le scansioni vengono riunite in un solo file.
3. Scegli dove salvare o inviare il file. Il file non è cifrato, quindi conservalo in un posto sicuro.
4. Su un telefono nuovo, tocca **Restore from backup** e scegli il file. L'app chiede conferma prima di sostituire tutte le scansioni del telefono con quelle del backup.

## Bloccare l'app e cambiare le impostazioni

1. In **Scans**, tocca l'icona delle impostazioni in alto a destra.
2. Attiva **App lock** per richiedere impronta, volto o blocco schermo prima di aprire le scansioni.
3. In **Text language (OCR)**, scegli la scrittura dei tuoi documenti. **Latin** comprende inglese, spagnolo, francese, tedesco, indonesiano e altre lingue. L'app propone quella usata dalla lingua del telefono.
4. Tocca **App language** per usare l'app in una lingua diversa da quella del telefono.
5. Scegli **Image quality** (Balanced o Full) e il **Theme** (System, Light o Dark).

![Impostazioni: Premium, App lock, Text language (OCR) e Image quality](shots/06-settings.png)

## Premium

Premium è un pagamento unico, non un abbonamento. Apri **Settings** e tocca **See Premium**. Ti offre:

- Nessuna pubblicità.
- Testo cinese, giapponese e coreano, più hindi e altri testi devanagari su Android.
- Unione di più scansioni in un solo PDF o file di testo.
- Importazione di PDF più lunghi: fino a 50 pagine invece di 20.

Se hai già acquistato Premium, tocca **Restore purchase** nella schermata Premium.

## Domande

**Funziona offline?**
Sì. Scansione, riconoscimento del testo, ricerca ed esportazione avvengono tutti sul telefono.

**Dove vengono conservate le scansioni?**
Solo sul tuo dispositivo. Se disinstalli l'app, le scansioni vengono eliminate con lei, quindi prima tocca **Back up scans** in Settings per conservarle.

**Il testo contiene errori. Cosa posso fare?**
Rifai la foto con buona luce e la pagina ben piana, prova il filtro **Magic** o **B&W** e controlla che **Text language (OCR)** corrisponda al documento. Puoi anche correggere singole parole con **Edit**.

**Legge la scrittura a mano?**
È pensata per il testo stampato. La scrittura a mano spesso viene letta in modo errato.

## Privacy

I tuoi documenti non vengono mai caricati online. La versione gratuita mostra annunci di Google AdMob. Leggi l'[informativa sulla privacy](https://varian1.github.io/ocrscanner/privacy.html) completa.
