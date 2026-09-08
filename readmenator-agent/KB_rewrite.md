# Subsystem: rewrite

## hyvideo/utils/rewrite/clients.py
- Layer: infrastructure
- Doc: -*- coding: utf-8 -*- Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use th
- Language: py
- Symbols:
  - `NonStreamResponse` (class, line 29) `class NonStreamResponse(object)`
  - `DeepSeekClient` (class, line 37) `class DeepSeekClient(object)`
  - `QwenClient` (class, line 84) `class QwenClient(object)`
  - `QwenVLClient` (class, line 133) `class QwenVLClient(object)`
  - `__init__` (method, line 30) `def __init__(self)`
  - `_deserialize` (method, line 33) `def _deserialize(self, obj)`
  - `__init__` (method, line 38) `def __init__(self, key_id, key_secret)`
  - `run_single_recaption` (method, line 51) `def run_single_recaption(self, system_prompt, input_prompt)`
  - `__init__` (method, line 85) `def __init__(self, base_url, model_name)`
  - `qwen_api_call` (method, line 90) `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens)`
  - `run_single_recaption` (method, line 128) `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens)`
  - `__init__` (method, line 135) `def __init__(self, base_url, model_name)`
  - `_encode_image_to_base64` (method, line 141) `def _encode_image_to_base64(self, image_path, max_dimension)`
  - `qwen_api_call` (method, line 176) `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens, img_path)`
  - `run_single_recaption` (method, line 246) `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens, img_path)`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

## hyvideo/utils/rewrite/i2v_prompt.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

## hyvideo/utils/rewrite/rewrite_utils.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `t2v_rewrite` (function, line 22) `def t2v_rewrite(user_prompt, rewrite_client)`
  - `i2v_rewrite` (function, line 40) `def i2v_rewrite(user_input, img_path, rewrite_client)`
  - `run_prompt_rewrite` (function, line 63) `def run_prompt_rewrite(user_prompt, img_path, task_type)`
- Depends on: `hyvideo/utils/rewrite/clients.py`, `hyvideo/utils/rewrite/i2v_prompt.py`, `hyvideo/utils/rewrite/t2v_prompt.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/utils/rewrite/t2v_prompt.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`
