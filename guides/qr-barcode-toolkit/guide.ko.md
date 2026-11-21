---
title: QR 코드 스캐너 & 바코드 생성
name: QR & Barcode Toolkit
tagline: QR 코드와 바코드를 스캔하고 만들어요. 기기 안에서 처리하고 기록 저장과 내보내기도 지원해요.
project: QRBarcode and toolkit
package: com.varian1.qrtoolkit
version: 1.0.0
updated: 2026-11-21
privacy: https://varian1.github.io/qr-barcode-toolkit/privacy.html
---

## 기능 소개

QR & Barcode Toolkit은 카메라나 사진으로 QR 코드와 바코드를 스캔하고, 열기 전에 안에 든 내용을 먼저 보여 줍니다. QR 코드와 바코드를 직접 만들어 이미지로 저장하거나 공유할 수도 있어요. 앱은 21개 언어를 지원하며 휴대폰 언어를 따라갑니다.

- 코드는 기기에서 읽습니다. 링크는 저절로 열리지 않아요.
- 계정이 필요 없고, 기록은 내 휴대폰에만 남아요.
- QR 코드와 12가지 바코드 종류(EAN-13, UPC-A, Code 128 등)를 읽어요.
- 광고가 있는 무료 앱이에요. 한 번 결제하는 Premium으로 광고를 없애고 스타일 옵션을 더 쓸 수 있어요.

## 시작하기

1. QR & Barcode Toolkit을 엽니다. **Home**에 **Scan QR**, **Scan Barcode**, **Create QR**, **Create Barcode** 바로가기 네 개가 있어요.
2. **Scan QR**을 누릅니다. 처음에는 **Allow camera**를 누르고, Android가 물으면 카메라를 허용하세요.
3. 카메라를 쓰고 싶지 않다면 **Scan from an image instead**를 누르고 사진을 고르세요. 사진 보관함 전체에 접근할 필요는 없어요.

![Scan QR, Scan Barcode, Create QR, Create Barcode 바로가기와 Recent activity가 보이는 Home 화면](shots/01-home.png)

## 코드 스캔하기

1. 아래쪽의 **Scan**을 누르거나 **Home**의 스캔 바로가기를 누릅니다.
2. 위쪽에서 **QR Code** 또는 **Barcode**를 고릅니다.
3. 카메라를 코드에 맞춥니다. 바코드는 프레임 안에 들어오게 하세요.
4. 어두운 곳에서는 손전등 버튼을 누릅니다. 사진에서 코드를 읽으려면 사진 버튼을 누르고 사진을 고르세요.
5. 코드를 읽으면 **Scan Result**가 열립니다. **Website**, **Wi-Fi**, **Contact**, **Product** 같은 내용 종류가 표시돼요.
6. **Copy content** 또는 **Share as text**를 누르거나, **Scan another**를 눌러 카메라로 돌아갑니다.

![QR Code와 Barcode 전환 버튼, 프레임, 사진 버튼, 손전등 버튼이 있는 스캐너 화면](shots/06-scan.png)

## 링크를 열기 전에 확인하기

1. 웹 주소가 담긴 코드를 스캔합니다. 결과에 사이트 이름과 전체 주소가 나옵니다.
2. 경고가 있으면 읽어 보세요. 암호화되지 않은(http) 링크, 단축 링크, IP 주소 그대로인 링크, 숨겨진 로그인 정보, 비슷하게 생긴 문자를 쓴 링크에 대해 경고해 줍니다.
3. 믿을 수 있는 사이트일 때만 **Open link**를 누르고, 확인 창에서 **Open**을 누르세요.

![웹사이트 Scan Result: Open link 버튼 위에 경고 두 개가 보이는 화면](shots/03-link.png)

다른 종류의 코드에는 각각 맞는 버튼이 나옵니다. **Compose email**, **Call**, **Send message**, **Open in Maps**, **Search the web**이 있어요. 어느 버튼이든 앱을 벗어나기 전에 먼저 물어봅니다.

## Wi-Fi 코드 읽기

1. Wi-Fi QR 코드를 스캔합니다. 결과에 **Network**, **Security**, **Password**가 표시됩니다.
2. 눈 모양 아이콘을 눌러 비밀번호를 표시합니다.
3. 비밀번호 옆의 복사 아이콘을 누릅니다.
4. 휴대폰의 Wi-Fi 설정을 열고, 복사한 비밀번호로 네트워크에 연결하세요. 앱이 대신 연결해 주지는 않아요.

![네트워크 이름, 보안 종류, 가려진 비밀번호가 보이는 Wi-Fi 코드의 Scan Result 화면](shots/02-wifi.png)

## QR 코드 만들기

1. **Create**를 누르고 **QR Code**를 고릅니다.
2. **Content type**에서 **Website**, **Text**, **Wi-Fi**, **Email**, **Phone**, **SMS**, **Contact**, **Location** 중 하나를 고릅니다.
3. 항목을 입력합니다. 내용이 올바르면 바로 QR 코드가 나타나요. 기록에서 부를 이름을 정하고 싶다면 **Title (optional)**을 입력하세요.
4. **Style**에서 템플릿 **Classic**, **Indigo**, **Forest** 중 하나를 고릅니다. **Foreground**와 **Background** 색, **Error correction** 단계도 바꿀 수 있어요.
5. 보관하려면 **Save to history**, 이미지를 보내려면 **Share**, 갤러리에 넣으려면 **Save image**를 누릅니다.

