# API

## generate.py

### save_video `def save_video(video, path)`
- Defined: `generate.py:42`
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### rank0_log `def rank0_log(message, level)`
- Defined: `generate.py:50`
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### save_config `def save_config(args, output_path, task, transformer_version)`
- Defined: `generate.py:54`
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### str_to_bool `def str_to_bool(value)`
- Defined: `generate.py:81`
- Doc: Convert string to boolean, supporting true/false, 1/0, yes/no.
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### load_checkpoint_to_transformer `def load_checkpoint_to_transformer(pipe, checkpoint_path)`
- Defined: `generate.py:96`
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### load_lora_adapter `def load_lora_adapter(pipe, lora_path)`
- Defined: `generate.py:112`
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### generate_video `def generate_video(args)`
- Defined: `generate.py:128`
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### main `def main()`
- Defined: `generate.py:274`
- Depends on: `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/__init__.py

### find_free_port `def find_free_port()`
- Defined: `hyvideo/__init__.py:25`
- Depends on: `hyvideo/commons/__init__.py`

### __initialize_default_distributed_environment `def __initialize_default_distributed_environment()`
- Defined: `hyvideo/__init__.py:32`
- Depends on: `hyvideo/commons/__init__.py`

## hyvideo/commons/__init__.py

### _ntuple `def _ntuple(n)`
- Defined: `hyvideo/commons/__init__.py:24`
- Doc: Create a function that converts input to n-tuple.
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### is_flash2_available `def is_flash2_available()`
- Defined: `hyvideo/commons/__init__.py:142`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### is_flash3_available `def is_flash3_available()`
- Defined: `hyvideo/commons/__init__.py:149`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### is_flash_available `def is_flash_available()`
- Defined: `hyvideo/commons/__init__.py:156`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### is_sparse_attn_supported `def is_sparse_attn_supported()`
- Defined: `hyvideo/commons/__init__.py:159`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### is_sparse_attn_available `def is_sparse_attn_available()`
- Defined: `hyvideo/commons/__init__.py:162`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### is_angelslim_available `def is_angelslim_available()`
- Defined: `hyvideo/commons/__init__.py:171`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### maybe_fallback_attn_mode `def maybe_fallback_attn_mode(attn_mode)`
- Defined: `hyvideo/commons/__init__.py:178`
- Doc: Determine the final attention mode based on configuration and availability.
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### auto_offload_model `def auto_offload_model(models, device, enabled)`
- Defined: `hyvideo/commons/__init__.py:229`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### get_gpu_memory `def get_gpu_memory(device)`
- Defined: `hyvideo/commons/__init__.py:243`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### get_rank `def get_rank()`
- Defined: `hyvideo/commons/__init__.py:254`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### parse `def parse(x)`
- Defined: `hyvideo/commons/__init__.py:26`
- Imported by: `hyvideo/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/commons/infer_state.py

### parse_range `def parse_range(value)`
- Defined: `hyvideo/commons/infer_state.py:42`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### initialize_infer_state `def initialize_infer_state(args)`
- Defined: `hyvideo/commons/infer_state.py:49`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### get_infer_state `def get_infer_state()`
- Defined: `hyvideo/commons/infer_state.py:87`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/commons/parallel_states.py

### initialize_parallel_state `def initialize_parallel_state(sp, dp_replicate)`
- Defined: `hyvideo/commons/parallel_states.py:81`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_parallel_state `def get_parallel_state()`
- Defined: `hyvideo/commons/parallel_states.py:89`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### __post_init__ `def __post_init__(self)`
- Defined: `hyvideo/commons/parallel_states.py:29`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### build_mesh `def build_mesh(self, device_type)`
- Defined: `hyvideo/commons/parallel_states.py:37`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### sp_enabled `def sp_enabled(self)`
- Defined: `hyvideo/commons/parallel_states.py:68`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### sp_mesh `def sp_mesh(self)`
- Defined: `hyvideo/commons/parallel_states.py:72`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### dp_enabled `def dp_enabled(self)`
- Defined: `hyvideo/commons/parallel_states.py:76`
- Imported by: `generate.py`, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

## hyvideo/models/autoencoders/hunyuanvideo_15_vae.py

