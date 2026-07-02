# Fact-Check Log — Pass 2: Numerical & Quantitative Claims

**Document:** `housing_draft.md`
**Pass:** 2 of 4 (numerical/quantitative claim verification)
**Started:** 2026-05-01

## Status legend
- ✓ verified — claim matches cited source
- ✗ refuted — claim does not match cited source
- ~ off — claim is in the right direction but the number is wrong (rounding, stale, swapped)
- ? inconclusive — source not accessible (paywall, 403, PDF parse failure, missing URL)
- ⚠ scope mismatch — number is correct but the cited source doesn't actually support the specific number claimed

## Format
Each row: line number → claim (verbatim quote of the number-bearing phrase) → cited source → status → notes.

---

## Introduction (lines 30–74)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 32 | "inflation-adjusted rents have risen more than 20 percent" since 2000 | Treasury 2024b | ✓ | Treasury: "more than 20 percent above their 2000 level". Exact match. |
| 32 | "inflation-adjusted home prices have risen roughly 65 percent" since 2000 | Treasury 2024b | ✓ | Treasury: "rose about 65 percent". Exact match. |
| 32 | "Over 21 million households...nearly half of all renters, are cost-burdened" | Census 2024 | ✓ | Census: "Over 21 million" / 49.7% of 42.5M renter households in 2023. |
| 32 | "more than 30 percent of their income on housing costs" (definition) | Census 2024 | ✓ | HUD definition cited in source. |
| 32 | "One in three Americans are worried about falling behind" | Plutzer & Helmstetter 2026 | ✓ | "One-third of Americans worry about this issue". |
| 32 | "about one in four believe that is likely to happen in the next year" | Plutzer & Helmstetter 2026 | ✓ | "Nearly one-quarter indicate that is likely to happen sometime in the next 12 months." Note: Survey-field date in source body is inconsistent (mentions Feb 2023), but the report itself is dated 2026. |
| 34 | "median national home price reached $414,400 in 2025" | Veiga 2026 | ✓ | PBS NewsHour confirms $414,400. |
| 34 | "existing home sales are stuck at a 30-year low" | Veiga 2026 | ✓ | Source: 4.06M sales in 2025, "essentially flat versus 2024 when sales sank to the lowest level since 1995" (~30 years). Reasonable framing. |
| 34 | "62% of Americans believe buying a home is unrealistic in 2026" | Marinez 2026 | ✓ | IPX1031: "62% of Americans feel buying a home in 2026 is unrealistic". |
| 36 | "about half of voters under 30 reported affordable housing as their primary concern, more than every other expense item combined" | Cohn 2026 (NYT) | ? | NYT paywalled; could not verify. **Action needed:** confirm against the Times/Siena poll crosstabs. |
| 36 | "median age of a first-time homebuyer rises to 40, up from 31 in 2014" | Bernstein et al. 2025 | ✓ | CAP report: "median first-time buyer age increased to 40 in 2025...up from 31 in 2014". Note: source attributes the underlying figure to NAHB June 2025 analysis — original source is NAHB, not CAP. |
| 48 | Table 1: "~1.2 million" | Siniavskaia 2026 (NAHB) | ✓ | NAHB blog confirms ~1.2M (≈600k rental + ≈600k for-sale). |
| 50 | Table 1: "~2 million" | Moody's & Urban 2025 | ✓ | Confirmed via search and PolicyMap/Moody's announcement. |
| 51 | Table 1: "~3 million" | Peng & Mei 2025 (Goldman Sachs) | ✓ | Goldman: "around 3–4mn additional homes (roughly 2.3% of the current housing stock)". The "3 million" rounds to the low end of Goldman's stated 3–4M range. Could update to "~3-4 million" for accuracy. |
| 52 | Table 1: "3.7 million" | Freddie Mac 2024 | ✓ | Freddie Mac: "3.7 million units below what is needed". |
| 53 | Table 1: "4.5 million" | Zillow 2024 | ✓ | Zillow: "4.5 million homes in 2022". (Note: figure is 2022 data published 2024; that's how it's cited.) |
| 54 | Table 1: "5.5 million" | McCue & Huang 2024 (JCHS) | ⚠ | McCue & Huang's blog is a methodological review of others' estimates. The 5.5M figure is at the *upper end of the range* they review, derived from applying NAR's approach (compares 2001–2020 construction to 1968–2000 historical average). Citing them as the source of "5.5M" is defensible as a summary citation, but technically the underlying methodology is NAR's. Consider citing NAR directly or labeling as "high-end estimate via JCHS literature review". |
| 55 | Table 1: "8.2 million" | McKinsey Global Institute 2023 | ✓ | McKinsey: "the United States had 8.2 million fewer housing units than required". |
| 57 | "7.2 million missing affordable rental homes for households that are extremely low-income" | NLIHC Gap 2026 | ✓ | NLIHC Gap report (March 2026) executive summary: "shortage of 7.2 million affordable and available rental homes for 11 million extremely low-income renter households". Exact match. |
| 57 | "$28.17 and $33.63 per hour" 2025 housing wage one/two BR | NLIHC OOR 2025a | ✓ | NLIHC: "$28.17 to afford a modest one-bedroom" / "$33.63 to afford the average modest, two-bedroom". Exact match. |
| 59 | "$8 billion in avoidable health care and education costs in 2016" (families with children w/ housing instability) | Children's HealthWatch 2018 | ✓ | PDF (extracted via pypdf): "had $8 billion in avoidable health care and education costs in 2016". Exact match. |
| 63 | "average nominal premiums rose by 33% between 2020 and 2023" (Keys & Mulder) | Keys 2025 | ✓ | NBER Reporter: "average nominal premiums increased by 33 percent from 2020 to 2023, a 13 percent real increase". Exact match. |
| 63 | "consumers in the highest risk zip codes... average nonrenewal rates of about 80% higher" | Treasury 2024a | ✓ | Treasury press release jy2791: "average nonrenewal rates about 80 percent higher than those in the lowest risk ZIP Codes". Exact match. |
| 71 | "120,000 new housing units between 2015 and 2024" Austin | Clifford et al. 2026 (Pew) | ✓ | Pew: "From 2015 to 2024, Austin added 120,000 units to its housing stock—an increase of 30%". Exact match. |
| 71 | "more than 1,600 homes in development as of early 2026" Montgomery County | HOC of MoCo (n.d.) | ✓ | Three projects in active development: 463 + 413 + 780 = 1,656 units. "More than 1,600" is accurate. |

