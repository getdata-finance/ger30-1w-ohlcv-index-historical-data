# GER30 1w OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_948_rows-blue)](https://getdata.finance/datasets/ger30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ger30)

### -> [**Download the full GER30 dataset on getdata.finance**](https://getdata.finance/datasets/ger30)

**GER30 1w OHLCV stock index historical data** — ultra high-quality 1w OHLCV for **Germany 30 (DAX)**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1w OHLCV** for **Germany 30 (DAX)** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ger30) · **2,948** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `GER30_1w.csv` (105 rows, `2024-08-01` -> `2026-07-30`). **Full archive on [getdata.finance](https://getdata.finance/datasets/ger30)** — **2,948** `1m` rows (~0.21 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `1970-02-05` -> `2026-07-30`.

## Download sample

**[GER30_1w.csv](https://github.com/getdata-finance/ger30-1w-ohlcv-index-historical-data/blob/main/GER30_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ger30-1w-ohlcv-index-historical-data/main/GER30_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/ger30-1w-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ger30-1w-ohlcv-index-historical-data/](https://getdata-finance.github.io/ger30-1w-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ger30](https://getdata.finance/datasets/ger30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ger30))** |
|---|--:|---|
| Instrument | Germany 30 (DAX) · Stock index | Germany 30 (DAX) · Stock index |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 105 | **2,948** |
| Size | 0.01 MB | ~0.21 MB |
| Period | `2024-08-01` -> `2026-07-30` | `1970-02-05` -> `2026-07-30` |
| File | `GER30_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Coverage report | — | [GER30 coverage](https://getdata.finance/coverage/ger30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ger30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/ger30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GER30_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-08-01T00:00:00+00:00 | 18482.39 | 18532.59 | 17023.37 | 17426.44 | 842040 |
| 2024-08-08T00:00:00+00:00 | 17426.44 | 17922.8 | 17369 | 17896.2 | 479352 |
| 2024-08-15T00:00:00+00:00 | 17896.2 | 18499.47 | 17896.2 | 18472.49 | 296658 |
| 2024-08-22T00:00:00+00:00 | 18472.49 | 18864.81 | 18428.63 | 18785.69 | 343300 |
| 2024-08-29T00:00:00+00:00 | 18785.69 | 18997.99 | 18475.94 | 18569.7 | 415372 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-02T00:00:00+00:00 | 25066.72 | 25931.29 | 24843.13 | 25031.03 | 1234939 |
| 2026-07-09T00:00:00+00:00 | 25031.03 | 25219.05 | 24776.55 | 25003.3 | 1249794 |
| 2026-07-16T00:00:00+00:00 | 25003.3 | 25278.91 | 24615.42 | 25156.8 | 1344582 |
| 2026-07-23T00:00:00+00:00 | 25156.8 | 25594.17 | 24692.73 | 25383.42 | 1630384 |
| 2026-07-30T00:00:00+00:00 | 25383.42 | 25827.61 | 25297.5 | 25788.6 | 321665 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GER30_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GER30_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('GER30_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[getdata.finance](https://getdata.finance/datasets/ger30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,948** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full GER30 dataset on getdata.finance](https://getdata.finance/datasets/ger30)**

---
*GetData · GER30 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ger30) · 2026-08-05 UTC*