### swish `def swish(x, inplace)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:45`
- Doc: Applies the swish activation function (SiLU) with optional inplace support.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward_with_checkpointing `def forward_with_checkpointing(module)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:50`
- Doc: Forward with optional gradient checkpointing.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### prepare_causal_attention_mask `def prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:163`
- Doc: Prepare a causal attention mask for 3D videos.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### create_custom_forward `def create_custom_forward(module)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:52`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### find_split_indices `def find_split_indices(self, seq_len, part_num)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:67`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, input)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:86`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, dim, channel_first, images, bias)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:113`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:123`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:132`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:158`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, in_channels)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:189`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### attention `def attention(self, h_)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:200`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:215`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, in_channels, out_channels)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:222`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:236`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, in_channels, out_channels, add_temporal_downsample)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:253`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:261`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, in_channels, out_channels, add_temporal_upsample)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:296`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:303`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, in_channels, z_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, downsample_match_channel)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:334`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:386`
- Doc: Forward pass through the encoder.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, upsample_match_channel)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:416`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, z)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:468`
- Doc: Forward pass through the decoder.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### __init__ `def __init__(self, in_channels, out_channels, latent_channels, block_out_channels, layers_per_block, ffactor_spatial, ffactor_temporal, sample_size, sample_tsize, scaling_factor, shift_factor, downsample_match_channel, upsample_match_channel)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:500`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### set_tile_sample_min_size `def set_tile_sample_min_size(self, sample_size, tile_overlap_factor)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:554`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### _set_gradient_checkpointing `def _set_gradient_checkpointing(self, module, value)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:563`
- Doc: Enable or disable gradient checkpointing on encoder and decoder.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### enable_temporal_tiling `def enable_temporal_tiling(self, use_tiling)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:569`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### disable_temporal_tiling `def disable_temporal_tiling(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:573`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### enable_spatial_tiling `def enable_spatial_tiling(self, use_tiling)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:576`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### disable_spatial_tiling `def disable_spatial_tiling(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:579`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### enable_tiling `def enable_tiling(self, use_tiling)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:582`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### disable_tiling `def disable_tiling(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:585`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### enable_slicing `def enable_slicing(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:588`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### disable_slicing `def disable_slicing(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:591`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### blend_h `def blend_h(self, a, b, blend_extent)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:594`
- Doc: Blend tensor b horizontally into a at blend_extent region.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### blend_v `def blend_v(self, a, b, blend_extent)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:601`
- Doc: Blend tensor b vertically into a at blend_extent region.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### blend_t `def blend_t(self, a, b, blend_extent)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:608`
- Doc: Blend tensor b temporally into a at blend_extent region.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### spatial_tiled_encode `def spatial_tiled_encode(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:615`
- Doc: Tiled spatial encoding for large inputs via overlapping.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### temporal_tiled_encode `def temporal_tiled_encode(self, x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:643`
- Doc: Tiled temporal encoding for large video sequences.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### enable_tile_parallelism `def enable_tile_parallelism(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:671`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### disable_tile_parallelism `def disable_tile_parallelism(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:674`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### tile_parallel_spatial_tiled_decode `def tile_parallel_spatial_tiled_decode(self, z)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:677`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### spatial_tiled_decode `def spatial_tiled_decode(self, z)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:772`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### temporal_tiled_decode `def temporal_tiled_decode(self, z)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:803`
- Doc: Tiled temporal decoding for long sequence latents.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### encode `def encode(self, x, return_dict)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:833`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### decode `def decode(self, z, return_dict, generator)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:856`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### forward `def forward(self, sample, sample_posterior, return_posterior, return_dict)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:876`
- Doc: Forward autoencoder pass. Returns both reconstruction and optionally the posterior.
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### memory_efficient_context `def memory_efficient_context(self)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:890`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### custom_forward `def custom_forward()`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:53`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### _encode `def _encode(x)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:835`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

### _decode `def _decode(z)`
- Defined: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:858`
- Depends on: `hyvideo/commons/parallel_states.py`
- Imported by: `hyvideo/models/transformers/modules/upsample.py`

## hyvideo/models/text_encoders/__init__.py

### use_default `def use_default(value, default)`
- Defined: `hyvideo/models/text_encoders/__init__.py:32`
- Doc: Utility: return value if not None, else default.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### load_text_encoder `def load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)`
- Defined: `hyvideo/models/text_encoders/__init__.py:84`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### load_tokenizer `def load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)`
- Defined: `hyvideo/models/text_encoders/__init__.py:114`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### __init__ `def __init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type, tokenizer_path, output_key, use_attention_mask, prompt_template, prompt_template_video, hidden_state_skip_layer, apply_final_norm, reproduce, logger, device)`
- Defined: `hyvideo/models/text_encoders/__init__.py:155`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### dtype `def dtype(self)`
- Defined: `hyvideo/models/text_encoders/__init__.py:245`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### device `def device(self)`
- Defined: `hyvideo/models/text_encoders/__init__.py:249`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### __repr__ `def __repr__(self)`
- Defined: `hyvideo/models/text_encoders/__init__.py:252`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### apply_text_to_template `def apply_text_to_template(text, template, prevent_empty_text)`
- Defined: `hyvideo/models/text_encoders/__init__.py:256`
- Doc: Apply text to template.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### calculate_crop_start `def calculate_crop_start(self, tokenized_input)`
- Defined: `hyvideo/models/text_encoders/__init__.py:281`
- Doc: Automatically calculate the crop_start position based on identifying user tokens.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### text2tokens `def text2tokens(self, text, data_type, max_length)`
- Defined: `hyvideo/models/text_encoders/__init__.py:316`
- Doc: Tokenize the input text.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### encode `def encode(self, batch_encoding, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts, data_type, device, is_uncond)`
- Defined: `hyvideo/models/text_encoders/__init__.py:415`
- Doc: Args:
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### forward `def forward(self, text, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts)`
- Defined: `hyvideo/models/text_encoders/__init__.py:487`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/models/text_encoders/byT5/__init__.py

### load_glyph_byT5_v2 `def load_glyph_byT5_v2(args, device)`
- Defined: `hyvideo/models/text_encoders/byT5/__init__.py:23`
- Doc: Loads ByT5 tokenizer and encoder model for glyph encoding.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### create_byt5 `def create_byt5(args, device)`
- Defined: `hyvideo/models/text_encoders/byT5/__init__.py:43`
- Doc: Create ByT5 tokenizer and encoder, load weights if provided.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### add_special_token `def add_special_token(tokenizer, text_encoder, add_color, add_font, color_ann_path, font_ann_path, multilingual)`
- Defined: `hyvideo/models/text_encoders/byT5/__init__.py:89`
- Doc: Add special tokens for color and font to tokenizer and text encoder.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### load_byt5_and_byt5_tokenizer `def load_byt5_and_byt5_tokenizer(byt5_name, special_token, color_special_token, font_special_token, color_ann_path, font_ann_path, huggingface_cache_dir, multilingual, device)`
- Defined: `hyvideo/models/text_encoders/byT5/__init__.py:131`
- Doc: Load ByT5 encoder and tokenizer from Huggingface, and add special tokens if needed.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)`
- Defined: `hyvideo/models/text_encoders/byT5/__init__.py:199`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/text_encoders/byT5/__init__.py:210`
- Doc: Forward pass for ByT5Mapper.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/models/text_encoders/byT5/format_prompt.py

### closest_color `def closest_color(requested_color)`
- Defined: `hyvideo/models/text_encoders/byT5/format_prompt.py:20`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### convert_rgb_to_names `def convert_rgb_to_names(rgb_tuple)`
- Defined: `hyvideo/models/text_encoders/byT5/format_prompt.py:34`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, font_path, color_path)`
- Defined: `hyvideo/models/text_encoders/byT5/format_prompt.py:46`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### format_prompt `def format_prompt(self, texts, styles)`
- Defined: `hyvideo/models/text_encoders/byT5/format_prompt.py:56`
- Doc: Text "{text}" in {color}, {type}.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py