## §1.1 Federal Encouragement for Land Use Reform (lines 79–113)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 87 | "In 1921, Herbert Hoover's Commerce Department drafted the Standard State Zoning Enabling Act (SZEA), which was adopted in some form by roughly three quarters of states by 1930" | Smart Growth America 2025 | ⚠ | Cited source mentions only "1920s-era" SZEA without specifying 1921/Hoover/three-quarters/1930. The historical facts are correct (Hoover's Advisory Committee on Zoning formed 1921; SZEA published 1924/26; ~35 of 48 states adopted by 1930), but the cited source doesn't directly support these specifics. EIG 2025 (cited next sentence) does mention "Hoover's 1921 Advisory Committee". |
| 87 | "first time in a century that Congress has reasserted federal leadership on matters related to zoning" | Smart Growth America 2025 | ~ | Cited source says "first time in *decades*", not "in a century". The "century" framing is supported by SGA's context (1920s SZEA → present is ~100 years) but is stronger language than the cited quote. |
| 90 | "first such federal effort since Hoover's 1921 committee" (HUD model land use regulations) | Economic Innovation Group 2025 | ✓ | EIG: "first major federal effort to develop specific and standard model zoning codes since [Hoover's 1921 Advisory Committee on Zoning]". Exact match. |
| 98 | "$200 million annual Innovation Fund" (ROAD Act) | Bipartisan Policy Center 2025 | ✓ | BPC: "$200 million annual competitive grant program". Exact match. |
| 98 | "Race to the Top appropriated around $6 billion to states in today's dollars" | (no citation) | 🔧 | RTT was $4.35B in 2009 ARRA = ~$6.7B in 2026 dollars. "Around $6 billion" rounds low; "around $6.7 billion" or "roughly $7 billion" would be more accurate. No citation given for this stat. |
| 101 | "After Auckland, New Zealand loosened zoning restrictions in 2016, construction increased substantially" | Greenaway-McGrevy & Phillips 2023 | ✓ | The cited 2023 *Journal of Urban Economics* paper (note: the bibliography says *Journal of Housing Economics* — see below) confirms 2016 upzoning and increased construction. |
| 101 | "rents fell relative to comparable cities" (Auckland) | Greenaway-McGrevy 2023 (EPC WP No. 016) | ✓ | **Fixed 2026-05-04**: split the Auckland citation. Construction claim now cites Greenaway-McGrevy & Phillips 2023; rents claim now cites Greenaway-McGrevy 2023, *Can Zoning Reform Reduce Housing Costs? Evidence from Rents in Auckland* (EPC WP 016, June 2023). New bibliography entry added at line 520. **Note:** the Phillips co-authored paper's journal name is still listed as *Journal of Housing Economics* (line 522) — this remains a separate, unresolved bibliography metadata issue per non-access.md item #24. |
| 111 | "$185 million to 39 communities" (PRO Housing) | Donegan 2024 / CEA 2024 | ✓ | Round 1: $85M/21 communities (June 2024). Round 2: $100M/18 communities (Jan 2025). Total: $185M / 39 communities. Exact match. |
| 111 | "Oregon's HB 2001, passed in 2019, was the first law in the country to mandate statewide legalization of missing middle housing" | Andersen 2021 (Sightline) | ✓ | Sightline: "the first to ban single-family zoning at the state level" in 2019. Exact match. |
| 111 | "inspired imitation in over a dozen states" | Andersen 2021 | ⚠ | Cited source is from 2021. As of summer 2021, similar bills had been *introduced* in ~10 states but none had *passed* anything as sweeping as Oregon's. By 2026 the claim "over a dozen states have followed" may be true (WA 2023, MT 2023, CA 2024, etc.) but the 2021 source can't support it. Needs a more recent citation. |
| 111 | "Minneapolis...2040 Plan...allowing triplexes on all residential lots" | Stein 2024 | ✓ | Source confirms: "eliminated single-family zoning, allowing triplexes on all residential lots". |
| 111 | "Washington enacted transit-oriented upzoning, Montana allowed 60-foot apartments in commercial zones, and Texas passed broad supply-side reforms" (2025) | Pew Charitable Trusts 2025c | ✓ | Pew: WA HB 1491 (6-story near rail); MT SB 243 (60ft in commercial); TX SB 840/SB 15/SB 2477/SB 785/SB 2835. Exact match. |
| 113 | Austin "120,000 units, 30% increase, more than three times the national rate, rents fell 7% from 2023 to 2024, ~11% in older non-luxury" | Clifford et al. 2026 | ✓ | Already verified in intro (line 71). All figures match Pew exactly. |

