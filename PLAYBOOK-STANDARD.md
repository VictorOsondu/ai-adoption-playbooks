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

## Community standard

- **Root hygiene files** in every repo: README, CONTRIBUTING, CODE_OF_CONDUCT, CHANGELOG, LICENSE.
- **CONTRIBUTING differs by repo:** playbooks invite corrections, case studies, and translations; reference repos invite entries judged against a published bar; `resources/` sections invite vetted links in the strict format above.
- **PR discipline:** reviewed as promptly as a one-person team reasonably can — an aspiration, not a public SLA. Rejections are polite and give a clear reason.

## Licence

Content under CC BY 4.0 (attribution funnels back). Any code under MIT.
