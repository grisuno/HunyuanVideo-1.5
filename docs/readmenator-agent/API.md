# API

## generate.py
Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `save_video` (function) `generate.py:42` `def save_video(video, path)`
- `rank0_log` (function) `generate.py:50` `def rank0_log(message, level)`
- `save_config` (function) `generate.py:54` `def save_config(args, output_path, task, transformer_version)`
- `str_to_bool` (function) `generate.py:81` `def str_to_bool(value)` -- Convert string to boolean, supporting true/false, 1/0, yes/no.
- `load_checkpoint_to_transformer` (function) `generate.py:96` `def load_checkpoint_to_transformer(pipe, checkpoint_path)`
- `load_lora_adapter` (function) `generate.py:112` `def load_lora_adapter(pipe, lora_path)`
- `generate_video` (function) `generate.py:128` `def generate_video(args)`
- `main` (function) `generate.py:274` `def main()`

## hyvideo/__init__.py
Depends on: `hyvideo/commons/__init__.py`
- `find_free_port` (function) `hyvideo/__init__.py:25` `def find_free_port()`

## hyvideo/commons/__init__.py
Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
- `parse` (function) `hyvideo/commons/__init__.py:26` `def parse(x)`
- `is_flash2_available` (function) `hyvideo/commons/__init__.py:142` `def is_flash2_available()`
- `is_flash3_available` (function) `hyvideo/commons/__init__.py:149` `def is_flash3_available()`
- `is_flash_available` (function) `hyvideo/commons/__init__.py:156` `def is_flash_available()`
- `is_sparse_attn_supported` (function) `hyvideo/commons/__init__.py:159` `def is_sparse_attn_supported()`
- `is_sparse_attn_available` (function) `hyvideo/commons/__init__.py:162` `def is_sparse_attn_available()`
- `is_angelslim_available` (function) `hyvideo/commons/__init__.py:171` `def is_angelslim_available()`
- `maybe_fallback_attn_mode` (function) `hyvideo/commons/__init__.py:178` `def maybe_fallback_attn_mode(attn_mode)` -- Determine the final attention mode based on configuration and availability.
- `auto_offload_model` (function) `hyvideo/commons/__init__.py:229` `def auto_offload_model(models, device, enabled)`
- `get_gpu_memory` (function) `hyvideo/commons/__init__.py:243` `def get_gpu_memory(device)`
- `get_rank` (function) `hyvideo/commons/__init__.py:254` `def get_rank()`

## hyvideo/commons/infer_state.py
Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `InferState.parse_range` (method) `hyvideo/commons/infer_state.py:42` `def parse_range(value)`
- `InferState.initialize_infer_state` (method) `hyvideo/commons/infer_state.py:49` `def initialize_infer_state(args)`
- `InferState.get_infer_state` (method) `hyvideo/commons/infer_state.py:87` `def get_infer_state()`

