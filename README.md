# Messy sales CSV/XLSX → clean summary workbook

Apify Actor that turns a messy sales/ledger table into a clean Excel summary (`KPIs`, `ByCategory`, `ByRegion`, `ByMonth`, `CleanDetail`).

- **Run on Apify Store:** https://apify.com/keiwy/messy-sales-to-summary
- **Price:** Pay per event — **$0.10** per successful `summary.xlsx`
- **Sample input:** [`sample_input.csv`](./sample_input.csv) (also [raw gist](https://gist.githubusercontent.com/KEithwy1030/c9aa87a298dbdb64574d07eae43658c3/raw/sample_input.csv))
- **Promo write-up:** https://telegra.ph/Messy-sales-CSV--clean-Excel-summary-010-10-15

## Quick try

1. Open the Store link
2. Paste the sample CSV raw URL into the file input (or upload your own)
3. Run → download `summary.xlsx` from Key-value store

## Columns expected

`date`, `order_id`, `product`, `category`, `quantity`, `unit_price`, `region` (+ optional `currency`)