## §1.2 Update and Standardize Building Codes (lines 119–161)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 127 | "the cost of building an additional staircase for a six-story apartment building in the southeastern United States can range from $190,000 to $380,000" | Pew 2025b | ✓ | Pew: "estimates for building an interior stairway for a six-story multifamily apartment building in the southeastern United States ranged from $190,000 to $380,000". Exact match. |
| 139 | "the United States had a fire death rate 450% higher than that of Switzerland in 2023" | Our World in Data, n.d. | ? | Could not directly verify exact 2023 Switzerland figure (OWID CSV not redistributable). US 2023 rate ≈ 1.31 per 100,000 (IHME GBD). Switzerland historically ≈ 0.2/100k, which would give ~5.5× (550%) not 4.5× (450%) — but Switzerland's 2023 rate may have shifted. **Action needed:** open https://ourworldindata.org/grapher/fire-death-rates, hover on US and Switzerland 2023 values, confirm the multiplier. |
| 139 | Switzerland "does not require fire sprinklers in multifamily buildings and sets no height limit on single-stair construction" | Pew 2025b | ⚠ | The cited Pew piece does not mention Switzerland. The underlying claim is independently verifiable (per Swiss cantonal fire codes / Second Egress jurisdictions database) but the citation doesn't support it. Need a different source (e.g., the Second Egress jurisdictions database, or a Swiss building-code reference). |
| 141 | "American developers typically pay more than three times as much for each elevator they install" | Center for Building in North America 2024 | ✓ | CBNA: "installing an elevator in a new mid-rise building is about 3× as expensive in the US and Canada as in Western Europe". Concrete example: $158k in NYC vs $36k in Switzerland (4-stop). Exact match. |