## hyvideo/commons/parallel_states.py
Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`
- `ParallelDims.build_mesh` (method) `hyvideo/commons/parallel_states.py:37` `def build_mesh(self, device_type)`
- `ParallelDims.sp_enabled` (method) `hyvideo/commons/parallel_states.py:68` `def sp_enabled(self)`
- `ParallelDims.sp_mesh` (method) `hyvideo/commons/parallel_states.py:72` `def sp_mesh(self)`
- `ParallelDims.dp_enabled` (method) `hyvideo/commons/parallel_states.py:76` `def dp_enabled(self)`
- `ParallelDims.initialize_parallel_state` (method) `hyvideo/commons/parallel_states.py:81` `def initialize_parallel_state(sp, dp_replicate)`
- `ParallelDims.get_parallel_state` (method) `hyvideo/commons/parallel_states.py:89` `def get_parallel_state()`

## hyvideo/models/autoencoders/hunyuanvideo_15_vae.py
Depends on: `hyvideo/commons/parallel_states.py`
Imported by: `hyvideo/models/transformers/modules/upsample.py`
- `DecoderOutput.swish` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:45` `def swish(x, inplace)` -- Applies the swish activation function (SiLU) with optional inplace support.
- `DecoderOutput.forward_with_checkpointing` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:50` `def forward_with_checkpointing(module)` -- Forward with optional gradient checkpointing.
- `DecoderOutput.create_custom_forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:52` `def create_custom_forward(module)`
- `DecoderOutput.custom_forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:53` `def custom_forward()`
- `PatchCausalConv3d.find_split_indices` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:67` `def find_split_indices(self, seq_len, part_num)`
- `PatchCausalConv3d.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:86` `def forward(self, input)`
- `RMS_norm.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:113` `def __init__(self, dim, channel_first, images, bias)`
- `RMS_norm.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:123` `def forward(self, x)`
- `CausalConv3d.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:132` `def __init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)`
- `CausalConv3d.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:158` `def forward(self, x)`
- `CausalConv3d.prepare_causal_attention_mask` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:163` `def prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)` -- Prepare a causal attention mask for 3D videos.
- `AttnBlock.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:189` `def __init__(self, in_channels)`
- `AttnBlock.attention` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:200` `def attention(self, h_)`
- `AttnBlock.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:215` `def forward(self, x)`
- `ResnetBlock.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:222` `def __init__(self, in_channels, out_channels)`
- `ResnetBlock.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:236` `def forward(self, x)`
- `Downsample.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:253` `def __init__(self, in_channels, out_channels, add_temporal_downsample)`
- `Downsample.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:261` `def forward(self, x)`
- `Upsample.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:296` `def __init__(self, in_channels, out_channels, add_temporal_upsample)`
- `Upsample.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:303` `def forward(self, x)`
- `Encoder.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:334` `def __init__(self, in_channels, z_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal...`
- `Encoder.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:386` `def forward(self, x)` -- Forward pass through the encoder.
- `Decoder.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:416` `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal...`
- `Decoder.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:468` `def forward(self, z)` -- Forward pass through the decoder.
- `AutoencoderKLConv3D.__init__` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:500` `def __init__(self, in_channels, out_channels, latent_channels, block_out_channels, layers_per_block...`
- `AutoencoderKLConv3D.set_tile_sample_min_size` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:554` `def set_tile_sample_min_size(self, sample_size, tile_overlap_factor)`
- `AutoencoderKLConv3D.enable_temporal_tiling` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:569` `def enable_temporal_tiling(self, use_tiling)`
- `AutoencoderKLConv3D.disable_temporal_tiling` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:573` `def disable_temporal_tiling(self)`
- `AutoencoderKLConv3D.enable_spatial_tiling` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:576` `def enable_spatial_tiling(self, use_tiling)`
- `AutoencoderKLConv3D.disable_spatial_tiling` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:579` `def disable_spatial_tiling(self)`
- `AutoencoderKLConv3D.enable_tiling` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:582` `def enable_tiling(self, use_tiling)`
- `AutoencoderKLConv3D.disable_tiling` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:585` `def disable_tiling(self)`
- `AutoencoderKLConv3D.enable_slicing` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:588` `def enable_slicing(self)`
- `AutoencoderKLConv3D.disable_slicing` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:591` `def disable_slicing(self)`
- `AutoencoderKLConv3D.blend_h` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:594` `def blend_h(self, a, b, blend_extent)` -- Blend tensor b horizontally into a at blend_extent region.
- `AutoencoderKLConv3D.blend_v` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:601` `def blend_v(self, a, b, blend_extent)` -- Blend tensor b vertically into a at blend_extent region.
- `AutoencoderKLConv3D.blend_t` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:608` `def blend_t(self, a, b, blend_extent)` -- Blend tensor b temporally into a at blend_extent region.
- `AutoencoderKLConv3D.spatial_tiled_encode` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:615` `def spatial_tiled_encode(self, x)` -- Tiled spatial encoding for large inputs via overlapping.
- `AutoencoderKLConv3D.temporal_tiled_encode` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:643` `def temporal_tiled_encode(self, x)` -- Tiled temporal encoding for large video sequences.
- `AutoencoderKLConv3D.enable_tile_parallelism` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:671` `def enable_tile_parallelism(self)`
- `AutoencoderKLConv3D.disable_tile_parallelism` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:674` `def disable_tile_parallelism(self)`
- `AutoencoderKLConv3D.tile_parallel_spatial_tiled_decode` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:677` `def tile_parallel_spatial_tiled_decode(self, z)`
- `AutoencoderKLConv3D.spatial_tiled_decode` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:772` `def spatial_tiled_decode(self, z)`
- `AutoencoderKLConv3D.temporal_tiled_decode` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:803` `def temporal_tiled_decode(self, z)` -- Tiled temporal decoding for long sequence latents.
- `AutoencoderKLConv3D.encode` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:833` `def encode(self, x, return_dict)`
- `AutoencoderKLConv3D.decode` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:856` `def decode(self, z, return_dict, generator)`
- `AutoencoderKLConv3D.forward` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:876` `def forward(self, sample, sample_posterior, return_posterior, return_dict)` -- Forward autoencoder pass.
- `AutoencoderKLConv3D.memory_efficient_context` (method) `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:890` `def memory_efficient_context(self)`

## hyvideo/models/text_encoders/__init__.py
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
- `use_default` (function) `hyvideo/models/text_encoders/__init__.py:32` `def use_default(value, default)` -- Utility: return value if not None, else default.
- `load_text_encoder` (function) `hyvideo/models/text_encoders/__init__.py:84` `def load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)`
- `load_tokenizer` (function) `hyvideo/models/text_encoders/__init__.py:114` `def load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)`
- `TextEncoder.__init__` (method) `hyvideo/models/text_encoders/__init__.py:155` `def __init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type...`
- `TextEncoder.dtype` (method) `hyvideo/models/text_encoders/__init__.py:245` `def dtype(self)`
- `TextEncoder.device` (method) `hyvideo/models/text_encoders/__init__.py:249` `def device(self)`
- `TextEncoder.apply_text_to_template` (method) `hyvideo/models/text_encoders/__init__.py:256` `def apply_text_to_template(text, template, prevent_empty_text)` -- Apply text to template.
- `TextEncoder.calculate_crop_start` (method) `hyvideo/models/text_encoders/__init__.py:281` `def calculate_crop_start(self, tokenized_input)` -- Automatically calculate the crop_start position based on identifying user tokens.
- `TextEncoder.text2tokens` (method) `hyvideo/models/text_encoders/__init__.py:316` `def text2tokens(self, text, data_type, max_length)` -- Tokenize the input text.
- `TextEncoder.encode` (method) `hyvideo/models/text_encoders/__init__.py:415` `def encode(self, batch_encoding, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer...` -- Args: batch_encoding (dict): Batch encoding from tokenizer. use_attention_mask (bool): Whether to use attention mask.
- `TextEncoder.forward` (method) `hyvideo/models/text_encoders/__init__.py:487` `def forward(self, text, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts)`

## hyvideo/models/text_encoders/byT5/__init__.py
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `load_glyph_byT5_v2` (function) `hyvideo/models/text_encoders/byT5/__init__.py:23` `def load_glyph_byT5_v2(args, device)` -- Loads ByT5 tokenizer and encoder model for glyph encoding.
- `create_byt5` (function) `hyvideo/models/text_encoders/byT5/__init__.py:43` `def create_byt5(args, device)` -- Create ByT5 tokenizer and encoder, load weights if provided.
- `add_special_token` (function) `hyvideo/models/text_encoders/byT5/__init__.py:89` `def add_special_token(tokenizer, text_encoder, add_color, add_font, color_ann_path, font_ann_path, multilingual)` -- Add special tokens for color and font to tokenizer and text encoder.
- `load_byt5_and_byt5_tokenizer` (function) `hyvideo/models/text_encoders/byT5/__init__.py:131` `def load_byt5_and_byt5_tokenizer(byt5_name, special_token, color_special_token, font_special_token, color_ann_path...` -- Load ByT5 encoder and tokenizer from Huggingface, and add special tokens if needed.
- `ByT5Mapper.__init__` (method) `hyvideo/models/text_encoders/byT5/__init__.py:199` `def __init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)`
- `ByT5Mapper.forward` (method) `hyvideo/models/text_encoders/byT5/__init__.py:210` `def forward(self, x)` -- Forward pass for ByT5Mapper.

## hyvideo/models/text_encoders/byT5/format_prompt.py
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `closest_color` (function) `hyvideo/models/text_encoders/byT5/format_prompt.py:20` `def closest_color(requested_color)`
- `convert_rgb_to_names` (function) `hyvideo/models/text_encoders/byT5/format_prompt.py:34` `def convert_rgb_to_names(rgb_tuple)`
- `MultilingualPromptFormat.__init__` (method) `hyvideo/models/text_encoders/byT5/format_prompt.py:46` `def __init__(self, font_path, color_path)`
- `MultilingualPromptFormat.format_prompt` (method) `hyvideo/models/text_encoders/byT5/format_prompt.py:56` `def format_prompt(self, texts, styles)` -- Text "{text}" in {color}, {type}.

## hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py
Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
- `MMDoubleStreamBlock.__init__` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:47` `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type...`
- `MMDoubleStreamBlock.enable_deterministic` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:111` `def enable_deterministic(self)`
- `MMDoubleStreamBlock.disable_deterministic` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:114` `def disable_deterministic(self)`
- `MMDoubleStreamBlock.forward` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:117` `def forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)`
- `MMSingleStreamBlock.__init__` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:210` `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type...`
- `MMSingleStreamBlock.enable_deterministic` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:255` `def enable_deterministic(self)`
- `MMSingleStreamBlock.disable_deterministic` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:258` `def disable_deterministic(self)`
- `MMSingleStreamBlock.forward` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:261` `def forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)` -- Forward pass for the single stream block.
- `HunyuanVideo_1_5_DiffusionTransformer.__init__` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:351` `def __init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio...`
- `HunyuanVideo_1_5_DiffusionTransformer.load_hunyuan_state_dict` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:563` `def load_hunyuan_state_dict(self, model_path)`
- `HunyuanVideo_1_5_DiffusionTransformer.enable_deterministic` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:601` `def enable_deterministic(self)`
- `HunyuanVideo_1_5_DiffusionTransformer.disable_deterministic` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:607` `def disable_deterministic(self)`
- `HunyuanVideo_1_5_DiffusionTransformer.get_rotary_pos_embed` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:613` `def get_rotary_pos_embed(self, rope_sizes)`
- `HunyuanVideo_1_5_DiffusionTransformer.reorder_txt_token` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:631` `def reorder_txt_token(self, byt5_txt, txt, byt5_text_mask, text_mask, zero_feat, is_reorder)`
- `HunyuanVideo_1_5_DiffusionTransformer.forward` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:667` `def forward(self, hidden_states, timestep, text_states, text_states_2, encoder_attention_mask, timestep_r...`
- `HunyuanVideo_1_5_DiffusionTransformer.unpatchify` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:867` `def unpatchify(self, x, t, h, w)` -- Unpatchify a tensorized input back to frame format.
- `HunyuanVideo_1_5_DiffusionTransformer.set_attn_mode` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:888` `def set_attn_mode(self, attn_mode)`
- `HunyuanVideo_1_5_DiffusionTransformer.save_lora_adapter` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:896` `def save_lora_adapter(self, save_directory, adapter_name, upcast_before_saving, safe_serialization, weight_name)` -- Save the LoRA parameters corresponding to the underlying model.
- `HunyuanVideo_1_5_DiffusionTransformer.save_function` (method) `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:943` `def save_function(weights, filename)`

## hyvideo/models/transformers/modules/activation_layers.py
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`
- `get_activation_layer` (function) `hyvideo/models/transformers/modules/activation_layers.py:20` `def get_activation_layer(act_type)` -- get activation layer

