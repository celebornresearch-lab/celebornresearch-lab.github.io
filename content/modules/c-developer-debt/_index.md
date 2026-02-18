---
title: "Module C: Developer Debt & DC Credit Analysis"
layout: "single"
url: "/modules/c-developer-debt/"
summary: "Credit analysis of the DC developer universe — ~$16.3B in identified debt across 10 public developers"
weight: 1
---

# Module C: AI Infrastructure Developer Debt & Credit Analysis

**Report Date:** February 13, 2026  
**Status:** Draft 1 — XBRL data extracted, filing deep-dives in progress  

---

## Executive Summary

We mapped debt across 18 public AI infrastructure / BTC-mining-to-HPC developers using SEC EDGAR XBRL data and 8-K filings. The sector has **~$19.8B+ in identified long-term debt**, dominated by four large issuances:

- **IREN:** $3.7B convertible notes (as of Dec 2025)
- **MARA:** $3.2B long-term debt (as of Sep 2025)  
- **WULF:** $3.2B Sr Sec Notes (WULF Compute LLC)
- **CIFR:** $2.0B Sr Sec Notes + $1.0B prior facility = $3.0B total
- **APLD:** $2.9B total debt, including $2.35B Sr Sec Notes at 9.25%
- **CLSK:** $1.8B long-term debt (as of Dec 2025)

The sector has undergone a massive leveraging event in 2025-2026 as BTC miners pivot to AI/HPC. Deal structures are moving from unsecured convertibles (2021-2023 era) to **project-finance-style secured debt** backed by specific DC facilities and hyperscaler off-take agreements.

**Key Credit Observations:**
1. Morgan Stanley is the dominant bookrunner (CIFR, WULF) — suggests institutional bid for AI infra secured debt
2. Google backstop on WULF creates a two-tier credit structure (guaranteed vs unguaranteed cash flows)
3. CORZ emerged from Ch11 essentially debt-free — now re-leveraging for HPC pivot
4. Convertible note programs (IREN, MARA) are at massive scale — dilution risk if conversions trigger
5. **The sector is bifurcating:** PF-style secured debt (CIFR 6.125%, WULF 7.750%, APLD 9.25%) vs zero-coupon converts used to buy BTC (MARA 0.00%) — fundamentally different credit profiles
6. **APLD's 9.25% coupon** on $2.35B Sr Sec Notes is the highest in the sector, 148bps over WULF and 313bps over CIFR
7. **IREN and MARA converts are unsecured and structurally subordinated** to any future secured debt — creating a clear path for secured lenders to prime existing holders

---

## Master Debt Summary Table