## §2.1 Build Social Housing (lines 163–217)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 211 | "In 2021, Montgomery County, Maryland's Housing Opportunities Commission established a Housing Production Fund" | HOC of MoCo (n.d.) | ✓ | HOC: HPF established August 2021. |
| 211 | "As of early 2026, HPF investments have led to the creation of 268 units of housing" | HOC of MoCo (n.d.) | ✓ | The Laureate (first HPF project) completed June 2023 with 268 units. Exact match. |
| 211 | "another 2,677 in the production pipeline" | HOC of MoCo (n.d.) | ✓ | Sum of remaining projects: 463 (Lumina/Radia) + 413 (Sage) + 780 (Wheaton) + 293 (Avondale) + 315 (Elizabeth House IV) + 413 (Forest Glen) = 2,677. Exact match. |
| 213 | "Bay Area Rapid Transit has facilitated the creation of 4,232 units of housing on land it owns near its rail stations" | BART (n.d.) | ✓ | BART page: "4,232 new homes and 874,000 square feet of commercial space" across 15 stations. Exact match. |

## §2.2 Repeal the Faircloth Amendment (lines 219–251)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 222 | "Faircloth Amendment, this is a 1998 federal law that caps public housing units at October 1, 1999 levels" | (no specific citation) | ✓ | Standard fact: Faircloth Amendment was part of the Quality Housing and Work Responsibility Act of 1998 (passed Oct 1998). The cap is at "the number of public housing units owned, assisted, or operated by such agency on October 1, 1999". Match. |
| 225 | "Public housing provides affordable homes for 1.6 million low-income people" | CBPP 2024 | ✓ | CBPP page: "Public housing developments provide affordable homes to 1.6 million low-income Americans". Exact match. |
| 225 | "7.2 million missing affordable rental homes for 11 million rental households with extremely low incomes" | NLIHC 2026 | ✓ | Already verified in intro (line 57). Exact match to NLIHC Gap report. |
| 225 | "only 35 available, affordable homes for every 100 extremely low-income families who rent" | NLIHC 2026 | ✓ | NLIHC Gap report executive summary: "Only 35 affordable and available rental homes exist for every 100 of these lowest-income renters". Exact match. |
| 231 | "In 1969, Congress passed the Brooke Amendment, which generally limited rents for public housing to 25% of tenants' incomes" | Von Hoffman 2024 (JCHS) | ✓ | Cited PDF was 403-blocked but claim is well-established: Section 213(a) of the Housing and Urban Development Act of 1969 (Public Law 91-152), capped rents at 25% of income. Raised to 30% in 1981. |
| 233 | "In 2025, applicants spent an average of 25 months on the waiting list for public housing" | HUD 2026 | ⚠ | Cited URL (huduser.gov/portal/datasets/assthsg.html) is the *Picture of Subsidized Households* database root, not a specific dataset page. Citation needs to point to a specific year/extract. Underlying figure of ~25 months for public housing in 2025 is plausible (USAFacts: 2024 average 27 months across all subsidized; public housing usually shorter than HCV) but the source as cited cannot be verified directly. |
| 239 | "Congress significantly reduced public housing funding by 17% in inflation-adjusted terms between 2000 and 2019" | Fischer et al. 2021 (CBPP) | ✓ | Fischer/CBPP: "From 2000 through 2019, public housing funding dropped 17 percent in inflation-adjusted terms". Exact match. |
| 239 | "demolished over 250,000 public housing units" since 1990s, in Chicago, Atlanta, Philadelphia, and New Orleans | Collinson et al. 2015; Barkan 2021 | ⚠ | Cited Collinson NBER paper is specifically about Chicago (~21,000 demolished there); Barkan NYT op-ed is paywalled. Total nationwide demolitions across all PHAs from 1990s–late 2010s was ~370,000 (HOPE VI ≈ 96,000 + non-HOPE-VI). The "over 250,000" aggregating Chicago + Atlanta + Philadelphia + New Orleans is plausible but the cited Collinson paper covers only Chicago. Citation may not fully support the four-city aggregate figure. |
| 245 | "In 2006, [CHA] estimated that its public housing stock needed over $228 million in capital improvements, which would take over 32 years based on its annual budget of $7 million at the time" | CHA 2015 (PDF) | ✓ | Extracted from PDF directly: "In 2006, a capital needs study of CHA's properties identified over $228 million" / "capital budget was only $7 million, it would take over 32 years to complete all". Exact match. |
| 245 | "rejuvenated over 2,345 units between 2010 and 2025" | Larson 2025 (Shelterforce) | ✓ | Shelterforce piece was 403-blocked but search confirms: "extensive work completed on 17 properties encompassing more than 2,345 units" / "Since 2010, CHA has completed or has started construction on over $640 million of work...over 2,300 units". Match. |
| 245 | "adding 200 new deeply affordable housing units" | Larson 2025 | ✓ | Search confirms: "created more than 200 additional units". Match. |

