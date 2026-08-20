# Brief and method — Halberg Fügetechnik GmbH

**Every figure, name and score in this example is illustrative.** The company is fictional.
The scores are constructed to exercise the method, not drawn from a real assessment. The
legal identifiers are real and were checked on the date stated; nothing else here is.

This is the `method.md` artefact for one run of the skill, plus the brief it was run against.

## The company

Halberg Fügetechnik GmbH — cold-formed fasteners and welded assemblies for automotive and
rail. Headquarters and main works in Solingen; welded assembly plant in Zwickau; machining
plant in Mielec, Poland.

| Item | Value | Source |
|---|---|---|
| Turnover FY2025 | EUR 312m *[illustrative]* | *[replace with: audited FY2025 accounts]* |
| Employees | 1,180 own, ~140 agency *[illustrative]* | *[replace with: HR headcount 31.12.2025]* |
| Electricity | 38 GWh/yr *[illustrative]* | *[replace with: energy accounts]* |
| Revenue split | ~70% automotive, ~30% rail *[illustrative]* | *[replace with: sales ledger]* |

Solingen runs a zinc-nickel electroplating line and a degreasing plant. Castings come from
two foundries in Türkiye and one in India; steel wire rod from EU mills. Rail products
include safety-critical fastening for track and bogie assemblies.

## The request

From the CFO: the group falls in scope for the first time and the auditor has asked for the
materiality assessment before the interim review. The 2024 exercise was a workshop with a
bubble chart and no underlying scores. It cannot be re-used.

## Vintage block

| Field | Value |
|---|---|
| Entity | Halberg Fügetechnik GmbH and subsidiaries, consolidated |
| Value chain boundary | Upstream to tier 2 (foundries and their labour intermediaries); downstream to first customer, plus end-use for rail products |
| Reporting period | FY2026 |
| ESRS version applied | Delegated Regulation (EU) 2023/2772, Annex I, as in force at the scoring date |
| Legal texts retrieved | 2022/2464, 2025/794, 2026/470, 2023/2772 — EUR-Lex, 20 August 2026 |
| Open point | Amending delegated act adopted 3 July 2026 was in scrutiny at the scoring date. Scope under Directive (EU) 2026/470 to be confirmed with counsel against the consolidated text of Directive 2013/34/EU before the assessment is relied on. |
| Method version | DMA-2026.1 |
| Threshold hypothesis | 3.0 on both dimensions, minuted by the sustainability steering committee on 2026-04-28, before any scoring |

## Topic list and provenance

Twenty-six sub-topics across ten ESRS topics, taken from the table of sustainability matters
in ESRS 1's application requirements, plus one entity-specific matter:

- **ENT-1 — plating chemistry authorisation.** The Solingen line depends on a plating
  chemistry subject to EU chemicals authorisation. Added because the ESRS table has no
  sub-topic for a single-process regulatory dependency. *Verify the current authorisation
  status on the ECHA authorisation list before this row is used; it is not stated here.*

Sub-topics dropped before scoring, with reason recorded: E3 marine resources (no marine
interface), S4 sub-topics other than product safety (no consumer-facing sales).

## Scale ladders

Anchored to described consequences. Agreed 2026-04-28; magnitude bands set by the CFO.

| Level | Scale (harm) | Scope (spread) | Irremediable character | Likelihood | Magnitude *[illustrative bands]* |
|---|---|---|---|---|---|
| 1 | No discernible harm | One individual or point source | Remediable in days, low cost | Remote; unknown in the sector | < EUR 0.5m |
| 2 | Reversible discomfort or minor disturbance | One work team or a site's immediate surroundings | Remediable within the reporting period | Unlikely; known in sector, not here | EUR 0.5–2m |
| 3 | Harm requiring intervention; lost-time injury; measurable local degradation | A site's whole workforce or the adjacent community | Remediable in 1–5 years, or compensable | Possible; occurred at a comparable undertaking within 5 years | EUR 2–8m |
| 4 | Serious harm; permanent impairment; degradation persisting beyond a decade | Several sites, or a supplier's whole workforce; a river reach or airshed | Remediable only over decades, or compensable but not restorable | Likely; occurred here or at a named supplier within 5 years | EUR 8–25m |
| 5 | Loss of life; deprivation of liberty or fundamental rights; irreversible loss | Dispersed and global; whole populations | Irreversible; no remedy restores the prior state | Near-certain; occurring now or expected this period | > EUR 25m, or threatens a business line or access to finance |

**Calibration decision C-01.** Two reference impacts were scored by the whole panel first: a
lost-time hand injury on the press line, and the plating line's metal load to the municipal
sewer. Round one spread was two points on the second reference (procurement scored 2,
environment scored 4), so the level-4 wording for irremediable character was rewritten to
name persistence in sediment explicitly. Round two spread was one point on both.

**Calibration decision C-02.** For diffuse global impacts, *scope* is scored as the extent of
the harm attributable to this undertaking's own activity, not the extent of the phenomenon.
Without this rule every greenhouse gas row scores 5 on scope and the dimension carries no
information. Recorded with its reason because it materially raises climate's dependence on
scale and irremediable character instead.

## Panels and weights

| Panel | Respondents *[illustrative]* | Class | Weight |
|---|---|---|---|
| Impact | 3 works council members, 2 union officials | Affected rights-holders / representatives | 3 |
| Impact | 1 labour rights NGO covering the Coimbatore foundry cluster | Representative of affected workers | 3 |
| Impact | 1 Solingen neighbourhood association officer | Affected community | 3 |
| Impact | 2 environmental NGO analysts with published work on plating effluent | Expert body with documented evidence | 2 |
| Impact | 2 tier-1 customer sustainability leads | Business relationship, observed | 2 |
| Impact | 3 internal (HSE, operations, procurement) | Internal opinion | 1 |
| Financial | 2 relationship banks, 1 family-office shareholder | Providers of capital | 3 |
| Financial | CFO, treasurer, head of risk | Documented model basis | 3 |
| Financial | 2 commercial directors | Other | 1 |

Panel scores are aggregated by weighted median with the interquartile range recorded. The
impact weights do not apply to the financial panel and vice versa: the works council is not
an authority on the cost of a permit variation, and the bank is not an authority on heat
stress in a foundry.

## Aggregation rules as applied

- `S = max(scale, scope, irremediability)`, +1 capped at 5 where two or more components ≥ 4.
- Actual impacts: `IM = S`. Potential: `IM = S − δ(L)`, `δ` = 0 / 0 / 0.5 / 1.0 / 1.5 for
  L5…L1. Human rights rows: `δ` capped at 0.5.
- `FM = M − δ(L)` per horizon; `FM = max` across horizons, driving horizon recorded.
- Topic roll-up by maximum over sub-topics. Material if `IM ≥ T` **or** `FM ≥ T`.
- Positive impacts: irremediable character recorded `NA`, `S = max(scale, scope)`.

Scoring window 2026-05-11 to 2026-06-05. 148 score records. Reviewer: head of internal audit.
