# Track Awesome Quant Updates Daily

A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance)

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/wilsonfreitas/awesome-quant/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) · ⭐ 25K · 🏷️ Finance

[ Daily / [Weekly](/content/wilsonfreitas/awesome-quant/week/README.md) / [Overview](/content/wilsonfreitas/awesome-quant/readme/README.md) ]

## [Mar 22, 2026](/content/2026/03/22/README.md)

### Rust / Data Visualization

*   [OpenFinClaw (⭐119)](https://github.com/cryptoSUN2049/openFinclaw) - AI-native one-person hedge fund platform with Rust trading engine. Natural language → strategy → backtest → execution in 60s. Multi-market (US/HK/CN/Crypto), self-evolving strategy pipeline. Built on OpenClaw (68K+ stars).
*   [fin-primitives (⭐4)](https://github.com/Mattbusel/fin-primitives) - Financial market primitives in Rust: Price/Quantity/Symbol newtypes, BTreeMap order book, OHLCV aggregation, SMA/EMA/RSI indicators, position ledger with PnL, and composable risk monitor.
*   [fin-stream (⭐2)](https://github.com/Mattbusel/fin-stream) - Real-time market data streaming in Rust: lock-free SPSC ring buffer, 100K+ ticks/second ingestion, multi-timeframe OHLCV construction, and Lorentz transforms on financial time series.
*   [Special-Relativity-in-Financial-Modeling (⭐4)](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) - C++20 implementation of special-relativistic geometry applied to OHLCV data: Lorentz factors, spacetime intervals, Christoffel symbols, and geodesic deviation signals from live market data. DOI: 10.5281/zenodo.18639919

### Python / Trading & Backtesting

*   [VARRD (⭐10)](https://github.com/augiemazza/varrd) - AI-powered trading edge discovery platform that validates trading ideas with event studies, statistical tests, and real market data. Web app, MCP server, CLI (`pip install varrd`), and Python SDK.

### Python / Data Sources

*   [Polymarket Scanner API (⭐1)](https://github.com/vesper-astrena/polymarket-scanner-api) - Real-time arbitrage detection API for Polymarket prediction markets, scanning 12,000+ markets for mispricings.
*   [SwapAPI](https://swapapi.dev) - Free DEX aggregator API returning executable swap calldata across 46 EVM chains. No API key required.
*   [swiss-finance-data (⭐0)](https://github.com/EMen11/swiss-finance-data) - Python package for Swiss financial data (SNB Policy Rate, SARON, CHF FX rates, CPI, SMI equities, Confederation bond yields) from official SNB sources.
*   [RTPR](https://rtpr.io) - Real-time press release API delivering news from Business Wire, PR Newswire, and GlobeNewswire with sub-500ms latency. REST and WebSocket APIs for financial applications. Python and Node.js SDKs available.

### JavaScript / FrameWorks

*   [SimpleFunctions (⭐1)](https://github.com/spfunctions/simplefunctions-cli) - Prediction market intelligence CLI for Kalshi and Polymarket. Causal thesis models, edge detection, 24/7 orderbook monitoring, what-if scenarios, and trade execution. MCP server for AI agent integration.
*   [PreReason (⭐0)](https://github.com/PreReason/mcp) - Pre-analyzed Bitcoin and macro market briefings for AI agents. 17 contexts with trend signals, confidence scores, and regime classification via REST API and MCP.
*   [rebalance (⭐2)](https://github.com/cjroth/rebalance) - Interactive portfolio rebalancing tool that imports brokerage CSV data, sets target allocations, and generates trade instructions.

### CPP / Data Visualization

*   [NexusFix (⭐11)](https://github.com/SilverstreamsAI/NexusFix) - C++23 FIX protocol engine with zero-copy parsing and SIMD acceleration, 3x faster than QuickFIX.

### Reproducing Works, Training & Books / Data Visualization

*   [Portfolio Optimization Book](https://portfoliooptimizationbook.com/) - Prof. Daniel Palomar's Portfolio Optimization Book

### Related Lists / Data Visualization

*   [CONVEXFI](https://github.com/convexfi) - Official GitHub organization for the convex research group at the Hong Kong University of Science and Technology (HKUST).

## [Feb 24, 2026](/content/2026/02/24/README.md)

### JavaScript / FrameWorks

*   [pmxt (⭐1.1k)](https://github.com/pmxt-dev/pmxt) - The CCXT for prediction markets. A unified API for trading on Polymarket, Kalshi, and more.
*   [pmxt (⭐1.1k)](https://github.com/qoery-com/pmxt) - A unified API for accessing prediction market data across multiple exchanges. CCXT for prediction markets.

### Python / Financial Instruments and Pricing

*   [quantra (⭐27)](https://github.com/joseprupi/quantraserver) High-performance pricing engine built on QuantLib. It exposes QuantLib's functionality through gRPC and REST APIs, enabling distributed computations with FlatBuffers serialization.
*   [optionlab (⭐486)](https://github.com/rgaveiga/optionlab) - A Python library for evaluating option trading strategies.

### Python / Trading & Backtesting

*   [the0 (⭐199)](https://github.com/alexanderwanyoike/the0) - Self-hosted execution engine for algorithmic trading bots. Write strategies in Python, TypeScript, Rust, C++, C#, Scala, or Haskell and deploy with one command. Each bot runs in an isolated container with scheduled or streaming execution.
*   [PRISM-INSIGHT (⭐503)](https://github.com/dragon1086/prism-insight) - AI-powered stock analysis system with 13 specialized agents, automated trading via KIS API, supporting Korean & US markets.
*   [Chartscout](https://chartscout.io) - Real-time cryptocurrency chart pattern detection with automated alerts across multiple exchanges
*   [DayTradingBench](https://daytradingbench.com) - Live autonomous benchmark that evaluates LLM trading performance on DAX and Nasdaq indices using identical strategies and real-time market data. API access available.
*   [CoinTester](https://cointester.io) - No-code crypto backtesting platform with 100+ indicators, AI sentiment signals, and 5+ years of historical data across 1,000+ trading pairs.
*   [PythonTradingFramework (⭐27)](https://github.com/JustinGuese/python_tradingbot_framework) ![Github last commit (branch)](https://img.shields.io/github/last-commit/JustinGuese/python_tradingbot_framework/main) - Python algorithmic trading bot framework for Kubernetes: backtesting, hyperparameter optimization, 150+ technical analysis indicators (RSI, MACD, Bollinger Bands, ADX), portfolio management, PostgreSQL integration, Helm deployment, CronJob scheduling. Minimal overhead, production-ready, Yahoo Finance data.
*   [QTradeX-AI-Agents (⭐16)](https://github.com/squidKid-deluxe/QTradeX-AI-Agents) - Example strategies for the QTradeX platfrom.
*   [QTradeX-Algo-Trading-SDK (⭐59)](https://github.com/squidKid-deluxe/QTradeX-Algo-Trading-SDK) - AI-powered SDK featuring algorithmic trading, backtesting, deployment on 100+ exchanges, and multiple optimization engines.
*   [antback (⭐15)](https://github.com/ts-kontakt/antback) - A lightweight, event-loop-style backtest engine that allows a function-driven imperative style using efficient stateful helper functions and data containers.

### Python / Risk Analysis

*   [curistat](https://github.com/moxiespirit/MyClone/tree/main/volatility_platform) - Futures volatility forecasting platform for ES/NQ. Proprietary CVN rating (1-10), regime detection (CRC composite), 8 directional signals, economic event impact analytics. Includes MCP server for AI agent integration.
*   [Prop Trader Compass](https://otto-ships.github.io/prop-trader-compass/) - Interactive risk and payout calculator for Futures and CFD traders; features one-time fee firm comparisons.

### Python / Factor Analysis

*   [quant-lab-alpha (⭐27)](https://github.com/husainm97/quant-lab-alpha) - Open-source investment analytics platform bridging academic research and retail finance.

### Python / Sentiment Analysis

*   [Social Stock Sentiment API](https://api.adanos.org/docs) - REST API analyzing Reddit and X/Twitter for stock mentions and sentiment, providing buzz scores, trending stocks, and AI-generated trend explanations.

### Python / Data Sources

*   [goMacro.ai](https://gomacro.ai) - AI-powered economic calendar with institutional-grade insights, bull/bear/base case scenario planning for NFP, CPI, PPI and other macro data releases.
*   [StockAInsights](https://stockainsights.com) - AI-extracted financial statements API covering SEC filings including foreign filers (20-F, 6-K, 40-F), normalized quarterly and annual data from 2014+.
*   [edinet-mcp (⭐4)](https://github.com/ajtgjmdjp/edinet-mcp) - Parse Japanese XBRL financial statements from EDINET with 161 normalized labels, 26 financial metrics, and multi-company screening.
*   [estat-mcp (⭐0)](https://github.com/ajtgjmdjp/estat-mcp) - Access Japanese government statistics (e-Stat) covering population, GDP, CPI, labor, and trade data with MCP integration and Polars export.
*   [tdnet-disclosure-mcp (⭐1)](https://github.com/ajtgjmdjp/tdnet-disclosure-mcp) - Access Japanese timely disclosures (TDNet) via MCP. Retrieve earnings, dividends, forecasts, buybacks, and other filings for 4,000+ listed companies. No API key required.
*   [coinpulse (⭐1)](https://github.com/soutone/coinpulse-python) - Python SDK for cryptocurrency portfolio tracking with real-time prices, P/L calculations, and price alerts. Free tier available.
*   [brapi.dev](https://brapi.dev/) - Brazilian stock market data API for B3/Bovespa quotes, historical OHLCV, dividends, and fundamentals.
*   [13F Insight](https://13finsight.com/) - Track institutional investor 13F holdings with AI-powered analysis, position change alerts, and filing summaries.
*   [edgartools (⭐1.8k)](https://github.com/dgunning/edgartools) - AI-native SEC EDGAR library with XBRL financials, clean text extraction, 17+ typed forms, and pandas DataFrames.
*   [FXMacroData](https://fxmacrodata.com/) - Real-time forex macroeconomic API for all major currency pairs sourced from central bank announcements.

### CPP / Data Visualization

*   [rallyplot](https://rallyplot.com) - Fast, GPU-accelerated financial plotting library
*   [PandoraTrader (⭐1.4k)](https://github.com/pegasusTrader/PandoraTrader) - A C++ CTP trading framework, with very clear logic

### Reproducing Works, Training & Books / Data Visualization

*   [KeepRule](https://keeprule.com/) - Curated library of decision-making principles and investment wisdom from masters like Buffett and Munger, featuring mental models for better investment thinking.

### Related Lists / Data Visualization

*   [awesome-sec-filings (⭐9)](https://github.com/vibeyclaw/awesome-sec-filings) - A curated list of tools, data sources, libraries, and resources for working with SEC filings (13F, 10-K, 10-Q, 8-K).

## [Jan 07, 2026](/content/2026/01/07/README.md)

### Julia / FrameWorks

*   [CcyConv.jl (⭐25)](https://github.com/bhftbootcamp/CcyConv.jl) - Currency conversion library for Julia
*   [OnlinePortfolioAnalytics.jl (⭐13)](https://github.com/femtotrader/OnlinePortfolioAnalytics.jl) - A Julia quantitative portfolio analytics (risk / performance) via online algorithms.

### CPP / Data Visualization

*   [OrderMatchingEngine (⭐127)](https://github.com/PIYUSH-KUMAR1809/order-matching-engine) - A production-grade, lock-free, high-frequency trading matching engine achieving 150M+ orders/sec.

## [Jan 04, 2026](/content/2026/01/04/README.md)

### Python / Trading & Backtesting

*   [Gunbot Quant (⭐42)](https://github.com/GuntharDeNiro/gunbot-quant) - Toolkit for quantitative trading analysis. It integrates an advanced market screener, a multi-strategy, multi-asset backtesting engine. Use with built-in GUI or through CLI.
*   [StrateQueue (⭐170)](https://github.com/StrateQueue/StrateQueue) - An open‑source, broker‑agnostic Python library that lets you seamlessly deploy strategies from any major backtesting engine to live (or paper) trading with zero code changes and built‑in safety controls.

### Python / Risk Analysis

*   [Quant Lab Alpha (⭐27)](https://github.com/husainm97/quant-lab-alpha) — Portfolio risk decomposition and Monte Carlo simulation toolkit with factor-based modeling.
*   [quantitative-finance-tools (⭐4)](https://github.com/omichauhan-lgtm/quantitative-finance-tools) - Library for portfolio optimization (MVO) and rigorous risk metrics (VaR/CVaR).

### Python / Data Sources

*   [StockAPI](https://stockapi.com.cn) – Free real-time Chinese stock data (REST & WebSocket).
*   [defeatbeta-api (⭐519)](https://github.com/defeat-beta/defeatbeta-api) - An open-source alternative to Yahoo Finance's market data APIs with higher reliability.
*   [oilpriceapi (⭐0)](https://github.com/OilpriceAPI/python-sdk) - Python SDK for real-time oil and commodity prices (WTI, Brent, Urals, natural gas, coal) with OpenBB integration.
*   [Earnings Feed](https://earningsfeed.com/api) - Real-time SEC filings, insider trades, and institutional holdings API.
*   [fsynth (⭐4)](https://github.com/welcra/fsynth) - Python library for high-fidelity unlimited synthetic financial data generation using Heston Stochastic Volatility and Merton Jump Diffusion.
*   [fedfred](https://nikhilxsunder.github.io/fedfred/) - FRED & GeoFRED Economic data API with preprocessed dataframe output in pandas/geopandas, polars/polars\_st, and dask dataframes/geodataframes.
*   [edgar-sec](https://nikhilxsunder.github.io/edgar-sec/) - EDGAR Financial data API with preprocessed dataclass outputs.

### Matlab / Alternatives

*   [RunMat](https://runmat.org) - High performance, Open Source, MATLAB syntax runtime.

### Julia / FrameWorks

*   [CryptoExchangeAPIs.jl (⭐30)](https://github.com/bhftbootcamp/CryptoExchangeAPIs.jl) - A Julia library for cryptocurrency exchange APIs
*   [Fastback.jl (⭐19)](https://github.com/rbeeli/Fastback.jl) - Blazing fast Julia backtester.
*   [LightweightCharts.jl (⭐48)](https://github.com/bhftbootcamp/LightweightCharts.jl) - Julia wrapper for Lightweight Charts™ by TradingView.
*   [TechnicalIndicatorCharts.jl (⭐6)](https://github.com/g-gundam/TechnicalIndicatorCharts.jl) - Visualize OnlineTechnicalIndicators.jl using LightweightCharts.jl.
*   [OnlineTechnicalIndicators.jl (⭐33)](https://github.com/femtotrader/OnlineTechnicalIndicators.jl) - Julia Technical Analysis Indicators via online algorithms.
*   [OnlineResamplers.jl (⭐2)](https://github.com/femtotrader/OnlineResamplers.jl) - High-performance Julia package for real-time resampling of financial market data.
*   [RiskPerf.jl (⭐15)](https://github.com/rbeeli/RiskPerf.jl) - Quantitative risk and performance analysis package for financial time series powered by the Julia language.
*   [TimeArrays.jl (⭐38)](https://github.com/bhftbootcamp/TimeArrays.jl) - Time series handling for Julia

### Rust / Data Visualization

*   [RunMat (⭐190)](https://github.com/runmat-org/runmat) - Rust runtime for MATLAB-syntax array math with automatic CPU/GPU execution and fused kernels for quant simulations.

### Reproducing Works, Training & Books / Data Visualization

*   [AlgoTradingLib (⭐28)](https://github.com/usdaud/algotradinglib.github.io) - A catalog of algorithmic trading libraries, frameworks, strategies, and educational materials.

## [Apr 09, 2025](/content/2025/04/09/README.md)

### Python / Trading & Backtesting

*   [rust\_bt (⭐58)](https://github.com/jensnesten/rust_bt) - A high performance, low-latency backtesting engine for testing quantitative trading strategies on historical and live data in Rust.

### Python / Data Sources

*   [SaxoOpenAPI](https://www.developer.saxo/) - Saxo Bank financial data API.

## [Apr 01, 2025](/content/2025/04/01/README.md)

### Python / Data Sources

*   [polygon.io (⭐1.4k)](https://github.com/polygon-io/client-python) - A python library for Polygon.io financial data APIs.
*   [Financial Data](https://financialdata.net/) - Stock Market and Financial Data API.

## [Jan 22, 2025](/content/2025/01/22/README.md)

### JavaScript / FrameWorks

*   [chart-patterns](https://github.com/focus1691/chart-patterns) - Technical analysis library for Market Profile, Volume Profile, Stacked Imbalances and High Volume Node indicators.
*   [orderflow (⭐65)](https://github.com/focus1691/orderflow) - Orderflow trade aggregator for building Footprint Candles from exchange websocket data.

## [Dec 24, 2024](/content/2024/12/24/README.md)

### Python / Data Sources

*   [datamule-python (⭐518)](https://github.com/john-friedman/datamule-python) - A package to work with SEC data. Incorporates datamule endpoints.

### Reproducing Works, Training & Books / Data Visualization

*   [AFML (⭐810)](https://github.com/boyboi86/AFML) - All the answers for exercises from Advances in Financial Machine Learning by Dr Marco Lopez de Parodo.

## [Nov 23, 2024](/content/2024/11/23/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [RoughVolatilityWorkshop (⭐71)](https://github.com/jgatheral/RoughVolatilityWorkshop) - 2024 QuantMind's Rough Volatility Workshop lectures.

## [Oct 14, 2024](/content/2024/10/14/README.md)

### Python / Financial Instruments and Pricing

*   [Fincept Terminal (⭐2.9k)](https://github.com/Fincept-Corporation/FinceptTerminal) - Advance Data Based A.I Terminal for all Types of Financial Asset Research.
*   [fypy (⭐139)](https://github.com/jkirkby3/fypy) - Vanilla and exotic option pricing library to support quantitative R\&D. Focus on pricing interesting/useful models and contracts (including and beyond Black-Scholes), as well as calibration of financial models to market data.

### Python / Trading & Backtesting

*   [zipline-reloaded (⭐1.7k)](https://github.com/stefan-jansen/zipline-reloaded) - Zipline, a Pythonic Algorithmic Trading Library.
*   [Trading Strategy (⭐207)](https://github.com/tradingstrategy-ai/getting-started) - TradingStrategy.ai is a market data, backtesting, live trading and investor management framework for decentralised finance

### CPP / Data Visualization

*   [Hikyuu (⭐3.1k)](https://github.com/fasiondog/hikyuu) - A base on Python/C++ open source high-performance quant framework for faster analysis and backtesting, contains the complete trading system components for reuse and combination. You can use python or c++ freely.

### Python / Factor Analysis

*   [alphalens-reloaded (⭐557)](https://github.com/stefan-jansen/alphalens-reloaded) - Performance analysis of predictive (alpha) stock factors.

### Python / Time Series

*   [functime (⭐1.2k)](https://github.com/functime-org/functime) - Time-series machine learning at scale. Built with Polars for embarrassingly parallel feature extraction and forecasts on panel data.

### Python / Data Sources

*   [Trading Strategy (⭐351)](https://github.com/tradingstrategy-ai/trading-strategy/) - download price data for decentralised exchanges and lending protocols (DeFi)

### Python / Visualization

*   [QuantInvestStrats (⭐520)](https://github.com/ArturSepp/QuantInvestStrats) - Quantitative Investment Strategies (QIS) package implements Python analytics for visualisation of financial data, performance reporting, analysis of quantitative strategies.

### R / Data Sources

*   [tidyfinance (⭐20)](https://github.com/tidy-finance/r-tidyfinance) - Tidy Finance helper functions to download financial data and process the raw data into a structured Format (tidy data), including
    date conversion, scaling factor values, and filtering by the specified date.

### Matlab / FrameWorks

*   [PROJ\_Option\_Pricing\_Matlab (⭐208)](https://github.com/jkirkby3/PROJ_Option_Pricing_Matlab) - Quant Option Pricing - Exotic/Vanilla: Barrier, Asian, European, American, Parisian, Lookback, Cliquet, Variance Swap, Swing, Forward Starting, Step, Fader

### Reproducing Works, Training & Books / Data Visualization

*   [Tidy Finance](https://www.tidy-finance.org/) - An opinionated approach to empirical research in financial economics - a fully transparent, open-source code base in multiple programming languages (Python and R) to enable the reproducible implementation of financial research projects for students and practitioners.

## [Aug 12, 2024](/content/2024/08/12/README.md)

### Python / Numerical Libraries & Data Structures

*   [polars](https://docs.pola.rs/) - Polars is a blazingly fast DataFrame library for manipulating structured data.

### Python / Trading & Backtesting

*   [YABTE (⭐6)](https://github.com/bsdz/yabte) - Yet Another (Python) BackTesting Engine.

### Python / Risk Analysis

*   [QuantLibRisks (⭐19)](https://github.com/auto-differentiation/QuantLib-Risks-Py) - Fast risks with QuantLib
*   [XAD (⭐19)](https://github.com/auto-differentiation/xad-py) - Automatic Differentation (AAD) Library

### CPP / Data Visualization

*   [QuantLibRisks (⭐38)](https://github.com/auto-differentiation/QuantLib-Risks-Cpp) - Fast risks with QuantLib in C++
*   [XAD (⭐411)](https://github.com/auto-differentiation/xad) - Automatic Differentation (AAD) Library

### Frameworks / Data Visualization

*   XAD: Automatic Differentation (AAD) Library for [Python](https://pypi.org/project/xad/) and [C++ (⭐411)](https://github.com/auto-differentiation/xad)

### Reproducing Works, Training & Books / Data Visualization

*   [Auto-Differentiation Website](https://auto-differentiation.github.io/) - Background and  resources on Automatic Differentiation (AD) / Adjoint Algorithmic Differentitation (AAD).

## [Jul 14, 2024](/content/2024/07/14/README.md)

### Python / Sentiment Analysis

*   [Asset News Sentiment Analyzer (⭐192)](https://github.com/KVignesh122/AssetNewsSentimentAnalyzer) - Sentiment analysis and report generation package for financial assets and securities utilizing GPT models.

## [Apr 04, 2024](/content/2024/04/04/README.md)

### Python / Indicators

*   [talipp (⭐526)](https://github.com/nardew/talipp) - Incremental technical analysis library for Python.
*   [streaming\_indicators (⭐146)](https://github.com/mr-easy/streaming_indicators) - A python library for computing technical analysis indicators on streaming data.

### Python / Risk Analysis

*   [fortitudo.tech (⭐289)](https://github.com/fortitudo-tech/fortitudo.tech) - Conditional Value-at-Risk (CVaR) portfolio optimization and Entropy Pooling views / stress-testing in Python.

### Python / Data Sources

*   [FinanceDatabase (⭐7.2k)](https://github.com/JerBouma/FinanceDatabase) - This is a database of 300.000+ symbols containing Equities, ETFs, Funds, Indices, Currencies, Cryptocurrencies and Money Markets.

## [Mar 18, 2024](/content/2024/03/18/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [Finance (⭐3.7k)](https://github.com/shashankvemuri/Finance) - 150+ quantitative finance Python programs to help you gather, manipulate, and analyze stock market data.
*   [101\_formulaic\_alphas (⭐45)](https://github.com/ram-ki/101_formulaic_alphas) - Implementation of [101 formulaic alphas](https://arxiv.org/ftp/arxiv/papers/1601/1601.00991.pdf) using qstrader.

## [Mar 11, 2024](/content/2024/03/11/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [Autoencoder-Asset-Pricing-Models (⭐140)](https://github.com/RichardS0268/Autoencoder-Asset-Pricing-Models) - Reimplementation of Autoencoder Asset Pricing Models ([GKX, 2019](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3335536)).

## [Feb 27, 2024](/content/2024/02/27/README.md)

### Julia / FrameWorks

*   [Lucky.jl (⭐26)](https://github.com/oliviermilla/Lucky.jl) - Modular, asynchronous trading engine in pure Julia.

## [Feb 23, 2024](/content/2024/02/23/README.md)

### Python / Financial Instruments and Pricing

*   [rateslib (⭐327)](https://github.com/attack68/rateslib) - A fixed income library for pricing bonds and bond futures, and derivatives such as IRS, cross-currency and FX swaps.

### Python / Risk Analysis

*   [empyrical-reloaded (⭐101)](https://github.com/stefan-jansen/empyrical-reloaded) - Common financial risk and performance metrics. [empyrical (⭐1.5k)](https://github.com/quantopian/empyrical) fork.
*   [pyfolio-reloaded (⭐579)](https://github.com/stefan-jansen/pyfolio-reloaded) - Portfolio and risk analytics in Python. [pyfolio (⭐6.3k)](https://github.com/quantopian/pyfolio) fork.

### R / Financial Instruments and Pricing

*   [RQuantLib (⭐131)](https://github.com/eddelbuettel/rquantlib) - RQuantLib connects GNU R with QuantLib.

### Java / FrameWorks

*   [JQuantLib (⭐152)](https://github.com/frgomes/jquantlib) - JQuantLib is a free, open-source, comprehensive framework for quantitative finance, written in 100% Java.

### Frameworks / Data Visualization

*   [QuantLib (⭐6.9k)](https://github.com/lballabio/QuantLib) - The QuantLib project is aimed at providing a comprehensive software framework for quantitative finance.
    *   QuantLibRisks - Fast risks with QuantLib in [Python](https://pypi.org/project/QuantLib-Risks/) and [C++ (⭐38)](https://github.com/auto-differentiation/QuantLib-Risks-Cpp)
    *   XAD - Automatic Differentiation (AAD) Library in [Python](https://pypi.org/project/xad/) and [C++ (⭐411)](https://github.com/auto-differentiation/xad/)
    *   [JQuantLib (⭐152)](https://github.com/frgomes/jquantlib) - Java port.
    *   [RQuantLib (⭐131)](https://github.com/eddelbuettel/rquantlib) - R port.
    *   [QuantLibAddin](https://www.quantlib.org/quantlibaddin/) - Excel support.
    *   [QuantLibXL](https://www.quantlib.org/quantlibxl/) - Excel support.
    *   [QLNet (⭐422)](https://github.com/amaggiulli/qlnet) - .Net port.
    *   [PyQL (⭐1.3k)](https://github.com/enthought/pyql) - Python port.
    *   [QuantLib.jl (⭐143)](https://github.com/pazzo83/QuantLib.jl) - Julia port.
    *   [QuantLib-Python Documentation](https://quantlib-python-docs.readthedocs.io/) - Documentation for the Python bindings for the QuantLib library

### Reproducing Works, Training & Books / Data Visualization

*   [book\_irds3 (⭐114)](https://github.com/attack68/book_irds3) - Code repository for Pricing and Trading Interest Rate Derivatives.

## [Feb 08, 2024](/content/2024/02/08/README.md)

### Python / Trading & Backtesting

*   [fastquant (⭐1.7k)](https://github.com/enzoampil/fastquant) - fastquant allows you to easily backtest investment strategies with as few as 3 lines of python code.
*   [nautilus\_trader (⭐21k)](https://github.com/nautechsystems/nautilus_trader) - A high-performance algorithmic trading platform and event-driven backtester.

### Rust / Data Visualization

*   [finalytics (⭐67)](https://github.com/Nnamdi-sys/finalytics) - A rust library for financial data analysis.

### Reproducing Works, Training & Books / Data Visualization

*   [Statistical-Learning-based-Portfolio-Optimization](https://github.com/YannickKae/Statistical-Learning-based-Portfolio-Optimization) - This R Shiny App utilizes the Hierarchical Equal Risk Contribution (HERC) approach, a modern portfolio optimization method developed by Raffinot (2018).

## [Jan 14, 2024](/content/2024/01/14/README.md)

### Python / Numerical Libraries & Data Structures

*   [ArcticDB (⭐2.2k)](https://github.com/man-group/ArcticDB) - High performance datastore for time series and tick data.

## [Jan 02, 2024](/content/2024/01/02/README.md)

### Python / Trading & Backtesting

*   [skfolio (⭐1.9k)](https://github.com/skfolio/skfolio) - Python library for portfolio optimization built on top of scikit-learn. It provides a unified interface and sklearn compatible tools to build, tune and cross-validate portfolio models.

## [Dec 27, 2023](/content/2023/12/27/README.md)

### Python / Trading & Backtesting

*   [Investing algorithm framework (⭐700)](https://github.com/coding-kitties/investing-algorithm-framework) - Framework for developing, backtesting, and deploying automated trading algorithms.
*   [vnpy (⭐38k)](https://github.com/vnpy/vnpy) - VeighNa is a Python-based open source quantitative trading system development framework.
*   [Intelligent Trading Bot (⭐1.6k)](https://github.com/asavinov/intelligent-trading-bot) - Automatically generating signals and trading based on machine learning and feature engineering

### Python / Quant Research Environment

*   [Jupyter Quant (⭐19)](https://github.com/gnzsnz/jupyter-quant) - A dockerized Jupyter quant research environment with preloaded tools for quant analysis, statsmodels, pymc, arch, py\_vollib, zipline-reloaded, PyPortfolioOpt, etc.

### Reproducing Works, Training & Books / Data Visualization

*   [QuantFinanceTraining (⭐40)](https://github.com/JoaoJungblut/QuantFinanceTraining) - This repository contains codes that were executed during my training in the CQF (Certificate in Quantitative Finance). The codes are organized by class, facilitating navigation and reference.

## [Nov 13, 2023](/content/2023/11/13/README.md)

### Python / Trading & Backtesting

*   [hftbacktest (⭐3.8k)](https://github.com/nkaz001/hftbacktest) - A high-frequency trading and market-making backtesting tool accounts for limit orders, queue positions, and latencies, utilizing full tick data for trades and order books.

## [Oct 25, 2023](/content/2023/10/25/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [Quant-Finance-With-Python-Code (⭐168)](https://github.com/lingyixu/Quant-Finance-With-Python-Code) - Repo for code examples in Quantitative Finance with Python by Chris Kelliher

## [Oct 17, 2023](/content/2023/10/17/README.md)

### Python / Trading & Backtesting

*   [OctoBot Script (⭐39)](https://github.com/Drakkar-Software/OctoBot-Script) - A quant framework to create cryptocurrencies strategies - from backtesting to optimization to livetrading.

### Reproducing Works, Training & Books / Data Visualization

*   [MesoSim Options Trading Strategy Library (⭐20)](https://github.com/deltaray-io/strategy-library) - Free and public Options Trading strategy library for MesoSim.

## [Sep 21, 2023](/content/2023/09/21/README.md)

### Python / Financial Instruments and Pricing

*   [Kelly-Criterion (⭐110)](https://github.com/deltaray-io/kelly-criterion) - Kelly Criterion implemented in Python to size portfolios based on J. L. Kelly Jr's formula.

### Python / Trading & Backtesting

*   [QSTrader (⭐3.3k)](https://github.com/mhallsmoore/qstrader) - QSTrader backtesting simulation engine.

## [Aug 14, 2023](/content/2023/08/14/README.md)

### Python / Numerical Libraries & Data Structures

*   [modelx](https://docs.modelx.io/) - Python reimagination of spreadsheets as formula-centric objects that are interoperable with pandas.

### Python / Financial Instruments and Pricing

*   [OpenBB Terminal (⭐63k)](https://github.com/OpenBB-finance/OpenBBTerminal) - Terminal for investment research for everyone.
*   [pypme (⭐13)](https://github.com/ymyke/pypme) - PME (Public Market Equivalent) calculation.
*   [AbsBox (⭐64)](https://github.com/yellowbean/AbsBox) - A Python based library to model cashflow for structured product like Asset-backed securities (ABS) and Mortgage-backed securities (MBS).
*   [Intrinsic-Value-Calculator (⭐83)](https://github.com/akashaero/Intrinsic-Value-Calculator) - A Python tool for quick calculations of a stock's fair value using Discounted Cash Flow analysis.

### Python / Trading & Backtesting

*   [basana (⭐820)](https://github.com/gbeced/basana) - A Python async and event driven framework for algorithmic trading, with a focus on crypto currencies.
*   [pysystemtrade (⭐3.2k)](https://github.com/robcarver17/pysystemtrade) - pysystemtrade is the open source version of Robert Carver's backtesting and trading engine that implements systems according to the framework outlined in his book "Systematic Trading", which is further developed on his [blog](https://qoppac.blogspot.com/).
*   [pytrendseries (⭐163)](https://github.com/rafa-rod/pytrendseries) - Detect trend in time series, drawdown, drawdown within a constant look-back window , maximum drawdown, time underwater.
*   [PyLOB (⭐198)](https://github.com/DrAshBooth/PyLOB) - Fully functioning fast Limit Order Book written in Python.
*   [PyBroker (⭐3.2k)](https://github.com/edtechre/pybroker) - Algorithmic Trading with Machine Learning.

### Python / Data Sources

*   [market-prices (⭐95)](https://github.com/maread99/market_prices) - Create meaningful OHLCV datasets from knowledge of [exchange-calendars (⭐607)](https://github.com/gerrymanoim/exchange_calendars) (works out-the-box with data from Yahoo Finance).
*   [tardis-python (⭐140)](https://github.com/tardis-dev/tardis-python) - Python interface for Tardis.dev high frequency crypto market data
*   [lake-api (⭐63)](https://github.com/crypto-lake/lake-api) - Python interface for Crypto Lake high frequency crypto market data
*   [tessa (⭐53)](https://github.com/ymyke/tessa) - simple, hassle-free access to price information of financial assets (currently based on yfinance and pycoingecko), including search and a symbol class.
*   [pandaSDMX (⭐133)](https://github.com/dr-leo/pandaSDMX) - Python package that implements SDMX 2.1 (ISO 17369:2013), a format for exchange of statistical data and metadata used by national statistical agencies, central banks, and international organisations.
*   [cif (⭐64)](https://github.com/LenkaV/CIF) - Python package that include few composite indicators, which summarize multidimensional relationships between individual economic indicators.
*   [finagg (⭐525)](https://github.com/theOGognf/finagg) - finagg is a Python package that provides implementations of popular and free financial APIs, tools for aggregating historical data from those APIs into SQL databases, and tools for transforming aggregated data into features useful for analysis and AI/ML.

### Python / Visualization

*   [market-analy (⭐75)](https://github.com/maread99/market_analy) - Analysis and interactive charting using [market-prices (⭐95)](https://github.com/maread99/market_prices) and bqplot.

### R / Data Sources

*   [rb3 (⭐91)](https://github.com/ropensci/rb3) - A bunch of downloaders and parsers for data delivered from B3.
*   [simfinapi (⭐21)](https://github.com/matthiasgomolka/simfinapi) - Makes 'SimFin' data (<https://simfin.com/>) easily accessible in R.

### Julia / FrameWorks

*   [DataFrames.jl (⭐1.8k)](https://github.com/JuliaData/DataFrames.jl) - In-memory tabular data in Julia
*   [TSFrames.jl (⭐100)](https://github.com/xKDR/TSFrames.jl) - Handle timeseries data on top of the powerful and mature DataFrames.jl

### JavaScript / FrameWorks

*   [PENDAX (⭐48)](https://github.com/CompendiumFi/PENDAX-SDK) - Javascript SDK for Trading/Data API and Websockets for FTX, FTXUS, OKX, Bybit, & More.

### Rust / Data Visualization

*   [Barter (⭐2k)](https://github.com/barter-rs/barter-rs) - Open-source Rust framework for building event-driven live-trading & backtesting systems
*   [LFEST (⭐77)](https://github.com/MathisWellmann/lfest-rs) - Simulated perpetual futures exchange to trade your strategy against.
*   [TradeAggregation (⭐114)](https://github.com/MathisWellmann/trade_aggregation-rs) - Aggregate trades into user-defined candles using information driven rules.
*   [SlidingFeatures (⭐72)](https://github.com/MathisWellmann/sliding_features-rs) - Chainable tree-like sliding windows for signal processing and technical analysis.
*   [RustQuant (⭐1.7k)](https://github.com/avhz/RustQuant) - Quantitative finance library written in Rust.

### Reproducing Works, Training & Books / Data Visualization

*   [Value Investing Studies (⭐92)](https://github.com/euclidjda/value-investing-studies) - A collection of data analysis studies that examine the performance and characteristics of value investing over long periods of time.
*   [Machine Learning Asset Management (⭐1.7k)](https://github.com/firmai/machine-learning-asset-management) - Machine Learning in Asset Management (by @firmai).
*   [Deep Learning Machine Learning Stock (⭐1.7k)](https://github.com/LastAncientOne/Deep-Learning-Machine-Learning-Stock) - Deep Learning and Machine Learning stocks represent a promising long-term or short-term opportunity for investors and traders.
*   [Technical Analysis and Feature Engineering (⭐198)](https://github.com/jo-cho/Technical_Analysis_and_Feature_Engineering) - Feature Engineering and Feature Importance of Machine Learning in Financial Market.
*   [Differential Machine Learning and Axes that matter by Brian Huge and Antoine Savine (⭐148)](https://github.com/differential-machine-learning/notebooks) - Implement, demonstrate, reproduce and extend the results of the Risk articles 'Differential Machine Learning' (2020) and 'PCA with a Difference' (2021) by Huge and Savine, and cover implementation details left out from the papers.
*   [systematictradingexamples (⭐461)](https://github.com/robcarver17/systematictradingexamples) - Examples of code related to book [Systematic Trading](https://github.com/wilsonfreitas/awesome-quant/blob/master/README.md/www.systematictrading.org) and [blog](http://qoppac.blogspot.com)
*   [pysystemtrade\_examples (⭐259)](https://github.com/robcarver17/pysystemtrade_examples) - Examples using pysystemtrade for Robert Carver's [blog](http://qoppac.blogspot.com).
*   [ML\_Finance\_Codes (⭐2.5k)](https://github.com/mfrdixon/ML_Finance_Codes) - Machine Learning in Finance: From Theory to Practice Book
*   [Hands-On Machine Learning for Algorithmic Trading (⭐1.8k)](https://github.com/packtpublishing/hands-on-machine-learning-for-algorithmic-trading) - Hands-On Machine Learning for Algorithmic Trading, published by Packt
*   [financialnoob-misc (⭐28)](https://github.com/financialnoob/misc) - Codes from @financialnoob's posts

## [Jul 23, 2023](/content/2023/07/23/README.md)

### Python / Trading & Backtesting

*   [pythalesians (⭐63)](https://github.com/thalesians/pythalesians) - Python library to backtest trading strategies, plot charts, seamlessly download market data, analyze market patterns etc.

## [May 12, 2022](/content/2022/05/12/README.md)

### JavaScript / FrameWorks

*   [ccxt (⭐41k)](https://github.com/ccxt/ccxt) - A JavaScript / Python / PHP cryptocurrency trading API with support for more than 100 bitcoin/altcoin exchanges.

## [Apr 03, 2022](/content/2022/04/03/README.md)

### Python / Time Series

*   [gluon-ts (⭐5.1k)](https://github.com/awslabs/gluon-ts) - vProbabilistic time series modeling in Python.

## [Mar 28, 2022](/content/2022/03/28/README.md)

### Python / Trading & Backtesting

*   [TA-Lib (⭐12k)](https://github.com/mrjbq7/ta-lib) - Python wrapper for TA-Lib (<http://ta-lib.org/>).
*   [zipline (⭐19k)](https://github.com/quantopian/zipline) - Pythonic algorithmic trading library.

### Python / Data Sources

*   [pystlouisfed (⭐21)](https://github.com/TomasKoutek/pystlouisfed) - Python client for Federal Reserve Bank of St. Louis API - FRED, ALFRED, GeoFRED and FRASER.
*   [python-bcb (⭐109)](https://github.com/wilsonfreitas/python-bcb) - Python interface to Brazilian Central Bank web services.

### R / Numerical Libraries & Data Structures

*   [xts (⭐222)](https://github.com/joshuaulrich/xts) - eXtensible Time Series: Provide for uniform handling of R's different time-based data classes by extending zoo, maximizing native format information preservation and allowing for user level customization and extension, while simplifying cross-class interoperability.
*   [data.table (⭐3.9k)](https://github.com/Rdatatable/data.table) - Extension of data.frame: Fast aggregation of large data (e.g. 100GB in RAM), fast ordered joins, fast add/modify/delete of columns by group using no copies at all, list columns and a fast file reader (fread). Offers a natural and flexible syntax, for faster development.

### R / Data Sources

*   [Rblpapi (⭐175)](https://github.com/Rblp/Rblpapi) - An R Interface to 'Bloomberg' is provided via the 'Blp API'.
*   [Rbitcoin (⭐57)](https://github.com/jangorecki/Rbitcoin) - Unified markets API interface (bitstamp, kraken, btce, bitmarket).
*   [GetTDData (⭐26)](https://github.com/msperlin/GetTDData) - Downloads and aggregates data for Brazilian government issued bonds directly from the website of Tesouro Direto.
*   [GetHFData (⭐41)](https://github.com/msperlin/GetHFData) - Downloads and aggregates high frequency trading data for Brazilian instruments directly from Bovespa ftp site.
*   [Reddit WallstreetBets API](https://dashboard.nbshare.io/apps/reddit/api/) - Provides daily top 50 stocks from reddit (subreddit) Wallstreetbets and their sentiments via the API.
*   [td (⭐18)](https://github.com/eddelbuettel/td) - Interfaces the 'twelvedata' API for stocks and (digital and standard) currencies.
*   [rbcb (⭐99)](https://github.com/wilsonfreitas/rbcb) - R interface to Brazilian Central Bank web services.

### R / Financial Instruments and Pricing

*   [portfolio (⭐17)](https://github.com/dgerlanc/portfolio) - Analysing equity portfolios.
*   [credule (⭐7)](https://github.com/blenezet/credule) - Credit Default Swap Functions.
*   [PortfolioAnalytics (⭐98)](https://github.com/braverock/PortfolioAnalytics) - Portfolio Analysis, Including Numerical Methods for Optimizationof Portfolios.
*   [fmbasics (⭐12)](https://github.com/imanuelcostigan/fmbasics) - Financial Market Building Blocks.
*   [R-fixedincome (⭐64)](https://github.com/wilsonfreitas/R-fixedincome) - Fixed income tools for R.

### R / Trading

*   [TTR (⭐342)](https://github.com/joshuaulrich/TTR) - Technical Trading Rules.

### R / Risk Analysis

*   [PerformanceAnalytics (⭐235)](https://github.com/braverock/PerformanceAnalytics) - Econometric tools for performance and risk analysis.

### R / Time Series

*   [rugarch (⭐31)](https://github.com/alexiosg/rugarch) - Univariate GARCH Models.
*   [rmgarch (⭐17)](https://github.com/alexiosg/rmgarch) - Multivariate GARCH Models.

### R / Calendars

*   [bizdays (⭐57)](https://github.com/wilsonfreitas/R-bizdays) - Business days calculations and utilities

### Julia / FrameWorks

*   [Miletus.jl (⭐90)](https://github.com/JuliaComputing/Miletus.jl) - A financial contract definition, modeling language, and valuation framework.

### Reproducing Works, Training & Books / Data Visualization

*   [Machine-Learning-for-Asset-Managers (⭐615)](https://github.com/emoen/Machine-Learning-for-Asset-Managers) - Implementation of code snippets, exercises and application to live data from Machine Learning for Asset Managers (Elements in Quantitative Finance) written by Prof. Marcos López de Prado.

## [Mar 27, 2022](/content/2022/03/27/README.md)

### Python / Financial Instruments and Pricing

*   [Q-Fin (⭐582)](https://github.com/RomanMichaelPaolucci/Q-Fin) - A Python library for mathematical finance.
*   [Quantsbin (⭐612)](https://github.com/quantsbin/Quantsbin) - Tools for pricing and plotting of vanilla option prices, greeks and various other analysis around them.

### Python / Trading & Backtesting

*   [TuneTA (⭐457)](https://github.com/jmrichardson/tuneta) - TuneTA optimizes technical indicators using a distance correlation measure to a user defined target feature such as next day return.
*   [AutoTrader (⭐1.2k)](https://github.com/kieran-mackle/AutoTrader) - A Python-based development platform for automated trading systems - from backtesting to optimization to livetrading.
*   [qf-lib (⭐902)](https://github.com/quarkfin/qf-lib) - QF-Lib is a Python library that provides high quality tools for quantitative finance.

### JavaScript / Data Visualization

*   [QUANTAXIS\_Webkit (⭐37)](https://github.com/yutiansut/QUANTAXIS_Webkit) - An awesome visualization center based on quantaxis.

### Scala / Data Visualization

*   [Scala Quant (⭐10)](https://github.com/frankcash/Scala-Quant) - Scala library for working with stock data from IFTTT recipes or Google Finance.

### Reproducing Works, Training & Books / Data Visualization

*   [QuantFinance (⭐605)](https://github.com/PythonCharmers/QuantFinance) - Training materials in quantitative finance.
*   [IPythonScripts (⭐175)](https://github.com/mgroncki/IPythonScripts) - Tutorials about Quantitative Finance in Python and QuantLib: Pricing, xVAs, Hedging, Portfolio Optimisation, Machine Learning and Deep Learning.
*   [Computational-Finance-Course (⭐490)](https://github.com/LechGrzelak/Computational-Finance-Course) - Materials for the course of Computational Finance.

## [Mar 11, 2022](/content/2022/03/11/README.md)

### Python / Financial Instruments and Pricing

*   [pynance (⭐439)](https://github.com/GriffinAustin/pynance) - Lightweight Python library for assembling and analyzing financial data.

## [Feb 24, 2022](/content/2022/02/24/README.md)

### Python / Trading & Backtesting

*   [fast-trade (⭐532)](https://github.com/jrmeier/fast-trade) - Low code backtesting library utilizing pandas and technical analysis indicators.
*   [Lean (⭐18k)](https://github.com/QuantConnect/Lean) - Lean Algorithmic Trading Engine by QuantConnect (Python, C#).

### Java / FrameWorks

*   [ta4j (⭐2.4k)](https://github.com/ta4j/ta4j) - A Java library for technical analysis.

### Haskell / Data Visualization

*   [Haxcel (⭐37)](https://github.com/MarcusRainbow/Haxcel) - Excel Addin for Haskell.
*   [Ffinar (⭐5)](https://github.com/MarcusRainbow/Ffinar) - A financial maths library in Haskell.

## [Feb 04, 2022](/content/2022/02/04/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [rough\_bergomi (⭐141)](https://github.com/ryanmccrickerd/rough_bergomi) - A Python implementation of the rough Bergomi model.
*   [frh-fx (⭐13)](https://github.com/ryanmccrickerd/frh-fx) - A python implementation of the fast-reversion Heston model of Mechkov for FX purposes.

## [Jan 27, 2022](/content/2022/01/27/README.md)

### Frameworks / Data Visualization

*   [Portfolio Optimizer](https://portfoliooptimizer.io/) - Portfolio Optimizer is a Web API for portfolio analysis and optimization.

## [Jan 23, 2022](/content/2022/01/23/README.md)

### Python / Trading & Backtesting

*   [Blankly (⭐2.4k)](https://github.com/Blankly-Finance/Blankly) - Fully integrated backtesting, paper trading, and live deployment.

## [Jan 12, 2022](/content/2022/01/12/README.md)

### JavaScript / FrameWorks

*   [IndicatorTS (⭐429)](https://github.com/cinar/indicatorts) - Indicator is a TypeScript module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.

### Golang / Data Visualization

*   [IndicatorGo (⭐828)](https://github.com/cinar/indicator) - IndicatorGo is a Golang module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.

## [Jan 02, 2022](/content/2022/01/02/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [QuantFinanceBook (⭐857)](https://github.com/LechGrzelak/QuantFinanceBook) - Quantitative Finance book.

## [Dec 31, 2021](/content/2021/12/31/README.md)

### Python / Trading & Backtesting

*   [tda-api (⭐1.3k)](https://github.com/alexgolec/tda-api) - Gather data and trade equities, options, and ETFs via TDAmeritrade.
*   [vectorbt (⭐6.9k)](https://github.com/polakowo/vectorbt) - Find your trading edge, using a powerful toolkit for backtesting, algorithmic trading, and research.

## [Dec 27, 2021](/content/2021/12/27/README.md)

### Python / Financial Instruments and Pricing

*   [finoptions (⭐295)](https://github.com/bbcho/finoptions-dev) - Complete python implementation of R package fOptions with partial implementation of fExoticOptions for pricing various options.

## [Dec 23, 2021](/content/2021/12/23/README.md)

### Python / Risk Analysis

*   [Riskfolio-Lib (⭐3.8k)](https://github.com/dcajasn/Riskfolio-Lib) - Portfolio Optimization and Quantitative Strategic Asset Allocation in Python.

## [Dec 17, 2021](/content/2021/12/17/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [ML-Quant](https://www.ml-quant.com/) - Top Quant resources like ArXiv (sanity), SSRN, RePec, Journals, Podcasts, Videos, and Blogs.
*   [py4fi2nd (⭐2.1k)](https://github.com/yhilpisch/py4fi2nd) - Jupyter Notebooks and code for Python for Finance (2nd ed., O'Reilly) by Yves Hilpisch.
*   [aiif (⭐385)](https://github.com/yhilpisch/aiif) - Jupyter Notebooks and code for the book Artificial Intelligence in Finance (O'Reilly) by Yves Hilpisch.
*   [py4at (⭐826)](https://github.com/yhilpisch/py4at) - Jupyter Notebooks and code for the book Python for Algorithmic Trading (O'Reilly) by Yves Hilpisch.
*   [dawp (⭐633)](https://github.com/yhilpisch/dawp) - Jupyter Notebooks and code for Derivatives Analytics with Python (Wiley Finance) by Yves Hilpisch.
*   [dx (⭐767)](https://github.com/yhilpisch/dx) - DX Analytics | Financial and Derivatives Analytics with Python.

## [Dec 09, 2021](/content/2021/12/09/README.md)

### Python / Time Series

*   [pmdarima (⭐1.7k)](https://github.com/alkaline-ml/pmdarima) - A statistical library designed to fill the void in Python's time series analysis capabilities, including the equivalent of R's auto.arima function.

## [Oct 26, 2021](/content/2021/10/26/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [NMOF (⭐38)](https://github.com/enricoschumann/NMOF) - Functions, examples and data from the first and the second edition of "Numerical Methods and Optimization in Finance" by M. Gilli, D. Maringer and E. Schumann (2019, ISBN:978-0128150658).

## [Oct 24, 2021](/content/2021/10/24/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [modelos\_vol\_derivativos (⭐59)](https://github.com/ysaporito/modelos_vol_derivativos) - "Modelos de Volatilidade para Derivativos" book's Jupyter notebooks

## [Oct 19, 2021](/content/2021/10/19/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [Python-for-Finance-Cookbook (⭐784)](https://github.com/PacktPublishing/Python-for-Finance-Cookbook) - Python for Finance Cookbook, published by Packt.

## [Sep 09, 2021](/content/2021/09/09/README.md)

### Elixir/Erlang / Data Visualization

*   [Prop (⭐55)](https://github.com/fremantle-industries/prop) - An open and opinionated trading platform using productive & familiar open source libraries and tools for strategy research, execution and operation.

## [Jul 26, 2021](/content/2021/07/26/README.md)

### JavaScript / FrameWorks

*   [Ghostfolio (⭐7.9k)](https://github.com/ghostfolio/ghostfolio) - Wealth management software to keep track of financial assets like stocks, ETFs or cryptocurrencies and make solid, data-driven investment decisions.

## [Jul 01, 2021](/content/2021/07/01/README.md)

### Python / Risk Analysis

*   [risktools (⭐38)](https://github.com/bbcho/risktools-dev) - Risk tools for use within the crude and crude products trading space with partial implementation of R's PerformanceAnalytics.

## [Jun 17, 2021](/content/2021/06/17/README.md)

### JavaScript / FrameWorks

*   [portfolio-allocation (⭐187)](https://github.com/lequant40/portfolio_allocation_js) - PortfolioAllocation is a JavaScript library designed to help constructing financial portfolios made of several assets: bonds, commodities, cryptocurrencies, currencies, exchange traded funds (ETFs), mutual funds, stocks...

## [Jun 02, 2021](/content/2021/06/02/README.md)

### Python / Risk Analysis

*   [Empyrial (⭐1.1k)](https://github.com/ssantoshp/Empyrial) - Portfolio's risk and performance analytics and returns predictions.

## [Jun 01, 2021](/content/2021/06/01/README.md)

### Python / Calendars

*   [exchange\_calendars (⭐607)](https://github.com/gerrymanoim/exchange_calendars) - Stock Exchange Trading Calendars.

## [May 30, 2021](/content/2021/05/30/README.md)

### Python / Indicators

*   [Tulipy (⭐92)](https://github.com/cirla/tulipy) - Financial Technical Analysis Indicator Library (Python bindings for [tulipindicators (⭐943)](https://github.com/TulipCharts/tulipindicators))

### Python / Trading & Backtesting

*   [qtpylib (⭐2.3k)](https://github.com/ranaroussi/qtpylib) - QTPyLib, Pythonic Algorithmic Trading <http://qtpylib.io>
*   [Qlib (⭐39k)](https://github.com/microsoft/qlib) - An AI-oriented Quantitative Investment Platform by Microsoft. Full ML pipeline of data processing, model training, back-testing; and covers the entire chain of quantitative investment: alpha seeking, risk modeling, portfolio optimization, and order execution.

### Python / Time Series

*   [tsmoothie (⭐769)](https://github.com/cerlymarco/tsmoothie) - A python library for time-series smoothing and outlier detection in a vectorized way.

### Python / Data Sources

*   [FinanceDataReader (⭐1.4k)](https://github.com/FinanceData/FinanceDataReader) - Open Source Financial data reader for U.S, Korean, Japanese, Chinese, Vietnamese Stocks

### R / Financial Instruments and Pricing

*   [Rmetrics](https://www.rmetrics.org) - The premier open source software solution for teaching and training quantitative finance.
    *   [fAsianOptions](https://cran.r-project.org/web/packages/fAsianOptions/index.html) - EBM and Asian Option Valuation.
    *   [fAssets](https://cran.r-project.org/web/packages/fAssets/index.html) - Analysing and Modelling Financial Assets.
    *   [fBasics](https://cran.r-project.org/web/packages/fBasics/index.html) - Markets and Basic Statistics.
    *   [fBonds](https://cran.r-project.org/web/packages/fBonds/index.html) - Bonds and Interest Rate Models.
    *   [fExoticOptions](https://cran.r-project.org/web/packages/fExoticOptions/index.html) - Exotic Option Valuation.
    *   [fOptions](https://cran.r-project.org/web/packages/fOptions/index.html) - Pricing and Evaluating Basic Options.
    *   [fPortfolio](https://cran.r-project.org/web/packages/fPortfolio/index.html) - Portfolio Selection and Optimization.

### Reproducing Works, Training & Books / Data Visualization

*   [MEDIUM\_NoteBook (⭐2.1k)](https://github.com/cerlymarco/MEDIUM_NoteBook) - Repository containing notebooks of [cerlymarco](https://github.com/cerlymarco)'s posts on Medium.

## [May 29, 2021](/content/2021/05/29/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [algorithmic-trading-with-python (⭐3.3k)](https://github.com/chrisconlan/algorithmic-trading-with-python) - Source code for Algorithmic Trading with Python (2020) by Chris Conlan.

### CPP / Data Visualization

*   [TradeFrame (⭐651)](https://github.com/rburkholder/trade-frame) - C++ 17 based framework/library (with sample applications) for testing options based automated trading ideas using DTN IQ real time data feed and Interactive Brokers (TWS API) for trade execution. Comes with built-in [Option Greeks/IV (⭐651)](https://github.com/rburkholder/trade-frame/tree/master/lib/TFOptions) calculation library.

## [May 27, 2021](/content/2021/05/27/README.md)

### R / Trading

*   [blotter (⭐118)](https://github.com/braverock/blotter) - Transaction infrastructure for defining instruments, transactions, portfolios and accounts for trading systems and simulation. Provides portfolio support for multi-asset class and multi-currency portfolios. Actively maintained and developed.

### R / Factor Analysis

*   [FactorAnalytics (⭐85)](https://github.com/braverock/FactorAnalytics) - The FactorAnalytics package contains fitting and analysis methods for the three main types of factor models used in conjunction with portfolio construction, optimization and risk management, namely fundamental factor models, time series factor models and statistical factor models.
*   [Expected Returns (⭐56)](https://github.com/JustinMShea/ExpectedReturns) - Solutions for enhancing portfolio diversification and replications of seminal papers with R, most of which are discussed in one of the best investment references of the recent decade, Expected Returns: An Investors Guide to Harvesting Market Rewards by Antti Ilmanen.

### CSharp / Data Visualization

*   [TDAmeritrade.DotNetCore (⭐56)](https://github.com/NVentimiglia/TDAmeritrade.DotNetCore) - Free, open-source .NET Client for the TD Ameritrade Trading Platform. Helps developers integrate TD Ameritrade API into custom trading solutions.

## [May 26, 2021](/content/2021/05/26/README.md)

### Python / Indicators

*   [lppls (⭐449)](https://github.com/Boulder-Investment-Technologies/lppls) - A Python module for fitting the [Log-Periodic Power Law Singularity (LPPLS)](https://en.wikipedia.org/wiki/Didier_Sornette#The_JLS_and_LPPLS_models) model.

### R / Backtesting

*   [quantstrat (⭐301)](https://github.com/braverock/quantstrat) - Transaction-oriented infrastructure for constructing trading systems and simulation. Provides support for multi-asset class and multi-currency portfolios for backtesting and other financial research.

## [May 06, 2021](/content/2021/05/06/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [Stock\_Analysis\_For\_Quant (⭐2k)](https://github.com/LastAncientOne/Stock_Analysis_For_Quant) - Different Types of Stock Analysis in Excel, Matlab, Power BI, Python, R, and Tableau.

## [May 05, 2021](/content/2021/05/05/README.md)

### Python / Trading & Backtesting

*   [Eiten (⭐3.2k)](https://github.com/tradytics/eiten) - Eiten is an open source toolkit by Tradytics that implements various statistical and algorithmic investing strategies such as Eigen Portfolios, Minimum Variance Portfolios, Maximum Sharpe Ratio Portfolios, and Genetic Algorithms based Portfolios.
*   [Stock-Prediction-Models (⭐9.2k)](https://github.com/huseinzol05/Stock-Prediction-Models) - Gathers machine learning and deep learning models for Stock forecasting including trading bots and simulations.

## [Apr 21, 2021](/content/2021/04/21/README.md)

### Python / Visualization

*   [finvizfinance (⭐1.3k)](https://github.com/lit26/finvizfinance) - Finviz analysis python library.

### Golang / Data Visualization

*   [marketstore](https://github.com/alpacahq/marketstore) - DataFrame Server for Financial Timeseries Data.

## [Apr 20, 2021](/content/2021/04/20/README.md)

### R / Time Series

*   [garchmodels (⭐35)](https://github.com/AlbertoAlmuinha/garchmodels) - A parsnip backend for GARCH models.

## [Apr 16, 2021](/content/2021/04/16/README.md)

### Python / Trading & Backtesting

*   [bta-lib (⭐492)](https://github.com/mementum/bta-lib) - Technical Analysis library in pandas for backtesting algotrading and quantitative analysis.

## [Apr 14, 2021](/content/2021/04/14/README.md)

### Python / Visualization

*   [finplot (⭐1.1k)](https://github.com/highfestiva/finplot) - Performant and effortless finance plotting for Python.

## [Apr 12, 2021](/content/2021/04/12/README.md)

### Python / Financial Instruments and Pricing

*   [tf-quant-finance (⭐5.3k)](https://github.com/google/tf-quant-finance) - High-performance TensorFlow library for quantitative finance.

### Python / Trading & Backtesting

*   [rqalpha (⭐6.2k)](https://github.com/ricequant/rqalpha) - A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities.
*   [FinRL-Library (⭐14k)](https://github.com/AI4Finance-LLC/FinRL-Library) - A Deep Reinforcement Learning Library for Automated Trading in Quantitative Finance. NeurIPS 2020.
*   [bulbea (⭐2.3k)](https://github.com/achillesrasquinha/bulbea) - Deep Learning based Python Library for Stock Market Prediction and Modelling.
*   [ib\_nope (⭐33)](https://github.com/ajhpark/ib_nope) - Automated trading system for NOPE strategy over IBKR TWS.
*   [OctoBot (⭐5.4k)](https://github.com/Drakkar-Software/OctoBot) - Open source cryptocurrency trading bot for high frequency, arbitrage, TA and social trading with an advanced web interface.

### Python / Risk Analysis

*   [universal-portfolios (⭐850)](https://github.com/Marigold/universal-portfolios) - Collection of algorithms for online portfolio selection.
*   [FinQuant (⭐1.7k)](https://github.com/fmilthaler/FinQuant) - A program for financial portfolio management, analysis and optimization.

### Python / Data Sources

*   [alpha\_vantage (⭐4.7k)](https://github.com/RomelTorres/alpha_vantage) - A python wrapper for Alpha Vantage API for financial data.

### JavaScript / FrameWorks

*   [finance.js (⭐1.3k)](https://github.com/ebradyjobory/finance.js) - A JavaScript library for common financial calculations.

### CSharp / Data Visualization

*   [StockSharp (⭐9.3k)](https://github.com/StockSharp/StockSharp) - Algorithmic trading and quantitative trading open source platform to develop trading robots (stock markets, forex, crypto, bitcoins, and options).

### Reproducing Works, Training & Books / Data Visualization

*   [python-training (⭐13k)](https://github.com/jpmorganchase/python-training) - J.P. Morgan's Python training for business analysts and traders.

## [Apr 10, 2021](/content/2021/04/10/README.md)

### Python / Trading & Backtesting

*   [AlphaPy (⭐1.7k)](https://github.com/ScottfreeLLC/AlphaPy) - Automated Machine Learning \[AutoML] with Python, scikit-learn, Keras, XGBoost, LightGBM, and CatBoost
*   [jesse (⭐7.6k)](https://github.com/jesse-ai/jesse) - An advanced crypto trading bot written in Python

### Python / Time Series

*   [Facebook Prophet (⭐20k)](https://github.com/facebook/prophet) - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.

### Rust / Data Visualization

*   [QuantMath (⭐401)](https://github.com/MarcusRainbow/QuantMath) - Financial maths library for risk-neutral pricing and risk

## [Apr 05, 2021](/content/2021/04/05/README.md)

### Python / Data Sources

*   [yfinance (⭐22k)](https://github.com/ranaroussi/yfinance) - Yahoo! Finance market data downloader (+faster Pandas Datareader)

## [Mar 18, 2021](/content/2021/03/18/README.md)

### Python / Financial Instruments and Pricing

*   [willowtree (⭐344)](https://github.com/federicomariamassari/willowtree) - Robust and flexible Python implementation of the willow tree lattice for derivatives pricing.
*   [financial-engineering (⭐500)](https://github.com/federicomariamassari/financial-engineering) - Applications of Monte Carlo methods to financial engineering projects, in Python.
*   [optlib (⭐1.3k)](https://github.com/dbrojas/optlib) - A library for financial options pricing written in Python.

### Reproducing Works, Training & Books / Data Visualization

*   [FinanceHub (⭐781)](https://github.com/Finance-Hub/FinanceHub) - Resources for Quantitative Finance
*   [Python\_Option\_Pricing (⭐828)](https://github.com/dedwards25/Python_Option_Pricing) - An library to price financial options written in Python. Includes: Black Scholes, Black 76, Implied Volatility, American, European, Asian, Spread Options.

## [Feb 23, 2021](/content/2021/02/23/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [QuantEcon](https://quantecon.org/) - Lecture series on economics, finance, econometrics and data science; QuantEcon.py, QuantEcon.jl, notebooks

## [Feb 08, 2021](/content/2021/02/08/README.md)

### Python / Trading & Backtesting

*   [machine-learning-for-trading (⭐17k)](https://github.com/stefan-jansen/machine-learning-for-trading) - Code and resources for Machine Learning for Algorithmic Trading

## [Jan 16, 2021](/content/2021/01/16/README.md)

### R / Time Series

*   [matrixprofile (⭐387)](https://github.com/matrix-profile-foundation/matrixprofile) - Time series data mining library built on top of the novel Matrix Profile data structure and algorithms.

## [Dec 10, 2020](/content/2020/12/10/README.md)

### Python / Visualization

*   [mplfinance (⭐4.3k)](https://github.com/matplotlib/mplfinance) - matplotlib utilities for the visualization, and visual analysis, of financial data.

## [Nov 03, 2020](/content/2020/11/03/README.md)

### Python / Factor Analysis

*   [Spectre (⭐784)](https://github.com/Heerozh/spectre) - GPU-accelerated Factors analysis library and Backtester

## [Oct 08, 2020](/content/2020/10/08/README.md)

### Python / Financial Instruments and Pricing

*   [gs-quant (⭐10k)](https://github.com/goldmansachs/gs-quant) - Python toolkit for quantitative finance

## [Sep 28, 2020](/content/2020/09/28/README.md)

### Python / Financial Instruments and Pricing

*   [FinancePy (⭐2.8k)](https://github.com/domokane/FinancePy) - A Python Finance Library that focuses on the pricing and risk-management of Financial Derivatives, including fixed-income, equity, FX and credit derivatives.

## [Sep 17, 2020](/content/2020/09/17/README.md)

### Python / Data Sources

*   [iexfinance (⭐650)](https://github.com/addisonlynch/iexfinance) - Python Interface for retrieving real-time and historical prices and equities data from The Investor's Exchange.
*   [pyEX (⭐409)](https://github.com/timkpaine/pyEX) - Python interface to IEX with emphasis on pandas, support for streaming data, premium data, points data (economic, rates, commodities), and technical indicators.

## [Aug 28, 2020](/content/2020/08/28/README.md)

### Python / Indicators

*   [finta (⭐2.2k)](https://github.com/peerchemist/finta) - Common financial technical analysis indicators implemented in Pandas.

## [Jul 23, 2020](/content/2020/07/23/README.md)

### Python / Data Sources

*   [bbgbridge (⭐2)](https://github.com/ran404/bbgbridge) - Easy to use Bloomberg Desktop API wrapper for Python.

## [Jun 14, 2020](/content/2020/06/14/README.md)

### Python / Data Sources

*   [yliveticker (⭐163)](https://github.com/yahoofinancelive/yliveticker) - Live stream of market data from Yahoo Finance websocket.

## [Jun 08, 2020](/content/2020/06/08/README.md)

### Python / Visualization

*   [D-Tale (⭐5.1k)](https://github.com/man-group/dtale) - Visualizer for pandas dataframes and xarray datasets.

## [Jun 07, 2020](/content/2020/06/07/README.md)

### Python / Trading & Backtesting

*   [DeepDow (⭐1.1k)](https://github.com/jankrepl/deepdow) - Portfolio optimization with deep learning

### Python / Data Sources

*   [investpy (⭐1.8k)](https://github.com/alvarobartt/investpy) - Financial Data Extraction from Investing.com with Python! <https://investpy.readthedocs.io/>

## [May 09, 2020](/content/2020/05/09/README.md)

### Golang / Data Visualization

*   [Kelp (⭐1.1k)](https://github.com/stellar/kelp) - Kelp is an open-source Golang algorithmic cryptocurrency trading bot that runs on centralized exchanges and Stellar DEX (command-line usage and desktop GUI).

## [May 03, 2020](/content/2020/05/03/README.md)

### Elixir/Erlang / Data Visualization

*   [Workbench (⭐121)](https://github.com/fremantle-industries/workbench) - From Idea to Execution - Manage your trading operation across a globally distributed cluster

## [Apr 03, 2020](/content/2020/04/03/README.md)

### Python / Trading & Backtesting

*   [freqtrade (⭐48k)](https://github.com/freqtrade/freqtrade) - Free, open source crypto trading bot

## [Mar 05, 2020](/content/2020/03/05/README.md)

### Python / Data Sources

*   [yahooquery (⭐900)](https://github.com/dpguthrie/yahooquery) - Python interface for retrieving data through unofficial Yahoo Finance API.

## [Mar 01, 2020](/content/2020/03/01/README.md)

### Python / Data Sources

*   [metatrader5](https://pypi.org/project/MetaTrader5/) - API Connector to MetaTrader 5 Terminal
*   [akshare (⭐17k)](https://github.com/jindaxiang/akshare) - AkShare is an elegant and simple financial data interface library for Python, built for human beings! <https://akshare.readthedocs.io>

## [Feb 25, 2020](/content/2020/02/25/README.md)

### Python / Trading & Backtesting

*   [quantstats (⭐6.9k)](https://github.com/ranaroussi/quantstats) - Portfolio analytics for quants, written in Python
*   [Quantdom (⭐761)](https://github.com/constverum/Quantdom) - Python-based framework for backtesting trading strategies & analyzing financial markets \[GUI :neckbeard:]

### Reproducing Works, Training & Books / Data Visualization

*   [Quantitative-Notebooks (⭐1.3k)](https://github.com/LongOnly/Quantitative-Notebooks) - Educational notebooks on quantitative finance, algorithmic trading, financial modelling and investment strategy

## [Feb 18, 2020](/content/2020/02/18/README.md)

### Python / Trading & Backtesting

*   [riskparity.py (⭐318)](https://github.com/dppalomar/riskparity.py) - fast and scalable design of risk parity portfolios with TensorFlow 2.0

## [Dec 30, 2019](/content/2019/12/30/README.md)

### Elixir/Erlang / Data Visualization

*   [Tai (⭐493)](https://github.com/fremantle-capital/tai) - Open Source composable, real time, market data and trade execution toolkit.

## [Jul 14, 2019](/content/2019/07/14/README.md)

### Python / Trading & Backtesting

*   [Backtesting.py](https://kernc.github.io/backtesting.py/) - Backtest trading strategies in Python

## [Jul 13, 2019](/content/2019/07/13/README.md)

### Python / Indicators

*   [pandas\_talib (⭐782)](https://github.com/femtotrader/pandas_talib) - A Python Pandas implementation of technical analysis indicators.

### Python / Trading & Backtesting

*   [ta (⭐4.9k)](https://github.com/bukosabino/ta) - Technical Analysis Library using Pandas (Python)
*   [pyqstrat (⭐371)](https://github.com/abbass2/pyqstrat) - A fast, extensible, transparent python library for backtesting quantitative strategies.
*   [NowTrade (⭐101)](https://github.com/edouardpoitras/NowTrade) - Python library for backtesting technical/mechanical strategies in the stock and currency markets.
*   [pinkfish (⭐293)](https://github.com/fja05680/pinkfish) - A backtester and spreadsheet library for security analysis.
*   [aat (⭐780)](https://github.com/timkpaine/aat) - Async Algorithmic Trading Engine
*   [catalyst (⭐2.6k)](https://github.com/enigmampc/catalyst) - An Algorithmic Trading Library for Crypto-Assets in Python

## [Jul 10, 2019](/content/2019/07/10/README.md)

### Java / FrameWorks

*   [Strata](http://strata.opengamma.io/) - Modern open-source analytics and market risk library designed and written in Java.

## [Jun 30, 2019](/content/2019/06/30/README.md)

### Python / Trading & Backtesting

*   [zvt (⭐4k)](https://github.com/zvtvz/zvt) - the project using sql, pandas to provide an uniform and extendable way to record data, computing factors, select securities, backtesting, realtime trading and it could show all of them in clearly charts in realtime.

## [May 18, 2019](/content/2019/05/18/README.md)

### Python / Trading & Backtesting

*   [mlfinlab (⭐4.6k)](https://github.com/hudson-and-thames/mlfinlab) - Implementations regarding "Advances in Financial Machine Learning" by Marcos Lopez de Prado. (Feature Engineering, Financial Data Structures, Meta-Labeling)

## [Apr 04, 2019](/content/2019/04/04/README.md)

### Python / Trading & Backtesting

*   [PyPortfolioOpt (⭐5.6k)](https://github.com/robertmartin8/PyPortfolioOpt) - Financial portfolio optimization in python, including classical efficient frontier and advanced methods.

## [Mar 05, 2019](/content/2019/03/05/README.md)

### Python / Numerical Libraries & Data Structures

*   [numpy](https://www.numpy.org) - NumPy is the fundamental package for scientific computing with Python.
*   [pandas](https://pandas.pydata.org) - pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
*   [quantdsl (⭐377)](https://github.com/johnbywater/quantdsl) - Domain specific language for quantitative analytics in finance and trading.
*   [statistics](https://docs.python.org/3/library/statistics.html) - Builtin Python library for all basic statistical calculations.
*   [sympy](https://www.sympy.org/) - SymPy is a Python library for symbolic mathematics.
*   [pymc3](https://docs.pymc.io/) - Probabilistic Programming in Python: Bayesian Modeling and Probabilistic Machine Learning with Theano.

### Python / Financial Instruments and Pricing

*   [PyQL (⭐1.3k)](https://github.com/enthought/pyql) - QuantLib's Python port.
*   [pyfin (⭐316)](https://github.com/opendoor-labs/pyfin) - Basic options pricing in Python. *ARCHIVED*
*   [QuantPy (⭐973)](https://github.com/jsmidt/QuantPy) - A framework for quantitative finance In python.
*   [Finance-Python (⭐873)](https://github.com/alpha-miner/Finance-Python) - Python tools for Finance.
*   [ffn (⭐2.5k)](https://github.com/pmorissette/ffn) - A financial function library for Python.
*   [tia (⭐430)](https://github.com/bpsmith/tia) - Toolkit for integration and analysis.
*   [hasura/base-python-dash](https://platform.hasura.io/hub/projects/hasura/base-python-dash) - Hasura quick start to deploy Dash framework. Written on top of Flask, Plotly.js, and React.js, Dash is ideal for building data visualization apps with highly custom user interfaces in pure Python.
*   [hasura/base-python-bokeh](https://platform.hasura.io/hub/projects/hasura/base-python-bokeh) - Hasura quick start to visualize data with bokeh library.
*   [pysabr (⭐591)](https://github.com/ynouri/pysabr) - SABR model Python implementation.

### Python / Trading & Backtesting

*   [QuantSoftware Toolkit (⭐476)](https://github.com/QuantSoftware/QuantSoftwareToolkit) - Python-based open source software framework designed to support portfolio construction and management.
*   [quantitative (⭐66)](https://github.com/jeffrey-liang/quantitative) - Quantitative finance, and backtesting library.
*   [analyzer (⭐214)](https://github.com/llazzaro/analyzer) - Python framework for real-time financial and backtesting trading strategies.
*   [bt (⭐2.8k)](https://github.com/pmorissette/bt) - Flexible Backtesting for Python.
*   [backtrader (⭐21k)](https://github.com/backtrader/backtrader) - Python Backtesting library for trading strategies.
*   [pyalgotrade (⭐4.6k)](https://github.com/gbeced/pyalgotrade) - Python Algorithmic Trading Library.
*   [tradingWithPython](https://pypi.org/project/tradingWithPython/) - A collection of functions and classes for Quantitative trading.
*   [algobroker (⭐97)](https://github.com/joequant/algobroker) - This is an execution engine for algo trading.
*   [pysentosa](https://pypi.org/project/pysentosa/) - Python API for sentosa trading system.
*   [finmarketpy (⭐3.7k)](https://github.com/cuemacro/finmarketpy) - Python library for backtesting trading strategies and analyzing financial markets.
*   [binary-martingale (⭐48)](https://github.com/metaperl/binary-martingale) - Computer program to automatically trade binary options martingale style.
*   [fooltrader (⭐1.2k)](https://github.com/foolcage/fooltrader) - the project using big-data technology to provide an uniform way to analyze the whole market.
*   [pylivetrader (⭐681)](https://github.com/alpacahq/pylivetrader) - zipline-compatible live trading library.
*   [pipeline-live (⭐206)](https://github.com/alpacahq/pipeline-live) - zipline's pipeline capability with IEX for live trading.
*   [zipline-extensions (⭐18)](https://github.com/quantrocket-llc/zipline-extensions) - Zipline extensions and adapters for QuantRocket.
*   [moonshot (⭐256)](https://github.com/quantrocket-llc/moonshot) - Vectorized backtester and trading engine for QuantRocket based on Pandas.

### Python / Risk Analysis

*   [pyfolio (⭐6.3k)](https://github.com/quantopian/pyfolio) - Portfolio and risk analytics in Python.
*   [empyrical (⭐1.5k)](https://github.com/quantopian/empyrical) - Common financial risk and performance metrics.
*   [finance](https://pypi.org/project/finance/) - Financial Risk Calculations. Optimized for ease of use through class construction and operator overload.
*   [qfrm](https://pypi.org/project/qfrm/) - Quantitative Financial Risk Management: awesome OOP tools for measuring, managing and visualizing risk of financial instruments and portfolios.
*   [visualize-wealth (⭐146)](https://github.com/benjaminmgross/visualize-wealth) - Portfolio construction and quantitative analysis.
*   [VisualPortfolio (⭐107)](https://github.com/wegamekinglc/VisualPortfolio) - This tool is used to visualize the performance of a portfolio.

### Python / Factor Analysis

*   [alphalens (⭐4.2k)](https://github.com/quantopian/alphalens) - Performance analysis of predictive alpha factors.

### Python / Time Series

*   [ARCH (⭐1.5k)](https://github.com/bashtage/arch) - ARCH models in Python.
*   [dynts (⭐87)](https://github.com/quantmind/dynts) - Python package for timeseries analysis and manipulation.
*   [PyFlux (⭐2.1k)](https://github.com/RJT1990/pyflux) - Python library for timeseries modelling and inference (frequentist and Bayesian) on models.
*   [tsfresh (⭐9.1k)](https://github.com/blue-yonder/tsfresh) - Automatic extraction of relevant features from time series.
*   [hasura/quandl-metabase](https://platform.hasura.io/hub/projects/anirudhm/quandl-metabase-time-series) - Hasura quickstart to visualize Quandl's timeseries datasets with Metabase.

### Python / Calendars

*   [bizdays (⭐89)](https://github.com/wilsonfreitas/python-bizdays) - Business days calculations and utilities.
*   [pandas\_market\_calendars (⭐958)](https://github.com/rsheftel/pandas_market_calendars) - Exchange calendars to use with pandas for trading applications.

### Python / Data Sources

*   [googlefinance (⭐818)](https://github.com/hongtaocai/googlefinance) - Python module to get real-time stock data from Google Finance API.
*   [yahoo-finance (⭐1.4k)](https://github.com/lukaszbanasiak/yahoo-finance) - Python module to get stock data from Yahoo! Finance.
*   [pandas-datareader (⭐3.2k)](https://github.com/pydata/pandas-datareader) - Python module to get data from various sources (Google Finance, Yahoo Finance, FRED, OECD, Fama/French, World Bank, Eurostat...) into Pandas datastructures such as DataFrame, Panel with a caching mechanism.
*   [pandas-finance (⭐160)](https://github.com/davidastephens/pandas-finance) - High level API for access to and analysis of financial data.
*   [pyhoofinance (⭐9)](https://github.com/innes213/pyhoofinance) - Rapidly queries Yahoo Finance for multiple tickers and returns typed data for analysis.
*   [yfinanceapi (⭐9)](https://github.com/Karthik005/yfinanceapi) - Finance API for Python.
*   [yql-finance (⭐16)](https://github.com/slawek87/yql-finance) - yql-finance is simple and fast. API returns stock closing prices for current period of time and current stock ticker (i.e. APPL, GOOGL).
*   [ystockquote (⭐537)](https://github.com/cgoldberg/ystockquote) - Retrieve stock quote data from Yahoo Finance.
*   [wallstreet (⭐1.6k)](https://github.com/mcdallas/wallstreet) - Real time stock and option data.
*   [stock\_extractor (⭐51)](https://github.com/ZachLiuGIS/stock_extractor) - General Purpose Stock Extractors from Online Resources.
*   [Stockex (⭐33)](https://github.com/cttn/Stockex) - Python wrapper for Yahoo! Finance API.
*   [finsymbols (⭐123)](https://github.com/skillachie/finsymbols) - Obtains stock symbols and relating information for SP500, AMEX, NYSE, and NASDAQ.
*   [FRB (⭐180)](https://github.com/avelkoski/FRB) - Python Client for FRED® API.
*   [inquisitor (⭐56)](https://github.com/econdb/inquisitor) - Python Interface to Econdb.com API.
*   [yfi (⭐2)](https://github.com/nickelkr/yfi) - Yahoo! YQL library.
*   [chinesestockapi](https://pypi.org/project/chinesestockapi/) - Python API to get Chinese stock price.
*   [exchange (⭐18)](https://github.com/akarat/exchange) - Get current exchange rate.
*   [ticks (⭐16)](https://github.com/jamescnowell/ticks) - Simple command line tool to get stock ticker data.
*   [pybbg (⭐53)](https://github.com/bpsmith/pybbg) - Python interface to Bloomberg COM APIs.
*   [ccy (⭐95)](https://github.com/lsbardel/ccy) - Python module for currencies.
*   [tushare](https://pypi.org/project/tushare/) - A utility for crawling historical and Real-time Quotes data of China stocks.
*   [jsm](https://pypi.org/project/jsm/) - Get the japanese stock market data.
*   [cn\_stock\_src (⭐34)](https://github.com/jealous/cn_stock_src) - Utility for retrieving basic China stock data from different sources.
*   [coinmarketcap (⭐435)](https://github.com/barnumbirr/coinmarketcap) - Python API for coinmarketcap.
*   [after-hours (⭐38)](https://github.com/datawrestler/after-hours) - Obtain pre market and after hours stock prices for a given symbol.
*   [bronto-python](https://pypi.org/project/bronto-python/) - Bronto API Integration for Python.
*   [pytdx (⭐1.5k)](https://github.com/rainx/pytdx) - Python Interface for retrieving chinese stock realtime quote data from TongDaXin Nodes.
*   [pdblp (⭐255)](https://github.com/matthewgilbert/pdblp) - A simple interface to integrate pandas and the Bloomberg Open API.
*   [tiingo (⭐303)](https://github.com/hydrosquall/tiingo-python) - Python interface for daily composite prices/OHLC/Volume + Real-time News Feeds, powered by the Tiingo Data Platform.
*   [alpaca-trade-api (⭐1.9k)](https://github.com/alpacahq/alpaca-trade-api-python) - Python interface for retrieving real-time and historical prices from Alpaca API as well as trade execution.

### Python / Excel Integration

*   [xlwings](https://www.xlwings.org/) - Make Excel fly with Python.
*   [openpyxl](https://openpyxl.readthedocs.io/en/latest/) - Read/Write Excel 2007 xlsx/xlsm files.
*   [xlrd (⭐2.2k)](https://github.com/python-excel/xlrd) - Library for developers to extract data from Microsoft Excel spreadsheet files.
*   [xlsxwriter](https://xlsxwriter.readthedocs.io/) - Write files in the Excel 2007+ XLSX file format.

### R / Time Series

*   [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - Time Series Analysis and Computational Finance.
*   [fGarch](https://cran.r-project.org/web/packages/fGarch/index.html) - Rmetrics - Autoregressive Conditional Heteroskedastic Modelling.
*   [timeSeries](https://cran.r-project.org/web/packages/timeSeries/index.html) - Rmetrics - Financial Time Series Objects.
*   [tidypredict (⭐3)](https://github.com/edgararuiz/tidypredict) - Run predictions inside the database <https://tidypredict.netlify.com/>.
*   [tidyquant (⭐900)](https://github.com/business-science/tidyquant) - Bringing financial analysis to the tidyverse.
*   [timetk (⭐639)](https://github.com/business-science/timetk) - A toolkit for working with time series in R.

### R / Financial Instruments and Pricing

*   [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) - Quantitative Financial Modelling Framework.
*   [sparseIndexTracking (⭐59)](https://github.com/dppalomar/sparseIndexTracking) - Portfolio design to track an index.
*   [covFactorModel (⭐38)](https://github.com/dppalomar/covFactorModel) - Covariance matrix estimation via factor models.
*   [riskParityPortfolio (⭐121)](https://github.com/dppalomar/riskParityPortfolio) - Blazingly fast design of risk parity portfolios.
*   [sde](https://cran.r-project.org/web/packages/sde/index.html) - Simulation and Inference for Stochastic Differential Equations.
*   [YieldCurve](https://cran.r-project.org/web/packages/YieldCurve/index.html) - Modelling and estimation of the yield curve.
*   [SmithWilsonYieldCurve](https://cran.r-project.org/web/packages/SmithWilsonYieldCurve/index.html) - Constructs a yield curve by the Smith-Wilson method from a table of LIBOR and SWAP rates.
*   [ycinterextra](https://cran.r-project.org/web/packages/ycinterextra/index.html) - Yield curve or zero-coupon prices interpolation and extrapolation.
*   [AmericanCallOpt](https://cran.r-project.org/web/packages/AmericanCallOpt/index.html) - This package includes pricing function for selected American call options with underlying assets that generate payouts.
*   [VarSwapPrice](https://cran.r-project.org/web/packages/VarSwapPrice/index.html) - Pricing a variance swap on an equity index.
*   [RND](https://cran.r-project.org/web/packages/RND/index.html) - Risk Neutral Density Extraction Package.
*   [LSMonteCarlo](https://cran.r-project.org/web/packages/LSMonteCarlo/index.html) - American options pricing with Least Squares Monte Carlo method.
*   [OptHedging](https://cran.r-project.org/web/packages/OptHedging/index.html) - Estimation of value and hedging strategy of call and put options.
*   [tvm](https://cran.r-project.org/web/packages/tvm/index.html) - Time Value of Money Functions.
*   [OptionPricing](https://cran.r-project.org/web/packages/OptionPricing/index.html) - Option Pricing with Efficient Simulation Algorithms.
*   [derivmkts](https://cran.r-project.org/web/packages/derivmkts/index.html) - Functions and R Code to Accompany Derivatives Markets.
*   [FinCal (⭐24)](https://github.com/felixfan/FinCal) - Package for time value of money calculation, time series analysis and computational finance.
*   [r-quant (⭐34)](https://github.com/artyyouth/r-quant) - R code for quantitative analysis in finance.
*   [options.studies (⭐6)](https://github.com/taylorizing/options.studies) - options trading studies functions for use with options.data package and shiny.

### R / Trading

*   [backtest](https://cran.r-project.org/web/packages/backtest/index.html) - Exploring Portfolio-Based Conjectures About Financial Instruments.
*   [pa](https://cran.r-project.org/web/packages/pa/index.html) - Performance Attribution for Equity Portfolios.
*   [QuantTools](https://quanttools.bitbucket.io/_site/index.html) - Enhanced Quantitative Trading Modelling.

### Matlab / FrameWorks

*   [QUANTAXIS (⭐10k)](https://github.com/yutiansut/quantaxis) - Integrated Quantitative Toolbox with Matlab.

### Julia / FrameWorks

*   [Ito.jl (⭐39)](https://github.com/aviks/Ito.jl) - A Julia package for quantitative finance.
*   [TALib.jl (⭐52)](https://github.com/femtotrader/TALib.jl) - A Julia wrapper for TA-Lib.
*   [Temporal.jl (⭐101)](https://github.com/dysonance/Temporal.jl) - Flexible and efficient time series class & methods.
*   [Indicators.jl (⭐227)](https://github.com/dysonance/Indicators.jl) - Financial market technical analysis & indicators on top of Temporal.
*   [Strategems.jl (⭐167)](https://github.com/dysonance/Strategems.jl) - Quantitative systematic trading strategy development and backtesting.
*   [TimeSeries.jl (⭐366)](https://github.com/JuliaStats/TimeSeries.jl) - Time series toolkit for Julia.
*   [MarketTechnicals.jl (⭐129)](https://github.com/JuliaQuant/MarketTechnicals.jl) - Technical analysis of financial time series on top of TimeSeries.
*   [MarketData.jl (⭐162)](https://github.com/JuliaQuant/MarketData.jl) - Time series market data.
*   [TimeFrames.jl (⭐4)](https://github.com/femtotrader/TimeFrames.jl) - A Julia library that defines TimeFrame (essentially for resampling TimeSeries).

### Java / FrameWorks

*   [finmath.net](http://finmath.net) - Java library with algorithms and methodologies related to mathematical finance.
*   [quantcomponents (⭐169)](https://github.com/lsgro/quantcomponents) - Free Java components for Quantitative Finance and Algorithmic Trading.

### Haskell / Data Visualization

*   [quantfin (⭐139)](https://github.com/boundedvariation/quantfin) - quant finance in pure haskell.

### Scala / Data Visualization

*   [QuantScale (⭐50)](https://github.com/choucrifahed/quantscale) - Scala Quantitative Finance Library.

### Frameworks / Data Visualization

*   [TA-Lib](https://ta-lib.org) - perform technical analysis of financial market data.
    *   [ta-lib-python (⭐12k)](https://github.com/TA-Lib/ta-lib-python)
    *   [ta-lib (⭐1.5k)](https://github.com/TA-Lib/ta-lib)

### Reproducing Works, Training & Books / Data Visualization

*   [quant (⭐405)](https://github.com/paulperry/quant) - Quantitative Finance and Algorithmic Trading exhaust; mostly ipython notebooks based on Quantopian, Zipline, or Pandas.

## [Oct 09, 2018](/content/2018/10/09/README.md)

### R / Numerical Libraries & Data Structures

*   [sparseEigen (⭐12)](https://github.com/dppalomar/sparseEigen) - Sparse principal component analysis.

## [Mar 27, 2018](/content/2018/03/27/README.md)

### Reproducing Works, Training & Books / Data Visualization

*   [fecon235 (⭐1.3k)](https://github.com/rsvp/fecon235) - Open source project for software tools in financial economics. Many jupyter notebook to verify theoretical ideas and practical methods interactively.

## [Mar 05, 2018](/content/2018/03/05/README.md)

### R / Time Series

*   [tibbletime (⭐177)](https://github.com/business-science/tibbletime) - Built on top of the tidyverse, tibbletime is an extension that allows for the creation of time aware tibbles through the setting of a time index.

## [Dec 21, 2017](/content/2017/12/21/README.md)

### CSharp / Data Visualization

*   [QuantConnect (⭐18k)](https://github.com/QuantConnect/Lean) - Lean Engine is an open-source fully managed C# algorithmic trading engine built for desktop and cloud usage.

## [Feb 16, 2017](/content/2017/02/16/README.md)

### Java / FrameWorks

*   [DRIP](https://lakshmidrip.github.io/DRIP) - Fixed Income, Asset Allocation, Transaction Cost Analysis, XVA Metrics Libraries.

## [Jan 13, 2017](/content/2017/01/13/README.md)

### Ruby / Data Visualization

*   [Jiji (⭐249)](https://github.com/unageanu/jiji2) - Open Source Forex algorithmic trading framework using OANDA REST API.

## [Dec 05, 2016](/content/2016/12/05/README.md)

### R / Numerical Libraries & Data Structures

*   [TSdbi](http://tsdbi.r-forge.r-project.org/) - Provides a common interface to time series databases.
*   [zoo](https://cran.r-project.org/web/packages/zoo/index.html) - S3 Infrastructure for Regular and Irregular Time Series (Z's Ordered Observations).
*   [tis](https://cran.r-project.org/web/packages/tis/index.html) - Functions and S3 classes for time indexes and time indexed series, which are compatible with FAME frequencies.
*   [tfplot](https://cran.r-project.org/web/packages/tfplot/index.html) - Utilities for simple manipulation and quick plotting of time series data.
*   [tframe](https://cran.r-project.org/web/packages/tframe/index.html) - A kernel of functions for programming time series methods in a way that is relatively independently of the representation of time.

### R / Data Sources

*   [IBrokers](https://cran.r-project.org/web/packages/IBrokers/index.html) - Provides native R access to Interactive Brokers Trader Workstation API.
*   [Quandl](https://www.quandl.com/tools/r) - Get Financial Data Directly Into R.

## [Aug 22, 2016](/content/2016/08/22/README.md)

### Python / Data Sources

*   [findatapy (⭐2k)](https://github.com/cuemacro/findatapy) - Python library to download market data via Bloomberg, Quandl, Yahoo etc.

## [Jul 18, 2016](/content/2016/07/18/README.md)

### Python / Excel Integration

*   [xlwt (⭐1k)](https://github.com/python-excel/xlwt) - Library to create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files, on any platform.
*   [DataNitro](https://datanitro.com/) - DataNitro also offers full-featured Python-Excel integration, including UDFs. Trial downloads are available, but users must purchase a license.
*   [xlloop](http://xlloop.sourceforge.net) - XLLoop is an open source framework for implementing Excel user-defined functions (UDFs) on a centralised server (a function server).
*   [expy](http://www.bnikolic.co.uk/expy/expy.html) - The ExPy add-in allows easy use of Python directly from within an Microsoft Excel spreadsheet, both to execute arbitrary code and to define new Excel functions.
*   [pyxll](https://www.pyxll.com) - PyXLL is an Excel add-in that enables you to extend Excel using nothing but Python code.

## [Jun 24, 2016](/content/2016/06/24/README.md)

### Python / Trading & Backtesting

*   [pybacktest (⭐817)](https://github.com/ematvey/pybacktest) - Vectorized backtesting framework in Python / pandas, designed to make your backtesting easier.

## [Jun 22, 2016](/content/2016/06/22/README.md)

### Python / Numerical Libraries & Data Structures

*   [scipy](https://www.scipy.org) - SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering.

### Python / Financial Instruments and Pricing

*   [vollib (⭐929)](https://github.com/vollib/vollib) - vollib is a python library for calculating option prices, implied volatility and greeks.

### Python / Time Series

*   [statsmodels](http://statsmodels.sourceforge.net) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests.

### R / Calendars

*   [timeDate](https://cran.r-project.org/web/packages/timeDate/index.html) - Chronological and Calendar Objects

### Julia / FrameWorks

*   [QuantLib.jl (⭐143)](https://github.com/pazzo83/QuantLib.jl) - Quantlib implementation in pure Julia.

### Reproducing Works, Training & Books / Data Visualization

*   [Derman Papers (⭐506)](https://github.com/MarcosCarreira/DermanPapers) - Notebooks that replicate original quantitative finance papers from Emanuel Derman.
*   [volatility-trading (⭐1.9k)](https://github.com/jasonstrimpel/volatility-trading) - A complete set of volatility estimators based on Euan Sinclair's Volatility Trading.