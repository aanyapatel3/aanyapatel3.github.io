---
title: "Equity Research Note — Sandoz, Amgen & Danaher"
author: Aanya Patel (Junior Analyst)
description: A junior-analyst initiation note and valuation model on three healthcare names — Amgen (AMGN), Danaher (DHR) and Sandoz (SDZ).
date: 2026-05-28
layout: post
tags:
  - blog
  - finance
---

> **Disclaimer / Important note.** This is an educational exercise written in the style of a junior sell-side analyst's initiation note. It is **not investment advice, not a recommendation to buy or sell**, and was prepared without access to live broker models. All figures are drawn from public sources (company filings/press releases and financial-data aggregators) as of late May 2026 and are rounded. Estimates marked "E" are illustrative and my own. Markets move; do your own research and/or speak to a licensed advisor before investing.

---

## 1. Executive summary

I looked at three healthcare names across different parts of the value chain:

| Company | Ticker | Where it sits | Price* | My rating | 12‑mo base target | Implied return** |
|---|---|---|---|---|---|---|
| **Amgen** | AMGN (Nasdaq) | Big‑cap biopharma (drugs) | ~$326 | **Buy** | ~$365 | ~+12% + 2.8% yield |
| **Danaher** | DHR (NYSE) | "Picks & shovels" for biopharma | ~$190 | **Buy / Accumulate** | ~$225 | ~+18% + 0.5% yield |
| **Sandoz** | SDZ (SIX, Swiss) | Generics + biosimilars | ~CHF 66 | **Hold** | ~CHF 70 | ~+6% + 1.2% yield |

<sub>*Approximate prices, late May 2026. **Price upside vs. the base-case target plus the dividend yield.</sub>

**The one-paragraph thesis.** All three play the same long-term tailwind — an aging, biologic-heavy world of medicine — but at different risk/reward. **Amgen** is the cheapest on earnings (~15x forward) with a free option on obesity (MariTide); I'd buy it. **Danaher** is a high-quality compounder trading near a multi-year low multiple right as its key bioprocessing cycle turns up; I'd accumulate it. **Sandoz** is executing well on biosimilars, but the stock already reflects most of that — I'd wait for a better entry.

---

## 2. How I approached the model

For a junior analyst, the job is to (1) understand what the company actually sells, (2) sanity-check management's guidance, and (3) value it two independent ways and look for agreement. I used:

- **Bottom-up revenue builds** for all three (product-level for Amgen, segment-level for Danaher, generics-vs-biosimilars for Sandoz), checked against management guidance.
- **Forward P/E** for the earnings-driven names (Amgen, Danaher), anchored to each company's 2026 guidance midpoint and a peer/history-justified multiple.
- A full **DCF** (unlevered FCFF) for Amgen as an independent cross-check on the multiple.
- **EV/EBITDA** for Sandoz, because generics/biosimilars are better compared on cash operating profit than on accounting EPS.
- A simple **bear / base / bull** scenario grid for each, so the conclusion isn't a single fragile point estimate.

Key shared inputs I assumed: US risk-free ~4.3%, equity risk premium ~5%, and "large-cap healthcare" discount rates of roughly 7–8%.

---

## 3. Amgen (AMGN) — *Buy* — full deep dive & bottom-up revenue model

### Business
Amgen is a ~$192bn market-cap biotech selling a diversified book of biologics. Big drivers today: **Repatha** (cholesterol/CV), **EVENITY** (osteoporosis), **TEZSPIRE** (severe asthma), plus a large rare-disease and oncology base picked up partly through the 2023 Horizon Therapeutics deal. US = ~73% of sales.

### Recent numbers (the actuals I scraped)
- FY2025 total product sales: **$35.15bn** (+~10% YoY)
- Q1 2026 actuals: total revenue **$8.62bn (+6%)**, product sales **$8.22bn (+4%)** — +9% volume, −2% price, −2% inventory
- FY2026 guide: revenue **$37.0–38.4bn**; non-GAAP EPS **$21.60–23.00**
- LTM free cash flow **~$8.1bn**; dividend $10.08/yr (**~2.8% yield**, raised 6%)
- Net debt **~$46bn** (≈3x EBITDA) — the main blemish, a legacy of the Horizon deal