## hyvideo/models/transformers/modules/attention.py
Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`
- `attention` (function) `hyvideo/models/transformers/modules/attention.py:50` `def attention(q, k, v, drop_rate, attn_mask, causal, attn_mode)` -- Compute attention using flash_attn_no_pad or torch scaled_dot_product_attention.
- `parallel_attention` (function) `hyvideo/models/transformers/modules/attention.py:112` `def parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
- `sequence_parallel_attention` (function) `hyvideo/models/transformers/modules/attention.py:120` `def sequence_parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
- `shrink_head` (function) `hyvideo/models/transformers/modules/attention.py:145` `def shrink_head(encoder_state, dim)`
- `score_mod` (function) `hyvideo/models/transformers/modules/attention.py:188` `def score_mod(score, b, h, q_idx, kv_idx)`
- `get_image_tile` (function) `hyvideo/models/transformers/modules/attention.py:231` `def get_image_tile(tile_size)`

## hyvideo/models/transformers/modules/embed_layers.py
Depends on: `hyvideo/commons/__init__.py`
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`
- `PatchEmbed.__init__` (method) `hyvideo/models/transformers/modules/embed_layers.py:37` `def __init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer...`
- `PatchEmbed.forward` (method) `hyvideo/models/transformers/modules/embed_layers.py:82` `def forward(self, x)`
- `TextProjection.__init__` (method) `hyvideo/models/transformers/modules/embed_layers.py:97` `def __init__(self, in_channels, hidden_size, act_layer, dtype, device)`
- `TextProjection.forward` (method) `hyvideo/models/transformers/modules/embed_layers.py:114` `def forward(self, caption)`
- `VisionProjection.__init__` (method) `hyvideo/models/transformers/modules/embed_layers.py:124` `def __init__(self, input_dim, output_dim)`
- `VisionProjection.forward` (method) `hyvideo/models/transformers/modules/embed_layers.py:136` `def forward(self, vision_embeds)`
- `ClipVisionProjection.__init__` (method) `hyvideo/models/transformers/modules/embed_layers.py:140` `def __init__(self, in_channels, out_channels)`
- `ClipVisionProjection.forward` (method) `hyvideo/models/transformers/modules/embed_layers.py:147` `def forward(self, x)`
- `ClipVisionProjection.timestep_embedding` (method) `hyvideo/models/transformers/modules/embed_layers.py:151` `def timestep_embedding(t, dim, max_period)` -- Create sinusoidal timestep embeddings.
- `TimestepEmbedder.__init__` (method) `hyvideo/models/transformers/modules/embed_layers.py:183` `def __init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)`
- `TimestepEmbedder.forward` (method) `hyvideo/models/transformers/modules/embed_layers.py:208` `def forward(self, t)`

