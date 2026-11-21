---
title: OCR Scanner: Larawan sa Text PDF
name: OCRScanner
tagline: I-scan ang dokumento at gawing text na puwedeng i-edit. Hanapin, kopyahin, i-share bilang PDF.
project: OCRScanner
package: io.github.varian1.ocrscanner
version: 1.2.0
updated: 2026-11-21
privacy: https://varian1.github.io/ocrscanner/privacy.html
---

## Ano ang ginagawa nito

Kinukunan ng OCRScanner ng litrato ang pahina ng papel, itinutuwid ito, at binabasa ang text sa mismong telepono mo. Puwede mong i-edit at kopyahin ang text, hanapin ang anumang na-scan mo na, at i-share ang scan bilang PDF na may hanapin na text, text file, o larawan.

- Sa device mismo gumagana ang pagkilala ng text, kaya hindi kailangan ng internet.
- Walang account. Nasa telepono mo lang ang mga scan mo at hindi ina-upload kahit saan.
- Mag-import ng PDF, o mag-share ng mga larawan mula sa ibang app sa Android.
- Libre na may mga ad. Ang minsanang pagbili ng Premium ay nag-aalis ng ad at nagdaragdag ng mas maraming wika.

## Simulan

1. Buksan ang OCRScanner. Walang laman ang listahan ng **Scans** sa unang pagbukas.
2. I-tap ang **Scan** para gamitin ang camera, o ang **Import** para pumili ng mga litratong mayroon ka na.
3. Payagan ang camera kapag nagtanong ang Android. Hindi kailangan ng Import ng access sa buong photo library mo.

![Ang listahan ng Scans na may mga button na Scan at Import](shots/01-home.png)

## Mag-scan ng pahina

1. I-tap ang **Scan** at itutok ang camera sa pahina. I-tap ang shutter button para kumuha ng litrato.
2. Sa **Review**, awtomatikong hahanapin ang mga gilid ng pahina. I-drag ang asul na sulok kung mali ang isang gilid, o i-tap ang **Full page** para panatilihin ang buong litrato.
3. Pumili ng filter para luminis ang pahina: **Original**, **Magic**, **Gray** o **B&W**.
4. I-tap ang **Rotate 90°** kung nakatagilid ang pahina, o ang **Retake** para kunan ito ulit.
5. I-tap ang **Recognize text**.

![Ang Review screen na may mga sulok ng pahina, mga filter at ang button na Recognize text](shots/02-review.png)

Para mag-scan ng ilang pahina sa iisang dokumento, buksan ang scan mamaya, i-tap ang **⋯** at piliin ang **Add pages**.

## Mag-import ng PDF

Nababasa ng OCRScanner ang hanggang 20 pahina ng isang PDF, o 50 kung may Premium. Bawat pahina ay binabasa bilang larawan, kaya hindi ginagamit ang text na nasa loob na ng PDF.

1. Pumili ng isang PDF sa file picker ng telepono mo. Hindi kailangan ng pahintulot sa storage.
2. Sa **Review**, tingnan ang mga pahina. Kung mas mahaba ang PDF kaysa sa limitasyon, sasabihin ng Review kung ilang pahina ang naiwan.
3. I-tap ang **Recognize text**.

## Mag-share ng mga larawan mula sa ibang app

Gumagana ito sa Android.

1. Sa gallery mo o sa ibang app, pumili ng hanggang 20 larawan at i-tap ang share.
2. Piliin ang OCRScanner.
3. I-unlock ang app kung naka-on ang **App lock**. Magbubukas ang mga larawan sa **Review** bilang bagong scan.

Kung may mga hindi pa nase-save na pahina na nakabukas, magtatanong muna ang app bago ito palitan.

## Basahin, i-edit at kopyahin ang text

1. Pagkatapos ng pagkilala, ipinapakita ng **Result** ang pahina sa itaas at ang text nito sa ibaba.
2. I-tap ang isang linya ng text para makita kung nasaan ito sa pahina. I-tap ang isang salita sa pahina para tumalon sa linya nito.
3. Naka-highlight ang mga linyang hindi sigurado ang app, para alam mo kung ano ang dapat suriin.
4. I-tap ang **Edit** para itama ang text, **Copy** para kopyahin ito, o **Share** para ipadala ito.
5. I-tap ang **Save** para itago ang scan sa listahan mo.

![Ang Result screen: ang pahina sa itaas, ang nakilalang text sa ibaba, na may Edit, Copy, Share at Save](shots/03-result.png)

## Hanapin ang scan gamit ang text nito

