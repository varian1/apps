---
title: Kelime Sayacı: Text Toolkit
name: Text Toolkit
tagline: Metni çevrimdışı say, harf boyutunu değiştir, temizle, sırala ve karşılaştır.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## Ne işe yarar

Text Toolkit, dokuz metin aracı sunan tek bir ekrandır. Üstteki kutuya metin yazın veya yapıştırın, bir araç seçin, sonucu kopyalayın ya da paylaşın. Kelime sayar, harf büyüklüğünü değiştirir, boşlukları temizler, satırları sıralar, bul ve değiştir yapar, metni ters çevirir, kodlar, JSON biçimlendirir ve iki metni karşılaştırır.

- Tüm araçlar cihazınızda çalışır, internet gerekmez.
- Hesap yok. Metniniz hiçbir zaman yüklenmez; uygulama kameranızı, fotoğraflarınızı, kişilerinizi ya da konumunuzu kullanmaz.
- Metniniz kaydedilmez. Uygulamayı kapattığınızda silinir.
- Ücretsiz. Ekranın altında bir banner reklam görünebilir.

## Başlarken

1. Text Toolkit'i açın. **YOUR TEXT** kutusunda kısa bir örnek metin bulunur; her aracı bununla deneyebilirsiniz.
2. **Clear**'a dokunup kendi metninizi yazın ya da **Paste**'e dokunarak metni başka bir uygulamada kopyaladığınızla değiştirin. **Sample** örnek metni geri getirir.
3. Kutunun altındaki sıradan bir araç seçin: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format** veya **Diff**. Hepsini görmek için sırayı yana kaydırın.

![Ana ekran: Paste, Sample ve Clear düğmeleriyle YOUR TEXT kutusu, araç sırası ve Counter sayıları](shots/01-home.png)

Uygulama telefonunuzun dilini kullanır. 11 dilde sunulur: İngilizce, İspanyolca, Portekizce, Almanca, Fransızca, Hintçe, Endonezce, Arapça, İtalyanca, Rusça ve Türkçe.

## Kelime ve karakter say

1. **Counter**'a dokunun.
2. Sayılara bakın: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines** ve **Reading time**.
3. En çok kullandığınız kelimeleri, sayılarıyla birlikte en fazla sekiz tane olarak görmek için aşağıdaki **TOP WORDS** bölümüne bakın.

Sayılar siz yazdıkça değişir. Okuma süresi dakikada 200 kelimeye göre hesaplanır.

## Harf büyüklüğünü değiştir

1. **Case**'e dokunun.
2. Kartları kaydırın. Her kart metninizi başka bir biçimde gösterir: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE** ve **URL slug**.
3. İstediğiniz kartta **Copy**'ye dokunun.

![Case aracı: UPPERCASE, lowercase ve Title Case kartları; her birinde Use input, Share ve Copy var](shots/02-case.png)

## Metni temizle

1. **Clean**'e dokunun.
2. Bir işleme dokunun:
   - **Clean all**: sekmeleri, tekrarlanan boşlukları, satır sonlarındaki boşlukları, boş satırları ve tekrarlanan satırları tek seferde siler.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates** veya **Remove tabs**: yalnızca o işlemi yapar.
   - Satır sonu işlemi: metninizdeki satır sonlarını kaldırır.
3. Sonucu **CLEANED RESULT** altında okuyun. Kutudaki kendi metniniz olduğu gibi kalır.

![Clean aracı: temizleme düğmeleri ve CLEANED RESULT kartı](shots/03-clean.png)

## Sırala veya ters çevir

1. Tam satırlarla çalışmak için **Lines**'a dokunun: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates** veya **Reverse characters**. Sıralama, büyük harfleri ve satır başındaki boşlukları yok sayar.
2. Metni ters çevirmek için **Reverse**'e dokunun: **Entire text**, **Each word**, **Word order**, **Line order** veya **Characters per line**.
3. Sonuç, düğmelerin altındaki kartta görünür.

## Bul ve değiştir

