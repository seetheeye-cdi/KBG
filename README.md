# KBG · 지금 대구에 필요한 사람

김부겸 전 국무총리 · 2026 대구시장 후보 공식 소개 단일 페이지.

## 기술 스택
- 단일 HTML · vanilla CSS · vanilla JS (빌드 도구 없음)
- Pretendard (jsDelivr) + DM Serif Display · Archivo Black · Cormorant Garamond · Space Grotesk (Google Fonts)
- 인터랙티브 대구 9개 구·군 지도 + 지역별 공약 도시에(dossier) 패널
- 반응형 · 접근성 WCAG AA · `prefers-reduced-motion` 대응

## 개발·배포
```bash
# 로컬 프리뷰
open index.html

# Vercel 배포
vercel --prod
```

## 구조
- `index.html` — 단일 페이지
- `kbg-portrait.jpg` — 후보 공식 초상
- `vercel.json` — 보안 헤더·캐싱 설정

## 콘텐츠 섹션
1. Hero — 지도 + 도시에 패널
2. Crisis — 대구의 현실 (31년 GRDP · 매일 13명 청년 유출 · 58% 고용률)
3. Story — 1977~2026년 마일스톤
4. Five Pillars — AX · 공공기관 이전 · 청년 일자리 10만 · 500만 메가시티 · 실행 증거
5. Voices — 증언 4건
6. Spring Dossier — 2026년 봄 활동 기록
7. Commitment — 서약
8. Contact — 010-3170-5521

## 라이선스 & 법적 고지
© 2026 Kim Bu-Gyeom for Daegu Mayor · 더불어민주당 공식 후보.
이 웹사이트는 공직선거법에 따라 선거운동 기간에 운영됩니다.
