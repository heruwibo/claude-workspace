---
title: "NRF Inflation Watch"
subtitle: "How to monitor and evaluate the inflation impact of the Natural Resource Fund, and the design of a monitoring platform"
date: "October 2026"
status: "Draft for steering committee discussion"
---

# NRF Inflation Watch

**How to monitor and evaluate the inflation impact of the Natural Resource Fund (NRF), and the design of a platform to do it**

October 2026 · Draft for steering committee discussion · Companion to *Kajian Danantara, NRF dan Tokenisasi (Oktober 2026)*

> This is a design note, not a macroeconomic forecast. The numbers in Section 2.3 are illustrative and use assumed parameters. They must be replaced by estimates from the models in Section 4 before anyone quotes them.

---

## 1. Why the NRF needs an inflation watch

The NRF Executive Summary (25 Sept 2025) sets direct fiscal benefit targets of **Rp100 T in year 1 and Rp1,000 T within three years**. It projects a 2026 SDA benefit of Rp336 T (10.68% of state revenue) and coal capitalisation of at least Rp10,000 T. It is funded by securitising state-owned reserves (Sovereign ABS, mineral-based Sovereign Notes, Royalty-Backed Financing, Mineral Reserve Trust). Benefits are distributed through APBN debt reprofiling, tax revenue and Koperasi Merah Putih.

The document does not discuss inflation. That gap matters for three reasons:

1. **Scale.** Rp1,000 T is about 4% of nominal GDP (roughly Rp24,000 T). An injection that size, spent domestically and quickly, would visibly change demand.
2. **Price-setting levers.** Coal is both the NRF's main asset and the main fuel for PLN electricity. Any change to coal pricing for fiscal capture feeds into administered prices.
3. **Credibility.** Bank Indonesia's target is **2.5% ± 1% (2025–2027)**. Markets will judge whether reserve-backed financing is quietly monetised. A perception of "printing money against coal" can raise inflation expectations and the rupiah risk premium even before any rupiah is spent.

The inflation watch has two jobs:

- **Monitor:** detect early, at national and regional level, whether NRF activity is adding price pressure.
- **Evaluate:** after the fact, estimate how much of observed inflation is attributable to the NRF. The NRF's net benefit should then be reported net of that cost.

---

## 2. How the NRF can affect inflation: transmission channels

### 2.1 Channel map

| # | Channel | Mechanism | Direction | Speed | What to watch |
|---|---|---|---|---|---|
| C1 | **Fiscal demand** | Proceeds spent on projects, transfers or koperasi distribution raise aggregate demand | ↑ inflation | 2–6 quarters | Disbursement pace vs output gap; core inflation; retail sales |
| C2 | **Monetary financing** | If BI or the banking system absorbs NRF securities, base money or credit expands | ↑ (strong if BI buys) | 1–4 quarters | Buyer composition of each series; M0/M2; bank liquidity; BI primary purchases |
| C3 | **Exchange rate** | Foreign buyers of NRF paper → rupiah appreciation (disinflationary). A loss of credibility → depreciation and imported inflation | ↕ | 0–3 months to rate, 1–3 quarters to CPI | USD/IDR (JISDOR), CDS, SBN yields, foreign holdings |
| C4 | **Energy and administered prices** | Coal re-pricing (DMO price for PLN, HBA-linked royalties) raises PLN cost → tariff or compensation pressure | ↑ (administered) | Tied to tariff decisions (quarterly) | DMO coal price, PLN BPP, tariff adjustment, compensation budget |
| C5 | **Supply disruption** | Nationalising illegal mines and reviewing IUP/HGU can disrupt coal, nickel or plantation output (e.g. palm oil → cooking oil) | ↑ (volatile food, energy) | 1–6 months | Production volumes; cooking oil and rice prices in affected provinces |
| C6 | **Regional overheating** | Hilirisasi and anchor projects concentrate spending in mining regions (Kalimantan, Sulawesi, Maluku), so local wages, rent and food prices rise | ↑ regional | 2–8 quarters | Regional CPI vs national; local wages; housing rent |
| C7 | **Expectations** | Market reading of the NRF as fiscal dominance or a "resource currency" | ↑ | Immediate | BI price expectation indices; survey forecasts; yield curve |
| C8 | **Supply-side capacity (positive)** | Debt reprofiling lowers interest cost; productive investment (logistics, food chain, koperasi distribution) expands supply over time | ↓ | 2–5 years | Logistics costs; price dispersion between regions; productivity |

