---
name: double-materiality-assessment
description: "Run a double materiality assessment as scored data rather than a workshop artefact — impact and financial scoring per sub-topic, stakeholder weighting, threshold sensitivity and an audit trail an assurance provider can follow. Use when the ask is \"çifte önemlilik analizi\", \"çifte materiality\", \"materiality yap\", \"önemlilik analizi yapalım\", \"CSRD önemlilik\", \"ESRS konu listesi çıkar\", \"önemlilik matrisi\", \"paydaş görüşleriyle önemlilik\", \"geçen yılki önemlilik analizini güncelle\", \"double materiality assessment\", \"DMA\", \"materiality matrix\", \"which ESRS topics are material\", \"impact and financial materiality\", \"where should the materiality threshold sit\", \"refresh last year's materiality assessment\", or when someone is deciding which sustainability topics a company must report on."
---

# Double Materiality Assessment

A double materiality assessment usually arrives as a picture: a two-axis chart of topic
bubbles, produced from a workshop and defended by the fact that a workshop happened. It cannot
be re-run, the threshold was drawn after the bubbles were placed, and nobody can say which
scores would have to change for a topic to move. An assurer asked to opine on that has nothing
to test.

This skill produces the same conclusion as data: one row per score, per topic, per scorer, with
its evidence reference; a stated aggregation rule; and a table showing how the material topic
set changes as the threshold moves. That sensitivity table is what distinguishes an assessment
from a workshop. A topic list stable across a wide band of thresholds is defensible in one
sentence; an unstable one is the finding, and better found now than during assurance.

## Regulatory basis and vintage

All identifiers below were checked against EUR-Lex on **20 August 2026**. Re-check and record
your own date: this area moved three times in eighteen months.

- **Directive (EU) 2022/2464** of 14 December 2022 (CSRD), OJ L 322, 16.12.2022 — amends
  Directive 2013/34/EU to require sustainability reporting under adopted standards, and
  introduces an assurance requirement on that reporting.
- **Directive (EU) 2025/794** of 14 April 2025 ("stop the clock") — postponed application dates
  for later reporting waves.
- **Directive (EU) 2026/470** of 24 February 2026 ("Omnibus I"), in force 18 March 2026 —
  amends Directives 2006/43/EC, 2013/34/EU, (EU) 2022/2464 and (EU) 2024/1760, and narrows the
  reporting population. **Do not state scope, employee or turnover thresholds from memory or
  from this file.** Read the scope articles in the consolidated text of Directive 2013/34/EU on
  EUR-Lex as it stands on the date of your work.
- **Commission Delegated Regulation (EU) 2023/2772** of 31 July 2023, OJ L, 2023/2772,
  22.12.2023 — the ESRS. **Annex I is ESRS 1 *General requirements*.**
- A **Commission Delegated Regulation amending (EU) 2023/2772** (the revised, simplified ESRS)
  was **adopted 3 July 2026** and was still in the Parliament/Council scrutiny period at the date
  checked, so it had no OJ number yet. It is reported to apply to financial years beginning on or
  after 1 January 2027 (early application permitted for 2026), and to cut datapoints, simplify
  the application requirements and permit a top-down materiality approach. **Establish which
  version binds your client before scoring**, and confirm whether it has since been published.

Paragraph references below are to **ESRS 1 as adopted in 2023/2772**: severity of negative
impacts as scale, scope and irremediable character (para. 45, elaborated at AR 10); positive
impacts by scale and scope, plus likelihood where potential (para. 46); severity taking
precedence over likelihood for potential negative human rights impacts (AR 11); time horizons
(para. 77); the table of sustainability matters by topic, sub-topic and sub-sub-topic (AR 16).
**The amending act renumbers and simplifies the application requirements**, so before citing
any paragraph in a deliverable, open the consolidated Annex I and confirm the number; if you
cannot, state the requirement in substance and say which version you read. Nothing here is
legal advice — it produces analysis for an accountable person to check.

## When to use / when not to

Use it for a first assessment, for an annual refresh where last year's list must be defended or
changed, when an assurer has challenged the topic list, or when two functions disagree about a
topic and the argument needs a number.

Do not use it to decide *what to disclose about* a material topic — that is the topical
standard's job — or to design stakeholder engagement, or where nobody owns the output.

## The method

1. **Write the vintage block first.** Entity, consolidation boundary, value chain boundary
   (which tiers upstream and downstream are in), reporting period, the ESRS version that applies,
   and the date each legal text was retrieved. Every later output carries it; without it the
   assessment cannot be re-used next year, because nobody will know what it was run against.

