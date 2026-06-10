# 임다은 | AI & Development Portfolio

> 웹프로그래밍 학기말 개인프로젝트 — 노코드 + 바이브코딩 + 반응형 웹

🔗 **배포 URL:** `https://<깃허브아이디>.github.io/<저장소이름>/` ← 배포 후 수정

---

## 📌 프로젝트 소개

생성형 AI와 LLM 서비스에 관심을 가진 가천대학교 영미어문학 / 소프트웨어 복수전공 학생의 개인 포트폴리오 웹사이트입니다.
Claude AI와의 대화(바이브코딩)를 통해 구현하고, 직접 검증·수정하며 완성했습니다.

---

## 🗂️ 파일 구조

```
📁 portfolio/
├── index.html          # 전체 포트폴리오 (HTML + CSS + JS 단일 파일)
├── README.md           # 프로젝트 설명
└── images/             # 이미지 폴더
    └──image.jpg     # About 섹션 사진
```

---

## ⚡ JavaScript 기능

### 1. 프로젝트 필터 + 검색
- 카테고리 버튼(All / AI / Web / Content)으로 필터링
- 텍스트 검색과 카테고리 필터 동시 적용 (`applyFilter()` 함수)
- 결과 없을 때 안내 메시지 표시

### 2. 다크모드 토글
- 버튼 클릭으로 라이트 ↔ 다크 전환
- `localStorage`에 설정 저장 → 다음 방문 시 유지

### 3. Contact 폼 검증
- 이름 공백 체크
- 이메일 정규식 검증 (`/^[^\s@]+@[^\s@]+\.[^\s@]+$/`)
- 메시지 공백 체크
- 오류 시 빨간 테두리 + 안내 메시지, 성공 시 완료 화면 전환

---

## 📱 반응형 브레이크포인트

```css
@media (max-width: 1024px) { /* 태블릿 — 2컬럼 → 1컬럼 */ }
@media (max-width: 768px)  { /* 모바일 — 햄버거 메뉴, 패딩 축소 */ }
@media (max-width: 480px)  { /* 소형 모바일 — 1컬럼 강제 */ }
```

---

## 🛠️ 사용 기술

| 분류 | 내용 |
|------|------|
| HTML / CSS / JS | 단일 파일 (`index.html`) — 외부 라이브러리 없음 |
| 폰트 | Playfair Display + Outfit (Google Fonts, SIL OFL) |
| 이미지 | 직접 촬영 / Unsplash (CC0) |
| AI 도구 | Claude (Anthropic) — 바이브코딩 보조 |
| 배포 | GitHub Pages |

---

## 🤖 노코드 & 바이브코딩 활용

### 노코드 (옵션 A — 프로토타입/레이아웃 설계)
- **도구:** Claude AI (대화형 AI 설계 보조)
- **활용 내용:** 섹션 구성, 컬럼 레이아웃 방향, 색상 팔레트 설계
- **최종 결과물:** 직접 작성한 HTML / CSS / JS 포함

### 바이브코딩
- Claude AI와 대화하며 코드 뼈대를 받고, 실행 → 테스트 → 수정 → 개선 반복
- 프롬프트 12개, 수정 사례 3개, 오류 해결 1개 → 프롬프트 로그 파일 참조

---

## 📜 출처 & 라이선스

| 리소스 | 출처 | 라이선스 |
|--------|------|----------|
| Playfair Display 폰트 | Google Fonts | SIL Open Font License (OFL) |
| Outfit 폰트 | Google Fonts | SIL Open Font License (OFL) |
| 프로필 사진 | 직접 촬영 | 자체 보유 |
| 기타 이미지 | Unsplash | Unsplash License (CC0) |
| 이모지 | Unicode / OS | 퍼블릭 도메인 |

---

## 👩‍💻 제작자

**임다은** · 가천대학교 영미어문학 / 소프트웨어 복수전공  
© 2026 Daeun Lim