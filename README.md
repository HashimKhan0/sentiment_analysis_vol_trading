# Sentiment Analysis for Volatility Trading

*Planning stage.* This repository documents an idea: use machine-learning models on news and media sentiment to forecast and trade **volatility**. The end goal is a tradable edge; along the way it's an excuse to explore web scraping, NLP and ML for finance.

## Skills this project is meant to build

- Web scraping as a data pipeline for ML
- Text / sentiment modelling
- Backtesting ML-driven strategies honestly

## Open design questions

**Finance**

- Which instruments to trade (one type or several)?
- Which media source can be scraped reliably with minimal manual input?
- Market-neutral, or bullish/bearish regime switching?

**Code / ML**

- How to build a robust scraping pipeline?
- Classification or probability estimation? Probabilities are better for sizing risk but make the dataset harder to build.
- Which model?
- How to backtest the ML component so results reflect the strategy and not chance or overfitting?
- How to eventually host and live-trade it?

---

*There is no "right" way to do it, only yours.*
