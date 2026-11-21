---
title: Word Counter at Text Tools
name: Text Toolkit
tagline: Magbilang ng salita, magpalit ng case, maglinis at mag-ayos ng teksto, offline.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## Ano ang magagawa nito

Ang Text Toolkit ay iisang screen na may siyam na gamit para sa teksto. I-type o i-paste ang teksto sa kahon sa itaas, pumili ng gamit, at kopyahin o i-share ang resulta. Nagbibilang ito ng salita, nagpapalit ng letter case, naglilinis ng espasyo, nag-aayos ng mga linya, naghahanap at nagpapalit, nagbabaliktad, nag-e-encode, nagfo-format ng JSON at naghahambing ng dalawang teksto.

- Tumatakbo sa device mo ang bawat gamit at gumagana ito kahit walang internet.
- Walang account. Hindi ina-upload ang teksto mo, at hindi ginagamit ng app ang camera, mga larawan, contacts o lokasyon mo.
- Hindi sine-save ang teksto mo. Mawawala ito kapag isinara mo ang app.
- Libre. Maaaring may lumabas na banner ad sa ibaba ng screen.

## Pagsisimula

1. Buksan ang Text Toolkit. May maikling sample sa kahong **YOUR TEXT** para masubukan mo ang bawat gamit.
2. I-tap ang **Clear** at i-type ang sarili mong teksto, o i-tap ang **Paste** para palitan ang teksto ng kinopya mo sa ibang app. Ibabalik ng **Sample** ang sample na teksto.
3. Pumili ng gamit sa hanay sa ilalim ng kahon: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format** o **Diff**. I-swipe pahalang ang hanay para makita lahat.

![Pangunahing screen: ang kahong YOUR TEXT na may Paste, Sample at Clear, ang hanay ng mga gamit, at ang mga numero ng Counter](shots/01-home.png)

Sinusunod ng app ang wika ng telepono mo. Available ito sa 11 wika: English, Spanish, Portuguese, German, French, Hindi, Indonesian, Arabic, Italian, Russian at Turkish.

## Magbilang ng salita at karakter

1. I-tap ang **Counter**.
2. Basahin ang mga numero: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines** at **Reading time**.
3. Tingnan ang **TOP WORDS** sa ibaba para makita ang mga salitang pinakamadalas mong gamitin, hanggang walo, may kasamang bilang ng bawat isa.

Nagbabago ang mga numero habang nagta-type ka. Ang Reading time ay batay sa 200 salita kada minuto.

## Magpalit ng letter case

1. I-tap ang **Case**.
2. I-scroll ang mga card. Ipinapakita ng bawat isa ang teksto mo sa ibang istilo: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE** at **URL slug**.
3. I-tap ang **Copy** sa card na gusto mo.

![Case tool: mga card para sa UPPERCASE, lowercase at Title Case, bawat isa ay may Use input, Share at Copy](shots/02-case.png)

## Maglinis ng teksto

1. I-tap ang **Clean**.
2. Pumili ng isang aksyon:
   - **Clean all**: sabay-sabay na inaalis ang mga tab, paulit-ulit na espasyo, espasyo sa dulo ng mga linya, walang lamang linya at paulit-ulit na linya.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates** o **Remove tabs**: isa lang ang ginagawa.
   - Ang aksyon para sa line break: inaalis ang mga line break sa teksto mo.
3. Basahin ang resulta sa ilalim ng **CLEANED RESULT**. Hindi nagbabago ang sarili mong teksto sa kahon.

![Clean tool: ang mga button panlinis at ang card na CLEANED RESULT](shots/03-clean.png)

## Mag-ayos o magbaliktad

1. I-tap ang **Lines** para gumawa sa buong linya: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates** o **Reverse characters**. Hindi pinapansin ng pag-aayos ang malalaking titik at ang espasyo sa simula ng linya.
2. I-tap ang **Reverse** para baliktarin ang teksto: **Entire text**, **Each word**, **Word order**, **Line order** o **Characters per line**.
3. Lalabas ang resulta sa card sa ibaba ng mga button.

## Maghanap at magpalit

