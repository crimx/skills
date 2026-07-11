---
name: x-ray
description: Rewrite drafts to conform to an explicit or discovered editorial style through sentence, paragraph, and full-draft passes while preserving meaning. Use when the user explicitly invokes $x-ray with a draft and a named style skill, style guide, reference corpus, or publication or brand target.
---

# X-Ray

Make the draft belong to the target editorial system while preserving what it says.

## Resolve the Target Style

Inspect all available context before asking the user for a source. Treat an explicitly invoked style skill, named style guide, supplied reference, or specified publication or brand as the authoritative target.

When the source is not explicit, look for reliable evidence in this order:

1. Formal style guides and approved writing rules
2. Approved examples of the same content type, channel, audience, and purpose
3. Recent representative work from the same publication or brand
4. Relevant examples supplied earlier in the conversation

Prefer sources that are authoritative, current, representative, and relevant to the draft. Distinguish stable style from subject matter and one-off phrasing. Do not copy topic-specific language merely because it appears in the references.

If another explicitly invoked skill defines the writing style, follow its constraints as the style specification. Use other evidence only to clarify or supplement it. Do not silently blend materially conflicting sources. Resolve minor conflicts using the more specific, authoritative, relevant, and current source; ask one focused question when the choice would materially change the result.

If the target style still cannot be inferred reliably, ask for one representative reference or a concise style specification before editing.

## Build the Style Profile

Privately derive a compact profile of the target style. Separate:

- hard rules such as terminology, capitalization, punctuation, formatting, and prohibited language
- stable patterns such as voice, tone, diction, syntax, rhythm, pacing, structure, imagery, point of view, and information density
- contextual variations required by the draft's audience, channel, content type, purpose, and language

Use the profile as an editing standard, not as content to reproduce mechanically.

## X-Ray the Draft

Work through three passes:

1. **Sentence:** Ask whether each sentence belongs in the target editorial system. Rewrite genuine mismatches until they fit.
2. **Paragraph:** Check each paragraph for flow, pacing, transitions, emphasis, and tonal consistency. Reconcile sentence-level edits so they work together.
3. **Full draft:** Check the complete piece for a coherent voice, structure, momentum, narrative distance, terminology, imagery, and emotional register. Resolve drift and contradictions introduced by local edits.

Rewrite only where the change materially improves fit or clarity. Preserve useful variation in sentence length, rhythm, and emphasis. Do not flatten the author's intentional voice into a uniform template.

## Protect the Draft

Preserve the original meaning, facts, claims, reasoning, terminology, links, citations, quotations, code, and intentional nuance unless the user explicitly asks to change them. Do not introduce unsupported information. Flag a factual or semantic problem instead of hiding it with stylistic rewriting.

After the final pass, verify that:

- local rewrites still work at paragraph and full-draft level
- meaning and factual content remain intact
- all hard style rules are satisfied
- no new repetition, contradiction, or artificial uniformity was introduced

## Return the Result

Return the clean revised draft in the requested format. Briefly identify the style source used when it is not already obvious. Mention only unresolved passages whose intended meaning or target style remains genuinely uncertain. Provide detailed diagnostics or a change-by-change explanation only when requested.
