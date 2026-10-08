# hyvideo/pipelines

*Community 0 | 17 files | cohesion 0.74*

## Definition

This community groups 17 file(s) rooted at `hyvideo/pipelines` with dominant language py (cohesion 0.74). Central symbols: `AttnBlock`, `AutoencoderKLConv3D`, `BucketMap`, `ByT5Mapper`, `CausalConv3d`, `Decoder`, `DecoderOutput`, `Downsample`. Core file: `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py` (62 symbols). Documented purpose: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain .

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `generate.py` | py | utility | 8 | yes |
| `hyvideo/commons/infer_state.py` | py | utility | 4 | yes |
| `hyvideo/commons/parallel_states.py` | py | utility | 8 | yes |
| `hyvideo/models/autoencoders/__init__.py` | py | business_logic | 0 | yes |
| `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py` | py | business_logic | 62 | yes |
| `hyvideo/models/text_encoders/__init__.py` | py | business_logic | 14 | yes |
| `hyvideo/models/text_encoders/byT5/__init__.py` | py | business_logic | 7 | yes |
| `hyvideo/models/text_encoders/byT5/format_prompt.py` | py | business_logic | 5 | yes |
| `hyvideo/models/transformers/modules/upsample.py` | py | business_logic | 11 | yes |
| `hyvideo/optim/muon.py` | py | utility | 6 | no |
| `hyvideo/pipelines/hunyuan_video_pipeline.py` | py | utility | 43 | yes |
| `hyvideo/pipelines/hunyuan_video_sr_pipeline.py` | py | utility | 10 | yes |
| `hyvideo/pipelines/pipeline_utils.py` | py | utility | 2 | yes |
| `hyvideo/schedulers/scheduling_flow_match_discrete.py` | py | infrastructure | 16 | yes |
| `hyvideo/utils/data_utils.py` | py | data_access | 3 | yes |
| `hyvideo/utils/multitask_utils.py` | py | utility | 2 | yes |
| `train.py` | py | utility | 45 | yes |

## Key Symbols

