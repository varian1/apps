---
title: アプリロック：PINでアプリをロック
name: AppLock
tagline: PIN・パターン・パスワード・指紋でアプリをロック。オフラインで使えます。
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.0
updated: 2026-11-10
privacy: https://varian1.github.io/privacy.html
---

## できること

AppLockは、選んだアプリの前にロック画面を表示します。ロックしたアプリを開くと、PIN・パターン・パスワードを入力するか指紋で認証しない限り、中身を見られません。アプリ内では名前が「App Lock」と表示されます。

- アカウントは不要です。PIN、ロックしたアプリの一覧、セキュリティログ、侵入者の写真はすべてスマートフォンの中に保存され、アップロードされません。
- 間違ったコードを何度も入力した人の写真を撮影できます。
- PINを忘れても、リカバリーコードで再びアクセスできます。
- 広告つきで無料です。アプリのロックはずっと無料で使えます。1回払いのPremiumで広告が消え、機能も追加されます。

## はじめに

1. AppLockを開き、**Get started** をタップします。
2. **How do you want to unlock?** で、**PIN**、**Pattern**、**Password** のいずれかを選びます。
3. 入力し、確認のためもう一度入力します。PINは6桁です。パターンは4つ以上の点をつなぎます。パスワードは4文字以上です。パターンとパスワードは、入力のたびに **Continue** をタップします。
4. **Save your recovery code** の画面で、表示された8桁のコードを書き留め、安全な場所に保管します。コードが表示されるのは一度だけです。PIN、パターン、パスワードを忘れたときに再びアクセスする方法は、このコードだけです。
5. **I’ve saved this code somewhere safe** にチェックを入れ、**Continue** をタップします。

ホーム画面が表示されます。権限を許可して最初のアプリをロックするまでは、**Protection off** と表示されます。

## 権限を許可する

アプリのロックには、Androidからの2つの許可が必要です。1つは、アプリが開かれたことを検知すること。もう1つは、その上にロック画面を表示することです。必要な権限は **Accessibility** と **Display over other apps** の2つです。そのほかの権限は任意です。

1. ホーム画面で **Finish setup** または **Permissions** をタップします。
2. **Accessibility** をタップします。AppLockはまず **What Accessibility access does** というページを表示します。内容を読んでください。
3. **I understand — open settings** をタップします。同意しない場合は **Not now** をタップしてください。何も変更されず、設定画面も開きません。
4. 開いたAndroidの設定画面で、AppLockのサービスをオンにして、AppLockに戻ります。
5. **Display over other apps** をタップし、Androidの設定画面で許可します。
6. ほかに許可したい項目があれば、その行をタップします。許可が完了すると、行に **Granted** と表示されます。

![Androidの設定を開く前に表示される「What Accessibility access does」のページ](shots/05-accessibility-disclosure.png)

**AppLockがAccessibilityを必要とする理由** AppLockはAndroidのAccessibilityサービスを、ひとつの目的のためだけに使います。どのアプリが前面に出たかを検知して、保護対象に選んだアプリの上にロック画面を表示するためです。

- 行うこと：開かれたアプリの名前だけを監視します。ロックしたアプリが解除されたときや、間違ったコードが入力されたときは、そのアプリ名がスマートフォン内の **Security log** に保存され、あとから確認できます。
- 行わないこと：画面の内容、キー入力、パスワード、メッセージなど、画面上のデータは、AppLockの中でも他のアプリでも一切読み取りません。端末の外には何も送信されません。
- Androidの設定からいつでもオフにできます。オフにすると、AppLockはロック画面を表示できなくなります。

**そのほかの権限の用途**

- **Display over other apps**：ロックしたアプリの上にロック画面を表示します。
- **Usage access**：保護が正しく動いているかの確認に役立ちます。
- **Notifications**：ロックの案内や不正アクセスの試みをお知らせします。
- **Camera**（任意）：ロック解除に失敗した人の写真を撮影します。
- **Notification access**：ロックしたアプリの通知内容を隠します。
- **Ignore battery optimization**：バックグラウンドで保護を動かし続けます。

どの権限も、スマートフォンの中だけで使われます。

![権限の画面：各権限の理由と、緑色の Granted 表示](shots/03-permissions.png)

## ロックするアプリを選ぶ

1. ホーム画面で **Lock apps** をタップします。
2. アプリを探します。**Search apps** にアプリ名を入力するか、**User**、**System**、**Recent** のタブを切り替えます。**Recent** では、新しくインストールしたアプリが先頭に表示されます。
3. ロックしたいアプリの横にあるスイッチをオンにします。
4. 前の画面に戻ります。ホーム画面に **Protected** と、ロック中のアプリの数が表示されます。

![検索欄、タブ、各アプリのスイッチが並ぶ Lock apps の一覧](shots/06-lock-apps.png)

アプリのロックを完全にやめるには、もう一度 **Lock apps** を開き、そのアプリのスイッチをオフにします。

![ホーム画面：Protected、6 apps locked、Lock apps、Permissions、Security log、Intruder photos、Settings](shots/01-home.png)

## ロックしたアプリを開く