1. Sa **Scans**, i-tap ang **Search text in your scans**.
2. Mag-type ng salita. Ililista ang bawat scan na may ganoong salita, at naka-bold ang tugma.
3. I-tap ang isang resulta para buksan ang scan sa tugmang iyon.

![Ang paghahanap sa salitang "lighting" ay nakakahanap ng scan na may ganoong salita](shots/04-search.png)

Para makita lang ang mga scan na may isang tag, i-tap ang tag na iyon sa ilalim ng search field. Sa mga scan na iyon na lang maghahanap ang search. I-tap muli ang tag para makita ang lahat ng scan.

## I-share o i-export

1. Magbukas ng scan at i-tap ang share button.
2. Pumili ng format:
   - **PDF**: ang mga larawan ng pahina na may hanapin na text sa likod.
   - **Text file**: payak na text (.txt).
   - **Page image**: i-save sa Photos o ipadala.
3. Piliin ang app na pagpapadalhan.

![Ang share o export sheet na may PDF, Text file at Page image](shots/05-share.png)

## Palitan ang pangalan, lagyan ng tag at burahin

1. Magbukas ng scan at i-tap ang **⋯**.
2. Piliin ang **Rename** para palitan ang pamagat, o ang **Edit tags** para magdagdag ng mga tag na pinaghihiwalay ng kuwit.
3. Piliin ang **Recognize text again** para basahin muli ang mga pahina sa ibang wika ng text. Mapapalitan ang anumang text na na-edit mo.
4. Piliin ang **Delete scan** para alisin ito sa telepono mo.

## I-back up at ibalik ang mga scan

1. Sa **Scans**, i-tap ang settings icon sa kanang itaas.
2. Sa ilalim ng **Storage**, i-tap ang **Back up scans**. Ipapaketeng lahat ng scan mo sa isang file.
3. Piliin kung saan ise-save o ipadadala ang file. Hindi naka-encrypt ang file, kaya itago ito sa ligtas na lugar.
4. Sa bagong telepono, i-tap ang **Restore from backup** at piliin ang file. Magtatanong muna ang app bago palitan ang lahat ng scan sa telepono ng mga nasa backup.

## I-lock ang app at baguhin ang settings

1. Sa **Scans**, i-tap ang settings icon sa kanang itaas.
2. I-on ang **App lock** para hingin ang fingerprint, mukha o screen lock mo bago magbukas ang mga scan.
3. Sa ilalim ng **Text language (OCR)**, piliin ang script ng mga dokumento mo. Sakop ng **Latin** ang English, Spanish, French, German, Indonesian at iba pa. Ipinapayo ng app ang ginagamit ng wika ng telepono mo.
4. I-tap ang **App language** para gamitin ang app sa wikang iba sa wika ng telepono mo.
5. Piliin ang **Image quality** (Balanced o Full) at ang **Theme** (System, Light o Dark).

![Settings: Premium, App lock, Text language (OCR) at Image quality](shots/06-settings.png)

## Premium

Isang bayad lang ang Premium, hindi subscription. Buksan ang **Settings** at i-tap ang **See Premium**. Ito ang makukuha mo:

- Walang ad.
- Text na Chinese, Japanese at Korean, pati Hindi at iba pang Devanagari na text sa Android.
- Pagsasama ng ilang scan sa isang PDF o text file.
- Pag-import ng mas mahahabang PDF: hanggang 50 pahina sa halip na 20.

Kung nakabili ka na ng Premium dati, i-tap ang **Restore purchase** sa Premium screen.

## Mga tanong

**Gumagana ba ito nang offline?**
Oo. Ang pag-scan, pagkilala ng text, paghahanap at pag-export ay pawang gumagana sa telepono mo.

**Saan itinatago ang mga scan ko?**
Sa device mo lang. Kapag in-uninstall mo ang app, mabubura rin ang mga scan, kaya i-tap muna ang **Back up scans** sa Settings para mapanatili ang mga ito.

**May mali sa text. Ano ang puwede kong gawin?**
Kunan muli ng litrato sa magandang ilaw na patag ang pahina, subukan ang filter na **Magic** o **B&W**, at tiyaking tugma ang **Text language (OCR)** sa dokumento. Puwede mo ring ayusin ang mga indibidwal na salita gamit ang **Edit**.

**Nababasa ba nito ang sulat-kamay?**
Ginawa ito para sa naka-print na text. Madalas na mali ang basa sa sulat-kamay.

## Privacy

Hindi kailanman ina-upload ang mga dokumento mo. Ang libreng bersyon ay nagpapakita ng mga ad mula sa Google AdMob. Basahin ang buong [patakaran sa privacy](https://varian1.github.io/ocrscanner/privacy.html).
