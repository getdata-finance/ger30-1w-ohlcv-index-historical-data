# GER30 1w OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-940_rows-blue)](https://getdata.finance/datasets/ger30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ger30)

### -> [**Download the full GER30 dataset on getdata.finance**](https://getdata.finance/datasets/ger30)

**GER30 1w OHLCV index historical data** — ultra high-quality 1w OHLCV for **DAX 40 (GER30)**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **DAX 40 (GER30)** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ger30) · **940** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `GER30_1w.csv` (106 rows, `2024-08-29` -> `2026-09-03`, 10.37 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ger30)** — **940** `1w` rows (full `1m`: 2,329,742), **11 timeframes**, `2008-09-04` -> `2026-09-03`.

## Download sample

**[GER30_1w.csv](https://github.com/getdata-finance/ger30-1w-ohlcv-index-historical-data/blob/main/GER30_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ger30-1w-ohlcv-index-historical-data/main/GER30_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/ger30-1w-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ger30-1w-ohlcv-index-historical-data/](https://getdata-finance.github.io/ger30-1w-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ger30](https://getdata.finance/datasets/ger30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ger30))** |
|---|--:|---|
| Instrument | DAX 40 (GER30) · Index | DAX 40 (GER30) · Index |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 106 | **940** |
| Size | 10.37 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Period | `2024-08-29` -> `2026-09-03` | `2008-09-04` -> `2026-09-03` |
| File | `GER30_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Coverage report | — | [GER30 coverage](https://getdata.finance/coverage/ger30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ger30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

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
| 2024-08-29T00:00:00+00:00 | 18785.69 | 18996.59 | 18475.94 | 18569.7 | 415378.57676 |
| 2024-09-05T00:00:00+00:00 | 18569.7 | 18677.63 | 18187.01 | 18476.91 | 518914 |
| 2024-09-12T00:00:00+00:00 | 18476.91 | 18917.88 | 18373.99 | 18748.39 | 449885.51464 |
| 2024-09-19T00:00:00+00:00 | 18747.79 | 19047.71 | 18687.94 | 18921.67 | 439904.41075 |
| 2024-09-26T00:00:00+00:00 | 18921.67 | 19507.25 | 18921.67 | 19163.29 | 501995.6516 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-06T00:00:00+00:00 | 26169.77 | 26565.57 | 26066.57 | 26363.48 | 637018.68334 |
| 2026-08-13T00:00:00+00:00 | 26363.48 | 26522.89 | 26040.44 | 26068.7 | 568902.20332 |
| 2026-08-20T00:00:00+00:00 | 26068.7 | 26474.05 | 25886.87 | 26290.49 | 586704.50177 |
| 2026-08-27T00:00:00+00:00 | 26290.49 | 26625.43 | 25730.12 | 25858.03 | 722170 |
| 2026-09-03T00:00:00+00:00 | 25858.53 | 26164.11 | 25784.34 | 25873.26 | 536627 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[getdata.finance](https://getdata.finance/datasets/ger30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **940** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full GER30 dataset on getdata.finance](https://getdata.finance/datasets/ger30)**

---
*GetData · GER30 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ger30)*
