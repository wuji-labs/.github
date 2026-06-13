# Contributing to WUJI Labs Open Source

Thank you for considering a contribution. These repositories are part of the
**HuaXia Skills** family — ten gifts the Chinese stream of wisdom offers to the
world's open-source community.

## Ways to contribute

- **Report a bug** — open an issue with steps to reproduce.
- **Suggest an improvement** — open an issue describing the use case.
- **Improve a skill** — sharpen prompts, add worked examples, fix a translation.
- **Add a platform adapter** — port a skill to a new agent runtime.
- **Run the benchmark** — produce real evaluation data (we never pre-fill numbers).

## Ground rules

1. **Cite your sources.** Every classical reference must name the book and chapter.
   Do not invent quotations. This is a hard rule (research integrity).
2. **No "civilization X is superior" framing.** We begin with the lineage we know
   best and place it on a shared shelf; keep the language inclusive.
3. **Advisory skills carry disclaimers.** Health / legal / financial / divination
   content must keep its disclaimer intact.
4. **Keep versions in sync.** `package.json`, `.claude-plugin/plugin.json`, and the
   `SKILL.md` frontmatter must agree. Update `CHANGELOG.md` for any release.

## Pull request flow

1. Fork the repository and create a feature branch.
2. Make your change. Keep diffs focused.
3. Update `CHANGELOG.md` under an `## [Unreleased]` heading.
4. Open a pull request describing **what** changed and **why**.

## Local layout

```
SKILL.md              the skill itself (frontmatter + principles + navigation)
README.md / .zh-CN.md bilingual front door
reference/            the "ammunition" — structured source material
examples/             worked input -> output cases
benchmark/            evaluation design (scenarios + rubric)
platforms/            per-runtime entry points
```

By contributing you agree your work is licensed under this repository's MIT License.
