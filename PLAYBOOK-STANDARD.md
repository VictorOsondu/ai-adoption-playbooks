# Playbook Standard v1

The house standard every playbook in the AI Adoption Playbooks series conforms to. These are not awesome-lists, so we set our own standard — and holding to it is what makes separate repos read as one deliberate series rather than scattered side projects.

## Repository structure

```
<repo>/
  README.md            # signature anatomy (below), including a Table of Contents
  framework/           # ICE Method + six-stage model, cut for this audience. Authored, and it leads.
  assessment/          # readiness / stage-locator — link to the toolkit or an audience-cut version
  templates/           # policy / acknowledgement / request forms, audience-adapted (light, free)
  rollout/             # the adoption plan — a 2-week rollout, or a session-based curriculum
  resources/           # CURATED external links — sits BELOW authored content, never leads
  examples/            # a worked example or case study — the field-tested proof
  CHANGELOG.md         # semver, per repo
  CONTRIBUTING.md      # per-repo inclusion rules
  CODE_OF_CONDUCT.md
  LICENSE              # CC BY 4.0 on content; MIT on any code
```

**Lean launch, never thin.** A repo may ship with only the README, `framework/`, an assessment link, and the root files — the rest filling in over later commits. What it must *never* do is ship empty or placeholder sections. If a section isn't ready, it's named on a roadmap, not stubbed as a hollow folder.

## Signature README anatomy

The same order in every repo. This is the series fingerprint:

1. **Positioning line + badges** (last-updated, provenance, licence). Provenance is honest: `practitioner-built` where the material is built from real work, `field-tested` only where a named, real rollout backs it. Never the official Awesome badge — these aren't awesome-lists.
2. **Table of Contents** — anchor links to every major section.
3. **Who this is for.**
4. **The six stages** — the self-locator callout.
5. **Start here** — the assessment link.
6. **Field-tested note** — where this was actually delivered. The single biggest differentiator; must be truthful.
7. **Free vs done-with-you** — the funnel line to the paid service.
8. **A pull-quote** from the AI Tutorium quote set.
9. **A link back to this index** — "part of the AI Adoption Playbooks series".

## Curation standard (for `resources/` sections only)

Adapted from the Awesome-list blueprint. It governs the curated components, never the authored prose.

- Item format, strict: `- [Name](url) — one objective sentence.`
- Sorted alphabetically within each category.
- Uniform bullet character; every description ends with a full stop.
- Objective, factual language — no "amazing", no subjective praise.
- Seed with a vetted set; never ship an empty resources section.
- Curation means saying no more than yes. Signal-to-noise is the whole value.

## Source Adaptation Standard

External playbooks and organisational case studies can strengthen the series, but they do not replace authored judgement.

- Record any source-derived pattern in the affected repo's `sources.md`.
- Prefer primary sources, official guidance, and first-party practitioner accounts; state what kind of evidence each source provides.
- Treat a company's public playbook as evidence of its reported practice, not independent proof that the practice works everywhere.
- Adapt the operating idea to the audience, risk context, house terminology, and existing canonical tools instead of copying a foreign framework wholesale.
- Preserve the distinction between `practitioner-built`, `sourced`, and `field-tested`.
- Credit copied or closely adapted CC BY material, link the licence and source, and say that changes were made.
- Do not imply that a source organisation endorses this series.
- Reject source ideas that create coercion, surveillance, false assurance, terminology collisions, or conflict with the identity-led model and governance boundaries.

## Community standard

- **Root hygiene files** in every repo: README, CONTRIBUTING, CODE_OF_CONDUCT, CHANGELOG, LICENSE.
- **CONTRIBUTING differs by repo:** playbooks invite corrections, case studies, and translations; reference repos invite entries judged against a published bar; `resources/` sections invite vetted links in the strict format above.
- **PR discipline:** reviewed as promptly as a one-person team reasonably can — an aspiration, not a public SLA. Rejections are polite and give a clear reason.

## Content validation standard

Every repository uses:

- `main` as the default branch;
- a checked-in `.markdownlint-cli2.jsonc` profile;
- a pull-request workflow that runs a pinned Markdown linter on Node 22;
- an offline link check for relative files and document paths; and
- an external link check once the repository is public, with rate-limit and
  bot-blocking responses handled explicitly rather than silently ignored.

The shared Markdown profile catches structural and whitespace defects while
allowing the series' established prose-line, compact-table, and emphasised-label
styles. A raw default-rule count isn't used as a launch-quality metric.

## Licence

Content under CC BY 4.0 (attribution funnels back). Any code under MIT.