### 2.2 Which channels matter most

In order of risk for the NRF design as written:

1. **C2 monetary financing.** This is the most dangerous channel and the easiest to prevent. It is a design choice, not a market outcome.
2. **C4 energy/administered prices.** Coal is the quick win and also the electricity input. A coal-price decision is an inflation decision.
3. **C1 fiscal demand.** It depends on how fast proceeds are spent and how much is saved or invested abroad.
4. **C7 expectations.** Small in normal times, large if communication fails.

C8 is the reason to do the NRF at all. Over the long run, well-allocated investment lowers costs. The platform should measure it as well, so the evaluation is not one-sided.

### 2.3 Illustrative sizing of the fiscal demand channel (C1)

Assumptions (to be replaced by estimates): fiscal multiplier 0.3–0.8; inflation response 0.1–0.3 pp per 1% of GDP of extra demand; nominal GDP about Rp24,000 T.

| Scenario | Injection | % of GDP | Demand effect (% GDP) | Inflation effect (pp) |
|---|---|---|---|---|
| Year 1 target | Rp100 T | ~0.4% | 0.1–0.3% | ~0.01–0.1 |
| Rp1,000 T spread over 3 years | ~Rp333 T/yr | ~1.4%/yr | 0.4–1.1% | ~0.04–0.3 per year |
| Rp1,000 T spent in year 3 | Rp1,000 T | ~4% | 1.2–3.2% | ~0.1–1.0 |

**Reading:** the year-1 target is small for national inflation. A year-3 flow of Rp1,000 T could use up to the whole ±1 pp tolerance band, before counting C2, C4 or C7. Pacing and the savings share are therefore the main inflation levers inside the NRF's own control.

---

## 3. What to measure: indicator framework

Indicators are arranged in five layers, from outcome back to cause. Every indicator has an owner, source, frequency, threshold and an evidence class (A = official statistic, B = official administrative data, C = source-document claim, D = model estimate).

### Layer 1: Inflation outcomes (BPS)

| Indicator | Frequency | Source | Note |
|---|---|---|---|
| Headline CPI, yoy and mtm | Monthly (first working day) | BPS | Base 2022=100, 150 regencies/cities |
| Core inflation | Monthly | BPS | Best signal of demand pressure (C1) |
| Administered prices | Monthly | BPS | Electricity, fuel, transport (C4) |
| Volatile food | Monthly | BPS | Supply shocks (C5); TPIP guidance about 3–5% |
| Regional CPI (provincial and city) | Monthly | BPS | Needed for C6 and for regional evaluation |
| Core 3-month annualised momentum | Monthly, derived | Platform | Catches turns earlier than yoy |

### Layer 2: High-frequency prices (nowcasting)

| Indicator | Frequency | Source |
|---|---|---|
| Strategic food prices by province and market | Daily | PIHPS Nasional (BI) |
| Food price panel | Daily | Panel Harga Pangan (Bapanas) |
| Staple price monitoring | Daily/weekly | SP2KP (Kemendag) |
| Fuel prices (subsidised and non-subsidised) | On change | Pertamina / ESDM |
| Electricity tariff adjustment | Quarterly | ESDM / PLN |

### Layer 3: Upstream costs and external

| Indicator | Frequency | Source |
|---|---|---|
| Producer and wholesale price indices | Monthly / quarterly | BPS |
| USD/IDR (JISDOR), import price proxies | Daily | BI |
| Coal reference price (HBA), DMO price for PLN | Periodic | ESDM |
| Global commodity prices (energy, food, fertiliser) | Monthly | World Bank Pink Sheet, FAO Food Price Index |

### Layer 4: Monetary, financial and expectations

| Indicator | Frequency | Source |
|---|---|---|
| BI-Rate, M0, M2, credit growth | Monthly | BI (SEKI) |
| SBN yield curve, foreign holdings of SBN | Daily | Kemenkeu DJPPR, market data |
| Sovereign CDS (5y) | Daily | Market data |
| Price expectations of consumers and retailers | Monthly | BI Consumer Survey, Retail Sales Survey |
| Consensus inflation forecasts | Monthly | Market surveys |

### Layer 5: NRF activity (internal; the layer that does not exist anywhere else)