## hyvideo/models/transformers/modules/mlp_layers.py
Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`
- `MLP.__init__` (method) `hyvideo/models/transformers/modules/mlp_layers.py:32` `def __init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device...`
- `MLP.forward` (method) `hyvideo/models/transformers/modules/mlp_layers.py:60` `def forward(self, x)`
- `LinearWarpforSingle.__init__` (method) `hyvideo/models/transformers/modules/mlp_layers.py:71` `def __init__(self, in_dim, out_dim, bias, device, dtype)`
- `LinearWarpforSingle.forward` (method) `hyvideo/models/transformers/modules/mlp_layers.py:76` `def forward(self, x, y)`
- `MLPEmbedder.__init__` (method) `hyvideo/models/transformers/modules/mlp_layers.py:85` `def __init__(self, in_dim, hidden_dim, device, dtype)`
- `MLPEmbedder.forward` (method) `hyvideo/models/transformers/modules/mlp_layers.py:92` `def forward(self, x)`
- `FinalLayer.__init__` (method) `hyvideo/models/transformers/modules/mlp_layers.py:99` `def __init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)`
- `FinalLayer.forward` (method) `hyvideo/models/transformers/modules/mlp_layers.py:133` `def forward(self, x, c)`

## hyvideo/models/transformers/modules/modulate_layers.py
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`
- `ModulateDiT.__init__` (method) `hyvideo/models/transformers/modules/modulate_layers.py:26` `def __init__(self, hidden_size, factor, act_layer, dtype, device)`
- `ModulateDiT.forward` (method) `hyvideo/models/transformers/modules/modulate_layers.py:42` `def forward(self, x)`
- `ModulateDiT.modulate` (method) `hyvideo/models/transformers/modules/modulate_layers.py:46` `def modulate(x, shift, scale)` -- modulate by shift and scale
- `ModulateDiT.apply_gate` (method) `hyvideo/models/transformers/modules/modulate_layers.py:67` `def apply_gate(x, gate, tanh)` -- AI is creating summary for apply_gate
- `ModulateDiT.ckpt_wrapper` (method) `hyvideo/models/transformers/modules/modulate_layers.py:86` `def ckpt_wrapper(module)`
- `ModulateDiT.ckpt_forward` (method) `hyvideo/models/transformers/modules/modulate_layers.py:87` `def ckpt_forward()`

## hyvideo/models/transformers/modules/norm_layers.py
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`
- `RMSNorm.__init__` (method) `hyvideo/models/transformers/modules/norm_layers.py:22` `def __init__(self, dim, elementwise_affine, eps, device, dtype)` -- Initialize the RMSNorm normalization layer.
- `RMSNorm.reset_parameters` (method) `hyvideo/models/transformers/modules/norm_layers.py:61` `def reset_parameters(self)`
- `RMSNorm.forward` (method) `hyvideo/models/transformers/modules/norm_layers.py:65` `def forward(self, x)` -- Forward pass through the RMSNorm layer.
- `RMSNorm.get_norm_layer` (method) `hyvideo/models/transformers/modules/norm_layers.py:82` `def get_norm_layer(norm_layer)` -- Get the normalization layer.

## hyvideo/models/transformers/modules/posemb_layers.py
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`
- `get_meshgrid_nd` (function) `hyvideo/models/transformers/modules/posemb_layers.py:32` `def get_meshgrid_nd(start)` -- Get n-D meshgrid with start, stop and num.
- `reshape_for_broadcast` (function) `hyvideo/models/transformers/modules/posemb_layers.py:83` `def reshape_for_broadcast(freqs_cis, x, head_first)` -- Reshape frequency tensor for broadcasting it with another tensor.
- `rotate_half` (function) `hyvideo/models/transformers/modules/posemb_layers.py:151` `def rotate_half(x)`
- `apply_rotary_emb` (function) `hyvideo/models/transformers/modules/posemb_layers.py:158` `def apply_rotary_emb(xq, xk, freqs_cis, head_first)` -- Apply rotary embeddings to input tensors using the given frequency tensor.
- `get_nd_rotary_pos_embed` (function) `hyvideo/models/transformers/modules/posemb_layers.py:210` `def get_nd_rotary_pos_embed(rope_dim_list, start)` -- This is a n-d version of precompute_freqs_cis, which is a RoPE for tokens with n-d structure.
- `get_1d_rotary_pos_embed` (function) `hyvideo/models/transformers/modules/posemb_layers.py:281` `def get_1d_rotary_pos_embed(dim, pos, theta, use_real, theta_rescale_factor, interpolation_factor)` -- Precompute the frequency tensor for complex exponential (cis) with given dimensions.

