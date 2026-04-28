# AGENT.md

## 프로젝트 목적

이 저장소는 금융공학 및 금융 데이터 기반 커리어를 위한 포트폴리오 허브(repository) 입니다.

이 레포지토리는 개별 프로젝트의 전체 소스코드를 직접 저장하는 공간이 아니라, 다음 역할을 수행합니다.

* 나의 전문 분야와 연구 방향을 구조적으로 소개
* 프로젝트 카테고리별 안내 페이지 제공
* 향후 생성될 개별 프로젝트 repository 연결
* Notion 연구 노트 연결
* 발표 자료(PPT/PDF) 연결
* GitHub Pages 기반 웹 포트폴리오 확장 기반 마련

즉, 이 저장소는 **포트폴리오의 중심 Index 역할**을 수행합니다.

---

## 현재 사용자 배경

KAIST-DFMBA Repository에 현재 다음과 같은 상태의 자료가 존재합니다.

* 대학원 과목별 폴더 구성
* 과목별 과제, 프로젝트, 코드, 실습 자료가 분산 저장
* Notion에 강의 수강 내용 및 일부 프로젝트 정리 페이지 존재
* 자료량은 충분하지만, 대외 PR 가능한 프로젝트 단위로 재구성되지 않은 상태

현재 단계의 목표는:

* 기존 자료를 직접 재검토
* 의미 있는 프로젝트 후보 선정
* 프로젝트 단위로 재구성
* GitHub + Notion + Web Portfolio 형태로 연결

---

## 포트폴리오 핵심 카테고리

향후 모든 프로젝트는 아래 7개 카테고리 중 하나에 배치합니다.

### 1. Stochastic Models & Market Risk

대상 repository:

* covariance-risk-decomposition
* market-risk-var-backtesting
* monte-carlo-simulation
* stock-price-path-simulation
* interest-rate-prediction-model

### 2. Derivatives Pricing & Volatility

대상 repository:

* black-scholes-model
* option-pricing
* greek-risk-analysis
* implied-volatility-analysis

### 3. Portfolio Optimization & Allocation

대상 repository:

* optimal-portfolio
* portfolio-rebalancing-strategy

### 4. Factor Investing

대상 repository:

* multi-factor-portfolio
* betting-against-beta-portfolio

### 5. Dynamic Portfolio Insurance

대상 repository:

* cppi-portfolio-insurance
* tipp-dynamic-floor-strategy

### 6. Financial Data Science

대상 repository:

* financial-big-data-analysis
* financial-news-nlp-pipeline

### 7. Market Signals & Event Analytics

대상 repository:

* sentiment-trading-strategy
* ceo-twitter-market-impact
* technical-indicator-backtest

---

## 저장소 구조 원칙

현재 저장소는 markdown-first 구조를 유지합니다.

초기 구조:

financial-engineering-portfolio/
├── README.md
├── docs/
├── projects/
├── links/
├── slides/
├── assets/

---

## 각 폴더 역할

### docs/

설명 문서 저장

예:

* about.md
* research-interests.md
* roadmap.md

### projects/

카테고리별 안내 페이지 저장

예:

* stochastic-models-and-market-risk.md
* derivatives-pricing-and-volatility.md
* portfolio-optimization-and-allocation.md
* factor-investing.md
* dynamic-portfolio-insurance.md
* financial-data-science.md
* market-signals-and-event-analytics.md

### links/

외부 링크 정리

예:

* notion-links.md

### slides/

발표자료 저장

### assets/

이미지 및 다이어그램 저장

---

## 문서 작성 원칙

모든 문서는 다음 원칙을 따른다.

* 과장 금지
* 실제 수행 내용 기반 작성
* 전문적 문체 유지
* 불필요한 수식어 최소화
* markdown heading 일관성 유지
* 지나친 디자인보다 구조 우선

---

## 프로젝트 연결 원칙

향후 실제 프로젝트는 별도 repository로 생성하여 본 Repository는 포트폴리오 구조 설계 및 웹 포트폴리오로써 활용합니다.

즉:

이 저장소 = 안내 허브

개별 프로젝트 repo = 실제 증명 자료

구조:

Portfolio Hub → Project Repo → Notion Detail → Slides

---

## Codex 작업 원칙

Codex는 다음 역할로 활용합니다.

* 문서 구조 생성
* markdown 파일 생성
* README 보완
* category page template 생성
* 문서 naming consistency 유지

Codex는 아직 다음을 수행하지 않습니다.

* 프로젝트 주제 임의 선정
* 과장된 성과 작성
* 존재하지 않는 경험 생성

---

## 향후 진행 단계

### Phase 1

포트폴리오 허브 구조 완성

### Phase 2

카테고리별 프로젝트 후보 정리

### Phase 3

첫 번째 프로젝트 repository 생성

### Phase 4

GitHub Pages 기반 웹 포트폴리오 공개

---

## 최우선 기준

현재 가장 중요한 것은:

"많은 자료를 빠르게 공개하는 것"이 아니라

"하나씩 정확하게 재구성 가능한 구조를 만드는 것"