### __init__ `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:47`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### enable_deterministic `def enable_deterministic(self)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:111`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### disable_deterministic `def disable_deterministic(self)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:114`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### forward `def forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:117`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### __init__ `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dtype, device)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:210`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### enable_deterministic `def enable_deterministic(self)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:255`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### disable_deterministic `def disable_deterministic(self)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:258`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### forward `def forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:261`
- Doc: Forward pass for the single stream block.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### __init__ `def __init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, mm_double_blocks_depth, mm_single_blocks_depth, rope_dim_list, qkv_bias, qk_norm, qk_norm_type, guidance_embed, use_meanflow, text_projection, use_attention_mask, text_states_dim, text_states_dim_2, text_pool_type, rope_theta, attn_mode, attn_param, glyph_byT5_v2, vision_projection, vision_states_dim, is_reshape_temporal_channels, use_cond_type_embedding, ideal_resolution, ideal_task)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:351`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### load_hunyuan_state_dict `def load_hunyuan_state_dict(self, model_path)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:563`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### enable_deterministic `def enable_deterministic(self)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:601`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### disable_deterministic `def disable_deterministic(self)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:607`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### get_rotary_pos_embed `def get_rotary_pos_embed(self, rope_sizes)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:613`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### reorder_txt_token `def reorder_txt_token(self, byt5_txt, txt, byt5_text_mask, text_mask, zero_feat, is_reorder)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:631`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### forward `def forward(self, hidden_states, timestep, text_states, text_states_2, encoder_attention_mask, timestep_r, vision_states, output_features, output_features_stride, attention_kwargs, freqs_cos, freqs_sin, return_dict, guidance, mask_type, extra_kwargs)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:667`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### unpatchify `def unpatchify(self, x, t, h, w)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:867`
- Doc: Unpatchify a tensorized input back to frame format.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### set_attn_mode `def set_attn_mode(self, attn_mode)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:888`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### save_lora_adapter `def save_lora_adapter(self, save_directory, adapter_name, upcast_before_saving, safe_serialization, weight_name)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:896`
- Doc: Save the LoRA parameters corresponding to the underlying model.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### save_function `def save_function(weights, filename)`
- Defined: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py:943`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`, `hyvideo/models/transformers/modules/posemb_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`, `hyvideo/utils/communications.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/models/transformers/modules/activation_layers.py

### get_activation_layer `def get_activation_layer(act_type)`
- Defined: `hyvideo/models/transformers/modules/activation_layers.py:20`
- Doc: get activation layer
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/attention.py

### attention `def attention(q, k, v, drop_rate, attn_mask, causal, attn_mode)`
- Defined: `hyvideo/models/transformers/modules/attention.py:50`
- Doc: Compute attention using flash_attn_no_pad or torch scaled_dot_product_attention.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### parallel_attention `def parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
- Defined: `hyvideo/models/transformers/modules/attention.py:112`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### sequence_parallel_attention `def sequence_parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
- Defined: `hyvideo/models/transformers/modules/attention.py:120`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### shrink_head `def shrink_head(encoder_state, dim)`
- Defined: `hyvideo/models/transformers/modules/attention.py:145`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### score_mod `def score_mod(score, b, h, q_idx, kv_idx)`
- Defined: `hyvideo/models/transformers/modules/attention.py:188`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### get_image_tile `def get_image_tile(tile_size)`
- Defined: `hyvideo/models/transformers/modules/attention.py:231`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/transformers/modules/ssta_attention.py`, `hyvideo/utils/communications.py`, `hyvideo/utils/flash_attn_no_pad.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/embed_layers.py

### timestep_embedding `def timestep_embedding(t, dim, max_period)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:151`
- Doc: Create sinusoidal timestep embeddings.
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:37`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:82`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, in_channels, hidden_size, act_layer, dtype, device)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:97`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, caption)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:114`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, input_dim, output_dim)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:124`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, vision_embeds)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:136`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, in_channels, out_channels)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:140`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:147`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:183`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, t)`
- Defined: `hyvideo/models/transformers/modules/embed_layers.py:208`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/mlp_layers.py

### __init__ `def __init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:32`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:60`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, in_dim, out_dim, bias, device, dtype)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:71`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x, y)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:76`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, in_dim, hidden_dim, device, dtype)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:85`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:92`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:99`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x, c)`
- Defined: `hyvideo/models/transformers/modules/mlp_layers.py:133`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/models/transformers/modules/modulate_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/modulate_layers.py

### modulate `def modulate(x, shift, scale)`
- Defined: `hyvideo/models/transformers/modules/modulate_layers.py:46`
- Doc: modulate by shift and scale
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### apply_gate `def apply_gate(x, gate, tanh)`
- Defined: `hyvideo/models/transformers/modules/modulate_layers.py:67`
- Doc: AI is creating summary for apply_gate
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### ckpt_wrapper `def ckpt_wrapper(module)`
- Defined: `hyvideo/models/transformers/modules/modulate_layers.py:86`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, hidden_size, factor, act_layer, dtype, device)`
- Defined: `hyvideo/models/transformers/modules/modulate_layers.py:26`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/modulate_layers.py:42`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### ckpt_forward `def ckpt_forward()`
- Defined: `hyvideo/models/transformers/modules/modulate_layers.py:87`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/norm_layers.py

