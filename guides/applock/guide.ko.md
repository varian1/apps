---
title: 앱 잠금 AppLock: PIN·지문 잠금
name: AppLock
tagline: PIN, 패턴, 비밀번호, 지문으로 원하는 앱을 잠그세요. 오프라인에서도 작동합니다.
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.0
updated: 2026-11-10
privacy: https://varian1.github.io/privacy.html
---

## What it does

AppLock은 내가 고른 앱 앞에 잠금 화면을 띄웁니다. 누군가 잠긴 앱을 열면 PIN, 패턴, 비밀번호를 입력하거나 지문을 인식해야 앱 화면을 볼 수 있습니다. 앱 안에서는 이름이 "App Lock"으로 표시됩니다.

- 계정이 필요 없습니다. PIN, 잠근 앱 목록, 보안 기록, 침입자 사진은 휴대폰에만 저장되며 업로드되지 않습니다.
- 잘못된 코드를 계속 입력하는 사람의 사진을 찍을 수 있습니다.
- PIN을 잊어버려도 복구 코드로 다시 들어갈 수 있습니다.
- 광고가 있는 무료 앱입니다. 앱 잠금은 언제나 무료입니다. Premium을 한 번 구매하면 광고가 사라지고 추가 기능을 쓸 수 있습니다.

## Get started

1. AppLock을 열고 **Get started**를 탭하세요.
2. **How do you want to unlock?**에서 **PIN**, **Pattern**, **Password** 중 하나를 고르세요.
3. 입력한 뒤 확인을 위해 한 번 더 입력하세요. PIN은 6자리입니다. 패턴은 점을 4개 이상 이어야 합니다. 비밀번호는 4자 이상이어야 합니다. 패턴이나 비밀번호는 입력할 때마다 **Continue**를 탭하세요.
4. **Save your recovery code** 화면에서 8자리 코드를 적어 안전한 곳에 보관하세요. 이 코드는 한 번만 보이며, PIN, 패턴, 비밀번호를 잊었을 때 다시 들어갈 수 있는 유일한 방법입니다.
5. **I’ve saved this code somewhere safe**에 체크하고 **Continue**를 탭하세요.

이제 홈 화면입니다. 권한을 허용하고 첫 번째 앱을 잠그기 전까지는 **Protection off**라고 표시됩니다.

## 권한 허용하기

Android가 앱이 열린 것을 AppLock이 알아차리고 그 위에 잠금 화면을 그릴 수 있도록 허용해야 AppLock이 앱을 잠guardrail 수 있습니다. 이를 위해 **Accessibility**와 **Display over other apps** 두 가지 권한이 필요합니다. 나머지 권한은 선택 사항입니다.

1. 홈 화면에서 **Finish setup** 또는 **Permissions**를 탭하세요.
2. **Accessibility**를 탭하세요. AppLock이 먼저 **What Accessibility access does** 페이지를 보여 줍니다. 내용을 읽어 보세요.
3. **I understand — open settings**를 탭하세요. 동의하지 않으면 **Not now**를 탭하세요. 아무것도 바뀌지 않고 설정도 열리지 않습니다.
4. 열리는 Android 설정 화면에서 AppLock 서비스를 켜고 AppLock으로 돌아오세요.
5. **Display over other apps**를 탭하고 Android 설정 화면에서 허용하세요.
6. 허용하고 싶은 다른 항목도 탭하세요. 허용이 끝난 항목에는 **Granted**가 표시됩니다.

![Android 설정이 열리기 전에 나오는 "What Accessibility access does" 페이지](shots/05-accessibility-disclosure.png)

**AppLock이 접근성 권한을 요청하는 이유.** AppLock은 Android의 접근성 서비스를 단 한 가지 목적으로만 사용합니다. 어떤 앱이 방금 화면 앞으로 나왔는지 알아차려서, 내가 보호하려고 고른 앱 위에 잠금 화면을 보여 주기 위해서입니다.

