---
title: Ekran Kilidi: Tek Dokunuş
name: TapLock
tagline: Telefonu tek dokunuşla kilitle. Parmak izi ve yüzle kilit açma çalışır.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## Ne işe yarar

TapLock, ekranına büyük bir **Lock** düğmesi koyar. Düğmeye dokunduğunda telefonun, güç düğmesine basmışsın gibi hemen kilitlenir. Güç düğmesine ulaşmak zorsa, düğme aşınmışsa ya da bozulmuşsa işine yarar.

- Erişilebilirlik kilidiyle telefonunun kilidini her zamanki gibi parmak izi, yüz, PIN veya desenle açarsın.
- Cihaz Yöneticisi kilidi, Erişilebilirlik olmadan çalışan ikinci bir kilitleme yoludur.
- Tek ekran, tek düğme. Hesap ve giriş yok.
- Reklamlarla ücretsiz.

## Başlarken

1. TapLock'u aç. İlk açılışta **Lock** düğmesinin altındaki satırda "One-time setup needed (about a minute)." yazar.
2. **Set up TapLock** düğmesine dokun. **Lock setup** ekranı açılır.
3. İki kilitleme yolundan birini seç:
   - **Accessibility lock** (önerilir, Android 9 veya üstü): güç düğmesi gibi kilitler, parmak izi ve yüzle kilit açma çalışmaya devam eder.
   - **Device Admin lock**: Erişilebilirlik olmadan çalışır. Android, bir sonraki kilit açışında PIN, desen veya parola ister.
4. Aşağıda seçtiğin yolun adımlarını izle.

**Lock setup** ekranını istediğin zaman ana ekranın sağ üstündeki ayarlar simgesiyle yeniden açabilirsin.

## Erişilebilirlik kilidini aç

1. **Lock setup** ekranında, **Accessibility lock** kartında **Turn on Accessibility lock** düğmesine dokun.
2. **Allow TapLock to use Accessibility?** başlıklı bir pencere açılır. TapLock'un bu izni nasıl kullandığını oku.
3. Devam etmek için **Agree** düğmesine dokun. **Decline** düğmesine dokunursan hiçbir şey değişmez ve Erişilebilirlik kilidi kapalı kalır.
4. Android'in Erişilebilirlik ayarları açılır. TapLock'u bul; genellikle "Downloaded apps" altındadır.
5. "Use TapLock" seçeneğini aç, **Allow** düğmesine dokun, sonra TapLock'a geri dön.
6. Kartta artık **On** yazar ve üstte **You're all set** görünür. **Back to Lock** düğmesine dokun.

![TapLock'un Erişilebilirlik'i kullanmasına izin verip vermediğini soran "Allow TapLock to use Accessibility?" penceresi, Decline ve Agree düğmeleriyle](shots/04-accessibility-consent.png)

**TapLock neden Erişilebilirlik izni ister?** TapLock, Erişilebilirlik Hizmeti API'sini yalnızca **Lock** düğmesine dokunduğunda ekranını kilitlemek için kullanır; bu, güç düğmesine basmakla aynıdır. Parmak izi ve yüzle kilit açma da bu yüzden çalışmaya devam eder. TapLock ekranını okumaz, ne yazdığını görmez ve bu izin üzerinden hiçbir kişisel veriyi toplamaz, saklamaz veya paylaşmaz. Android'in ayarları açılmadan önce **Agree** ya da **Decline** seçeneğini sen seçersin ve izni istediğin zaman yeniden kapatabilirsin.

Kart birkaç saniyeden uzun süre **Starting** gösteriyorsa Erişilebilirlik ayarlarında TapLock'u kapatıp yeniden aç. Android ayarlarındaki anahtar gri ve dokunulamıyorsa **Lock setup** ekranında **Switch greyed out?** seçeneğine dokun ve oradaki ipucunu izle.

## Bunun yerine Cihaz Yöneticisi kilidini kullan

1. **Lock setup** ekranında, **Device Admin lock** kartında **Enable Device Admin** düğmesine dokun.
2. Android onay ister. TapLock bu izni yalnızca **Lock** düğmesine dokunduğunda ekranı kilitlemek için kullanır.
3. Kartta artık **On** yazar.

