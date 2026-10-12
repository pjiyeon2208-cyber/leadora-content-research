# LEADORA · 우주선가 콘텐츠 연구 저장소

## 저장소 목적

이 저장소는 LEADORA와 우주선가의

- 콘텐츠 전략
- SEO 분석
- 검색 유입 진단
- 원천 콘텐츠 설계
- 콘텐츠 맵
- 유튜브 확장
- 두 축의 연결 구조

를 관리하기 위한 **연구·문서 전용 저장소**입니다.

이 저장소는 실제 서비스 개발 저장소가 아닙니다. 여기에는 문서(Markdown)와 분석용 데이터(CSV 등)만 보관합니다.

## 하지 않는 일

다음은 이 저장소에서 하지 않습니다.

- LEADORA 앱 개발
- Founder Test 개발
- 양영 완공데이 개발
- Vercel 배포
- Supabase 변경
- Blogger 코드 수정
- 네이버 블로그 자동 게시
- 실제 운영 서비스 코드 수정

또한 패키지 설치, `package.json`, 빌드 시스템, API 키·환경변수 등 개발/운영 설정을 이 저장소에 만들지 않습니다.

## 브랜드 역할

LEADORA는 전체 사업 및 교육 브랜드이며, 우주선가는 LEADORA 사업의 주요 상품/콘텐츠 축 중 하나입니다.
두 축은 분리된 브랜드가 아니라 **서로 다른 역할을 가진 LEADORA 사업의 주요 축**입니다.

| 축 | 역할 |
| --- | --- |
| **우주선가** | 알아차림, 수행, 내면 관찰, 깊은 자기이해 |
| **LEADORA** | 선택, 행동, 현실 적용, 자기주도권 |

**공통 연결축**

> “알아차림은 자기 자신을 함부로 다루지 않는 연습이기도 합니다.”

**LEADORA 핵심 철학**

> “세상이 나를 함부로 대하더라도,
> 나까지 나를 함부로 대하지 않는 법.”

**LEADORA 방법론**: AWARE → ENVISION → ACT → BLOOM

- LEADORA 주요 주제: 자기이해, 자기주도권, 선택, 행동, 감정, 관계, 경계, 직장 문제, 평가와 인정, 행동 변화, AI 시대의 셀프리더십
- 우주선가 주요 주제: 명상, 수행, 알아차림, 송과체, 위빠사나, 몸과 마음 관찰, 직관과 분별, 차크라, 정기신, 자비심, 수행을 통한 깊은 자기이해

## 현재 운영 원칙

- 우주선가 11월까지 기존 발행기획 유지 (재설계하지 않음 — 실행, 품질관리, 구조화, 영상 재활용 우선)
- LEADORA는 기존 발행글/예약글 분석 후 다음 원천 콘텐츠 선정
- 원천 콘텐츠를 먼저 만들고 유튜브로 확장
- 새 글 수보다 장기 자산 가치 우선
- 실제 검색 데이터가 있으면 데이터 기반으로 판단
- 추정과 사실을 구분
- 콘텐츠 중복 최소화

## 데이터 입력 원칙

앞으로 Google Search Console CSV, 기존 글 목록, 예약발행 목록, SEO 보고서, 유튜브 기획 등이 추가됩니다. 데이터를 다루는 모든 문서는 다음을 지킵니다.

- **사실**(데이터로 확인된 내용)과 **추정**(해석·가설)을 명확히 구분해 표기합니다.
- 확인되지 않은 내용은 **“미확인”** 또는 **“데이터 부족”**으로 표시합니다.
- 확인되지 않은 콘텐츠 제목·수치를 임의로 만들지 않습니다.
- 원본 데이터 파일에는 출처와 추출 기간을 함께 기록합니다(예: `leadora/search-console/2026-10_gsc-queries.csv` + 간단한 메모).

## 폴더 구조

```
/
├─ README.md
├─ leadora/                 LEADORA Blogger 콘텐츠
│  ├─ published-content/    기존 발행글 목록
│  ├─ scheduled-content/    예약발행글 목록
│  ├─ search-console/       Google Search Console 원본 데이터(CSV 등)
│  ├─ seo-reports/          SEO 진단 보고서
│  ├─ content-map/          LEADORA 콘텐츠 맵
│  ├─ source-content/       LEADORA 원천 콘텐츠 기획
│  └─ youtube/              LEADORA 유튜브 전환 기획
├─ ujusunga/                우주선가 네이버 블로그 콘텐츠
│  ├─ published-content/    기존 발행글 목록
│  ├─ scheduled-content/    예약발행글 목록
│  ├─ content-map/          우주선가 콘텐츠 맵
│  ├─ source-content/       우주선가 원천 콘텐츠 기획
│  ├─ publishing-plan/      확정된 발행 기획(11월까지 유지)
│  └─ youtube/              우주선가 유튜브 전환 기획
├─ shared/                  두 축 공통
│  ├─ brand-bridge/         우주선가 ↔ LEADORA 연결 구조, 브리지 콘텐츠
│  ├─ content-strategy/     전략 기준 문서, 전체 콘텐츠 맵 현황
│  ├─ youtube-strategy/     유튜브 채널·확장 전략
│  └─ decision-log/         콘텐츠 의사결정 기록
└─ templates/               반복 작성용 템플릿
   ├─ seo-diagnosis-template.md
   ├─ content-map-template.md
   ├─ source-content-template.md
   └─ youtube-conversion-template.md
```

## 시작점

- 전략 기준: [`shared/content-strategy/CONTENT_STRATEGY_FOUNDATION.md`](shared/content-strategy/CONTENT_STRATEGY_FOUNDATION.md)
- 콘텐츠 현황: [`shared/content-strategy/CONTENT_MAP_STATUS.md`](shared/content-strategy/CONTENT_MAP_STATUS.md)
- 템플릿: [`templates/`](templates/)
