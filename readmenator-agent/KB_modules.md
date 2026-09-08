# Subsystem: modules

## hyvideo/models/transformers/modules/activation_layers.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `get_activation_layer` (function, line 20) `def get_activation_layer(act_type)`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/attention.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `attention` (function, line 50) `def attention(q, k, v, drop_rate, attn_mask, causal, attn_mode)`
  - `parallel_attention` (function, line 112) `def parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
  - `sequence_parallel_attention` (function, line 120) `def sequence_parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
  - `shrink_head` (function, line 145) `def shrink_head(encoder_state, dim)`
  - `score_mod` (function, line 188) `def score_mod(score, b, h, q_idx, kv_idx)`
  - `get_image_tile` (function, line 231) `def get_image_tile(tile_size)`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/embed_layers.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `PatchEmbed` (class, line 23) `class PatchEmbed(Module)`
  - `TextProjection` (class, line 90) `class TextProjection(Module)`
  - `VisionProjection` (class, line 122) `class VisionProjection(Module)`
  - `ClipVisionProjection` (class, line 139) `class ClipVisionProjection(Module)`
  - `timestep_embedding` (method, line 151) `def timestep_embedding(t, dim, max_period)`
  - `TimestepEmbedder` (class, line 178) `class TimestepEmbedder(Module)`
  - `__init__` (method, line 37) `def __init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)`
  - `forward` (method, line 82) `def forward(self, x)`
  - `__init__` (method, line 97) `def __init__(self, in_channels, hidden_size, act_layer, dtype, device)`
  - `forward` (method, line 114) `def forward(self, caption)`
  - `__init__` (method, line 124) `def __init__(self, input_dim, output_dim)`
  - `forward` (method, line 136) `def forward(self, vision_embeds)`
  - `__init__` (method, line 140) `def __init__(self, in_channels, out_channels)`
  - `forward` (method, line 147) `def forward(self, x)`
  - `__init__` (method, line 183) `def __init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)`
  - `forward` (method, line 208) `def forward(self, t)`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/mlp_layers.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `MLP` (class, line 29) `class MLP(Module)`
  - `LinearWarpforSingle` (class, line 70) `class LinearWarpforSingle(Module)`
  - `MLPEmbedder` (class, line 82) `class MLPEmbedder(Module)`
  - `FinalLayer` (class, line 96) `class FinalLayer(Module)`
  - `__init__` (method, line 32) `def __init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)`
  - `forward` (method, line 60) `def forward(self, x)`
  - `__init__` (method, line 71) `def __init__(self, in_dim, out_dim, bias, device, dtype)`
  - `forward` (method, line 76) `def forward(self, x, y)`
  - `__init__` (method, line 85) `def __init__(self, in_dim, hidden_dim, device, dtype)`
  - `forward` (method, line 92) `def forward(self, x)`
  - `__init__` (method, line 99) `def __init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)`
  - `forward` (method, line 133) `def forward(self, x, c)`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/modulate_layers.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `ModulateDiT` (class, line 23) `class ModulateDiT(Module)`
  - `modulate` (method, line 46) `def modulate(x, shift, scale)`
  - `apply_gate` (method, line 67) `def apply_gate(x, gate, tanh)`
  - `ckpt_wrapper` (method, line 86) `def ckpt_wrapper(module)`
  - `__init__` (method, line 26) `def __init__(self, hidden_size, factor, act_layer, dtype, device)`
  - `forward` (method, line 42) `def forward(self, x)`
  - `ckpt_forward` (method, line 87) `def ckpt_forward()`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/norm_layers.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `RMSNorm` (class, line 21) `class RMSNorm(Module)`
  - `get_norm_layer` (method, line 82) `def get_norm_layer(norm_layer)`
  - `__init__` (method, line 22) `def __init__(self, dim, elementwise_affine, eps, device, dtype)`
  - `_norm` (method, line 48) `def _norm(self, x)`
  - `reset_parameters` (method, line 61) `def reset_parameters(self)`
  - `forward` (method, line 65) `def forward(self, x)`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/posemb_layers.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `_to_tuple` (function, line 23) `def _to_tuple(x, dim)`
  - `get_meshgrid_nd` (function, line 32) `def get_meshgrid_nd(start)`
  - `reshape_for_broadcast` (function, line 83) `def reshape_for_broadcast(freqs_cis, x, head_first)`
  - `rotate_half` (function, line 151) `def rotate_half(x)`
  - `apply_rotary_emb` (function, line 158) `def apply_rotary_emb(xq, xk, freqs_cis, head_first)`
  - `get_nd_rotary_pos_embed` (function, line 210) `def get_nd_rotary_pos_embed(rope_dim_list, start)`
  - `get_1d_rotary_pos_embed` (function, line 281) `def get_1d_rotary_pos_embed(dim, pos, theta, use_real, theta_rescale_factor, interpolation_factor)`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