- 하는 일: 방금 열린 앱의 이름만 확인합니다. 잠긴 앱이 잠금 해제되거나 잘못된 코드가 입력되면 그 앱의 이름이 휴대폰의 **Security log**에 저장되어 나중에 확인할 수 있습니다.
- 절대 하지 않는 일: AppLock 안에서든 다른 앱에서든 화면 내용, 키 입력, 비밀번호, 메시지 등 화면에 표시되는 어떤 데이터도 읽지 않습니다. 기기 밖으로 전송되는 정보도 없습니다.
- Android 설정에서 언제든 끌 수 있습니다. 끄면 AppLock이 더 이상 잠금 화면을 보여 줄 수 없습니다.

**나머지 권한은 어디에 쓰나요.**

- **Display over other apps**: 잠긴 앱 위에 잠금 화면이 나타나게 합니다.
- **Usage access**: 보호 기능이 안정적으로 작동하는지 확인하는 데 도움이 됩니다.
- **Notifications**: 잠금 안내와 침입 시도를 알려 줍니다.
- **Camera** (선택): 잠금 해제에 실패한 사람의 사진을 찍습니다.
- **Notification access**: 잠긴 앱의 알림 내용을 숨깁니다.
- **Ignore battery optimization**: 보호 기능이 백그라운드에서 계속 작동하게 합니다.

모든 권한은 휴대폰 안에서만 사용됩니다.

![권한 화면: 각 권한과 이유, 초록색 Granted 표시](shots/03-permissions.png)

## 잠글 앱 고르기

1. 홈 화면에서 **Lock apps**를 탭하세요.
2. 앱을 찾으세요. **Search apps**에 앱 이름을 입력하거나 **User**, **System**, **Recent** 탭을 오가며 찾을 수 있습니다. **Recent**에는 최근에 설치한 앱이 먼저 나옵니다.
3. 잠그고 싶은 앱 옆의 스위치를 켜세요.
4. 뒤로 가세요. 홈 화면에 **Protected**와 잠긴 앱 수가 표시됩니다.

![검색창, 탭, 앱별 스위치가 있는 Lock apps 목록](shots/06-lock-apps.png)

앱 잠금을 완전히 풀려면 **Lock apps**를 다시 열고 해당 앱의 스위치를 끄세요.

![Protected, 6 apps locked가 표시된 홈 화면과 Lock apps, Permissions, Security log, Intruder photos, Settings 메뉴](shots/01-home.png)

## 잠긴 앱 열기

1. 잠가 둔 앱을 여세요. 잠금 화면이 바로 앱을 덮습니다.
2. PIN, 패턴, 비밀번호를 입력하세요. **Unlock with biometrics**를 켰다면 지문으로 대신 열 수 있습니다.
3. 잘못 입력하면 다시 시도할 수 있습니다. 너무 많이 틀리면 잠시 기다려야 합니다.

AppLock 자체도 같은 방식으로 잠기므로 다른 사람이 내 설정을 바꿀 수 없습니다.

!["Enter your PIN"과 숫자 키패드가 있는 잠금 화면](shots/02-lock-screen.png)

## 잠금 방식 바꾸기

1. 홈 화면에서 **Settings**를 탭하세요.
2. **Appearance**에서 **System**, **Light**, **Dark** 중 하나를 고르세요.
3. **Re-lock**에서 잠금을 해제한 앱을 언제 다시 잠글지 고르세요. 앱을 나가자마자 잠그는 **Immediately**, **On screen off**, **After 5 min**이 있습니다.
4. **Security**에서 **Unlock with biometrics**를 켜세요. 먼저 PIN, 패턴, 비밀번호로 본인 확인을 합니다. 휴대폰에 지문이나 얼굴이 이미 등록되어 있어야 합니다.
5. **Protection**에서 **Scramble the PIN pad**를 켜면 숫자 키 위치가 뒤섞여, 손가락 위치만 보고 PIN을 짐작할 수 없습니다.
6. **Hide notification content for locked apps**를 켜면 잠긴 앱의 메시지 내용이 알림에 나타나지 않습니다. **Permissions**에서 **Notification access**를 허용해야 합니다.
7. **Disguise**에서 **Hide from Recents**를 켜면 최근 앱 목록에 AppLock이 나타나지 않습니다.

![Settings: Premium 카드, Appearance, Re-lock, Security](shots/04-settings.png)

## 누가 열어 보려 했는지 확인하기

