# Subsystem: misc

## hyvideo/__init__.py
- Layer: utility
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `find_free_port` (function, line 25) `def find_free_port()`
  - `__initialize_default_distributed_environment` (function, line 32) `def __initialize_default_distributed_environment()`
- Depends on: `hyvideo/commons/__init__.py`

## hyvideo/models/__init__.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py

## hyvideo/models/text_encoders/__init__.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `use_default` (function, line 32) `def use_default(value, default)`
  - `load_text_encoder` (function, line 84) `def load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)`
  - `load_tokenizer` (function, line 114) `def load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)`
  - `TextEncoderModelOutput` (class, line 131) `class TextEncoderModelOutput(ModelOutput)`
  - `TextEncoder` (class, line 154) `class TextEncoder(Module)`
  - `__init__` (method, line 155) `def __init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type, tokenizer_path, output_key, use_attention_mask, prompt_template, prompt_template_video, hidden_state_skip_layer, apply_final_norm, reproduce, logger, device)`
  - `dtype` (method, line 245) `def dtype(self)`
  - `device` (method, line 249) `def device(self)`
  - `__repr__` (method, line 252) `def __repr__(self)`
  - `apply_text_to_template` (method, line 256) `def apply_text_to_template(text, template, prevent_empty_text)`
  - `calculate_crop_start` (method, line 281) `def calculate_crop_start(self, tokenized_input)`
  - `text2tokens` (method, line 316) `def text2tokens(self, text, data_type, max_length)`
  - `encode` (method, line 415) `def encode(self, batch_encoding, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts, data_type, device, is_uncond)`
  - `forward` (method, line 487) `def forward(self, text, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts)`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `MMDoubleStreamBlock` (class, line 45) `class MMDoubleStreamBlock(Module)`
  - `MMSingleStreamBlock` (class, line 208) `class MMSingleStreamBlock(Module)`
  - `HunyuanVideo_1_5_DiffusionTransformer` (class, line 316) `class HunyuanVideo_1_5_DiffusionTransformer(ModelMixin, ConfigMixin, PeftAdapterMixin)`
  - `__init__` (method, line 47) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
  - `enable_deterministic` (method, line 111) `def enable_deterministic(self)`
  - `disable_deterministic` (method, line 114) `def disable_deterministic(self)`
  - `forward` (method, line 117) `def forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)`
  - `__init__` (method, line 210) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dtype, device)`
  - `enable_deterministic` (method, line 255) `def enable_deterministic(self)`
  - `disable_deterministic` (method, line 258) `def disable_deterministic(self)`
  - `forward` (method, line 261) `def forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)`
  - `__init__` (method, line 351) `def __init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, mm_double_blocks_depth, mm_single_blocks_depth, rope_dim_list, qkv_bias, qk_norm, qk_norm_type, guidance_embed, use_meanflow, text_projection, use_attention_mask, text_states_dim, text_states_dim_2, text_pool_type, rope_theta, attn_mode, attn_param, glyph_byT5_v2, vision_projection, vision_states_dim, is_reshape_temporal_channels, use_cond_type_embedding, ideal_resolution, ideal_task)`
  - `load_hunyuan_state_dict` (method, line 563) `def load_hunyuan_state_dict(self, model_path)`
  - `enable_deterministic` (method, line 601) `def enable_deterministic(self)`
  - `disable_deterministic` (method, line 607) `def disable_deterministic(self)`
  - `get_rotary_pos_embed` (method, line 613) `def get_rotary_pos_embed(self, rope_sizes)`
  - `reorder_txt_token` (method, line 631) `def reorder_txt_token(self, byt5_txt, txt, byt5_text_mask, text_mask, zero_feat, is_reorder)`
  - `forward` (method, line 667) `def forward(self, hidden_states, timestep, text_states, text_states_2, encoder_attention_mask, timestep_r, vision_states, output_features, output_features_stride, attention_kwargs, freqs_cos, freqs_sin, return_dict, guidance, mask_type, extra_kwargs)`
  - `unpatchify` (method, line 867) `def unpatchify(self, x, t, h, w)`
  - `set_attn_mode` (method, line 888) `def set_attn_mode(self, attn_mode)`
  - `save_lora_adapter` (method, line 896) `def save_lora_adapter(self, save_directory, adapter_name, upcast_before_saving, safe_serialization, weight_name)`
  - `save_function` (method, line 943) `def save_function(weights, filename)`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/models/vision_encoder/__init__.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `use_default` (function, line 29) `def use_default(value, default)`
  - `load_vision_encoder` (function, line 33) `def load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)`
  - `load_image_processor` (function, line 63) `def load_image_processor(processor_type, processor_path, logger)`
  - `VisionEncoderModelOutput` (class, line 83) `class VisionEncoderModelOutput(ModelOutput)`
  - `VisionEncoder` (class, line 104) `class VisionEncoder(Module)`
  - `__init__` (method, line 105) `def __init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type, processor_path, output_key, logger, device)`
  - `__repr__` (method, line 149) `def __repr__(self)`
  - `encode_latents_to_images` (method, line 152) `def encode_latents_to_images(self, latents, vae, reorg_token)`
  - `encode_images` (method, line 179) `def encode_images(self, images)`
  - `encode_latents` (method, line 205) `def encode_latents(self, latents, vae, reorg_token)`
  - `forward` (method, line 225) `def forward(self, images)`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/optim/muon.py
- Layer: utility
- Language: py
- Symbols:
  - `zeropower_via_newtonschulz5` (function, line 17) `def zeropower_via_newtonschulz5(G, steps)`
  - `Muon` (class, line 54) `class Muon(Optimizer)`
  - `get_muon_optimizer` (method, line 214) `def get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)`
  - `__init__` (method, line 72) `def __init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)`
  - `adjust_lr_for_muon` (method, line 108) `def adjust_lr_for_muon(self, lr, param_shape)`
  - `step` (method, line 116) `def step(self, closure)`
- Imported by: `train.py`

## hyvideo/schedulers/scheduling_flow_match_discrete.py
- Layer: infrastructure
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `FlowMatchDiscreteSchedulerOutput` (class, line 50) `class FlowMatchDiscreteSchedulerOutput(BaseOutput)`
  - `FlowMatchDiscreteScheduler` (class, line 63) `class FlowMatchDiscreteScheduler(SchedulerMixin, ConfigMixin)`
  - `__init__` (method, line 86) `def __init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift, n_tokens, flux_base_token, flux_max_token, flux_shift_factor)`
  - `step_index` (method, line 119) `def step_index(self)`
  - `begin_index` (method, line 126) `def begin_index(self)`
  - `set_begin_index` (method, line 133) `def set_begin_index(self, begin_index)`
  - `_sigma_to_t` (method, line 143) `def _sigma_to_t(self, sigma)`
  - `set_timesteps` (method, line 146) `def set_timesteps(self, num_inference_steps, device, n_tokens)`
  - `index_for_timestep` (method, line 182) `def index_for_timestep(self, timestep, schedule_timesteps)`
  - `_init_step_index` (method, line 196) `def _init_step_index(self, timestep)`
  - `scale_model_input` (method, line 204) `def scale_model_input(self, sample, timestep)`
  - `get_lin_function` (method, line 208) `def get_lin_function(x1, y1, x2, y2)`
  - `flux_time_shift` (method, line 214) `def flux_time_shift(mu, sigma, t)`
  - `sd3_time_shift` (method, line 217) `def sd3_time_shift(self, t)`
  - `step` (method, line 220) `def step(self, model_output, timestep, sample, generator, n_tokens, return_dict)`
  - `__len__` (method, line 291) `def __len__(self)`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
