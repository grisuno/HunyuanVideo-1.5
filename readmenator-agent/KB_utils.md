# Subsystem: utils

## hyvideo/utils/communications.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `broadcast` (function, line 24) `def broadcast(input_, group)`
  - `_all_to_all_4D` (function, line 29) `def _all_to_all_4D(input, scatter_idx, gather_idx, group)`
  - `SeqAllToAll4D` (class, line 147) `class SeqAllToAll4D(Function)`
  - `all_to_all_4D` (method, line 174) `def all_to_all_4D(input_, group, scatter_dim, gather_dim)`
  - `_all_to_all` (method, line 180) `def _all_to_all(input_, world_size, group, scatter_dim, gather_dim)`
  - `_AllToAll` (class, line 195) `class _AllToAll(Function)`
  - `all_to_all` (method, line 233) `def all_to_all(input_, group, scatter_dim, gather_dim)`
  - `_Reduce_Scatter` (class, line 239) `class _Reduce_Scatter(Function)`
  - `_AllGather` (class, line 255) `class _AllGather(Function)`
  - `all_gather` (method, line 304) `def all_gather(input_, dim, group)`
  - `forward` (method, line 149) `def forward(ctx, group, input, scatter_idx, gather_idx)`
  - `backward` (method, line 163) `def backward(ctx)`
  - `forward` (method, line 206) `def forward(ctx, input_, process_group, scatter_dim, gather_dim)`
  - `backward` (method, line 217) `def backward(ctx, grad_output)`
  - `forward` (method, line 242) `def forward(ctx, op, group, tensor)`
  - `backward` (method, line 251) `def backward(ctx, grad_output)`
  - `forward` (method, line 264) `def forward(ctx, input_, dim, group)`
  - `backward` (method, line 283) `def backward(ctx, grad_output)`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

## hyvideo/utils/data_utils.py
- Layer: data_access
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `resize_and_center_crop` (function, line 20) `def resize_and_center_crop(image, target_width, target_height)`
  - `get_closest_ratio` (function, line 38) `def get_closest_ratio(height, width, ratios, buckets)`
  - `generate_crop_size_list` (function, line 61) `def generate_crop_size_list(base_size, patch_size, max_ratio)`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/utils/flash_attn_no_pad.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `flash_attn_no_pad` (function, line 20) `def flash_attn_no_pad(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`
  - `flash_attn_no_pad_v3` (function, line 52) `def flash_attn_no_pad_v3(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`
- Imported by: `hyvideo/models/transformers/modules/attention.py`

## hyvideo/utils/infer_utils.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `torch_compile_wrapper` (function, line 19) `def torch_compile_wrapper()`
  - `decorator` (function, line 20) `def decorator(func)`
  - `wrapper` (function, line 21) `def wrapper(self)`

## hyvideo/utils/multitask_utils.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `numpy_to_pil` (function, line 23) `def numpy_to_pil(images)`
  - `merge_tensor_by_mask` (function, line 45) `def merge_tensor_by_mask(tensor_1, tensor_2, mask, dim)`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
