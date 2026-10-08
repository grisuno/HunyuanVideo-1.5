# Second Brain

*Last synthesized: 2026-10-07 | 38 files | 5 concept pages | offline, zero tokens*

> Raw sources -> readmenator wiki -> links (Karpathy LLM Wiki Pattern, deterministic).
> Start here, then open one community page. Prefer grep over full reads.

## Vault Overview

The codebase centres on `hunyuan_video_pipeline.py`, `hunyuanvideo_1_5_transformer.py`, `__init__.py`. Architecturally it is 4 layers, dominant business_logic (18 files) across 5 import-based communities. Recorded risk surface: 0 security findings and 1 dependency cycles.

Surprising tissue lives between hyvideo/pipelines, hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer, hyvideo/models/transformers/modules: communications: 4 extracted cross-community imports and 10 inferred bridges. Follow `connections.json` sorted by strength before refactoring.

Open work clusters around documentation (97% file coverage), 0 security findings, 0 taint paths, and 5 suggested exploration questions in `queries.md`.

## Stats

| Metric | Value |
|--------|-------|
| Files | 38 |
| Symbols | 409 |
| Resolved imports | 64 |
| Languages | py |
| Communities | 5 |
| Doc coverage | 97% (37/38 files) |
| Security findings | 0 |
| Estimated read cost | ~25396 tokens (chars/4, offline so $0) |

## Reading Order

1. Skim Stats and God Nodes below for blast radius.
2. Open the largest community page first, then follow Connections.
3. Use `queries.md` for the next question; log the answer there.

```
grep -rn '<keyword>' index.md community_*.md
readmenator query "<question>" --target readmenator_HunyuanVideo-1.5_hvlo4z4s
```

## Concept Wiki

- [hyvideo/pipelines (17 files, cohesion 0.74)](./community_0_hyvideo_pipelines.md)
- [hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer (8 files, cohesion 0.57)](./community_1_hyvideo_models_transformers_modules_hunyuanvideo_1_5_transformer.md)
- [hyvideo/models/transformers/modules: communications (7 files, cohesion 0.38)](./community_2_hyvideo_models_transformers_modules_communications.md)
- [hyvideo/utils/rewrite (4 files, cohesion 0.75)](./community_3_hyvideo_utils_rewrite.md)
- [orphans (2 files, cohesion 0.00)](./community_4_orphans.md)

## God Nodes

| File | Score |
|------|-------|
| `hyvideo/pipelines/hunyuan_video_pipeline.py` | 40.3 |
| `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py` | 30.2 |
| `hyvideo/commons/__init__.py` | 17.2 |
| `hyvideo/pipelines/hunyuan_video_sr_pipeline.py` | 17.0 |
| `hyvideo/models/transformers/modules/token_refiner.py` | 14.9 |

## Strongest Connections

- 1 -> 2: depends_on (strength 0.9, EXTRACTED)
- 1 -> 0: depends_on (strength 0.9, EXTRACTED)
- 2 -> 0: depends_on (strength 0.9, EXTRACTED)
- 0 -> 3: depends_on (strength 0.9, EXTRACTED)
- 2 -> 3: bridges (strength 0.5, INFERRED)
- 2 -> 3: bridges (strength 0.5, INFERRED)
- 2 -> 3: bridges (strength 0.5, INFERRED)
- 2 -> 3: bridges (strength 0.5, INFERRED)
- 2 -> 3: bridges (strength 0.5, INFERRED)
- 0 -> 4: shares_context (strength 0.5, INFERRED)

## Navigation Tips

- Obsidian Graph View works: every community page links back here.
- `connections.json` is machine-readable for GraphRAG pipelines.
- `REPORT.md` states what was extracted vs inferred and current limits.
- Regenerate offline: `readmenator . --rebuild` (no network, no tokens).