## hyvideo/models/transformers/modules/ssta_attention.py
Imported by: `hyvideo/models/transformers/modules/attention.py`
- `tile` (function) `hyvideo/models/transformers/modules/ssta_attention.py:23` `def tile(x, canvas_thw, tile_thw, sp_size)` -- Rearrange tensor into tiles for block-based attention.
- `untile` (function) `hyvideo/models/transformers/modules/ssta_attention.py:53` `def untile(x, canvas_thw, tile_thw, sp_size)` -- Reverse the tiling operation to restore original tensor layout.
- `get_tile_t_h_w` (function) `hyvideo/models/transformers/modules/ssta_attention.py:82` `def get_tile_t_h_w(tile_id, tile_thw_dim)` -- Extract temporal, height, and width indices from a flattened tile ID.
- `importance_sampling` (function) `hyvideo/models/transformers/modules/ssta_attention.py:90` `def importance_sampling(q, k, topk, threshold, lambda_, adaptive_pool)` -- Select top-k blocks based on importance scores considering both similarity and redundancy.
- `similarity_sampling` (function) `hyvideo/models/transformers/modules/ssta_attention.py:126` `def similarity_sampling(q, k, topk, threshold, block_num, adaptive_pool, temperature)` -- Select top-k blocks based on similarity scores between query and key averages.
- `create_moba_3d_mask` (function) `hyvideo/models/transformers/modules/ssta_attention.py:170` `def create_moba_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, add_text_mask, threshold...` -- Create MOBA (Mixture of Block Attention) 3D mask for sparse attention.
- `get_block_avg_feat` (function) `hyvideo/models/transformers/modules/ssta_attention.py:216` `def get_block_avg_feat(x, adaptive_pool, pooling_type)`
- `create_sta_3d_mask_optimize` (function) `hyvideo/models/transformers/modules/ssta_attention.py:323` `def create_sta_3d_mask_optimize(canvas_thw, tile_thw, kernel_thw)` -- Create optimized STA (Spatio-Temporal Attention) 3D mask using vectorized operations.
- `create_sta_3d_mask` (function) `hyvideo/models/transformers/modules/ssta_attention.py:374` `def create_sta_3d_mask(canvas_thw, tile_thw, kernel_thw, text_block_num)` -- Create STA (Spatio-Temporal Attention) 3D mask.
- `create_ssta_3d_mask` (function) `hyvideo/models/transformers/modules/ssta_attention.py:404` `def create_ssta_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, threshold, lambda_, text_mask...` -- Create SSTA (Sparse Spatio-Temporal Attention) 3D mask combining STA and MOBA masks.
- `ssta_3d_attention` (function) `hyvideo/models/transformers/modules/ssta_attention.py:465` `def ssta_3d_attention(all_q, all_k, all_v, canvas_thw, topk, tile_thw, kernel_thw, text_len, sparse_type, threshold...` -- Sparse Spatio-Temporal Attention (SSTA) 3D attention mechanism.