| Indicator | Frequency | Source | Channel |
|---|---|---|---|
| Securities issued by series and instrument type | Per issuance | NRF register (TEPSDA ledger) | C2, C3 |
| **Buyer composition** (BI, banks, non-bank domestic, foreign, retail) | Per issuance | Registrar / KSEI | C2, C3 |
| Proceeds by use: savings, stabilisation, domestic investment, supplier development, distribution | Monthly | NRF ledger | C1 |
| Disbursement by province and sector | Monthly | NRF / Danantara project register | C1, C6 |
| Koperasi Merah Putih distribution (cash vs in-kind vs productive) | Monthly | Koperasi programme data | C1 |
| Coal pricing decisions affecting PLN; PLN compensation | On decision | ESDM, Kemenkeu | C4 |
| Production in IUP/HGU under review or nationalisation | Monthly | ESDM MODI/MOMS, Kementan | C5 |
| Debt reprofiled and interest saved | Quarterly | Kemenkeu | C8 |

**Derived NRF indicators**

- **NRF fiscal impulse** = change in NRF-financed domestic spending, as % of GDP, per quarter.
- **Monetisation share** = share of NRF securities held by BI plus the change in bank holdings funded by BI liquidity.
- **Domestic absorption ratio** = proceeds spent domestically ÷ total proceeds. A lower ratio means less inflation pressure.
- **Regional intensity** = NRF disbursement per capita by province, used for regional evaluation.

---

## 4. How to evaluate: methods

Evaluation answers two questions. **Is there pressure now?** (monitoring) and **How much did the NRF cause?** (attribution).

### 4.1 Monitoring: nowcast and early warning

| Tool | What it does | Method |
|---|---|---|
| Monthly CPI nowcast | Predicts this month's CPI before BPS releases it | Bridge equations or a dynamic factor model on daily PIHPS/Bapanas prices, fuel and tariff changes |
| Inflation decomposition | Splits headline into core, administered and volatile food, then into demand, supply and imported drivers | Component accounting plus sign-restricted model |
| Early-warning dashboard | Traffic-light status per indicator | Thresholds below |
| Regional heat map | Provinces where inflation exceeds national by a margin, overlaid with NRF disbursement | Regional CPI, NRF register |

**Suggested thresholds (to be calibrated with BI and TPIP)**

| Signal | Green | Amber | Red |
|---|---|---|---|
| Headline CPI yoy | 1.5–3.5% | 3.5–4.0% or < 1.5% | > 4.0% |
| Core 3m annualised | < 3.0% | 3.0–4.0% | > 4.0% |
| Volatile food yoy | < 5% | 5–8% | > 8% |
| Provincial CPI minus national, in NRF-intensive provinces | < 1 pp | 1–2 pp | > 2 pp |
| Monetisation share of NRF securities | 0% | > 0% under crisis framework | Any BI primary purchase outside the legal crisis framework |
| 1-year inflation expectations | Inside target band | Edge of band | Above band for 2 months |
| USD/IDR 1-month change | < 3% | 3–5% | > 5% |

A red signal should trigger a defined response (Section 5), not only a chart.

### 4.2 Attribution: how much is the NRF's fault

Use more than one method and report the range.

| Method | Question it answers | Data need |
|---|---|---|
| **Structural VAR / local projections with an NRF fiscal shock** | National inflation response to an NRF spending or issuance shock | Quarterly macro series, NRF impulse |
| **Regional difference-in-differences** | Did provinces with high NRF intensity see higher inflation than similar provinces with low intensity? | Regional CPI, disbursement per capita, controls |
| **Synthetic control** | Counterfactual CPI for a single heavily affected region (e.g. a hilirisasi hub) | Regional panel |
| **Pass-through models** | Effect of coal/DMO decisions on electricity and on CPI; exchange-rate pass-through | Tariff history, input-output tables |
| **Ex-ante vs ex-post review** | Was the projected inflation impact at approval right? | Project approval files, outcomes |

**Evaluation output for each NRF review (quarterly or semi-annual):**

1. Estimated NRF contribution to headline and core inflation (pp, with range).
2. Contribution by channel C1–C8.
3. Regional hot spots.
4. **Real net benefit** = nominal NRF benefit minus the welfare cost of the extra inflation. The cost should be reported for the bottom 40% of households separately, because food and energy inflation hit them hardest.
5. Recommendation: keep, slow or redirect disbursement.

### 4.3 Real-time data discipline