![Lock setup ekranı: Accessibility lock kartında On yazıyor, Device Admin lock kartında Enable Device Admin düğmesi var](shots/02-setup.png)

Bu kilitleme yolunda Android, bir sonraki kilit açışında parmak izi veya yüz yerine PIN, desen ya da parola ister. İki yol da açıksa TapLock, Erişilebilirlik kilidini kullanır.

## Ekranını kilitle

1. TapLock'u aç. Düğmenin altındaki satır "Ready." ile başlar.
2. **Lock** düğmesine dokun. Ekran hemen kilitlenir.
3. Telefonunun kilidini her zamanki gibi aç.

![Yuvarlak Lock düğmesi ve "Ready. Fingerprint and face unlock stay on." satırıyla ana ekran](shots/01-home.png)

## Koyu modu kullan

1. Telefonunun Android ayarlarında koyu temayı aç.
2. TapLock'u aç. Telefonunu takip eder ve kendiliğinden koyu moda geçer. Uygulamada ayrı bir ayar yoktur.

![TapLock ana ekranı koyu modda](shots/03-dark-mode.png)

## Dili değiştir

1. Ana ekranda ayarlar simgesine dokunarak **Lock setup** ekranını aç.
2. Dil seçiciyi aç.
3. 31 dilden birini seç ya da sistem varsayılanını bırak; böylece TapLock telefonunun diline uyar.

![Dil listesini gösteren dil seçici](shots/06-language.png)

Arapça, Urduca ve İbranice sağdan sola gösterilir. Android 13 veya üstünde TapLock'un dilini Android'in uygulama dili ayarlarından da değiştirebilirsin.

## Bir kilit yöntemini kapat veya uygulamayı kaldır

1. Ana ekranda ayarlar simgesine dokunarak **Lock setup** ekranını aç.
2. Erişilebilirlik kilidini kapatmak için **Manage in Accessibility settings** düğmesine dokun ve TapLock'u orada kapat.
3. Cihaz Yöneticisi kilidini kapatmak için **Turn off Device Admin** düğmesine dokun.
4. TapLock'u kaldırmadan önce Cihaz Yöneticisi'ni kapat. Android, etkin bir cihaz yöneticisi olan uygulamanın kaldırılmasına izin vermez.

![You're all set kartı ve Cihaz Yöneticisi'ni kapatma düğmesiyle Lock setup ekranı](shots/05-device-admin-on.png)

## Sorular

**TapLock neden Erişilebilirlik iznine ihtiyaç duyar?**
Yalnızca **Lock** düğmesine dokunduğunda ekranı kilitlemek için; bu, güç düğmesine basmakla aynıdır. Ekranını okumaz, ne yazdığını görmez. İzni vermek istemezsen Cihaz Yöneticisi kilidini kullan.

**TapLock ile kilitledikten sonra parmak izim çalışmıyor. Neden?**
Cihaz Yöneticisi kilidini kullanıyorsun; bu yöntemde Android bir kez PIN, desen veya parola ister. Parmak izi ve yüzle kilit açmanın çalışmaya devam etmesi için Erişilebilirlik kilidini aç.

**TapLock'u kaldıramıyorum. Ne yapabilirim?**
**Lock setup** ekranını aç, **Turn off Device Admin** düğmesine dokun, sonra uygulamayı kaldır.

**Hangi Android sürümü gerekir?**
Erişilebilirlik kilidi için Android 9 veya üstü gerekir. Daha eski sürümlerde Cihaz Yöneticisi kilidini kullan.

**TapLock'u kendi dilimde kullanabilir miyim?**
Evet. TapLock 31 dilde gelir. Dilini **Lock setup** ekranında seç ya da sistem varsayılanını bırak.

## Gizlilik

TapLock, Erişilebilirlik ve Cihaz Yöneticisi izinlerini yalnızca ekranını kilitlemek için kullanır ve bu izinler üzerinden kişisel veri toplamaz. Uygulama Google AdMob reklamları gösterir; gerekli olan yerlerde reklam tercihlerini **Lock setup** ekranındaki **Privacy settings** ile değiştirebilirsin. Tam [gizlilik politikasını](https://varian1.github.io/LockAppOnlyWeb/privacy.html) oku.
