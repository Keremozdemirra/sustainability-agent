# Double materiality assessment — Halberg Fügetechnik GmbH, FY2026

**Illustrative throughout.** The company is fictional and every score, figure and name below
is constructed to exercise the method. This is analysis for an accountable person to check,
not a compliance conclusion. Method, scales, panels and vintage block: see `brief.md`. Audit
trail: `scores.csv` (30 of 148 records reproduced).

Method version DMA-2026.1. Threshold hypothesis 3.0 minuted 2026-04-28, before scoring.
Scoring window 2026-05-11 to 2026-06-05. Legal texts retrieved from EUR-Lex 2026-08-20.

## Results by topic

Weighted medians. `IM` and `FM` are on the 1–5 scale. A topic is material where `IM ≥ T` or
`FM ≥ T`; the two are never combined.

| Topic | Driving sub-topic | IM | FM | FM horizon | Max IQR | Contested |
|---|---|---|---|---|---|---|
| E1 Climate change | GHG, own operations (actual) | **5.0** | **4.0** | medium | 1 | |
| E2 Pollution | Metals to water, plating line (actual) | **4.0** | **3.0** | medium | 2 | yes |
| E3 Water and marine resources | Process water discharge (actual) | 2.0 | 1.5 | long | 1 | |
| E4 Biodiversity and ecosystems | Upstream iron ore and steel land use (potential) | 2.5 | 1.0 | long | 1 | |
| E5 Resource use and circular economy | Steel scrap loop (actual positive) | 2.0 | 2.5 | medium | 2 | yes |
| S1 Own workforce | H&S, press and plating (actual) | **4.0** | **3.5** | medium | 1 | |
| S2 Value chain workers | Forced labour via intermediaries (potential) | **4.5** | 2.0 | medium | 2 | yes |
| S3 Affected communities | Night-shift noise, Solingen (potential) | 2.5 | 1.5 | short | 1 | |
| S4 Consumers and end-users | Rail fastener failure (potential) | **4.0** | **4.0** | long | 1 | |
| G1 Business conduct | Corruption via sales agents (potential) | **3.0** | **3.5** | medium | 1 | |
| ENT-1 Plating chemistry authorisation | Substitution of restricted chemistry | **3.0** | **4.0** | short | 1 | |

## Three calculations shown in full

**S2 — forced labour via labour intermediaries, tier 2 foundry (potential negative, human
rights).** Weighted medians scale 5, scope 3, irremediable character 4. `S = max(5,3,4) = 5`;
two components ≥ 4, so +1, capped at 5. `S = 5`. Likelihood 3, so `δ = 0.5`, and the human
rights cap of 0.5 does not bind. `IM = 4.5`. Financially: magnitude 3, likelihood 2, so
`FM = 3 − 1.0 = 2.0` in the medium term.

The topic is material on impact and immaterial on financial effect at the chosen threshold.
Averaging the two dimensions would give 3.25; multiplying severity by likelihood on the
impact side would give 3.0 and then 1.5 after weighting the financial leg in. Both routes
demote the most severe impact in the assessment to the middle of the list. Averaging the
three severity components would give `(5+3+4)/3 = 4.0` before likelihood and `3.5` after —
still material here, but only because scale was 5; the same arithmetic buries a narrow
irreversible impact.

**E2 — metals to water from the plating line (actual negative).** Scale 3, scope 2,
irremediable character 4. `S = max(3,2,4) = 4`; only one component ≥ 4, no uplift. Actual, so
`IM = 4.0`. Financially: magnitude 3 (effluent treatment capex, illustrative EUR 2.5m),
likelihood 4, `δ = 0`, `FM = 3.0` in the medium term. Material on both.

**E5 — steel scrap loop (actual positive).** Scale 2, scope 2, irremediable character `NA`.
`S = max(2,2) = 2`, actual, `IM = 2.0`. Record R-0128 shows this row was first scored with
irremediable character 1, which would have produced the same `S` here but does so by
accident; the correction and its reason are in the trail.

## Threshold sensitivity

The deliverable. `M` = material at that threshold on at least one dimension.

| Topic | Max score | T = 2.0 | T = 2.5 | T = 3.0 | T = 3.5 | T = 4.0 |
|---|---|---|---|---|---|---|
| E1 Climate change | 5.0 | M | M | M | M | M |
| S2 Value chain workers | 4.5 | M | M | M | M | M |
| E2 Pollution | 4.0 | M | M | M | M | M |
| S1 Own workforce | 4.0 | M | M | M | M | M |
| S4 Consumers and end-users | 4.0 | M | M | M | M | M |
| ENT-1 Plating chemistry | 4.0 | M | M | M | M | M |
| G1 Business conduct | 3.5 | M | M | M | M | — *(exits)* |
| E4 Biodiversity | 2.5 | M | M | — *(exits)* | — | — |
| E5 Circular economy | 2.5 | M | M | — *(exits)* | — | — |
| S3 Affected communities | 2.5 | M | M | — *(exits)* | — | — |
| E3 Water | 2.0 | M | — *(exits)* | — | — | — |
| **Topics material** | | **11** | **10** | **7** | **7** | **6** |