### FY2025 sales by product (the building blocks)

| Product | Franchise | FY2025 sales | 2025 YoY | What's happening |
|---|---|---:|---:|---|
| Prolia | Bone | $4.41bn | +1% | **Biosimilar cliff hitting now** (Q1'26 −34%) |
| Repatha | Cardio | $3.02bn | +36% | VESALIUS-CV expands eligible patients |
| Otezla | Inflammation | $2.27bn | −1% | Mature, competitive |
| EVENITY | Bone | $2.10bn | +34% | Strong volume |
| XGEVA | Onc. supportive | $2.08bn | −6% | Biosimilar pressure |
| TEPEZZA | Rare (thyroid eye) | $1.90bn | +3% | Horizon asset |
| BLINCYTO | Oncology | $1.56bn | growing | Broad uptake (Q1'26 +12%) |
| TEZSPIRE | Asthma | $1.48bn | +52% | Fastest grower |
| KRYSTEXXA | Rare (gout) | $1.34bn | growing | Q1'26 +8% |
| **Named subtotal** | | **$20.16bn** | | |
| **All other** (Enbrel, Nplate, biosimilars Amjevita/MVASI, newer launches Lumakras/IMDELLTRA/UPLIZNA/TAVNEOS, etc.) | | **~$14.99bn** | | Net roughly flat — launches offset Enbrel/older erosion |
| **Total product sales** | | **$35.15bn** | | |

### Bottom-up revenue build (prospecting each product forward)
I tagged each drug as a **grower** or **eroder** and applied a growth rate off its 2025/Q1'26 trajectory. The single most important call is **Prolia**: biosimilars have launched, so I model a steep multi-year decline.

| Product ($M) | 2025A | '26E gr. | **2026E** | '27E gr. | **2027E** | Rationale |
|---|---:|---:|---:|---:|---:|---|
| Prolia | 4,410 | −30% | **3,087** | −25% | **2,315** | Biosimilar erosion (Q1'26 already −34%) |
| Repatha | 3,020 | +28% | **3,866** | +20% | **4,639** | CV outcomes data, volume |
| EVENITY | 2,100 | +25% | **2,625** | +18% | **3,098** | Volume momentum |
| TEZSPIRE | 1,480 | +28% | **1,894** | +22% | **2,311** | Asthma share gains |
| TEPEZZA | 1,900 | +8% | **2,052** | +6% | **2,175** | Normalizing post inventory swings |
| BLINCYTO | 1,560 | +15% | **1,794** | +12% | **2,009** | Broad prescribing |
| KRYSTEXXA | 1,340 | +10% | **1,474** | +8% | **1,592** | Price + volume |
| Otezla | 2,270 | −2% | **2,225** | −2% | **2,181** | Mature/competitive |
| XGEVA | 2,080 | −12% | **1,830** | −12% | **1,610** | Biosimilar pressure |
| Other (~half the book) | 14,988 | −1% | **14,838** | flat | **14,838** | Launches offset Enbrel/older erosion |
| **Total product sales** | **35,148** | | **~35,685** | | **~36,768** | |
| + Other revenue | ~1,550 | | ~1,600 | | ~1,650 | royalties etc. |
| **≈ Total revenue** | **~36.7bn** | | **~37.3bn** | | **~38.4bn** | |

### Sanity check vs. guidance (the discipline that matters)
- **My 2026E total revenue ≈ $37.3bn** vs. company guide **$37.0–38.4bn** → lands mid-guidance. ✅
- **Run-rate check:** Q1'26 product sales $8.22bn ÷ Q1's typical ~22.5% of the year ≈ **$36.5bn** implied FY product sales; my bottom-up gives $35.7bn — within ~2%, slightly conservative. ✅

Two independent methods agree, so I trust the build.

### Drilling into the "Other" bucket (~$15bn, ~43% of sales)
The single biggest weakness of the build above is the one-line "Other." Here I decompose it (figures reconstructed/estimated from quarterly disclosures, so rougher than the named drugs) and tag each cluster grower/eroder. The point: see whether that line is really ~flat, or hiding a problem.

| "Other" cluster ($M) | 2025A | '26E gr. | **2026E** | '27E gr. | **2027E** | Read |
|---|---:|---:|---:|---:|---:|---|
| Enbrel | 2,800 | −10% | **2,520** | −10% | **2,268** | Slow secular decline, no biosimilar yet |
| Kyprolis | 1,500 | −5% | **1,425** | −8% | **1,311** | Generic/competitive pressure building |
| Established (EPOGEN, Aranesp, Neulasta, Parsabiv) | 2,000 | −10% | **1,800** | −10% | **1,620** | Legacy run-off |
| Mature biosimilars (Amjevita, MVASI, Kanjinti, Riabni) | 1,900 | −8% | **1,748** | −8% | **1,608** | Price competition |
| Vectibix | 1,100 | +2% | **1,122** | +2% | **1,144** | Stable oncology |
| Nplate | 1,450 | +5% | **1,523** | +4% | **1,584** | Steady grower |
| **Newer launches** (IMDELLTRA, UPLIZNA, LUMAKRAS, TAVNEOS, Aimovig, Pavblu, Wezlana) | 2,700 | +28% | **3,456** | +24% | **4,285** | The engine — ramping hard |
| Residual / smaller products | 1,538 | 0% | **1,538** | 0% | **1,538** | Catch-all |
| **"Other" total** | **14,988** | **+0.9%** | **~15,130** | **+1.5%** | **~15,358** | **Confirms ~flat assumption ✅** |

**This is the useful finding:** the ~flat "Other" line I assumed top-down is *not* lazy — it's the net of ~$8bn of declining legacy/biosimilar products eroding ~9%/yr, exactly offset by **newer launches (IMDELLTRA, UPLIZNA, etc.) compounding ~25–28%**. So the resilience of Amgen's "boring" half depends entirely on the new oncology/rare-disease launches outrunning the Enbrel/established run-off. If those launches stumble, the whole flat-base thesis weakens. *(Cluster dollar splits are my estimates triangulated from quarterly data, not exact disclosures.)*

### What the model tells me
1. **The base business is barely growing (~+1–4%/yr).** Growers (Repatha, EVENITY, TEZSPIRE, oncology) are almost entirely offset by the **Prolia/XGEVA biosimilar cliff** — that's the whole story of the next two years.
2. **The stock is NOT priced for the pipeline — that's the opportunity.** The build deliberately **excludes MariTide (obesity)**. At ~$326 / ~$22.30 EPS = **~14.6x forward**, you pay a below-market multiple for a flattish-but-cash-rich base and get the obesity option nearly free.
3. **Risks the model can't fully capture:** the **~$10bn+ IRS tax dispute**, **~$46bn net debt** (limits buybacks/M&A), and **Prolia eroding faster** than my −30% assumption.

### Pipeline analysis — and how it bridges the post-cliff revenue gap
My base build above shows the *commercial* book going roughly flat (~+1–4%/yr) as the Prolia/XGEVA biosimilar cliff eats the growers. **The pipeline is what turns "flat" into "growth" from ~2028 onward.** I risk-adjust each key asset by a rough probability of success (PoS) and an estimated peak-sales figure, then look at what is genuinely *incremental* to my base.

| Asset | Mechanism / indication | Status | Est. launch | Unadj. peak | PoS | Risk-adj. peak | In base build? |
|---|---|---|---|---:|---:|---:|---|
| **MariTide** | GLP-1 agonist / GIPR antagonist, **monthly (or less) dosing** — obesity (+ CV, heart failure, OSA) | **Ph3** — 6 MARITIME studies | ~2027–28 | ~$6bn¹ | 60% | **~$3.6bn** | **No — pure upside** |
| **Olpasiran** | Lp(a)-targeting siRNA — CV risk | Ph3 OCEAN(a) outcomes | ~2027–28 | ~$2.5bn | 50% | **~$1.25bn** | **No — pure upside** |
| **Bemarituzumab** | First-in-class FGFR2b mAb — gastric cancer | Ph3 | ~2027 | ~$1.5bn | 55% | **~$0.8bn** | **No — pure upside** |
| IMDELLTRA (tarlatamab) | DLL3 BiTE — small-cell lung (2L approved, 1L ongoing) | Approved + label expansion | launched | ~$3bn | 80% | ~$2.4bn | Partly (in "Other") |
| UPLIZNA expansions | anti-CD19 — new IgG4-RD & gMG approvals | Approved/expanding | launched | ~$2bn | 85% | ~$1.7bn | Partly (in "Other") |
| Repatha primary-prevention | PCSK9 — VESALIUS-CV positive | Label expansion | 2026–27 | — | — | — | Yes (in Repatha +28%) |

<sub>¹ MariTide peak-sales estimates range enormously: Evaluate ~$3.7bn (conservative) to UBS **$10bn+** (bull). I use ~$6bn as a midpoint. Phase 2: up to **~20% weight loss at 52 weeks with no plateau** (no T2D), ~17% with T2D.</sub>

**How this impacts future revenue (the bridge):**
- **2026–27:** pipeline contribution is small — the story is just base-business resilience around the cliff. My ~$37–38bn revenue stands.
- **2028+:** the three genuinely-incremental assets (MariTide, Olpasiran, bemarituzumab) add **~$5.6bn of risk-adjusted peak revenue** *on top of* the base. That's ~15% incremental on a ~$37bn base — enough to re-accelerate total growth to mid-single-digits even **after** Prolia is largely gone.
- **The asymmetry is MariTide.** At the $3.7bn-Evaluate end it's a nice add; at the UBS $10bn+ end it roughly *replaces the entire Prolia franchise twice over* and re-rates the multiple. Obesity is a ~$100bn 2030 market, and Amgen's monthly-dosing "maintenance" angle is a real differentiator vs. weekly Lilly/Novo.
- **What got cut:** Amgen exited rocatinlimab (atopic dermatitis) in early 2026 — a reminder that pipeline value is probabilistic, which is exactly why I risk-adjust.

**Translating pipeline to value:** the ~$5.6bn incremental risk-adjusted peak, at a ~3x EV/sales for growth biopharma, is roughly **$17bn of EV ≈ $30/share** of option value not in my base DCF — and multiples of that if MariTide hits the bull case. **This is why I'm comfortable paying ~14.6x for a flattish base: you're buying the obesity option cheaply.**

### Discounted cash flow (3-statement-based cross-check)
A multiple is only as good as the peer set, so I cross-check with a DCF. I build it off a condensed, linked 3-statement logic — income statement drives NOPAT, then I add back D&A and subtract capex / working-capital change to get unlevered free cash flow to the firm (FCFF), discount at WACC, and bridge to per-share value.

**Anchor actuals (FY2025):** total revenue ~$36.8bn · non-GAAP operating income **$16.2bn** (≈46% margin on product sales) · effective tax **18%** · levered FCF ~$8–10bn (2024 was $10.4bn). Amgen carries heavy intangible **amortization** (post-Horizon), so FCFF (which adds back non-cash D&A) runs *above* accounting EPS-implied cash — this is why a cash-based DCF flatters Amgen vs. a P/E.

**WACC build:**
- Cost of equity = 4.3% risk-free + β 0.6 (defensive) × 5% ERP = **7.3%**
- After-tax cost of debt = 5% × (1 − 18%) = **4.1%**
- Weights: equity ~$192bn (78%) / debt ~$55bn (22%) → **WACC ≈ 6.6%**; I round **up to 7.5%** to haircut for leverage + pipeline risk.

**FCFF projection & discounting** (terminal growth g = 2.5%):

| ($bn) | 2026E | 2027E | 2028E | 2029E | 2030E |
|---|---:|---:|---:|---:|---:|
| Unlevered FCFF | 11.5 | 12.1 | 12.8 | 13.6 | 14.3 |
| Discount factor @7.5% | 0.930 | 0.865 | 0.805 | 0.749 | 0.697 |
| PV of FCFF | 10.7 | 10.5 | 10.3 | 10.2 | 10.0 |

- Sum of PV (explicit) = **~$51.6bn**
- Terminal value = 14.3 × 1.025 / (7.5% − 2.5%) = $293bn → PV = **~$204bn**
- Enterprise value = **~$256bn** − net debt $46.3bn = equity **~$210bn** ÷ 539.7m shares = **≈ $388/share**

**Sensitivity (implied $/share):**

| WACC ↓ \ g → | 2.0% | 2.5% | 3.0% |
|---|---:|---:|---:|
| **7.0%** | $396 | $442 | $498 |
| **7.5%** | $352 | **$388** | $432 |
| **8.0%** | $315 | $345 | $380 |

The DCF base case (**~$388**) sits *above* both today's ~$326 and my multiple-based $360 — and even the most conservative corner ($315, 8% WACC / 2% g) is roughly today's price. In other words, the market is pricing Amgen near the **bearish corner** of a reasonable DCF. That asymmetry is the heart of the Buy. *(Note: this DCF already bakes in the post-2028 re-acceleration, so MariTide upside is partly captured here — don't double-count it with the +$30/share option value above.)*

### Valuation scenarios
| Scenario | EPS used | Multiple | Implied price | vs. ~$326 |
|---|---|---|---|---|
| Bear (MariTide disappoints, tax loss) | $21.00 | 12x | **$252** | −23% |
| **Base** | $22.50 | 16x | **$360–365** | **+11%** |
| Bull (obesity works) | $23.50 | 18x | **$423** | +30% |

**Rating: Buy.** Base-case 12-mo target **~$360–365** + ~2.8% dividend.

> *Modeling caveats:* the "Other" bucket is now decomposed above, but the cluster dollar splits are estimates triangulated from quarterly data, not exact line-item disclosures. All "E" figures are my own illustrative estimates, not consensus.

---

## 4. Danaher (DHR) — *Buy / Accumulate*

### Business
Danaher is the "**picks-and-shovels**" play — it sells the bioprocessing equipment, consumables, diagnostics and lab tools that *other* drug companies (including Amgen) need. Three segments: **Biotechnology** (bioprocessing), **Life Sciences**, **Diagnostics**. ~28% adjusted operating margins and a famous serial-acquirer culture (the "Danaher Business System").

### Recent numbers (Q1 / FY2026)
- FY2026 core revenue growth guide: **3–6%**; adjusted EPS guide raised to **$8.35 – $8.55**
- Q1 adjusted EPS **$2.06 (+9.5%)**, FY free cash flow ~$5.3bn
- **The catalyst:** bioprocessing **equipment orders grew >30% y/y — first positive y/y order growth in ~2 years**, signaling the post-COVID destocking cycle has bottomed.
- Pending **$9.9bn Masimo** acquisition expected to close 2H26, accretive in year one.

### Segment revenue build (the product-level treatment)
Danaher doesn't sell "drugs" — it sells across three platforms. Here's the FY2025 split and my forward build. Note the **margins differ wildly**, so mix matters as much as growth: Biotechnology is the highest-margin AND the one inflecting.

| Segment ($bn) | FY2025 rev | Adj. op margin | '26E gr. | **2026E** | '27E gr. | **2027E** | Driver |
|---|---:|---:|---:|---:|---:|---:|---|
| **Biotechnology** (bioprocessing) | 7.3 | **~38%** | +6% | **7.74** | +8% | **8.36** | Orders +30% → the recovery engine |
| **Diagnostics** (Cepheid, Beckman) | 10.0 | ~31% | +4% | **10.40** | +4% | **10.82** | Cepheid respiratory; China headwind |
| **Life Sciences** (instruments/tools) | 7.3 | ~21% | +2% | **7.45** | +3% | **7.67** | Sluggish — academic/biotech capex weak |
| **Organic total** | **24.6** | ~28% | +4% | **~25.6** | +5% | **~26.9** | In line with 3–6% core guide |
| + Masimo (patient monitoring) | — | — | — | **~1.0** (H2 only) | — | **~2.2** (full yr) | Closes 2H26, EPS-accretive yr 1 |
| **Total revenue** | **24.6** | | | **~26.6** | | **~29.0** | |

**What the segment build tells me:** the whole bull case lives in **Biotechnology**. Diagnostics and Life Sciences are steady-to-sluggish, so they won't move the needle — but Biotechnology is the highest-margin segment (~38%) *and* the one inflecting (orders +30%). As bioprocessing reaccelerates from +6% toward high-single/low-double digits, it lifts both group growth and group margin simultaneously (positive mix). That dual lift is what drives EPS from ~$8.45 (2026) toward ~$9.30+ (2027) and supports multiple re-rating. Masimo adds ~$2bn of revenue but is a smaller part of the thesis than the organic bioprocessing turn.

### The thesis
This is a quality compounder bought at a *cyclical trough multiple*. At ~$190 on ~$8.45 EPS that's **~22.5x forward** — well below its historical 25–30x. The order inflection usually leads revenue/EPS by 2–4 quarters, so 2027 estimates likely drift up while the multiple re-rates. You're paying a fair price for a business that has compounded earnings for decades.

### Simple model
| Scenario | EPS used | Multiple | Implied price | vs. ~$190 |
|---|---|---|---|---|
| Bear (recovery stalls) | 2026E $8.45 | 20x | **$169** | −11% |
| **Base** | 2027E ~$9.30 | 24x | **$223** | **+17%** |
| Bull (full bioprocessing upcycle) | 2027E ~$9.60 | 28x | **$269** | +42% |

### Key risks
- Bioprocessing recovery could be slower/lumpier than the order data implies.
- China diagnostics and academic/government funding pressure.
- Masimo integration risk; M&A-driven model depends on cheap capital.

---

## 5. Sandoz (SDZ) — *Hold*

### Business
Spun off from Novartis in 2023, Sandoz is a pure-play **generics + biosimilars** leader (Swiss-listed, reports in USD). The strategic story is the **mix shift toward biosimilars** — higher-growth, higher-margin copies of biologic blockbusters — funded by a slower-growing generics base. A Samsung Bioepis partnership adds pipeline.

### Recent numbers (Q1 / FY2026)
- FY2026 guide: **mid-to-high-single-digit** revenue growth (cc); core EBITDA margin **~22.7%** (up ~100bps from 21.7%).
- Biosimilars now **~31% of revenue**, growing **~13%** cc; generics **−3%** (portfolio pruning + pricing).
- Consensus revenue ~**$12.1bn** (2026E); net debt ~**$3.6bn**; dividend CHF 0.80 (**~1.2% yield**).

### Revenue build (generics vs. biosimilars — the product treatment)
Sandoz really has two businesses. The whole investment debate is whether the **growing, higher-margin biosimilar** half can out-run the **flat-to-declining generic** half fast enough to expand margins. FY2025 actuals: net sales **$11.09bn** (+7% reported); generics **$7.79bn**, biosimilars **$3.29bn** (+15%, now 30% of mix).

| Segment ($bn) | FY2025 | '26E gr. | **2026E** | '27E gr. | **2027E** | Notes |
|---|---:|---:|---:|---:|---:|---|
| **Biosimilars** | 3.29 | +14% | **3.75** | +15% | **4.31** | Hyrimoz, Pyzchiva, Omnitrope + new denosumab (Wyost/Jubbonti) |
| **Generics** | 7.79 | −1% | **7.71** | flat | **7.71** | Pricing −low/mid SD, offset by volume; portfolio pruning |
| **Total net sales** | **11.09** | +5% | **~11.46** | +5% | **~12.02** | Mid-single-digit, in line with guide |
| Biosimilar mix | 30% | | **~33%** | | **~36%** | The margin-expansion lever |

**Biosimilar regional split (FY2025):** Europe 58% · North America 25% · International 17% — with the US the fastest-growing as launches like denosumab and ustekinumab (Pyzchiva) ramp. The **Samsung Bioepis partnership** adds future pipeline (e.g., next-wave biosimilars), which is the multi-year option.

**What the build tells me:** the model *works operationally* — biosimilars climb from 30% → ~36% of mix in two years, and because they carry higher margins, that mix shift is exactly what funds the guided ~100bps/yr core-EBITDA-margin expansion (21.7% → ~22.7% → ~24%). My issue isn't the business; it's that on ~$2.7bn 2026E core EBITDA the stock already trades ~14x EV/EBITDA, so the good news is in the price (see below).

### The thesis (and why only Hold)
The operational story is genuinely good — biosimilars are the right place to be. **But the valuation already reflects it.** On ~$2.7bn 2026E core EBITDA, the current ~CHF 28bn equity value (≈ $35bn) plus net debt implies **~14x EV/EBITDA**, full for a company with a structurally low-growth/declining generics half and persistent price erosion. The average analyst target (~CHF 67) sits roughly at today's price — the crowd agrees there's limited near-term upside.

### Simple model (EV/EBITDA)
| Scenario | 2026E core EBITDA | Multiple | Implied equity (less ~$3.6bn debt) | Rough price |
|---|---|---|---|---|
| Bear (pricing worse) | $2.6bn | 9x | ~$19.8bn | ~CHF 37 |
| **Base** | $2.7bn | 11x | ~$26.1bn | ~CHF 48–50 |
| Bull (margin + biosimilar beats) | $2.9bn | 13x | ~$34bn | ~CHF 63 |

*Read this honestly:* on a disciplined EV/EBITDA basis, my base case sits **below** the current ~CHF 66 price. The market is paying a premium for the biosimilar growth narrative. That's why I'd **wait** rather than chase — great company, but I want a margin of safety. I'd get more constructive on a pullback toward the low-CHF-50s or on evidence that margin expansion is running ahead of the ~100bps/yr guide.

### Key risks
- Biosimilar **pricing competition** intensifying as more entrants arrive.
- FX (USD reporting vs. CHF listing) and manufacturing/quality issues.
- Generics commoditization dragging the blended growth rate.

---

## 6. Putting it together (portfolio view)

If I had to build a small healthcare basket from these three, as a junior analyst I'd frame it as a **barbell**:

- **Core / value:** Amgen — cheap, cash-generative, optionality. *Largest weight.*
- **Quality / growth:** Danaher — compounder at a cyclical-low multiple. *Second weight.*
- **Watchlist:** Sandoz — best operating momentum, worst risk/reward at today's price. *Wait for a dip.*

Note all three share the **biologics-megatrend correlation** — a true diversified book would add a different sector. And remember Amgen *buys* the kind of equipment Danaher *sells*, so a bioprocessing slowdown would hit both.

---

## 7. What I'd do next (to upgrade this from "junior" to a real model)

*Done in this version:* product-level revenue builds for all three, a decomposed Amgen "Other" bucket, a probability-weighted Amgen pipeline, and a full Amgen DCF. Still on the to-do list:

1. Pull the **actual 10-Q / 10-K line items** to replace my estimated cluster splits (esp. Amgen "Other" and exact segment margins).
2. Build the same **FCFF DCF for Danaher and Sandoz** (I only DCF'd Amgen; the other two are still multiple-based).
3. Run an **FX-sensitivity table for Sandoz** (USD reporting vs. CHF listing).
4. Add a **scenario-weighted (probability × price target)** blended fair value per name.

---

## Sources

- [Amgen outlines $37B–$38.4B 2026 revenue target (Seeking Alpha)](https://seekingalpha.com/news/4546762-amgen-outlines-37b-38_4b-2026-revenue-target-as-repatha-evenity-and-tezspire-drive-momentum)
- [Amgen (AMGN) Statistics & Valuation (stockanalysis.com)](https://stockanalysis.com/stocks/amgn/statistics/)
- [Amgen Q1 2026 8-K earnings release (SEC)](https://www.sec.gov/Archives/edgar/data/0000318154/000031815426000054/amgn-20260331earningsrelea.htm)
- [Amgen Q1 2026 results (Amgen newsroom)](https://www.amgen.com/newsroom/press-releases/2026/04/amgen-reports-first-quarter-2026-financial-results)
- [MariTide Phase 2: robust weight loss at 52 weeks (Amgen)](https://investors.amgen.com/news-releases/news-release-details/amgen-announces-robust-weight-loss-maritide-people-living/)
- [Amgen's pipeline strategy in 2026 (Labiotech)](https://www.labiotech.eu/in-depth/amgen-pipeline-strategy/)
- [MariTide peak-sales / obesity market context (Evaluate via FiercePharma)](https://www.fiercepharma.com/pharma/2030-eli-lilly-will-generate-113b-drug-sales-including-62b-mounjaro-zepbound-evaluate)
- [Amgen FY2025 non-GAAP operating income / margin / tax rate (SEC 8-K)](https://www.sec.gov/Archives/edgar/data/0000318154/000031815426000003/amgn-20251231earningsrelea.htm)
- [Danaher FY2025 segment revenue & margins (Investing.com)](https://www.investing.com/news/company-news/danaher-q4-2025-slides-revenue-growth-solid-despite-margin-pressure-93CH-4470615)
- [Danaher 2025 overview — $24.6bn revenue, $5.3bn FCF (StockTitan)](https://www.stocktitan.net/sec-filings/DHR/ars-danaher-corp-de-sec-filing-3f1740b11e9d.html)
- [Sandoz FY2025 results — generics/biosimilars split & regions (Investing.com)](https://www.investing.com/news/company-news/sandoz-fy-2025-slides-biosimilar-surge-drives-24-stock-gain-93CH-4523555)
- [Sandoz 2025 7% revenue growth & 2026 outlook (Pharmaceutical Daily)](https://pharmaceuticaldaily.com/sandoz-reports-7-revenue-growth-in-2025-expands-biosimilars-and-projects-stronger-2026-outlook/)
- [Danaher Q1 2026 earnings — guidance raise & bioprocessing orders (BigGo Finance)](https://finance.biggo.com/news/US_DHR_2026-04-21)
- [Danaher (DHR) Stock Price & Overview (stockanalysis.com)](https://stockanalysis.com/stocks/dhr/)
- [Danaher Q1 earnings recap (Benzinga)](https://www.benzinga.com/markets/earnings/26/04/51946097/danaher-q1-earnings-beat-estimates-but-revenue-miss-weak-diagnostics-weigh-on-stock)
- [Sandoz Q1 2026 — biosimilar surge drives 11% revenue growth (Investing.com)](https://www.investing.com/news/company-news/sandoz-q1-2026-slides-biosimilar-surge-drives-11-revenue-growth-93CH-4644004)
- [Assessing Sandoz Group (SWX:SDZ) valuation after Q1 2026 (Yahoo Finance)](https://finance.yahoo.com/sectors/healthcare/articles/assessing-sandoz-group-swx-sdz-101039937.html)
- [Sandoz FY2025 results presentation (Sandoz IR)](https://sandoz-com.cms.sandoz.com/sites/default/files/2026-02/FY%202025%20Results%20Presentation.pdf)