1. **Replace**'e dokunun.
2. Aranacak metni **Find** alanına, yeni metni **Replace with** alanına yazın.
3. Seçenekleri açıp kapatmak için dokunun: **Replace all** (kapalıyken yalnızca ilk eşleşme değişir), **Case sensitive** ve **Whole word**.
4. Değiştirme sayısına ve **REPLACEMENT PREVIEW** bölümüne bakın. İkisi de siz yazdıkça güncellenir.

![Replace aracı: Find ve Replace with alanları, üç seçenek düğmesi, değiştirme sayısı ve önizleme](shots/04-replace.png)

Arama, yazdığınızın birebir aynısını arar. Desen ya da joker karakter kullanmaz.

## Kodla, kodu çöz ve biçimlendir

1. **Encode**'a dokunun, **URL**, **Base64** veya **HTML Entities** seçin, sonra **Encode** ya da **Decode**'a dokunun.
2. **Format**'a dokunun ve JSON'u iki boşlukla girintilemek için **Format JSON**, tek satıra almak için **Minify JSON**, Markdown'ı düz metne çevirmek için **Strip Markdown** seçin.
3. JSON'da hata varsa ekranın üst kısmındaki bir satır "Invalid JSON" ile başlar ve neyin yanlış olduğunu söyler.

## İki metni karşılaştır

1. İlk sürümü **YOUR TEXT** kutusuna koyun ve **Diff**'e dokunun.
2. İkinci sürümü **COMPARE WITH** kutusuna yazın veya yapıştırın.
3. **DIFF COMPARISON** bölümünü okuyun. Yalnızca ikinci sürümde olan satırlar **+** ile yeşil görünür. Yalnızca ilk sürümde olan satırlar **-** ile kırmızı görünür. Eşleşen satırlarda işaret yoktur.
4. Karşılaştırmayı + ve - işaretleriyle kopyalamak için **Copy Diff**'e dokunun.

![Diff aracı: COMPARE WITH kutusu ve DIFF COMPARISON kartı; bir yeşil eklenen satır ve bir kırmızı silinen satır](shots/05-diff.png)

## Kopyala, paylaş veya çalışmaya devam et

1. Sonucu panoya almak için sonuç kartında **Copy**'ye dokunun.
2. Başka bir uygulamaya göndermek için **Share**'e dokunun.
3. Sonucu **YOUR TEXT** kutusuna taşımak için **Use input**'a dokunun; böylece üzerinde başka bir araç çalıştırabilirsiniz.

## Premium

Tüm araçlar ücretsizdir. İsteğe bağlı, tek seferlik bir satın alma reklamları kaldırır. Bir kez ödersiniz; abonelik değildir.

## Sorular

**Çevrimdışı çalışır mı?**
Evet. Dokuz aracın hepsi telefonunuzda çalışır. Yalnızca reklamlar ve reklamları kaldıran satın alma internet bağlantısı kullanır.

**Metnim kaydediliyor mu?**
Hayır. Uygulama metninizi yalnızca açık olduğu sürece tutar. Saklamak istediğiniz sonucu kopyalayın veya paylaşın.

**Araç değiştirdikten sonra sonuç neden boş?**
Clean, Lines, Reverse, Encode ve Format tek bir sonuç kartını paylaşır ve araç değiştirdiğinizde bu kart temizlenir. İşleme yeniden dokunun. Metninizi düzenledikten sonra da aynısını yapın. Counter, Case, Replace ve Diff kendiliğinden güncellenir.

**Karanlık modu destekliyor mu?**
Evet. Uygulama, telefonunuzda ayarlı açık ya da koyu temayı kullanır.

**Lisanslar nerede?**
En alta kaydırın ve **Open-source licenses**'a dokunun. **Privacy policy** onun yanındadır.

## Gizlilik

Metniniz telefonunuzda işlenir; hiçbir zaman yüklenmez veya kaydedilmez. Uygulama Google AdMob reklamları gösterebilir; yasanın gerektirdiği yerlerde önce tercihiniz sorulur ve bunu ana ekrandaki **Ad privacy choices** ile değiştirebilirsiniz. Tam [gizlilik politikasını](https://varian1.github.io/text-toolkit/privacy.html) okuyun.
