# sustainability-agent

Agents and skills for sustainability consulting, where the regulation moves faster than the advice.

Sustainability advice has a specific hazard: the rules change, the
figures get restated, and a deliverable written six months ago can be confidently
wrong in a way that is hard to spot. A carbon factor without a vintage, a
threshold from a superseded implementing act, a framework requirement that was
dropped in the final text. Each one looks exactly like a correct answer.

This repository holds the agents and skills for doing the work with that hazard
in view. Every regulatory input carries its source and its date, every claim
about a requirement is checked against the current text rather than remembered,
and the deliverables are built so a later reader can tell which parts have aged.

The calculation engines live in
[esg-toolkit](https://github.com/Keremozdemirra/esg-toolkit), a separate
repository and not part of this one; its CBAM embedded-emissions calculator,
formerly the archived `cbam-calc`, is now `projects/004-embedded-emissions` there. This repository is the advisory layer.

## What this is not

It is not legal or compliance advice. It produces analysis for
someone accountable to check.

It does not track regulatory releases automatically, and nothing here should be
trusted to be current without checking. That is stated in every deliverable it
produces, not just here.

The emissions mathematics lives in [esg-toolkit](https://github.com/Keremozdemirra/esg-toolkit).

## How to use this

These are skills for Claude. There is nothing to
build and nothing to import: you describe the work and the matching skill
fires on its own.

**In Claude Code**, clone the repository and link its skills into the
folders Claude Code reads (`~/.claude/skills/`):

```bash
git clone https://github.com/Keremozdemirra/sustainability-agent ~/agent-packs/sustainability-agent
cd ~/agent-packs/sustainability-agent
mkdir -p ~/.claude/skills
for s in skills/*; do ln -sfn "$PWD/$s" ~/.claude/skills/; done
```

The links point back into the clone, so `git pull` there brings in whatever
ships next. To copy the files instead of linking them, replace the
line starting with `for` with:

```bash
cp -R skills/* ~/.claude/skills/
```

Skills placed there are available in every session and every folder; start a
new session after installing.

Then simply ask. Each skill's `description` frontmatter is written to match how
the request actually gets phrased, in English or Turkish, so you do not name the
skill and generally should not have to think about which one applies.

**If nothing fires**, that is a defect in the skill rather than in how you
asked. The description was written for the wrong phrasing. Say what you asked
and what you expected, and it gets fixed. That feedback is more valuable than
working around it.

**What is actually built** is listed under Contents below and in the Done
section of [BACKLOG.md](BACKLOG.md). Everything under Queue is planned and does
not exist yet.

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

`agents/` is empty so far.

## Roadmap

See [BACKLOG.md](BACKLOG.md). The first unchecked item is the one being built.

## Contents

| Skill | What it does |
| --- | --- |
| [double-materiality-assessment](skills/double-materiality-assessment) | Run the assessment as data: scored, weighted, threshold-tested and auditable. |

Everything still under Queue in [BACKLOG.md](BACKLOG.md) does not exist
yet.
## Licence

MIT. See [LICENSE](LICENSE).
