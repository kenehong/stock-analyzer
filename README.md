# Tech Stock 5-Step Analyzer

A single-page interactive tool for analyzing tech stocks using a structured 5-step framework. Built for investors who want a quick, systematic way to evaluate big tech companies.

**[Live Demo](https://kenehong.github.io/stock-analyzer/)**

![Tech Stock Analyzer](https://img.shields.io/badge/Chart.js-4.4-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## What It Does

Enter a company's financial data and get an instant A-F grade across five dimensions. The tool compares each metric against sector-specific benchmarks and generates actionable insights automatically.

### The 5-Step Framework

| Step | Question | Key Metrics |
|------|----------|-------------|
| **1. Valuation** | Is it expensive? | P/E, Forward P/E, P/S, PEG, EV/EBITDA |
| **2. Growth** | Is it growing? | Revenue Growth, EPS Growth |
| **3. Profitability** | Does it make money? | Gross Margin, Operating Margin |
| **4. Cash Flow** | Is real cash coming in? | FCF, OCF/Net Income ratio |
| **5. Business Health** | Is the business sustainable? | Rule of 40, NRR (SaaS only) |

## Features

- **Pre-loaded data** for 8 major companies (AAPL, MSFT, GOOGL, AMZN, NVDA, META, TSLA, AMD)
- **Manual input** for any company
- **Sector-aware grading** with 4 benchmark sets (Big Tech, Semiconductor, SaaS, Hardware)
- **Radar chart** for visual 5-dimension comparison
- **Auto-generated insights** that flag strengths and red flags
- **Benchmark table** showing where the company stands vs. sector averages

## Quick Start

1. Open `index.html` in a browser (or visit the [live demo](https://kenehong.github.io/stock-analyzer/))
2. Click a company card (e.g., NVDA) — data auto-fills
3. Click **분석하기** (Analyze)
4. Review the dashboard: overall grade, step-by-step breakdown, insights

For manual analysis, click **+ 직접 입력**, enter the financials, and hit analyze.

## Where to Find the Data

All metrics can be found for free on:

| Source | Best For |
|--------|----------|
| [StockAnalysis.com](https://stockanalysis.com) | P/E, P/S, margins, growth rates |
| [Finviz.com](https://finviz.com) | Quick overview, Forward P/E, PEG |
| [Macrotrends.net](https://macrotrends.net) | Historical financials, FCF, OCF |
| [Yahoo Finance](https://finance.yahoo.com) | Real-time data, EV/EBITDA |
| [SEC EDGAR](https://www.sec.gov/edgar) | Official filings (10-K, 10-Q) |

## Grading System

Each metric is graded A through F based on sector-specific thresholds:

- **A** — Excellent (top tier for the sector)
- **B** — Good (above average)
- **C** — Fair (around average)
- **D** — Below average (needs attention)
- **F** — Poor (significant concern)

The overall grade is a weighted average:

| Step | Weight |
|------|--------|
| Valuation | 25% |
| Growth | 25% |
| Profitability | 20% |
| Cash Flow | 20% |
| Business Health | 10% |

## Tech Stack

- Vanilla HTML/CSS/JS (no build tools, no dependencies to install)
- [Chart.js 4.4](https://www.chartjs.org/) for radar chart visualization
- Single file, fully self-contained

## Disclaimer

This tool is for **educational purposes only** and does not constitute investment advice. Pre-loaded data is approximate and may not reflect current market conditions. Always verify data from official sources before making investment decisions.

## License

MIT
