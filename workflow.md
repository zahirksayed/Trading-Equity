# Stock Trading Workflow (Cash, F&O, Commodity)

## Beginner Level
- **Cash (Equity)**
  - Buy/Sell shares
  - Delivery (CNC)
  - Intraday (MIS)
  - Market / Limit / Stop Loss Orders
- **F&O (Derivatives)**
  - Simple Options Buying (Calls, Puts)
  - Small capital, limited risk
  - Exit before expiry
- **Commodity**
  - Gold/Crude intraday trading
  - MCX contracts with fixed lot size
  - High liquidity instruments

## Intermediate Level
- **Cash (Equity)**
  - Stock Screening (Technical + Fundamental)
  - Use indicators (RSI, MACD, VWAP, Volume breakout)
  - Bracket Orders / Cover Orders
  - Swing trades with GTT
  - Journaling & review
- **F&O**
  - Futures trading (Long/Short positions)
  - Hedging with Futures against Cash
  - Multi-leg option strategies (Spreads, Covered Calls)
  - Risk Management with Stop Loss & Position Sizing
- **Commodity**
  - Futures spreads (near-month vs far-month)
  - Macro analysis (USD-INR, Oil supply, Geopolitics)
  - Calendar spreads for hedging

## Expert Level
- **Cash (Equity)**
  - Algorithmic & Quant Trading
  - Momentum & Pairs Trading
  - Cash-Futures Arbitrage
  - Portfolio hedging with Index Options
- **F&O**
  - Advanced Multi-leg Strategies (Iron Condor, Straddle, Strangle)
  - Option Chain & OI analysis
  - Options Greeks (Delta, Theta, Vega, Gamma)
  - Volatility Trading
  - Algo-based automated execution
- **Commodity**
  - Global macro-driven trades
  - Cross-commodity arbitrage (Gold-Silver ratio, Crude-NatGas correlation)
  - Corporate hedging for imports/exports

## Institutional / Professional Level
- Research Desk
  - Quant models
  - AI/ML-driven signals
- Execution Desk
  - Algo Execution
  - Smart Order Routing
  - High Frequency Trading (HFT)
- Risk Desk
  - Portfolio VaR
  - Stress testing & exposure management
- Compliance & Reporting
  - SEBI norms
  - Auditing & regulations

# Stock Trading Workflow Diagram

```mermaid
flowchart TD
    A[Beginner Level] --> B[Cash: Buy/Sell Shares]
    A --> C[F&O: Options Buying]
    A --> D[Commodity: Intraday Crude/Gold]

    B --> E[Intermediate: Technical Screening]
    C --> F[Futures + Multi-leg Options]
    D --> G[Macro + Futures Spreads]

    E --> H[Expert: Algo & Hedging]
    F --> I[Expert: Greeks + Volatility]
    G --> J[Expert: Arbitrage + Global Hedging]

    H --> K[Institutional: Quant Models]
    I --> L[Institutional: HFT + Algo Execution]
    J --> M[Institutional: Risk Desk + Compliance]
