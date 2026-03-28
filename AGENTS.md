# Documentation project instructions

## About this project

- This is the Mintlify documentation site for Offload / CasesAI.
- Pages are MDX files with YAML frontmatter.
- Site configuration lives in `docs.json`.
- Run `mint dev` to preview locally.
- Run `mint broken-links` before shipping larger edits.

## Terminology

- Prefer `Offload` when referring to the product.
- Use `case` for the async unit of work.
- Use `counterparty` for the person or team Offload contacts.
- Use `result schema` for the JSON Schema requested at case creation.
- Use `human in the loop` for pause-and-resume workflows that require customer input.

## Style preferences

- Write for developers integrating the API.
- Use active voice and second person.
- Keep examples concrete and operational.
- Be explicit about current limitations when the codebase has them.
- Prefer short sections, tables, and example payloads over marketing copy.

## Content boundaries

- Document public API behavior, webhook payloads, and integration patterns.
- Do not document speculative features as if they are already available.
- If a field exists in code but is not fully surfaced in the public API, call that out clearly.
