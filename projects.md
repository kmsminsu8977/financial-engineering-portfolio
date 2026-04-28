# Projects Index

## Navigation

- [Back to README](README.md)
- [About This Research Hub](docs/about/)

## Project Classification

이 문서는 `financial-engineering-lab`에서 연결하는 개별 프로젝트 repository를 7개 연구 축에 따라 정리합니다. 각 프로젝트의 세부 구현, 데이터, 산출물은 별도 repository에서 관리합니다.

### [Category 1] Stochastic Models & Market Risk

1. **공분산 리스크 분해 (`covariance-risk-decomposition`)**
   - Repository: [covariance-risk-decomposition](../covariance-risk-decomposition)
   - 주제: 공분산 행렬, PCA, 요인모형을 활용한 포트폴리오 리스크 기여도 분석

2. **시장 리스크 VaR 백테스팅 (`market-risk-var-backtesting`)**
   - Repository: [market-risk-var-backtesting](../market-risk-var-backtesting)
   - 주제: VaR 추정, 예외 발생률 검정, 리스크 모델 검증

3. **몬테카를로 시뮬레이션 (`monte-carlo-simulation`)**
   - Repository: [monte-carlo-simulation](../monte-carlo-simulation)
   - 주제: 확률분포와 시나리오 생성을 활용한 금융 변수 시뮬레이션

4. **주가 경로 시뮬레이션 (`stock-price-path-simulation`)**
   - Repository: [stock-price-path-simulation](../stock-price-path-simulation)
   - 주제: GBM 등 가격 과정 기반 경로 생성과 민감도 분석

5. **금리 예측 모델 (`interest-rate-prediction-model`)**
   - Repository: [interest-rate-prediction-model](../interest-rate-prediction-model)
   - 주제: 거시 변수와 시계열 특징을 활용한 금리 방향성/수준 예측

### [Category 2] Derivatives Pricing & Volatility

1. **블랙-숄즈 모형 (`black-scholes-model`)**
   - Repository: [black-scholes-model](../black-scholes-model)
   - 주제: 폐쇄형 옵션 가격공식, 민감도, 모형 가정의 한계 정리

2. **옵션 가격결정 (`option-pricing`)**
   - Repository: [option-pricing](../option-pricing)
   - 주제: 몬테카를로 엔진, 유럽형/아시안 옵션 가격평가, 수렴 분석

3. **Greek 리스크 분석 (`greek-risk-analysis`)**
   - Repository: [greek-risk-analysis](../greek-risk-analysis)
   - 주제: Delta, Gamma, Vega 등 옵션 민감도와 헤지 관점의 리스크 분석

4. **내재변동성 분석 (`implied-volatility-analysis`)**
   - Repository: [implied-volatility-analysis](../implied-volatility-analysis)
   - 주제: 시장가격 기반 내재변동성 역산, smile/surface 구조 해석

### [Category 3] Portfolio Optimization & Allocation

1. **최적 포트폴리오 (`optimal-portfolio`)**
   - Repository: [optimal-portfolio](../optimal-portfolio)
   - 주제: 평균-분산 최적화, 제약조건, 추정 오차와 자산배분 민감도

2. **포트폴리오 리밸런싱 전략 (`portfolio-rebalancing-strategy`)**
   - Repository: [portfolio-rebalancing-strategy](../portfolio-rebalancing-strategy)
   - 주제: 리밸런싱 주기, 밴드 규칙, 거래비용을 고려한 포트폴리오 운영

### [Category 4] Factor Investing

1. **멀티팩터 포트폴리오 (`multi-factor-portfolio`)**
   - Repository: [multi-factor-portfolio](../multi-factor-portfolio)
   - 주제: 가치, 모멘텀, 퀄리티, 저변동성 등 복수 요인의 결합과 배분

2. **Betting Against Beta 포트폴리오 (`betting-against-beta-portfolio`)**
   - Repository: [betting-against-beta-portfolio](../betting-against-beta-portfolio)
   - 주제: 저베타 프리미엄 검증, 레버리지 제약, 시장 베타 중립 구성

### [Category 5] Dynamic Portfolio Insurance

1. **CPPI 포트폴리오 보험 (`cppi-portfolio-insurance`)**
   - Repository: [cppi-portfolio-insurance](../cppi-portfolio-insurance)
   - 주제: 고정 비율 포트폴리오 보험 전략의 하방 보호와 상승 참여도 분석

2. **TIPP 동적 Floor 전략 (`tipp-dynamic-floor-strategy`)**
   - Repository: [tipp-dynamic-floor-strategy](../tipp-dynamic-floor-strategy)
   - 주제: 성과 연동 floor 조정, 동적 위험자산 노출, drawdown 방어

### [Category 6] Financial Data Science

1. **금융 빅데이터 분석 (`financial-big-data-analysis`)**
   - Repository: [financial-big-data-analysis](../financial-big-data-analysis)
   - 주제: 대용량 금융 데이터 처리, 특징 생성, 분석/시각화 워크플로우

2. **금융 뉴스 NLP 파이프라인 (`financial-news-nlp-pipeline`)**
   - Repository: [financial-news-nlp-pipeline](../financial-news-nlp-pipeline)
   - 주제: 뉴스 수집, 전처리, 토큰화, 감성·토픽·임베딩 분석 파이프라인

### [Category 7] Market Signals & Event Analytics

1. **감성 트레이딩 전략 (`sentiment-trading-strategy`)**
   - Repository: [sentiment-trading-strategy](../sentiment-trading-strategy)
   - 주제: 뉴스/텍스트 감성 신호를 활용한 매매전략과 백테스트

2. **CEO 트위터 시장 영향 (`ceo-twitter-market-impact`)**
   - Repository: [ceo-twitter-market-impact](../ceo-twitter-market-impact)
   - 주제: CEO 발언 이벤트와 주가/거래량/변동성 반응 분석

3. **기술적 지표 백테스트 (`technical-indicator-backtest`)**
   - Repository: [technical-indicator-backtest](../technical-indicator-backtest)
   - 주제: 이동평균, 모멘텀, 변동성 돌파 등 기술적 지표의 재현 가능한 백테스트
