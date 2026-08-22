<div align="center">
### 🌐 Languages / Langues / Idiomas / 语言 / لغات
[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • **[🇰🇷 한국어](../ko/README.md)** • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

</div>

---
# ARAS 번역 돕기

ARAS는 커뮤니티 구성원들의 자발적인 참여로 번역됩니다. 다른 언어를 구사할 수 있다면, 메뉴, 버튼, 알림 메시지가 더 많은 사람들에게 자연스럽고 편안하게 전달되도록 도울 수 있습니다.

프로그래밍 경험이나 특별한 소프트웨어, ARAS 소스 코드 접근 권한이 없어도 괜찮습니다. 웹 브라우저를 통해 GitHub에서 모든 작업을 바로 진행할 수 있습니다.

## 참여 방법

- 아직 목록에 없는 새로운 언어 추가하기
- 영문으로 남아 있는 텍스트 번역하기
- 맞춤법 및 문법 오류 수정하기
- 더 자연스러운 한국어 표현으로 다듬기
- 메뉴 및 메시지 간의 용어 일관성 개선하기
- 다른 기여자가 제출한 번역 검토하기

작은 기여라도 언제나 환영합니다. 한 번에 모든 텍스트를 번역할 필요는 없습니다.

## 기존 언어 편집하기

1. `.json` 파일 목록에서 언어를 찾습니다. 한국어는 `ko.json`입니다.
2. 파일을 열고 연필 모양의 **Edit this file** 버튼을 클릭합니다.
3. 오른쪽에 위치한 번역 텍스트만 수정합니다.
4. **Preview changes**를 클릭하여 변경 사항을 확인합니다.
5. **Propose changes**를 클릭하고 Pull Request(PR)를 생성합니다.

```json
"Cancel": "취소"
```

왼쪽의 `Cancel`은 원본 영어 텍스트입니다. 오른쪽의 `취소`는 한국어 번역입니다. 오른쪽만 수정해 주세요.

## 새로운 언어 요청하기

Issue를 열고 언어 이름, 지역, 자체 표기명 및 번역/검토 가능 여부를 알려주세요.

## 중요한 번역 지침

- 제품 이름인 `ARAS`는 변경하지 않고 그대로 유지합니다.
- Android, macOS, Mac, ProMotion, Adreno 등의 고유 명사는 원문 그대로 유지합니다.
- ADB, QEMU, QCOW2, DPI, FPS, GiB 등의 기술 약어는 번역하지 않습니다.
- 직역을 지양하고 한국어 화자에게 자연스러운 표현을 사용합니다.
- 메뉴와 버튼 레이블은 간결하게 작성합니다.
- ‘기기’, ‘설정’, ‘저장 공간’, ‘업데이트’ 등 자주 쓰이는 단어의 일관성을 유지합니다.
- 데이터 삭제 및 초기화 경고 문구는 명확하고 단호하게 표현합니다.
- `%@`, `%ld`, `%s`, `%.1f`, `\n` 같은 서식 지정자는 절대 수정하지 않습니다.
- 기계 번역은 초안으로만 활용하고 반드시 직접 검토합니다.
- 광고, 링크, 개인정보 등 불필요한 내용을 포함하지 않습니다.

`%@`, `%ld`, `%s`, `%.1f`, `\n` 등은 실행 시 자동으로 데이터로 치환됩니다.

자세한 가이드는 [번역 스타일 가이드](STYLE_GUIDE.md)를 참고하세요.

## 언어 파일 이름 규칙

파일명의 코드는 언어를 나타냅니다 (예: `ko.json` — 한국어).

## 검토 및 피드백

제출된 PR은 메인테이너와 커뮤니티 검토자가 확인합니다. [커뮤니티 행동 강령](CODE_OF_CONDUCT.md)이 적용됩니다.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## 커뮤니티 문서

- `README.md` — 시작 가이드 및 개요
- `CONTRIBUTING.md` — 기여 방법 안내
- `CODE_OF_CONDUCT.md` — 커뮤니티 행동 강령
- `STYLE_GUIDE.md` — 스타일 및 용어 가이드
- `REVIEW_CHECKLIST.md` — 검토 체크리스트
- `../../ko.json` — ARAS 한국어 번역 카탈로그

## 라이선스

번역 파일 및 문서는 [MIT 라이선스](../../LICENSE)에 따라 공유됩니다.
