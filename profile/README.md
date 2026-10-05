<p align="center">
  <a href="https://tokker.dev"><img src="https://img.shields.io/badge/SITE-TOKKER.DEV-F2B33D?style=for-the-badge&labelColor=101418" alt="Site: tokker.dev"></a>
  <img src="https://img.shields.io/badge/PRICE%20INDEX-IN%20DEVELOPMENT-9AA1AB?style=for-the-badge&labelColor=101418" alt="Price index: in development">
  <a href="https://factory0.ventures"><img src="https://img.shields.io/badge/FACTORY%20ZERO-VENTURE-E8EAED?style=for-the-badge&labelColor=101418" alt="A Factory Zero venture"></a>
</p>

<p align="center">
  <sub>
    <a href="https://github.com/Tokker-dev/tokker">Data and source</a> &nbsp;·&nbsp;
    <a href="https://github.com/Tokker-dev/tokker/blob/main/data/pricing.json">pricing.json</a> &nbsp;·&nbsp;
    <a href="https://github.com/Tokker-dev/tokker/blob/main/docs/plan.md">The plan</a> &nbsp;·&nbsp;
    <a href="https://github.com/Tokker-dev/tokker/issues">Issues</a>
  </sub>
</p>

---

## What AI tokens really cost.

An open price index for AI APIs and AI subscriptions. About 60 API providers quote $ per 1M tokens in
different currencies, with cache, batch, off-peak and regional surcharges. Subscriptions hide their limits in
5-hour windows, weekly caps and fair-use wording. Tokker puts both on one scale: every API price, and every
plan's published limits turned into **$ per 1M tokens at full use**, with the source and the date beside
each number.

As of 2026-10-05 the seed dataset covers 62 API providers (480 offers) and 103 subscription plans from
32 vendors, Western and Chinese side by side. At full use, coding subscriptions come out 20–200× cheaper per
token than the API for the same agentic workload, and the weekly cap, not the 5-hour window, is what runs out.

---

## What exists, and what is planned

| | What it is | Status |
| :--- | :--- | :--- |
| **Dataset** | `pricing.json` and CSVs, every value sourced and dated. CC BY 4.0 (proposed) | `SEED` |
| **Freshness** | Scheduled agents re-check each source daily and open reviewed pull requests with evidence | `PLANNED` |
| **API and MCP** | A free JSON API, `llms.txt`, and an MCP server with `cheapest_provider` and `estimate_cost` | `PLANNED` |
| **Alerts** | Price-drop and limit-change alerts by email or webhook | `PLANNED` |
| **Site** | [tokker.dev](https://tokker.dev): the ticker, the compare tables and the calculator | `PLANNED` |

## Repositories

| Repo | What it is |
| :--- | :--- |
| **[tokker](https://github.com/Tokker-dev/tokker)** | The product, open source: the data, the schema, the freshness loops, the API and MCP on the Cratefield harness, and the plan as issues. Start here |
| **website** | tokker.dev: static HTML on Cloudflare Pages |
| **.github** | This page |

**Get involved.** Every issue in [Tokker-dev/tokker](https://github.com/Tokker-dev/tokker/issues) is written so
one person or one coding agent can finish it in one pull request. Found a wrong price? Open an issue with the
source link.

Free and open first: there are no affiliate links at launch, and if any are added they will be marked and
will never change a ranking.

<p align="center">
  <br>
  <a href="https://tokker.dev"><b>tokker.dev</b></a>
  &nbsp;·&nbsp;
  a <a href="https://factory0.ventures">Factory Zero</a> venture
</p>
