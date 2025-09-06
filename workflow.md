flowchart TD

    %% Beginner Level
    A1[Beginner Level] --> B1[Cash: Buy/Sell Shares<br>(Delivery & Intraday)]
    A1 --> B2[F&O: Simple Options Buying<br>(Calls/Puts)]
    A1 --> B3[Commodity: Intraday Gold/Crude]

    %% Intermediate Level
    A2[Intermediate Level] --> C1[Cash: Stock Screening<br>Tech/Fundamental, BO/CO Orders]
    A2 --> C2[F&O: Futures & Multi-leg Options<br>Hedging Strategies]
    A2 --> C3[Commodity: Futures Spreads<br>Macro Analysis]

    %% Expert Level
    A3[Expert Level] --> D1[Cash: Algo Trading, Arbitrage<br>Portfolio Hedging]
    A3 --> D2[F&O: Options Greeks, Volatility Trading<br>Algo Execution]
    A3 --> D3[Commodity: Global Hedging<br>Cross-Commodity Arbitrage]

    %% Institutional Level
    A4[Institutional / Pro Level] --> E1[Quant Models & AI/ML]
    A4 --> E2[Algo Execution & HFT]
    A4 --> E3[Risk Desk: VaR, Stress Testing]
    A4 --> E4[Compliance & Reporting]

    %% Level Connections
    B1 --> C1
    B2 --> C2
    B3 --> C3
    C1 --> D1
    C2 --> D2
    C3 --> D3
    D1 --> E1
    D2 --> E2
    D3 --> E3
    E1 --> E4
