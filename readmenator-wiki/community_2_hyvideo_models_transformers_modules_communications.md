# hyvideo/models/transformers/modules: communications

*Community 2 | 7 files | cohesion 0.38*

## Definition

This community groups 7 file(s) rooted at `hyvideo/models/transformers/modules` with dominant language py (cohesion 0.38). Central symbols: `SeqAllToAll4D`, `VisionEncoder`, `VisionEncoderModelOutput`, `_AllGather`, `_AllToAll`, `_Reduce_Scatter`, `__init__`, `__initialize_default_distributed_environment`. Core file: `hyvideo/utils/communications.py` (18 symbols). Documented purpose: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain .

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `hyvideo/__init__.py` | py | utility | 2 | yes |
| `hyvideo/commons/__init__.py` | py | utility | 12 | yes |
| `hyvideo/models/transformers/modules/attention.py` | py | business_logic | 6 | yes |
| `hyvideo/models/transformers/modules/ssta_attention.py` | py | business_logic | 11 | yes |
| `hyvideo/models/vision_encoder/__init__.py` | py | business_logic | 11 | yes |
| `hyvideo/utils/communications.py` | py | utility | 18 | yes |
| `hyvideo/utils/flash_attn_no_pad.py` | py | utility | 2 | yes |

## Key Symbols

- `find_free_port` (function, `hyvideo/__init__.py:25`) `def find_free_port()`
- `__initialize_default_distributed_environment` (function, `hyvideo/__init__.py:32`) `def __initialize_default_distributed_environment()`
- `_ntuple` (function, `hyvideo/commons/__init__.py:24`) `def _ntuple(n)` - Create a function that converts input to n-tuple.
- `parse` (function, `hyvideo/commons/__init__.py:26`) `def parse(x)`
- `is_flash2_available` (function, `hyvideo/commons/__init__.py:142`) `def is_flash2_available()`
- `is_flash3_available` (function, `hyvideo/commons/__init__.py:149`) `def is_flash3_available()`
- `is_flash_available` (function, `hyvideo/commons/__init__.py:156`) `def is_flash_available()`
- `is_sparse_attn_supported` (function, `hyvideo/commons/__init__.py:159`) `def is_sparse_attn_supported()`
- `is_sparse_attn_available` (function, `hyvideo/commons/__init__.py:162`) `def is_sparse_attn_available()`
- `is_angelslim_available` (function, `hyvideo/commons/__init__.py:171`) `def is_angelslim_available()`
- `maybe_fallback_attn_mode` (function, `hyvideo/commons/__init__.py:178`) `def maybe_fallback_attn_mode(attn_mode)` - Determine the final attention mode based on configuration and availability.
- `auto_offload_model` (function, `hyvideo/commons/__init__.py:229`) `def auto_offload_model(models, device, enabled)`
- `get_gpu_memory` (function, `hyvideo/commons/__init__.py:243`) `def get_gpu_memory(device)`
- `get_rank` (function, `hyvideo/commons/__init__.py:254`) `def get_rank()`
- `attention` (function, `hyvideo/models/transformers/modules/attention.py:50`) `def attention(q, k, v, drop_rate, attn_mask, causal, attn_mode)` - Compute attention using flash_attn_no_pad or torch scaled_dot_product_attention.
- `parallel_attention` (function, `hyvideo/models/transformers/modules/attention.py:112`) `def parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, att`
- `sequence_parallel_attention` (function, `hyvideo/models/transformers/modules/attention.py:120`) `def sequence_parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_`
- `shrink_head` (function, `hyvideo/models/transformers/modules/attention.py:145`) `def shrink_head(encoder_state, dim)`
- `score_mod` (function, `hyvideo/models/transformers/modules/attention.py:188`) `def score_mod(score, b, h, q_idx, kv_idx)`
- `get_image_tile` (function, `hyvideo/models/transformers/modules/attention.py:231`) `def get_image_tile(tile_size)`
- `tile` (function, `hyvideo/models/transformers/modules/ssta_attention.py:23`) `def tile(x, canvas_thw, tile_thw, sp_size)` - Rearrange tensor into tiles for block-based attention.
- `untile` (function, `hyvideo/models/transformers/modules/ssta_attention.py:53`) `def untile(x, canvas_thw, tile_thw, sp_size)` - Reverse the tiling operation to restore original tensor layout.
- `get_tile_t_h_w` (function, `hyvideo/models/transformers/modules/ssta_attention.py:82`) `def get_tile_t_h_w(tile_id, tile_thw_dim)` - Extract temporal, height, and width indices from a flattened tile ID.
- `importance_sampling` (function, `hyvideo/models/transformers/modules/ssta_attention.py:90`) `def importance_sampling(q, k, topk, threshold, lambda_, adaptive_pool)` - Select top-k blocks based on importance scores considering both similarity and redundancy.
- `similarity_sampling` (function, `hyvideo/models/transformers/modules/ssta_attention.py:126`) `def similarity_sampling(q, k, topk, threshold, block_num, adaptive_pool, tempera` - Select top-k blocks based on similarity scores between query and key averages.
- `create_moba_3d_mask` (function, `hyvideo/models/transformers/modules/ssta_attention.py:170`) `def create_moba_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block` - Create MOBA (Mixture of Block Attention) 3D mask for sparse attention.
- `get_block_avg_feat` (function, `hyvideo/models/transformers/modules/ssta_attention.py:216`) `def get_block_avg_feat(x, adaptive_pool, pooling_type)`
- `create_sta_3d_mask_optimize` (function, `hyvideo/models/transformers/modules/ssta_attention.py:323`) `def create_sta_3d_mask_optimize(canvas_thw, tile_thw, kernel_thw)` - Create optimized STA (Spatio-Temporal Attention) 3D mask using vectorized operations.
- `create_sta_3d_mask` (function, `hyvideo/models/transformers/modules/ssta_attention.py:374`) `def create_sta_3d_mask(canvas_thw, tile_thw, kernel_thw, text_block_num)` - Create STA (Spatio-Temporal Attention) 3D mask.
- `create_ssta_3d_mask` (function, `hyvideo/models/transformers/modules/ssta_attention.py:404`) `def create_ssta_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block` - Create SSTA (Sparse Spatio-Temporal Attention) 3D mask combining STA and MOBA masks.

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 6
- Cross-boundary resolved imports (EXTRACTED): 10

