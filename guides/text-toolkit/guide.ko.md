---
title: 글자수 세기 - Text Toolkit
name: Text Toolkit
tagline: 단어 수 세기, 대소문자 변환, 정리, 정렬, 비교를 인터넷 없이 휴대폰에서 한 번에.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## 주요 기능

Text Toolkit은 텍스트 도구 아홉 가지를 한 화면에 모아 둔 앱입니다. 맨 위 입력창에 글을 입력하거나 붙여넣고, 도구를 고른 다음, 결과를 복사하거나 공유하세요. 단어 수 세기, 대소문자 변경, 공백 정리, 줄 정렬, 찾아 바꾸기, 뒤집기, 인코딩, JSON 정리, 두 텍스트 비교를 할 수 있습니다.

- 모든 도구가 기기에서 실행되며 인터넷 없이 작동합니다.
- 계정이 필요 없습니다. 입력한 글은 업로드되지 않고, 앱은 카메라, 사진, 연락처, 위치를 사용하지 않습니다.
- 입력한 글은 저장되지 않습니다. 앱을 닫으면 사라집니다.
- 무료입니다. 화면 아래에 배너 광고가 나올 수 있습니다.

## 시작하기

1. Text Toolkit을 엽니다. **YOUR TEXT** 입력창에 짧은 예시 문장이 들어 있어 각 도구를 바로 써 볼 수 있습니다.
2. **Clear**를 눌러 내용을 지우고 직접 입력하거나, **Paste**를 눌러 다른 앱에서 복사한 글로 바꾸세요. **Sample**을 누르면 예시 문장이 다시 들어갑니다.
3. 입력창 아래 줄에서 도구를 고릅니다: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format**, **Diff**. 줄을 옆으로 밀면 전체 도구를 볼 수 있습니다.

![메인 화면: Paste, Sample, Clear가 있는 YOUR TEXT 입력창, 도구 목록, Counter 수치](shots/01-home.png)

앱은 휴대폰의 언어 설정을 따릅니다. 영어, 스페인어, 포르투갈어, 독일어, 프랑스어, 힌디어, 인도네시아어, 아랍어, 이탈리아어, 러시아어, 터키어의 11개 언어로 제공됩니다.

## 단어 수와 글자 수 세기

1. **Counter**를 누릅니다.
2. 수치를 확인하세요: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines**, **Reading time**.
3. 아래 **TOP WORDS**에서 가장 많이 쓴 단어를 최대 여덟 개까지, 횟수와 함께 볼 수 있습니다.

글을 입력하는 대로 수치가 바뀝니다. 읽는 시간은 1분에 200단어를 기준으로 계산합니다.

## 대소문자 바꾸기

1. **Case**를 누릅니다.
2. 카드를 넘겨 보세요. 카드마다 입력한 글이 다른 형식으로 나옵니다: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE**, **URL slug**.
3. 원하는 카드의 **Copy**를 누릅니다.

![Case 도구: UPPERCASE, lowercase, Title Case 카드와 각 카드의 Use input, Share, Copy 버튼](shots/02-case.png)

## 텍스트 정리하기

1. **Clean**을 누릅니다.
2. 동작 하나를 누릅니다:
   - **Clean all**: 탭, 반복된 공백, 줄 끝 공백, 빈 줄, 중복된 줄을 한 번에 지웁니다.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates**, **Remove tabs**: 해당하는 한 가지만 처리합니다.
   - 줄바꿈 제거 버튼: 글에서 줄바꿈을 없앱니다.
3. **CLEANED RESULT** 아래에서 결과를 확인하세요. 입력창의 원래 글은 그대로 남습니다.

![Clean 도구: 정리 버튼들과 CLEANED RESULT 카드](shots/03-clean.png)

## 정렬하거나 뒤집기

1. 줄 단위로 작업하려면 **Lines**를 누릅니다: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates**, **Reverse characters**. 정렬할 때 대소문자와 줄 앞의 공백은 무시합니다.
2. 텍스트를 뒤집으려면 **Reverse**를 누릅니다: **Entire text**, **Each word**, **Word order**, **Line order**, **Characters per line**.
3. 결과는 버튼 아래 카드에 나타납니다.

## 찾아 바꾸기

