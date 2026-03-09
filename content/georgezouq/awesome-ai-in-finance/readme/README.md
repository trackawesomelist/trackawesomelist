# Awesome Ai in Finance Overview

🔬 A curated list of awesome LLMs & deep learning strategies & tools in financial market.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/georgezouq/awesome-ai-in-finance/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 georgezouq/awesome-ai-in-finance](https://github.com/georgezouq/awesome-ai-in-finance) · ⭐ 4.9K · 🏷️ Computer Science

[ [Daily](/content/georgezouq/awesome-ai-in-finance/README.md) / [Weekly](/content/georgezouq/awesome-ai-in-finance/week/README.md) / Overview ]

---

# Awesome AI in Finance [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) [![Community](https://img.shields.io/discord/733027681184251937.svg?style=flat\&label=Join%20Community\&color=7289DA)](https://discord.gg/cqaUf47)

There are millions of trades made in the global financial market every day. Data grows very quickly and people are hard to understand.
With the power of the latest artificial intelligence research, people analyze & trade automatically and intelligently. This list contains the research, tools and code that people use to beat the market.

\[[中文资源](https://github.com/georgezouq/awesome-ai-in-finance/blob/main/README.md/./chinese.md)]

## Contents

*   [Agents](#agents)
*   [LLMs](#llms)
*   [Papers](#papers)
*   [Courses & Books](#courses--books)
*   [Strategies & Research](#strategies--research)
    *   [Time Series Data](#time-series-data)
    *   [Portfolio Management](#portfolio-management)
    *   [High Frequency Trading](#high-frequency-trading)
    *   [Event Drive](#event-drive)
    *   [Crypto Currencies Strategies](#crypto-currencies-strategies)
    *   [Technical Analysis](#technical-analysis)
    *   [Lottery & Gamble](#lottery--gamble)
    *   [Arbitrage](#arbitrage)
*   [Data Sources](#data-sources)
*   [Research Tools](#research-tools)
*   [Trading System](#trading-system)
*   [TA Lib](#ta-lib)
*   [Exchange API](#exchange-api)
*   [Articles](#articles)
*   [Others](#others)

## Agents

*   🌟🌟 [nofx (⭐11k)](https://github.com/NoFxAiOS/nofx) - A multi-exchange Al trading platform with multi-Ai competition self-evolution, and real-time dashboard.
*   [TradingAgents (⭐31k)](https://github.com/TauricResearch/TradingAgents) - Multi-Agents LLM Financial Trading Framework.
*   🌟 [FinRobot (⭐6.3k)](https://github.com/AI4Finance-Foundation/FinRobot) - An Open-Source AI Agent Platform for Financial Analysis using LLMs.

## LLMs

*   🌟🌟🌟 [Nof1](https://thenof1.com/) - Benchmark designed to measure AI's investing abilities. Each model is given $10,000 of real money, in real markets, with identical prompts and input data.
*   🌟 [AI Hedge Fund (⭐46k)](https://github.com/virattt/ai-hedge-fund) - Explore the use of AI to make trading decisions.
*   🌟🌟 [MarS (⭐1.6k)](https://github.com/microsoft/MarS) - A Financial Market Simulation Engine Powered by Generative Foundation Model.
*   🌟🌟 [Financial Statement Analysis with Large Language Models](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4835311) - GPT-4 can outperform professional financial analysts in predicting future earnings changes, generating useful narrative insights, and resulting in superior trading strategies with higher Sharpe ratios and alphas, thereby suggesting a potential central role for LLMs in financial decision-making.
*   [FinRpt](https://arxiv.org/abs/2511.07322) - Dataset, Evaluation System and LLM-based Multi-agent Framework for Equity Research Report Generation.
*   [PIXIU (⭐832)](https://github.com/chancefocus/PIXIU) - An open-source resource providing a financial large language model, a dataset with 136K instruction samples, and a comprehensive evaluation benchmark.
*   [FinGPT (⭐19k)](https://github.com/AI4Finance-Foundation/FinGPT) - Provides a playground for all people interested in LLMs and NLP in Finance.
*   [MACD + RSI + ADX Strategy (ChatGPT-powered) by TradeSmart](https://www.tradingview.com/script/GxkUyJKW-MACD-RSI-ADX-Strategy-ChatGPT-powered-by-TradeSmart/) - Asked ChatGPT on which indicators are the most popular for trading. We used all of the recommendations given.
*   [A ChatGPT trading algorithm delivered 500% returns in stock market. My breakdown on what this means for hedge funds and retail investors](https://www.reddit.com/r/ChatGPT/comments/13duech/a_chatgpt_trading_algorithm_delivered_500_returns/)
*   [Use chatgpt to adjust strategy parameters](https://twitter.com/0xUnicorn/status/1663413848593031170)
*   [Hands-on LLMs: Train and Deploy a Real-time Financial Advisor (⭐3.4k)](https://github.com/iusztinpaul/hands-on-llms) - Train and deploy a real-time financial advisor chatbot with Falcon 7B and CometLLM.
*   [ChatGPT Strategy by OctoBot](https://blog.octobot.online/trading-using-chat-gpt) - Use ChatGPT to determine which cryptocurrency to trade based on technical indicators.

## Papers

*   [The Theory of Speculation L. Bachelier, 1900](http://www.radio.goldseek.com/bachelier-thesis-theory-of-speculation-en.pdf) - The influences which determine the movements of the Stock Exchange are.
*   [Brownian Motion in the Stock Market Osborne, 1959](http://m.e-m-h.org/Osbo59.pdf) - The common-stock prices can be regarded as an ensemble of decisions in statistical equilibrium.
*   [An Investigation into the Use of Reinforcement Learning Techniques within the Algorithmic Trading Domain, 2015](http://www.doc.ic.ac.uk/teaching/distinguished-projects/2015/j.cumming.pdf)
*   [A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem](https://arxiv.org/pdf/1706.10059.pdf)
*   [Reinforcement Learning for Trading, 1994](http://papers.nips.cc/paper/1551-reinforcement-learning-for-trading.pdf)
*   [Dragon-Kings, Black Swans and the Prediction of Crises Didier Sornette](https://arxiv.org/pdf/0907.4290.pdf) - The power laws in the distributions of event sizes under a broad range of conditions in a large variety of systems.
*   [Financial Trading as a Game: A Deep Reinforcement Learning Approach](https://arxiv.org/pdf/1807.02787.pdf) - Deep reinforcement learning provides a framework toward end-to-end training of such trading agent.
*   [Machine Learning for Trading](https://cims.nyu.edu/~ritter/ritter2017machine.pdf) - With an appropriate choice of the reward function, reinforcement learning techniques can successfully handle the risk-averse case.
*   [Ten Financial Applications of Machine Learning, 2018](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3197726) - Slides review few important financial ML applications.
*   [FinRL: A Deep Reinforcement Learning Library for Automated Stock Trading in Quantitative Finance, 2020](https://arxiv.org/abs/2011.09607) - Introduce a DRL library FinRL that facilitates beginners to expose themselves to quantitative finance and to develop their own stock trading strategies.
*   [Deep Reinforcement Learning for Automated Stock Trading: An Ensemble Strategy, 2020](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3690996) - Propose an ensemble strategy that employs deep reinforcement schemes to learn a stock trading strategy by maximizing investment return.

## Courses & Books & Blogs

*   🌟 [QuantResearch (⭐2.8k)](https://github.com/letianzj/QuantResearch) - Quantitative analysis, strategies and backtests <https://letianzj.github.io/>
*   [NYU: Overview of Advanced Methods of Reinforcement Learning in Finance](https://www.coursera.org/learn/advanced-methods-reinforcement-learning-finance/home/welcome)
*   [Udacity: Artificial Intelligence for Trading](https://www.udacity.com/course/ai-for-trading--nd880)
*   [AI in Finance](https://cfte.education/) - Learn Fintech Online.
*   [Advanced-Deep-Trading (⭐565)](https://github.com/Rachnog/Advanced-Deep-Trading) - Experiments based on "Advances in financial machine learning" book.
*   [Advances in Financial Machine Learning](https://www.amazon.com/Advances-Financial-Machine-Learning-Marcos-ebook/dp/B079KLDW21/ref=sr_1_1?s=books\&ie=UTF8\&qid=1541717436\&sr=1-1) - Using advanced ML solutions to overcome real-world investment problems.
*   [Build Financial Software with Generative AI](https://www.manning.com/books/build-financial-software-with-generative-ai?ar=false\&lpse=B&) - Book about how to build financial software hands-on using generative AI tools like ChatGPT and Copilot.
*   [Financial AI in Practice](https://www.manning.com/books/financial-ai-in-practice) - A book about creating profitable, regulation-compliant financial applications.
*   [Investing for Programmers](https://www.manning.com/books/investing-for-programmers) - A book about maximizing your portfolio, analyzing markets, and making data-driven investment decisions using Python and generative AI
*   [Mastering Python for Finance (⭐442)](https://github.com/jamesmawm/mastering-python-for-finance-second-edition) - Sources codes for: Mastering Python for Finance, Second Edition.
*   [MLSys-NYU-2022 (⭐548)](https://github.com/jacopotagliabue/MLSys-NYU-2022/tree/main) - Slides, scripts and materials for the Machine Learning in Finance course at NYU Tandon, 2022.
*   [Train and Deploy a Serverless API to predict crypto prices (⭐877)](https://github.com/Paulescu/hands-on-train-and-deploy-ml) - In this tutorial you won't build an ML system that will make you rich. But you will master the MLOps frameworks and tools you need to build ML systems that, together with tons of experimentation, can take you there.

## Strategies & Research

### Time Series Data

Price and Volume process with Technology Analysis Indices

*   🌟🌟 [stockpredictionai (⭐5.5k)](https://github.com/borisbanushev/stockpredictionai) - A complete process for predicting stock price movements.
*   🌟 [Personae (⭐1.4k)](https://github.com/Ceruleanacg/Personae) - Implements and environment of Deep Reinforcement Learning & Supervised Learning for Quantitative Trading.
*   🌟 [Ensemble-Strategy (⭐2.7k)](https://github.com/AI4Finance-LLC/Deep-Reinforcement-Learning-for-Automated-Stock-Trading-Ensemble-Strategy-ICAIF-2020) - Deep Reinforcement Learning for Automated Stock Trading.
*   [FinRL (⭐14k)](https://github.com/AI4Finance-LLC/FinRL-Library) - A Deep Reinforcement Learning Library for Automated Stock Trading in Quantitative Finance.
*   [AutomatedStockTrading-DeepQ-Learning (⭐285)](https://github.com/sachink2010/AutomatedStockTrading-DeepQ-Learning) - Build a Deep Q-learning reinforcement agent model as automated trading robot.
*   [tf\_deep\_rl\_trader (⭐254)](https://github.com/miroblog/tf_deep_rl_trader) - Trading environment(OpenAI Gym) + PPO(TensorForce).
*   [trading-gym (⭐233)](https://github.com/6-Billionaires/trading-gym) - Trading agent to train with episode of short term trading itself.
*   [trading-rl (⭐223)](https://github.com/Kostis-S-Z/trading-rl) - Deep Reinforcement Learning for Financial Trading using Price Trailing.
*   [deep\_rl\_trader (⭐420)](https://github.com/miroblog/deep_rl_trader) - Trading environment(OpenAI Gym) + DDQN (Keras-RL).
*   [Quantitative-Trading (⭐37)](https://github.com/Ceruleanacg/Quantitative-Trading) - Papers and code implementing Quantitative-Trading.
*   [gym-trading (⭐713)](https://github.com/hackthemarket/gym-trading) - Environment for reinforcement-learning algorithmic trading models.
*   [zenbrain (⭐51)](https://github.com/carlos8f/zenbrain) - A framework for machine-learning bots.
*   [DeepLearningNotes (⭐379)](https://github.com/AlphaSmartDog/DeepLearningNotes) - Machine learning in quant analysis.
*   [stock\_market\_reinforcement\_learning (⭐799)](https://github.com/kh-kim/stock_market_reinforcement_learning) - Stock market trading OpenAI Gym environment with Deep Reinforcement Learning using Keras.
*   [Chaos Genius (⭐774)](https://github.com/chaos-genius/chaos_genius) - ML powered analytics engine for outlier/anomaly detection and root cause analysis..
*   [mlforecast (⭐1.2k)](https://github.com/Nixtla/mlforecast) - Scalable machine learning based time series forecasting.

### Portfolio Management

*   [Deep-Reinforcement-Stock-Trading (⭐688)](https://github.com/Albert-Z-Guo/Deep-Reinforcement-Stock-Trading) - A light-weight deep reinforcement learning framework for portfolio management.
*   [qtrader (⭐476)](https://github.com/filangel/qtrader) - Reinforcement Learning for portfolio management.
*   [PGPortfolio (⭐1.9k)](https://github.com/ZhengyaoJiang/PGPortfolio) - A Deep Reinforcement Learning framework for the financial portfolio management problem.
*   [DeepDow (⭐1.1k)](https://github.com/jankrepl/deepdow) - Portfolio optimization with deep learning.
*   [skfolio (⭐1.9k)](https://github.com/skfolio/skfolio) - Python library for portfolio optimization built on top of scikit-learn.

### High Frequency Trading

*   [High-Frequency-Trading-Model-with-IB (⭐2.9k)](https://github.com/jamesmawm/High-Frequency-Trading-Model-with-IB) - A high-frequency trading model using Interactive Brokers API with pairs and mean-reversion.
*   🌟 [SGX-Full-OrderBook-Tick-Data-Trading-Strategy (⭐2.2k)](https://github.com/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy) - Solutions for high-frequency trading (HFT) strategies using data science approaches (Machine Learning) on Full Orderbook Tick Data.
*   [HFT\_Bitcoin (⭐168)](https://github.com/ghgr/HFT_Bitcoin) - Analysis of High Frequency Trading on Bitcoin exchanges.

### Event Drive

*   🌟🌟 [stockpredictionai (⭐5.5k)](https://github.com/borisbanushev/stockpredictionai) - Complete process for predicting stock price movements.
*   🌟 [trump2cash (⭐6.5k)](https://github.com/maxbbraun/trump2cash) - A stock trading bot powered by Trump tweets.

### Crypto Currencies Strategies

*   [LSTM-Crypto-Price-Prediction (⭐354)](https://github.com/SC4RECOIN/LSTM-Crypto-Price-Prediction) - Predicting price trends in crypto markets using an LSTM-RNN for trading.
*   [tforce\_btc\_trader (⭐832)](https://github.com/lefnire/tforce_btc_trader) - TensorForce Bitcoin trading bot.
*   [Tensorflow-NeuroEvolution-Trading-Bot (⭐163)](https://github.com/SC4RECOIN/Tensorflow-NeuroEvolution-Trading-Bot) - A population model that trade cyrpto and breed and mutate iteratively.
*   [gekkoga (⭐311)](https://github.com/gekkowarez/gekkoga) - Genetic algorithm for solving optimization of trading strategies using Gekko.
*   [Gekko\_ANN\_Strategies (⭐55)](https://github.com/markchen8717/Gekko_ANN_Strategies) - ANN trading strategies for the Gekko trading bot.
*   [gekko-neuralnet (⭐94)](https://github.com/zschro/gekko-neuralnet) - Neural network strategy for Gekko.
*   [bitcoin\_prediction (⭐235)](https://github.com/llSourcell/bitcoin_prediction) - Code for "Bitcoin Prediction" by Siraj Raval on YouTube.

### Technical Analysis

*   [QTradeX (⭐56)](https://github.com/squidKid-deluxe/QTradeX-Algo-Trading-SDK) - A powerful and flexible Python framework for designing, backtesting, optimizing, and deploying algotrading bots
*   [quant-trading (⭐9.2k)](https://github.com/je-suis-tm/quant-trading) - Python quantitative trading strategies.
*   [Gekko-Bot-Resources (⭐196)](https://github.com/cloggy45/Gekko-Bot-Resources) - Gekko bot resources.
*   [gekko\_tools (⭐143)](https://github.com/tommiehansen/gekko_tools) - Gekko strategies, tools etc.
*   [gekko RSI\_WR (⭐4)](https://github.com/zzmike76/gekko) - Gekko RSI\_WR strategies.
*   [gekko HL (⭐11)](https://github.com/mounirlabaied/gekko-strat-hl) - Calculate down peak and trade on.
*   [EthTradingAlgorithm (⭐4)](https://github.com/Philipid3s/EthTradingAlgorithm) - Ethereum trading algorithm using Python 3.5 and the library ZipLine.
*   [gekko\_trading\_stuff (⭐110)](https://github.com/thegamecat/gekko-trading-stuff) - Awesome crypto currency trading platform.
*   [forex.analytics (⭐189)](https://github.com/mkmarek/forex.analytics) - Node.js native library performing technical analysis over an OHLC dataset with use of genetic algorithmv.
*   [Bitcoin\_MACD\_Strategy (⭐10)](https://github.com/VermeirJellen/Bitcoin_MACD_Strategy) - Bitcoin MACD crossover trading strategy backtest.
*   [crypto-signal (⭐5.5k)](https://github.com/CryptoSignal/crypto-signal) - Automated crypto trading & technical analysis (TA) bot for Bittrex, Binance, GDAX, and more.
*   [Gekko-Strategies (⭐1.4k)](https://github.com/xFFFFF/Gekko-Strategies) - Strategies to Gekko trading bot with backtests results and some useful tools.
*   [gekko-gannswing (⭐71)](https://github.com/johndoe75/gekko-gannswing) - Gann's Swing trade strategy for Gekko trade bot.
*   [Chartscout](https://chartscout.io) - Real-time cryptocurrency chart pattern detection with automated alerts using pattern recognition algorithms

### Lottery & Gamble

*   [LotteryPredict (⭐412)](https://github.com/chengstone/LotteryPredict) - Use LSTM to predict lottery.

### Arbitrage

*   [ArbitrageBot (⭐176)](https://github.com/BatuhanUsluel/ArbitrageBot) - Arbitrage bot that currently works on bittrex & poloniex.
*   [r2 (⭐810)](https://github.com/bitrinjani/r2) - Automatic arbitrage trading system powered by Node.js + TypeScript.
*   [cryptocurrency-arbitrage (⭐1.3k)](https://github.com/manu354/cryptocurrency-arbitrage) - A crypto currency arbitrage opportunity calculator. Over 800 currencies and 50 markets.
*   [bitcoin-arbitrage (⭐2.6k)](https://github.com/maxme/bitcoin-arbitrage) - Bitcoin arbitrage opportunity detector.
*   [blackbird](https://github.com/butor/blackbird) - Long / short market-neutral strategy.

## Data Sources

#### Traditional Markets

*   🌟 [Quandl](https://www.quandl.com/tools/api) - Get millions of financial and economic dataset from hundreds of publishers via a single free API.
*   [yahoo-finance (⭐1.4k)](https://github.com/lukaszbanasiak/yahoo-finance) - Python module to get stock data from Yahoo! Finance.
*   [Tushare (⭐14k)](https://github.com/waditu/tushare) - Crawling historical data of Chinese stocks.
*   [Financial Data](https://financialdata.net/) - Stock Market and Financial Data API.
*   [ValueRay](https://www.valueray.com/api) - Technical, quantitative and sentiment data for stocks and ETFs with risk metrics, peer percentiles and market regime signals. Optimized for AI/LLM agents.

#### Crypto Currencies

*   [CryptoInscriber (⭐52)](https://github.com/Optixal/CryptoInscriber) - A live crypto currency historical trade data blotter. Download live historical trade data from any crypto exchange.
*   [CoinPulse (⭐0)](https://github.com/soutone/coinpulse-python) - Python SDK for cryptocurrency portfolio tracking with real-time prices, P/L calculations, backtesting, and price alerts. Free tier: 25 req/hr.
*   [Gekko-Datasets (⭐174)](https://github.com/xFFFFF/Gekko-Datasets) - Gekko trading bot dataset dumps. Download and use history files in SQLite format.
*   [Frostbyte Crypto API](https://agent-gateway-kappa.vercel.app) - Free real-time cryptocurrency price data API. Supports BTC, ETH, SOL, and 20+ tokens. No signup or API key required for basic endpoints. JSON responses with price, 24h change, market cap, and volume.

#### News Data

*   [WorldMonitor (⭐22k)](https://github.com/koala73/worldmonitor) - AI-powered news aggregation, geopolitical monitoring, and infrastructure tracking in a unified situational awareness interface.

#### Alternative Data

*   [Pizzint](https://www.pizzint.watch/) - Pentagon Pizza Index (PizzINT) is a real-time Pentagon pizza tracker that visualizes unusual activity at Pentagon-area pizzerias. It highlights a signal that has historically aligned with late-night, high-tempo operations and breaking news.

## Research Tools

*   [Synthical](https://synthical.com) - AI-powered collaborative environment for Research.
*   🌟🌟 [TensorTrade (⭐6k)](https://github.com/tensortrade-org/tensortrade) - Trade efficiently with reinforcement learning.
*   [ML-Quant](https://www.ml-quant.com/) - Quant resources from ArXiv (sanity), SSRN, RePec, Journals, Podcasts, Videos, and Blogs.
*   [JAQS (⭐633)](https://github.com/quantOS-org/JAQS) - An open source quant strategies research platform.
*   [pyfolio (⭐6.2k)](https://github.com/quantopian/pyfolio) - Portfolio and risk analytics in Python.
*   [alphalens (⭐4.1k)](https://github.com/quantopian/alphalens) - Performance analysis of predictive (alpha) stock factors.
*   [empyrical (⭐1.5k)](https://github.com/quantopian/empyrical) - Common financial risk and performance metrics. Used by Zipline and pyfolio.
*   [zvt (⭐4k)](https://github.com/zvtvz/zvt) - Zero vector trader.
*   [WFGY (⭐1.5k)](https://github.com/onestardao/WFGY) – Open source framework for debugging and stress testing LLM agents and RAG pipelines. Includes a 16 mode failure map and long-horizon stress tests that are useful for financial research agents.

## Trading System

For Back Test & Live trading

### Traditional Market

**System**

*   [the0 (⭐164)](https://github.com/alexanderwanyoike/the0) - Self-hosted execution engine for algorithmic trading bots. Supports Python, TypeScript, Rust, C++, C#, Scala, and Haskell. Each bot runs in an isolated container with scheduled or streaming execution.
*   🌟🌟🌟 [OpenBB (⭐63k)](https://github.com/OpenBB-finance/OpenBB) - AI-powered opensource research and analytics workspace.
*   🌟🌟 [zipline (⭐19k)](https://github.com/quantopian/zipline) - A python algorithmic trading library.
*   🌟 [TradingView](http://tradingview.com/) - Get real-time information and market insights.
*   [rqalpha (⭐6.2k)](https://github.com/ricequant/rqalpha) - A extendable, replaceable Python algorithmic backtest & trading framework.
*   [backtrader (⭐21k)](https://github.com/backtrader/backtrader) - Python backtesting library for trading strategies.
*   [kungfu (⭐3.8k)](https://github.com/taurusai/kungfu) - Kungfu Master trading system.
*   [lean (⭐17k)](https://github.com/QuantConnect/Lean) - Algorithmic trading engine built for easy strategy research, backtesting and live trading.

**Combine & Rebuild**

*   [pylivetrader (⭐681)](https://github.com/alpacahq/pylivetrader) - Python live trade execution library with zipline interface.
*   [CoinMarketCapBacktesting (⭐3)](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting) - As backtest frameworks for coin trading strategy.

### Crypto Currencies

*   [zenbot (⭐8.3k)](https://github.com/DeviaVir/zenbot) - Command-line crypto currency trading bot using Node.js and MongoDB.
*   [bot18 (⭐202)](https://github.com/carlos8f/bot18) - High-frequency crypto currency trading bot developed by Zenbot.
*   [magic8bot (⭐397)](https://github.com/magic8bot/magic8bot) - Crypto currency trading bot using Node.js and MongoDB.
*   [catalyst (⭐2.6k)](https://github.com/enigmampc/catalyst) - An algorithmic trading library for Crypto-Assets in python.
*   [QuantResearchDev (⭐32)](https://github.com/mounirlabaied/QuantResearchDev) - Quant Research dev & Traders open source project.
*   [MACD](https://github.com/sudoscripter/MACD) - Zenbot MACD Auto-Trader.
*   [abu (⭐16k)](https://github.com/bbfamily/abu) - A quant trading system base on python.

#### Plugins

*   [CoinMarketCapBacktesting (⭐3)](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting) - Tests bt and Quantopian Zipline as backtesting frameworks for coin trading strategy.
*   [Gekko-BacktestTool (⭐230)](https://github.com/xFFFFF/Gekko-BacktestTool) - Batch backtest, import and strategy params optimalization for Gekko Trading Bot.

## TA Lib

*   [pandas\_talib (⭐781)](https://github.com/femtotrader/pandas_talib) - A Python Pandas implementation of technical analysis indicators.
*   [finta (⭐2.2k)](https://github.com/peerchemist/finta) - Common financial technical indicators implemented in Python-Pandas (70+ indicators).
*   [tulipnode (⭐513)](https://github.com/TulipCharts/tulipnode) - Official Node.js wrapper for Tulip Indicators. Provides over 100 technical analysis overlay and indicator functions.
*   [techan.js (⭐2.4k)](https://github.com/andredumas/techan.js) - A visual, technical analysis and charting (Candlestick, OHLC, indicators) library built on D3.

## Exchange API

Do it in real world!

*   [IbPy (⭐1.4k)](https://github.com/blampe/IbPy) - Python API for the Interactive Brokers on-line trading system.
*   [HuobiFeeder (⭐38)](https://github.com/mmmaaaggg/HuobiFeeder) - Connect HUOBIPRO exchange, get market/historical data for ABAT trading platform backtest analysis and live trading.
*   [ctpwrapper (⭐561)](https://github.com/nooperpudd/ctpwrapper) - Shanghai future exchange CTP api.
*   [PENDAX (⭐48)](https://github.com/CompendiumFi/PENDAX-SDK) - Javascript SDK for Trading/Data API and Websockets for cryptocurrency exchanges like FTX, FTXUS, OKX, Bybit, & More

### Framework

*   [tf-quant-finance (⭐5.2k)](https://github.com/google/tf-quant-finance) - High-performance TensorFlow library for quantitative finance.

### Visualizing

*   [playground (⭐13k)](https://github.com/tensorflow/playground) - Play with neural networks.
*   [netron (⭐33k)](https://github.com/lutzroeder/netron) - Visualizer for deep learning and machine learning models.
*   [KLineChart (⭐3.6k)](https://github.com/liihuu/KLineChart) - Highly customizable professional lightweight financial charts

### GYM Environment

*   🌟 [TradingGym (⭐1.8k)](https://github.com/Yvictor/TradingGym) - Trading and Backtesting environment for training reinforcement learning agent.
*   [TradzQAI (⭐166)](https://github.com/kkuette/TradzQAI) - Trading environment for RL agents, backtesting and training.
*   [btgym (⭐1k)](https://github.com/Kismuz/btgym) - Scalable, event-driven, deep-learning-friendly backtesting library.

## Articles

*   [The-Economist (⭐3.8k)](https://github.com/nailperry-zd/The-Economist) - The Economist.
*   [nyu-mlif-notes (⭐104)](https://github.com/wizardforcel/nyu-mlif-notes) - NYU machine learning in finance notes.
*   [Using LSTMs to Turn Feelings Into Trades](https://www.quantopian.com/posts/watch-our-webinar-buying-happiness-using-lstms-to-turn-feelings-into-trades-now?utm_source=forum\&utm_medium=twitter\&utm_campaign=sentiment-analysis)

## Others

*   [zipline-tensorboard (⭐107)](https://github.com/jimgoo/zipline-tensorboard) - TensorBoard as a Zipline dashboard.
*   [gekko-quasar-ui (⭐112)](https://github.com/H256/gekko-quasar-ui) - An UI port for gekko trading bot using Quasar framework.
*   [Floom (⭐46)](https://github.com/FloomAI/Floom) AI gateway and marketplace for developers, enables streamlined integration and least volatile approach of AI features into products

#### Other Resource

*   🌟🌟🌟 [Stock-Prediction-Models (⭐9.2k)](https://github.com/huseinzol05/Stock-Prediction-Models) - Stock-Prediction-Models, Gathers machine learning and deep learning models for Stock forecasting, included trading bots and simulations.
*   🌟🌟 [Financial Machine Learning (⭐8.4k)](https://github.com/firmai/financial-machine-learning) - A curated list of practical financial machine learning (FinML) tools and applications. This collection is primarily in Python.
*   🌟 [Awesome-Quant-Machine-Learning-Trading (⭐3.5k)](https://github.com/grananqvist/Awesome-Quant-Machine-Learning-Trading) - Quant / Algorithm trading resources with an emphasis on Machine Learning.
*   [awesome-quant (⭐24k)](https://github.com/wilsonfreitas/awesome-quant) - A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance).
*   [FinancePy (⭐2.8k)](https://github.com/domokane/FinancePy) - A Python Finance Library that focuses on the pricing and risk-management of Financial Derivatives, including fixed-income, equity, FX and credit derivatives.
*   [Explore Finance Service Libraries & Projects](https://kandi.openweaver.com/explore/financial-services#Top-Authors) - Explore a curated list of Fintech popular & new libraries, top authors, trending project kits, discussions, tutorials & learning resources on kandi.
*   [AgentMarket](https://agentmarket.cloud) - B2A marketplace for AI agents. 189 listings, 28M+ real energy data records, LangChain/MCP integration.