## Connections

- [EXTRACTED] depends_on community 1 <-> 2 (strength 0.9): Extracted import edge crosses communities: hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py imports hyvideo/commons/__init__.py.
- [EXTRACTED] depends_on community 2 <-> 0 (strength 0.9): Extracted import edge crosses communities: hyvideo/models/transformers/modules/attention.py imports hyvideo/commons/parallel_states.py.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/models/transformers/modules/ssta_attention.py reaches hyvideo/utils/rewrite/clients.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/models/transformers/modules/ssta_attention.py reaches hyvideo/utils/rewrite/i2v_prompt.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/models/transformers/modules/ssta_attention.py reaches hyvideo/utils/rewrite/t2v_prompt.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/utils/flash_attn_no_pad.py reaches hyvideo/utils/rewrite/clients.py in 5 hops.
- [INFERRED] bridges community 2 <-> 3 (strength 0.5): Inferred cross-community bridge: hyvideo/utils/flash_attn_no_pad.py reaches hyvideo/utils/rewrite/i2v_prompt.py in 5 hops.
- [INFERRED] shares_context community 2 <-> 4 (strength 0.5): Inferred shared context (language py) with no import path between community 2 (hyvideo/models/transformers/modules: communications) and community 4 (orphans).

## Risks

- [dataflow UNCHECKED_ALLOC] `hyvideo/__init__.py:26` `find_free_port` `sock`: Result of allocator stored in `sock` is never checked against NULL.

## Open Questions

- What would break if the most connected file in hyvideo/models/transformers/modules: communications changed?
- Should hyvideo/models/transformers/modules: communications be split, given cohesion 0.38?

## Sources

- `hyvideo/__init__.py`
- `hyvideo/commons/__init__.py`
- `hyvideo/models/transformers/modules/attention.py`
- `hyvideo/models/transformers/modules/ssta_attention.py`
- `hyvideo/models/vision_encoder/__init__.py`
- `hyvideo/utils/communications.py`
- `hyvideo/utils/flash_attn_no_pad.py`