## hyvideo/models/transformers/modules/token_refiner.py
Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`
- `IndividualTokenRefinerBlock.__init__` (method) `hyvideo/models/transformers/modules/token_refiner.py:50` `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type...`
- `IndividualTokenRefinerBlock.forward` (method) `hyvideo/models/transformers/modules/token_refiner.py:98` `def forward(self, x, c, attn_mask)` -- Forward pass for IndividualTokenRefinerBlock.
- `IndividualTokenRefiner.__init__` (method) `hyvideo/models/transformers/modules/token_refiner.py:145` `def __init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type...`
- `IndividualTokenRefiner.forward` (method) `hyvideo/models/transformers/modules/token_refiner.py:178` `def forward(self, x, c, mask)` -- Forward pass for IndividualTokenRefiner.
- `SingleTokenRefiner.__init__` (method) `hyvideo/models/transformers/modules/token_refiner.py:222` `def __init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm...`
- `SingleTokenRefiner.forward` (method) `hyvideo/models/transformers/modules/token_refiner.py:256` `def forward(self, x, t, mask)` -- Forward pass for SingleTokenRefiner.

## hyvideo/models/transformers/modules/upsample.py
Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
- `SRResidualCausalBlock3D.__init__` (method) `hyvideo/models/transformers/modules/upsample.py:56` `def __init__(self, channels)`
- `SRResidualCausalBlock3D.forward` (method) `hyvideo/models/transformers/modules/upsample.py:66` `def forward(self, x)`
- `SRTo720pUpsampler.__init__` (method) `hyvideo/models/transformers/modules/upsample.py:73` `def __init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)`
- `SRTo720pUpsampler.forward` (method) `hyvideo/models/transformers/modules/upsample.py:89` `def forward(self, x)`
- `SRTo1080pUpsampler.__init__` (method) `hyvideo/models/transformers/modules/upsample.py:103` `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)`
- `SRTo1080pUpsampler.forward` (method) `hyvideo/models/transformers/modules/upsample.py:137` `def forward(self, z, target_shape)` -- Args: target_shape: (H, W)

## hyvideo/models/vision_encoder/__init__.py
Depends on: `hyvideo/commons/__init__.py`
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `use_default` (function) `hyvideo/models/vision_encoder/__init__.py:29` `def use_default(value, default)`
- `load_vision_encoder` (function) `hyvideo/models/vision_encoder/__init__.py:33` `def load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)`
- `load_image_processor` (function) `hyvideo/models/vision_encoder/__init__.py:63` `def load_image_processor(processor_type, processor_path, logger)`
- `VisionEncoder.__init__` (method) `hyvideo/models/vision_encoder/__init__.py:105` `def __init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type...`
- `VisionEncoder.encode_latents_to_images` (method) `hyvideo/models/vision_encoder/__init__.py:152` `def encode_latents_to_images(self, latents, vae, reorg_token)` -- Convert latents to images using VAE decoder.
- `VisionEncoder.encode_images` (method) `hyvideo/models/vision_encoder/__init__.py:179` `def encode_images(self, images)` -- Encode images using the vision encoder.
- `VisionEncoder.encode_latents` (method) `hyvideo/models/vision_encoder/__init__.py:205` `def encode_latents(self, latents, vae, reorg_token)` -- Encode latents by first converting to images, then encoding.
- `VisionEncoder.forward` (method) `hyvideo/models/vision_encoder/__init__.py:225` `def forward(self, images)` -- Forward pass for direct image encoding.

## hyvideo/optim/muon.py
Imported by: `train.py`
- `zeropower_via_newtonschulz5` (function) `hyvideo/optim/muon.py:17` `def zeropower_via_newtonschulz5(G, steps)` -- Newton-Schulz iteration to compute the zeroth power / orthogonalization of G.
- `Muon.__init__` (method) `hyvideo/optim/muon.py:72` `def __init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)`
- `Muon.adjust_lr_for_muon` (method) `hyvideo/optim/muon.py:108` `def adjust_lr_for_muon(self, lr, param_shape)`
- `Muon.step` (method) `hyvideo/optim/muon.py:116` `def step(self, closure)` -- Perform a single optimization step.
- `Muon.get_muon_optimizer` (method) `hyvideo/optim/muon.py:214` `def get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)`

## hyvideo/pipelines/hunyuan_video_pipeline.py
Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`
- `HunyuanVideo_1_5_Pipeline.__init__` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:92` `def __init__(self, vae, text_encoder, transformer, scheduler, text_encoder_2, flow_shift, guidance_scale...`
- `HunyuanVideo_1_5_Pipeline.encode_prompt` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:242` `def encode_prompt(self, prompt, device, num_videos_per_prompt, do_classifier_free_guidance, negative_prompt...` -- Encodes the prompt into text encoder hidden states.
- `HunyuanVideo_1_5_Pipeline.prepare_extra_func_kwargs` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:413` `def prepare_extra_func_kwargs(self, func, kwargs)` -- Prepare extra keyword arguments for scheduler functions.
- `HunyuanVideo_1_5_Pipeline.prepare_latents` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:429` `def prepare_latents(self, batch_size, num_channels_latents, latent_height, latent_width, video_length, dtype...` -- Prepare latents for video generation.
- `HunyuanVideo_1_5_Pipeline.get_guidance_scale_embedding` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:483` `def get_guidance_scale_embedding(self, w, embedding_dim, dtype)` -- See https://github.com/google-research/vdm/blob/dc27b98a554f65cdc654b800da5aa1846545d41b/model_vdm.py#L298
- `HunyuanVideo_1_5_Pipeline.guidance_scale` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:517` `def guidance_scale(self)`
- `HunyuanVideo_1_5_Pipeline.guidance_rescale` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:521` `def guidance_rescale(self)`
- `HunyuanVideo_1_5_Pipeline.clip_skip` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:525` `def clip_skip(self)`
- `HunyuanVideo_1_5_Pipeline.do_classifier_free_guidance` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:532` `def do_classifier_free_guidance(self)`
- `HunyuanVideo_1_5_Pipeline.cross_attention_kwargs` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:536` `def cross_attention_kwargs(self)`
- `HunyuanVideo_1_5_Pipeline.num_timesteps` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:540` `def num_timesteps(self)`
- `HunyuanVideo_1_5_Pipeline.interrupt` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:544` `def interrupt(self)`
- `HunyuanVideo_1_5_Pipeline.get_byt5_text_tokens` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:548` `def get_byt5_text_tokens(byt5_tokenizer, byt5_max_length, text_prompt)` -- Tokenize text prompt for byT5 model.
- `HunyuanVideo_1_5_Pipeline.extract_image_features` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:680` `def extract_image_features(self, reference_image)` -- Extract features from a reference image using VisionEncoder.
- `HunyuanVideo_1_5_Pipeline.get_task_mask` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:766` `def get_task_mask(self, task_type, latent_target_length)`
- `HunyuanVideo_1_5_Pipeline.get_closest_resolution_given_reference_image` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:776` `def get_closest_resolution_given_reference_image(self, reference_image, target_resolution)` -- Get closest supported resolution for a reference image.
- `HunyuanVideo_1_5_Pipeline.get_closest_resolution_given_original_size` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:800` `def get_closest_resolution_given_original_size(self, origin_size, target_size)` -- Get closest supported resolution for given original size and target resolution.
- `HunyuanVideo_1_5_Pipeline.get_image_condition_latents` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:826` `def get_image_condition_latents(self, task_type, reference_image, height, width)`
- `HunyuanVideo_1_5_Pipeline.vae_spatial_compression_ratio` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:861` `def vae_spatial_compression_ratio(self)`
- `HunyuanVideo_1_5_Pipeline.vae_temporal_compression_ratio` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:868` `def vae_temporal_compression_ratio(self)`
- `HunyuanVideo_1_5_Pipeline.get_latent_size` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:874` `def get_latent_size(self, video_length, height, width)`
- `HunyuanVideo_1_5_Pipeline.__call__` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:886` `def __call__(self, prompt, aspect_ratio, video_length, prompt_rewrite, num_inference_steps, guidance_scale...` -- Generates a video (or videos) based on text (and optionally image) conditions.
- `HunyuanVideo_1_5_Pipeline.ideal_resolution` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1324` `def ideal_resolution(self)`
- `HunyuanVideo_1_5_Pipeline.ideal_task` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1328` `def ideal_task(self)`
- `HunyuanVideo_1_5_Pipeline.use_meanflow` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1332` `def use_meanflow(self)`
- `HunyuanVideo_1_5_Pipeline.apply_infer_optimization` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1335` `def apply_infer_optimization(self, infer_state, enable_offloading, enable_group_offloading, overlap_group_offloading)` -- Apply inference optimizations to transformer based on infer_state.
- `HunyuanVideo_1_5_Pipeline.load_sr_transformer_upsampler` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1416` `def load_sr_transformer_upsampler(cls, cached_folder, sr_version, transformer_dtype, device)`
- `HunyuanVideo_1_5_Pipeline.create_sr_pipeline` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1426` `def create_sr_pipeline(self, cached_folder, sr_version, transformer_dtype, device)`
- `HunyuanVideo_1_5_Pipeline.get_transformer_version` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1452` `def get_transformer_version(resolution, task, cfg_distilled, step_distilled, sparse_attn)`
- `HunyuanVideo_1_5_Pipeline.create_pipeline` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1467` `def create_pipeline(cls, pretrained_model_name_or_path, transformer_version, create_sr_pipeline, transformer_dtype...`
- `HunyuanVideo_1_5_Pipeline.get_offloading_config` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1550` `def get_offloading_config(memory_limitation)`
- `HunyuanVideo_1_5_Pipeline.get_vae_inference_config` (method) `hyvideo/pipelines/hunyuan_video_pipeline.py:1566` `def get_vae_inference_config(memory_limitation)`

## hyvideo/pipelines/hunyuan_video_sr_pipeline.py
Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `expand_dims` (function) `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:42` `def expand_dims(tensor, ndim)`
- `BucketMap.__init__` (method) `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:49` `def __init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)`
- `BucketMap.__call__` (method) `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:62` `def __call__(self, lr_bucket)` -- Args: lr_bucket (tuple): Low-resolution bucket size as (width, height).
- `HunyuanVideo_1_5_SR_Pipeline.__init__` (method) `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:87` `def __init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale...`
- `HunyuanVideo_1_5_SR_Pipeline.add_noise_to_lq` (method) `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:142` `def add_noise_to_lq(self, lq_latents, strength)`
- `HunyuanVideo_1_5_SR_Pipeline.__call__` (method) `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:165` `def __call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt...` -- Runs the super-resolution (SR) pipeline for video generation.

## hyvideo/pipelines/pipeline_utils.py
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
- `retrieve_timesteps` (function) `hyvideo/pipelines/pipeline_utils.py:21` `def retrieve_timesteps(scheduler, num_inference_steps, device, timesteps, sigmas)` -- Calls the scheduler's `set_timesteps` method and retrieves timesteps from the scheduler after the call.
- `rescale_noise_cfg` (function) `hyvideo/pipelines/pipeline_utils.py:86` `def rescale_noise_cfg(noise_cfg, noise_pred_text, guidance_rescale)` -- Rescale `noise_cfg` according to `guidance_rescale`.

## hyvideo/schedulers/scheduling_flow_match_discrete.py
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `FlowMatchDiscreteScheduler.__init__` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:86` `def __init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift...`
- `FlowMatchDiscreteScheduler.step_index` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:119` `def step_index(self)` -- The index counter for current timestep.
- `FlowMatchDiscreteScheduler.begin_index` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:126` `def begin_index(self)` -- The index for the first timestep.
- `FlowMatchDiscreteScheduler.set_begin_index` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:133` `def set_begin_index(self, begin_index)` -- Sets the begin index for the scheduler.
- `FlowMatchDiscreteScheduler.set_timesteps` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:146` `def set_timesteps(self, num_inference_steps, device, n_tokens)` -- Sets the discrete timesteps used for the diffusion chain (to be run before inference).
- `FlowMatchDiscreteScheduler.index_for_timestep` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:182` `def index_for_timestep(self, timestep, schedule_timesteps)`
- `FlowMatchDiscreteScheduler.scale_model_input` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:204` `def scale_model_input(self, sample, timestep)`
- `FlowMatchDiscreteScheduler.get_lin_function` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:208` `def get_lin_function(x1, y1, x2, y2)`
- `FlowMatchDiscreteScheduler.flux_time_shift` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:214` `def flux_time_shift(mu, sigma, t)`
- `FlowMatchDiscreteScheduler.sd3_time_shift` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:217` `def sd3_time_shift(self, t)`
- `FlowMatchDiscreteScheduler.step` (method) `hyvideo/schedulers/scheduling_flow_match_discrete.py:220` `def step(self, model_output, timestep, sample, generator, n_tokens, return_dict)` -- Predict the sample from the previous timestep by reversing the SDE.

## hyvideo/utils/communications.py
Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`
- `broadcast` (function) `hyvideo/utils/communications.py:24` `def broadcast(input_, group)`
- `SeqAllToAll4D.forward` (method) `hyvideo/utils/communications.py:149` `def forward(ctx, group, input, scatter_idx, gather_idx)`
- `SeqAllToAll4D.backward` (method) `hyvideo/utils/communications.py:163` `def backward(ctx)`
- `SeqAllToAll4D.all_to_all_4D` (method) `hyvideo/utils/communications.py:174` `def all_to_all_4D(input_, group, scatter_dim, gather_dim)`
- `_AllToAll.forward` (method) `hyvideo/utils/communications.py:206` `def forward(ctx, input_, process_group, scatter_dim, gather_dim)`
- `_AllToAll.backward` (method) `hyvideo/utils/communications.py:217` `def backward(ctx, grad_output)`
- `_AllToAll.all_to_all` (method) `hyvideo/utils/communications.py:233` `def all_to_all(input_, group, scatter_dim, gather_dim)`
- `_Reduce_Scatter.forward` (method) `hyvideo/utils/communications.py:242` `def forward(ctx, op, group, tensor)`
- `_Reduce_Scatter.backward` (method) `hyvideo/utils/communications.py:251` `def backward(ctx, grad_output)`
- `_AllGather.forward` (method) `hyvideo/utils/communications.py:264` `def forward(ctx, input_, dim, group)`
- `_AllGather.backward` (method) `hyvideo/utils/communications.py:283` `def backward(ctx, grad_output)`
- `_AllGather.all_gather` (method) `hyvideo/utils/communications.py:304` `def all_gather(input_, dim, group)` -- Performs an all-gather operation on the input tensor along the specified dimension.

