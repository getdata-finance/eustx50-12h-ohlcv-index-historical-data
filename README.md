# EUSTX50 12h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-7_164_rows-blue)](https://getdata.finance/datasets/eustx50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eustx50)

### -> [**Download the full EUSTX50 dataset on getdata.finance**](https://getdata.finance/datasets/eustx50)

**EUSTX50 12h OHLCV index historical data** — ultra high-quality 12h OHLCV for **EURO STOXX 50**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **EURO STOXX 50** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eustx50) · **7,164** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `EUSTX50_12h.csv` (257 rows, `2026-03-26` -> `2026-09-25`, 24.81 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eustx50)** — **7,164** `12h` rows (full `1m`: 2,770,438), **11 timeframes**, `2012-08-27` -> `2026-09-25`.

## Download sample

**[EUSTX50_12h.csv](https://github.com/getdata-finance/eustx50-12h-ohlcv-index-historical-data/blob/main/EUSTX50_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eustx50-12h-ohlcv-index-historical-data/main/EUSTX50_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/eustx50-12h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eustx50-12h-ohlcv-index-historical-data/](https://getdata-finance.github.io/eustx50-12h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eustx50](https://getdata.finance/datasets/eustx50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eustx50))** |
|---|--:|---|
| Instrument | EURO STOXX 50 · Index | EURO STOXX 50 · Index |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 257 | **7,164** |
| Size | 24.81 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Period | `2026-03-26` -> `2026-09-25` | `2012-08-27` -> `2026-09-25` |
| File | `EUSTX50_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Coverage report | — | [EUSTX50 coverage](https://getdata.finance/coverage/eustx50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eustx50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/eustx50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T12:00:00+00:00 | 5612.59 | 5692.1 | 5579.1 | 5609.15 | 25967.4602 |
| 2026-03-27T00:00:00+00:00 | 5609.15 | 5632.16 | 5528.16 | 5553.67 | 16391.81831 |
| 2026-03-27T12:00:00+00:00 | 5553.67 | 5587.66 | 5505.16 | 5506.16 | 28877.61955 |
| 2026-03-30T00:00:00+00:00 | 5506.16 | 5624.21 | 5502.66 | 5577.72 | 17440.81111 |
| 2026-03-30T12:00:00+00:00 | 5577.72 | 5619.22 | 5540.21 | 5567.77 | 27401.60425 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23T12:00:00+00:00 | 6308.81 | 6323.82 | 6269.81 | 6302.32 | 11577 |
| 2026-09-24T00:00:00+00:00 | 6302.32 | 6309.39 | 6255.37 | 6298.89 | 18285 |
| 2026-09-24T12:00:00+00:00 | 6298.89 | 6336.39 | 6275.38 | 6312.44 | 19452 |
| 2026-09-25T00:00:00+00:00 | 6312.44 | 6346.12 | 6312.44 | 6324.11 | 9437 |
| 2026-09-25T12:00:00+00:00 | 6324.11 | 6353.62 | 6296.11 | 6351.65 | 13887 |

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

df = pd.read_csv('EUSTX50_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EUSTX50_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[getdata.finance](https://getdata.finance/datasets/eustx50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **7,164** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full EUSTX50 dataset on getdata.finance](https://getdata.finance/datasets/eustx50)**

---
*GetData · EUSTX50 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eustx50)*