1. ロックしたアプリを開きます。すぐにロック画面が表示されます。
2. PIN、パターン、パスワードを入力します。**Unlock with biometrics** をオンにしている場合は、指紋でも解除できます。
3. 入力を間違えても、もう一度試せます。間違いが続くと、しばらく待つ必要があります。

AppLock自体も同じようにロックされるので、ほかの人が設定を変更することはできません。

![「Enter your PIN」とテンキーが表示されたロック画面](shots/02-lock-screen.png)

## ロックの動作を変更する

1. ホーム画面で **Settings** をタップします。
2. **Appearance** で、**System**、**Light**、**Dark** から選びます。
3. **Re-lock** で、解除したアプリがいつ再びロックされるかを選びます。アプリを離れたらすぐの **Immediately**、画面を消したときの **On screen off**、5分後の **After 5 min** から選べます。
4. **Security** で **Unlock with biometrics** をオンにします。先にPIN、パターン、パスワードで本人確認をします。スマートフォンに指紋または顔認証が設定されている必要があります。
5. **Protection** で **Scramble the PIN pad** をオンにすると、数字キーの配置が入れ替わり、タップする位置からPINを推測されにくくなります。
6. **Hide notification content for locked apps** をオンにすると、ロックしたアプリのメッセージの内容を隠せます。これには **Permissions** の **Notification access** が必要です。
7. **Disguise** で **Hide from Recents** をオンにすると、最近使ったアプリの一覧にAppLockが表示されなくなります。

![Settings：Premiumカード、Appearance、Re-lock、Security](shots/04-settings.png)

## 誰が開こうとしたか確認する

1. **Settings** を開き、**Intruder photo after failed attempts** をオンにします。
2. **Permissions** を開き、**Camera** を許可します。
3. 以後、ロック画面で3回続けて間違えると、フロントカメラで写真が撮影されます。
4. ホーム画面で **Intruder photos** をタップすると、写真と、開かれたアプリを確認できます。
5. **Security log** をタップすると、ロック解除、失敗した試行、設定の変更を確認できます。

![ロック解除の失敗後に撮影された写真が並ぶ Intruder photos 画面](shots/07-intruder-photos.png)

## PINを忘れたときに再びアクセスする

1. AppLockを開きます。ロック解除画面で **Can’t get in?** をタップします。
2. 保存しておいた8桁のリカバリーコードを入力し、**Continue** をタップします。
3. 新しいPIN、パターン、パスワードを設定します。新しいリカバリーコードが発行され、古いコードは使えなくなります。

PINがわかっているうちに新しいリカバリーコードを作りたいときは、**Settings** を開き、**Replace recovery code** をタップします。

## Premium

Premiumは1回払いで、定期購入ではありません。**Settings** を開き、**Unlock Premium** をタップします。Premiumがなくても、アプリのロックは無料で使えます。Premiumで使えるようになる機能は次のとおりです。

- 広告が表示されなくなります。
- **Fake crash screen (long-press to unlock)**：ロックしたアプリを開くと、ロック画面の代わりに、アプリがクラッシュしたような画面が表示されます。
- アイコンの偽装：ホーム画面のAppLockのアイコンと名前を **Calculator**、**Notes**、**Weather** に変更できます。**Calculator** では、**Open a real calculator instead** をオンにして **Secret code** を設定できます。コードを入力して = を押すと、AppLockが開きます。PINでもいつでも開けます。
- 侵入者の写真の全履歴。無料版では最新の5件が表示されます。
- **Export backup**：設定とロック一覧の暗号化されたコピーを、自分で決めたパスワードで保護して作成します。**Restore backup** は無料です。

以前にPremiumを購入した場合は、**Settings** で **Restore purchases** をタップします。

## よくある質問

**AppLockはなぜAccessibility権限が必要なのですか？**
どのアプリが開かれたかを検知して、ロックしたアプリの上にロック画面を表示するためだけです。画面の内容や入力した内容は読み取りません。前の「権限を許可する」もご覧ください。

**ホーム画面に「Protection off」と表示されます。何が問題ですか？**
**Accessibility** か **Display over other apps** が許可されていないか、まだロックしているアプリがありません。**Finish setup** をタップして権限の一覧を開き、そのあと **Lock apps** を確認してください。

**AppLockを完全に隠せますか？**
できません。Androidでは、インストールしたアプリのアイコンが必ず残ります。Premiumでは、アイコンと名前を別のものに変えて偽装できます。

**PINを忘れ、リカバリーコードも失くしました。リセットしてもらえますか？**
できません。AppLockはアカウントなしのオフラインで動くため、メールでのリセットはありません。再びアクセスする方法は、リカバリーコードだけです。安全な場所に保管してください。

**バックアップにPINや侵入者の写真は含まれますか？**
含まれません。バックアップを復元すると、まず新しいPIN、パターン、パスワードの設定を求められます。

## プライバシー

PIN、ロックしたアプリ、セキュリティログ、侵入者の写真は端末内に保存され、アップロードされません。無料版では Google AdMob の広告が表示されます。詳しくは[プライバシーポリシー](https://varian1.github.io/privacy.html)をご覧ください。
