# stock — 주식 분석 노트

기관투자자 수준의 주식 분석 교재.

## 목표
단순 개념 설명이 아니라, 셀사이드·바이사이드 애널리스트가 실제로 사용하는 프레임과 사고체계를 원고 형태로 정리한다. 최종 목표 분량은 200–500페이지 이상.

## 구조 원칙 (2단)
폴더 계층은 **2단까지만** 둔다. 자세한 규칙은 [`STRUCTURE.md`](STRUCTURE.md) 참고.

```
stock/                    ← repo (대분류)
├─ SessionNN_주제/         ← 중분류 (하나의 학습 세션)
│   ├─ 01_....md          ← 콘텐츠 파일 (더 이상 폴더로 나누지 않음)
│   └─ ...
```

- **repo = 대분류(category)** : 이 저장소(`stock`)가 곧 하나의 과목이다.
- **Session = 중분류** : 한 덩어리로 학습·집필하는 단위. 폴더로 표현한다.
- **콘텐츠 파일** : 세션 폴더 안의 `.md`. 계층을 더 늘리지 않는다.

## Session 구성

| Session | 주제 | 핵심 파일 |
| --- | --- | --- |
| Session01 | 밸류에이션 (Valuation & Earnings) | EPS / Forward EPS / PER / Forward PER / PBR / ROE / DuPont |
| Session02 | 밸류에이션 심화 | PEG / EV·EBITDA / DCF / Target Price |
| Session03 | 시장 구조 (Market Structure) | ETF·패시브 / 패시브 vs 액티브 / 외국인 / 수급 |
| Session04 | 매크로 (예정) | 금리 / 환율 / 경기 / 유동성 |
| Session05 | 케이스 스터디 (예정) | 삼성전자 / SK하이닉스 / NVIDIA / TSMC 등 |

## 콘텐츠 파일 구성 (공통 9절)
1. 개념
2. 회계 연결
3. 시장 메커니즘
4. 기관 사고방식
5. 실제 사례
6. 계산 예시
7. 실전 적용
8. 체크리스트
9. 요약

## 원칙
- Markdown이 Source of Truth. PDF/DOCX는 파생물.
- 파일 단위 집필, 완성된 원고만 커밋한다.
- 미완성분을 완료로 표기하지 않는다.
- 참고 기준: IFRS, CFA Institute Curriculum, KRX, FnGuide, 기업 공시, 공개 가능한 컨센서스 자료.

## 진행 상태
- [x] Repo 스켈레톤
- [x] Session01 밸류에이션 — 7개 파일 초고 (EPS / Forward EPS / PER / Forward PER & Target PER / PBR / ROE / DuPont)
- [x] Session02 밸류에이션 심화 — 4개 파일 초고 (PEG / EV·EBITDA / DCF / Target Price)
- [x] Session03 시장 구조 — 4개 파일 초고 (ETF·패시브 / 패시브 vs 액티브 / 외국인 / 수급)
- [ ] Session04 매크로
- [ ] Session05 케이스 스터디