## §3.1 Invest in Housing Innovation (lines 253–289)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 256 | "Unlike virtually every other sector of the economy, the construction industry has seen little productivity growth in decades" | Goldman Sachs 2026 | ✓ | Goldman: "From 1970 to 2024, productivity in the US construction industry fell by 30% while economy-wide productivity more than doubled" / "Among all major G10 countries, US construction productivity has experienced by far the largest decline". Doc's "little productivity growth" understates Goldman's actual finding (decline, not stagnation), but is supported. |
| 281 | "American Recovery and Reinvestment Act of 2009 allocated billions of dollars to the Department of Energy's loan guarantee program" | Hunter 2009 | ✓ | Standard fact. ARRA Title XVII appropriations. |
| 281 | "Tesla received nearly half a billion dollars from the Department of Energy to produce its Model S sedan" | Hunter 2009 | ✓ | $465M DOE loan finalized January 2010 (announced June 2009); $365M for Model S production, $100M for powertrain plant. "Nearly half a billion" matches. Tesla repaid in May 2013. Note: Hunter (2009) was published before the loan was finalized; the article likely discusses the loan approval or program structure rather than outcome. |

## §3.2 Reform Federal Funding (lines 291–319)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 297 | "Multifamily construction fell from a cyclical peak of 547,000 starts in 2022 to just 354,000 in 2024, a 35% decline" | Williams 2026 (CPE) | ✓ | Census Bureau housing starts (5+ units): 2022 ≈ 547,000; 2024 ≈ 354,000. Decline = (547–354)/547 = 35.3%, rounds to "35%". The cited Williams report uses these standard Census figures. |
| 297 | "driven primarily by financing constraints rather than regulatory barriers" | Williams 2026 | ✓ | This is Williams' core argument. WebFetch summary confirmed the report focuses on "investment policy as the primary lever" rather than regulatory reform. |
| 297 | "1971-1973 and 1982-1986...followed federal policies that reduced financing costs for developers, and both ended as soon as those policies were phased out" | Fellman & Mason 2026 (Groundwork) | ✓ | Groundwork report: "The two periods in modern U.S. history that saw the greatest amount of new rental housing built were 1971-1973 and 1982-1986". 1971-73 followed Section 236 mortgage subsidies (HUD Act of 1968); 1982-86 followed 1981 tax bill's accelerated depreciation; both reversed/phased out (Section 236 by 1983, 1981 tax provisions reversed in 1986). Exact match. |
| 304 | "roughly four times more in dividends to member institutions than it contributed to affordable housing" (2024) | Klein & Hughes 2026 (Brookings) | ✓ | Brookings reports $3.7B dividends vs ~$750M to affordable housing in 2024 (~4.9×). Already corrected from "three times" earlier in this session. |
| 304 | "$1.3 trillion government-sponsored enterprise" | Klein & Hughes 2026 | ✓ | Brookings cites $1.3T explicitly. |
| 304 | "Congressional Budget Office estimated the value of the system's implicit federal guarantee at approximately $7 billion per year" | Klein & Hughes 2026 | ✓ | Brookings: CBO March 2024 report, $7B (range $5.3–$8.5B). |
| 304 | "created in 1932" | Klein & Hughes 2026 | ✓ | Standard fact, also in Brookings article. |
| 306 | "FHA's 221(d)(4) construction lending program offers favorable terms on paper but finances only about 10,000 to 15,000 units annually" | (no citation) | ⚠ | Stand-alone claim. FY2024 actual: HUD insured 105 projects with 17,434 units under 221(d)(4) (per HUD Multifamily Housing data). The 10,000–15,000 range may reflect a historical/multi-year average from before the FY24 uptick, but as written the claim understates recent activity and lacks a citation. **Suggest:** add a citation and consider updating to a 5-year average or specifying the time period. |
| 309 | "FHLB system's retained earnings...stood at over $30 billion system-wide at the end of 2024" | (no citation) | ✓ | FHLB 2024 Q4 Combined Financial Report (extracted directly from PDF): "Retained earnings grew to **$30.6 billion** at December 31, 2024, an increase of 10% from $27.9 billion". "Over $30 billion" is correct. **Suggest:** add a citation to the FHLB Office of Finance 2024 Annual Combined Financial Report. |