**Plateau.** The material set is identical across 3.0 to 3.5 — seven topics, no entries and
no exits. It is the only interval in the tested range where the set does not move.

**Chosen threshold: 3.0**, the lower edge of the plateau. Reason recorded: within a plateau
the set is invariant, so the lower edge is preferred because it is the more inclusive of two
equivalent answers and requires no argument about why a topic just above 3.0 was excluded.
This choice matches the hypothesis minuted before scoring; had it not, the change and its
reason would be recorded here.

**Boundary topics** (max score within 0.5 of 3.0):

| Topic | Max | Call | Reason |
|---|---|---|---|
| G1 Business conduct | 3.5 | in | Four of nine sales agents have no due diligence file (R-0118). Exits only at T = 4.0; closing the files is expected to lower the score next year, which is the point of including it. |
| E4 Biodiversity | 2.5 | out | Impact is real but entirely upstream of tier 2 and scored on sector literature, not on the actual mills. Excluded with the evidence gap named, and to be re-scored when mill-level data exists. |
| E5 Circular economy | 2.5 | out | Positive impact, small in scale and scope. Excluded on impact; the financial leg (2.5) is scrap price exposure, already covered in treasury reporting. |
| S3 Affected communities | 2.5 | out | Depends on a night-shift extension that has not been approved. If it is approved, likelihood moves to 5 and `IM` becomes 3.0 — a decision that changes the topic list. |

## Weighted versus unweighted

| Topic | Unweighted max | Weighted max | Effect at T = 3.0 |
|---|---|---|---|
| S2 Value chain workers | 2.5 | 4.5 | **Enters** under weighting |
| E5 Circular economy | 3.0 | 2.5 | **Leaves** under weighting |
| All others | unchanged | unchanged | none |

S2 is the finding. The simple median across all fourteen impact respondents gives scale 3 and
irremediable character 3, because the internal and business-relationship respondents outnumber
those with knowledge of the site (records R-0085 and R-0086 are internal scores with no
evidence cited). Weighting the labour rights NGO at 3 and internal opinion at 1 moves the
weighted median to scale 5 and irremediable character 4, and the topic crosses the threshold.
The severest impact in this assessment is material only because the weighting rule was written
down before the panel scored. That sentence belongs in the disclosure of the process.

E5 moves the other way for the same reason: internal enthusiasm about the scrap loop, no
external corroboration.

## Audit trail quality

| Measure | Value |
|---|---|
| Score records | 148 |
| Typed "judgement" (no evidence reference beyond the scorer's opinion) | 32 (22%) |
| Judgement share, S2 rows | 6 of 14 (43%) |
| Rows with IQR ≥ 2 (contested) | 3 topics: E2, E5, S2 |
| Revisions after first pass | 4, each with prior value and reason (R-0008, R-0036, R-0128, and one not extracted) |

The judgement concentration in S2 is the weakness an assurer will find first. The topic that
depends most on weighting is also the topic with the least evidence. Recommendation: a tier-2
audit at the Coimbatore foundry before the FY2026 disclosure, which would convert R-0084 from
judgement to measured and settle the contested scale score either way.

## Cross-checks

- **Enterprise risk register.** Top ten includes "Turkish foundry supply interruption", which
  maps to E1 physical risk and S2; both material. "Customer concentration" and "cyber" are
  not sustainability matters and are correctly absent here.
- **Prior year.** The 2024 voluntary exercise listed water as material. It is not material
  now. Reason recorded: 2024 ranked topics by a stakeholder importance survey, not by severity
  against a defined scale. The change is a change of method, not of circumstances, and must be
  disclosed as such.
- **Climate.** Material on both dimensions, so the detailed explanation ESRS requires where
  climate is concluded not to be material does not arise. Verify the current wording in Annex I.

## Open points before this is relied on

1. Scope under Directive (EU) 2026/470 to be confirmed by counsel against the consolidated
   text of Directive 2013/34/EU. Not determined here.
2. Which ESRS version binds FY2026 — the amending delegated act adopted 3 July 2026 was in
   scrutiny at the scoring date. If it applies, re-check the sustainability matters table and
   the paragraph references before any of them are quoted.
3. ENT-1 rests on a plating chemistry authorisation status that has not been independently
   confirmed (R-0139, R-0140). Confirm on the ECHA authorisation list before disclosure; if
   the status differs, the financial magnitude changes and ENT-1 may leave the material set.
4. Calibration decision C-03: the panel did not settle whether passenger safety is a human
   rights impact for the purposes of the likelihood cap. Applying the cap raises S4 `IM` from
   4.0 to 4.5 and changes nothing at any tested threshold, so the point was left open and
   recorded rather than decided.
