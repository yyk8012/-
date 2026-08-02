# Changelog

본 문서는 `stock`(주식 분석 노트) 교재의 실질적 원고 변경 이력을 기록한다. 원칙: 실제 커밋된 원고에 대해서만 항목을 추가한다.

## [Unreleased]

### Changed
- 구조 개편: **Volume → Session 2단 구조**로 재배치. `Volume1~3` → `Session01~03`, 챕터 파일의 `Chapter` 접두어 제거(`01_...` 형식). 저장소 명칭을 `stock`으로 정리.
- 공통 구조 규칙 문서 `STRUCTURE.md` 추가 (모든 저장소 공통 2단 표준).

### Added
- Repository 스켈레톤 (README, CHANGELOG, Session01–03)
- Session01 "밸류에이션" — 7개 파일 초고 (9개 절 전체)
  - 01_EPS / 02_ForwardEPS / 03_PER / 04_ForwardPER_TargetPER / 05_PBR / 06_ROE / 07_DuPont
- Session02 "밸류에이션 심화" — 4개 파일 초고 (9개 절 전체)
  - 01_PEG / 02_EV_EBITDA / 03_DCF / 04_TargetPrice
- Session03 "시장 구조" — 4개 파일 초고 (9개 절 전체)
  - 01_ETF_Passive / 02_Passive_vs_Active / 03_Foreign_Flows / 04_SupplyDemand
