# sustainability-agent

Agents and skills for sustainability consulting, where the regulation moves faster than the advice.

Sustainability advice has a specific hazard: the rules change, the
figures get restated, and a deliverable written six months ago can be confidently
wrong in a way that is hard to spot. A carbon factor without a vintage, a
threshold from a superseded implementing act, a framework requirement that was
dropped in the final text — each one looks exactly like a correct answer.

This repository holds the agents and skills for doing the work with that hazard
in view. Every regulatory input carries its source and its date, every claim
about a requirement is checked against the current text rather than remembered,
and the deliverables are built so a later reader can tell which parts have aged.

The calculation engines live in `esg-toolkit` and `cbam-calc`. This repository is
the advisory layer.

## What this is not

It is not legal or compliance advice. It produces analysis for
someone accountable to check.

It does not track regulatory releases automatically, and nothing here should be
trusted to be current without checking. That is stated in every deliverable it
produces, not just here.

It does not implement emissions mathematics — `esg-toolkit` and `cbam-calc` do.

## Layout

```
agents/
  <name>.md           one specialist, its brief and its boundaries
skills/
  <name>/
    SKILL.md          the instruction, with triggering description frontmatter
    scripts/          only where deterministic code beats instruction
examples/
  <name>/             worked example on real input, with the output committed
```

## Roadmap

See [BACKLOG.md](BACKLOG.md). The first unchecked item is the one being built.

## Planned contents

Nothing here is built yet. This table is the intended shape, and the daily loop
fills it in one item at a time.

| # | Skill | What it does |
| --- | --- | --- |
| 001 | [double-materiality-assessment](skills/double-materiality-assessment) | Run the assessment as data rather than a workshop artefact: impact and financial scores per topic, stakeholder weighting, threshold sensitivity, and a trail of who scored what and when. |
| 002 | [csrd-readiness-gap](skills/csrd-readiness-gap) | Check what a company can currently report against what its disclosure obligation requires, and rank the gaps by how long each takes to close rather than by how large it is. |
| 003 | [decarbonisation-roadmap](skills/decarbonisation-roadmap) | Turn a target into a sequence of measures with cost, abatement and dependency, and say plainly which part of the target has no measure behind it yet. |
| 004 | [disclosure-review](skills/disclosure-review) | Read a published sustainability report the way a sceptical reader would: restated figures, dropped metrics, quietly moved baselines, claims with no method behind them. |
| 005 | [supplier-data-request](skills/supplier-data-request) | Design the data request that gets usable answers from suppliers who have never been asked before, and validate what comes back. |
| 006 | [greenwash-check](skills/greenwash-check) | Test a claim against what can actually be evidenced, using the tests a regulator applies rather than the ones a marketing team applies. |
| 007 | [factor-vintage-audit](skills/factor-vintage-audit) | Find every emission factor, threshold and rate in a deliverable and check each against its current published value, reporting what has been superseded. |
| 008 | [target-setting-brief](skills/target-setting-brief) | What a credible target commits an organisation to, what the standard actually requires, and what the common shortcuts cost in credibility. |
| 009 | [transition-risk-narrative](skills/transition-risk-narrative) | Write the financial narrative of transition risk in the language of the finance function rather than the sustainability team. |

## Licence

MIT. See [LICENSE](LICENSE).