Evaluate with the data that was available at the time of decision ("vintages"), not only revised data. Otherwise the review will judge decisions unfairly. The platform must store every release with its publication date.

---

## 5. Inflation guardrails to build into the NRF itself

Monitoring is only useful if it is tied to levers. Proposed rules for the NRF charter:

1. **No monetary financing.** BI does not buy NRF or TEPSDA paper in the primary market, except under the existing legal crisis framework and its sunset rules. Buyer composition is disclosed per series.
2. **Savings and absorption rule.** A legislated minimum share of proceeds goes to the savings tranche invested offshore (Norway, Chile, Timor-Leste model). Domestic spending is capped by an absorption rule linked to the output gap.
3. **Counter-cyclical pacing.** When the dashboard shows red on core inflation or expectations for two consecutive months, new domestic disbursement for non-critical items is slowed. Approved project milestones continue.
4. **Coal price-setting is an inflation decision.** Any change to DMO pricing or coal fiscal terms that affects PLN needs an inflation impact note and BI/Kemenkeu consultation before approval.
5. **Distribution design.** Koperasi Merah Putih benefits should lean toward productive and supply-side uses (storage, distribution, cold chain, inputs for farmers). These lower food prices, whereas pure cash transfers add to demand.
6. **Regional absorption plans.** Large projects in mining regions must include a local supply plan (food, housing, labour) agreed with the provincial TPID.
7. **Communication.** NRF instruments are always described as rupiah-denominated state securities, not a currency (consistent with Ch. 6 of the main study).

---

## 6. The platform: NRF Inflation Watch

### 6.1 Users and decisions

| User | Decision supported | View |
|---|---|---|
| NRF / Danantara steering committee | Pace and allocation of disbursement; approve coal pricing changes | Monthly brief, channel monitor, scenario lab |
| Kemenkeu (fiscal) | Budget coordination, compensation | Fiscal impulse, administered prices |
| BI (as data partner and observer) | Monetary stance; not directed by the platform | Monetisation share, expectations |
| TPIP / TPID (central and regional inflation control teams) | Local food supply actions | Regional heat map, food prices |
| Public (subset) | Transparency | Quarterly NRF inflation report |

The platform should **complement** the existing TPIP/TPID and BI systems, not compete with them. Its unique value is Layer 5: linking NRF flows to prices.

### 6.2 Architecture

```
 SOURCES                      PIPELINE                   ANALYTICS                 OUTPUTS
 ───────                      ────────                   ─────────                 ───────
 BPS WebAPI (CPI, PPI) ─┐
 BI SEKI, PIHPS, JISDOR ─┤    Ingestion connectors       Nowcast models            Dashboards
 Bapanas, Kemendag ──────┤ →  + validation + vintage  →  Decomposition        →    (national, regional,
 ESDM (HBA, DMO, prod.) ─┤    store (time-series DB)     Attribution (VAR,          NRF channels)
 Kemenkeu (SBN, APBN) ───┤    + data catalog             DiD, synth. control)      Alerts (email/WA)
 Market data (CDS, FX) ──┤    + lineage                  Threshold engine          Monthly brief
 World Bank, FAO ────────┤                               Scenario simulator        Quarterly report
 NRF ledger / register ──┘    (restricted zone)                                    API for partners
```

**Components**

| Component | Suggested technology | Notes |
|---|---|---|
| Ingestion | Python connectors, scheduled (Airflow or Dagster) | One connector per source; schema checks; keep every vintage |
| Storage | PostgreSQL + TimescaleDB; object storage for raw files | Separate restricted schema for NRF internal data |
| Data catalog | Indicator registry (name, source, frequency, owner, evidence class, threshold) | The registry drives the dashboard, so adding an indicator is a config change |
| Models | Python (statsmodels, PyMC), scheduled re-estimation | Version-controlled; each output stores model version |
| Dashboard | Web app (e.g. Next.js or Streamlit for MVP) with map component | Indonesian and English |
| Alerting | Rule engine on the threshold table | Escalation matrix in Section 5 |
| Security | Role-based access; NRF ledger and pre-release data restricted | Hosting in a national sovereign cloud, consistent with BSSN rules |

### 6.3 Screens

