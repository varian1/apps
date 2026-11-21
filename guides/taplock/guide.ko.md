---
title: 화면 잠금 원터치 버튼
name: TapLock
tagline: 버튼 한 번으로 휴대폰을 잠그세요. 지문·얼굴 인식 잠금 해제도 그대로 쓸 수 있어요.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## 주요 기능

TapLock은 화면에 큰 **Lock** 버튼 하나를 보여 줍니다. 버튼을 누르면 전원 버튼을 누른 것처럼 휴대폰이 바로 잠깁니다. 전원 버튼이 손에 닿기 어렵거나, 닳았거나, 고장 났을 때 편리합니다.

- Accessibility lock을 쓰면 지문, 얼굴, PIN, 패턴으로 평소처럼 잠금을 해제할 수 있습니다.
- Device Admin lock은 Accessibility 없이 쓸 수 있는 또 하나의 잠금 방법입니다.
- 화면 하나, 버튼 하나. 계정도 로그인도 필요 없습니다.
- 광고가 포함된 무료 앱입니다.

## 시작하기

1. TapLock을 엽니다. 처음에는 **Lock** 버튼 아래에 "One-time setup needed (about a minute)."라는 문구가 보입니다.
2. **Set up TapLock**을 누릅니다. **Lock setup** 화면이 열립니다.
3. 두 가지 잠금 방법 중 하나를 고릅니다.
   - **Accessibility lock** (권장, Android 9 이상): 전원 버튼처럼 잠기며, 지문·얼굴 인식 잠금 해제도 계속 쓸 수 있습니다.
   - **Device Admin lock**: Accessibility 없이 작동합니다. 다음에 잠금을 해제할 때 Android가 PIN, 패턴 또는 비밀번호를 요구합니다.
4. 고른 방법에 맞춰 아래 안내를 따릅니다.

홈 화면 오른쪽 위의 설정 아이콘을 누르면 언제든지 **Lock setup**을 다시 열 수 있습니다.

## Accessibility lock 켜기

1. **Lock setup**의 **Accessibility lock** 카드에서 **Turn on Accessibility lock**을 누릅니다.
2. **Allow TapLock to use Accessibility?** 대화상자가 나타납니다. TapLock이 이 권한을 어떻게 쓰는지 읽어 보세요.
3. 계속하려면 **Agree**를 누릅니다. **Decline**을 누르면 아무것도 바뀌지 않고 Accessibility lock은 꺼진 채로 남습니다.
4. Android의 접근성 설정이 열립니다. TapLock을 찾으세요. 보통 "Downloaded apps" 아래에 있습니다.
5. "Use TapLock"을 켜고 **Allow**를 누른 다음 TapLock으로 돌아옵니다.
6. 카드에 **On**이 표시되고 화면 위쪽에 **You're all set**이 나타납니다. **Back to Lock**을 누릅니다.

![Decline, Agree 버튼이 있는 "Allow TapLock to use Accessibility?" 대화상자](shots/04-accessibility-consent.png)

**TapLock이 Accessibility 권한을 요청하는 이유** TapLock은 **Lock** 버튼을 눌렀을 때 화면을 잠그는 데에만 Accessibility Service API를 사용합니다. 전원 버튼을 누르는 것과 같은 동작이며, 그래서 지문·얼굴 인식 잠금 해제도 계속 작동합니다. TapLock은 이 권한으로 화면을 읽거나, 입력하는 내용을 보거나, 개인정보를 수집·저장·공유하지 않습니다. Android 설정이 열리기 전에 **Agree** 또는 **Decline**을 직접 선택할 수 있고, 언제든지 다시 끌 수 있습니다.

카드에 **Starting**이 몇 초 넘게 계속 표시되면 접근성 설정에서 TapLock을 껐다가 다시 켜 보세요. Android 설정의 스위치가 회색으로 비활성화되어 있으면 **Lock setup**에서 **Switch greyed out?**을 누르고 안내를 따르세요.

## Device Admin lock 사용하기

1. **Lock setup**의 **Device Admin lock** 카드에서 **Enable Device Admin**을 누릅니다.
2. Android가 확인을 요청합니다. TapLock은 **Lock** 버튼을 눌렀을 때 화면을 잠그는 데에만 이 권한을 사용합니다.
3. 카드에 **On**이 표시됩니다.

