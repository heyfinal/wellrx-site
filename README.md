# WellRX — AI-Powered Daily Diagnostics for Gas-Well Operators

**[wellrx.app](https://wellrx.app)** — Decision support for small-to-mid-size natural gas operators.

WellRX connects to your SCADA system, reads every active well's live telemetry, cross-references production historian and chemical field service records, and delivers a role-tailored diagnostic + recommended actions to your entire team before 6:30 AM CT — every morning, automatically.

## What it does

- **Pulls live data** from SCADA (zdSCADA and REST/OData APIs), historian exports, and FSR logs
- **Runs a virtual AI petroleum + production + chemical engineering team** against every covered well
- **Detects** liquid loading, paraffin/asphaltene issues, compressor anomalies, pressure deviations, chemical program drift, artificial lift problems, gathering bottlenecks, and RTU/communication faults
- **Delivers role-specific Rx** — pumper field card, production engineer write-up, chemical vendor Rx, executive summary — all from the same diagnostic engine, each formatted for its recipient
- **Bills per active well** — offline/unreachable wells aren't counted; month-to-month, no long-term contract

## Who it's for

Gas-well operators running 20–300 active wells in the US (TX, OK, LA, PA). If your pumpers are reading raw SCADA tags on a phone screen and your engineers are stretched across more wells than they can manually review, WellRX is the overnight engineering team that fills the gap.

## This repo

Static marketing site served via GitHub Pages at [wellrx.app](https://wellrx.app).

```
index.html          — main product page
quote/              — interactive ROI-grounded quote calculator
beta/               — charter partner enrollment
samples/            — anonymized sample deliverables (real artifacts, scrubbed identifiers)
  01_vendor_daily.html        — WellRX Daily, Vendor / Operator edition
  02_pumper_daily.html        — Field Route Brief (pumper)
  03_q1_review.html           — Quarterly Chemistry Review
  04_portfolio_diagnostic.html — Portfolio Diagnostic (sample engagement)
  05_foreman_daily.html       — Operations Desk daily
  06_photo_diagnosis.html     — Photo / Video Analysis
sitemap.xml         — search engine sitemap
```

No build step. No backend. No cookies. Pure static HTML.

## Contact

- **Chris Rowan** · CRO, Production Chemical Consultant · 903.932.6584 · sales.wellrx@gmail.com · Longview, TX
- **Daniel Gillaspy** · CEO, Developer & Drilling Consultant · wellrx@wellrx.app · Oklahoma City, OK

---

*AI production diagnostics · SCADA integration · gas well monitoring · petroleum engineering decision support · East Texas · South Texas · Oklahoma · Louisiana · Pennsylvania*