1. **Overview:** headline, core, administered and volatile food; traffic lights; nowcast for the current month; BI target band.
2. **NRF channel monitor:** one tile per channel C1–C8 with its leading indicator and status; issuance and buyer composition; fiscal impulse.
3. **Regional map:** provincial inflation gap vs national, overlaid with NRF disbursement intensity; drill-down to city and commodity.
4. **Food and energy:** daily strategic food prices; fuel and electricity; coal HBA and DMO.
5. **Scenario lab:** "If the NRF disburses Rp X T in quarter Q through channel K, in region R, with Y% savings", showing projected inflation range. Also "if the DMO coal price rises to Z": electricity cost → CPI.
6. **Evaluation:** latest attribution results, real net benefit, ex-ante vs ex-post comparison.

### 6.4 Role of AI agents

Consistent with the multi-agent approach in the Danantara study, agents can reduce analyst workload. They should not make decisions.

| Agent | Task | Human control |
|---|---|---|
| Data steward | Monitors connectors, flags missing or anomalous data, checks against previous vintages | Analyst confirms corrections |
| Price-signal analyst | Explains movements ("chili prices +18% in 3 provinces, likely weather; not NRF-related") with cited data | Analyst reviews |
| Brief writer | Drafts the monthly NRF inflation brief from dashboard data | Economist edits and signs |
| Scenario assistant | Runs the scenario simulator from natural-language questions and shows assumptions | Results labelled as model estimates |

Rules: every AI statement cites the indicator and vintage it used, and no AI output is published without a named human reviewer.

### 6.5 Delivery roadmap

| Phase | Duration | Scope | Done when |
|---|---|---|---|
| 0. MVP on public data | 6–8 weeks | Layers 1–4 from public sources; overview, regional map and food screens; threshold alerts | Dashboard updates automatically after each BPS release and daily for food prices |
| 1. NRF data integration | +2–3 months | Layer 5 from NRF ledger and project register; channel monitor; restricted access | Buyer composition and disbursement by province visible |
| 2. Models | +3 months | Nowcast, decomposition, scenario lab; first attribution study | Nowcast error tracked; first quarterly evaluation report |
| 3. Institutionalise | +3 months | Data-sharing MoUs (BI, BPS, Bapanas, ESDM, Kemenkeu, TPIP); guardrails linked to alerts; public quarterly report | Steering committee uses the brief in every disbursement decision |

**Team for phase 0–2:** 1 product lead, 2 data engineers, 2 economists or econometricians, 1 front-end developer, 1 data steward, plus a BI/BPS liaison.

---

## 7. Recommendations to the steering committee

1. **Add an inflation impact section to the NRF design.** The Executive Summary should state the savings share, disbursement pacing rule and the no-monetisation rule.
2. **Make buyer composition and disbursement-by-region mandatory disclosures** from the first issuance. Without them, the inflation impact cannot be evaluated.
3. **Treat coal pricing decisions as inflation decisions** and require an impact note before approval.
4. **Build the platform MVP now on public data,** so a pre-NRF baseline exists before the first rupiah is disbursed. Attribution needs a baseline.
5. **Report the NRF's benefit in real terms,** net of its inflation cost and with a distributional view.
6. **Coordinate rather than duplicate.** Sign data-sharing arrangements with BI, BPS and TPIP, and position the platform as the NRF-specific layer on top of existing inflation control.

---

## Annex A. Indicator registry template

| Field | Example |
|---|---|
| ID | L5-02 |
| Name | Buyer composition of NRF securities |
| Layer / channel | 5 / C2, C3 |
| Definition | Share of each series held by BI, banks, non-bank domestic, foreign, retail at settlement and month-end |
| Source / owner | NRF registrar; KSEI |
| Frequency / lag | Per issuance; T+1 |
| Evidence class | B |
| Thresholds | Green 0% BI; Red any BI primary purchase outside crisis framework |
| Response | Escalate to steering committee and Kemenkeu within 24 hours |

## Annex B. Glossary

| Term | Meaning |
|---|---|
| BPS | Statistics Indonesia |
| PIHPS | BI's national strategic food price information centre |
| Bapanas | National Food Agency |
| SP2KP | Kemendag staple price monitoring system |
| TPIP / TPID | Central / regional inflation control teams |
| DMO | Domestic market obligation (coal for domestic use, with a price cap for electricity) |
| HBA | Coal reference price set by ESDM |
| TEPSDA | Tokenised securities backed by natural resource revenue (proposed in the main study) |
| Fiscal impulse | Change in fiscal stance that adds to demand, as % of GDP |
