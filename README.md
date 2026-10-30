# Crypto volume analysis across centralised exchanges

> **Archived learning exercise (2022).** Kept as-is; not maintained and not part of the current portfolio.

An ETL notebook (`Final.ipynb`) that pulls market and price data for centralised exchanges through the Cryptowatch API client, loads it into pandas, and charts trading volume with Plotly. Steps are laid out as ETL 1 to n in the notebook headings: install and authenticate, list active markets, fetch USDT prices for the main assets excluding stablecoins and fiat, then aggregate and plot.

The Cryptowatch service has since been discontinued, so the data-fetching cells no longer run as written. The transformation and charting cells still show the approach.

## Run it

Open the notebook in Jupyter with `pandas`, `numpy`, `plotly` and `requests` installed. A Cryptowatch API key was required at the time.

## Current work

This repo is kept for the record and is not maintained. Current data engineering projects start at https://github.com/nathanmars7/dbt-analytics-engineering, which links the rest of the portfolio.