![Indigo 템플릿의 QR 코드와 그 아래 Style 템플릿, 색상이 보이는 Create 화면](shots/04-create.png)

자물쇠가 있는 옵션은 Premium에 포함돼요.

## 바코드 만들기

1. **Create**를 누르고 **Barcode**를 고릅니다.
2. **Format**에서 **EAN-13**, **EAN-8**, **UPC-A**, **Code 128**, **Code 39**, **ITF-14** 중 하나를 고릅니다.
3. **Value**를 입력합니다. 입력란 아래 문구에 그 형식이 받는 값이 안내돼요. 상품 코드는 체크 숫자를 빼고 입력해도 앱이 붙여 줍니다.
4. 이름을 정하고 싶다면 **Title (optional)**을 입력합니다.
5. **Save to history**, **Share**, **Save image** 중 하나를 누릅니다.

![값, 바코드 미리보기, 자동으로 붙은 체크 숫자가 보이는 EAN-13 바코드 Create 화면](shots/05-barcode.png)

## 코드 찾기, 다시 쓰기, 삭제하기

1. **History**를 누릅니다. 스캔한 코드와 만든 코드가 목록으로 나와요.
2. **Search**에 입력하거나 **All**, **Scanned**, **Created**, **Favorites**, **Any type**, **QR**, **Barcode** 필터를 사용하세요.
3. 목록에서 별을 누르면 즐겨찾기에 추가됩니다.
4. 항목을 누르면 **Details**가 열립니다. 여기서 **Copy content**, **Share as text**, **Delete**를 누를 수 있어요. QR 코드와 앱에서 만들 수 있는 바코드 형식은 코드 이미지도 함께 보이고 **Share image**, **Edit / reuse**도 쓸 수 있습니다.
5. 목록을 비우려면 위쪽의 휴지통 아이콘을 누른 뒤 **Clear**를 누르세요. 즐겨찾기는 남습니다.

![검색창, 필터, 스캔한 코드와 만든 코드 목록이 보이는 History 화면](shots/07-history.png)

## 설정 바꾸기

1. **Settings**를 누릅니다.
2. 스캔 기록을 남기고 싶지 않다면 **Save scans to history**를 끕니다.
3. **Haptic feedback**을 켜거나 끕니다.
4. Wi-Fi 비밀번호를 저장하고 싶을 때만 **Keep Wi-Fi passwords in history**를 켜세요. 기본값은 꺼짐이에요.
5. **Language**를 눌러 앱 언어를 고릅니다. 기본적으로 앱은 휴대폰 언어를 따라갑니다.
6. 즐겨찾기를 포함해 모든 스캔과 만든 코드를 지우려면 **Clear all history**를 누른 뒤 **Delete all**을 누릅니다.

![Preferences, Privacy, About 섹션이 보이는 Settings 화면](shots/08-settings.png)

## Premium

Premium은 구독이 아니라 한 번만 결제하는 방식이에요. **Settings**를 열고 **Go Premium**을 누르거나, **Home**에서 **See plans**를 누르세요. Premium으로 다음을 쓸 수 있어요.

- 광고 없음
- 원하는 색, 프리미엄 템플릿, QR 코드 속 로고
- 무제한 기록과 즐겨찾기
- 1024px, 2048px 크기로 내보내기

Premium이 없을 때 잠긴 템플릿, 색, **Add logo**를 누르면 **Watch an ad**가 나올 수 있어요. 광고를 보면 앱을 닫을 때까지 이 스타일 옵션을 쓸 수 있습니다. 전에 Premium을 구매했다면 **Settings**에서 **Restore purchases**를 누르세요.

## 자주 묻는 질문

**앱이 링크를 저절로 열기도 하나요?**
아니요. 먼저 주소와 경고를 보여 줍니다. **Open link**를 누르고 확인한 뒤에만 링크가 열려요.

**어떤 코드를 읽을 수 있나요?**
QR, EAN-13, EAN-8, UPC-A, UPC-E, Code 128, Code 39, Code 93, Codabar, ITF-14, PDF417, Data Matrix, Aztec을 읽을 수 있어요.

**기록에 Wi-Fi 비밀번호가 없는 이유가 뭔가요?**
Wi-Fi 비밀번호는 코드를 저장하기 전에 지워집니다. 비밀번호를 남기려면 코드를 스캔하거나 만들기 전에 **Settings**에서 **Keep Wi-Fi passwords in history**를 켜세요.

**코드는 몇 개까지 저장되나요?**
무료 버전은 최근 스캔 100개와 만든 코드 100개, 즐겨찾기 최대 10개를 보관해요. 무료 목록이 가득 차면 **History**에서 알려 주고, 새 항목이 가장 오래된 항목을 대신합니다. 즐겨찾기는 목록이 가득 차도 지워지지 않아요. Premium은 제한이 없습니다.

**다크 모드가 있나요?**
네. 앱은 휴대폰의 밝은 테마 또는 어두운 테마를 따라갑니다.

## 개인정보

코드는 기기에서 읽고, 기록은 내 휴대폰에만 남아요. 무료 버전에는 Google AdMob 광고가 표시됩니다. 자세한 내용은 [개인정보 처리방침](https://varian1.github.io/qr-barcode-toolkit/privacy.html)에서 확인하세요.
