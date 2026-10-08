# orphans

*Community 4 | 2 files | cohesion 0.00*

## Definition

This community groups 2 file(s) rooted at `hyvideo/models` with dominant language py (cohesion 0.00). Central symbols: `decorator`, `torch_compile_wrapper`, `wrapper`. Core file: `hyvideo/utils/infer_utils.py` (3 symbols). Documented purpose: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain .

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `hyvideo/models/__init__.py` | py | business_logic | 0 | yes |
| `hyvideo/utils/infer_utils.py` | py | utility | 3 | yes |

## Key Symbols

- `torch_compile_wrapper` (function, `hyvideo/utils/infer_utils.py:19`) `def torch_compile_wrapper()`
- `decorator` (function, `hyvideo/utils/infer_utils.py:20`) `def decorator(func)`
- `wrapper` (function, `hyvideo/utils/infer_utils.py:21`) `def wrapper(self)`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 0
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- [INFERRED] shares_context community 0 <-> 4 (strength 0.5): Inferred shared context (language py) with no import path between community 0 (hyvideo/pipelines) and community 4 (orphans).
- [INFERRED] shares_context community 1 <-> 4 (strength 0.5): Inferred shared context (language py and layer business_logic) with no import path between community 1 (hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer) and community 4 (orphans).
- [INFERRED] shares_context community 2 <-> 4 (strength 0.5): Inferred shared context (language py) with no import path between community 2 (hyvideo/models/transformers/modules: communications) and community 4 (orphans).
- [INFERRED] shares_context community 3 <-> 4 (strength 0.5): Inferred shared context (language py) with no import path between community 3 (hyvideo/utils/rewrite) and community 4 (orphans).

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- What would break if the most connected file in orphans changed?
- Should orphans be split, given cohesion 0.00?

## Sources

- `hyvideo/models/__init__.py`
- `hyvideo/utils/infer_utils.py`