2. **Build the topic list from the standard, then extend it.** Take the topics, sub-topics and
   sub-sub-topics from the table of sustainability matters in ESRS 1's application requirements,
   then add entity-specific matters it does not cover — a process chemical, a single-site water
   dependency, a community. The list is a floor, not a ceiling; an assessment returning exactly
   the standard's list is evidence that the entity-specific step was skipped.

3. **Score at sub-topic level, not topic level.** "Own workforce" is not scorable; "health and
   safety of agency workers on the plating line" is. Split until each row carries one affected
   group, one value chain location and one mechanism; roll up later.

4. **Define the scales and calibrate before scoring anything.** Each of scale, scope,
   irremediable character, likelihood and magnitude gets a 1–5 ladder whose levels are anchored
   to described consequences, not to adjectives. Magnitude is anchored to a financial quantum
   agreed with finance and written down — a percentage of EBIT or an absolute band — because
   "high" means different things to a treasurer and an HSE manager. Then calibrate: have the panel
   score two reference impacts, one obviously severe and one marginal. If scorers differ by more
   than a point on those, the anchors are not usable yet. Fix them first.

5. **Score impact materiality per row.** Record impact type (actual or potential, negative or
   positive), value chain location, affected group, time horizon, then the components. Negative
   impacts take scale, scope and irremediable character. **Positive impacts take scale and scope
   only** — irremediable character does not apply and is recorded as not applicable. Recording
   it as 1 is the commonest silent spreadsheet error and suppresses positive impacts wholesale.

6. **Aggregate severity with a non-compensatory rule, and never by averaging.** Use `S =
   max(scale, scope, irremediability)`, uplifted by 1 (capped at 5) where two or more
   components are 4 or above. Averaging the three is wrong for a specific reason: it lets a low
   component cancel a high one, so an impact that is irreversible but narrow — a fatality, an
   aquifer, an extinction — averages to mid-scale and drops out of the material set, which is
   the opposite of what severity means. Any replacement must be monotone in each component,
   non-compensatory and reproducible from the recorded vector. Keep the vector: the aggregate
   alone is not auditable.

7. **Apply likelihood without letting it dominate severity.** Actual impacts have occurred, so
   `IM = S`. For potential impacts, `IM = S − δ(L)` with `δ`: L5 → 0, L4 → 0, L3 → 0.5, L2 → 1.0,
   L1 → 1.5. For potential negative **human rights** impacts, cap `δ` at 0.5, because severity
   takes precedence over likelihood there (ESRS 1 AR 11; same rule in the UN Guiding Principles).
   Multiplying severity by probability is the other common error: it drives a rare catastrophic
   impact below a routine minor one.

8. **Score financial materiality separately, per time horizon.** For each impact or dependency,
   identify the risk or opportunity it generates and score magnitude of the financial effect and
   likelihood, for short, medium and long term. `FM = M − δ(L)` using the same ladder, with no
   human rights floor. Take `FM = max` across horizons and **record which horizon drove it** — a
   topic material only in the long term is a different management problem. Every financial score
   must trace to a named impact or dependency; without a mechanism it is a forecast.

9. **Weight stakeholder input as evidence, not as votes.** The justification: affected people
   are the authority on the severity of impacts on them, and are not an authority on the financial
   effect on the undertaking. The two panels are therefore weighted differently.

   | Panel | Class | Weight | Why |
   |---|---|---|---|
   | Impact | Affected rights-holders or their credible representatives | 3 | Direct knowledge of scale, scope, remediability |
   | Impact | Civil society or expert bodies with documented evidence on the topic | 2 | Evidence, not experience |
   | Impact | Business relationships reporting impacts they observe | 2 | Observed, second-hand |
   | Impact | Internal functions with no evidence beyond opinion | 1 | Opinion |
   | Financial | Providers of capital; finance and risk functions with a documented basis | 3 | Own the decision the score is about |
   | Financial | Everyone else | 1 | |

   Aggregate a panel with the **weighted median**, not the weighted mean: it is robust to a
   single extreme respondent, keeps the result on the defined scale, and cannot be moved by
   adding respondents who all say the same thing. Record the interquartile range beside it and
   **flag any row with IQR ≥ 2 as contested** — those rows are where the threshold decision
   bites, and they are the first thing an assurer samples. Report weighted and unweighted
   results side by side and name every topic that moves between them. If weighting changes
   nothing, say so; that is a result.

10. **Roll up by maximum, and never combine the two dimensions.** A topic is material if any of
    its sub-topics is, and if `IM ≥ threshold` **or** `FM ≥ threshold`. Do not average, add or
    multiply IM and FM into one score. That single number is what the bubble chart encodes, and
    it is exactly the failure double materiality exists to prevent: a topic that is severely
    impact-material and financially immaterial is material, and averaging deletes it.

