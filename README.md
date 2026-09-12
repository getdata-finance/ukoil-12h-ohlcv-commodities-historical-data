# UKOIL 12h OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-8_575_rows-blue)](https://getdata.finance/datasets/ukoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ukoil)

### -> [**Download the full UKOIL dataset on getdata.finance**](https://getdata.finance/datasets/ukoil)

**UKOIL 12h OHLCV commodities historical data** — ultra high-quality 12h OHLCV for **Brent Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **Brent Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ukoil) · **8,575** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `UKOIL_12h.csv` (261 rows, `2026-03-12` -> `2026-09-11`, 25.04 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ukoil)** — **8,575** `12h` rows (full `1m`: 5,228,763), **11 timeframes**, `2010-02-01` -> `2026-09-11`.

## Download sample

**[UKOIL_12h.csv](https://github.com/getdata-finance/ukoil-12h-ohlcv-commodities-historical-data/blob/main/UKOIL_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ukoil-12h-ohlcv-commodities-historical-data/main/UKOIL_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/ukoil-12h-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ukoil-12h-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/ukoil-12h-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ukoil](https://getdata.finance/datasets/ukoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ukoil))** |
|---|--:|---|
| Instrument | Brent Crude Oil · Commodities | Brent Crude Oil · Commodities |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 261 | **8,575** |
| Size | 25.04 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Period | `2026-03-12` -> `2026-09-11` | `2010-02-01` -> `2026-09-11` |
| File | `UKOIL_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Coverage report | — | [UKOIL coverage](https://getdata.finance/coverage/ukoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ukoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/ukoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`UKOIL_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T12:00:00+00:00 | 97.687 | 101.572 | 97.441 | 100.981 | 212956 |
| 2026-03-13T00:00:00+00:00 | 100.981 | 102.528 | 98.272 | 98.802 | 156674.44999 |
| 2026-03-13T12:00:00+00:00 | 98.802 | 103.633 | 97.466 | 103.201 | 162943 |
| 2026-03-16T00:00:00+00:00 | 103.201 | 106.187 | 101.812 | 102.928 | 133716.79648 |
| 2026-03-16T12:00:00+00:00 | 102.928 | 103.338 | 99.357 | 100.652 | 170093 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T12:00:00+00:00 | 100.761 | 101.701 | 100.174 | 101.604 | 112524 |
| 2026-09-10T00:00:00+00:00 | 101.604 | 103.439 | 100.18 | 103.439 | 96726 |
| 2026-09-10T12:00:00+00:00 | 103.439 | 109.036 | 103.226 | 108.944 | 155816 |
| 2026-09-11T00:00:00+00:00 | 108.944 | 108.946 | 103.474 | 104.069 | 227804 |
| 2026-09-11T12:00:00+00:00 | 104.069 | 105.551 | 103.72 | 104.731 | 150172 |

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

df = pd.read_csv('UKOIL_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('UKOIL_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('UKOIL_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **UKOIL** archive on **[getdata.finance](https://getdata.finance/datasets/ukoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **8,575** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full UKOIL dataset on getdata.finance](https://getdata.finance/datasets/ukoil)**

---
*GetData · UKOIL 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ukoil)*
