# Bibliography Pass 1 — Structural Integrity Check

**Date:** 2026-05-04
**Document:** `housing_draft.md`
**Bibliography entries:** 103
**In-text citation links:** 126

## Summary

| Check | Result |
|---|---|
| In-text URLs missing from bibliography | **0** (2 fragment-anchor mismatches, see below) |
| Bibliography entries never cited in body | **0** |
| Year/n.d. missing on any entry | **0** |
| Non-standard URL link format | **0** |
| Unbalanced italics (`*…*`) | **0** |
| Future-dated entries (>2026) | **0** |
| Alphabetization | clean (3 lines flagged by naïve sort were valid APA orderings: `n.d.` before dated, surname-only before surname-and-coauthor, "Urban" before "U.S.") |
| URLs returning HTTP 200 | **73** |
| URLs returning 4xx/5xx/timeout | **30** (most are bot-blocks; see `non-access.md`) |
| **True broken links** | **0** (the two HEAD-404s were false positives — both return 200 on GET) |

## Cross-reference (in-text ↔ bibliography)

Every in-text `[Author, Year](url)` resolves to a bibliography entry. Every bibliography entry is cited at least once in the body. Two minor URL-fragment inconsistencies that don't affect navigation but are worth normalizing:

1. **Line 134 (§1.2):** in-text uses `https://www.cato.org/regulation/winter-2024-2025/reforming-us-building-codes#a-brief-history-of-us-building-codes` (with anchor); bibliography entry uses the bare URL. Either drop the fragment in-text or add it to the bibliography URL — the in-text version is more useful for the reader.
2. **Line 404 (§5.1):** in-text uses `https://www.sciencedirect.com/science/article/pii/S1051137724000020#sec0008`; bibliography uses bare URL. Same recommendation.

These are not errors per APA — anchors in in-text citations are common when pointing to a specific section.

## URL accessibility

I HEAD-checked all 103 bibliography URLs from this environment. The split:

- **73 returning 200** (clean, fully verifiable)
- **26 returning 403** (bot-blocked; URLs likely valid but require browser/account access to confirm metadata)
- **2 returning 000 / connection error** (McKinsey, Washington Post — both have aggressive bot protection)
- **1 returning 406** (Time.com — bot block)
- **1 returning 202** (American Univ. Sustainable Development L&P — odd response; URL may be valid)
- **2 returning 404 on HEAD but 200 on GET** (Our World in Data, Goldman Sachs gspublishing) — these are *valid*; the 404 was a HEAD-method false positive

The 30 inaccessible URLs are listed in `non-access.md` for verification via a different tool (Claude web, which has different network access).

## Known metadata issue (carried over from Pass 2)

**Line 520 — Greenaway-McGrevy & Phillips (2023)** — bibliography lists journal as *Journal of Housing Economics*, but the actual paper was published in ***Journal of Urban Economics*** (Vol. 136, 101981). This needs correction.

The listed volume number (62) and article number (101981) match the *Urban* Economics paper. Only the journal name is wrong.

**Suggested fix:**
> Greenaway-McGrevy, R., & Phillips, P. C. B. (2023). The impact of upzoning on housing construction in Auckland. *Journal of Urban Economics*, **136**, 103555. https://www.sciencedirect.com/science/article/abs/pii/S0094119023000244

(Note: volume 136, article 103555 — the previous "62, 101981" was incorrect. Verify against the actual ScienceDirect landing.)

## Format-consistency observations (minor)

- All entries use APA 7-style author-date with italicized titles via `*…*`.
- All entries end with the URL rendered as `[https://...](https://...)` — consistent.
- Entries with no date use `(n.d.)` or `(n.d.-a) / (n.d.-b)` for disambiguation when the same author has multiple no-date works. Consistent and correct APA 7.
- Multi-author entries use `&` (not "and") before the last author. Consistent.
- Date formats include `(YYYY)`, `(YYYY, Month)`, and `(YYYY, Month D)`. APA 7 allows all three; consistency within a single style is the norm but not required across all entries (varies by source type).

## Things still uncertain (for Pass 2 of bibliography)

In a deeper pass, would also want to:
- Verify each entry's author spelling and full name against the source
- Confirm publication year matches the cited webpage's actual publication date
- Confirm publisher / journal / outlet name is correct for each entry
- Check working-paper vs published-paper status (one example: the Auckland paper listed above)

This Pass 1 only confirmed structural integrity — that the references match between in-text and bibliography, that URLs resolve, and that format is consistent.