### get_norm_layer `def get_norm_layer(norm_layer)`
- Defined: `hyvideo/models/transformers/modules/norm_layers.py:82`
- Doc: Get the normalization layer.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### __init__ `def __init__(self, dim, elementwise_affine, eps, device, dtype)`
- Defined: `hyvideo/models/transformers/modules/norm_layers.py:22`
- Doc: Initialize the RMSNorm normalization layer.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### _norm `def _norm(self, x)`
- Defined: `hyvideo/models/transformers/modules/norm_layers.py:48`
- Doc: Apply the RMSNorm normalization to the input tensor.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### reset_parameters `def reset_parameters(self)`
- Defined: `hyvideo/models/transformers/modules/norm_layers.py:61`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/norm_layers.py:65`
- Doc: Forward pass through the RMSNorm layer.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/token_refiner.py`

## hyvideo/models/transformers/modules/posemb_layers.py

### _to_tuple `def _to_tuple(x, dim)`
- Defined: `hyvideo/models/transformers/modules/posemb_layers.py:23`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### get_meshgrid_nd `def get_meshgrid_nd(start)`
- Defined: `hyvideo/models/transformers/modules/posemb_layers.py:32`
- Doc: Get n-D meshgrid with start, stop and num.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### reshape_for_broadcast `def reshape_for_broadcast(freqs_cis, x, head_first)`
- Defined: `hyvideo/models/transformers/modules/posemb_layers.py:83`
- Doc: Reshape frequency tensor for broadcasting it with another tensor.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### rotate_half `def rotate_half(x)`
- Defined: `hyvideo/models/transformers/modules/posemb_layers.py:151`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### apply_rotary_emb `def apply_rotary_emb(xq, xk, freqs_cis, head_first)`
- Defined: `hyvideo/models/transformers/modules/posemb_layers.py:158`
- Doc: Apply rotary embeddings to input tensors using the given frequency tensor.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### get_nd_rotary_pos_embed `def get_nd_rotary_pos_embed(rope_dim_list, start)`
- Defined: `hyvideo/models/transformers/modules/posemb_layers.py:210`
- Doc: This is a n-d version of precompute_freqs_cis, which is a RoPE for tokens with n-d structure.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### get_1d_rotary_pos_embed `def get_1d_rotary_pos_embed(dim, pos, theta, use_real, theta_rescale_factor, interpolation_factor)`
- Defined: `hyvideo/models/transformers/modules/posemb_layers.py:281`
- Doc: Precompute the frequency tensor for complex exponential (cis) with given dimensions.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

## hyvideo/models/transformers/modules/ssta_attention.py

### tile `def tile(x, canvas_thw, tile_thw, sp_size)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:23`
- Doc: Rearrange tensor into tiles for block-based attention.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### untile `def untile(x, canvas_thw, tile_thw, sp_size)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:53`
- Doc: Reverse the tiling operation to restore original tensor layout.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### get_tile_t_h_w `def get_tile_t_h_w(tile_id, tile_thw_dim)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:82`
- Doc: Extract temporal, height, and width indices from a flattened tile ID.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### importance_sampling `def importance_sampling(q, k, topk, threshold, lambda_, adaptive_pool)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:90`
- Doc: Select top-k blocks based on importance scores considering both similarity and redundancy.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### similarity_sampling `def similarity_sampling(q, k, topk, threshold, block_num, adaptive_pool, temperature)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:126`
- Doc: Select top-k blocks based on similarity scores between query and key averages.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### create_moba_3d_mask `def create_moba_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, add_text_mask, threshold, lambda_, mask_share_within_head, q_block_avg_pool, adaptive_pool, sampling_type)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:170`
- Doc: Create MOBA (Mixture of Block Attention) 3D mask for sparse attention.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### create_sta_3d_mask_optimize `def create_sta_3d_mask_optimize(canvas_thw, tile_thw, kernel_thw)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:323`
- Doc: Create optimized STA (Spatio-Temporal Attention) 3D mask using vectorized operations.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### create_sta_3d_mask `def create_sta_3d_mask(canvas_thw, tile_thw, kernel_thw, text_block_num)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:374`
- Doc: Create STA (Spatio-Temporal Attention) 3D mask.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### create_ssta_3d_mask `def create_ssta_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, threshold, lambda_, text_mask, mask_share_within_head, adaptive_pool, sampling_type)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:404`
- Doc: Create SSTA (Sparse Spatio-Temporal Attention) 3D mask combining STA and MOBA masks.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### ssta_3d_attention `def ssta_3d_attention(all_q, all_k, all_v, canvas_thw, topk, tile_thw, kernel_thw, text_len, sparse_type, threshold, lambda_, pad_type, text_mask, mask_share_within_head, sampling_type, adaptive_pool)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:465`
- Doc: Sparse Spatio-Temporal Attention (SSTA) 3D attention mechanism.
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### get_block_avg_feat `def get_block_avg_feat(x, adaptive_pool, pooling_type)`
- Defined: `hyvideo/models/transformers/modules/ssta_attention.py:216`
- Imported by: `hyvideo/models/transformers/modules/attention.py`

## hyvideo/models/transformers/modules/token_refiner.py

### __init__ `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- Defined: `hyvideo/models/transformers/modules/token_refiner.py:50`
- Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### forward `def forward(self, x, c, attn_mask)`
- Defined: `hyvideo/models/transformers/modules/token_refiner.py:98`
- Doc: Forward pass for IndividualTokenRefinerBlock.
- Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### __init__ `def __init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- Defined: `hyvideo/models/transformers/modules/token_refiner.py:145`
- Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### forward `def forward(self, x, c, mask)`
- Defined: `hyvideo/models/transformers/modules/token_refiner.py:178`
- Doc: Forward pass for IndividualTokenRefiner.
- Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### __init__ `def __init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- Defined: `hyvideo/models/transformers/modules/token_refiner.py:222`
- Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

