# Validation scope — 0.1.0

This is an experimental instruction package, not a tested end-to-end renderer.

## Release checks

The release process checks skill front matter and structure, reference links, an explicit public file allowlist, and accidental private-data patterns. Reasoning scenarios are evaluated separately from media production. Final results are recorded below before publication.

### Results, 2026-09-30

- Skill structure validator: passed.
- Four fresh-context, read-only reasoning cases: photo-led sensory film without narration; sparse contact sheets and an unsupported hunt claim; music-only revision of a flattened mix; bilingual platform adaptation with unverified travel facts.
- Reviewer responses respected the relevant evidence and capability boundaries; no substantive high/medium-priority workflow defect was identified in those four cases.
- This was **not a blinded evaluation**: the reviewer read the public scenario reference, which includes expected behaviors. It is a consistency check, not independent proof of robustness or a comparison against another Skill.
- No video was rendered, watched or heard during that reasoning check. Actual-media regression coverage remains incomplete.

For future blinded evaluation, give the evaluator only the task-specific workflow references and raw task inputs. Keep the expected-answer rubric with the assessor; do not route the evaluator through `behavior-checks.md`.

The routing and rubric were clarified after this review. The initial instruction-only release is explicitly experimental; production-readiness claims still require actual-media regression evidence.

## Practical provenance, not a benchmark

The workflow was refined while revising an actual 192-second documentary-style travel video: supported hooks, narration separated from editing notes, source intervals preserved, a bounded voice correction, and technical output checks. That private project is not distributed here, is not a reproducible public benchmark, and does not establish that every rule or toolchain works.

## Known limitations

- No renderer, media-analysis model, automatic rights clearance or publishing integration is bundled.
- Behavioral reasoning checks cannot establish picture quality, audible intelligibility, music fit, motion quality or audience retention.
- Technical decode, loudness or black-frame checks are not a substitute for watching and listening.
- No public controlled audience experiment has been run; no engagement uplift is claimed.
- Real photo-led and platform-adaptation end-to-end regression fixtures are still needed. The scenarios in `references/behavior-checks.md` are a specification, not a passed automated test suite.
- Capability and permission failures must be reported, not hidden by a successful-looking plan or manifest.
