# USDCNH 4h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-22_303_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full USDCNH dataset on ork.ad**](https://ork.ad/)

**USDCNH 4h OHLCV Forex historical data** — ultra high-quality 4h OHLCV for **US Dollar / Chinese Yuan**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 4h OHLCV** for **US Dollar / Chinese Yuan** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **22,303** `4h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `USDCNH_4h.csv` (1,155 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **22,303** `4h` rows (~1.25 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2012-02-19` → `2026-07-03`.

## Download sample

**[USDCNH_4h.csv](https://github.com/ork-ad/usdcnh-4h-ohlcv-forex-historical-data/blob/main/USDCNH_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/usdcnh-4h-ohlcv-forex-historical-data/main/USDCNH_4h.csv)) · [GitHub Releases](https://github.com/ork-ad/usdcnh-4h-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/usdcnh-4h-ohlcv-forex-historical-data/](https://ork-ad.github.io/usdcnh-4h-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | US Dollar / Chinese Yuan · Forex | US Dollar / Chinese Yuan · Forex |
| Timeframes | `4h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 4h rows | 1,155 | **22,303** |
| Size | 0.07 MB | ~1.25 MB |
| Period | `2025-10-03` → `2026-07-03` | `2012-02-19` → `2026-07-03` |
| File | `USDCNH_4h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`4h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `4h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCNH_4h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T17:00:00Z | 7.13594 | 7.137853714 | 7.13153 | 7.13625 | 9272 |
| 2025-10-05T21:00:00Z | 7.13651358 | 7.1453 | 7.133323261 | 7.14319 | 11513 |
| 2025-10-06T01:00:00Z | 7.14319 | 7.14709 | 7.139893918 | 7.14689 | 14723 |
| 2025-10-06T05:00:00Z | 7.14689 | 7.150805009 | 7.14548 | 7.14892 | 21119 |
| 2025-10-06T09:00:00Z | 7.14892 | 7.149444873 | 7.14164 | 7.14257 | 16051 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T01:00:00Z | 6.788 | 6.78852 | 6.7826 | 6.785 | 20772 |
| 2026-07-03T05:00:00Z | 6.785 | 6.78696 | 6.78177 | 6.78455 | 25430 |
| 2026-07-03T09:00:00Z | 6.78455 | 6.7868 | 6.78264 | 6.78412 | 15292 |
| 2026-07-03T13:00:00Z | 6.78412 | 6.78633 | 6.78403 | 6.78531 | 15212 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDCNH_4h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCNH_4h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('USDCNH_4h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='4h')
print(pf.stats())
```

## Download full data

The complete **USDCNH** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **22,303** rows at `4h`, plus all other timeframes in the same ZIP.

**[→ Get the full USDCNH dataset on ork.ad](https://ork.ad/)**

---
*GetData · USDCNH 4h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*