| Company | Ticker | Total LT Debt | Key Instrument(s) | Rate | Maturity | Collateral | Source |
|---------|--------|--------------|-------------------|------|----------|------------|--------|
| **Iris Energy** | IREN | ~$3.7B | $1.15B Conv Notes (0.25%) | 0.25% | Jun 2032 | Unsecured | 8-K 12/8/25 |
| | | | $1.15B Conv Notes (1.00%) | 1.00% | Jun 2033 | Unsecured | 8-K 12/8/25 |
| **Marathon Digital** | MARA | ~$3.2B | $850M Conv Notes (0.00%) | 0.00% | Jun 2031 | Unsecured | 8-K 12/4/24 |
| | | | $850M Conv Notes (0.00%) | 0.00% | 2032 | Unsecured | 8-K 7/23/25 |
| **TeraWulf** | WULF | ~$3.2B | $3.2B Sr Sec Notes (WULF Compute LLC) | 7.750% | 2030 | DC Portfolio + Google $3.2B backstop | 8-K (verify) |
| **Cipher Mining** | CIFR | ~$3.0B | $2.0B Sr Sec Notes (Black Pearl Compute) | 6.125% | Feb 2031 | Wink TX DC | 8-K 2/11/26 |
| | | | $1.0B prior facility (as of Sep '25) | TBD | TBD | TBD | 10-Q 9/30/25 |
| **Applied Digital** | APLD | ~$2.9B | $2.35B Sr Sec Notes | 9.25% | Dec 2030 | DC assets | 10-Q 11/30/25 |
| | | | $450M Convertible Notes | 2.75% | Jun 2030 | Unsecured | 10-Q 11/30/25 |
| **CleanSpark** | CLSK | ~$1.8B | LT Debt; $2B face instrument @ 7.17% | 7.17% | TBD | TBD | 10-Q 12/31/25 |
| **Nebius Group** | NBIS | ~$1.6B | LT Debt (STALE data) | TBD | TBD | TBD | 20-F 12/31/23 |
| **Riot Platforms** | RIOT | ~$592M | $587M LT noncurrent + $5M current | TBD | TBD | TBD | 10-Q 9/30/25 |
| **Bitdeer Tech** | BTDR | ~$400M | Convertible Senior Notes | TBD | TBD | TBD | 6-K 11/25 |
| **Hut 8** | HUT | ~$301M | $236M noncurrent + $65M current | TBD | TBD | Google guarantee | 10-K 12/31/24 |
| **Hyperscale Data** | GPUS | ~$80M | Long-term debt | TBD | TBD | TBD | 10-Q 9/30/25 |
| **Greenidge Gen** | GREE | ~$46M | Long-term debt | TBD | TBD | TBD | 10-Q 9/30/25 |
| **WhiteFiber** | WYFI | ~$44M | Debt instruments | TBD | TBD | TBD | 10-Q 9/30/25 |
| **Mawson Infra** | MIGI | ~$21M | Long-term debt | TBD | TBD | TBD | 10-Q 12/31/24 |
| **Soluna Holdings** | SLNH | ~$13M | $23M face, $13M net | TBD | TBD | TBD | 10-Q 9/30/25 |
| **Bit Digital** | BTBT | ~$3M | Long-term debt (STALE) | TBD | TBD | TBD | 10-Q 12/31/22 |
| **Core Scientific** | CORZ | ~minimal | Post-Ch11 — $102M operating leases only | N/A | N/A | N/A | 10-Q 9/30/25 |
| **Bitfarms** | BITF | ~$1M | $791K convertible (de minimis) | 12% | TBD | TBD | 10-Q 6/30/25 |

---

## Per-Company Deep Dives

### CIFR — Cipher Mining Inc.
**CIK:** 0001819989 | **Latest Filing:** 10-Q (Sep 30, 2025), 8-K (Feb 11, 2026)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Sr Sec Notes | $2,000,000,000 | 6.125% | Feb 15, 2031 | Black Pearl Compute LLC | Wink TX HPC DC |
| Prior LT Debt | $1,023,075,000 | TBD | TBD | TBD | TBD |
| **Total** | **~$3,023,075,000** | | | | |

**Key Details (from 8-K Feb 11, 2026):**
- Issuer: Black Pearl Compute LLC (indirect wholly-owned sub)
- Guarantors: Cipher Black Pearl LLC, 11786 Wink LLC
- Bookrunner: Morgan Stanley & Co.
- Use of proceeds: (1) Finance remaining Black Pearl Facility cost, (2) Reimburse Cipher ~$232.5M for prior equity contributions, (3) Fund debt service reserves
- Amortization: 7.00% per annum semi-annual, starting after construction completion
- Call protection: Make-whole premium prior to Feb 15, 2028; par call after
- 40% equity clawback provision
- Placement: 144A / Reg S to QIBs

**Lease Obligations:**
- Finance leases: $8.3M (Sep 2025)
- Operating leases: $12.6M (Sep 2025)

**Credit View:** Massive step-up from $167M (Jun 2025) to $1.0B (Sep 2025) to $3.0B (Feb 2026). Rapid leveraging for HPC buildout. The Black Pearl structure is clean project finance — ring-fenced subsidiary, specific facility collateral. The 6.125% coupon vs WULF's 7.750% suggests market views CIFR's facility as lower risk (or better structured). Need to verify: what is the off-take agreement backing Black Pearl? Who is the tenant?

---

### WULF — TeraWulf Inc.
**CIK:** 0001783875 | **Latest XBRL:** 10-Q (Sep 30, 2024) — STALE

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Sr Sec Notes | $3,200,000,000 | 7.750% | 2030 | WULF Compute LLC | DC Portfolio |
| **Total** | **~$3,200,000,000** | | | | |

**Key Details (from prior research / Josh intel):**
- Bookrunner: Morgan Stanley
- Google $3.2B backstop arrangement
- Hut 8 comparison: 15yr full Google guarantee (terms unknown)
- TeraWulf structure: 15yr lease, ~8yr Google guarantee only
- **Critical gap:** Need to pull the actual 8-K/indenture for exact terms

**Credit View:** The 7.750% coupon is rich for secured debt with a Google backstop. The mismatch between 15yr lease and ~8yr guarantee creates a tail risk — what happens in years 9-15? This is the structural question. The 162.5bps premium over CIFR (7.750% vs 6.125%) likely reflects the guarantee gap or construction stage difference.

**⚠️ XBRL data is stale (Sep 2024).** Pre-dates the $3.2B issuance. Need to pull more recent filings manually.

---

### IREN — Iris Energy Ltd.
**CIK:** 0001878848 | **Latest Filing:** 10-Q (Dec 31, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Convertible Notes | $3,685,296,000 | TBD | TBD | Iris Energy | Likely unsecured |
| **Total** | **~$3,685,296,000** | | | | |

**Key Details:**
- Convertible notes jumped from $2.27B (Dec 8, 2025) to $3.69B (Dec 31, 2025) — ~$1.4B added in <1 month
- Multiple 8-Ks in Nov-Dec 2025 suggest sequential issuances
- Finance leases: $155.9M (Dec 2025) — significant equipment financing
- JPMorgan adding 688K shares (+103%) per X/Twitter signal

**Instrument Details (from 8-K Dec 8, 2025, Accession 0001140361-25-044888):**

| Tranche | Principal | Rate | Maturity | Conversion Price | Call Protection |
|---------|-----------|------|----------|-----------------|----------------|
| 0.25% Convertible Sr Notes due 2032 | $1,150,000,000 | 0.25% | Jun 1, 2032 | ~$51.40/sh | After Dec 6, 2028 |
| 1.00% Convertible Sr Notes due 2033 | $1,150,000,000 | 1.00% | Jun 1, 2033 | ~$51.40/sh | After Dec 6, 2029 |

- Both tranches include $150M greenshoe fully exercised
- Net proceeds: ~$2,270M; $201M used for capped call transactions
- Used ~$608M to repurchase ~$228M of existing 2030 converts; ~$1,024M to repurchase ~$317M of existing 2029 converts
- Trustee: U.S. Bank Trust Company, N.A.
- Placement: 144A to QIBs
- **Senior unsecured** — structurally subordinated to subsidiary debt

**Credit View:** $2.3B in new unsecured converts at ~$51.40 conversion price. If IREN stock trades below conversion price at maturity, these become a $2.3B repayment obligation. The sub-1% coupons mean almost no cash drain, but the repayment wall is real. The structural subordination to future secured debt at subsidiaries means a PF lender to an IREN DC project would be senior to these holders.

---

### MARA — Marathon Digital Holdings
**CIK:** 0001507605 | **Latest Filing:** 10-Q (Sep 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| LT Debt | $3,247,561,000 | TBD | TBD | Marathon Digital | TBD |
| **Total** | **~$3,247,561,000** | | | | |

**Key Details:**
- Grew from $326M (Dec 2023) to $2.25B (Jun 2025) to $3.25B (Sep 2025)
- Historical: $747.5M face convertible notes (Nov 2021, 1% coupon)
- Operating leases: $40.9M; Finance leases: $4.0M
- Need to identify current instruments — the $3.25B is likely multiple tranches

**Instrument Details:**

| Tranche | Principal | Rate | Maturity | Conv. Price | Bookrunners | Source |
|---------|-----------|------|----------|------------|-------------|--------|
| 0.00% Conv Sr Notes due 2031 | $850,000,000 | 0.00% | Jun 1, 2031 | ~$34.58/sh | JPM, Barclays | 8-K Dec 4, 2024 |
| 0.00% Conv Sr Notes due 2032 | $850,000,000 | 0.00% | 2032 | TBD | TBD | 8-K Jul 23, 2025 |
| 1.00% Conv Sr Notes due 2026 | Residual (being retired) | 1.00% | 2026 | TBD | — | Legacy |

- Both 2031 and 2032 tranches: zero coupon, senior unsecured, 144A placement
- 2031 Notes: +$150M greenshoe option; ~$48M used to retire 2026 converts; remainder to buy BTC
- 2032 Notes: +$150M greenshoe option; up to $50M to retire remaining 2026 converts; capped call + buy BTC
- **BTC Holdings:** ~49,951 BTC as of Jun 30, 2025 (~$3.4B at $67.5K)
- Trustee: U.S. Bank Trust Company, N.A.

**Credit View:** MARA is issuing zero-coupon converts to buy bitcoin. No cash interest cost, no secured debt, no collateral. The entire credit thesis is BTC price. If BTC drops below conversion prices, these become ~$1.7B+ in unsecured obligations with no coupon, no collateral, and a BTC treasury declining in value. Pure equity cushion play. The MicroStrategy model applied to mining. The structural unsecured status creates clear room for secured lenders at the project level.

---

### CLSK — CleanSpark Inc.
**CIK:** 0000827876 | **Latest Filing:** 10-Q (Dec 31, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| LT Debt | $1,786,759,000 | 7.17% | TBD | CleanSpark | TBD |
| Face amount | $2,000,000,000 | 7.17% | TBD | CleanSpark | TBD |
| **Total** | **~$1,787,000,000** | | | | |

**Key Details:**
- $2B face amount instrument at 7.17% — this is a significant secured or convertible issuance
- Rapid growth from $645M (Sep 2025) to $1.79B (Dec 2025) — nearly 3x in one quarter
- De minimis lease obligations

**Credit View:** Another 2025 leveraging story. The 7.17% rate is in-line with sector (between CIFR's 6.125% and WULF's 7.750%). Need to find the 8-K announcing this issuance and identify the structure.

---

### RIOT — Riot Platforms Inc.
**CIK:** 0001167419 | **Latest Filing:** 10-Q (Sep 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| LT Debt (noncurrent) | $586,501,000 | TBD | TBD | Riot Platforms | TBD |
| LT Debt (current) | $5,323,000 | TBD | TBD | Riot Platforms | TBD |
| **Total** | **~$591,824,000** | | | | |

**Key Details:**
- Operating leases: $32.1M
- Historical $6M line of credit facility
- Relatively conservative leverage vs peers
- Recent 8-Ks (Jan 2026) — need to check for new issuances

**Credit View:** RIOT is notably less leveraged than peers. $592M vs MARA's $3.2B or IREN's $3.7B. Could indicate either discipline or inability to access markets at scale. The failed Bitfarms hostile takeover attempt may have distracted from capital markets activity.

---

### HUT — Hut 8 Corp.
**CIK:** 0001964789 | **Latest Filing:** 10-K (Dec 31, 2024)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| LT Debt (noncurrent) | $235,620,000 | TBD | TBD | Hut 8 Corp | TBD |
| LT Debt (current) | $64,965,000 | TBD | TBD | Hut 8 Corp | TBD |
| **Total** | **~$300,585,000** | | | | |

**Key Details:**
- Per Josh intel: 15yr lease with full Google guarantee (terms unknown)
- Historical face amounts: $142-151M (2023)
- Finance leases: $23.4M; Operating leases: $19.7M (Sep 2025)

**Credit View:** The Google guarantee makes HUT's credit profile fundamentally different from peers. Need to find the actual off-take/guarantee documentation. If it's a full 15yr guarantee vs WULF's 8yr partial, that's a meaningful credit differential.

---

### CORZ — Core Scientific Inc.
**CIK:** 0001839341 | **Latest Filing:** 10-Q (Sep 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Operating leases | $102,222,000 | N/A | Various | Core Scientific | N/A |
| Finance leases | $547,000 | N/A | Various | Core Scientific | N/A |
| **Total Debt** | **~$0** (post-Ch11) | | | | |

**Key Details:**
- Emerged from Chapter 11: January 2024
- ~$1.6B debt converted to equity in restructuring
- Now pivoting to HPC with CoreWeave contracts
- **Pending acquisition by CoreWeave** (per 10-Q risk factors mentioning "proposed transaction")
- Fresh start accounting — clean balance sheet

**Credit View:** CORZ is the most interesting credit story in the group. Debt-free post-Ch11, pivoting to HPC with major contracts, and now subject to a CoreWeave acquisition. If the CRWV acquisition closes, CORZ debt analysis becomes CRWV debt analysis. If it doesn't close, CORZ will likely need project finance for its HPC buildout — potential origination target.

---

### APLD — Applied Digital Corp.
**CIK:** 0001144879 | **Latest Filing:** 10-Q (Nov 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| **Sr Secured Notes** | $2,350,000,000 | 9.25% | Dec 2030 | Applied Digital | DC assets |
| Convertible Notes | $450,000,000 | 2.75% | Jun 2030 | Applied Digital | Unsecured |
| Starion Ellendale Loan | $10,234,000 | 7.48% | Feb 2028 | Applied Digital | Ellendale DC facility |
| Cornerstone Bank Loan | $11,429,000 | 8.59% | Mar 2029 | Applied Digital | Jamestown hosting ToS |
| Starion Term Loan | $5,506,000 | 6.50% | Jul 2027 | Applied Digital | Jamestown facility |
| Other LT debt (incl SAFEs) | $31,891,000 | Various | Various | Applied Digital | Various |
| Deferred financing costs | ($252,494,000) | — | — | — | — |
| **Total (gross)** | **$2,859,061,000** | | | | |
| **Total (net)** | **$2,594,011,000** | | | | |

**Key Details:**
- Used $2.35B Sr Sec Notes proceeds to repay $375M SMBC loan facility
- $65M Revolving Credit Facility (First National Bank of Omaha, SOFR+2.75%, undrawn)
- DC Portfolio: Polaris Forge 1 (Ellendale ND, 400MW, leased to hyperscaler), Polaris Forge 2 (Harwood ND, 200MW), Delta Forge 1 (Southern US, 430MW)
- NVIDIA sold entire 7.7M share position per 13F
- ChronoScale spinout: GPU/cloud business separating from DC hosting/development

**Credit View:** **MAJOR CORRECTION** — APLD is now the third-largest debtor in the universe at $2.86B (previous data showing $44M was stale). The 9.25% coupon on $2.35B Sr Sec Notes is **the highest in the sector** — 148bps over WULF (7.75%), 313bps over CIFR (6.125%). This reflects either higher construction/execution risk or weaker off-take agreements compared to peers. The SMBC repayment + Sr Sec Notes = classic PF refinancing. NVIDIA exiting equity while the company leverages up 65x is a significant divergent signal. The $450M convertible at 2.75% creates a two-tier capital structure.

---

### BTDR — Bitdeer Technologies Group
**CIK:** 0001899123 | **Latest Filing:** 6-K (foreign filer)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Convertible Sr Notes | $400,000,000 | TBD | TBD | Bitdeer | TBD |
| **Total** | **~$400,000,000** | | | | |

**Key Details:**
- Singapore-based company, files 6-K/20-F as foreign filer
- ASIC chip manufacturer + mining + DC operations
- $400M convertible notes announced November 2025
- No XBRL debt data available due to foreign filing status

**Credit View:** Mid-tier issuance in the sector. Need to track down the actual offering docs for terms. Bitdeer's chip manufacturing adds hardware exposure beyond pure DC/hosting plays.

---

### NBIS — Nebius Group N.V. (formerly Yandex)
**CIK:** 0001513845 | **Latest Filing:** 20-F (Dec 31, 2023) — STALE

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Long-term debt | $1,577,500,000 | TBD | TBD | Nebius | TBD |
| Convertible debt | $1,155,400,000 | TBD | TBD | Nebius | TBD |
| Finance leases | $353,400,000 | N/A | Various | Nebius | N/A |
| **Total** | **~$1,577,500,000** | | | | |

**Key Details:**
- **Data is STALE** — last 20-F filing is Dec 2023
- Formerly Yandex, spun out non-Russian operations
- Files as foreign entity (Netherlands)
- Significant AI/cloud infrastructure operations

**Credit View:** Major debt load but data freshness is concerning. Need updated 20-F or 6-K filings to verify current debt levels. The $1.6B makes this the 6th largest in the universe if still accurate.

---

### GPUS — Hyperscale Data Inc. (formerly BitNile/Ault)
**CIK:** 0000896493 | **Latest Filing:** 10-Q (Sep 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Long-term debt | $80,000,000 | TBD | TBD | Hyperscale Data | TBD |
| Convertible notes | $9,500,000 | TBD | TBD | Hyperscale Data | TBD |
| **Total** | **~$80,000,000** | | | | |

**Credit View:** Diversified holding company with DC operations. Moderate debt load for the sector. Multiple name changes suggest operational pivoting.

---

### GREE — Greenidge Generation Holdings
**CIK:** 0001844971 | **Latest Filing:** 10-Q (Sep 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Long-term debt | $45,800,000 | TBD | TBD | Greenidge | TBD |
| **Total** | **~$45,800,000** | | | | |

**Key Details:**
- Historical face amount: $176.2M (Sep 2022) — significant deleveraging
- Power plant + mining operations
- Dresden NY facility

**Credit View:** GREE has actively deleveraged from $176M to $46M over 3 years. Either refinanced to off-balance sheet, paid down, or restructured. The power plant asset base provides unique collateral vs pure DC plays.

---

### MIGI — Mawson Infrastructure Group
**CIK:** 0001218683 | **Latest Filing:** 10-Q (Dec 31, 2024)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Long-term debt | $20,900,000 | TBD | TBD | Mawson | TBD |
| **Total** | **~$20,900,000** | | | | |

**Credit View:** Small player in the universe. Need to identify specific facilities and off-take agreements.

---

### SLNH — Soluna Holdings Inc.
**CIK:** 0000064463 | **Latest Filing:** 10-Q (Sep 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Long-term debt | $13,300,000 | TBD | TBD | Soluna | TBD |
| Face amount debt | $23,300,000 | TBD | TBD | Soluna | TBD |
| Convertible notes | $8,500,000 | TBD | TBD | Soluna | TBD |
| **Total** | **~$13,300,000** | | | | |

**Credit View:** Small player with behind-the-meter DC model. The face vs. carrying value spread ($23M vs $13M) suggests discount or fair value adjustments.

---

### WYFI — WhiteFiber Inc.
**CIK:** 0002042022 | **Latest Filing:** 10-Q (Sep 30, 2025)

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Debt instruments | $43,900,000 | TBD | TBD | WhiteFiber | TBD |
| Operating leases | $41,400,000 | N/A | Various | WhiteFiber | N/A |
| **Total** | **~$43,900,000** | | | | |

**Credit View:** Small DC/fiber infrastructure company. High lease obligations relative to debt suggests asset-light model.

---

### BTBT — Bit Digital Inc.
**CIK:** 0001710350 | **Latest Filing:** 10-Q (Dec 31, 2022) — STALE

**Debt Schedule:**
| Instrument | Principal | Rate | Maturity | Issuer | Collateral |
|-----------|-----------|------|----------|--------|------------|
| Long-term debt | $3,000,000 | TBD | TBD | Bit Digital | TBD |
| Operating leases | $41,900,000 | N/A | Various | Bit Digital | N/A |
| **Total** | **~$3,000,000** | | | | |

**Credit View:** Essentially unleveraged. **Data is STALE** (Dec 2022) — need current filings. High lease obligations suggest operating vs. owning strategy.

---

## Sector-Level Observations

### Total Identified Debt: ~$19.8B across 18 companies

| Tier | Companies | Combined Debt | Notes |
|------|-----------|--------------|-------|
| **Mega** (>$3B) | IREN, MARA, WULF, CIFR | ~$13.1B | The "Big Four" of AI infra debt |
| **Large** ($1B-$3B) | APLD, CLSK, NBIS | ~$6.1B | APLD corrected to $2.9B; NBIS data stale |
| **Mid** ($100M-$1B) | RIOT, BTDR, HUT | ~$1.3B | BTDR $400M converts, others mixed |
| **Small** (<$100M) | GPUS, GREE, WYFI, MIGI, SLNH, BTBT, CORZ, BITF | ~$253M | Mix of small players and post-Ch11 |

### Key Structural Themes
1. **Project Finance Migration:** CIFR (Black Pearl), WULF (WULF Compute), and APLD have moved to ring-fenced subsidiary structures — classic PF. This is the model that will dominate going forward.
2. **Coupon Dispersion Signals Risk Assessment:** APLD's 9.25% Sr Sec Notes (highest in sector) vs CIFR's 6.125% suggests market is pricing construction/execution risk or weaker off-take agreements. 313bps spread is material.
3. **Convertible Overhang:** IREN's $3.7B + MARA's $1.7B in zero/low-coupon convertibles create $5.4B in potential repayment obligations if conversions fail. Sector's biggest concentration risk.
4. **Hyperscaler Backstops:** Google (via WULF, HUT) and potentially others are providing credit support. This creates a bifurcation: backstopped debt trades tight, unbackstopped trades wide.
5. **Morgan Stanley Dominance:** MS bookran both CIFR and WULF — they are the de facto AI infra debt banker.

---

## Data Gaps & Next Steps

### Critical Gaps to Fill
1. **WULF 8-K/Indenture:** Need exact filing for the $3.2B 7.750% notes — verify terms, covenants, Google backstop structure
2. **IREN Convertible Terms:** Conversion price, maturity, put/call — $3.7B is too large to leave unspecified
3. **MARA Debt Breakdown:** What comprises the $3.2B? Multiple tranches? Convertibles vs secured?
4. **CLSK $2B Instrument:** Find the 8-K announcing this issuance, verify terms
5. **CORZ/CRWV Acquisition:** Terms, timeline, what happens to CORZ's DC assets if CRWV deal closes
6. **NVIDIA $3.8B Junk Bond DC:** Identify the issuer, structure (per X/Twitter Feb 12, 2026)
7. **Off-take agreements:** For each PF structure, who is the tenant? What are the lease terms?

### Companies Not in SEC Filings
**Foreign/Canadian/De-listed companies not captured in this analysis:**
- **HIVE Digital** (TSX: HIVE) — Canadian-listed, check SEDAR filings
- **ANY** — Sphere 3D Corp (may be de-listed or renamed)
- **SDIG** — Stronghold Digital Mining (may have been acquired)
- **SATO** — Sato Technologies (likely Canadian/private)
- **ARBK** — Argo Blockchain PLC (London LSE-listed)
- **BTOG** — Bit Origin (not found in EDGAR)
- **LGHL** — Lion Group Holding (status uncertain)

**Additional Targets to Research:**
- **Galaxy Digital / GLXY** — Canadian-listed, check SEDAR
- **Solaris Energy Infrastructure** — DC power equipment rental
- **Fermi Inc. (FRMI)** — CIK 0002071778, 8-K filed Feb 10, 2026 (Josh portfolio company)

### Filing Deep-Dives Needed
For each company where we have XBRL totals but not instrument-level detail, need to:
1. Pull the actual 10-Q/10-K HTML
2. Extract Note on Debt/Borrowings
3. Map each instrument with full terms

---

*Sources: SEC EDGAR XBRL API (data.sec.gov/api/xbrl/companyfacts/), EDGAR full-text search (efts.sec.gov), individual 8-K filings. All data as of most recent filing dates noted per company.*
