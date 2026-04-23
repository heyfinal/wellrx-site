# WellRX — Sales Site

Public marketing site for [WellRX](https://wellrx.app) — decision support for gas-well operators.

Live at: **https://wellrx.app**

## What this repo contains

- `index.html` — the brochure / main pitch (this is what a visitor sees at the root URL)
- `samples/` — six anonymized sample deliverables linked from the brochure:
  - `01_vendor_daily.html` — The WellRX Daily, Vendor / Operator edition
  - `02_pumper_daily.html` — Field Route Brief
  - `03_q1_review.html` — Quarterly Chemistry Review
  - `04_portfolio_diagnostic.html` — Portfolio Diagnostic (Sample Engagement)
  - `05_foreman_daily.html` — Operations Desk daily
  - `06_photo_diagnosis.html` — Photo / Video Analysis (Iron in Oil)
- `CNAME` — custom domain config for GitHub Pages (`wellrx.app`)

## How it's deployed

Static HTML served via GitHub Pages. No build step, no backend, no cookies.

Source of the content lives in the private `heyfinal/wellrx` repo (`sales/` directory). When a brochure edit lands, re-publish via:

```bash
cp -r /Users/daniel/Desktop/rowan/wellrx/sales/brochure.html  index.html
cp    /Users/daniel/Desktop/rowan/wellrx/sales/samples/*.html samples/
git add -A && git commit -m "publish: refresh from private source" && git push
```

## Contact

- **Chris Rowan** · Co-owner & Sales · 903.932.6584 · sales.wellrx@gmail.com
- **Daniel Gillaspy** · Co-owner, Developer & Drilling Consultant · dgillaspy@me.com
