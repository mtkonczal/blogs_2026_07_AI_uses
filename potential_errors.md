# Items Worthy of Attention — Pass 2 (Numerical Claims)

This file collects every numerical or factual issue surfaced during Pass 2 fact-checking that needs your judgment or action. The companion `factcheck_log.md` records all claims checked (verified or otherwise); this file is the subset that requires you to do something.

**Status legend:**
- **⚠ scope mismatch** — number is correct but the cited source doesn't squarely support the specific claim
- **~ off** — number is in the right direction but doesn't match the cited source
- **✗ refuted** — claim does not match the cited source
- **? inconclusive** — source not accessible (paywall, 403, missing URL); needs your manual check
- **🔧 refinement** — claim is technically defensible but a small wording change would make it more faithful

## Pass 2 totals
- 87 numerical claims checked across the document
- ~82% verified clean
- 1 outright factual error (line 442 — Cuéllar numbers swapped)
- 2 numbers off (line 349 Family Options "18 months"; line 87 "first time in a century")
- ~10 scope-mismatch issues (cited source doesn't carry the specific claim)
- 3 inconclusive (paywalled or chart-only; need your in-browser verification)

## Top priority — fix verbatim
1. **Line 442 (§5.2)** — Cuéllar 0.81/0.78 labels are swapped (item #19 below).
2. **Line 349 (§4.1)** — Family Options Study tracked at 20 months and 3 years, not 18 (item #15 below).
3. **Line 87 (§1.1)** — "first time in a century" overstates cited source's "first time in decades" (item #5 below).

The remaining items below are mostly citation-pointer problems: the underlying numbers are usually right, but the cited sources don't fully support them. Group them by section and address opportunistically when revising each section.

---

## Introduction (lines 30–74)

### 1. Line 54 — Table 1 row: "5.5 million — McCue & Huang, 2024" (⚠ scope mismatch)

**The claim:** Table 1 ("Estimates of the United States Housing Shortage") attributes a 5.5 million figure to McCue & Huang (2024) at JCHS Harvard.

**The issue:** The McCue & Huang blog post is a *methodological review* of other organizations' estimates, not their own estimate. The 5.5M figure is at the upper end of the range they describe, derived from applying NAR's approach (which compares 2001–2020 construction to the 1968–2000 historical annual average of 1.5M/year). McCue & Huang don't endorse 5.5M as their own estimate.

**Why this matters:** The other rows in Table 1 cite the producing organization directly (NAHB via Siniavskaia, Freddie Mac, Zillow, Goldman/Peng & Mei, Moody's-Urban, McKinsey). This row is the only one citing a literature reviewer rather than the originating analyst.

**Options:**
- (a) Change attribution to NAR directly (the underlying methodology source).
- (b) Keep JCHS but relabel the row as "up to 5.5 million (high-end estimate)" or "1.5–5.5 million range".
- (c) Leave as-is and accept the slight imprecision since the prose around the table acknowledges that estimates "vary widely depending on methodology".

---

### 2. Line 36 — Cohn (NYT 2026) poll claim (? inconclusive)

**The claim:** "A New York Times/Siena poll found that about half of voters under 30 reported affordable housing as their primary concern, more than every other expense item combined, including retirement, health care, education, bills, transportation, and food."

**The issue:** NYT is paywalled; could not verify either (a) the "about half" share of under-30 voters or (b) the "more than every other expense item combined" framing.

**Why this matters:** The "combined" framing is a strong claim. If the poll asked respondents to choose a *single* top concern, "about half choosing housing" automatically beats any other single category but does not necessarily beat every other category combined. Worth eyeballing the actual crosstabs.

**Action needed:** You almost certainly have NYT access — please pull the Cohn 2026 piece or the Times/Siena crosstabs and confirm both numbers and the "combined" language.

---

### 3. Line 51 — Table 1 row: "~3 million" Goldman Sachs (🔧 refinement)

**The claim:** Table 1 attributes "~3 million" to Peng & Mei (2025) at Goldman Sachs.

**The issue:** Goldman's actual phrasing is "around 3–4mn additional homes (roughly 2.3% of the current housing stock)". Citing them at "~3 million" puts them at the low end of their own stated range.

**Why this matters:** Minor, but Table 1 is meant to display the range of estimates accurately, and Goldman's range is wider than what the table shows.

**Suggested fix:** Change "~3 million" to "~3–4 million", which preserves Goldman's full range and is consistent with the table's other "~" entries.

---

## §1.1 Federal Encouragement for Land Use Reform (lines 79–113)

### 4. Line 87 — SZEA historical detail not supported by cited source (⚠ scope mismatch)

**The claim:** "In 1921, Herbert Hoover's Commerce Department drafted the Standard State Zoning Enabling Act (SZEA), which was adopted in some form by roughly three quarters of states by 1930." Citation: Smart Growth America (2025).

**The issue:** The Smart Growth America piece references the SZEA only as "1920s-era" — it does not cite the 1921 date, Hoover, the Commerce Department's role in drafting, or the "three quarters of states by 1930" figure. The underlying historical facts are accurate (Hoover's Advisory Committee on Zoning was convened in 1921; SZEA was published in 1924, revised 1926; by 1930 about 35 of 48 states had adopted laws based on it), but the cited source doesn't support these specifics.

**Why this matters:** This is a sentence with several precise historical claims, and the only citation it carries doesn't substantiate them. A reader who clicks through to verify will not find the 1921/three-quarters/1930 numbers in the cited piece.

**Suggested fix:** Add a citation that does support the details (a planning history textbook, the original SZEA itself, or HUD's "Standard Zoning and Subdivision Acts" history). The next sentence in the same paragraph cites EIG (2025), which does mention "Hoover's 1921 Advisory Committee on Zoning" — so EIG could carry part of this load.

---

### 5. Line 87 — "first time in a century" overstates the cited source (~ off)

**The claim:** "The ROAD to Housing Act represents the first time in a century that Congress has reasserted federal leadership on matters related to zoning."

**The issue:** The cited Smart Growth America piece says "first time in *decades*" — not "in a century". The "century" framing is plausible given the 1920s SZEA → 2025 gap (~100 years), but it's a stronger claim than the source actually makes.

**Suggested fix:** Either (a) soften to "first time in decades" to match the source, or (b) keep "in a century" and add a supporting citation that uses that framing.

---

### 6. Line 98 — "Race to the Top appropriated around $6 billion to states in today's dollars" (🔧 refinement, also no citation)

**The claim:** Stated as fact without any citation.

**The issue:** RTT was funded at $4.35B in 2009 ARRA. Inflation-adjusted to 2026 dollars: ~$6.7B (using 2009 → 2026 CPI ratio of ~1.54). "Around $6 billion" rounds the figure down; "around $6.7 billion" or "roughly $7 billion" is more accurate.

**Suggested fix:** Update to "around $6.7 billion in today's dollars" and add a citation (Department of Education's RTT page, or Wikipedia's RTT entry citing the original ARRA appropriation).

---

### 7. Line 101 — Auckland rent claim citation [RESOLVED 2026-05-04]

**Status:** ✅ Fixed in `housing_draft.md`. The Auckland in-text citation has been split: construction → Greenaway-McGrevy & Phillips (2023); rents → Greenaway-McGrevy (2023), *Can Zoning Reform Reduce Housing Costs? Evidence from Rents in Auckland* (Economic Policy Centre Working Paper No. 016, University of Auckland, June 2023). New bibliography entry added at line 520.

**Still open (separate issue):** The *Greenaway-McGrevy & Phillips* bibliography entry (now line 522) still lists the journal as *Journal of Housing Economics*. The actual paper was published in ***Journal of Urban Economics*** (Vol. 136, art. 103555). See item #21 below and `non-access.md` item #24.

---

## §1.2 Update and Standardize Building Codes (lines 119–161)

### 8a. Line 139 — Switzerland sprinkler/height-limit claim cites a source that doesn't mention Switzerland (⚠ scope mismatch)

**The claim:** "...even though Switzerland does not require fire sprinklers in multifamily buildings and sets no height limit on single-stair construction ([Pew Charitable Trusts, 2025b])."

**The issue:** The cited Pew report ("Small Single-Stairway Apartment Buildings Have Strong Safety Record") discusses building codes in the Netherlands, Europe generally, and various U.S. cities — but it does not mention Switzerland. The underlying claim is independently verifiable (Swiss cantonal fire codes do permit single-stair multifamily without a height limit, and sprinklering is generally not required), but the Pew piece can't carry it.

**Suggested fix:** Replace the Pew citation here with a source that actually documents Swiss requirements. Candidates:
- The Second Egress jurisdictions database (https://secondegress.ca/Jurisdictions)
- The Swiss cantonal fire insurance association's regulations
- A working paper that surveys international single-stair regulations

The Pew citation is fine for the staircase cost figure earlier in the paragraph (line 127) — the issue is only on line 139.

---

### 8b. Line 139 — "Fire death rate 450% higher" needs direct verification (? inconclusive)

**The claim:** "The United States had a fire death rate 450% higher than that of Switzerland in 2023 ([Our World in Data, n.d.])."

**The issue:** Could not directly verify the 2023 Switzerland figure. OWID's underlying IHME data is not downloadable as CSV (license restriction). U.S. 2023 rate is ~1.31 per 100,000; if Switzerland's 2023 rate is around 0.24, the ratio would be ~5.4× (≈440%), close to the claimed 450%. But Switzerland's historical figure has hovered around 0.2/100k, which would yield ~6.5× (550%). Sensitive to small absolute differences in the Switzerland figure.

**Action needed:** Load https://ourworldindata.org/grapher/fire-death-rates, set country filter to United States and Switzerland, and read the 2023 values directly. Confirm or correct the "450%" figure.

---

## §2.2 Repeal the Faircloth Amendment (lines 219–251)

### 10a. Line 233 — HUD citation points to a database root, not a specific dataset (⚠ citation precision)

**The claim:** "In 2025, applicants spent an average of 25 months on the waiting list for public housing ([U.S. Department of Housing and Urban Development, 2026])."

**The issue:** The cited URL (https://www.huduser.gov/portal/datasets/assthsg.html) is the landing page for HUD's *Picture of Subsidized Households* database, not a specific dataset extract or report year. A reader can't reproduce "25 months for public housing in 2025" without knowing exactly which file/year/variable to query. The underlying figure is plausible (USAFacts reports 2024 average waiting time at ~27 months across all subsidized programs, and public housing is generally shorter than Section 8 HCV).

**Suggested fix:** Either (a) cite a specific HUD report or publication that reports the 25-month figure for 2025, or (b) cite a secondary source (USAFacts, NLIHC) that summarizes the data. As-is, the citation is hard to verify.

---

### 10b. Line 239 — "Demolished over 250,000 public housing units" citations don't fully cover the four-city scope (⚠ scope mismatch)

**The claim:** "Since the 1990s, major cities including Chicago, Atlanta, Philadelphia, and New Orleans have demolished over 250,000 public housing units due to deterioration; these homes had become uninhabitable and unsafe ([Collinson et al., 2015]; [Barkan, 2021])."

**The issue:**
- Collinson et al. (NBER w21071, 2015) is specifically about Chicago, not a four-city analysis. Chicago alone demolished ~21,000–25,000 units, well below 250,000.
- Barkan (2021, NYT) is an op-ed and is paywalled — couldn't verify.
- Total *nationwide* public housing demolitions from the 1990s through the late 2010s were ~370,000 (HOPE VI accounted for ~96,000; non-HOPE-VI demolitions made up the rest). So "over 250,000 nationally" is correct. But the doc's framing — "Chicago, Atlanta, Philadelphia, and New Orleans...250,000" — implies that those four cities alone demolished 250,000, which is not supported.

**Suggested fix:** Either:
- (a) Reframe as "Since the 1990s, U.S. cities have demolished over 250,000 public housing units, with the largest losses in Chicago, Atlanta, Philadelphia, and New Orleans" (citing Collinson for Chicago plus a national-aggregate source).
- (b) Replace with a national-level citation. The Urban Institute's "A Decade of HOPE VI" or the Vale & Freemark literature on public housing demolitions would carry this load. HOPE VI alone was ~96,000 units demolished; combined with non-HOPE-VI losses the national total clears 250k.

---

## §3.2 Reform Federal Funding (lines 291–319)

### 12. Line 306 — FHA 221(d)(4) "10,000 to 15,000 units annually" likely understates recent activity and has no citation (⚠ stale + missing citation)

**The claim:** "FHA's 221(d)(4) construction lending program offers favorable terms on paper but finances only about 10,000 to 15,000 units annually because of compliance burdens."

**The issue:** No citation for either the unit range or the "compliance burdens" diagnosis. Per HUD Multifamily Housing FY2024 data, the program insured 105 projects with **17,434 units** in FY2024, above the cited range. The 10,000–15,000 range may reflect a historical multi-year average (pre-FY24 figures were lower), but as written the claim is stale.

**Suggested fix:** Either:
- (a) Update to "averaged about 12,000 units annually over the past decade, with FY2024 reaching 17,434" and add a HUD citation.
- (b) Use a multi-year average and label it as such ("averaged ~13,000 units annually FY2018–FY2023").
- (c) Cite a secondary source (Williams 2026 may discuss the program; or HUD's Multifamily Production Data report).

---

### 13. Line 309 — "$30 billion FHLB retained earnings" is correct but uncited (🔧 missing citation)

**The claim:** "[The FHLB system's] retained earnings, which stood at over $30 billion system-wide at the end of 2024..."

**The issue:** The figure is verifiable and correct (the FHLB 2024 Q4 Combined Financial Report shows retained earnings of **$30.6 billion** at December 31, 2024, up 10% from $27.9 billion the prior year). But there's no citation in the text.

**Suggested fix:** Add a citation: FHLBanks Office of Finance, *Combined Financial Report for the Year Ended December 31, 2024* (https://www.fhlb-of.com/ofweb_userWeb/resources/2024Q4CFR.pdf).

---

## §4.1 Give Low-Income Renters Money (lines 321–355)

### 15. Line 349 — Family Options Study follow-up duration is wrong (~ off)

**The claim:** "The federal Department of Housing and Urban Development's Family Options Study...randomly assigned 2,282 homeless families to a series of different treatments and traced their impact over a period of 18 months."

**The issue:** The 2,282 enrollment is correct, but the follow-up duration is wrong. The Family Options Study tracked families at:
- **20 months** after random assignment (first follow-up, "Short-Term Impacts" report, 2015)
- **37 months / 3 years** after random assignment ("Long-Term Impacts" report, 2016, by Gubits et al.)

There was no 18-month follow-up. The doc's "18 months" is likely a misremembering of the 20-month first follow-up, or possibly confusing the rapid re-housing intervention (which provides up to 18 months of assistance) with the study's measurement period.

**Suggested fix:** Replace "18 months" with either:
- (a) "20 months" if referring to the first follow-up
- (b) "3 years" or "37 months" if referring to the long-term impact study
- (c) "20 and 37 months" to capture both measurement points

The substantive finding (rent subsidies most reduced homelessness) is correct in either timeframe.

---

## §5.1 Stabilize Rents for Older Rental Properties (lines 384–416)

### 17. Line 404 — Kholodilin direct quote may not be verbatim (⚠ exact-quote accuracy)

**The claim:** "A 2024 literature review published in the *Journal of Housing Economics* ([Kholodilin, 2024]) affirmed the academic consensus that the 'imposition of rent ceilings amplifies the shortage of housing.'"

**The issue:** The substance is correct (Kholodilin's review reaches this conclusion). However, the doc places the phrase in quotation marks, implying it's verbatim from the paper. Multiple secondary summaries of Kholodilin's paper render the line as "The imposition of rent **control** amplifies the shortage of housing" (not "rent ceilings"). The paper itself is paywalled and I couldn't access the exact wording.

**Why this matters:** Quoting a phrase that isn't verbatim is a citation error that could be flagged by an attentive reader. "Rent ceilings" and "rent control" are not identical concepts in this literature — rent ceilings are a stricter form of rent control.

**Action needed:** Pull the Kholodilin (2024) paper from ScienceDirect or via institutional access, find the exact phrasing in the conclusion or abstract, and either:
- (a) Confirm the quote is verbatim and leave the quotation marks.
- (b) Update to the actual verbatim phrasing (likely "rent control" not "rent ceilings").
- (c) Drop the quotation marks and treat as paraphrase.

---

## §5.2 Just Cause Eviction Protections (lines 418–446)

### 19. Line 442 — Cuéllar (2019) eviction-rate vs filing-rate numbers are SWAPPED (✗ refuted)

**The claim:** "These just cause protections led to a reduction in eviction rates in East Palo Alto, Glendale, Oakland, and San Diego, where initial **eviction filing rates** dropped **0.81** percentage points and overall **eviction rates** dropped **0.78** percentage points ([Cuéllar, 2019])."

**The issue:** The numbers are attached to the wrong labels. Cuéllar's actual findings (Princeton JPIA, May 2019):
- **Eviction rates** dropped by **0.808** percentage points
- **Eviction filing rates** dropped by **0.780** percentage points

So 0.81 belongs with eviction *rates*, and 0.78 belongs with eviction *filing rates* — the opposite of what the doc says.

**Why this matters:** This is the only clear-cut factual error in §5.2 and one of only a few outright refuted numbers in the whole document. The substance of the claim (that just cause reduced both metrics) survives, but the specific numbers are mislabeled.

**Suggested fix:** Reword to:
> "...where overall eviction rates dropped 0.81 percentage points and eviction filing rates dropped 0.78 percentage points ([Cuéllar, 2019])."

Or, if you want to lead with filing rates first to match the doc's current ordering:
> "...where eviction filing rates dropped 0.78 percentage points and overall eviction rates dropped 0.81 percentage points ([Cuéllar, 2019])."

---

## Bibliography (Pass 1 — Structural)

### 21. Line 520 — Greenaway-McGrevy & Phillips wrong journal name (✗ refuted)

**The bibliography entry says:**
> Greenaway-McGrevy, R., & Phillips, P. C. B. (2023). The impact of upzoning on housing construction in Auckland. *Journal of Housing Economics*, 62, 101981. [URL]

**The issue:** The actual paper appeared in ***Journal of Urban Economics*** (Vol. 136, article 103555), not *Journal of Housing Economics*. The Auckland paper has been confused with Kholodilin's *Journal of Housing Economics* article that's also in this bibliography (line 544). The volume number "62" and article number "101981" in the doc don't match either paper as cited.

**Suggested fix:** Update line 520 to:
> Greenaway-McGrevy, R., & Phillips, P. C. B. (2023). The impact of upzoning on housing construction in Auckland. *Journal of Urban Economics*, 136, 103555. https://www.sciencedirect.com/science/article/abs/pii/S0094119023000244

(Verify volume/article number from the ScienceDirect landing page — see `non-access.md` item #24 for browser confirmation.)

---

### 22. Bibliography URLs requiring browser verification (30 entries)

Thirty bibliography URLs returned bot-blocks (403/406/timeout) from CLI. Listed in `non-access.md`. The most consequential to verify are:

- **Cohn 2026 (NYT)** — line 482 — needs the "about half of voters under 30" / "more than every other expense item combined" claims confirmed.
- **Greenaway-McGrevy & Phillips 2023** — line 520 — needs journal name corrected (above).
- **Kholodilin 2024** — line 544 — needs the verbatim "rent ceilings/control" wording confirmed.

The others are likely fine but cannot be confirmed from this environment.

---

### 23. Two URL-fragment inconsistencies between in-text and bibliography (🔧 cosmetic)

Two in-text citations include URL anchors (e.g., `#sec0008`) that point to specific sections of the cited piece, while the bibliography lists only the bare URL.

- **Line 134 (§1.2)**: in-text `#a-brief-history-of-us-building-codes` anchor on the Cato `reforming-us-building-codes` URL.
- **Line 404 (§5.1)**: in-text `#sec0008` anchor on the ScienceDirect Kholodilin URL.

These aren't errors — anchors that point to specific sections are useful for the reader. But for strict link consistency, you may want to either drop the anchor in-text or include it in the bibliography URL.

---

### 24. Line 111 — "Inspired imitation in over a dozen states" cites a 2021 source (⚠ stale citation)

**The claim:** Oregon's HB 2001 (2019) "has since inspired imitation in over a dozen states ([Andersen, 2021])."

**The issue:** The cited Sightline piece is from August 2021. At that time, similar bills had been *introduced* in ten states (CT, MN, MD, MT, NE, NH, NC, VT, VA, WA), but Andersen explicitly notes: "by summer 2021, nothing nearly so sweeping had yet passed anywhere else." So "over a dozen states have followed" cannot be supported by a 2021 source.

**Why this matters:** The claim may well be true *as of 2026* (Washington 2023 HB 1110, Montana 2023 SB 323, California 2024 SB 1123, etc.), but the 2021 citation predates most of those passages. A reader checking the citation will find a piece that says the opposite (that no other state had passed comparable legislation yet).

**Suggested fix:** Add or replace with a more recent citation that surveys post-2021 passage of missing-middle reforms across states. Pew (2025c), already in the bibliography, may be a fit. Alternatively, change "over a dozen states" to "ten states" and qualify with "where similar bills have been introduced" to match the 2021 source.

---