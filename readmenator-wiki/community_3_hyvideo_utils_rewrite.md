# hyvideo/utils/rewrite

*Community 3 | 4 files | cohesion 0.75*

## Definition

This community groups 4 file(s) rooted at `hyvideo/utils/rewrite` with dominant language py (cohesion 0.75). Central symbols: `DeepSeekClient`, `NonStreamResponse`, `QwenClient`, `QwenVLClient`, `__init__`, `_deserialize`, `_encode_image_to_base64`, `i2v_rewrite`. Core file: `hyvideo/utils/rewrite/clients.py` (15 symbols). Documented purpose: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain .

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `hyvideo/utils/rewrite/clients.py` | py | infrastructure | 15 | yes |
| `hyvideo/utils/rewrite/i2v_prompt.py` | py | utility | 0 | yes |
| `hyvideo/utils/rewrite/rewrite_utils.py` | py | utility | 3 | yes |
| `hyvideo/utils/rewrite/t2v_prompt.py` | py | utility | 0 | yes |

## Key Symbols

- `NonStreamResponse` (class, `hyvideo/utils/rewrite/clients.py:29`) `class NonStreamResponse(object)`
- `__init__` (method, `hyvideo/utils/rewrite/clients.py:30`) `def __init__(self)`
- `_deserialize` (method, `hyvideo/utils/rewrite/clients.py:33`) `def _deserialize(self, obj)`
- `DeepSeekClient` (class, `hyvideo/utils/rewrite/clients.py:37`) `class DeepSeekClient(object)`
- `__init__` (method, `hyvideo/utils/rewrite/clients.py:38`) `def __init__(self, key_id, key_secret)`
- `run_single_recaption` (method, `hyvideo/utils/rewrite/clients.py:51`) `def run_single_recaption(self, system_prompt, input_prompt)`
- `QwenClient` (class, `hyvideo/utils/rewrite/clients.py:84`) `class QwenClient(object)`
- `__init__` (method, `hyvideo/utils/rewrite/clients.py:85`) `def __init__(self, base_url, model_name)`
- `qwen_api_call` (method, `hyvideo/utils/rewrite/clients.py:90`) `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens)` - Use Qwen Chat API to perform text rewriting, parse <think>...</think> sections for reasoning content
- `run_single_recaption` (method, `hyvideo/utils/rewrite/clients.py:128`) `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tok`
- `QwenVLClient` (class, `hyvideo/utils/rewrite/clients.py:133`) `class QwenVLClient(object)`
- `__init__` (method, `hyvideo/utils/rewrite/clients.py:135`) `def __init__(self, base_url, model_name)`
- `_encode_image_to_base64` (method, `hyvideo/utils/rewrite/clients.py:141`) `def _encode_image_to_base64(self, image_path, max_dimension)` - 参考 hyvideo/utils/rewrite/qwen_vllm.py 的实现：
- `qwen_api_call` (method, `hyvideo/utils/rewrite/clients.py:176`) `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens, img_` - Use Qwen3-VL to perform text rewriting.
- `run_single_recaption` (method, `hyvideo/utils/rewrite/clients.py:246`) `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tok`
- `t2v_rewrite` (function, `hyvideo/utils/rewrite/rewrite_utils.py:22`) `def t2v_rewrite(user_prompt, rewrite_client)`
- `i2v_rewrite` (function, `hyvideo/utils/rewrite/rewrite_utils.py:40`) `def i2v_rewrite(user_input, img_path, rewrite_client)` - Use a rewrite client to generate a rewritten prompt for image-to-video.
- `run_prompt_rewrite` (function, `hyvideo/utils/rewrite/rewrite_utils.py:63`) `def run_prompt_rewrite(user_prompt, img_path, task_type)`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 3
- Cross-boundary resolved imports (EXTRACTED): 1

## Connections

- [EXTRACTED] depends_on community 0 <-> 3 (strength 0.9): Extracted import edge crosses communities: hyvideo/pipelines/hunyuan_video_pipeline.py imports hyvideo/utils/rewrite/rewrite_utils.py.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/models/transformers/modules/ssta_attention.py reaches hyvideo/utils/rewrite/clients.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/models/transformers/modules/ssta_attention.py reaches hyvideo/utils/rewrite/i2v_prompt.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/models/transformers/modules/ssta_attention.py reaches hyvideo/utils/rewrite/t2v_prompt.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/utils/flash_attn_no_pad.py reaches hyvideo/utils/rewrite/clients.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/utils/flash_attn_no_pad.py reaches hyvideo/utils/rewrite/i2v_prompt.py in 5 hops.
- [INFERRED] shares_context community 1 <-> 3 (strength 0.5): Inferred shared context (language py) with no import path between community 1 (hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer) and community 3 (hyvideo/utils/rewrite).
- [INFERRED] shares_context community 3 <-> 4 (strength 0.5): Inferred shared context (language py) with no import path between community 3 (hyvideo/utils/rewrite) and community 4 (orphans).

## Risks

- [dataflow UNCHECKED_ALLOC] `hyvideo/utils/rewrite/clients.py:155` `_encode_image_to_base64` `image`: Result of allocator stored in `image` is never checked against NULL.

## Open Questions

- What would break if the most connected file in hyvideo/utils/rewrite changed?
- Should hyvideo/utils/rewrite be split, given cohesion 0.75?

## Sources

- `hyvideo/utils/rewrite/clients.py`
- `hyvideo/utils/rewrite/i2v_prompt.py`
- `hyvideo/utils/rewrite/rewrite_utils.py`
- `hyvideo/utils/rewrite/t2v_prompt.py`
