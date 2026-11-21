---
title: QR Kod ve Barkod Okuyucu
name: QR & Barcode Toolkit
tagline: QR kod ve barkod okuyun, oluşturun. Cihazda çalışır, geçmiş ve dışa aktarma var.
project: QRBarcode and toolkit
package: com.varian1.qrtoolkit
version: 1.0.0
updated: 2026-11-21
privacy: https://varian1.github.io/qr-barcode-toolkit/privacy.html
---

## Ne işe yarar

QR & Barcode Toolkit, QR kodları ve barkodları kamerayla ya da bir fotoğraftan okur ve siz işlem yapmadan önce içinde ne olduğunu gösterir. Kendi QR kodlarınızı ve barkodlarınızı da oluşturup resim olarak kaydedebilir veya paylaşabilirsiniz. Uygulama 21 dilde sunulur ve telefonunuzun diline uyar.

- Kodlar cihazınızda okunur. Bağlantılar kendiliğinden açılmaz.
- Hesap gerekmez. Geçmişiniz telefonunuzda kalır.
- QR kodlarını ve EAN-13, UPC-A, Code 128 gibi 12 barkod türünü okur.
- Reklamlarla ücretsizdir. Tek seferlik Premium satın alımı reklamları kaldırır ve daha fazla stil seçeneği sunar.

## Başlarken

1. QR & Barcode Toolkit'i açın. **Home** ekranında dört kısayol görürsünüz: **Scan QR**, **Scan Barcode**, **Create QR** ve **Create Barcode**.
2. **Scan QR**'a dokunun. İlk seferde **Allow camera**'ya dokunun ve Android sorduğunda kamera iznini verin.
3. Kamerayı kullanmak istemezseniz **Scan from an image instead**'e dokunun ve bir fotoğraf seçin. Bunun için tüm fotoğraf arşivinize erişim gerekmez.

![Home ekranı: Scan QR, Scan Barcode, Create QR ve Create Barcode kısayolları ile Recent activity](shots/01-home.png)

## Kod tarama

1. Altta **Scan**'e ya da **Home** ekranındaki bir tarama kısayoluna dokunun.
2. Üstten **QR Code** veya **Barcode** seçin.
3. Kamerayı koda doğrultun. Barkodu çerçevenin içinde tutun.
4. Karanlıkta el feneri düğmesine dokunun. Fotoğraftan kod okumak için resim düğmesine dokunup fotoğrafı seçin.
5. Kod okunduğunda **Scan Result** açılır. İçeriğin türünü gösterir: **Website**, **Wi-Fi**, **Contact** veya **Product** gibi.
6. **Copy content** veya **Share as text**'e dokunun. Kameraya dönmek için **Scan another**'a dokunun.

![Tarayıcı: QR Code ve Barcode anahtarı, çerçeve, resim ve el feneri düğmeleri](shots/06-scan.png)

## Bağlantıyı açmadan önce kontrol etme

1. Web adresi içeren bir kodu tarayın. Sonuçta site adı ve tam adres görünür.
2. Varsa uyarıları okuyun. Uygulama şifrelenmemiş (http) bağlantılar, kısaltılmış bağlantılar, düz IP adresleri, gizlenmiş giriş bilgileri ve benzer görünen karakterler için uyarır.
3. Siteye güveniyorsanız **Open link**'e dokunun, ardından onaylamak için **Open**'a dokunun.

![Bir web sitesi için Scan Result: Open link düğmesinin üstünde iki uyarı](shots/03-link.png)

Diğer kod türlerinin kendi düğmesi vardır: **Compose email**, **Call**, **Send message**, **Open in Maps** veya **Search the web**. Her biri uygulamadan çıkmadan önce size sorar.

## Wi-Fi kodunu okuma

1. Wi-Fi QR kodunu tarayın. Sonuçta **Network**, **Security** ve **Password** görünür.
2. Parolayı göstermek için göz simgesine dokunun.
3. Parolanın yanındaki kopyala simgesine dokunun.
4. Telefonunuzun Wi-Fi ayarlarını açın ve kopyaladığınız parolayla ağa katılın. Uygulama sizin yerinize bağlanmaz.

![Wi-Fi kodu için Scan Result: ağ adı, güvenlik türü ve gizli parola](shots/02-wifi.png)

## QR kod oluşturma

1. **Create**'e dokunun ve **QR Code**'u seçin.
2. **Content type** altında **Website**, **Text**, **Wi-Fi**, **Email**, **Phone**, **SMS**, **Contact** veya **Location** seçin.
3. Alanları doldurun. Bilgiler geçerli olur olmaz QR kod görünür. Geçmişte bir adla görünmesini istiyorsanız **Title (optional)** alanını doldurun.
4. **Style** altında bir şablon seçin: **Classic**, **Indigo** veya **Forest**. **Foreground** ve **Background** renklerini ve **Error correction** düzeyini de değiştirebilirsiniz.
5. Saklamak için **Save to history**'ye, resmi göndermek için **Share**'e, galerinize kaydetmek için **Save image**'a dokunun.

