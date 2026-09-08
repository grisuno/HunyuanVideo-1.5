# Symbols

| Symbol | Kind | File:Line | Signature |
|--------|------|-----------|-----------|
| `generate_video` | function | `generate.py:128` | `def generate_video(args)` |
| `load_checkpoint_to_transformer` | function | `generate.py:96` | `def load_checkpoint_to_transformer(pipe, checkpoint_path)` |
| `load_lora_adapter` | function | `generate.py:112` | `def load_lora_adapter(pipe, lora_path)` |
| `main` | function | `generate.py:274` | `def main()` |
| `rank0_log` | function | `generate.py:50` | `def rank0_log(message, level)` |
| `save_config` | function | `generate.py:54` | `def save_config(args, output_path, task, transformer_version)` |
| `save_video` | function | `generate.py:42` | `def save_video(video, path)` |
| `str_to_bool` | function | `generate.py:81` | `def str_to_bool(value)` |
| `__initialize_default_distributed_environment` | function | `hyvideo/__init__.py:32` | `def __initialize_default_distributed_environment()` |
| `find_free_port` | function | `hyvideo/__init__.py:25` | `def find_free_port()` |
| `_ntuple` | function | `hyvideo/commons/__init__.py:24` | `def _ntuple(n)` |
| `auto_offload_model` | function | `hyvideo/commons/__init__.py:229` | `def auto_offload_model(models, device, enabled)` |
| `get_gpu_memory` | function | `hyvideo/commons/__init__.py:243` | `def get_gpu_memory(device)` |
| `get_rank` | function | `hyvideo/commons/__init__.py:254` | `def get_rank()` |
| `is_angelslim_available` | function | `hyvideo/commons/__init__.py:171` | `def is_angelslim_available()` |
| `is_flash2_available` | function | `hyvideo/commons/__init__.py:142` | `def is_flash2_available()` |
| `is_flash3_available` | function | `hyvideo/commons/__init__.py:149` | `def is_flash3_available()` |
| `is_flash_available` | function | `hyvideo/commons/__init__.py:156` | `def is_flash_available()` |
| `is_sparse_attn_available` | function | `hyvideo/commons/__init__.py:162` | `def is_sparse_attn_available()` |
| `is_sparse_attn_supported` | function | `hyvideo/commons/__init__.py:159` | `def is_sparse_attn_supported()` |
| `maybe_fallback_attn_mode` | function | `hyvideo/commons/__init__.py:178` | `def maybe_fallback_attn_mode(attn_mode)` |
| `parse` | function | `hyvideo/commons/__init__.py:26` | `def parse(x)` |
| `InferState` | class | `hyvideo/commons/infer_state.py:21` | `class InferState` |
| `get_infer_state` | method | `hyvideo/commons/infer_state.py:87` | `def get_infer_state()` |
| `initialize_infer_state` | method | `hyvideo/commons/infer_state.py:49` | `def initialize_infer_state(args)` |
| `parse_range` | method | `hyvideo/commons/infer_state.py:42` | `def parse_range(value)` |
| `ParallelDims` | class | `hyvideo/commons/parallel_states.py:24` | `class ParallelDims` |
| `__post_init__` | method | `hyvideo/commons/parallel_states.py:29` | `def __post_init__(self)` |
| `build_mesh` | method | `hyvideo/commons/parallel_states.py:37` | `def build_mesh(self, device_type)` |
| `dp_enabled` | method | `hyvideo/commons/parallel_states.py:76` | `def dp_enabled(self)` |
| `get_parallel_state` | method | `hyvideo/commons/parallel_states.py:89` | `def get_parallel_state()` |
| `initialize_parallel_state` | method | `hyvideo/commons/parallel_states.py:81` | `def initialize_parallel_state(sp, dp_replicate)` |
| `sp_enabled` | method | `hyvideo/commons/parallel_states.py:68` | `def sp_enabled(self)` |
| `sp_mesh` | method | `hyvideo/commons/parallel_states.py:72` | `def sp_mesh(self)` |
| `AttnBlock` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:186` | `class AttnBlock(Module)` |
| `AutoencoderKLConv3D` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:495` | `class AutoencoderKLConv3D(ModelMixin, ConfigMixin)` |
| `CausalConv3d` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:129` | `class CausalConv3d(Module)` |
| `Decoder` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:413` | `class Decoder(Module)` |
| `DecoderOutput` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:40` | `class DecoderOutput(BaseOutput)` |
| `Downsample` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:251` | `class Downsample(Module)` |
| `Encoder` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:331` | `class Encoder(Module)` |
| `PatchCausalConv3d` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:65` | `class PatchCausalConv3d(Conv3d)` |
| `RMS_norm` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:110` | `class RMS_norm(Module)` |
| `ResnetBlock` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:219` | `class ResnetBlock(Module)` |
| `Upsample` | class | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:293` | `class Upsample(Module)` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:113` | `def __init__(self, dim, channel_first, images, bias)` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:132` | `def __init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:189` | `def __init__(self, in_channels)` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:222` | `def __init__(self, in_channels, out_channels)` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:253` | `def __init__(self, in_channels, out_channels, add_temporal_downsample)` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:296` | `def __init__(self, in_channels, out_channels, add_temporal_upsample)` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:334` | `def __init__(self, in_channels, z_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, downs` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:416` | `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, upsa` |
| `__init__` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:500` | `def __init__(self, in_channels, out_channels, latent_channels, block_out_channels, layers_per_block, ffactor_spatial, ff` |
| `_decode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:858` | `def _decode(z)` |
| `_encode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:835` | `def _encode(x)` |
| `_set_gradient_checkpointing` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:563` | `def _set_gradient_checkpointing(self, module, value)` |
| `attention` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:200` | `def attention(self, h_)` |
| `blend_h` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:594` | `def blend_h(self, a, b, blend_extent)` |
| `blend_t` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:608` | `def blend_t(self, a, b, blend_extent)` |
| `blend_v` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:601` | `def blend_v(self, a, b, blend_extent)` |
| `create_custom_forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:52` | `def create_custom_forward(module)` |
| `custom_forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:53` | `def custom_forward()` |
| `decode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:856` | `def decode(self, z, return_dict, generator)` |
| `disable_slicing` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:591` | `def disable_slicing(self)` |
| `disable_spatial_tiling` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:579` | `def disable_spatial_tiling(self)` |
| `disable_temporal_tiling` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:573` | `def disable_temporal_tiling(self)` |
| `disable_tile_parallelism` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:674` | `def disable_tile_parallelism(self)` |
| `disable_tiling` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:585` | `def disable_tiling(self)` |
| `enable_slicing` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:588` | `def enable_slicing(self)` |
| `enable_spatial_tiling` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:576` | `def enable_spatial_tiling(self, use_tiling)` |
| `enable_temporal_tiling` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:569` | `def enable_temporal_tiling(self, use_tiling)` |
| `enable_tile_parallelism` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:671` | `def enable_tile_parallelism(self)` |
| `enable_tiling` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:582` | `def enable_tiling(self, use_tiling)` |
| `encode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:833` | `def encode(self, x, return_dict)` |
| `find_split_indices` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:67` | `def find_split_indices(self, seq_len, part_num)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:86` | `def forward(self, input)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:123` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:158` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:215` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:236` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:261` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:303` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:386` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:468` | `def forward(self, z)` |
| `forward` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:876` | `def forward(self, sample, sample_posterior, return_posterior, return_dict)` |
| `forward_with_checkpointing` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:50` | `def forward_with_checkpointing(module)` |
| `memory_efficient_context` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:890` | `def memory_efficient_context(self)` |
| `prepare_causal_attention_mask` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:163` | `def prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)` |
| `set_tile_sample_min_size` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:554` | `def set_tile_sample_min_size(self, sample_size, tile_overlap_factor)` |
| `spatial_tiled_decode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:772` | `def spatial_tiled_decode(self, z)` |
| `spatial_tiled_encode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:615` | `def spatial_tiled_encode(self, x)` |
| `swish` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:45` | `def swish(x, inplace)` |
| `temporal_tiled_decode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:803` | `def temporal_tiled_decode(self, z)` |
| `temporal_tiled_encode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:643` | `def temporal_tiled_encode(self, x)` |
| `tile_parallel_spatial_tiled_decode` | method | `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:677` | `def tile_parallel_spatial_tiled_decode(self, z)` |
| `TextEncoder` | class | `hyvideo/models/text_encoders/__init__.py:154` | `class TextEncoder(Module)` |
| `TextEncoderModelOutput` | class | `hyvideo/models/text_encoders/__init__.py:131` | `class TextEncoderModelOutput(ModelOutput)` |
| `__init__` | method | `hyvideo/models/text_encoders/__init__.py:155` | `def __init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type, tokenizer_p` |
| `__repr__` | method | `hyvideo/models/text_encoders/__init__.py:252` | `def __repr__(self)` |
| `apply_text_to_template` | method | `hyvideo/models/text_encoders/__init__.py:256` | `def apply_text_to_template(text, template, prevent_empty_text)` |
| `calculate_crop_start` | method | `hyvideo/models/text_encoders/__init__.py:281` | `def calculate_crop_start(self, tokenized_input)` |
| `device` | method | `hyvideo/models/text_encoders/__init__.py:249` | `def device(self)` |
| `dtype` | method | `hyvideo/models/text_encoders/__init__.py:245` | `def dtype(self)` |
| `encode` | method | `hyvideo/models/text_encoders/__init__.py:415` | `def encode(self, batch_encoding, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_te` |
| `forward` | method | `hyvideo/models/text_encoders/__init__.py:487` | `def forward(self, text, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts)` |
| `load_text_encoder` | function | `hyvideo/models/text_encoders/__init__.py:84` | `def load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)` |
| `load_tokenizer` | function | `hyvideo/models/text_encoders/__init__.py:114` | `def load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)` |
| `text2tokens` | method | `hyvideo/models/text_encoders/__init__.py:316` | `def text2tokens(self, text, data_type, max_length)` |
| `use_default` | function | `hyvideo/models/text_encoders/__init__.py:32` | `def use_default(value, default)` |
| `ByT5Mapper` | class | `hyvideo/models/text_encoders/byT5/__init__.py:187` | `class ByT5Mapper(Module)` |
| `__init__` | method | `hyvideo/models/text_encoders/byT5/__init__.py:199` | `def __init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)` |
| `add_special_token` | function | `hyvideo/models/text_encoders/byT5/__init__.py:89` | `def add_special_token(tokenizer, text_encoder, add_color, add_font, color_ann_path, font_ann_path, multilingual)` |
| `create_byt5` | function | `hyvideo/models/text_encoders/byT5/__init__.py:43` | `def create_byt5(args, device)` |
| `forward` | method | `hyvideo/models/text_encoders/byT5/__init__.py:210` | `def forward(self, x)` |
| `load_byt5_and_byt5_tokenizer` | function | `hyvideo/models/text_encoders/byT5/__init__.py:131` | `def load_byt5_and_byt5_tokenizer(byt5_name, special_token, color_special_token, font_special_token, color_ann_path, font` |
| `load_glyph_byT5_v2` | function | `hyvideo/models/text_encoders/byT5/__init__.py:23` | `def load_glyph_byT5_v2(args, device)` |
| `MultilingualPromptFormat` | class | `hyvideo/models/text_encoders/byT5/format_prompt.py:44` | `class MultilingualPromptFormat` |
| `__init__` | method | `hyvideo/models/text_encoders/byT5/format_prompt.py:46` | `def __init__(self, font_path, color_path)` |
| `closest_color` | function | `hyvideo/models/text_encoders/byT5/format_prompt.py:20` | `def closest_color(requested_color)` |
| `convert_rgb_to_names` | function | `hyvideo/models/text_encoders/byT5/format_prompt.py:34` | `def convert_rgb_to_names(rgb_tuple)` |
| `format_prompt` | method | `hyvideo/models/text_encoders/byT5/format_prompt.py:56` | `def format_prompt(self, texts, styles)` |
| `HunyuanVideo_1_5_DiffusionTransformer` | class | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:316` | `class HunyuanVideo_1_5_DiffusionTransformer(ModelMixin, ConfigMixin, PeftAdapterMixin)` |
| `MMDoubleStreamBlock` | class | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:45` | `class MMDoubleStreamBlock(Module)` |
| `MMSingleStreamBlock` | class | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:208` | `class MMSingleStreamBlock(Module)` |
| `__init__` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:47` | `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dt` |
| `__init__` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:210` | `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dt` |
| `__init__` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:351` | `def __init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp` |
| `disable_deterministic` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:114` | `def disable_deterministic(self)` |
| `disable_deterministic` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:258` | `def disable_deterministic(self)` |
| `disable_deterministic` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:607` | `def disable_deterministic(self)` |
| `enable_deterministic` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:111` | `def enable_deterministic(self)` |
| `enable_deterministic` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:255` | `def enable_deterministic(self)` |
| `enable_deterministic` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:601` | `def enable_deterministic(self)` |
| `forward` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:117` | `def forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)` |
| `forward` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:261` | `def forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)` |
| `forward` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:667` | `def forward(self, hidden_states, timestep, text_states, text_states_2, encoder_attention_mask, timestep_r, vision_states` |
| `get_rotary_pos_embed` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:613` | `def get_rotary_pos_embed(self, rope_sizes)` |
| `load_hunyuan_state_dict` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:563` | `def load_hunyuan_state_dict(self, model_path)` |
| `reorder_txt_token` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:631` | `def reorder_txt_token(self, byt5_txt, txt, byt5_text_mask, text_mask, zero_feat, is_reorder)` |
| `save_function` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:943` | `def save_function(weights, filename)` |
| `save_lora_adapter` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:896` | `def save_lora_adapter(self, save_directory, adapter_name, upcast_before_saving, safe_serialization, weight_name)` |
| `set_attn_mode` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:888` | `def set_attn_mode(self, attn_mode)` |
| `unpatchify` | method | `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:867` | `def unpatchify(self, x, t, h, w)` |
| `get_activation_layer` | function | `hyvideo/models/transformers/modules/activation_layers.py:20` | `def get_activation_layer(act_type)` |
| `attention` | function | `hyvideo/models/transformers/modules/attention.py:50` | `def attention(q, k, v, drop_rate, attn_mask, causal, attn_mode)` |
| `get_image_tile` | function | `hyvideo/models/transformers/modules/attention.py:231` | `def get_image_tile(tile_size)` |
| `parallel_attention` | function | `hyvideo/models/transformers/modules/attention.py:112` | `def parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)` |
| `score_mod` | function | `hyvideo/models/transformers/modules/attention.py:188` | `def score_mod(score, b, h, q_idx, kv_idx)` |
| `sequence_parallel_attention` | function | `hyvideo/models/transformers/modules/attention.py:120` | `def sequence_parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)` |
| `shrink_head` | function | `hyvideo/models/transformers/modules/attention.py:145` | `def shrink_head(encoder_state, dim)` |
| `ClipVisionProjection` | class | `hyvideo/models/transformers/modules/embed_layers.py:139` | `class ClipVisionProjection(Module)` |
| `PatchEmbed` | class | `hyvideo/models/transformers/modules/embed_layers.py:23` | `class PatchEmbed(Module)` |
| `TextProjection` | class | `hyvideo/models/transformers/modules/embed_layers.py:90` | `class TextProjection(Module)` |
| `TimestepEmbedder` | class | `hyvideo/models/transformers/modules/embed_layers.py:178` | `class TimestepEmbedder(Module)` |
| `VisionProjection` | class | `hyvideo/models/transformers/modules/embed_layers.py:122` | `class VisionProjection(Module)` |
| `__init__` | method | `hyvideo/models/transformers/modules/embed_layers.py:37` | `def __init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten,` |
| `__init__` | method | `hyvideo/models/transformers/modules/embed_layers.py:97` | `def __init__(self, in_channels, hidden_size, act_layer, dtype, device)` |
| `__init__` | method | `hyvideo/models/transformers/modules/embed_layers.py:124` | `def __init__(self, input_dim, output_dim)` |
| `__init__` | method | `hyvideo/models/transformers/modules/embed_layers.py:140` | `def __init__(self, in_channels, out_channels)` |
| `__init__` | method | `hyvideo/models/transformers/modules/embed_layers.py:183` | `def __init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)` |
| `forward` | method | `hyvideo/models/transformers/modules/embed_layers.py:82` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/transformers/modules/embed_layers.py:114` | `def forward(self, caption)` |
| `forward` | method | `hyvideo/models/transformers/modules/embed_layers.py:136` | `def forward(self, vision_embeds)` |
| `forward` | method | `hyvideo/models/transformers/modules/embed_layers.py:147` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/transformers/modules/embed_layers.py:208` | `def forward(self, t)` |
| `timestep_embedding` | method | `hyvideo/models/transformers/modules/embed_layers.py:151` | `def timestep_embedding(t, dim, max_period)` |
| `FinalLayer` | class | `hyvideo/models/transformers/modules/mlp_layers.py:96` | `class FinalLayer(Module)` |
| `LinearWarpforSingle` | class | `hyvideo/models/transformers/modules/mlp_layers.py:70` | `class LinearWarpforSingle(Module)` |
| `MLP` | class | `hyvideo/models/transformers/modules/mlp_layers.py:29` | `class MLP(Module)` |
| `MLPEmbedder` | class | `hyvideo/models/transformers/modules/mlp_layers.py:82` | `class MLPEmbedder(Module)` |
| `__init__` | method | `hyvideo/models/transformers/modules/mlp_layers.py:32` | `def __init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtyp` |
| `__init__` | method | `hyvideo/models/transformers/modules/mlp_layers.py:71` | `def __init__(self, in_dim, out_dim, bias, device, dtype)` |
| `__init__` | method | `hyvideo/models/transformers/modules/mlp_layers.py:85` | `def __init__(self, in_dim, hidden_dim, device, dtype)` |
| `__init__` | method | `hyvideo/models/transformers/modules/mlp_layers.py:99` | `def __init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)` |
| `forward` | method | `hyvideo/models/transformers/modules/mlp_layers.py:60` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/transformers/modules/mlp_layers.py:76` | `def forward(self, x, y)` |
| `forward` | method | `hyvideo/models/transformers/modules/mlp_layers.py:92` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/transformers/modules/mlp_layers.py:133` | `def forward(self, x, c)` |
| `ModulateDiT` | class | `hyvideo/models/transformers/modules/modulate_layers.py:23` | `class ModulateDiT(Module)` |
| `__init__` | method | `hyvideo/models/transformers/modules/modulate_layers.py:26` | `def __init__(self, hidden_size, factor, act_layer, dtype, device)` |
| `apply_gate` | method | `hyvideo/models/transformers/modules/modulate_layers.py:67` | `def apply_gate(x, gate, tanh)` |
| `ckpt_forward` | method | `hyvideo/models/transformers/modules/modulate_layers.py:87` | `def ckpt_forward()` |
| `ckpt_wrapper` | method | `hyvideo/models/transformers/modules/modulate_layers.py:86` | `def ckpt_wrapper(module)` |
| `forward` | method | `hyvideo/models/transformers/modules/modulate_layers.py:42` | `def forward(self, x)` |
| `modulate` | method | `hyvideo/models/transformers/modules/modulate_layers.py:46` | `def modulate(x, shift, scale)` |
| `RMSNorm` | class | `hyvideo/models/transformers/modules/norm_layers.py:21` | `class RMSNorm(Module)` |
| `__init__` | method | `hyvideo/models/transformers/modules/norm_layers.py:22` | `def __init__(self, dim, elementwise_affine, eps, device, dtype)` |
| `_norm` | method | `hyvideo/models/transformers/modules/norm_layers.py:48` | `def _norm(self, x)` |
| `forward` | method | `hyvideo/models/transformers/modules/norm_layers.py:65` | `def forward(self, x)` |
| `get_norm_layer` | method | `hyvideo/models/transformers/modules/norm_layers.py:82` | `def get_norm_layer(norm_layer)` |
| `reset_parameters` | method | `hyvideo/models/transformers/modules/norm_layers.py:61` | `def reset_parameters(self)` |
| `_to_tuple` | function | `hyvideo/models/transformers/modules/posemb_layers.py:23` | `def _to_tuple(x, dim)` |
| `apply_rotary_emb` | function | `hyvideo/models/transformers/modules/posemb_layers.py:158` | `def apply_rotary_emb(xq, xk, freqs_cis, head_first)` |
| `get_1d_rotary_pos_embed` | function | `hyvideo/models/transformers/modules/posemb_layers.py:281` | `def get_1d_rotary_pos_embed(dim, pos, theta, use_real, theta_rescale_factor, interpolation_factor)` |
| `get_meshgrid_nd` | function | `hyvideo/models/transformers/modules/posemb_layers.py:32` | `def get_meshgrid_nd(start)` |
| `get_nd_rotary_pos_embed` | function | `hyvideo/models/transformers/modules/posemb_layers.py:210` | `def get_nd_rotary_pos_embed(rope_dim_list, start)` |
| `reshape_for_broadcast` | function | `hyvideo/models/transformers/modules/posemb_layers.py:83` | `def reshape_for_broadcast(freqs_cis, x, head_first)` |
| `rotate_half` | function | `hyvideo/models/transformers/modules/posemb_layers.py:151` | `def rotate_half(x)` |
| `create_moba_3d_mask` | function | `hyvideo/models/transformers/modules/ssta_attention.py:170` | `def create_moba_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, add_text_mask, threshold, lambda_,` |
| `create_ssta_3d_mask` | function | `hyvideo/models/transformers/modules/ssta_attention.py:404` | `def create_ssta_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, threshold, lambda_, text_mask, mas` |
| `create_sta_3d_mask` | function | `hyvideo/models/transformers/modules/ssta_attention.py:374` | `def create_sta_3d_mask(canvas_thw, tile_thw, kernel_thw, text_block_num)` |
| `create_sta_3d_mask_optimize` | function | `hyvideo/models/transformers/modules/ssta_attention.py:323` | `def create_sta_3d_mask_optimize(canvas_thw, tile_thw, kernel_thw)` |
| `get_block_avg_feat` | function | `hyvideo/models/transformers/modules/ssta_attention.py:216` | `def get_block_avg_feat(x, adaptive_pool, pooling_type)` |
| `get_tile_t_h_w` | function | `hyvideo/models/transformers/modules/ssta_attention.py:82` | `def get_tile_t_h_w(tile_id, tile_thw_dim)` |
| `importance_sampling` | function | `hyvideo/models/transformers/modules/ssta_attention.py:90` | `def importance_sampling(q, k, topk, threshold, lambda_, adaptive_pool)` |
| `similarity_sampling` | function | `hyvideo/models/transformers/modules/ssta_attention.py:126` | `def similarity_sampling(q, k, topk, threshold, block_num, adaptive_pool, temperature)` |
| `ssta_3d_attention` | function | `hyvideo/models/transformers/modules/ssta_attention.py:465` | `def ssta_3d_attention(all_q, all_k, all_v, canvas_thw, topk, tile_thw, kernel_thw, text_len, sparse_type, threshold, lam` |
| `tile` | function | `hyvideo/models/transformers/modules/ssta_attention.py:23` | `def tile(x, canvas_thw, tile_thw, sp_size)` |
| `untile` | function | `hyvideo/models/transformers/modules/ssta_attention.py:53` | `def untile(x, canvas_thw, tile_thw, sp_size)` |
| `IndividualTokenRefiner` | class | `hyvideo/models/transformers/modules/token_refiner.py:127` | `class IndividualTokenRefiner(Module)` |
| `IndividualTokenRefinerBlock` | class | `hyvideo/models/transformers/modules/token_refiner.py:33` | `class IndividualTokenRefinerBlock(Module)` |
| `SingleTokenRefiner` | class | `hyvideo/models/transformers/modules/token_refiner.py:203` | `class SingleTokenRefiner(Module)` |
| `__init__` | method | `hyvideo/models/transformers/modules/token_refiner.py:50` | `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dt` |
| `__init__` | method | `hyvideo/models/transformers/modules/token_refiner.py:145` | `def __init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_b` |
| `__init__` | method | `hyvideo/models/transformers/modules/token_refiner.py:222` | `def __init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_nor` |
| `forward` | method | `hyvideo/models/transformers/modules/token_refiner.py:98` | `def forward(self, x, c, attn_mask)` |
| `forward` | method | `hyvideo/models/transformers/modules/token_refiner.py:178` | `def forward(self, x, c, mask)` |
| `forward` | method | `hyvideo/models/transformers/modules/token_refiner.py:256` | `def forward(self, x, t, mask)` |
| `SRResidualCausalBlock3D` | class | `hyvideo/models/transformers/modules/upsample.py:55` | `class SRResidualCausalBlock3D(Module)` |
| `SRTo1080pUpsampler` | class | `hyvideo/models/transformers/modules/upsample.py:100` | `class SRTo1080pUpsampler(ModelMixin, ConfigMixin)` |
| `SRTo720pUpsampler` | class | `hyvideo/models/transformers/modules/upsample.py:70` | `class SRTo720pUpsampler(ModelMixin, ConfigMixin)` |
| `UpsamplerConfig` | class | `hyvideo/models/transformers/modules/upsample.py:46` | `class UpsamplerConfig` |
| `UpsamplerType` | class | `hyvideo/models/transformers/modules/upsample.py:38` | `class UpsamplerType(Enum)` |
| `__init__` | method | `hyvideo/models/transformers/modules/upsample.py:56` | `def __init__(self, channels)` |
| `__init__` | method | `hyvideo/models/transformers/modules/upsample.py:73` | `def __init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)` |
| `__init__` | method | `hyvideo/models/transformers/modules/upsample.py:103` | `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)` |
| `forward` | method | `hyvideo/models/transformers/modules/upsample.py:66` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/transformers/modules/upsample.py:89` | `def forward(self, x)` |
| `forward` | method | `hyvideo/models/transformers/modules/upsample.py:137` | `def forward(self, z, target_shape)` |
| `VisionEncoder` | class | `hyvideo/models/vision_encoder/__init__.py:104` | `class VisionEncoder(Module)` |
| `VisionEncoderModelOutput` | class | `hyvideo/models/vision_encoder/__init__.py:83` | `class VisionEncoderModelOutput(ModelOutput)` |
| `__init__` | method | `hyvideo/models/vision_encoder/__init__.py:105` | `def __init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type, processor_path, o` |
| `__repr__` | method | `hyvideo/models/vision_encoder/__init__.py:149` | `def __repr__(self)` |
| `encode_images` | method | `hyvideo/models/vision_encoder/__init__.py:179` | `def encode_images(self, images)` |
| `encode_latents` | method | `hyvideo/models/vision_encoder/__init__.py:205` | `def encode_latents(self, latents, vae, reorg_token)` |
| `encode_latents_to_images` | method | `hyvideo/models/vision_encoder/__init__.py:152` | `def encode_latents_to_images(self, latents, vae, reorg_token)` |
| `forward` | method | `hyvideo/models/vision_encoder/__init__.py:225` | `def forward(self, images)` |
| `load_image_processor` | function | `hyvideo/models/vision_encoder/__init__.py:63` | `def load_image_processor(processor_type, processor_path, logger)` |
| `load_vision_encoder` | function | `hyvideo/models/vision_encoder/__init__.py:33` | `def load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)` |
| `use_default` | function | `hyvideo/models/vision_encoder/__init__.py:29` | `def use_default(value, default)` |
| `Muon` | class | `hyvideo/optim/muon.py:54` | `class Muon(Optimizer)` |
| `__init__` | method | `hyvideo/optim/muon.py:72` | `def __init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)` |
| `adjust_lr_for_muon` | method | `hyvideo/optim/muon.py:108` | `def adjust_lr_for_muon(self, lr, param_shape)` |
| `get_muon_optimizer` | method | `hyvideo/optim/muon.py:214` | `def get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)` |
| `step` | method | `hyvideo/optim/muon.py:116` | `def step(self, closure)` |
| `zeropower_via_newtonschulz5` | function | `hyvideo/optim/muon.py:17` | `def zeropower_via_newtonschulz5(G, steps)` |
| `HunyuanVideoPipelineOutput` | class | `hyvideo/pipelines/hunyuan_video_pipeline.py:82` | `class HunyuanVideoPipelineOutput(BaseOutput)` |
| `HunyuanVideo_1_5_Pipeline` | class | `hyvideo/pipelines/hunyuan_video_pipeline.py:87` | `class HunyuanVideo_1_5_Pipeline(DiffusionPipeline)` |
| `__call__` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:886` | `def __call__(self, prompt, aspect_ratio, video_length, prompt_rewrite, num_inference_steps, guidance_scale, enable_sr, s` |
| `__init__` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:92` | `def __init__(self, vae, text_encoder, transformer, scheduler, text_encoder_2, flow_shift, guidance_scale, num_inference_` |
| `_create_scheduler` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:185` | `def _create_scheduler(cls, flow_shift)` |
| `_extract_glyph_texts` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:573` | `def _extract_glyph_texts(self, prompt)` |
| `_load_byt5` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:194` | `def _load_byt5(cls, cached_folder, glyph_byT5_v2, byt5_max_length, device)` |
| `_load_text_encoders` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1582` | `def _load_text_encoders(cls, pretrained_model_path, device)` |
| `_load_vision_encoder` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1607` | `def _load_vision_encoder(cls, pretrained_model_name_or_path, device)` |
| `_prepare_byt5_embeddings` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:623` | `def _prepare_byt5_embeddings(self, prompts, device)` |
| `_prepare_cond_latents` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:734` | `def _prepare_cond_latents(self, task_type, cond_latents, latents, multitask_mask)` |
| `_prepare_vision_states` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:698` | `def _prepare_vision_states(self, reference_image, target_resolution, latents, device)` |
| `_process_single_byt5_prompt` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:589` | `def _process_single_byt5_prompt(self, prompt_text, device)` |
| `apply_infer_optimization` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1335` | `def apply_infer_optimization(self, infer_state, enable_offloading, enable_group_offloading, overlap_group_offloading)` |
| `clip_skip` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:525` | `def clip_skip(self)` |
| `create_pipeline` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1467` | `def create_pipeline(cls, pretrained_model_name_or_path, transformer_version, create_sr_pipeline, transformer_dtype, devi` |
| `create_sr_pipeline` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1426` | `def create_sr_pipeline(self, cached_folder, sr_version, transformer_dtype, device)` |
| `cross_attention_kwargs` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:536` | `def cross_attention_kwargs(self)` |
| `do_classifier_free_guidance` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:532` | `def do_classifier_free_guidance(self)` |
| `encode_prompt` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:242` | `def encode_prompt(self, prompt, device, num_videos_per_prompt, do_classifier_free_guidance, negative_prompt, prompt_embe` |
| `extract_image_features` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:680` | `def extract_image_features(self, reference_image)` |
| `get_byt5_text_tokens` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:548` | `def get_byt5_text_tokens(byt5_tokenizer, byt5_max_length, text_prompt)` |
| `get_closest_resolution_given_original_size` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:800` | `def get_closest_resolution_given_original_size(self, origin_size, target_size)` |
| `get_closest_resolution_given_reference_image` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:776` | `def get_closest_resolution_given_reference_image(self, reference_image, target_resolution)` |
| `get_guidance_scale_embedding` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:483` | `def get_guidance_scale_embedding(self, w, embedding_dim, dtype)` |
| `get_image_condition_latents` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:826` | `def get_image_condition_latents(self, task_type, reference_image, height, width)` |
| `get_latent_size` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:874` | `def get_latent_size(self, video_length, height, width)` |
| `get_offloading_config` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1550` | `def get_offloading_config(memory_limitation)` |
| `get_task_mask` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:766` | `def get_task_mask(self, task_type, latent_target_length)` |
| `get_transformer_version` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1452` | `def get_transformer_version(resolution, task, cfg_distilled, step_distilled, sparse_attn)` |
| `get_vae_inference_config` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1566` | `def get_vae_inference_config(memory_limitation)` |
| `guidance_rescale` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:521` | `def guidance_rescale(self)` |
| `guidance_scale` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:517` | `def guidance_scale(self)` |
| `ideal_resolution` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1324` | `def ideal_resolution(self)` |
| `ideal_task` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1328` | `def ideal_task(self)` |
| `interrupt` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:544` | `def interrupt(self)` |
| `load_sr_transformer_upsampler` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1416` | `def load_sr_transformer_upsampler(cls, cached_folder, sr_version, transformer_dtype, device)` |
| `num_timesteps` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:540` | `def num_timesteps(self)` |
| `prepare_extra_func_kwargs` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:413` | `def prepare_extra_func_kwargs(self, func, kwargs)` |
| `prepare_latents` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:429` | `def prepare_latents(self, batch_size, num_channels_latents, latent_height, latent_width, video_length, dtype, device, ge` |
| `use_meanflow` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:1332` | `def use_meanflow(self)` |
| `vae_spatial_compression_ratio` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:861` | `def vae_spatial_compression_ratio(self)` |
| `vae_temporal_compression_ratio` | method | `hyvideo/pipelines/hunyuan_video_pipeline.py:868` | `def vae_temporal_compression_ratio(self)` |
| `BucketMap` | class | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:46` | `class BucketMap` |
| `HunyuanVideo_1_5_SR_Pipeline` | class | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:85` | `class HunyuanVideo_1_5_SR_Pipeline(HunyuanVideo_1_5_Pipeline)` |
| `HunyuanVideo_1_5_SR_PipelineOutput` | class | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:81` | `class HunyuanVideo_1_5_SR_PipelineOutput(BaseOutput)` |
| `__call__` | method | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:62` | `def __call__(self, lr_bucket)` |
| `__call__` | method | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:165` | `def __call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt, num_videos_per_prompt, ge` |
| `__init__` | method | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:49` | `def __init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)` |
| `__init__` | method | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:87` | `def __init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale, num_inference_steps` |
| `_prepare_lq_cond_latents` | method | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:148` | `def _prepare_lq_cond_latents(self, lq_latents)` |
| `add_noise_to_lq` | method | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:142` | `def add_noise_to_lq(self, lq_latents, strength)` |
| `expand_dims` | function | `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:42` | `def expand_dims(tensor, ndim)` |
| `rescale_noise_cfg` | function | `hyvideo/pipelines/pipeline_utils.py:86` | `def rescale_noise_cfg(noise_cfg, noise_pred_text, guidance_rescale)` |
| `retrieve_timesteps` | function | `hyvideo/pipelines/pipeline_utils.py:21` | `def retrieve_timesteps(scheduler, num_inference_steps, device, timesteps, sigmas)` |
| `FlowMatchDiscreteScheduler` | class | `hyvideo/schedulers/scheduling_flow_match_discrete.py:63` | `class FlowMatchDiscreteScheduler(SchedulerMixin, ConfigMixin)` |
| `FlowMatchDiscreteSchedulerOutput` | class | `hyvideo/schedulers/scheduling_flow_match_discrete.py:50` | `class FlowMatchDiscreteSchedulerOutput(BaseOutput)` |
| `__init__` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:86` | `def __init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift, n_token` |
| `__len__` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:291` | `def __len__(self)` |
| `_init_step_index` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:196` | `def _init_step_index(self, timestep)` |
| `_sigma_to_t` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:143` | `def _sigma_to_t(self, sigma)` |
| `begin_index` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:126` | `def begin_index(self)` |
| `flux_time_shift` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:214` | `def flux_time_shift(mu, sigma, t)` |
| `get_lin_function` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:208` | `def get_lin_function(x1, y1, x2, y2)` |
| `index_for_timestep` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:182` | `def index_for_timestep(self, timestep, schedule_timesteps)` |
| `scale_model_input` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:204` | `def scale_model_input(self, sample, timestep)` |
| `sd3_time_shift` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:217` | `def sd3_time_shift(self, t)` |
| `set_begin_index` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:133` | `def set_begin_index(self, begin_index)` |
| `set_timesteps` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:146` | `def set_timesteps(self, num_inference_steps, device, n_tokens)` |
| `step` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:220` | `def step(self, model_output, timestep, sample, generator, n_tokens, return_dict)` |
| `step_index` | method | `hyvideo/schedulers/scheduling_flow_match_discrete.py:119` | `def step_index(self)` |
| `SeqAllToAll4D` | class | `hyvideo/utils/communications.py:147` | `class SeqAllToAll4D(Function)` |
| `_AllGather` | class | `hyvideo/utils/communications.py:255` | `class _AllGather(Function)` |
| `_AllToAll` | class | `hyvideo/utils/communications.py:195` | `class _AllToAll(Function)` |
| `_Reduce_Scatter` | class | `hyvideo/utils/communications.py:239` | `class _Reduce_Scatter(Function)` |
| `_all_to_all` | method | `hyvideo/utils/communications.py:180` | `def _all_to_all(input_, world_size, group, scatter_dim, gather_dim)` |
| `_all_to_all_4D` | function | `hyvideo/utils/communications.py:29` | `def _all_to_all_4D(input, scatter_idx, gather_idx, group)` |
| `all_gather` | method | `hyvideo/utils/communications.py:304` | `def all_gather(input_, dim, group)` |
| `all_to_all` | method | `hyvideo/utils/communications.py:233` | `def all_to_all(input_, group, scatter_dim, gather_dim)` |
| `all_to_all_4D` | method | `hyvideo/utils/communications.py:174` | `def all_to_all_4D(input_, group, scatter_dim, gather_dim)` |
| `backward` | method | `hyvideo/utils/communications.py:163` | `def backward(ctx)` |
| `backward` | method | `hyvideo/utils/communications.py:217` | `def backward(ctx, grad_output)` |
| `backward` | method | `hyvideo/utils/communications.py:251` | `def backward(ctx, grad_output)` |
| `backward` | method | `hyvideo/utils/communications.py:283` | `def backward(ctx, grad_output)` |
| `broadcast` | function | `hyvideo/utils/communications.py:24` | `def broadcast(input_, group)` |
| `forward` | method | `hyvideo/utils/communications.py:149` | `def forward(ctx, group, input, scatter_idx, gather_idx)` |
| `forward` | method | `hyvideo/utils/communications.py:206` | `def forward(ctx, input_, process_group, scatter_dim, gather_dim)` |
| `forward` | method | `hyvideo/utils/communications.py:242` | `def forward(ctx, op, group, tensor)` |
| `forward` | method | `hyvideo/utils/communications.py:264` | `def forward(ctx, input_, dim, group)` |
| `generate_crop_size_list` | function | `hyvideo/utils/data_utils.py:61` | `def generate_crop_size_list(base_size, patch_size, max_ratio)` |
| `get_closest_ratio` | function | `hyvideo/utils/data_utils.py:38` | `def get_closest_ratio(height, width, ratios, buckets)` |
| `resize_and_center_crop` | function | `hyvideo/utils/data_utils.py:20` | `def resize_and_center_crop(image, target_width, target_height)` |
| `flash_attn_no_pad` | function | `hyvideo/utils/flash_attn_no_pad.py:20` | `def flash_attn_no_pad(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)` |
| `flash_attn_no_pad_v3` | function | `hyvideo/utils/flash_attn_no_pad.py:52` | `def flash_attn_no_pad_v3(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)` |
| `decorator` | function | `hyvideo/utils/infer_utils.py:20` | `def decorator(func)` |
| `torch_compile_wrapper` | function | `hyvideo/utils/infer_utils.py:19` | `def torch_compile_wrapper()` |
| `wrapper` | function | `hyvideo/utils/infer_utils.py:21` | `def wrapper(self)` |
| `merge_tensor_by_mask` | function | `hyvideo/utils/multitask_utils.py:45` | `def merge_tensor_by_mask(tensor_1, tensor_2, mask, dim)` |
| `numpy_to_pil` | function | `hyvideo/utils/multitask_utils.py:23` | `def numpy_to_pil(images)` |
| `DeepSeekClient` | class | `hyvideo/utils/rewrite/clients.py:37` | `class DeepSeekClient(object)` |
| `NonStreamResponse` | class | `hyvideo/utils/rewrite/clients.py:29` | `class NonStreamResponse(object)` |
| `QwenClient` | class | `hyvideo/utils/rewrite/clients.py:84` | `class QwenClient(object)` |
| `QwenVLClient` | class | `hyvideo/utils/rewrite/clients.py:133` | `class QwenVLClient(object)` |
| `__init__` | method | `hyvideo/utils/rewrite/clients.py:30` | `def __init__(self)` |
| `__init__` | method | `hyvideo/utils/rewrite/clients.py:38` | `def __init__(self, key_id, key_secret)` |
| `__init__` | method | `hyvideo/utils/rewrite/clients.py:85` | `def __init__(self, base_url, model_name)` |
| `__init__` | method | `hyvideo/utils/rewrite/clients.py:135` | `def __init__(self, base_url, model_name)` |
| `_deserialize` | method | `hyvideo/utils/rewrite/clients.py:33` | `def _deserialize(self, obj)` |
| `_encode_image_to_base64` | method | `hyvideo/utils/rewrite/clients.py:141` | `def _encode_image_to_base64(self, image_path, max_dimension)` |
| `qwen_api_call` | method | `hyvideo/utils/rewrite/clients.py:90` | `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens)` |
| `qwen_api_call` | method | `hyvideo/utils/rewrite/clients.py:176` | `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens, img_path)` |
| `run_single_recaption` | method | `hyvideo/utils/rewrite/clients.py:51` | `def run_single_recaption(self, system_prompt, input_prompt)` |
| `run_single_recaption` | method | `hyvideo/utils/rewrite/clients.py:128` | `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens)` |
| `run_single_recaption` | method | `hyvideo/utils/rewrite/clients.py:246` | `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens, img_path)` |
| `i2v_rewrite` | function | `hyvideo/utils/rewrite/rewrite_utils.py:40` | `def i2v_rewrite(user_input, img_path, rewrite_client)` |
| `run_prompt_rewrite` | function | `hyvideo/utils/rewrite/rewrite_utils.py:63` | `def run_prompt_rewrite(user_prompt, img_path, task_type)` |
| `t2v_rewrite` | function | `hyvideo/utils/rewrite/rewrite_utils.py:22` | `def t2v_rewrite(user_prompt, rewrite_client)` |
| `DummyDataset` | class | `train.py:1108` | `class DummyDataset` |
| `HunyuanVideoTrainer` | class | `train.py:347` | `class HunyuanVideoTrainer` |
| `LinearInterpolationSchedule` | class | `train.py:186` | `class LinearInterpolationSchedule` |
| `SNRType` | class | `train.py:91` | `class SNRType(str, Enum)` |
| `TimestepSampler` | class | `train.py:204` | `class TimestepSampler` |
| `TrainingConfig` | class | `train.py:124` | `class TrainingConfig` |
| `__getitem__` | method | `train.py:1115` | `def __getitem__(self, idx)` |
| `__init__` | method | `train.py:188` | `def __init__(self, T)` |
| `__init__` | method | `train.py:209` | `def __init__(self, T, device, snr_type)` |
| `__init__` | method | `train.py:348` | `def __init__(self, config)` |
| `__init__` | method | `train.py:1109` | `def __init__(self, size)` |
| `__len__` | method | `train.py:1112` | `def __len__(self)` |
| `_apply_fsdp` | method | `train.py:498` | `def _apply_fsdp(self)` |
| `_apply_gradient_checkpointing` | method | `train.py:529` | `def _apply_gradient_checkpointing(self)` |
| `_apply_lora` | method | `train.py:464` | `def _apply_lora(self)` |
| `_build_models` | method | `train.py:412` | `def _build_models(self)` |
| `_build_optimizer` | method | `train.py:565` | `def _build_optimizer(self)` |
| `_check_interval` | method | `train.py:219` | `def _check_interval(self, eval)` |
| `_set_seed` | method | `train.py:406` | `def _set_seed(self, seed)` |
| `broadcast_object` | method | `train.py:287` | `def broadcast_object(obj, src, group, device, group_src)` |
| `broadcast_tensor` | method | `train.py:305` | `def broadcast_tensor(tensor, src, group, async_op, group_src)` |
| `create_dummy_dataloader` | method | `train.py:1047` | `def create_dummy_dataloader(config)` |
| `encode_byt5` | method | `train.py:608` | `def encode_byt5(self, text_ids, attention_mask)` |
| `encode_images` | method | `train.py:615` | `def encode_images(self, images)` |
| `encode_text` | method | `train.py:592` | `def encode_text(self, prompts, data_type)` |
| `encode_vae` | method | `train.py:625` | `def encode_vae(self, images)` |
| `forward` | method | `train.py:191` | `def forward(self, x0, x1, t)` |
| `get_condition` | method | `train.py:641` | `def get_condition(self, latents, task_type)` |
| `is_src` | method | `train.py:278` | `def is_src(src, group_src, group)` |
| `load_checkpoint` | method | `train.py:901` | `def load_checkpoint(self, checkpoint_path)` |
| `load_pretrained_lora` | method | `train.py:892` | `def load_pretrained_lora(self, lora_dir)` |
| `main` | method | `train.py:1144` | `def main()` |
| `non_reentrant_wrapper` | method | `train.py:547` | `def non_reentrant_wrapper(module)` |
| `prepare_batch` | method | `train.py:671` | `def prepare_batch(self, batch)` |
| `sample` | method | `train.py:226` | `def sample(self, batch_size, device)` |
| `sample_task` | method | `train.py:654` | `def sample_task(self, data_type)` |
| `save_checkpoint` | method | `train.py:828` | `def save_checkpoint(self, step)` |
| `save_video` | method | `train.py:114` | `def save_video(video, path)` |
| `selective_checkpointing` | method | `train.py:553` | `def selective_checkpointing(submodule)` |
| `str_to_bool` | method | `train.py:98` | `def str_to_bool(value)` |
| `sync_tensor_for_sp` | method | `train.py:333` | `def sync_tensor_for_sp(tensor, sp_group)` |
| `timestep_transform` | method | `train.py:269` | `def timestep_transform(timesteps, T, shift)` |
| `train` | method | `train.py:959` | `def train(self, dataloader)` |
| `train_step` | method | `train.py:776` | `def train_step(self, batch)` |
| `validate` | method | `train.py:1001` | `def validate(self, step)` |
