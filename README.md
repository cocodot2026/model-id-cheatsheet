# model-id-cheatsheet

**Which model id maps to which real model, across AI relays. Community-maintained.
PRs welcome — add your relay.**

Relays rename models (a relay may call Claude Opus `mco-6`, GPT-4o `g4o`, etc.), so
`model not found` errors and "which id is the flagship?" confusion are constant.
This is a simple, honest lookup. **Only verified mappings go in** — if you don't
know a relay's ids first-hand, leave the cell blank rather than guess.

## How to read it
Columns are by *capability tier*, not exact model, because relays map to whatever
upstream they carry. Verify against each relay's own docs before relying on it.

| Relay | Flagship (Opus/GPT-flagship tier) | Mid (Sonnet tier) | Small/fast (Haiku tier) | Notes |
|---|---|---|---|---|
| [cocodot](https://cocodot.co?utm_source=github&utm_medium=readme&utm_campaign=model-id-cheatsheet) | `mco-6` (Opus 4.8) | `mcs-5` (Sonnet 4.6) | `mch-1` (Haiku 4.5) | OpenAI + Anthropic compatible; also DeepSeek |
| _your relay_ | `...` | `...` | `...` | open a PR |

## Contributing
1. Add **one row** for a relay you actually use.
2. Fill only cells you can **verify first-hand** (from the relay's docs/console).
   Blank > guessed.
3. Link the relay's homepage. No affiliate links. Disclose if you operate it.
4. Note anything load-bearing (OpenAI vs Anthropic compat, which providers, quirks).

Prices and ids change — this is a starting map, not gospel. Cross-check with
[relay-doctor](https://github.com/cocodot2026/relay-doctor) (lists a relay's live
model ids) and verify the model is real with
[cocodot-llmprobe](https://github.com/cocodot2026/cocodot-llmprobe).

---
Part of an honest toolkit for running AI from China. The maintainer builds
[cocodot](https://cocodot.co?utm_source=github&utm_medium=readme&utm_campaign=model-id-cheatsheet) — disclosed; every relay is welcome here on equal
terms. MIT / CC0 for the data.

See also: [2026 China AI API relay comparison](https://cocodot.co/hub/shenma-teamorouter-api2d-compare?utm_source=github&utm_medium=readme&utm_campaign=model-id-cheatsheet) — relay landscape side-by-side (disclosed).