- `save_video` (function, `generate.py:42`) `def save_video(video, path)`
- `rank0_log` (function, `generate.py:50`) `def rank0_log(message, level)`
- `save_config` (function, `generate.py:54`) `def save_config(args, output_path, task, transformer_version)`
- `str_to_bool` (function, `generate.py:81`) `def str_to_bool(value)` - Convert string to boolean, supporting true/false, 1/0, yes/no.
- `load_checkpoint_to_transformer` (function, `generate.py:96`) `def load_checkpoint_to_transformer(pipe, checkpoint_path)`
- `load_lora_adapter` (function, `generate.py:112`) `def load_lora_adapter(pipe, lora_path)`
- `generate_video` (function, `generate.py:128`) `def generate_video(args)`
- `main` (function, `generate.py:274`) `def main()`
- `InferState` (class, `hyvideo/commons/infer_state.py:21`) `class InferState`
- `parse_range` (method, `hyvideo/commons/infer_state.py:42`) `def parse_range(value)`
- `initialize_infer_state` (method, `hyvideo/commons/infer_state.py:49`) `def initialize_infer_state(args)`
- `get_infer_state` (method, `hyvideo/commons/infer_state.py:87`) `def get_infer_state()`
- `ParallelDims` (class, `hyvideo/commons/parallel_states.py:24`) `class ParallelDims`
- `__post_init__` (method, `hyvideo/commons/parallel_states.py:29`) `def __post_init__(self)`
- `build_mesh` (method, `hyvideo/commons/parallel_states.py:37`) `def build_mesh(self, device_type)`
- `sp_enabled` (method, `hyvideo/commons/parallel_states.py:68`) `def sp_enabled(self)`
- `sp_mesh` (method, `hyvideo/commons/parallel_states.py:72`) `def sp_mesh(self)`
- `dp_enabled` (method, `hyvideo/commons/parallel_states.py:76`) `def dp_enabled(self)`
- `initialize_parallel_state` (method, `hyvideo/commons/parallel_states.py:81`) `def initialize_parallel_state(sp, dp_replicate)`
- `get_parallel_state` (method, `hyvideo/commons/parallel_states.py:89`) `def get_parallel_state()`
- `DecoderOutput` (class, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:40`) `class DecoderOutput(BaseOutput)`
- `swish` (method, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:45`) `def swish(x, inplace)` - Applies the swish activation function (SiLU) with optional inplace support.
- `forward_with_checkpointing` (method, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:50`) `def forward_with_checkpointing(module)` - Forward with optional gradient checkpointing.
- `create_custom_forward` (method, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:52`) `def create_custom_forward(module)`
- `custom_forward` (method, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:53`) `def custom_forward()`
- `PatchCausalConv3d` (class, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:65`) `class PatchCausalConv3d(Conv3d)` - Causal Conv3d with efficient patch processing for large tensors.
- `find_split_indices` (method, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:67`) `def find_split_indices(self, seq_len, part_num)`
- `forward` (method, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:86`) `def forward(self, input)`
- `RMS_norm` (class, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:110`) `class RMS_norm(Module)` - Root Mean Square Layer Normalization for Channel-First or Last
- `__init__` (method, `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py:113`) `def __init__(self, dim, channel_first, images, bias)`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 27
- Cross-boundary resolved imports (EXTRACTED): 9

## Connections

- [EXTRACTED] depends_on community 1 <-> 0 (strength 0.9): Extracted import edge crosses communities: hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py imports hyvideo/models/text_encoders/byT5/__init__.py.
- [EXTRACTED] depends_on community 2 <-> 0 (strength 0.9): Extracted import edge crosses communities: hyvideo/models/transformers/modules/attention.py imports hyvideo/commons/parallel_states.py.
- [EXTRACTED] depends_on community 0 <-> 3 (strength 0.9): Extracted import edge crosses communities: hyvideo/pipelines/hunyuan_video_pipeline.py imports hyvideo/utils/rewrite/rewrite_utils.py.
- [INFERRED] shares_context community 0 <-> 4 (strength 0.5): Inferred shared context (language py) with no import path between community 0 (hyvideo/pipelines) and community 4 (orphans).

## Risks

- [cycle] `hyvideo/pipelines/hunyuan_video_pipeline.py` -> `hyvideo/pipelines/hunyuan_video_sr_pipeline.py` -> `hyvideo/pipelines/hunyuan_video_pipeline.py`
- [dataflow UNCHECKED_ALLOC] `hyvideo/pipelines/hunyuan_video_pipeline.py:985` `__call__` `reference_image`: Result of allocator stored in `reference_image` is never checked against NULL.
- [dataflow UNCHECKED_ALLOC] `hyvideo/pipelines/hunyuan_video_sr_pipeline.py:228` `__call__` `reference_image`: Result of allocator stored in `reference_image` is never checked against NULL.

## Open Questions

- Why do 1 file(s) lack file-level docs (e.g. `hyvideo/optim/muon.py`)? What purpose do they serve?
- Can the cycle `hyvideo/pipelines/hunyuan_video_pipeline.py` -> `hyvideo/pipelines/hunyuan_video_sr_pipeline.py` be broken with an interface?
- What would break if the most connected file in hyvideo/pipelines changed?
- Should hyvideo/pipelines be split, given cohesion 0.74?

## Sources

- `generate.py`
- `hyvideo/commons/infer_state.py`
- `hyvideo/commons/parallel_states.py`
- `hyvideo/models/autoencoders/__init__.py`
- `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
- `hyvideo/models/text_encoders/__init__.py`
- `hyvideo/models/text_encoders/byT5/__init__.py`
- `hyvideo/models/text_encoders/byT5/format_prompt.py`
- `hyvideo/models/transformers/modules/upsample.py`
- `hyvideo/optim/muon.py`
- `hyvideo/pipelines/hunyuan_video_pipeline.py`
- `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
- `hyvideo/pipelines/pipeline_utils.py`
- `hyvideo/schedulers/scheduling_flow_match_discrete.py`
- `hyvideo/utils/data_utils.py`
- `hyvideo/utils/multitask_utils.py`
- `train.py`