1. **Replace**를 누릅니다.
2. **Find**에 찾을 글을, **Replace with**에 바꿀 글을 입력합니다.
3. 옵션을 눌러 켜거나 끕니다: **Replace all**(끄면 처음 일치하는 한 곳만 바뀝니다), **Case sensitive**, **Whole word**.
4. 바뀐 횟수와 **REPLACEMENT PREVIEW**를 확인하세요. 입력하는 대로 함께 바뀝니다.

![Replace 도구: Find와 Replace with 입력란, 옵션 버튼 세 개, 바뀐 횟수와 미리보기](shots/04-replace.png)

검색은 입력한 글자 그대로 찾습니다. 패턴이나 와일드카드는 쓸 수 없습니다.

## 인코딩, 디코딩, 형식 정리

1. **Encode**를 누르고 **URL**, **Base64**, **HTML Entities** 중 하나를 고른 다음 **Encode** 또는 **Decode**를 누릅니다.
2. **Format**을 누르고 **Format JSON**을 고르면 JSON이 공백 두 칸으로 들여쓰기됩니다. **Minify JSON**은 JSON을 한 줄로 만들고, **Strip Markdown**은 Markdown을 일반 텍스트로 바꿉니다.
3. JSON에 오류가 있으면 화면 위쪽에 "Invalid JSON"으로 시작하는 줄이 나타나 무엇이 잘못됐는지 알려 줍니다.

## 두 텍스트 비교하기

1. 첫 번째 글을 **YOUR TEXT**에 넣고 **Diff**를 누릅니다.
2. 두 번째 글을 **COMPARE WITH**에 입력하거나 붙여넣습니다.
3. **DIFF COMPARISON**을 확인하세요. 두 번째 글에만 있는 줄은 초록색에 **+** 표시가 붙습니다. 첫 번째 글에만 있는 줄은 빨간색에 **-** 표시가 붙습니다. 같은 줄에는 표시가 없습니다.
4. **Copy Diff**를 누르면 + 와 - 표시가 포함된 비교 결과가 복사됩니다.

![Diff 도구: COMPARE WITH 입력창과 추가된 초록색 줄 하나, 삭제된 빨간색 줄 하나가 보이는 DIFF COMPARISON 카드](shots/05-diff.png)

## 복사, 공유, 이어서 작업하기

1. 결과 카드의 **Copy**를 누르면 클립보드에 복사됩니다.
2. **Share**를 누르면 다른 앱으로 보낼 수 있습니다.
3. **Use input**을 누르면 결과가 **YOUR TEXT**로 옮겨져 다른 도구를 이어서 쓸 수 있습니다.

## 프리미엄

모든 도구는 무료입니다. 광고를 없애는 선택형 일회성 구매가 하나 있습니다. 한 번만 결제하며 구독이 아닙니다.

## 질문과 답변

**인터넷 없이도 작동하나요?**
네. 아홉 가지 도구 모두 휴대폰에서 실행됩니다. 광고와 광고 제거 구매에만 네트워크 연결이 필요합니다.

**입력한 글이 저장되나요?**
아니요. 앱이 열려 있는 동안에만 글을 보관합니다. 남기고 싶은 결과는 복사하거나 공유하세요.

**도구를 바꿨더니 결과가 비어 있어요. 왜 그런가요?**
Clean, Lines, Reverse, Encode, Format은 결과 카드 하나를 함께 쓰며, 도구를 바꾸면 카드가 비워집니다. 동작 버튼을 다시 누르세요. 글을 수정한 뒤에도 마찬가지입니다. Counter, Case, Replace, Diff는 자동으로 갱신됩니다.

**다크 모드를 지원하나요?**
네. 휴대폰에 설정된 밝은 테마 또는 어두운 테마를 따릅니다.

**라이선스는 어디서 볼 수 있나요?**
화면 맨 아래로 스크롤해서 **Open-source licenses**를 누르세요. 바로 옆에 **Privacy policy**가 있습니다.

## 개인정보 보호

입력한 글은 휴대폰에서만 처리되며 업로드되거나 저장되지 않습니다. 앱에 Google AdMob 광고가 표시될 수 있습니다. 법에서 요구하는 경우 먼저 선택을 묻고, 메인 화면의 **Ad privacy choices**에서 선택을 바꿀 수 있습니다. 전체 내용은 [개인정보 처리방침](https://varian1.github.io/text-toolkit/privacy.html)에서 확인하세요.