1. **Settings**를 열고 **Intruder photo after failed attempts**를 켜세요.
2. **Permissions**를 열고 **Camera**를 허용하세요.
3. 이제 잠금 화면에서 연달아 세 번 틀리게 입력하면 전면 카메라가 사진을 찍습니다.
4. 홈 화면에서 **Intruder photos**를 탭하면 사진과 함께 열려고 했던 앱이 표시됩니다.
5. **Security log**를 탭하면 잠금 해제, 실패한 시도, 설정 변경 내역을 볼 수 있습니다.

![잠금 해제 실패 후 찍힌 사진이 있는 Intruder photos 화면](shots/07-intruder-photos.png)

## PIN을 잊었을 때 다시 들어가기

1. AppLock을 여세요. 잠금 해제 화면에서 **Can’t get in?**을 탭하세요.
2. 저장해 둔 8자리 복구 코드를 입력하고 **Continue**를 탭하세요.
3. 새 PIN, 패턴, 비밀번호를 설정하세요. 새 복구 코드가 발급되며 이전 코드는 더 이상 쓸 수 없습니다.

PIN을 아직 기억할 때 새 복구 코드를 받으려면 **Settings**를 열고 **Replace recovery code**를 탭하세요.

## Premium

Premium은 구독이 아니라 한 번만 결제하는 방식입니다. **Settings**를 열고 **Unlock Premium**을 탭하세요. Premium이 없어도 앱 잠금은 계속 무료입니다. Premium으로 다음 기능을 쓸 수 있습니다.

- 광고 제거
- **Fake crash screen (long-press to unlock)**: 잠금 화면 대신 잠긴 앱이 강제 종료된 것처럼 보입니다.
- 위장 아이콘: 홈 화면의 AppLock 아이콘과 이름을 **Calculator**, **Notes**, **Weather** 중 하나로 바꿉니다. **Calculator**를 고르면 **Open a real calculator instead**를 켜고 **Secret code**를 설정할 수 있습니다. 코드를 입력하고 =를 누르면 AppLock이 열립니다. PIN으로도 언제나 열 수 있습니다.
- 침입자 사진 전체 기록. 무료 버전에서는 최근 5장만 보입니다.
- **Export backup**: 설정과 잠금 목록을 내가 정한 비밀번호로 보호해 암호화한 사본으로 내보냅니다. **Restore backup**은 무료입니다.

이전에 Premium을 구매했다면 **Settings**에서 **Restore purchases**를 탭하세요.

## Questions

**AppLock에 접근성 권한이 왜 필요한가요?**
어떤 앱이 방금 열렸는지 알아차려서, 잠가 둔 앱 위에 잠금 화면을 보여 주기 위해서입니다. 화면에 있는 내용이나 입력하는 내용은 읽지 않습니다. 위의 "권한 허용하기"를 참고하세요.

**홈 화면에 "Protection off"라고 나와요. 무엇이 문제인가요?**
**Accessibility** 또는 **Display over other apps**가 허용되지 않았거나, 아직 잠근 앱이 없는 경우입니다. **Finish setup**을 탭해 권한 목록을 열고, **Lock apps**도 확인하세요.

**AppLock을 완전히 숨길 수 있나요?**
아니요. Android는 설치된 앱의 아이콘을 항상 남겨 둡니다. Premium을 쓰면 아이콘과 이름을 다른 모습으로 바꿀 수 있습니다.

**PIN을 잊었고 복구 코드도 잃어버렸어요. 초기화해 줄 수 있나요?**
아니요. AppLock은 계정 없이 오프라인으로 작동하므로 이메일로 초기화할 수 없습니다. 복구 코드가 다시 들어갈 수 있는 유일한 방법이니 안전한 곳에 보관하세요.

**백업에 PIN이나 침입자 사진이 들어 있나요?**
아니요. 백업을 복원하면 앱이 먼저 새 PIN, 패턴, 비밀번호를 설정하도록 안내합니다.

## Privacy

PIN, 잠근 앱, 보안 기록, 침입자 사진은 기기에만 저장되며 업로드되지 않습니다. 무료 버전에는 Google AdMob 광고가 표시됩니다. 자세한 내용은 [개인정보 처리방침](https://varian1.github.io/privacy.html)에서 확인하세요.