![Create ekranı: Indigo şablonunda bir QR kod, altında Style şablonları ve renkler](shots/04-create.png)

Kilitli seçenekler Premium'a dahildir.

## Barkod oluşturma

1. **Create**'e dokunun ve **Barcode**'u seçin.
2. **Format** altında **EAN-13**, **EAN-8**, **UPC-A**, **Code 128**, **Code 39** veya **ITF-14** seçin.
3. **Value** alanına değeri yazın. Alanın altındaki satır, biçimin neyi kabul ettiğini söyler. Ürün kodlarında kontrol hanesini siz yazmazsanız uygulama ekler.
4. Ad vermek istiyorsanız **Title (optional)** alanını doldurun.
5. **Save to history**, **Share** veya **Save image**'a dokunun.

![EAN-13 barkod için Create ekranı: değer, barkod önizlemesi ve eklenen kontrol hanesi](shots/05-barcode.png)

## Kodları bulma, yeniden kullanma ve silme

1. **History**'ye dokunun. Taradığınız ve oluşturduğunuz kodlar listelenir.
2. **Search** alanına yazın ya da **All**, **Scanned**, **Created**, **Favorites**, **Any type**, **QR** ve **Barcode** ile süzün.
3. Favorilere eklemek için satırdaki yıldıza dokunun.
4. **Details**'i açmak için bir satıra dokunun. Buradan **Copy content**, **Share as text** veya **Delete**'e dokunabilirsiniz. QR kodlar ve uygulamanın oluşturabildiği barkod biçimlerinde kod ile birlikte **Share image** ve **Edit / reuse** da görünür.
5. Listeyi boşaltmak için üstteki çöp kutusu simgesine, ardından **Clear**'a dokunun. Favoriler korunur.

![History: arama kutusu, filtreler ve taranan ile oluşturulan kodların listesi](shots/07-history.png)

## Ayarları değiştirme

1. **Settings**'e dokunun.
2. Taramaların saklanmasını istemiyorsanız **Save scans to history**'yi kapatın.
3. **Haptic feedback**'i açın veya kapatın.
4. **Keep Wi-Fi passwords in history**'yi yalnızca parolaların kaydedilmesini istiyorsanız açın. Varsayılan olarak kapalıdır.
5. Uygulama dilini seçmek için **Language**'a dokunun. Varsayılan olarak uygulama telefonunuzun diline uyar.
6. Favoriler dahil tüm taramaları ve oluşturulan kodları silmek için **Clear all history**'ye, ardından **Delete all**'a dokunun.

![Settings: Preferences, Privacy ve About bölümleri](shots/08-settings.png)

## Premium

Premium tek seferlik bir ödemedir, abonelik değildir. **Settings**'i açıp **Go Premium**'a dokunun ya da **Home** ekranında **See plans**'a dokunun. Şunları sağlar:

- Reklam yok.
- Özel renkler, premium şablonlar ve QR kodunuza logo ekleme.
- Sınırsız geçmiş ve favori.
- 1024 px ve 2048 px dışa aktarma.

Premium olmadan kilitli bir şablona, renge veya **Add logo**'ya dokunduğunuzda **Watch an ad** seçeneği sunulabilir. Bu, uygulamayı kapatana kadar bu stil seçeneklerinin kilidini açar. Daha önce Premium aldıysanız **Settings** içinde **Restore purchases**'a dokunun.

## Sorular

**Uygulama bağlantıları kendiliğinden açar mı?**
Hayır. Önce adresi ve varsa uyarıları gösterir. Bağlantı yalnızca **Open link**'e dokunup onayladığınızda açılır.

**Hangi kodları okuyabilir?**
QR, EAN-13, EAN-8, UPC-A, UPC-E, Code 128, Code 39, Code 93, Codabar, ITF-14, PDF417, Data Matrix ve Aztec.

**Wi-Fi parolası neden geçmişimde yok?**
Wi-Fi parolaları kod kaydedilmeden önce silinir. Saklamak için kodu taramadan veya oluşturmadan önce **Settings** içinde **Keep Wi-Fi passwords in history**'yi açın.

**Kaç kod saklanır?**
Ücretsiz sürüm son 100 taramayı, son 100 oluşturulan kodu ve en fazla 10 favoriyi saklar. Ücretsiz liste dolduğunda **History** sizi bilgilendirir ve yeni öğeler en eskilerin yerine geçer. Liste dolduğunda favoriler silinmez. Premium'da sınır yoktur.

**Karanlık mod var mı?**
Evet. Uygulama telefonunuzun açık veya koyu temasına uyar.

## Gizlilik

Kodlar cihazınızda okunur ve geçmişiniz telefonunuzda kalır. Ücretsiz sürüm Google AdMob reklamları gösterir. Tüm [gizlilik politikasını](https://varian1.github.io/qr-barcode-toolkit/privacy.html) okuyun.
