# 김민수의 금융공학 연구소

금융공학, 리스크 모델링, 파생상품 가격결정, 포트폴리오 연구, 팩터 투자, 금융 데이터 사이언스 프로젝트를 구조적으로 정리합니다.

이 저장소는 개별 프로젝트의 전체 소스코드를 직접 보관하는 공간이 아니라, 연구 방향과 연구 카테고리, 외부 저장소 및 연구 기록을 연결하는 허브 역할을 수행합니다.

## Overview

- Repository 목적: 금융공학 및 금융 데이터 관련 연구 프로젝트를 연구 카테고리별로 소개
- 운영 방식: Financial Engineering Lab (연구 소개) -> Project Repository (소스코드, 결과) -> Notion/Slides (연구 상세)
- 프로젝트 단위: 상위 폴더의 개별 repository를 연구 축별로 분류

## Quick Navigation

- [About This Repository](docs/about/)
- [Projects Index](projects/)
- [Stochastic Models & Market Risk](research-categories/stochastic-models-and-market-risk/)
- [Derivatives Pricing & Volatility](research-categories/derivatives-pricing-and-volatility/)
- [Portfolio Optimization & Allocation](research-categories/portfolio-optimization-and-allocation/)
- [Factor Investing](research-categories/factor-investing/)
- [Dynamic Portfolio Insurance](research-categories/dynamic-portfolio-insurance/)
- [Financial Data Science](research-categories/financial-data-science/)
- [Market Signals & Event Analytics](research-categories/market-signals-and-event-analytics/)

## Research Categories

### 1. Stochastic Models & Market Risk

확률과정, 공분산 구조, VaR, 경로 시뮬레이션, 금리 예측을 통해 시장 리스크를 정량적으로 해석합니다.

- Research Category Page: [Stochastic Models & Market Risk](research-categories/stochastic-models-and-market-risk/)
- Projects: [covariance-risk-decomposition](../covariance-risk-decomposition), [market-risk-var-backtesting](../market-risk-var-backtesting), [monte-carlo-simulation](../monte-carlo-simulation), [stock-price-path-simulation](../stock-price-path-simulation), [interest-rate-prediction-model](../interest-rate-prediction-model)

### 2. Derivatives Pricing & Volatility

옵션 가격결정, 몬테카를로 pricing, Greeks, 내재변동성 분석을 다룹니다.

- Research Category Page: [Derivatives Pricing & Volatility](research-categories/derivatives-pricing-and-volatility/)
- Projects: [black-scholes-model](../black-scholes-model), [option-pricing](../option-pricing), [greek-risk-analysis](../greek-risk-analysis), [implied-volatility-analysis](../implied-volatility-analysis)

### 3. Portfolio Optimization & Allocation

위험-수익률 균형, 제약조건, 리밸런싱 규칙을 고려한 자산배분 연구를 다룹니다.

- Research Category Page: [Portfolio Optimization & Allocation](research-categories/portfolio-optimization-and-allocation/)
- Projects: [optimal-portfolio](../optimal-portfolio), [portfolio-rebalancing-strategy](../portfolio-rebalancing-strategy)

### 4. Factor Investing

멀티팩터 포트폴리오와 Betting Against Beta 전략을 중심으로 팩터 프리미엄과 리스크 기여도를 검증합니다.

- Research Category Page: [Factor Investing](research-categories/factor-investing/)
- Projects: [multi-factor-portfolio](../multi-factor-portfolio), [betting-against-beta-portfolio](../betting-against-beta-portfolio)

### 5. Dynamic Portfolio Insurance

CPPI, TIPP처럼 동적 floor를 사용하는 포트폴리오 보험 전략의 방어력과 기회비용을 분석합니다.

- Research Category Page: [Dynamic Portfolio Insurance](research-categories/dynamic-portfolio-insurance/)
- Projects: [cppi-portfolio-insurance](../cppi-portfolio-insurance), [tipp-dynamic-floor-strategy](../tipp-dynamic-floor-strategy)

### 6. Financial Data Science

금융 빅데이터 분석과 뉴스 NLP 파이프라인을 통해 데이터 수집, 정제, 모델링, 시각화 워크플로우를 정리합니다.

- Research Category Page: [Financial Data Science](research-categories/financial-data-science/)
- Projects: [financial-big-data-analysis](../financial-big-data-analysis), [financial-news-nlp-pipeline](../financial-news-nlp-pipeline)

### 7. Market Signals & Event Analytics

감성 신호, CEO 트위터 이벤트, 기술적 지표를 활용한 시장 반응과 전략 성과를 분석합니다.

- Research Category Page: [Market Signals & Event Analytics](research-categories/market-signals-and-event-analytics/)
- Projects: [sentiment-trading-strategy](../sentiment-trading-strategy), [ceo-twitter-market-impact](../ceo-twitter-market-impact), [technical-indicator-backtest](../technical-indicator-backtest)

## Repository Structure

```text
financial-engineering-lab/
├── README.md
├── docs/
│   └── about.md
├── research-categories/
│   ├── stochastic-models-and-market-risk.md
│   ├── derivatives-pricing-and-volatility.md
│   ├── portfolio-optimization-and-allocation.md
│   ├── factor-investing.md
│   ├── dynamic-portfolio-insurance.md
│   ├── financial-data-science.md
│   └── market-signals-and-event-analytics.md
├── projects/
├── links/
├── slides/
└── assets/
```