## hyvideo/models/transformers/modules/ssta_attention.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `tile` (function, line 23) `def tile(x, canvas_thw, tile_thw, sp_size)`
  - `untile` (function, line 53) `def untile(x, canvas_thw, tile_thw, sp_size)`
  - `get_tile_t_h_w` (function, line 82) `def get_tile_t_h_w(tile_id, tile_thw_dim)`
  - `importance_sampling` (function, line 90) `def importance_sampling(q, k, topk, threshold, lambda_, adaptive_pool)`
  - `similarity_sampling` (function, line 126) `def similarity_sampling(q, k, topk, threshold, block_num, adaptive_pool, temperature)`
  - `create_moba_3d_mask` (function, line 170) `def create_moba_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, add_text_mask, threshold, lambda_, mask_share_within_head, q_block_avg_pool, adaptive_pool, sampling_type)`
  - `create_sta_3d_mask_optimize` (function, line 323) `def create_sta_3d_mask_optimize(canvas_thw, tile_thw, kernel_thw)`
  - `create_sta_3d_mask` (function, line 374) `def create_sta_3d_mask(canvas_thw, tile_thw, kernel_thw, text_block_num)`
  - `create_ssta_3d_mask` (function, line 404) `def create_ssta_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, threshold, lambda_, text_mask, mask_share_within_head, adaptive_pool, sampling_type)`
  - `ssta_3d_attention` (function, line 465) `def ssta_3d_attention(all_q, all_k, all_v, canvas_thw, topk, tile_thw, kernel_thw, text_len, sparse_type, threshold, lambda_, pad_type, text_mask, mask_share_within_head, sampling_type, adaptive_pool)`
  - `get_block_avg_feat` (function, line 216) `def get_block_avg_feat(x, adaptive_pool, pooling_type)`
- Imported by: `hyvideo/models/transformers/modules/attention.py`

## hyvideo/models/transformers/modules/token_refiner.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `IndividualTokenRefinerBlock` (class, line 33) `class IndividualTokenRefinerBlock(Module)`
  - `IndividualTokenRefiner` (class, line 127) `class IndividualTokenRefiner(Module)`
  - `SingleTokenRefiner` (class, line 203) `class SingleTokenRefiner(Module)`
  - `__init__` (method, line 50) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
  - `forward` (method, line 98) `def forward(self, x, c, attn_mask)`
  - `__init__` (method, line 145) `def __init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
  - `forward` (method, line 178) `def forward(self, x, c, mask)`
  - `__init__` (method, line 222) `def __init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
  - `forward` (method, line 256) `def forward(self, x, t, mask)`
- Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

## hyvideo/models/transformers/modules/upsample.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `UpsamplerType` (class, line 38) `class UpsamplerType(Enum)`
  - `UpsamplerConfig` (class, line 46) `class UpsamplerConfig`
  - `SRResidualCausalBlock3D` (class, line 55) `class SRResidualCausalBlock3D(Module)`
  - `SRTo720pUpsampler` (class, line 70) `class SRTo720pUpsampler(ModelMixin, ConfigMixin)`
  - `SRTo1080pUpsampler` (class, line 100) `class SRTo1080pUpsampler(ModelMixin, ConfigMixin)`
  - `__init__` (method, line 56) `def __init__(self, channels)`
  - `forward` (method, line 66) `def forward(self, x)`
  - `__init__` (method, line 73) `def __init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)`
  - `forward` (method, line 89) `def forward(self, x)`
  - `__init__` (method, line 103) `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)`
  - `forward` (method, line 137) `def forward(self, z, target_shape)`
- Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
