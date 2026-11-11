# Source & Query Memory

Append-only-ish log. Each entry is one run's takeaways. Keep entries short (3-6 bullets).
Newest entry at the TOP. Before writing a new brief, read this whole file first and let it
bias which sources you hit first and which queries you use.

## How to use this file (read this before every run)
- If a source below is marked GOOD for a data type, try it first.
- If a source is marked BAD/PAYWALLED/STALE, don't waste a search on it for that data type.
- Reuse query phrasings marked GOOD; they're phrasings that actually returned the needed
  figure with a timestamp, not just a headline.
- Rates/FX/commodities levels go stale fast — always note the as-of timestamp you found,
  and prefer sources that show one.

## Starter defaults (no history yet — first run should validate/replace these)
- Reuters, Bloomberg, FT, AP — good for verified headlines on policy/deals/earnings, often
  paywalled beyond headline+lede for FT/Bloomberg; treat the free portion as the citable claim.
- Official sources for data prints: Eurostat, national stats offices (Destatis, INSEE,
  ISTAT, ONS), ECB/Fed/BoE/BoJ press releases — always prefer these over secondhand summaries
  for the actual vs. consensus figures.
- Investing.com / TradingEconomics — decent for quick level checks and consensus figures,
  but cross-check anything market-moving against a tier-1 source before citing as CONFIRMED.
- Exchange/company IR pages — best source for earnings figures, always the tie-breaker on
  beat/miss numbers.

---

## Entries

### 2026-11-11 (first run)
- GOOD: Yahoo Finance / TheStreet / Motley Fool / Washington Post for US index closing levels — query "stock market today November 10 2026 Wall Street close" on extended search returned exact closing table (S&P, Dow, Nasdaq). Standard search was too noisy with mixed-year results.
- GOOD: Applied Materials IR (appliedmaterials.com/newsroom) for official Q3 FY2026 segment data. SEC-API had a thorough breakdown of China revenue share. TIKR blog useful for valuation context and price history, though two articles had conflicting price levels ($333 vs $596 — the $333 was more recent).
- BAD: Standard WebSearch for European index levels returned undated/mixed results. Need to try "site:marketscreener.com" or "site:investing.com" with explicit dates on extended mode next time.
- BAD: Asian market closes (Nikkei/HSI/CSI) not findable for the exact date. Try Reuters Asia market report or CNBC Asia next time.
- BAD: Bond yields (Bund, BTP-Bund, OAT, Gilt) very hard to find for specific dates. Tradeweb snapshots only surfaced for Sept 2026. Try "site:tradeweb.com" or "site:tradingeconomics.com" with "November 2026" next time.
- GOOD: FXStreet for FX levels and macro calendar context — had EUR/USD, GBP/USD, USD/JPY for recent dates. Newsquawk for intraday headlines and commodity snapshots.
- GOOD: Barron's/Morningstar for earnings calendar and season summary (90% reported, 29% Y/Y growth). Digrin.com had a detailed daily earnings calendar.
- Spotlight source: Applied Materials IR press release (official) for segment data; TIKR blog for price/valuation context; SEC-API for China revenue analysis. Logged AMAT 2026-11-11 in spotlight-log.md.