## hyvideo/utils/data_utils.py
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
- `resize_and_center_crop` (function) `hyvideo/utils/data_utils.py:20` `def resize_and_center_crop(image, target_width, target_height)`
- `get_closest_ratio` (function) `hyvideo/utils/data_utils.py:38` `def get_closest_ratio(height, width, ratios, buckets)` -- Get the closest ratio in the buckets.
- `generate_crop_size_list` (function) `hyvideo/utils/data_utils.py:61` `def generate_crop_size_list(base_size, patch_size, max_ratio)`

## hyvideo/utils/flash_attn_no_pad.py
Imported by: `hyvideo/models/transformers/modules/attention.py`
- `flash_attn_no_pad` (function) `hyvideo/utils/flash_attn_no_pad.py:20` `def flash_attn_no_pad(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`
- `flash_attn_no_pad_v3` (function) `hyvideo/utils/flash_attn_no_pad.py:52` `def flash_attn_no_pad_v3(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`

## hyvideo/utils/infer_utils.py
- `torch_compile_wrapper` (function) `hyvideo/utils/infer_utils.py:19` `def torch_compile_wrapper()`
- `decorator` (function) `hyvideo/utils/infer_utils.py:20` `def decorator(func)`
- `wrapper` (function) `hyvideo/utils/infer_utils.py:21` `def wrapper(self)`

## hyvideo/utils/multitask_utils.py
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `numpy_to_pil` (function) `hyvideo/utils/multitask_utils.py:23` `def numpy_to_pil(images)` -- Convert a numpy image or a batch of images to a PIL image.
- `merge_tensor_by_mask` (function) `hyvideo/utils/multitask_utils.py:45` `def merge_tensor_by_mask(tensor_1, tensor_2, mask, dim)`

