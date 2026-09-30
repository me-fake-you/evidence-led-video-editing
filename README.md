# Evidence-led Video Editing

An experimental agent Skill for turning real photographs and footage into editable, source-grounded videos. 中文：一套先看真实素材、再讲故事、最后验证交付的视频剪辑工作流。

**Version 0.1.0 — workflow instructions, not a video editor or automatic publishing service.**

## What it helps with

- Hooks that the available footage can actually deliver on.
- Non-destructive photo correction before editing; restrained grading and stabilization for footage.
- Shot selection, narration, music, subtitles and platform-specific storytelling.
- Revisions that distinguish a requested change from its downstream timing and mix effects.
- Honest handoffs: a rendered file, technical checks, visual review, listening review and publication are separate states.

## 中文简介

不靠虚构经历、危险或攻略信息制造“爆款”。先核验素材能说明什么，再设计观众为什么愿意看、后文在哪里兑现。照片先逐张修图，保留原片；视频检查稳定性、主体裁切、颜色与声音。小红书、B站、短视频与英文平台可以采用不同叙事，但不用为了“差异化”强行换掉合适的镜头。

不保证流量，不把自评分当观众反馈，不把下载免费当公开视频授权。

## Use

1. Download or clone this repository.
2. Keep `SKILL.md` and `references/` together in a project-local skill directory supported by your agent.
3. Ask your agent to read `SKILL.md`, then give it a bounded source directory, audience, language, target duration and available editing tools.
4. Review the first real preview before authorizing public distribution.

Example prompt:

> Use evidence-led-video-editing. Make a 60-second travel film from the selected sources in this project. Preserve originals, inspect and correct each selected photograph first, propose an evidence-backed opening, and render a new preview without uploading it. Distinguish checks you performed from checks you could not perform.

The Skill does not install dependencies, provide renderers, bundle models, select paid services or grant account access. An agent still needs an actual editing/rendering toolchain. No specific model or vendor is required.

## Package

- `SKILL.md`: scoped workflow and reference routing.
- `references/source-and-story.md`: evidence, source identity and story construction.
- `references/hooks-and-retention.md`: hooks, payoff and responsible experimentation.
- `references/picture-and-sound.md`: picture treatment, narration, music and rights.
- `references/revisions-and-delivery.md`: revisions, verification and release handoff.
- `references/behavior-checks.md`: reasoning scenarios; not executable renderer tests.
- `VALIDATION.md`: actual validation scope and known limitations.

## Boundaries and provenance

This is an independently authored workflow informed by practical editing iterations and discussion of publicly described AI-editing ideas. It is **not affiliated with InVideo**, does not reproduce private code, models or internal architecture, and does not claim feature parity. Public product concepts are not proof of implementation here.

No private project media, raw conversations, account identifiers, credentials, publishing receipts, fonts or music recordings are included. Example scenarios are synthetic unless explicitly labelled otherwise. Rights to a user's source media remain with their respective owners.

## Contributing

Prefer a small reproducible failure case over a promise of better engagement. Describe the input, desired change, available evidence, observed failure and verification method. Do not submit private media, access tokens, account cookies or third-party recordings without permission.

## License

MIT for the original instructions in this repository. This license does not license third-party media, brand names or services.
