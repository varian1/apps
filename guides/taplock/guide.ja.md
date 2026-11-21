---
title: 画面ロック ワンタップでスマホをロック
name: TapLock
tagline: ワンタップでスマホをロック。指紋認証・顔認証でのロック解除もそのまま使えます。
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## What it does

TapLockは、画面に大きな**Lock**ボタンを1つ置くアプリです。タップするとすぐに画面がロックされます。電源ボタンを押したときと同じです。電源ボタンが押しにくいとき、すり減ったとき、壊れたときに便利です。

- Accessibility lockなら、いつもどおり指紋、顔、PIN、パターンでロックを解除できます。
- Device Admin lockは、Accessibilityを使わずにロックできるもう1つの方法です。
- 画面は1つ、ボタンも1つ。アカウント登録もログインも不要です。
- 無料で使えます（広告付き）。

## Get started

1. TapLockを開きます。初回は、**Lock**ボタンの下に「One-time setup needed (about a minute).」と表示されます。
2. **Set up TapLock**をタップします。**Lock setup**画面が開きます。
3. 2つのロック方法から1つを選びます。
   - **Accessibility lock**（おすすめ。Android 9以降）：電源ボタンと同じようにロックされ、指紋認証と顔認証も使えます。
   - **Device Admin lock**：Accessibilityなしで使えます。次にロックを解除するとき、AndroidがPIN、パターン、パスワードの入力を求めます。
4. 選んだ方法に合わせて、下の手順に進みます。

**Lock setup**は、ホーム画面の右上にある設定アイコンからいつでも開けます。

## Turn on Accessibility lock

1. **Lock setup**の**Accessibility lock**カードで、**Turn on Accessibility lock**をタップします。
2. **Allow TapLock to use Accessibility?**というダイアログが表示されます。TapLockがこの権限をどう使うかを読みます。
3. 続けるには**Agree**をタップします。**Decline**をタップした場合は何も変わらず、Accessibility lockはオフのままです。
4. AndroidのAccessibility設定が開きます。TapLockを探します。「Downloaded apps」の中にあることが多いです。
5. 「Use TapLock」をオンにして**Allow**をタップし、TapLockに戻ります。
6. カードに**On**と表示され、画面上部に**You're all set**と表示されます。**Back to Lock**をタップします。

![「Allow TapLock to use Accessibility?」のダイアログ。DeclineボタンとAgreeボタンが表示されています](shots/04-accessibility-consent.png)

**TapLockがAccessibilityを必要とする理由**：TapLockはAccessibility Service APIを、**Lock**ボタンをタップしたときに画面をロックするためだけに使います。電源ボタンを押すのと同じ動作です。そのため、指紋認証や顔認証も引き続き使えます。TapLockは、この権限を通じて画面の内容を読み取ったり、入力内容を見たり、個人データを収集・保存・共有したりすることはありません。Androidの設定が開く前に**Agree**か**Decline**を選べます。オフにしたいときは、いつでもオフにできます。

カードに**Starting**が数秒以上表示されたままのときは、Accessibility設定でTapLockをいったんオフにして、もう一度オンにしてください。Androidの設定でスイッチがグレーになって押せない場合は、**Lock setup**の**Switch greyed out?**をタップして、表示されるヒントに従ってください。

## Use Device Admin lock instead

1. **Lock setup**の**Device Admin lock**カードで、**Enable Device Admin**をタップします。
2. Androidが確認を求めます。TapLockはこの権限を、**Lock**ボタンをタップしたときに画面をロックするためだけに使います。
3. カードに**On**と表示されます。

![Lock setup画面。Accessibility lockカードにOnと表示され、Device Admin lockカードにEnable Device Adminボタンがあります](shots/02-setup.png)

この方法でロックすると、次にロックを解除するとき、指紋や顔ではなく、AndroidがPIN、パターン、パスワードの入力を求めます。両方の方法がオンの場合、TapLockはAccessibility lockを使います。

## Lock your screen

1. TapLockを開きます。ボタンの下の文は「Ready.」で始まります。
2. **Lock**をタップします。画面がすぐにロックされます。
3. いつもどおりにスマホのロックを解除します。

![丸い Lockボタンと「Ready. Fingerprint and face unlock stay on.」の文があるホーム画面](shots/01-home.png)

## Use dark mode

1. スマホのAndroid設定でダークテーマをオンにします。
2. TapLockを開きます。スマホの設定に合わせて、自動でダークモードに切り替わります。アプリの中に別の設定はありません。

![ダークモードのTapLockホーム画面](shots/03-dark-mode.png)

## Change the language

1. ホーム画面で設定アイコンをタップして、**Lock setup**を開きます。
2. 言語の選択画面を開きます。
3. 31の言語から1つを選びます。システムの既定のままにすると、TapLockはスマホの言語に合わせます。

![言語の一覧が表示された言語選択画面](shots/06-language.png)

アラビア語、ウルドゥー語、ヘブライ語は右から左に表示されます。Android 13以降では、Androidのアプリの言語設定からもTapLockの言語を変更できます。

## Turn a lock method off or uninstall

1. ホーム画面で設定アイコンをタップして、**Lock setup**を開きます。
2. Accessibility lockをオフにするには、**Manage in Accessibility settings**をタップして、そこでTapLockをオフにします。
3. Device Admin lockをオフにするには、**Turn off Device Admin**をタップします。
4. TapLockをアンインストールする前に、Device Adminをオフにしてください。Androidでは、デバイス管理アプリとして有効になっているアプリはアンインストールできません。

![「You're all set」カードとDevice AdminをオフにするボタンがあるLock setup画面](shots/05-device-admin-on.png)

## Questions

**TapLockにAccessibilityの権限が必要なのはなぜですか？**
**Lock**をタップしたときに画面をロックするためだけです。電源ボタンを押すのと同じ動作です。画面の内容を読み取ったり、入力内容を見たりすることはありません。許可したくない場合は、Device Admin lockを使ってください。

**TapLockでロックしたあと、指紋認証が使えません。なぜですか？**
Device Admin lockを使っているためです。この方法では、Androidが1回、PIN、パターン、パスワードの入力を求めます。指紋認証と顔認証を使い続けたい場合は、Accessibility lockをオンにしてください。

**TapLockをアンインストールできません。どうすればいいですか？**
**Lock setup**を開き、**Turn off Device Admin**をタップしてから、アンインストールしてください。

**どのAndroidバージョンが必要ですか？**
Accessibility lockにはAndroid 9以降が必要です。それより古いバージョンでは、Device Admin lockを使ってください。

**TapLockを日本語で使えますか？**
はい。TapLockは31の言語に対応しています。**Lock setup**で言語を選ぶか、システムの既定のままにしてください。

## Privacy

TapLockは、AccessibilityとDevice Adminの権限を画面をロックするためだけに使い、これらの権限を通じて個人データを収集することはありません。アプリにはGoogle AdMobの広告が表示されます。必要な地域では、**Lock setup**の**Privacy settings**から広告の選択を変更できます。詳しくは[プライバシーポリシー](https://varian1.github.io/LockAppOnlyWeb/privacy.html)をご覧ください。