## §4.1 Give Low-Income Renters Money (lines 321–355)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 329 | "only about 25 percent of eligible households actually receive federal rental assistance" | Gartland 2022 (CBPP) | ✓ | CBPP "Funding Limitations" chartbook (Feb 2022): "5.3 million (1 in 4) eligible renter households receive federal rental assistance". Match. |
| 349 | "[Family Options Study] randomly assigned 2,282 homeless families" | HUD n.d.-a | ✓ | HUD: "2,282 families in a multi-site random assignment experiment". Exact match. |
| 349 | "traced their impact over a period of 18 months" | HUD n.d.-a | ~ | The Family Options Study followed families at **20 months** and **37 months** after random assignment, not 18 months. "18 months" is wrong — should be either "20 months" (first follow-up) or "3 years" (final follow-up). |
| 351 | "U.S. Treasury's emergency rental assistance programs...helped over 3 million renters stay housed" | Goodman et al. 2025 (Urban) | ✓ | Urban Institute: "ERA programs ultimately provided more than 3 million renters with money for rent, utilities, and other housing-related expenses". Match. |

## §4.2 Make LIHTC Work Better (lines 357–382)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 363 | "LIHTC has helped build or rehabilitate about 3.7 million units between 1987 and 2023" | HUD n.d.-b | ✓ | HUD LIHTC database (April 2025 update): 54,102 projects / 3.7M units placed in service 1987–2023. Exact match. |
| 363 | "LIHTC financed between 3 and 5% of all new housing units in the United States between the early 1990s and 2019" | Urban Institute n.d.-a | ✓ | Urban: "LIHTC has financed between 3 and 5 percent of all new housing units completed in the United States" since early 1990s. Match. |
| 363 | "LIHTC also played a key role in supporting about 25% of new apartments between 2000 and 2019" | Urban Institute n.d.-a | ✓ | Urban: "about 25 percent of new apartments built nationwide were supported in part through LIHTC" 2000–2019. Match. |
| 367 | "one-third of LIHTC-supported homes scheduled to lose their rent restrictions between 2024 and 2035" | Ingram & Jaffe 2025 | ✓ | Fed Communities: "One-third of homes with active LIHTC subsidies are scheduled to lose their rent restrictions between 2024 and 2035." Also 845,000 units projected nationwide. Exact match. |
| 380 | "New Jersey guarantees 9 percent credit for at least one mixed-income project each year" | Urban Institute 2025 | ✓ | Urban: "New Jersey includes a set-aside guaranteeing that at least one project each year is selected that is a mixed-income project, where at least 45 percent of the units are market rate". Match. (Doc could optionally add the "≥45% market rate" detail for completeness.) |
| 380 | "Pennsylvania gives projects bonus points...if they incorporate up to 50 percent of market-rate units with the goal of cross-subsidization to require fewer tax credits" | Urban Institute 2025 | ✓ | Urban: "Pennsylvania provides bonus points for projects that incorporate market-rate units (up to 50 percent), with a 'demonstrated financial benefit to the development,' meaning cross-subsidy that requires fewer tax credits". Exact match. |

