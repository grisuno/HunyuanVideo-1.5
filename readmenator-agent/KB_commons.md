# Subsystem: commons

## hyvideo/commons/__init__.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `_ntuple` (function, line 24) `def _ntuple(n)`
  - `is_flash2_available` (function, line 142) `def is_flash2_available()`
  - `is_flash3_available` (function, line 149) `def is_flash3_available()`
  - `is_flash_available` (function, line 156) `def is_flash_available()`
  - `is_sparse_attn_supported` (function, line 159) `def is_sparse_attn_supported()`
  - `is_sparse_attn_available` (function, line 162) `def is_sparse_attn_available()`
  - `is_angelslim_available` (function, line 171) `def is_angelslim_available()`
  - `maybe_fallback_attn_mode` (function, line 178) `def maybe_fallback_attn_mode(attn_mode)`
  - `auto_offload_model` (function, line 229) `def auto_offload_model(models, device, enabled)`
  - `get_gpu_memory` (function, line 243) `def get_gpu_memory(device)`
  - `get_rank` (function, line 254) `def get_rank()`
  - `parse` (function, line 26) `def parse(x)`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/commons/infer_state.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `InferState` (class, line 21) `class InferState`
  - `parse_range` (method, line 42) `def parse_range(value)`
  - `initialize_infer_state` (method, line 49) `def initialize_infer_state(args)`
  - `get_infer_state` (method, line 87) `def get_infer_state()`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/commons/parallel_states.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `ParallelDims` (class, line 24) `class ParallelDims`
  - `initialize_parallel_state` (method, line 81) `def initialize_parallel_state(sp, dp_replicate)`
  - `get_parallel_state` (method, line 89) `def get_parallel_state()`
  - `__post_init__` (method, line 29) `def __post_init__(self)`
  - `build_mesh` (method, line 37) `def build_mesh(self, device_type)`
  - `sp_enabled` (method, line 68) `def sp_enabled(self)`
  - `sp_mesh` (method, line 72) `def sp_mesh(self)`
  - `dp_enabled` (method, line 76) `def dp_enabled(self)`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`
