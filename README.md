# Skills

A collection of agent skills I use in real work.

Built around a few simple defaults: inspect context first, preserve intent, make invocation behavior deliberate, and keep skills small enough to compose.

## Install

```bash
npx skills add crimx/skills
```

## Skills

### Explicit invocation

These skills run only when called by name.

#### [`grill-me`](skills/grill-me/SKILL.md)

Pressure-test an idea before implementation. `grill-me` acts like a senior collaborator: it inspects the available context, exposes weak assumptions, focuses discussion on decisions that can materially change the outcome, and pushes back on risky or needlessly complicated directions.

It asks one high-leverage question at a time and ends with a concise record of decisions, assumptions, risks, rejected options, and the recommended next step. It deliberately stays out of implementation during the grill phase.

```text
/grill-me We should rewrite the app in Rust.
```

#### [`x-ray`](skills/x-ray/SKILL.md)

Align a draft with an existing editorial style while preserving its meaning. `x-ray` resolves the most relevant style source, derives a working style profile, and examines the writing at sentence, paragraph, and full-draft level.

The target can be a style guide, a reference corpus, a publication or brand, or another explicitly invoked style skill. This makes `x-ray` useful as a general editing engine that can be paired with project-specific voices.

```text
/x-ray this draft using the style in content/blog/.
```

```text
/x-ray this draft using /brand-style.
```

### Automatic invocation

These skills may activate automatically when a request matches their scope.

#### [`copywriting`](skills/copywriting/SKILL.md)

Keep copy direct, concrete, and grounded. `copywriting` avoids forced contrasts, meta-narration, assumed user journeys, vague positioning language, unsupported claims, and unnecessary repetition.

It applies automatically when drafting or revising copy.

## License

[MIT](LICENSE)