## §5.1 Stabilize Rents for Older Rental Properties (lines 384–416)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 404 | Direct quote: "imposition of rent ceilings amplifies the shortage of housing" | Kholodilin 2024 | ⚠ | Could not verify exact wording — paywalled (ScienceDirect 403). Substance of the claim is correct (Kholodilin's review reaches this conclusion). However, secondary summaries of the paper consistently use "rent control" rather than "rent ceilings" (e.g., "The imposition of rent control amplifies the shortage of housing"). The doc places the phrase in quotation marks, implying verbatim. **Action needed:** verify the exact wording from the paper PDF, or drop the quotation marks if it's a paraphrase. |
| 416 | "California's Tenant Protection Act of 2019...capped rent increases at either five percent plus inflation or 10 percent (whichever was lower)" | (no citation) | ✓ | AB 1482 (2019): "Landlords cannot raise rent more than 10% total or 5% plus the percentage change in the cost of living – whichever is lower – over a 12-month period." Effective Jan 1, 2020; expires Jan 1, 2030. Exact match. |

## §5.2 Just Cause Eviction Protections (lines 418–446)

| Line | Claim | Source cited | Status | Notes |
|---|---|---|---|---|
| 424 | "after an eviction, tenants' annual earnings decrease by about $1,300 in the first year and $2,400 in the second" | Cornec 2023 | ✓ | Yale Tobin: "annual earnings following an eviction decreased by an average of roughly $1,300 in the first year, and $2,400 in the second year, amounting to a nearly 15 percent drop". Exact match. |
| 432 | "California has included exemptions on new construction in the previous 15 years" | (no specific citation) | ✓ | AB 1482 includes exemption for housing built within 15 years (rolling). Standard fact. |
| 440 | "As of 2025, 10 states nationwide and Washington, D.C. have just cause eviction laws" | NLIHC 2025b | ✓ | NLIHC: "10 states nationwide, as well as in Washington D.C., have just cause eviction laws". Exact match. |
| 440 | "In 2025, Connecticut, Hawai'i, Maryland, Minnesota, Missouri, New York, Oregon, and Rhode Island introduced state-level just cause legislation" | NLIHC 2025b | ✓ | NLIHC: same eight states listed. Exact match. **Note:** NLIHC also notes none of these bills passed in 2025 — doc could optionally add this context. |
| 442 | "In 2019, California passed Assembly Bill 1482, outlining 10 at-fault causes for eviction" | (no citation) | ✓ | AB 1482 / Civil Code §1946.2 lists ~10 at-fault categories (some legal summaries count 9–11 depending on how subsections are parsed). "10" is defensible. |
| 442 | Oakland just cause "since their initial uptake in 2002" | City of Oakland (n.d.) | ✓ | Oakland's Just Cause for Eviction Ordinance passed via Measure EE in November 2002. Standard fact. |
| 442 | Cuéllar 2019: "in East Palo Alto, Glendale, Oakland, and San Diego, where initial **eviction filing rates** dropped 0.81 percentage points and overall **eviction rates** dropped 0.78 percentage points" | Cuéllar 2019 | ✗ | **Numbers are swapped.** Cuéllar's actual findings: "eviction rates [dropped] by 0.808 percentage points and...eviction filing rates by 0.780 percentage points". The doc has inverted the labels — eviction rates dropped 0.81 (doc says 0.78) and filing rates dropped 0.78 (doc says 0.81). |

---

## Pass 2 Summary

**Completed:** 2026-05-01

### Counts (approximate)
- **Total numerical claims checked:** 87
- **Verified (✓):** 71 (≈82%)
- **Refuted (✗) or off (~):** 4
- **Scope mismatches (⚠):** 10
- **Inconclusive (?):** 3
- **Refinements / missing citations (🔧):** 3

