# Retail pass-through in Japan

How much of the yen's depreciation and rising import prices reached Japanese retail prices, item by item?

**Status:** work in progress (started November 2026).

## Question
When import prices rise, how much of the increase shows up on the shelf, and how fast? Which items pass costs through fully, and which absorb them?

## Data (all public)
| Source | What | Where |
|---|---|---|
| 小売物価統計調査 (Retail Price Survey) | Monthly item prices by city | e-Stat |
| 輸入物価指数 (Import Price Index) | Monthly import prices | Bank of Japan |
| Yen/dollar exchange rate | Monthly average | Bank of Japan |

Raw data is not committed. See `data/README.md` for how to download it.

## Method
_To be written: distributed-lag regression of item price changes on import price changes, with item fixed effects._

## Results
_None yet._

## Repository layout
```
data/        raw and intermediate data (not in Git)
src/         SQL and Python that build every table from the raw files
notebooks/   exploration only; anything that matters moves to src/
```

## Reproduce
_To be written: one command rebuilds everything from the raw files._
