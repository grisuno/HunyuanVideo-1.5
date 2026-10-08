# hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer

*Community 1 | 8 files | cohesion 0.57*

## Definition

This community groups 8 file(s) rooted at `hyvideo/models/transformers/modules` with dominant language py (cohesion 0.57). Central symbols: `ClipVisionProjection`, `FinalLayer`, `HunyuanVideo_1_5_DiffusionTransformer`, `IndividualTokenRefiner`, `IndividualTokenRefinerBlock`, `LinearWarpforSingle`, `MLP`, `MLPEmbedder`. Core file: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py` (22 symbols). Documented purpose: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain .

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py` | py | business_logic | 22 | yes |
| `hyvideo/models/transformers/modules/activation_layers.py` | py | business_logic | 1 | yes |
| `hyvideo/models/transformers/modules/embed_layers.py` | py | business_logic | 16 | yes |
| `hyvideo/models/transformers/modules/mlp_layers.py` | py | business_logic | 12 | yes |
| `hyvideo/models/transformers/modules/modulate_layers.py` | py | business_logic | 7 | yes |
| `hyvideo/models/transformers/modules/norm_layers.py` | py | business_logic | 6 | yes |
| `hyvideo/models/transformers/modules/posemb_layers.py` | py | business_logic | 7 | yes |
| `hyvideo/models/transformers/modules/token_refiner.py` | py | business_logic | 9 | yes |

## Key Symbols

- `MMDoubleStreamBlock` (class, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:45`) `class MMDoubleStreamBlock(Module)`
- `__init__` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:47`) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_m`
- `enable_deterministic` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:111`) `def enable_deterministic(self)`
- `disable_deterministic` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:114`) `def disable_deterministic(self)`
- `forward` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:117`) `def forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, blo`
- `MMSingleStreamBlock` (class, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:208`) `class MMSingleStreamBlock(Module)`
- `__init__` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:210`) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_m`
- `enable_deterministic` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:255`) `def enable_deterministic(self)`
- `disable_deterministic` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:258`) `def disable_deterministic(self)`
- `forward` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:261`) `def forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)` - Forward pass for the single stream block.
- `HunyuanVideo_1_5_DiffusionTransformer` (class, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:316`) `class HunyuanVideo_1_5_DiffusionTransformer(ModelMixin, ConfigMixin, PeftAdapter` - HunyuanVideo Transformer backbone.
- `__init__` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:351`) `def __init__(self, patch_size, in_channels, concat_condition, out_channels, hidd`
- `load_hunyuan_state_dict` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:563`) `def load_hunyuan_state_dict(self, model_path)`
- `enable_deterministic` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:601`) `def enable_deterministic(self)`
- `disable_deterministic` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:607`) `def disable_deterministic(self)`
- `get_rotary_pos_embed` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:613`) `def get_rotary_pos_embed(self, rope_sizes)`
- `reorder_txt_token` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:631`) `def reorder_txt_token(self, byt5_txt, txt, byt5_text_mask, text_mask, zero_feat,`
- `forward` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:667`) `def forward(self, hidden_states, timestep, text_states, text_states_2, encoder_a`
- `unpatchify` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:867`) `def unpatchify(self, x, t, h, w)` - Unpatchify a tensorized input back to frame format.
- `set_attn_mode` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:888`) `def set_attn_mode(self, attn_mode)`
- `save_lora_adapter` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:896`) `def save_lora_adapter(self, save_directory, adapter_name, upcast_before_saving,` - Save the LoRA parameters corresponding to the underlying model.
- `save_function` (method, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:943`) `def save_function(weights, filename)`
- `get_activation_layer` (function, `hyvideo/models/transformers/modules/activation_layers.py:20`) `def get_activation_layer(act_type)` - get activation layer
- `PatchEmbed` (class, `hyvideo/models/transformers/modules/embed_layers.py:23`) `class PatchEmbed(Module)` - 2D Image to Patch Embedding
- `__init__` (method, `hyvideo/models/transformers/modules/embed_layers.py:37`) `def __init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels`
- `forward` (method, `hyvideo/models/transformers/modules/embed_layers.py:82`) `def forward(self, x)`
- `TextProjection` (class, `hyvideo/models/transformers/modules/embed_layers.py:90`) `class TextProjection(Module)` - Projects text embeddings. Also handles dropout for classifier-free guidance.
- `__init__` (method, `hyvideo/models/transformers/modules/embed_layers.py:97`) `def __init__(self, in_channels, hidden_size, act_layer, dtype, device)`
- `forward` (method, `hyvideo/models/transformers/modules/embed_layers.py:114`) `def forward(self, caption)`
- `VisionProjection` (class, `hyvideo/models/transformers/modules/embed_layers.py:122`) `class VisionProjection(Module)`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 13
- Cross-boundary resolved imports (EXTRACTED): 10

## Connections

- [EXTRACTED] depends_on community 1 <-> 2 (strength 0.9): Extracted import edge crosses communities: hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py imports hyvideo/commons/__init__.py.
- [EXTRACTED] depends_on community 1 <-> 0 (strength 0.9): Extracted import edge crosses communities: hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py imports hyvideo/models/text_encoders/byT5/__init__.py.
- [INFERRED] shares_context community 1 <-> 3 (strength 0.5): Inferred shared context (language py) with no import path between community 1 (hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer) and community 3 (hyvideo/utils/rewrite).
- [INFERRED] shares_context community 1 <-> 4 (strength 0.5): Inferred shared context (language py and layer business_logic) with no import path between community 1 (hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer) and community 4 (orphans).

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- What would break if the most connected file in hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer changed?
- Should hyvideo/models/transformers/modules: hunyuanvideo_1_5_transformer be split, given cohesion 0.57?

## Sources

- `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`
- `hyvideo/models/transformers/modules/activation_layers.py`
- `hyvideo/models/transformers/modules/embed_layers.py`
- `hyvideo/models/transformers/modules/mlp_layers.py`
- `hyvideo/models/transformers/modules/modulate_layers.py`
- `hyvideo/models/transformers/modules/norm_layers.py`
- `hyvideo/models/transformers/modules/posemb_layers.py`
- `hyvideo/models/transformers/modules/token_refiner.py`
