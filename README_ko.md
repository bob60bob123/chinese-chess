# 초한쟁웅 - 중국 장기

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="버전">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="라이선스">
  <img src="https://img.shields.io/badge/HTML5-Game-orange.svg" alt="HTML5">
</p>

**초한쟁웅** 은 순수 HTML5로 구현된 중국 장기 게임입니다. 외부 의존성 없이 브라우저에서 바로 플레이할 수 있습니다. 사람 대 사람 모드와 사람 대 AI 모드를 지원합니다.

[English](README.md) | [简体中文](README_zh-CN.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md)

---

## 기능

### 장기 규칙
- ✅ 완전한 중국 장기 규칙 구현
- ✅ 7가지 말: 수/장, 사/사, 상/앙, 차/치, 마, 포/포, 병/졸
- ✅ 다리치기, 눈塞기 규칙
- ✅ 장수 대면 규칙
- ✅ 장군, 장마, 동귀 상태 판정

### 게임 모드
- 🔹 **사람 대 사람** -两人对战
- 🔹 **사람 대 AI** - AI와对战, 세 가지 난이도

### AI 난이도
| 난이도 | 설명 |
|--------|------|
| 입문 | 초보자向け, AI 실수 가능 |
| 중급 | 기본적인 공수 의식 |
| 상급 | 배치와 전술에 뛰어나 |

### 추가 기능
- 🎵 말 움직임 소리, 잡기 소리, 장군 알림음
- 📜 기보 기록
- ↩️ 뒤로 되기 기능
- 🔄重新 시작

---

## 플레이 방법

### 방법 1: 직접 열기
`index.html` 파일을 더블클릭하여任意の 모던 브라우저에서 열기

### 방법 2: 로컬 서버
```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .

# PHP
php -S localhost:8080
```
`http://localhost:8080` 에アクセス

---

## 기술 스택

| 기술 | 설명 |
|------|------|
| HTML5 | 시맨틱 구조 |
| CSS3 | 보드 스타일, 애니메이션 |
| JavaScript | 게임 로직, AI, 인터랙션 |

- **零의존** - 순수 네이티브 구현
- **반응형** - 데스크톱 및 모바일 지원
- **접근성** - ARIA 레이블 지원

---

## 브라우저 호환성

| 브라우저 | 지원 버전 |
|----------|----------|
| Chrome | 80+ |
| Firefox | 75+ |
| Safari | 13+ |
| Edge | 80+ |

---

## 프로젝트 구조

```
chinese-chess/
├── index.html        # 메인 페이지 (모든 코드 포함)
├── SPEC.md          # 프로젝트 사양
├── README.md         # 영어
├── README_zh-CN.md   # 간체자 중국어
├── README_ja.md      # 일본어
├── README_ko.md      # 한국어
├── README_es.md      # 스페인어
├── LICENSE           # MIT 라이선스
└── .gitignore        # Git 무시 파일
```

---

## 개발

### 테스트 실행
브라우저 콘솔에서：
```javascript
runSelfTests()
```

---

## 라이선스

MIT 라이선스采用（[LICENSE](LICENSE)）。