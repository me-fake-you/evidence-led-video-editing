# Scoped revisions and delivery

## Make the requested change explicit

Bind a change to a baseline revision/hash, selected objects, requested fields/range, timing mode and required invariants. Reject or reconcile stale baselines instead of overwriting newer work. A bounded proposal is not a working natural-language editor until it is connected to actual rendering and checked outputs.

For shortening a shot distinguish ripple, preserving total length and preserving downstream absolute times. Show the concrete replacement or retiming. Filling a removed portion with the same shot's handles may undo the requested shortening; source availability alone does not make it a valid solution. If no compatible supported picture exists, expose the conflict rather than silently freezing, repeating or slowing content.

Distinguish user-permitted edit range from technical recomputation range. A filter may require input handles or a wider recompute without permitting audible/visible changes outside the requested interval. Fit a fade inside the approved range where feasible; if the desired result requires broader observable changes, surface the scope change rather than claiming exact preservation.

Track transitions, audio tails, ducking, stabilization windows, captions and nested compositions. If the only available asset is a flattened mix, do not claim to lower music alone while leaving speech untouched. Seek stems/project media, explain the limitation, or propose an explicitly approved approximation.

## Rebuild and preserve

Store edits and outputs in new revisions. Published artifacts point to immutable hashes. Undo may create a new revision referencing prior state; do not erase the old result. Cache identity must reflect actual dependencies, not filenames: source ranges/hashes, processing, fonts, voice/alignment parents, time bases, renderer versions and relevant output settings.

Use exact time bases and a documented rounding policy; do not rely on floating milliseconds alone for frame/sample boundaries. Check VFR, codec delay and cross-boundary effects. Cached intermediate segments may avoid unnecessary work, but a final lossy encode can change decoded output outside edited ranges. Distinguish plan equality, decoded-content equality and binary equality; verify only the guarantee actually made.

Before rendering check space, dependencies and source availability. Finalize temporary outputs only after decode/duration checks. Atomic rename requires suitable same-filesystem semantics. Job identity should include immutable inputs/settings, and resume must verify checkpoints rather than trusting an existing filename. Avoid duplicate concurrent writers.

## Platform editions and data

Read the project's actual content contracts, audience and language preferences; do not impose a fixed national language or runtime on unrelated users. Share verified facts and suitable source masters. Change narration, structure, captions, framing and sound when needed for the audience; do not force all editions to differ when a shared sequence genuinely works.

Revalidate current platform specifications for the actual upload surface or official API. A developer API limit is not automatically the web uploader limit or an editorial recommendation. No private endpoint scraping, silent cloud uploads or paid services are implied by this skill.

Deliver the precise artifact version and review evidence. Upload, draft, processing, scheduled and public are distinct remote states. An existing remote ID or uncertain submission must be reconciled before retrying. Local schedules are not proof of platform scheduling. Existing account isolation and daily limits belong in project configuration, not a hardcoded public skill.

## Minimal records when useful

- Hook card: audience, mode, supporting sources, first frame, expected value, progression/payoff and review.
- Narration take: sentence ID, text revision, evidence, voice asset, measured duration, pronunciation and listening status.
- Change proposal: baseline, intended effect, allowed objects/observable range, recompute range, timing mode, invariants and dependencies.
- Rights record: exact asset, basis/source evidence, scope, attestation status, remaining uncertainty and intended-use decision.

These are semantic contracts, not implemented validators. Use the existing project's data model where possible; version schema changes and test required cross-field invariants before calling a format stable.