![Accessibility lock 카드에는 On이 표시되고, Device Admin lock 카드에는 Enable Device Admin 버튼이 있는 Lock setup 화면](shots/02-setup.png)

이 방법으로 잠그면 다음에 잠금을 해제할 때 지문이나 얼굴 대신 Android가 PIN, 패턴 또는 비밀번호를 요구합니다. 두 방법이 모두 켜져 있으면 TapLock은 Accessibility lock을 사용합니다.

## 화면 잠그기

1. TapLock을 엽니다. 버튼 아래 문구가 "Ready."로 시작합니다.
2. **Lock**을 누릅니다. 화면이 바로 잠깁니다.
3. 평소처럼 휴대폰 잠금을 해제합니다.

![둥근 Lock 버튼과 "Ready. Fingerprint and face unlock stay on." 문구가 있는 홈 화면](shots/01-home.png)

## 다크 모드 사용하기

1. 휴대폰의 Android 설정에서 다크 테마를 켭니다.
2. TapLock을 엽니다. 앱이 휴대폰 설정을 따라 자동으로 다크 모드로 바뀝니다. 앱 안에는 별도 설정이 없습니다.

![다크 모드의 TapLock 홈 화면](shots/03-dark-mode.png)

## 언어 바꾸기

1. 홈 화면에서 설정 아이콘을 눌러 **Lock setup**을 엽니다.
2. 언어 선택 메뉴를 엽니다.
3. 31개 언어 중 하나를 고르세요. 시스템 기본값을 그대로 두면 TapLock이 휴대폰 언어를 따릅니다.

![언어 목록이 있는 언어 선택 화면](shots/06-language.png)

아랍어, 우르두어, 히브리어는 오른쪽에서 왼쪽으로 표시됩니다. Android 13 이상에서는 Android의 앱 언어 설정에서도 TapLock의 언어를 바꿀 수 있습니다.

## 잠금 방법 끄기 또는 앱 삭제하기

1. 홈 화면에서 설정 아이콘을 눌러 **Lock setup**을 엽니다.
2. Accessibility lock을 끄려면 **Manage in Accessibility settings**를 누르고 그곳에서 TapLock을 끕니다.
3. Device Admin lock을 끄려면 **Turn off Device Admin**을 누릅니다.
4. TapLock을 삭제하기 전에 먼저 Device Admin을 끄세요. Android는 기기 관리자로 활성화된 앱을 삭제하지 못하게 합니다.

![You're all set 카드와 Device Admin을 끄는 버튼이 있는 Lock setup 화면](shots/05-device-admin-on.png)

## 자주 묻는 질문

**TapLock은 왜 Accessibility 권한이 필요한가요?**
**Lock**을 눌렀을 때 전원 버튼처럼 화면을 잠그는 데에만 사용합니다. 화면을 읽거나 입력 내용을 보지 않습니다. 허용하고 싶지 않다면 Device Admin lock을 사용하세요.

**TapLock으로 잠근 뒤 지문 인식이 되지 않아요. 왜 그런가요?**
Device Admin lock을 사용 중이라서, Android가 한 번은 PIN, 패턴 또는 비밀번호를 요구합니다. 지문·얼굴 인식 잠금 해제를 계속 쓰려면 Accessibility lock을 켜세요.

**TapLock을 삭제할 수 없어요. 어떻게 하나요?**
**Lock setup**을 열고 **Turn off Device Admin**을 누른 다음 삭제하세요.

**어떤 Android 버전이 필요한가요?**
Accessibility lock은 Android 9 이상에서 사용할 수 있습니다. 더 낮은 버전에서는 Device Admin lock을 사용하세요.

**TapLock을 한국어로 쓸 수 있나요?**
TapLock은 31개 언어를 지원합니다. **Lock setup**에서 원하는 언어를 고르거나 시스템 기본값을 그대로 두세요.

## 개인정보 보호

TapLock은 Accessibility와 Device Admin 권한을 화면을 잠그는 데에만 사용하며, 이 권한으로 개인정보를 수집하지 않습니다. 앱에는 Google AdMob 광고가 표시됩니다. 필요한 지역에서는 **Lock setup**의 **Privacy settings**에서 광고 선택을 바꿀 수 있습니다. 전체 [개인정보 처리방침](https://varian1.github.io/LockAppOnlyWeb/privacy.html)을 확인하세요.