1. I-tap ang **Replace**.
2. I-type ang hahanapin sa **Find** at ang bagong teksto sa **Replace with**.
3. I-tap ang mga opsyon para i-on o i-off: **Replace all** (kapag off, ang unang tugma lang ang papalitan), **Case sensitive** at **Whole word**.
4. Tingnan ang bilang ng mga pinalitan at ang **REPLACEMENT PREVIEW**. Parehong nag-a-update habang nagta-type ka.

![Replace tool: mga field ng Find at Replace with, ang tatlong button ng opsyon, ang bilang ng pinalitan at ang preview](shots/04-replace.png)

Eksaktong tinatype mo ang hinahanap. Hindi ito gumagamit ng pattern o wildcard.

## Mag-encode, mag-decode at mag-format

1. I-tap ang **Encode**, piliin ang **URL**, **Base64** o **HTML Entities**, pagkatapos ay i-tap ang **Encode** o **Decode**.
2. I-tap ang **Format** at piliin ang **Format JSON** para lagyan ng indent na dalawang espasyo ang JSON, **Minify JSON** para gawin itong isang linya, o **Strip Markdown** para gawing payak na teksto ang Markdown.
3. Kung may mali ang JSON, may linya malapit sa itaas ng screen na nagsisimula sa "Invalid JSON" at nagsasabi kung ano ang mali.

## Maghambing ng dalawang teksto

1. Ilagay ang unang bersyon sa **YOUR TEXT** at i-tap ang **Diff**.
2. I-type o i-paste ang pangalawang bersyon sa **COMPARE WITH**.
3. Basahin ang **DIFF COMPARISON**. Ang mga linyang nasa pangalawang bersyon lang ay berde at may **+**. Ang mga linyang nasa unang bersyon lang ay pula at may **-**. Walang marka ang mga linyang magkapareho.
4. I-tap ang **Copy Diff** para kopyahin ang paghahambing kasama ang mga marka nitong + at -.

![Diff tool: ang kahong COMPARE WITH at ang card na DIFF COMPARISON na may isang berdeng idinagdag na linya at isang pulang inalis na linya](shots/05-diff.png)

## Kopyahin, i-share o magpatuloy

1. I-tap ang **Copy** sa card ng resulta para ilagay ito sa clipboard.
2. I-tap ang **Share** para ipadala ito sa ibang app.
3. I-tap ang **Use input** para ilipat ang resulta sa **YOUR TEXT**, para makagamit ka ng isa pang gamit dito.

## Premium

Libre ang bawat gamit. May isang opsyonal na minsanang bayad na nag-aalis ng mga ad. Isang beses ka lang magbabayad; hindi ito subscription.

## Mga tanong

**Gumagana ba ito offline?**
Oo. Tumatakbo sa telepono mo ang lahat ng siyam na gamit. Ang mga ad at ang pagbili para alisin ang mga ito lang ang gumagamit ng internet.

**Sine-save ba ang teksto ko?**
Hindi. Itinatago lang ng app ang teksto mo habang bukas ito. Kopyahin o i-share ang resultang gusto mong itago.

**Bakit walang laman ang resulta pagkatapos kong magpalit ng gamit?**
Iisang card ng resulta ang ginagamit ng Clean, Lines, Reverse, Encode at Format, at nabubura ito kapag nagpalit ka ng gamit. I-tap muli ang aksyon. Gawin din ito pagkatapos mong baguhin ang teksto mo. Kusang nag-a-update ang Counter, Case, Replace at Diff.

**Sumusunod ba ito sa dark mode?**
Oo. Ginagamit ng app ang light o dark theme na itinakda sa telepono mo.

**Nasaan ang mga lisensya?**
Mag-scroll sa pinakaibaba at i-tap ang **Open-source licenses**. Katabi nito ang **Privacy policy**.

## Privacy

Pino-proseso ang teksto mo sa telepono mo at hindi ito ina-upload o sine-save. Maaaring magpakita ang app ng mga ad mula sa Google AdMob; kung hinihingi ng batas, tatanungin ka muna sa pipiliin mo at mababago mo ito gamit ang **Ad privacy choices** sa pangunahing screen. Basahin ang buong [privacy policy](https://varian1.github.io/text-toolkit/privacy.html).