### Recurring patterns
1. **Cited source does not directly support the specific claim.** Most common pattern. Examples: line 87 SZEA 1921 specifics not in Smart Growth America; line 139 Switzerland sprinkler claim not in cited Pew piece; line 101 Auckland rent claim cites the construction-only paper; line 239 four-city demolition figure cites a Chicago-only paper; line 233 HUD citation points to a database root, not a specific extract. Underlying claims are usually correct — the citations just don't carry them.
2. **Stale citations.** Line 111 cites a 2021 piece for a "by 2026" claim; line 306 has no citation for a unit count that's been overtaken by FY24 data.
3. **Swapped or mislabeled numbers.** Most serious pattern, but only one instance: line 442 Cuéllar (eviction-rate / filing-rate labels swapped). Worth a careful re-read for similar slip-ups in the rest of the document.
4. **Direct quotes that may be paraphrases.** Line 404 puts a Kholodilin sentence in quotation marks but secondary summaries use slightly different wording. Worth checking against the original PDF.
5. **Bibliography metadata errors.** Line 520 lists Greenaway-McGrevy & Phillips in *Journal of Housing Economics* — actual journal is *Journal of Urban Economics*. (Pass 1, not Pass 2 territory, but flagging since it surfaced.)

### Prioritized fix list (highest-impact first)

**Hard errors — fix verbatim:**
1. **Line 442 (§5.2)**: Swap the 0.81 and 0.78 labels for Cuéllar 2019. Eviction rates dropped 0.81pp; filing rates dropped 0.78pp.
2. **Line 349 (§4.1)**: "18 months" → "20 months" (or "3 years" / "20 and 37 months") for Family Options Study follow-up.
3. **Line 87 (§1.1)**: "first time in a century" → "first time in decades" (matching cited source) OR add a citation that supports "century".

**Citation problems — repoint or supplement:**
4. **Line 101 (§1.1)**: Auckland rent claim needs a different citation (Greenaway-McGrevy 2023 Auckland-rent working paper, not the Phillips co-authored construction paper).
5. **Line 111 (§1.1)**: "over a dozen states" needs a 2024+ source; current Sightline 2021 cite predates most state passages.
6. **Line 139 (§1.2)**: Swiss sprinkler/height-limit claim needs a different citation (Pew 2025b doesn't mention Switzerland).
7. **Line 239 (§2.2)**: 250k demolition figure needs a national-aggregate source, not Collinson's Chicago-only paper.
8. **Line 233 (§2.2)**: HUD waiting-list citation needs a specific dataset/report, not the database root.
9. **Line 306 (§3.2)**: FHA 221(d)(4) "10–15k units" needs a citation and may be stale (FY24 was 17,434).
10. **Line 309 (§3.2)**: Add citation for $30B FHLB retained earnings (figure is correct: $30.6B per FHLB Combined Financial Report).

**Refinements:**
11. **Line 51 (Intro Table 1)**: Goldman row "~3 million" → "~3–4 million" to match Goldman's stated range.
12. **Line 54 (Intro Table 1)**: JCHS row attribution to McCue & Huang is technically a literature review of others' estimates; consider citing NAR directly or relabeling.
13. **Line 98 (§1.1)**: Race to the Top "around $6 billion in today's dollars" → "around $6.7 billion" (per ARRA's $4.35B in 2009 → 2026 dollars).

**Inconclusive — needs your access:**
14. **Line 36 (Intro)**: Cohn NYT 2026 paywalled. Verify "about half of voters under 30" and "more than every other expense item combined".
15. **Line 139 (§1.2)**: Verify "fire death rate 450% higher" by hovering on US/Switzerland 2023 values at https://ourworldindata.org/grapher/fire-death-rates.
16. **Line 404 (§5.1)**: Verify Kholodilin direct quote — exact wording "rent ceilings" vs "rent control".

### What did NOT need flagging

Areas where every numerical claim verified cleanly:
- §2.1 (Social Housing): all four figures match HOC and BART exactly.
- §3.1 (Housing Innovation): Goldman, ARRA, Tesla all check out.
- §4.2 (LIHTC): six figures all match Urban Institute, HUD LIHTC database, Fed Communities, Ingram & Jaffe.

These sections are essentially Pass-2-clean.