### forward `def forward(self, x, t, mask)`
- Defined: `hyvideo/models/transformers/modules/token_refiner.py:256`
- Doc: Forward pass for SingleTokenRefiner.
- Depends on: `hyvideo/models/transformers/modules/activation_layers.py`, `hyvideo/models/transformers/modules/attention.py`, `hyvideo/models/transformers/modules/embed_layers.py`, `hyvideo/models/transformers/modules/mlp_layers.py`, `hyvideo/models/transformers/modules/modulate_layers.py`, `hyvideo/models/transformers/modules/norm_layers.py`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

## hyvideo/models/transformers/modules/upsample.py

### __init__ `def __init__(self, channels)`
- Defined: `hyvideo/models/transformers/modules/upsample.py:56`
- Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/upsample.py:66`
- Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### __init__ `def __init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)`
- Defined: `hyvideo/models/transformers/modules/upsample.py:73`
- Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### forward `def forward(self, x)`
- Defined: `hyvideo/models/transformers/modules/upsample.py:89`
- Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### __init__ `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)`
- Defined: `hyvideo/models/transformers/modules/upsample.py:103`
- Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### forward `def forward(self, z, target_shape)`
- Defined: `hyvideo/models/transformers/modules/upsample.py:137`
- Doc: Args:
- Depends on: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/models/vision_encoder/__init__.py

### use_default `def use_default(value, default)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:29`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### load_vision_encoder `def load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:33`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### load_image_processor `def load_image_processor(processor_type, processor_path, logger)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:63`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type, processor_path, output_key, logger, device)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:105`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __repr__ `def __repr__(self)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:149`
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### encode_latents_to_images `def encode_latents_to_images(self, latents, vae, reorg_token)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:152`
- Doc: Convert latents to images using VAE decoder.
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### encode_images `def encode_images(self, images)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:179`
- Doc: Encode images using the vision encoder.
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### encode_latents `def encode_latents(self, latents, vae, reorg_token)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:205`
- Doc: Encode latents by first converting to images, then encoding.
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### forward `def forward(self, images)`
- Defined: `hyvideo/models/vision_encoder/__init__.py:225`
- Doc: Forward pass for direct image encoding.
- Depends on: `hyvideo/commons/__init__.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/optim/muon.py

### zeropower_via_newtonschulz5 `def zeropower_via_newtonschulz5(G, steps)`
- Defined: `hyvideo/optim/muon.py:17`
- Doc: Newton-Schulz iteration to compute the zeroth power / orthogonalization of G. We opt to use a
- Imported by: `train.py`

### get_muon_optimizer `def get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)`
- Defined: `hyvideo/optim/muon.py:214`
- Imported by: `train.py`

### __init__ `def __init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)`
- Defined: `hyvideo/optim/muon.py:72`
- Imported by: `train.py`

### adjust_lr_for_muon `def adjust_lr_for_muon(self, lr, param_shape)`
- Defined: `hyvideo/optim/muon.py:108`
- Imported by: `train.py`

### step `def step(self, closure)`
- Defined: `hyvideo/optim/muon.py:116`
- Doc: Perform a single optimization step.
- Imported by: `train.py`

## hyvideo/pipelines/hunyuan_video_pipeline.py

### __init__ `def __init__(self, vae, text_encoder, transformer, scheduler, text_encoder_2, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:92`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _create_scheduler `def _create_scheduler(cls, flow_shift)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:185`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _load_byt5 `def _load_byt5(cls, cached_folder, glyph_byT5_v2, byt5_max_length, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:194`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### encode_prompt `def encode_prompt(self, prompt, device, num_videos_per_prompt, do_classifier_free_guidance, negative_prompt, prompt_embeds, attention_mask, negative_prompt_embeds, negative_attention_mask, clip_skip, text_encoder, data_type)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:242`
- Doc: Encodes the prompt into text encoder hidden states.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### prepare_extra_func_kwargs `def prepare_extra_func_kwargs(self, func, kwargs)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:413`
- Doc: Prepare extra keyword arguments for scheduler functions.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### prepare_latents `def prepare_latents(self, batch_size, num_channels_latents, latent_height, latent_width, video_length, dtype, device, generator, latents)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:429`
- Doc: Prepare latents for video generation.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_guidance_scale_embedding `def get_guidance_scale_embedding(self, w, embedding_dim, dtype)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:483`
- Doc: See https://github.com/google-research/vdm/blob/dc27b98a554f65cdc654b800da5aa1846545d41b/model_vdm.py#L298
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### guidance_scale `def guidance_scale(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:517`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### guidance_rescale `def guidance_rescale(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:521`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### clip_skip `def clip_skip(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:525`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### do_classifier_free_guidance `def do_classifier_free_guidance(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:532`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### cross_attention_kwargs `def cross_attention_kwargs(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:536`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### num_timesteps `def num_timesteps(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:540`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### interrupt `def interrupt(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:544`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_byt5_text_tokens `def get_byt5_text_tokens(byt5_tokenizer, byt5_max_length, text_prompt)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:548`
- Doc: Tokenize text prompt for byT5 model.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _extract_glyph_texts `def _extract_glyph_texts(self, prompt)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:573`
- Doc: Extract glyph texts from prompt using regex pattern.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _process_single_byt5_prompt `def _process_single_byt5_prompt(self, prompt_text, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:589`
- Doc: Process a single prompt for byT5 encoding.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _prepare_byt5_embeddings `def _prepare_byt5_embeddings(self, prompts, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:623`
- Doc: Prepare byT5 embeddings for both positive and negative prompts.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### extract_image_features `def extract_image_features(self, reference_image)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:680`
- Doc: Extract features from a reference image using VisionEncoder.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _prepare_vision_states `def _prepare_vision_states(self, reference_image, target_resolution, latents, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:698`
- Doc: Prepare vision states for multitask training.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _prepare_cond_latents `def _prepare_cond_latents(self, task_type, cond_latents, latents, multitask_mask)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:734`
- Doc: Prepare conditional latents and mask for multitask training.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_task_mask `def get_task_mask(self, task_type, latent_target_length)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:766`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_closest_resolution_given_reference_image `def get_closest_resolution_given_reference_image(self, reference_image, target_resolution)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:776`
- Doc: Get closest supported resolution for a reference image.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_closest_resolution_given_original_size `def get_closest_resolution_given_original_size(self, origin_size, target_size)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:800`
- Doc: Get closest supported resolution for given original size and target resolution.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_image_condition_latents `def get_image_condition_latents(self, task_type, reference_image, height, width)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:826`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### vae_spatial_compression_ratio `def vae_spatial_compression_ratio(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:861`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### vae_temporal_compression_ratio `def vae_temporal_compression_ratio(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:868`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_latent_size `def get_latent_size(self, video_length, height, width)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:874`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### __call__ `def __call__(self, prompt, aspect_ratio, video_length, prompt_rewrite, num_inference_steps, guidance_scale, enable_sr, sr_num_inference_steps, negative_prompt, generator, seed, flow_shift, embedded_guidance_scale, reference_image, output_type, return_dict, return_pre_sr_video, enable_vae_tile_parallelism)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:886`
- Doc: Generates a video (or videos) based on text (and optionally image) conditions.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### ideal_resolution `def ideal_resolution(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1324`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### ideal_task `def ideal_task(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1328`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### use_meanflow `def use_meanflow(self)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1332`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### apply_infer_optimization `def apply_infer_optimization(self, infer_state, enable_offloading, enable_group_offloading, overlap_group_offloading)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1335`
- Doc: Apply inference optimizations to transformer based on infer_state.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### load_sr_transformer_upsampler `def load_sr_transformer_upsampler(cls, cached_folder, sr_version, transformer_dtype, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1416`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### create_sr_pipeline `def create_sr_pipeline(self, cached_folder, sr_version, transformer_dtype, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1426`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_transformer_version `def get_transformer_version(resolution, task, cfg_distilled, step_distilled, sparse_attn)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1452`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### create_pipeline `def create_pipeline(cls, pretrained_model_name_or_path, transformer_version, create_sr_pipeline, transformer_dtype, device, transformer_init_device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1467`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_offloading_config `def get_offloading_config(memory_limitation)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1550`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### get_vae_inference_config `def get_vae_inference_config(memory_limitation)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1566`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _load_text_encoders `def _load_text_encoders(cls, pretrained_model_path, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1582`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

### _load_vision_encoder `def _load_vision_encoder(cls, pretrained_model_name_or_path, device)`
- Defined: `hyvideo/pipelines/hunyuan_video_pipeline.py:1607`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/infer_state.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/autoencoders/__init__.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/text_encoders/byT5/__init__.py`, `hyvideo/models/text_encoders/byT5/format_prompt.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/models/vision_encoder/__init__.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/schedulers/scheduling_flow_match_discrete.py`, `hyvideo/utils/data_utils.py`, `hyvideo/utils/multitask_utils.py`, `hyvideo/utils/rewrite/rewrite_utils.py`
- Imported by: `generate.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`, `train.py`

## hyvideo/pipelines/hunyuan_video_sr_pipeline.py

### expand_dims `def expand_dims(tensor, ndim)`
- Defined: `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:42`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)`
- Defined: `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:49`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __call__ `def __call__(self, lr_bucket)`
- Defined: `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:62`
- Doc: Args:
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, base_resolution, text_encoder_2, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)`
- Defined: `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:87`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### add_noise_to_lq `def add_noise_to_lq(self, lq_latents, strength)`
- Defined: `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:142`
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _prepare_lq_cond_latents `def _prepare_lq_cond_latents(self, lq_latents)`
- Defined: `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:148`
- Doc: Prepare conditional latents and mask for multitask training.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __call__ `def __call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt, num_videos_per_prompt, generator, seed, embedded_guidance_scale, reference_image, lq_latents, output_type, return_dict, enable_vae_tile_parallelism)`
- Defined: `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:165`
- Doc: Runs the super-resolution (SR) pipeline for video generation.
- Depends on: `hyvideo/commons/__init__.py`, `hyvideo/commons/parallel_states.py`, `hyvideo/models/text_encoders/__init__.py`, `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/upsample.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/pipeline_utils.py`, `hyvideo/utils/data_utils.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/pipelines/pipeline_utils.py

### retrieve_timesteps `def retrieve_timesteps(scheduler, num_inference_steps, device, timesteps, sigmas)`
- Defined: `hyvideo/pipelines/pipeline_utils.py:21`
- Doc: Calls the scheduler's `set_timesteps` method and retrieves timesteps from the scheduler after the call. Handles
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### rescale_noise_cfg `def rescale_noise_cfg(noise_cfg, noise_pred_text, guidance_rescale)`
- Defined: `hyvideo/pipelines/pipeline_utils.py:86`
- Doc: Rescale `noise_cfg` according to `guidance_rescale`. Based on findings of [Common Diffusion Noise Schedules and
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/schedulers/scheduling_flow_match_discrete.py

### __init__ `def __init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift, n_tokens, flux_base_token, flux_max_token, flux_shift_factor)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:86`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### step_index `def step_index(self)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:119`
- Doc: The index counter for current timestep. It will increase 1 after each scheduler step.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### begin_index `def begin_index(self)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:126`
- Doc: The index for the first timestep. It should be set from pipeline with `set_begin_index` method.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### set_begin_index `def set_begin_index(self, begin_index)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:133`
- Doc: Sets the begin index for the scheduler. This function should be run from pipeline before the inference.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _sigma_to_t `def _sigma_to_t(self, sigma)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:143`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### set_timesteps `def set_timesteps(self, num_inference_steps, device, n_tokens)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:146`
- Doc: Sets the discrete timesteps used for the diffusion chain (to be run before inference).
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### index_for_timestep `def index_for_timestep(self, timestep, schedule_timesteps)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:182`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _init_step_index `def _init_step_index(self, timestep)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:196`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### scale_model_input `def scale_model_input(self, sample, timestep)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:204`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### get_lin_function `def get_lin_function(x1, y1, x2, y2)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:208`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### flux_time_shift `def flux_time_shift(mu, sigma, t)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:214`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### sd3_time_shift `def sd3_time_shift(self, t)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:217`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### step `def step(self, model_output, timestep, sample, generator, n_tokens, return_dict)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:220`
- Doc: Predict the sample from the previous timestep by reversing the SDE. This function propagates the diffusion
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __len__ `def __len__(self)`
- Defined: `hyvideo/schedulers/scheduling_flow_match_discrete.py:291`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/utils/communications.py

### broadcast `def broadcast(input_, group)`
- Defined: `hyvideo/utils/communications.py:24`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### _all_to_all_4D `def _all_to_all_4D(input, scatter_idx, gather_idx, group)`
- Defined: `hyvideo/utils/communications.py:29`
- Doc: all-to-all for QKV
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### all_to_all_4D `def all_to_all_4D(input_, group, scatter_dim, gather_dim)`
- Defined: `hyvideo/utils/communications.py:174`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### _all_to_all `def _all_to_all(input_, world_size, group, scatter_dim, gather_dim)`
- Defined: `hyvideo/utils/communications.py:180`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### all_to_all `def all_to_all(input_, group, scatter_dim, gather_dim)`
- Defined: `hyvideo/utils/communications.py:233`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### all_gather `def all_gather(input_, dim, group)`
- Defined: `hyvideo/utils/communications.py:304`
- Doc: Performs an all-gather operation on the input tensor along the specified dimension.
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### forward `def forward(ctx, group, input, scatter_idx, gather_idx)`
- Defined: `hyvideo/utils/communications.py:149`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### backward `def backward(ctx)`
- Defined: `hyvideo/utils/communications.py:163`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### forward `def forward(ctx, input_, process_group, scatter_dim, gather_dim)`
- Defined: `hyvideo/utils/communications.py:206`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### backward `def backward(ctx, grad_output)`
- Defined: `hyvideo/utils/communications.py:217`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### forward `def forward(ctx, op, group, tensor)`
- Defined: `hyvideo/utils/communications.py:242`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### backward `def backward(ctx, grad_output)`
- Defined: `hyvideo/utils/communications.py:251`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### forward `def forward(ctx, input_, dim, group)`
- Defined: `hyvideo/utils/communications.py:264`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

### backward `def backward(ctx, grad_output)`
- Defined: `hyvideo/utils/communications.py:283`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/models/transformers/modules/attention.py`

## hyvideo/utils/data_utils.py

### resize_and_center_crop `def resize_and_center_crop(image, target_width, target_height)`
- Defined: `hyvideo/utils/data_utils.py:20`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### get_closest_ratio `def get_closest_ratio(height, width, ratios, buckets)`
- Defined: `hyvideo/utils/data_utils.py:38`
- Doc: Get the closest ratio in the buckets.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

### generate_crop_size_list `def generate_crop_size_list(base_size, patch_size, max_ratio)`
- Defined: `hyvideo/utils/data_utils.py:61`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`, `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

## hyvideo/utils/flash_attn_no_pad.py

### flash_attn_no_pad `def flash_attn_no_pad(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`
- Defined: `hyvideo/utils/flash_attn_no_pad.py:20`
- Imported by: `hyvideo/models/transformers/modules/attention.py`

### flash_attn_no_pad_v3 `def flash_attn_no_pad_v3(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`
- Defined: `hyvideo/utils/flash_attn_no_pad.py:52`
- Imported by: `hyvideo/models/transformers/modules/attention.py`

## hyvideo/utils/infer_utils.py

### torch_compile_wrapper `def torch_compile_wrapper()`
- Defined: `hyvideo/utils/infer_utils.py:19`

### decorator `def decorator(func)`
- Defined: `hyvideo/utils/infer_utils.py:20`

### wrapper `def wrapper(self)`
- Defined: `hyvideo/utils/infer_utils.py:21`

## hyvideo/utils/multitask_utils.py

### numpy_to_pil `def numpy_to_pil(images)`
- Defined: `hyvideo/utils/multitask_utils.py:23`
- Doc: Convert a numpy image or a batch of images to a PIL image.
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### merge_tensor_by_mask `def merge_tensor_by_mask(tensor_1, tensor_2, mask, dim)`
- Defined: `hyvideo/utils/multitask_utils.py:45`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/utils/rewrite/clients.py

### __init__ `def __init__(self)`
- Defined: `hyvideo/utils/rewrite/clients.py:30`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### _deserialize `def _deserialize(self, obj)`
- Defined: `hyvideo/utils/rewrite/clients.py:33`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### __init__ `def __init__(self, key_id, key_secret)`
- Defined: `hyvideo/utils/rewrite/clients.py:38`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### run_single_recaption `def run_single_recaption(self, system_prompt, input_prompt)`
- Defined: `hyvideo/utils/rewrite/clients.py:51`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### __init__ `def __init__(self, base_url, model_name)`
- Defined: `hyvideo/utils/rewrite/clients.py:85`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### qwen_api_call `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens)`
- Defined: `hyvideo/utils/rewrite/clients.py:90`
- Doc: Use Qwen Chat API to perform text rewriting, parse <think>...</think> sections for reasoning content, and return (thinki
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### run_single_recaption `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens)`
- Defined: `hyvideo/utils/rewrite/clients.py:128`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### __init__ `def __init__(self, base_url, model_name)`
- Defined: `hyvideo/utils/rewrite/clients.py:135`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### _encode_image_to_base64 `def _encode_image_to_base64(self, image_path, max_dimension)`
- Defined: `hyvideo/utils/rewrite/clients.py:141`
- Doc: 参考 hyvideo/utils/rewrite/qwen_vllm.py 的实现：
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### qwen_api_call `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens, img_path)`
- Defined: `hyvideo/utils/rewrite/clients.py:176`
- Doc: Use Qwen3-VL to perform text rewriting.
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

### run_single_recaption `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens, img_path)`
- Defined: `hyvideo/utils/rewrite/clients.py:246`
- Imported by: `hyvideo/utils/rewrite/rewrite_utils.py`

## hyvideo/utils/rewrite/rewrite_utils.py

### t2v_rewrite `def t2v_rewrite(user_prompt, rewrite_client)`
- Defined: `hyvideo/utils/rewrite/rewrite_utils.py:22`
- Depends on: `hyvideo/utils/rewrite/clients.py`, `hyvideo/utils/rewrite/i2v_prompt.py`, `hyvideo/utils/rewrite/t2v_prompt.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### i2v_rewrite `def i2v_rewrite(user_input, img_path, rewrite_client)`
- Defined: `hyvideo/utils/rewrite/rewrite_utils.py:40`
- Doc: Use a rewrite client to generate a rewritten prompt for image-to-video.
- Depends on: `hyvideo/utils/rewrite/clients.py`, `hyvideo/utils/rewrite/i2v_prompt.py`, `hyvideo/utils/rewrite/t2v_prompt.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

### run_prompt_rewrite `def run_prompt_rewrite(user_prompt, img_path, task_type)`
- Defined: `hyvideo/utils/rewrite/rewrite_utils.py:63`
- Depends on: `hyvideo/utils/rewrite/clients.py`, `hyvideo/utils/rewrite/i2v_prompt.py`, `hyvideo/utils/rewrite/t2v_prompt.py`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`

## train.py

### str_to_bool `def str_to_bool(value)`
- Defined: `train.py:98`
- Doc: Convert string to boolean, supporting true/false, 1/0, yes/no.
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### save_video `def save_video(video, path)`
- Defined: `train.py:114`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### timestep_transform `def timestep_transform(timesteps, T, shift)`
- Defined: `train.py:269`
- Doc: Transform timesteps with shift
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### is_src `def is_src(src, group_src, group)`
- Defined: `train.py:278`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### broadcast_object `def broadcast_object(obj, src, group, device, group_src)`
- Defined: `train.py:287`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### broadcast_tensor `def broadcast_tensor(tensor, src, group, async_op, group_src)`
- Defined: `train.py:305`
- Doc: shape and dtype safe broadcast of tensor
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### sync_tensor_for_sp `def sync_tensor_for_sp(tensor, sp_group)`
- Defined: `train.py:333`
- Doc: Sync tensor within sequence parallel group.
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### create_dummy_dataloader `def create_dummy_dataloader(config)`
- Defined: `train.py:1047`
- Doc: Create a dummy dataloader for testing.
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### main `def main()`
- Defined: `train.py:1144`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, T)`
- Defined: `train.py:188`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### forward `def forward(self, x0, x1, t)`
- Defined: `train.py:191`
- Doc: Linear interpolation: x_t = (1 - t/T) * x0 + (t/T) * x1
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, T, device, snr_type)`
- Defined: `train.py:209`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _check_interval `def _check_interval(self, eval)`
- Defined: `train.py:219`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### sample `def sample(self, batch_size, device)`
- Defined: `train.py:226`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, config)`
- Defined: `train.py:348`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _set_seed `def _set_seed(self, seed)`
- Defined: `train.py:406`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _build_models `def _build_models(self)`
- Defined: `train.py:412`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _apply_lora `def _apply_lora(self)`
- Defined: `train.py:464`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _apply_fsdp `def _apply_fsdp(self)`
- Defined: `train.py:498`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _apply_gradient_checkpointing `def _apply_gradient_checkpointing(self)`
- Defined: `train.py:529`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### _build_optimizer `def _build_optimizer(self)`
- Defined: `train.py:565`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### encode_text `def encode_text(self, prompts, data_type)`
- Defined: `train.py:592`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### encode_byt5 `def encode_byt5(self, text_ids, attention_mask)`
- Defined: `train.py:608`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### encode_images `def encode_images(self, images)`
- Defined: `train.py:615`
- Doc: Encode images to vision states (for i2v)
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### encode_vae `def encode_vae(self, images)`
- Defined: `train.py:625`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### get_condition `def get_condition(self, latents, task_type)`
- Defined: `train.py:641`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### sample_task `def sample_task(self, data_type)`
- Defined: `train.py:654`
- Doc: Sample task type based on data type and configuration.
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### prepare_batch `def prepare_batch(self, batch)`
- Defined: `train.py:671`
- Doc: Prepare batch for training.
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### train_step `def train_step(self, batch)`
- Defined: `train.py:776`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### save_checkpoint `def save_checkpoint(self, step)`
- Defined: `train.py:828`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### load_pretrained_lora `def load_pretrained_lora(self, lora_dir)`
- Defined: `train.py:892`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### load_checkpoint `def load_checkpoint(self, checkpoint_path)`
- Defined: `train.py:901`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### train `def train(self, dataloader)`
- Defined: `train.py:959`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### validate `def validate(self, step)`
- Defined: `train.py:1001`
- Doc: Implement your own validation logic here
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### non_reentrant_wrapper `def non_reentrant_wrapper(module)`
- Defined: `train.py:547`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### selective_checkpointing `def selective_checkpointing(submodule)`
- Defined: `train.py:553`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __init__ `def __init__(self, size)`
- Defined: `train.py:1109`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __len__ `def __len__(self)`
- Defined: `train.py:1112`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

### __getitem__ `def __getitem__(self, idx)`
- Defined: `train.py:1115`
- Depends on: `hyvideo/commons/parallel_states.py`, `hyvideo/optim/muon.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`