11. **Set the threshold before scoring, then test it.** ESRS gives no numeric threshold; the
    undertaking sets one and must be able to explain it. Minute a starting hypothesis — 3.0 on
    both dimensions is a reasonable default on a 1–5 scale — before the panel scores, so it
    cannot be fitted to a preferred answer. Then recompute the material set at 2.0, 2.5, 3.0, 3.5
    and 4.0 on each dimension and tabulate which topics enter and leave at each step. **Choose
    the threshold in the widest interval over which the material set does not change.** If no
    such plateau exists, the scoring does not discriminate and needs better evidence rather than
    a decision — report that. List every topic within 0.5 of the chosen threshold as a boundary
    topic with a written reason for inclusion or exclusion. Any threshold change after scoring is
    recorded with its reason and the previous value.

12. **Cross-check against what the company already says.** Compare the material set with the
    enterprise risk register, the prior year's list, board minutes, and any topic the entity
    publicly claims to manage. Every discrepancy is either an error here or an inconsistency in
    the company's own disclosures, and both need an answer. Treat climate separately: where it
    is concluded not to be material, ESRS requires a detailed explanation of that conclusion and
    has no equivalent requirement for other topical standards — verify the wording in Annex I.

13. **Record the audit trail as you go, not afterwards.** One row per score: record ID; topic /
    sub-topic and its ESRS reference; dimension; impact type; component; value; horizon; value
    chain location; affected group; evidence reference (document, page, date); evidence type
    (measured / modelled / third-party / interview / judgement); scorer name, role, panel class
    and weight; date scored; method version; and for any revision, the prior value, the reason and
    who approved it. **No score ships without an evidence reference.** Report the proportion of
    scores typed "judgement" as a headline quality figure: it says how much of the assessment is
    knowledge and how much is opinion.

## The hard parts

**Comparability across topics.** A "5" for greenhouse gas emissions must mean what a "5" for
forced labour means, or the ranking is arithmetic on incommensurable units. Calibration (step 4)
is what makes it defensible; it is also the step that gets cut when time is short. If it was cut,
name that as the first limitation.

**Control is not materiality.** Value chain impacts count where the undertaking is connected to
them, whether or not it can stop them. Lack of leverage changes what the company does about a
topic, not whether the topic is material. Panels containing operational managers drift on this,
because their instinct is to score what they can act on.

**The matrix is a communication device, not the record.** Produce it after the table exists, and
never let a bubble be moved by hand: a moved bubble is a changed score and belongs in the trail
with a reason.

**Refresh is not re-scoring.** Carry forward prior scores with their evidence and re-score only
rows where something changed — new evidence, new operations, a changed threshold, a row contested
last year — recording what was carried forward and why. Re-running from scratch destroys the
year-on-year comparison that makes movement visible.

**Bilingual panels.** Translate the anchor descriptions, never the scores, and keep one
authoritative scale document in one language. Turkish panels drift on "önemli", which carries
"important" and "material" at once; say in the instructions that the question is materiality
against a defined threshold, not importance.

**Assurance.** CSRD introduces an assurance requirement on sustainability reporting. Confirm the
level and applicable standard for the client's period and jurisdiction before promising what an
assurer will accept — the 2026 amendments touched this.

## Output format

Four artefacts, in this order. Each states at the top that it is analysis for an accountable
person to check, not a compliance conclusion.

- `method.md` — vintage block; topic list with the provenance of each entry; the five scale
  ladders with anchors; the calibration result; panel classes, weights and justification; the
  aggregation rules as formulas; the threshold hypothesis, its date and who minuted it.
- `scores.csv` — the audit trail, one row per score, every field from step 13. This is the
  record; everything else is derived from it and can be regenerated.
- `results.md` — per topic: IM, FM, driving sub-topic, driving horizon, IQR, contested flag,
  and the material / not material call on each dimension separately.
- `sensitivity.md` — the threshold table (one column per threshold, one row per topic, marking
  entry and exit); the plateau and the chosen threshold with its reason; boundary topics;
  weighted versus unweighted; the judgement-only proportion; and the step 12 cross-checks.

## Sources

- The legal instruments and their vintages are listed under *Regulatory basis and vintage*
  above, with the date each was retrieved from EUR-Lex.
- UN Guiding Principles on Business and Human Rights, HR/PUB/11/04 (2011), and the OECD Due
  Diligence Guidance for Responsible Business Conduct (2018) — severity as scale, scope and
  remediability; severity taking precedence over likelihood.
- EFRAG *IG 1: Materiality Assessment Implementation Guidance* (2024) — non-binding guidance,
  not law; useful for worked illustrations, not citable as a requirement.

The aggregation rule in step 6, the `δ` ladder in step 7, the weights and weighted-median rule
in step 9 and the plateau rule in step 11 are this repository's own conventions, stated so they
can be replaced. Any replacement must be written down before scoring and must survive the three
tests in step 6.