## hyvideo/utils/rewrite/clients.py
Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`
- `NonStreamResponse.__init__` (method) `hyvideo/utils/rewrite/clients.py:30` `def __init__(self)`
- `DeepSeekClient.__init__` (method) `hyvideo/utils/rewrite/clients.py:38` `def __init__(self, key_id, key_secret)`
- `DeepSeekClient.run_single_recaption` (method) `hyvideo/utils/rewrite/clients.py:51` `def run_single_recaption(self, system_prompt, input_prompt)`
- `QwenClient.__init__` (method) `hyvideo/utils/rewrite/clients.py:85` `def __init__(self, base_url, model_name)`
- `QwenClient.qwen_api_call` (method) `hyvideo/utils/rewrite/clients.py:90` `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens)` -- Use Qwen Chat API to perform text rewriting, parse <think>...</think> sections for reasoning content, and return...
- `QwenClient.run_single_recaption` (method) `hyvideo/utils/rewrite/clients.py:128` `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens)`
- `QwenVLClient.__init__` (method) `hyvideo/utils/rewrite/clients.py:135` `def __init__(self, base_url, model_name)`
- `QwenVLClient.qwen_api_call` (method) `hyvideo/utils/rewrite/clients.py:176` `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens, img_path)` -- Use Qwen3-VL to perform text rewriting.
- `QwenVLClient.run_single_recaption` (method) `hyvideo/utils/rewrite/clients.py:246` `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens, img_path)`

## hyvideo/utils/rewrite/rewrite_utils.py
Depends on: `hyvideo/utils/rewrite/clients.py`, `hyvideo/utils/rewrite/i2v_prompt.py`, `hyvideo/utils/rewrite/t2v_prompt.py`
Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `t2v_rewrite` (function) `hyvideo/utils/rewrite/rewrite_utils.py:22` `def t2v_rewrite(user_prompt, rewrite_client)`
- `i2v_rewrite` (function) `hyvideo/utils/rewrite/rewrite_utils.py:40` `def i2v_rewrite(user_input, img_path, rewrite_client)` -- Use a rewrite client to generate a rewritten prompt for image-to-video.
- `run_prompt_rewrite` (function) `hyvideo/utils/rewrite/rewrite_utils.py:63` `def run_prompt_rewrite(user_prompt, img_path, task_type)`

## train.py
Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `SNRType.str_to_bool` (method) `train.py:98` `def str_to_bool(value)` -- Convert string to boolean, supporting true/false, 1/0, yes/no.
- `SNRType.save_video` (method) `train.py:114` `def save_video(video, path)`
- `LinearInterpolationSchedule.__init__` (method) `train.py:188` `def __init__(self, T)`
- `LinearInterpolationSchedule.forward` (method) `train.py:191` `def forward(self, x0, x1, t)` -- Linear interpolation: x_t = (1 - t/T) * x0 + (t/T) * x1 Args: x0: starting point (clean latents) x1: ending point...
- `TimestepSampler.__init__` (method) `train.py:209` `def __init__(self, T, device, snr_type)`
- `TimestepSampler.sample` (method) `train.py:226` `def sample(self, batch_size, device)`
- `TimestepSampler.timestep_transform` (method) `train.py:269` `def timestep_transform(timesteps, T, shift)` -- Transform timesteps with shift
- `TimestepSampler.is_src` (method) `train.py:278` `def is_src(src, group_src, group)`
- `TimestepSampler.broadcast_object` (method) `train.py:287` `def broadcast_object(obj, src, group, device, group_src)`
- `TimestepSampler.broadcast_tensor` (method) `train.py:305` `def broadcast_tensor(tensor, src, group, async_op, group_src)` -- shape and dtype safe broadcast of tensor
- `TimestepSampler.sync_tensor_for_sp` (method) `train.py:333` `def sync_tensor_for_sp(tensor, sp_group)` -- Sync tensor within sequence parallel group.
- `HunyuanVideoTrainer.__init__` (method) `train.py:348` `def __init__(self, config)`
- `HunyuanVideoTrainer.non_reentrant_wrapper` (method) `train.py:547` `def non_reentrant_wrapper(module)`
- `HunyuanVideoTrainer.selective_checkpointing` (method) `train.py:553` `def selective_checkpointing(submodule)`
- `HunyuanVideoTrainer.encode_text` (method) `train.py:592` `def encode_text(self, prompts, data_type)`
- `HunyuanVideoTrainer.encode_byt5` (method) `train.py:608` `def encode_byt5(self, text_ids, attention_mask)`
- `HunyuanVideoTrainer.encode_images` (method) `train.py:615` `def encode_images(self, images)` -- Encode images to vision states (for i2v)
- `HunyuanVideoTrainer.encode_vae` (method) `train.py:625` `def encode_vae(self, images)`
- `HunyuanVideoTrainer.get_condition` (method) `train.py:641` `def get_condition(self, latents, task_type)`
- `HunyuanVideoTrainer.sample_task` (method) `train.py:654` `def sample_task(self, data_type)` -- Sample task type based on data type and configuration.
- `HunyuanVideoTrainer.prepare_batch` (method) `train.py:671` `def prepare_batch(self, batch)` -- Prepare batch for training.
- `HunyuanVideoTrainer.train_step` (method) `train.py:776` `def train_step(self, batch)`
- `HunyuanVideoTrainer.save_checkpoint` (method) `train.py:828` `def save_checkpoint(self, step)`
- `HunyuanVideoTrainer.load_pretrained_lora` (method) `train.py:892` `def load_pretrained_lora(self, lora_dir)`
- `HunyuanVideoTrainer.load_checkpoint` (method) `train.py:901` `def load_checkpoint(self, checkpoint_path)`
- `HunyuanVideoTrainer.train` (method) `train.py:959` `def train(self, dataloader)`
- `HunyuanVideoTrainer.validate` (method) `train.py:1001` `def validate(self, step)` -- Implement your own validation logic here An example:
- `HunyuanVideoTrainer.create_dummy_dataloader` (method) `train.py:1047` `def create_dummy_dataloader(config)` -- Create a dummy dataloader for testing.
- `DummyDataset.__init__` (method) `train.py:1109` `def __init__(self, size)`
- `DummyDataset.main` (method) `train.py:1144` `def main()`
