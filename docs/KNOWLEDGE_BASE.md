# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM.
> No LLMs. No tokens. Pure static analysis. See more [here](https://github.com/grisuno/ReadMenator)

**Total Files Parsed:** 39 | **Total Symbols Extracted:** 420 | **Total Imports:** 293

## Structural Knowledge Map
> **Note:** The visual graph below has been intelligently pruned to the top 300 most relevant nodes to prevent rendering crashes. Full details of all 39 files are documented below.

```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray:5 5,color:#aaa;
    hyvideo_pipelines_hunyuan_video_pipeline_py["hunyuan_video_pipeline.py (py)"]
    class hyvideo_pipelines_hunyuan_video_pipeline_py mod;
    hyvideo_pipelines_hunyuan_video_pipeline_py_HunyuanVideoPipelineOutput["HunyuanVideoPipelineOutput"]
    class hyvideo_pipelines_hunyuan_video_pipeline_py_HunyuanVideoPipelineOutput cls;
    hyvideo_pipelines_hunyuan_video_pipeline_py --> hyvideo_pipelines_hunyuan_video_pipeline_py_HunyuanVideoPipelineOutput
    hyvideo_pipelines_hunyuan_video_pipeline_py_HunyuanVideo_1_5_Pipeline["HunyuanVideo_1_5_Pipeline"]
    class hyvideo_pipelines_hunyuan_video_pipeline_py_HunyuanVideo_1_5_Pipeline cls;
    hyvideo_pipelines_hunyuan_video_pipeline_py --> hyvideo_pipelines_hunyuan_video_pipeline_py_HunyuanVideo_1_5_Pipeline
    hyvideo_pipelines_hunyuan_video_pipeline_py___init__["__init__"]
    class hyvideo_pipelines_hunyuan_video_pipeline_py___init__ fn;
    hyvideo_pipelines_hunyuan_video_pipeline_py --> hyvideo_pipelines_hunyuan_video_pipeline_py___init__
    hyvideo_pipelines_hunyuan_video_pipeline_py__create_scheduler["_create_scheduler"]
    class hyvideo_pipelines_hunyuan_video_pipeline_py__create_scheduler fn;
    hyvideo_pipelines_hunyuan_video_pipeline_py --> hyvideo_pipelines_hunyuan_video_pipeline_py__create_scheduler
    hyvideo_pipelines_hunyuan_video_pipeline_py__load_byt5["_load_byt5"]
    class hyvideo_pipelines_hunyuan_video_pipeline_py__load_byt5 fn;
    hyvideo_pipelines_hunyuan_video_pipeline_py --> hyvideo_pipelines_hunyuan_video_pipeline_py__load_byt5
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py["hunyuanvideo_1_5_transformer.py (py)"]
    class hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py mod;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_MMDoubleStreamBlock["MMDoubleStreamBlock"]
    class hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_MMDoubleStreamBlock cls;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py --> hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_MMDoubleStreamBlock
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_MMSingleStreamBlock["MMSingleStreamBlock"]
    class hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_MMSingleStreamBlock cls;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py --> hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_MMSingleStreamBlock
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_HunyuanVideo_1_5_DiffusionTransformer["HunyuanVideo_1_5_DiffusionTransformer"]
    class hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_HunyuanVideo_1_5_DiffusionTransformer cls;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py --> hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_HunyuanVideo_1_5_DiffusionTransformer
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py___init__["__init__"]
    class hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py___init__ fn;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py --> hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py___init__
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_enable_deterministic["enable_deterministic"]
    class hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_enable_deterministic fn;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py --> hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py_enable_deterministic
    train_py["train.py (py)"]
    class train_py mod;
    train_py_SNRType["SNRType"]
    class train_py_SNRType cls;
    train_py --> train_py_SNRType
    train_py_str_to_bool["str_to_bool"]
    class train_py_str_to_bool fn;
    train_py --> train_py_str_to_bool
    train_py_save_video["save_video"]
    class train_py_save_video fn;
    train_py --> train_py_save_video
    train_py_TrainingConfig["TrainingConfig"]
    class train_py_TrainingConfig cls;
    train_py --> train_py_TrainingConfig
    train_py_LinearInterpolationSchedule["LinearInterpolationSchedule"]
    class train_py_LinearInterpolationSchedule cls;
    train_py --> train_py_LinearInterpolationSchedule
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py["hunyuan_video_sr_pipeline.py (py)"]
    class hyvideo_pipelines_hunyuan_video_sr_pipeline_py mod;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py_expand_dims["expand_dims"]
    class hyvideo_pipelines_hunyuan_video_sr_pipeline_py_expand_dims fn;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py --> hyvideo_pipelines_hunyuan_video_sr_pipeline_py_expand_dims
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py_BucketMap["BucketMap"]
    class hyvideo_pipelines_hunyuan_video_sr_pipeline_py_BucketMap cls;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py --> hyvideo_pipelines_hunyuan_video_sr_pipeline_py_BucketMap
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_PipelineOutput["HunyuanVideo_1_5_SR_PipelineOutput"]
    class hyvideo_pipelines_hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_PipelineOutput cls;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py --> hyvideo_pipelines_hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_PipelineOutput
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_Pipeline["HunyuanVideo_1_5_SR_Pipeline"]
    class hyvideo_pipelines_hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_Pipeline cls;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py --> hyvideo_pipelines_hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_Pipeline
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py___init__["__init__"]
    class hyvideo_pipelines_hunyuan_video_sr_pipeline_py___init__ fn;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py --> hyvideo_pipelines_hunyuan_video_sr_pipeline_py___init__
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py["hunyuanvideo_15_vae.py (py)"]
    class hyvideo_models_autoencoders_hunyuanvideo_15_vae_py mod;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_DecoderOutput["DecoderOutput"]
    class hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_DecoderOutput cls;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py --> hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_DecoderOutput
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_swish["swish"]
    class hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_swish fn;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py --> hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_swish
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_forward_with_checkpointing["forward_with_checkpointing"]
    class hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_forward_with_checkpointing fn;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py --> hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_forward_with_checkpointing
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_PatchCausalConv3d["PatchCausalConv3d"]
    class hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_PatchCausalConv3d cls;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py --> hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_PatchCausalConv3d
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_RMS_norm["RMS_norm"]
    class hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_RMS_norm cls;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py --> hyvideo_models_autoencoders_hunyuanvideo_15_vae_py_RMS_norm
    generate_py["generate.py (py)"]
    class generate_py mod;
    generate_py_save_video["save_video"]
    class generate_py_save_video fn;
    generate_py --> generate_py_save_video
    generate_py_rank0_log["rank0_log"]
    class generate_py_rank0_log fn;
    generate_py --> generate_py_rank0_log
    generate_py_save_config["save_config"]
    class generate_py_save_config fn;
    generate_py --> generate_py_save_config
    generate_py_str_to_bool["str_to_bool"]
    class generate_py_str_to_bool fn;
    generate_py --> generate_py_str_to_bool
    generate_py_load_checkpoint_to_transformer["load_checkpoint_to_transformer"]
    class generate_py_load_checkpoint_to_transformer fn;
    generate_py --> generate_py_load_checkpoint_to_transformer
    hyvideo_commons___init___py["__init__.py (py)"]
    class hyvideo_commons___init___py mod;
    hyvideo_commons___init___py__ntuple["_ntuple"]
    class hyvideo_commons___init___py__ntuple fn;
    hyvideo_commons___init___py --> hyvideo_commons___init___py__ntuple
    hyvideo_commons___init___py_is_flash2_available["is_flash2_available"]
    class hyvideo_commons___init___py_is_flash2_available fn;
    hyvideo_commons___init___py --> hyvideo_commons___init___py_is_flash2_available
    hyvideo_commons___init___py_is_flash3_available["is_flash3_available"]
    class hyvideo_commons___init___py_is_flash3_available fn;
    hyvideo_commons___init___py --> hyvideo_commons___init___py_is_flash3_available
    hyvideo_commons___init___py_is_flash_available["is_flash_available"]
    class hyvideo_commons___init___py_is_flash_available fn;
    hyvideo_commons___init___py --> hyvideo_commons___init___py_is_flash_available
    hyvideo_commons___init___py_is_sparse_attn_supported["is_sparse_attn_supported"]
    class hyvideo_commons___init___py_is_sparse_attn_supported fn;
    hyvideo_commons___init___py --> hyvideo_commons___init___py_is_sparse_attn_supported
    hyvideo_utils_rewrite_clients_py["clients.py (py)"]
    class hyvideo_utils_rewrite_clients_py mod;
    hyvideo_utils_rewrite_clients_py_NonStreamResponse["NonStreamResponse"]
    class hyvideo_utils_rewrite_clients_py_NonStreamResponse cls;
    hyvideo_utils_rewrite_clients_py --> hyvideo_utils_rewrite_clients_py_NonStreamResponse
    hyvideo_utils_rewrite_clients_py_DeepSeekClient["DeepSeekClient"]
    class hyvideo_utils_rewrite_clients_py_DeepSeekClient cls;
    hyvideo_utils_rewrite_clients_py --> hyvideo_utils_rewrite_clients_py_DeepSeekClient
    hyvideo_utils_rewrite_clients_py_QwenClient["QwenClient"]
    class hyvideo_utils_rewrite_clients_py_QwenClient cls;
    hyvideo_utils_rewrite_clients_py --> hyvideo_utils_rewrite_clients_py_QwenClient
    hyvideo_utils_rewrite_clients_py_QwenVLClient["QwenVLClient"]
    class hyvideo_utils_rewrite_clients_py_QwenVLClient cls;
    hyvideo_utils_rewrite_clients_py --> hyvideo_utils_rewrite_clients_py_QwenVLClient
    hyvideo_utils_rewrite_clients_py___init__["__init__"]
    class hyvideo_utils_rewrite_clients_py___init__ fn;
    hyvideo_utils_rewrite_clients_py --> hyvideo_utils_rewrite_clients_py___init__
    hyvideo_models_transformers_modules_attention_py["attention.py (py)"]
    class hyvideo_models_transformers_modules_attention_py mod;
    hyvideo_models_transformers_modules_attention_py_attention["attention"]
    class hyvideo_models_transformers_modules_attention_py_attention fn;
    hyvideo_models_transformers_modules_attention_py --> hyvideo_models_transformers_modules_attention_py_attention
    hyvideo_models_transformers_modules_attention_py_parallel_attention["parallel_attention"]
    class hyvideo_models_transformers_modules_attention_py_parallel_attention fn;
    hyvideo_models_transformers_modules_attention_py --> hyvideo_models_transformers_modules_attention_py_parallel_attention
    hyvideo_models_transformers_modules_attention_py_sequence_parallel_attention["sequence_parallel_attention"]
    class hyvideo_models_transformers_modules_attention_py_sequence_parallel_attention fn;
    hyvideo_models_transformers_modules_attention_py --> hyvideo_models_transformers_modules_attention_py_sequence_parallel_attention
    hyvideo_models_transformers_modules_attention_py_shrink_head["shrink_head"]
    class hyvideo_models_transformers_modules_attention_py_shrink_head fn;
    hyvideo_models_transformers_modules_attention_py --> hyvideo_models_transformers_modules_attention_py_shrink_head
    hyvideo_models_transformers_modules_attention_py_score_mod["score_mod"]
    class hyvideo_models_transformers_modules_attention_py_score_mod fn;
    hyvideo_models_transformers_modules_attention_py --> hyvideo_models_transformers_modules_attention_py_score_mod
    hyvideo_models_transformers_modules_upsample_py["upsample.py (py)"]
    class hyvideo_models_transformers_modules_upsample_py mod;
    hyvideo_models_transformers_modules_upsample_py_UpsamplerType["UpsamplerType"]
    class hyvideo_models_transformers_modules_upsample_py_UpsamplerType cls;
    hyvideo_models_transformers_modules_upsample_py --> hyvideo_models_transformers_modules_upsample_py_UpsamplerType
    hyvideo_models_transformers_modules_upsample_py_UpsamplerConfig["UpsamplerConfig"]
    class hyvideo_models_transformers_modules_upsample_py_UpsamplerConfig cls;
    hyvideo_models_transformers_modules_upsample_py --> hyvideo_models_transformers_modules_upsample_py_UpsamplerConfig
    hyvideo_models_transformers_modules_upsample_py_SRResidualCausalBlock3D["SRResidualCausalBlock3D"]
    class hyvideo_models_transformers_modules_upsample_py_SRResidualCausalBlock3D cls;
    hyvideo_models_transformers_modules_upsample_py --> hyvideo_models_transformers_modules_upsample_py_SRResidualCausalBlock3D
    hyvideo_models_transformers_modules_upsample_py_SRTo720pUpsampler["SRTo720pUpsampler"]
    class hyvideo_models_transformers_modules_upsample_py_SRTo720pUpsampler cls;
    hyvideo_models_transformers_modules_upsample_py --> hyvideo_models_transformers_modules_upsample_py_SRTo720pUpsampler
    hyvideo_models_transformers_modules_upsample_py_SRTo1080pUpsampler["SRTo1080pUpsampler"]
    class hyvideo_models_transformers_modules_upsample_py_SRTo1080pUpsampler cls;
    hyvideo_models_transformers_modules_upsample_py --> hyvideo_models_transformers_modules_upsample_py_SRTo1080pUpsampler
    hyvideo_models_transformers_modules_token_refiner_py["token_refiner.py (py)"]
    class hyvideo_models_transformers_modules_token_refiner_py mod;
    hyvideo_models_transformers_modules_token_refiner_py_IndividualTokenRefinerBlock["IndividualTokenRefinerBlock"]
    class hyvideo_models_transformers_modules_token_refiner_py_IndividualTokenRefinerBlock cls;
    hyvideo_models_transformers_modules_token_refiner_py --> hyvideo_models_transformers_modules_token_refiner_py_IndividualTokenRefinerBlock
    hyvideo_models_transformers_modules_token_refiner_py_IndividualTokenRefiner["IndividualTokenRefiner"]
    class hyvideo_models_transformers_modules_token_refiner_py_IndividualTokenRefiner cls;
    hyvideo_models_transformers_modules_token_refiner_py --> hyvideo_models_transformers_modules_token_refiner_py_IndividualTokenRefiner
    hyvideo_models_transformers_modules_token_refiner_py_SingleTokenRefiner["SingleTokenRefiner"]
    class hyvideo_models_transformers_modules_token_refiner_py_SingleTokenRefiner cls;
    hyvideo_models_transformers_modules_token_refiner_py --> hyvideo_models_transformers_modules_token_refiner_py_SingleTokenRefiner
    hyvideo_models_transformers_modules_token_refiner_py___init__["__init__"]
    class hyvideo_models_transformers_modules_token_refiner_py___init__ fn;
    hyvideo_models_transformers_modules_token_refiner_py --> hyvideo_models_transformers_modules_token_refiner_py___init__
    hyvideo_models_transformers_modules_token_refiner_py_forward["forward"]
    class hyvideo_models_transformers_modules_token_refiner_py_forward fn;
    hyvideo_models_transformers_modules_token_refiner_py --> hyvideo_models_transformers_modules_token_refiner_py_forward
    hyvideo_schedulers_scheduling_flow_match_discrete_py["scheduling_flow_match_discrete.py (py)"]
    class hyvideo_schedulers_scheduling_flow_match_discrete_py mod;
    hyvideo_schedulers_scheduling_flow_match_discrete_py_FlowMatchDiscreteSchedulerOutput["FlowMatchDiscreteSchedulerOutput"]
    class hyvideo_schedulers_scheduling_flow_match_discrete_py_FlowMatchDiscreteSchedulerOutput cls;
    hyvideo_schedulers_scheduling_flow_match_discrete_py --> hyvideo_schedulers_scheduling_flow_match_discrete_py_FlowMatchDiscreteSchedulerOutput
    hyvideo_schedulers_scheduling_flow_match_discrete_py_FlowMatchDiscreteScheduler["FlowMatchDiscreteScheduler"]
    class hyvideo_schedulers_scheduling_flow_match_discrete_py_FlowMatchDiscreteScheduler cls;
    hyvideo_schedulers_scheduling_flow_match_discrete_py --> hyvideo_schedulers_scheduling_flow_match_discrete_py_FlowMatchDiscreteScheduler
    hyvideo_schedulers_scheduling_flow_match_discrete_py___init__["__init__"]
    class hyvideo_schedulers_scheduling_flow_match_discrete_py___init__ fn;
    hyvideo_schedulers_scheduling_flow_match_discrete_py --> hyvideo_schedulers_scheduling_flow_match_discrete_py___init__
    hyvideo_schedulers_scheduling_flow_match_discrete_py_step_index["step_index"]
    class hyvideo_schedulers_scheduling_flow_match_discrete_py_step_index fn;
    hyvideo_schedulers_scheduling_flow_match_discrete_py --> hyvideo_schedulers_scheduling_flow_match_discrete_py_step_index
    hyvideo_schedulers_scheduling_flow_match_discrete_py_begin_index["begin_index"]
    class hyvideo_schedulers_scheduling_flow_match_discrete_py_begin_index fn;
    hyvideo_schedulers_scheduling_flow_match_discrete_py --> hyvideo_schedulers_scheduling_flow_match_discrete_py_begin_index
    hyvideo_models_text_encoders___init___py["__init__.py (py)"]
    class hyvideo_models_text_encoders___init___py mod;
    hyvideo_models_text_encoders___init___py_use_default["use_default"]
    class hyvideo_models_text_encoders___init___py_use_default fn;
    hyvideo_models_text_encoders___init___py --> hyvideo_models_text_encoders___init___py_use_default
    hyvideo_models_text_encoders___init___py_load_text_encoder["load_text_encoder"]
    class hyvideo_models_text_encoders___init___py_load_text_encoder fn;
    hyvideo_models_text_encoders___init___py --> hyvideo_models_text_encoders___init___py_load_text_encoder
    hyvideo_models_text_encoders___init___py_load_tokenizer["load_tokenizer"]
    class hyvideo_models_text_encoders___init___py_load_tokenizer fn;
    hyvideo_models_text_encoders___init___py --> hyvideo_models_text_encoders___init___py_load_tokenizer
    hyvideo_models_text_encoders___init___py_TextEncoderModelOutput["TextEncoderModelOutput"]
    class hyvideo_models_text_encoders___init___py_TextEncoderModelOutput cls;
    hyvideo_models_text_encoders___init___py --> hyvideo_models_text_encoders___init___py_TextEncoderModelOutput
    hyvideo_models_text_encoders___init___py_TextEncoder["TextEncoder"]
    class hyvideo_models_text_encoders___init___py_TextEncoder cls;
    hyvideo_models_text_encoders___init___py --> hyvideo_models_text_encoders___init___py_TextEncoder
    hyvideo_models_vision_encoder___init___py["__init__.py (py)"]
    class hyvideo_models_vision_encoder___init___py mod;
    hyvideo_models_vision_encoder___init___py_use_default["use_default"]
    class hyvideo_models_vision_encoder___init___py_use_default fn;
    hyvideo_models_vision_encoder___init___py --> hyvideo_models_vision_encoder___init___py_use_default
    hyvideo_models_vision_encoder___init___py_load_vision_encoder["load_vision_encoder"]
    class hyvideo_models_vision_encoder___init___py_load_vision_encoder fn;
    hyvideo_models_vision_encoder___init___py --> hyvideo_models_vision_encoder___init___py_load_vision_encoder
    hyvideo_models_vision_encoder___init___py_load_image_processor["load_image_processor"]
    class hyvideo_models_vision_encoder___init___py_load_image_processor fn;
    hyvideo_models_vision_encoder___init___py --> hyvideo_models_vision_encoder___init___py_load_image_processor
    hyvideo_models_vision_encoder___init___py_VisionEncoderModelOutput["VisionEncoderModelOutput"]
    class hyvideo_models_vision_encoder___init___py_VisionEncoderModelOutput cls;
    hyvideo_models_vision_encoder___init___py --> hyvideo_models_vision_encoder___init___py_VisionEncoderModelOutput
    hyvideo_models_vision_encoder___init___py_VisionEncoder["VisionEncoder"]
    class hyvideo_models_vision_encoder___init___py_VisionEncoder cls;
    hyvideo_models_vision_encoder___init___py --> hyvideo_models_vision_encoder___init___py_VisionEncoder
    hyvideo_models_transformers_modules_ssta_attention_py["ssta_attention.py (py)"]
    class hyvideo_models_transformers_modules_ssta_attention_py mod;
    hyvideo_models_transformers_modules_ssta_attention_py_tile["tile"]
    class hyvideo_models_transformers_modules_ssta_attention_py_tile fn;
    hyvideo_models_transformers_modules_ssta_attention_py --> hyvideo_models_transformers_modules_ssta_attention_py_tile
    hyvideo_models_transformers_modules_ssta_attention_py_untile["untile"]
    class hyvideo_models_transformers_modules_ssta_attention_py_untile fn;
    hyvideo_models_transformers_modules_ssta_attention_py --> hyvideo_models_transformers_modules_ssta_attention_py_untile
    hyvideo_models_transformers_modules_ssta_attention_py_get_tile_t_h_w["get_tile_t_h_w"]
    class hyvideo_models_transformers_modules_ssta_attention_py_get_tile_t_h_w fn;
    hyvideo_models_transformers_modules_ssta_attention_py --> hyvideo_models_transformers_modules_ssta_attention_py_get_tile_t_h_w
    hyvideo_models_transformers_modules_ssta_attention_py_importance_sampling["importance_sampling"]
    class hyvideo_models_transformers_modules_ssta_attention_py_importance_sampling fn;
    hyvideo_models_transformers_modules_ssta_attention_py --> hyvideo_models_transformers_modules_ssta_attention_py_importance_sampling
    hyvideo_models_transformers_modules_ssta_attention_py_similarity_sampling["similarity_sampling"]
    class hyvideo_models_transformers_modules_ssta_attention_py_similarity_sampling fn;
    hyvideo_models_transformers_modules_ssta_attention_py --> hyvideo_models_transformers_modules_ssta_attention_py_similarity_sampling
    hyvideo_utils_flash_attn_no_pad_py["flash_attn_no_pad.py (py)"]
    class hyvideo_utils_flash_attn_no_pad_py mod;
    hyvideo_utils_flash_attn_no_pad_py_flash_attn_no_pad["flash_attn_no_pad"]
    class hyvideo_utils_flash_attn_no_pad_py_flash_attn_no_pad fn;
    hyvideo_utils_flash_attn_no_pad_py --> hyvideo_utils_flash_attn_no_pad_py_flash_attn_no_pad
    hyvideo_utils_flash_attn_no_pad_py_flash_attn_no_pad_v3["flash_attn_no_pad_v3"]
    class hyvideo_utils_flash_attn_no_pad_py_flash_attn_no_pad_v3 fn;
    hyvideo_utils_flash_attn_no_pad_py --> hyvideo_utils_flash_attn_no_pad_py_flash_attn_no_pad_v3
    hyvideo_models_transformers_modules_mlp_layers_py["mlp_layers.py (py)"]
    class hyvideo_models_transformers_modules_mlp_layers_py mod;
    hyvideo_models_transformers_modules_mlp_layers_py_MLP["MLP"]
    class hyvideo_models_transformers_modules_mlp_layers_py_MLP cls;
    hyvideo_models_transformers_modules_mlp_layers_py --> hyvideo_models_transformers_modules_mlp_layers_py_MLP
    hyvideo_models_transformers_modules_mlp_layers_py_LinearWarpforSingle["LinearWarpforSingle"]
    class hyvideo_models_transformers_modules_mlp_layers_py_LinearWarpforSingle cls;
    hyvideo_models_transformers_modules_mlp_layers_py --> hyvideo_models_transformers_modules_mlp_layers_py_LinearWarpforSingle
    hyvideo_models_transformers_modules_mlp_layers_py_MLPEmbedder["MLPEmbedder"]
    class hyvideo_models_transformers_modules_mlp_layers_py_MLPEmbedder cls;
    hyvideo_models_transformers_modules_mlp_layers_py --> hyvideo_models_transformers_modules_mlp_layers_py_MLPEmbedder
    hyvideo_models_transformers_modules_mlp_layers_py_FinalLayer["FinalLayer"]
    class hyvideo_models_transformers_modules_mlp_layers_py_FinalLayer cls;
    hyvideo_models_transformers_modules_mlp_layers_py --> hyvideo_models_transformers_modules_mlp_layers_py_FinalLayer
    hyvideo_models_transformers_modules_mlp_layers_py___init__["__init__"]
    class hyvideo_models_transformers_modules_mlp_layers_py___init__ fn;
    hyvideo_models_transformers_modules_mlp_layers_py --> hyvideo_models_transformers_modules_mlp_layers_py___init__
    hyvideo_utils_communications_py["communications.py (py)"]
    class hyvideo_utils_communications_py mod;
    hyvideo_utils_communications_py_broadcast["broadcast"]
    class hyvideo_utils_communications_py_broadcast fn;
    hyvideo_utils_communications_py --> hyvideo_utils_communications_py_broadcast
    hyvideo_utils_communications_py__all_to_all_4D["_all_to_all_4D"]
    class hyvideo_utils_communications_py__all_to_all_4D fn;
    hyvideo_utils_communications_py --> hyvideo_utils_communications_py__all_to_all_4D
    hyvideo_utils_communications_py_SeqAllToAll4D["SeqAllToAll4D"]
    class hyvideo_utils_communications_py_SeqAllToAll4D cls;
    hyvideo_utils_communications_py --> hyvideo_utils_communications_py_SeqAllToAll4D
    hyvideo_utils_communications_py_all_to_all_4D["all_to_all_4D"]
    class hyvideo_utils_communications_py_all_to_all_4D fn;
    hyvideo_utils_communications_py --> hyvideo_utils_communications_py_all_to_all_4D
    hyvideo_utils_communications_py__all_to_all["_all_to_all"]
    class hyvideo_utils_communications_py__all_to_all fn;
    hyvideo_utils_communications_py --> hyvideo_utils_communications_py__all_to_all
    hyvideo_models_transformers_modules_embed_layers_py["embed_layers.py (py)"]
    class hyvideo_models_transformers_modules_embed_layers_py mod;
    hyvideo_models_transformers_modules_embed_layers_py_PatchEmbed["PatchEmbed"]
    class hyvideo_models_transformers_modules_embed_layers_py_PatchEmbed cls;
    hyvideo_models_transformers_modules_embed_layers_py --> hyvideo_models_transformers_modules_embed_layers_py_PatchEmbed
    hyvideo_models_transformers_modules_embed_layers_py_TextProjection["TextProjection"]
    class hyvideo_models_transformers_modules_embed_layers_py_TextProjection cls;
    hyvideo_models_transformers_modules_embed_layers_py --> hyvideo_models_transformers_modules_embed_layers_py_TextProjection
    hyvideo_models_transformers_modules_embed_layers_py_VisionProjection["VisionProjection"]
    class hyvideo_models_transformers_modules_embed_layers_py_VisionProjection cls;
    hyvideo_models_transformers_modules_embed_layers_py --> hyvideo_models_transformers_modules_embed_layers_py_VisionProjection
    hyvideo_models_transformers_modules_embed_layers_py_ClipVisionProjection["ClipVisionProjection"]
    class hyvideo_models_transformers_modules_embed_layers_py_ClipVisionProjection cls;
    hyvideo_models_transformers_modules_embed_layers_py --> hyvideo_models_transformers_modules_embed_layers_py_ClipVisionProjection
    hyvideo_models_transformers_modules_embed_layers_py_timestep_embedding["timestep_embedding"]
    class hyvideo_models_transformers_modules_embed_layers_py_timestep_embedding fn;
    hyvideo_models_transformers_modules_embed_layers_py --> hyvideo_models_transformers_modules_embed_layers_py_timestep_embedding
    hyvideo_commons_parallel_states_py["parallel_states.py (py)"]
    class hyvideo_commons_parallel_states_py mod;
    hyvideo_commons_parallel_states_py_ParallelDims["ParallelDims"]
    class hyvideo_commons_parallel_states_py_ParallelDims cls;
    hyvideo_commons_parallel_states_py --> hyvideo_commons_parallel_states_py_ParallelDims
    hyvideo_commons_parallel_states_py_initialize_parallel_state["initialize_parallel_state"]
    class hyvideo_commons_parallel_states_py_initialize_parallel_state fn;
    hyvideo_commons_parallel_states_py --> hyvideo_commons_parallel_states_py_initialize_parallel_state
    hyvideo_commons_parallel_states_py_get_parallel_state["get_parallel_state"]
    class hyvideo_commons_parallel_states_py_get_parallel_state fn;
    hyvideo_commons_parallel_states_py --> hyvideo_commons_parallel_states_py_get_parallel_state
    hyvideo_commons_parallel_states_py___post_init__["__post_init__"]
    class hyvideo_commons_parallel_states_py___post_init__ fn;
    hyvideo_commons_parallel_states_py --> hyvideo_commons_parallel_states_py___post_init__
    hyvideo_commons_parallel_states_py_build_mesh["build_mesh"]
    class hyvideo_commons_parallel_states_py_build_mesh fn;
    hyvideo_commons_parallel_states_py --> hyvideo_commons_parallel_states_py_build_mesh
    hyvideo_models_text_encoders_byT5___init___py["__init__.py (py)"]
    class hyvideo_models_text_encoders_byT5___init___py mod;
    hyvideo_models_text_encoders_byT5___init___py_load_glyph_byT5_v2["load_glyph_byT5_v2"]
    class hyvideo_models_text_encoders_byT5___init___py_load_glyph_byT5_v2 fn;
    hyvideo_models_text_encoders_byT5___init___py --> hyvideo_models_text_encoders_byT5___init___py_load_glyph_byT5_v2
    hyvideo_models_text_encoders_byT5___init___py_create_byt5["create_byt5"]
    class hyvideo_models_text_encoders_byT5___init___py_create_byt5 fn;
    hyvideo_models_text_encoders_byT5___init___py --> hyvideo_models_text_encoders_byT5___init___py_create_byt5
    hyvideo_models_text_encoders_byT5___init___py_add_special_token["add_special_token"]
    class hyvideo_models_text_encoders_byT5___init___py_add_special_token fn;
    hyvideo_models_text_encoders_byT5___init___py --> hyvideo_models_text_encoders_byT5___init___py_add_special_token
    hyvideo_models_text_encoders_byT5___init___py_load_byt5_and_byt5_tokenizer["load_byt5_and_byt5_tokenizer"]
    class hyvideo_models_text_encoders_byT5___init___py_load_byt5_and_byt5_tokenizer fn;
    hyvideo_models_text_encoders_byT5___init___py --> hyvideo_models_text_encoders_byT5___init___py_load_byt5_and_byt5_tokenizer
    hyvideo_models_text_encoders_byT5___init___py_ByT5Mapper["ByT5Mapper"]
    class hyvideo_models_text_encoders_byT5___init___py_ByT5Mapper cls;
    hyvideo_models_text_encoders_byT5___init___py --> hyvideo_models_text_encoders_byT5___init___py_ByT5Mapper
    hyvideo_optim_muon_py["muon.py (py)"]
    class hyvideo_optim_muon_py mod;
    hyvideo_optim_muon_py_zeropower_via_newtonschulz5["zeropower_via_newtonschulz5"]
    class hyvideo_optim_muon_py_zeropower_via_newtonschulz5 fn;
    hyvideo_optim_muon_py --> hyvideo_optim_muon_py_zeropower_via_newtonschulz5
    hyvideo_optim_muon_py_Muon["Muon"]
    class hyvideo_optim_muon_py_Muon cls;
    hyvideo_optim_muon_py --> hyvideo_optim_muon_py_Muon
    hyvideo_optim_muon_py_get_muon_optimizer["get_muon_optimizer"]
    class hyvideo_optim_muon_py_get_muon_optimizer fn;
    hyvideo_optim_muon_py --> hyvideo_optim_muon_py_get_muon_optimizer
    hyvideo_optim_muon_py___init__["__init__"]
    class hyvideo_optim_muon_py___init__ fn;
    hyvideo_optim_muon_py --> hyvideo_optim_muon_py___init__
    hyvideo_optim_muon_py_adjust_lr_for_muon["adjust_lr_for_muon"]
    class hyvideo_optim_muon_py_adjust_lr_for_muon fn;
    hyvideo_optim_muon_py --> hyvideo_optim_muon_py_adjust_lr_for_muon
    hyvideo_models_text_encoders_byT5_format_prompt_py["format_prompt.py (py)"]
    class hyvideo_models_text_encoders_byT5_format_prompt_py mod;
    hyvideo_models_text_encoders_byT5_format_prompt_py_closest_color["closest_color"]
    class hyvideo_models_text_encoders_byT5_format_prompt_py_closest_color fn;
    hyvideo_models_text_encoders_byT5_format_prompt_py --> hyvideo_models_text_encoders_byT5_format_prompt_py_closest_color
    hyvideo_models_text_encoders_byT5_format_prompt_py_convert_rgb_to_names["convert_rgb_to_names"]
    class hyvideo_models_text_encoders_byT5_format_prompt_py_convert_rgb_to_names fn;
    hyvideo_models_text_encoders_byT5_format_prompt_py --> hyvideo_models_text_encoders_byT5_format_prompt_py_convert_rgb_to_names
    hyvideo_models_text_encoders_byT5_format_prompt_py_MultilingualPromptFormat["MultilingualPromptFormat"]
    class hyvideo_models_text_encoders_byT5_format_prompt_py_MultilingualPromptFormat cls;
    hyvideo_models_text_encoders_byT5_format_prompt_py --> hyvideo_models_text_encoders_byT5_format_prompt_py_MultilingualPromptFormat
    hyvideo_models_text_encoders_byT5_format_prompt_py___init__["__init__"]
    class hyvideo_models_text_encoders_byT5_format_prompt_py___init__ fn;
    hyvideo_models_text_encoders_byT5_format_prompt_py --> hyvideo_models_text_encoders_byT5_format_prompt_py___init__
    hyvideo_models_text_encoders_byT5_format_prompt_py_format_prompt["format_prompt"]
    class hyvideo_models_text_encoders_byT5_format_prompt_py_format_prompt fn;
    hyvideo_models_text_encoders_byT5_format_prompt_py --> hyvideo_models_text_encoders_byT5_format_prompt_py_format_prompt
    hyvideo_utils_rewrite_rewrite_utils_py["rewrite_utils.py (py)"]
    class hyvideo_utils_rewrite_rewrite_utils_py mod;
    hyvideo_utils_rewrite_rewrite_utils_py_t2v_rewrite["t2v_rewrite"]
    class hyvideo_utils_rewrite_rewrite_utils_py_t2v_rewrite fn;
    hyvideo_utils_rewrite_rewrite_utils_py --> hyvideo_utils_rewrite_rewrite_utils_py_t2v_rewrite
    hyvideo_utils_rewrite_rewrite_utils_py_i2v_rewrite["i2v_rewrite"]
    class hyvideo_utils_rewrite_rewrite_utils_py_i2v_rewrite fn;
    hyvideo_utils_rewrite_rewrite_utils_py --> hyvideo_utils_rewrite_rewrite_utils_py_i2v_rewrite
    hyvideo_utils_rewrite_rewrite_utils_py_run_prompt_rewrite["run_prompt_rewrite"]
    class hyvideo_utils_rewrite_rewrite_utils_py_run_prompt_rewrite fn;
    hyvideo_utils_rewrite_rewrite_utils_py --> hyvideo_utils_rewrite_rewrite_utils_py_run_prompt_rewrite
    hyvideo_utils_multitask_utils_py["multitask_utils.py (py)"]
    class hyvideo_utils_multitask_utils_py mod;
    hyvideo_utils_multitask_utils_py_numpy_to_pil["numpy_to_pil"]
    class hyvideo_utils_multitask_utils_py_numpy_to_pil fn;
    hyvideo_utils_multitask_utils_py --> hyvideo_utils_multitask_utils_py_numpy_to_pil
    hyvideo_utils_multitask_utils_py_merge_tensor_by_mask["merge_tensor_by_mask"]
    class hyvideo_utils_multitask_utils_py_merge_tensor_by_mask fn;
    hyvideo_utils_multitask_utils_py --> hyvideo_utils_multitask_utils_py_merge_tensor_by_mask
    hyvideo_models_transformers_modules_modulate_layers_py["modulate_layers.py (py)"]
    class hyvideo_models_transformers_modules_modulate_layers_py mod;
    hyvideo_models_transformers_modules_modulate_layers_py_ModulateDiT["ModulateDiT"]
    class hyvideo_models_transformers_modules_modulate_layers_py_ModulateDiT cls;
    hyvideo_models_transformers_modules_modulate_layers_py --> hyvideo_models_transformers_modules_modulate_layers_py_ModulateDiT
    hyvideo_models_transformers_modules_modulate_layers_py_modulate["modulate"]
    class hyvideo_models_transformers_modules_modulate_layers_py_modulate fn;
    hyvideo_models_transformers_modules_modulate_layers_py --> hyvideo_models_transformers_modules_modulate_layers_py_modulate
    hyvideo_models_transformers_modules_modulate_layers_py_apply_gate["apply_gate"]
    class hyvideo_models_transformers_modules_modulate_layers_py_apply_gate fn;
    hyvideo_models_transformers_modules_modulate_layers_py --> hyvideo_models_transformers_modules_modulate_layers_py_apply_gate
    hyvideo_models_transformers_modules_modulate_layers_py_ckpt_wrapper["ckpt_wrapper"]
    class hyvideo_models_transformers_modules_modulate_layers_py_ckpt_wrapper fn;
    hyvideo_models_transformers_modules_modulate_layers_py --> hyvideo_models_transformers_modules_modulate_layers_py_ckpt_wrapper
    hyvideo_models_transformers_modules_modulate_layers_py___init__["__init__"]
    class hyvideo_models_transformers_modules_modulate_layers_py___init__ fn;
    hyvideo_models_transformers_modules_modulate_layers_py --> hyvideo_models_transformers_modules_modulate_layers_py___init__
    hyvideo_models_transformers_modules_posemb_layers_py["posemb_layers.py (py)"]
    class hyvideo_models_transformers_modules_posemb_layers_py mod;
    hyvideo_models_transformers_modules_posemb_layers_py__to_tuple["_to_tuple"]
    class hyvideo_models_transformers_modules_posemb_layers_py__to_tuple fn;
    hyvideo_models_transformers_modules_posemb_layers_py --> hyvideo_models_transformers_modules_posemb_layers_py__to_tuple
    hyvideo_models_transformers_modules_posemb_layers_py_get_meshgrid_nd["get_meshgrid_nd"]
    class hyvideo_models_transformers_modules_posemb_layers_py_get_meshgrid_nd fn;
    hyvideo_models_transformers_modules_posemb_layers_py --> hyvideo_models_transformers_modules_posemb_layers_py_get_meshgrid_nd
    hyvideo_models_transformers_modules_posemb_layers_py_reshape_for_broadcast["reshape_for_broadcast"]
    class hyvideo_models_transformers_modules_posemb_layers_py_reshape_for_broadcast fn;
    hyvideo_models_transformers_modules_posemb_layers_py --> hyvideo_models_transformers_modules_posemb_layers_py_reshape_for_broadcast
    hyvideo_models_transformers_modules_posemb_layers_py_rotate_half["rotate_half"]
    class hyvideo_models_transformers_modules_posemb_layers_py_rotate_half fn;
    hyvideo_models_transformers_modules_posemb_layers_py --> hyvideo_models_transformers_modules_posemb_layers_py_rotate_half
    hyvideo_models_transformers_modules_posemb_layers_py_apply_rotary_emb["apply_rotary_emb"]
    class hyvideo_models_transformers_modules_posemb_layers_py_apply_rotary_emb fn;
    hyvideo_models_transformers_modules_posemb_layers_py --> hyvideo_models_transformers_modules_posemb_layers_py_apply_rotary_emb
    hyvideo___init___py["__init__.py (py)"]
    class hyvideo___init___py mod;
    hyvideo___init___py_find_free_port["find_free_port"]
    class hyvideo___init___py_find_free_port fn;
    hyvideo___init___py --> hyvideo___init___py_find_free_port
    hyvideo___init___py___initialize_default_distributed_environment["__initialize_default_distributed_environment"]
    class hyvideo___init___py___initialize_default_distributed_environment fn;
    hyvideo___init___py --> hyvideo___init___py___initialize_default_distributed_environment
    hyvideo_pipelines_pipeline_utils_py["pipeline_utils.py (py)"]
    class hyvideo_pipelines_pipeline_utils_py mod;
    hyvideo_pipelines_pipeline_utils_py_retrieve_timesteps["retrieve_timesteps"]
    class hyvideo_pipelines_pipeline_utils_py_retrieve_timesteps fn;
    hyvideo_pipelines_pipeline_utils_py --> hyvideo_pipelines_pipeline_utils_py_retrieve_timesteps
    hyvideo_pipelines_pipeline_utils_py_rescale_noise_cfg["rescale_noise_cfg"]
    class hyvideo_pipelines_pipeline_utils_py_rescale_noise_cfg fn;
    hyvideo_pipelines_pipeline_utils_py --> hyvideo_pipelines_pipeline_utils_py_rescale_noise_cfg
    hyvideo_models_transformers_modules_norm_layers_py["norm_layers.py (py)"]
    class hyvideo_models_transformers_modules_norm_layers_py mod;
    hyvideo_models_transformers_modules_norm_layers_py_RMSNorm["RMSNorm"]
    class hyvideo_models_transformers_modules_norm_layers_py_RMSNorm cls;
    hyvideo_models_transformers_modules_norm_layers_py --> hyvideo_models_transformers_modules_norm_layers_py_RMSNorm
    hyvideo_models_transformers_modules_norm_layers_py_get_norm_layer["get_norm_layer"]
    class hyvideo_models_transformers_modules_norm_layers_py_get_norm_layer fn;
    hyvideo_models_transformers_modules_norm_layers_py --> hyvideo_models_transformers_modules_norm_layers_py_get_norm_layer
    hyvideo_models_transformers_modules_norm_layers_py___init__["__init__"]
    class hyvideo_models_transformers_modules_norm_layers_py___init__ fn;
    hyvideo_models_transformers_modules_norm_layers_py --> hyvideo_models_transformers_modules_norm_layers_py___init__
    hyvideo_models_transformers_modules_norm_layers_py__norm["_norm"]
    class hyvideo_models_transformers_modules_norm_layers_py__norm fn;
    hyvideo_models_transformers_modules_norm_layers_py --> hyvideo_models_transformers_modules_norm_layers_py__norm
    hyvideo_models_transformers_modules_norm_layers_py_reset_parameters["reset_parameters"]
    class hyvideo_models_transformers_modules_norm_layers_py_reset_parameters fn;
    hyvideo_models_transformers_modules_norm_layers_py --> hyvideo_models_transformers_modules_norm_layers_py_reset_parameters
    hyvideo_commons_infer_state_py["infer_state.py (py)"]
    class hyvideo_commons_infer_state_py mod;
    hyvideo_commons_infer_state_py_InferState["InferState"]
    class hyvideo_commons_infer_state_py_InferState cls;
    hyvideo_commons_infer_state_py --> hyvideo_commons_infer_state_py_InferState
    hyvideo_commons_infer_state_py_parse_range["parse_range"]
    class hyvideo_commons_infer_state_py_parse_range fn;
    hyvideo_commons_infer_state_py --> hyvideo_commons_infer_state_py_parse_range
    hyvideo_commons_infer_state_py_initialize_infer_state["initialize_infer_state"]
    class hyvideo_commons_infer_state_py_initialize_infer_state fn;
    hyvideo_commons_infer_state_py --> hyvideo_commons_infer_state_py_initialize_infer_state
    hyvideo_commons_infer_state_py_get_infer_state["get_infer_state"]
    class hyvideo_commons_infer_state_py_get_infer_state fn;
    hyvideo_commons_infer_state_py --> hyvideo_commons_infer_state_py_get_infer_state
    hyvideo_utils_data_utils_py["data_utils.py (py)"]
    class hyvideo_utils_data_utils_py mod;
    hyvideo_utils_data_utils_py_resize_and_center_crop["resize_and_center_crop"]
    class hyvideo_utils_data_utils_py_resize_and_center_crop fn;
    hyvideo_utils_data_utils_py --> hyvideo_utils_data_utils_py_resize_and_center_crop
    hyvideo_utils_data_utils_py_get_closest_ratio["get_closest_ratio"]
    class hyvideo_utils_data_utils_py_get_closest_ratio fn;
    hyvideo_utils_data_utils_py --> hyvideo_utils_data_utils_py_get_closest_ratio
    hyvideo_utils_data_utils_py_generate_crop_size_list["generate_crop_size_list"]
    class hyvideo_utils_data_utils_py_generate_crop_size_list fn;
    hyvideo_utils_data_utils_py --> hyvideo_utils_data_utils_py_generate_crop_size_list
    hyvideo_utils_infer_utils_py["infer_utils.py (py)"]
    class hyvideo_utils_infer_utils_py mod;
    hyvideo_utils_infer_utils_py_torch_compile_wrapper["torch_compile_wrapper"]
    class hyvideo_utils_infer_utils_py_torch_compile_wrapper fn;
    hyvideo_utils_infer_utils_py --> hyvideo_utils_infer_utils_py_torch_compile_wrapper
    hyvideo_utils_infer_utils_py_decorator["decorator"]
    class hyvideo_utils_infer_utils_py_decorator fn;
    hyvideo_utils_infer_utils_py --> hyvideo_utils_infer_utils_py_decorator
    hyvideo_utils_infer_utils_py_wrapper["wrapper"]
    class hyvideo_utils_infer_utils_py_wrapper fn;
    hyvideo_utils_infer_utils_py --> hyvideo_utils_infer_utils_py_wrapper
    hyvideo_models_transformers_modules_activation_layers_py["activation_layers.py (py)"]
    class hyvideo_models_transformers_modules_activation_layers_py mod;
    hyvideo_models_transformers_modules_activation_layers_py_get_activation_layer["get_activation_layer"]
    class hyvideo_models_transformers_modules_activation_layers_py_get_activation_layer fn;
    hyvideo_models_transformers_modules_activation_layers_py --> hyvideo_models_transformers_modules_activation_layers_py_get_activation_layer
    hyvideo_commons_cache_helper_py["cache_helper.py (py)"]
    class hyvideo_commons_cache_helper_py mod;
    hyvideo_commons_cache_helper_py_CacheHelper["CacheHelper"]
    class hyvideo_commons_cache_helper_py_CacheHelper cls;
    hyvideo_commons_cache_helper_py --> hyvideo_commons_cache_helper_py_CacheHelper
    hyvideo_commons_cache_helper_py___init__["__init__"]
    class hyvideo_commons_cache_helper_py___init__ fn;
    hyvideo_commons_cache_helper_py --> hyvideo_commons_cache_helper_py___init__
    hyvideo_commons_cache_helper_py_enable["enable"]
    class hyvideo_commons_cache_helper_py_enable fn;
    hyvideo_commons_cache_helper_py --> hyvideo_commons_cache_helper_py_enable
    hyvideo_commons_cache_helper_py_disable["disable"]
    class hyvideo_commons_cache_helper_py_disable fn;
    hyvideo_commons_cache_helper_py --> hyvideo_commons_cache_helper_py_disable
    hyvideo_commons_cache_helper_py_is_skip_step["is_skip_step"]
    class hyvideo_commons_cache_helper_py_is_skip_step fn;
    hyvideo_commons_cache_helper_py --> hyvideo_commons_cache_helper_py_is_skip_step
    hyvideo_models___init___py["__init__.py (py)"]
    class hyvideo_models___init___py mod;
    hyvideo_models_autoencoders___init___py["__init__.py (py)"]
    class hyvideo_models_autoencoders___init___py mod;
    hyvideo_utils_rewrite_i2v_prompt_py["i2v_prompt.py (py)"]
    class hyvideo_utils_rewrite_i2v_prompt_py mod;
    hyvideo_utils_rewrite_t2v_prompt_py["t2v_prompt.py (py)"]
    class hyvideo_utils_rewrite_t2v_prompt_py mod;
    ext_os["os"]
    class ext_os ext;
    generate_py -.->|imports| ext_os
    ext_copy["copy"]
    class ext_copy ext;
    generate_py -.->|imports| ext_copy
    ext_datetime["datetime"]
    class ext_datetime ext;
    generate_py -.->|imports| ext_datetime
    ext_json["json"]
    class ext_json ext;
    generate_py -.->|imports| ext_json
    ext_loguru["loguru"]
    class ext_loguru ext;
    generate_py -.->|imports| ext_loguru
    ext_torch["torch"]
    class ext_torch ext;
    generate_py -.->|imports| ext_torch
    ext_argparse["argparse"]
    class ext_argparse ext;
    generate_py -.->|imports| ext_argparse
    ext_einops["einops"]
    class ext_einops ext;
    generate_py -.->|imports| ext_einops
    ext_imageio["imageio"]
    class ext_imageio ext;
    generate_py -.->|imports| ext_imageio
    generate_py -.->|imports| ext_torch
    ext_torch_distributed_checkpoint["torch.distributed.checkpoint"]
    class ext_torch_distributed_checkpoint ext;
    generate_py -.->|imports| ext_torch_distributed_checkpoint
    ext_torch_distributed_checkpoint_state_dict["torch.distributed.checkpoint.state_dict"]
    class ext_torch_distributed_checkpoint_state_dict ext;
    generate_py -.->|imports| ext_torch_distributed_checkpoint_state_dict
    ext_hyvideo_pipelines_hunyuan_video_pipeline["hyvideo.pipelines.hunyuan_video_pipeline"]
    class ext_hyvideo_pipelines_hunyuan_video_pipeline ext;
    generate_py -.->|imports| ext_hyvideo_pipelines_hunyuan_video_pipeline
    ext_hyvideo_commons_parallel_states["hyvideo.commons.parallel_states"]
    class ext_hyvideo_commons_parallel_states ext;
    generate_py -.->|imports| ext_hyvideo_commons_parallel_states
    ext_hyvideo_commons_infer_state["hyvideo.commons.infer_state"]
    class ext_hyvideo_commons_infer_state ext;
    generate_py -.->|imports| ext_hyvideo_commons_infer_state
    ext_sgl_kernel["sgl_kernel"]
    class ext_sgl_kernel ext;
    generate_py -.->|imports| ext_sgl_kernel
    hyvideo___init___py -.->|imports| ext_os
    ext_socket["socket"]
    class ext_socket ext;
    hyvideo___init___py -.->|imports| ext_socket
    ext_commons["commons"]
    class ext_commons ext;
    hyvideo___init___py -.->|imports| ext_commons
    hyvideo_commons___init___py -.->|imports| ext_os
    hyvideo_commons___init___py -.->|imports| ext_torch
    ext_itertools["itertools"]
    class ext_itertools ext;
    hyvideo_commons___init___py -.->|imports| ext_itertools
    ext_contextlib["contextlib"]
    class ext_contextlib ext;
    hyvideo_commons___init___py -.->|imports| ext_contextlib
    hyvideo_commons___init___py -.->|imports| ext_torch
    ext_collections_abc["collections.abc"]
    class ext_collections_abc ext;
    hyvideo_commons___init___py -.->|imports| ext_collections_abc
    ext_warnings["warnings"]
    class ext_warnings ext;
    hyvideo_commons___init___py -.->|imports| ext_warnings
    ext_diffusers_hooks_group_offloading["diffusers.hooks.group_offloading"]
    class ext_diffusers_hooks_group_offloading ext;
    hyvideo_commons___init___py -.->|imports| ext_diffusers_hooks_group_offloading
    ext_flash_attn["flash_attn"]
    class ext_flash_attn ext;
    hyvideo_commons___init___py -.->|imports| ext_flash_attn
    ext_flash_attn_interface["flash_attn_interface"]
    class ext_flash_attn_interface ext;
    hyvideo_commons___init___py -.->|imports| ext_flash_attn_interface
    ext_flex_block_attn["flex_block_attn"]
    class ext_flex_block_attn ext;
    hyvideo_commons___init___py -.->|imports| ext_flex_block_attn
    ext_angelslim["angelslim"]
    class ext_angelslim ext;
    hyvideo_commons___init___py -.->|imports| ext_angelslim
    ext_hyvideo_commons["hyvideo.commons"]
    class ext_hyvideo_commons ext;
    hyvideo_commons___init___py -.->|imports| ext_hyvideo_commons
    ext_sageattention["sageattention"]
    class ext_sageattention ext;
    hyvideo_commons___init___py -.->|imports| ext_sageattention
    ext_typing["typing"]
    class ext_typing ext;
    hyvideo_commons_infer_state_py -.->|imports| ext_typing
    ext_dataclasses["dataclasses"]
    class ext_dataclasses ext;
    hyvideo_commons_infer_state_py -.->|imports| ext_dataclasses
    hyvideo_commons_parallel_states_py -.->|imports| ext_os
    hyvideo_commons_parallel_states_py -.->|imports| ext_dataclasses
    ext_torch_distributed["torch.distributed"]
    class ext_torch_distributed ext;
    hyvideo_commons_parallel_states_py -.->|imports| ext_torch_distributed
    ext_torch_distributed_device_mesh["torch.distributed.device_mesh"]
    class ext_torch_distributed_device_mesh ext;
    hyvideo_commons_parallel_states_py -.->|imports| ext_torch_distributed_device_mesh
    ext_math["math"]
    class ext_math ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_math
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_dataclasses
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_typing
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_contextlib
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_loguru
    ext_numpy["numpy"]
    class ext_numpy ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_numpy
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_torch
    ext_torch_nn_functional["torch.nn.functional"]
    class ext_torch_nn_functional ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_torch_nn_functional
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_einops
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_torch
    ext_torch_nn["torch.nn"]
    class ext_torch_nn ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_torch_nn
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_torch
    ext_diffusers_configuration_utils["diffusers.configuration_utils"]
    class ext_diffusers_configuration_utils ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_diffusers_configuration_utils
    ext_diffusers_models_autoencoders_vae["diffusers.models.autoencoders.vae"]
    class ext_diffusers_models_autoencoders_vae ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_diffusers_models_autoencoders_vae
    ext_diffusers_models_modeling_outputs["diffusers.models.modeling_outputs"]
    class ext_diffusers_models_modeling_outputs ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_diffusers_models_modeling_outputs
    ext_diffusers_models_modeling_utils["diffusers.models.modeling_utils"]
    class ext_diffusers_models_modeling_utils ext;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_diffusers_models_modeling_utils
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -.->|imports| ext_hyvideo_commons_parallel_states
    hyvideo_models_text_encoders___init___py -.->|imports| ext_os
    hyvideo_models_text_encoders___init___py -.->|imports| ext_copy
    hyvideo_models_text_encoders___init___py -.->|imports| ext_dataclasses
    hyvideo_models_text_encoders___init___py -.->|imports| ext_typing
    hyvideo_models_text_encoders___init___py -.->|imports| ext_torch
    hyvideo_models_text_encoders___init___py -.->|imports| ext_torch_nn
    ext_transformers["transformers"]
    class ext_transformers ext;
    hyvideo_models_text_encoders___init___py -.->|imports| ext_transformers
    ext_transformers_utils["transformers.utils"]
    class ext_transformers_utils ext;
    hyvideo_models_text_encoders___init___py -.->|imports| ext_transformers_utils
    hyvideo_models_text_encoders_byT5___init___py -.->|imports| ext_json
    hyvideo_models_text_encoders_byT5___init___py -.->|imports| ext_torch
    hyvideo_models_text_encoders_byT5___init___py -.->|imports| ext_torch_nn
    hyvideo_models_text_encoders_byT5___init___py -.->|imports| ext_transformers
    hyvideo_models_text_encoders_byT5_format_prompt_py -.->|imports| ext_json
    ext_webcolors["webcolors"]
    class ext_webcolors ext;
    hyvideo_models_text_encoders_byT5_format_prompt_py -.->|imports| ext_webcolors
    hyvideo_models_text_encoders_byT5_format_prompt_py -.->|imports| ext_webcolors
    hyvideo_models_text_encoders_byT5_format_prompt_py -.->|imports| ext_webcolors
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_os
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_typing
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_torch
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_einops
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_loguru
    ext_diffusers_models["diffusers.models"]
    class ext_diffusers_models ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_diffusers_models
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_diffusers_configuration_utils
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_hyvideo_commons
    ext_modules_activation_layers["modules.activation_layers"]
    class ext_modules_activation_layers ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_activation_layers
    ext_modules_norm_layers["modules.norm_layers"]
    class ext_modules_norm_layers ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_norm_layers
    ext_modules_embed_layers["modules.embed_layers"]
    class ext_modules_embed_layers ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_embed_layers
    ext_modules_attention["modules.attention"]
    class ext_modules_attention ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_attention
    ext_modules_posemb_layers["modules.posemb_layers"]
    class ext_modules_posemb_layers ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_posemb_layers
    ext_modules_mlp_layers["modules.mlp_layers"]
    class ext_modules_mlp_layers ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_mlp_layers
    ext_modules_modulate_layers["modules.modulate_layers"]
    class ext_modules_modulate_layers ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_modulate_layers
    ext_modules_token_refiner["modules.token_refiner"]
    class ext_modules_token_refiner ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_modules_token_refiner
    ext_hyvideo_utils_communications["hyvideo.utils.communications"]
    class ext_hyvideo_utils_communications ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_hyvideo_utils_communications
    ext_hyvideo_models_text_encoders_byT5["hyvideo.models.text_encoders.byT5"]
    class ext_hyvideo_models_text_encoders_byT5 ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_hyvideo_models_text_encoders_byT5
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_hyvideo_commons_parallel_states
    ext_diffusers_loaders_peft["diffusers.loaders.peft"]
    class ext_diffusers_loaders_peft ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_diffusers_loaders_peft
    ext_peft_utils["peft.utils"]
    class ext_peft_utils ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_peft_utils
    ext_diffusers_loaders_lora_base["diffusers.loaders.lora_base"]
    class ext_diffusers_loaders_lora_base ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_diffusers_loaders_lora_base
    ext_diffusers_utils["diffusers.utils"]
    class ext_diffusers_utils ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_diffusers_utils
    ext_safetensors["safetensors"]
    class ext_safetensors ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_safetensors
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_json
    ext_pathlib["pathlib"]
    class ext_pathlib ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_pathlib
    ext_safetensors_torch["safetensors.torch"]
    class ext_safetensors_torch ext;
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -.->|imports| ext_safetensors_torch
    hyvideo_models_transformers_modules_activation_layers_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_einops
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_typing
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_loguru
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_numpy
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_torch_nn_functional
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_hyvideo_commons_parallel_states
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_hyvideo_utils_communications
    ext_hyvideo_utils_flash_attn_no_pad["hyvideo.utils.flash_attn_no_pad"]
    class ext_hyvideo_utils_flash_attn_no_pad ext;
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_hyvideo_utils_flash_attn_no_pad
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_hyvideo_commons
    ext_hyvideo_models_transformers_modules_ssta_attention["hyvideo.models.transformers.modules.ssta_attention"]
    class ext_hyvideo_models_transformers_modules_ssta_attention ext;
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_hyvideo_models_transformers_modules_ssta_attention
    ext_torch_nn_attention_flex_attention["torch.nn.attention.flex_attention"]
    class ext_torch_nn_attention_flex_attention ext;
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_torch_nn_attention_flex_attention
    hyvideo_models_transformers_modules_attention_py -.->|imports| ext_sageattention
    hyvideo_models_transformers_modules_embed_layers_py -.->|imports| ext_math
    hyvideo_models_transformers_modules_embed_layers_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_embed_layers_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_modules_embed_layers_py -.->|imports| ext_hyvideo_commons
    ext_functools["functools"]
    class ext_functools ext;
    hyvideo_models_transformers_modules_mlp_layers_py -.->|imports| ext_functools
    hyvideo_models_transformers_modules_mlp_layers_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_mlp_layers_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_modules_mlp_layers_py -.->|imports| ext_hyvideo_commons
    ext_modulate_layers["modulate_layers"]
    class ext_modulate_layers ext;
    hyvideo_models_transformers_modules_mlp_layers_py -.->|imports| ext_modulate_layers
    hyvideo_models_transformers_modules_modulate_layers_py -.->|imports| ext_typing
    hyvideo_models_transformers_modules_modulate_layers_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_modulate_layers_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_modules_norm_layers_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_norm_layers_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_modules_posemb_layers_py -.->|imports| ext_functools
    hyvideo_models_transformers_modules_posemb_layers_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_posemb_layers_py -.->|imports| ext_typing
    hyvideo_models_transformers_modules_ssta_attention_py -.->|imports| ext_math
    hyvideo_models_transformers_modules_ssta_attention_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_ssta_attention_py -.->|imports| ext_numpy
    hyvideo_models_transformers_modules_ssta_attention_py -.->|imports| ext_einops
    hyvideo_models_transformers_modules_ssta_attention_py -.->|imports| ext_functools
    hyvideo_models_transformers_modules_ssta_attention_py -.->|imports| ext_flex_block_attn
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_typing
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_einops
    ext_activation_layers["activation_layers"]
    class ext_activation_layers ext;
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_activation_layers
    ext_embed_layers["embed_layers"]
    class ext_embed_layers ext;
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_embed_layers
    ext_mlp_layers["mlp_layers"]
    class ext_mlp_layers ext;
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_mlp_layers
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_modulate_layers
    ext_norm_layers["norm_layers"]
    class ext_norm_layers ext;
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_norm_layers
    ext_attention["attention"]
    class ext_attention ext;
    hyvideo_models_transformers_modules_token_refiner_py -.->|imports| ext_attention
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_collections_abc
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_dataclasses
    ext_enum["enum"]
    class ext_enum ext;
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_enum
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_torch_nn
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_torch_nn_functional
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_einops
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_torch
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_diffusers_models
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_diffusers_configuration_utils
    ext_hyvideo_models_autoencoders_hunyuanvideo_15_vae["hyvideo.models.autoencoders.hunyuanvideo_15_vae"]
    class ext_hyvideo_models_autoencoders_hunyuanvideo_15_vae ext;
    hyvideo_models_transformers_modules_upsample_py -.->|imports| ext_hyvideo_models_autoencoders_hunyuanvideo_15_vae
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_dataclasses
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_typing
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_torch
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_torch_nn
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_transformers
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_transformers_utils
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_numpy
    hyvideo_models_vision_encoder___init___py -.->|imports| ext_hyvideo_commons
    hyvideo_optim_muon_py -.->|imports| ext_math
    hyvideo_optim_muon_py -.->|imports| ext_torch
    ext_torch_distributed_tensor["torch.distributed.tensor"]
    class ext_torch_distributed_tensor ext;
    hyvideo_optim_muon_py -.->|imports| ext_torch_distributed_tensor
    ext_torch_distributed_tensor_placement_types["torch.distributed.tensor.placement_types"]
    class ext_torch_distributed_tensor_placement_types ext;
    hyvideo_optim_muon_py -.->|imports| ext_torch_distributed_tensor_placement_types
    ext_psutil["psutil"]
    class ext_psutil ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_psutil
    ext_inspect["inspect"]
    class ext_inspect ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_inspect
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_os
    ext_random["random"]
    class ext_random ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_random
    ext_re["re"]
    class ext_re ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_re
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_dataclasses
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_typing
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_loguru
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_numpy
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_torch
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_einops
    ext_PIL["PIL"]
    class ext_PIL ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_PIL
    ext_torchvision_transforms["torchvision.transforms"]
    class ext_torchvision_transforms ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_torchvision_transforms
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_torch
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_diffusers_configuration_utils
    ext_diffusers_image_processor["diffusers.image_processor"]
    class ext_diffusers_image_processor ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_diffusers_image_processor
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_diffusers_models
    ext_diffusers_pipelines_pipeline_utils["diffusers.pipelines.pipeline_utils"]
    class ext_diffusers_pipelines_pipeline_utils ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_diffusers_pipelines_pipeline_utils
    ext_diffusers_schedulers["diffusers.schedulers"]
    class ext_diffusers_schedulers ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_diffusers_schedulers
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_diffusers_utils
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_commons
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_commons_parallel_states
    ext_hyvideo_models_autoencoders["hyvideo.models.autoencoders"]
    class ext_hyvideo_models_autoencoders ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_models_autoencoders
    ext_hyvideo_models_text_encoders["hyvideo.models.text_encoders"]
    class ext_hyvideo_models_text_encoders ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_models_text_encoders
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_models_text_encoders_byT5
    ext_hyvideo_models_text_encoders_byT5_format_prompt["hyvideo.models.text_encoders.byT5.format_prompt"]
    class ext_hyvideo_models_text_encoders_byT5_format_prompt ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_models_text_encoders_byT5_format_prompt
    ext_hyvideo_models_transformers_hunyuanvideo_1_5_transformer["hyvideo.models.transformers.hunyuanvideo_1_5_transformer"]
    class ext_hyvideo_models_transformers_hunyuanvideo_1_5_transformer ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_models_transformers_hunyuanvideo_1_5_transformer
    ext_hyvideo_models_transformers_modules_upsample["hyvideo.models.transformers.modules.upsample"]
    class ext_hyvideo_models_transformers_modules_upsample ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_models_transformers_modules_upsample
    ext_hyvideo_models_vision_encoder["hyvideo.models.vision_encoder"]
    class ext_hyvideo_models_vision_encoder ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_models_vision_encoder
    ext_hyvideo_schedulers_scheduling_flow_match_discrete["hyvideo.schedulers.scheduling_flow_match_discrete"]
    class ext_hyvideo_schedulers_scheduling_flow_match_discrete ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_schedulers_scheduling_flow_match_discrete
    ext_hyvideo_utils_data_utils["hyvideo.utils.data_utils"]
    class ext_hyvideo_utils_data_utils ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_utils_data_utils
    ext_hyvideo_utils_multitask_utils["hyvideo.utils.multitask_utils"]
    class ext_hyvideo_utils_multitask_utils ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_utils_multitask_utils
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_commons_infer_state
    ext_pipeline_utils["pipeline_utils"]
    class ext_pipeline_utils ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_pipeline_utils
    ext_hunyuan_video_sr_pipeline["hunyuan_video_sr_pipeline"]
    class ext_hunyuan_video_sr_pipeline ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hunyuan_video_sr_pipeline
    ext_hyvideo_utils_rewrite_rewrite_utils["hyvideo.utils.rewrite.rewrite_utils"]
    class ext_hyvideo_utils_rewrite_rewrite_utils ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_hyvideo_utils_rewrite_rewrite_utils
    ext_angelslim_compressor_diffusion["angelslim.compressor.diffusion"]
    class ext_angelslim_compressor_diffusion ext;
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_angelslim_compressor_diffusion
    hyvideo_pipelines_hunyuan_video_pipeline_py -.->|imports| ext_angelslim_compressor_diffusion
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_dataclasses
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_typing
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_numpy
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_torch
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_einops
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_PIL
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_torch_nn
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_diffusers_models
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_diffusers_schedulers
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_diffusers_utils
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_hyvideo_commons_parallel_states
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_hyvideo_commons
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_hyvideo_models_text_encoders
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_hyvideo_models_transformers_hunyuanvideo_1_5_transformer
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_hyvideo_models_transformers_modules_upsample
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_hyvideo_utils_data_utils
    ext_hunyuan_video_pipeline["hunyuan_video_pipeline"]
    class ext_hunyuan_video_pipeline ext;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_hunyuan_video_pipeline
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -.->|imports| ext_pipeline_utils
    hyvideo_pipelines_pipeline_utils_py -.->|imports| ext_typing
    hyvideo_pipelines_pipeline_utils_py -.->|imports| ext_inspect
    hyvideo_pipelines_pipeline_utils_py -.->|imports| ext_torch
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_math
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_dataclasses
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_typing
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_numpy
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_torch
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_diffusers_configuration_utils
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_diffusers_utils
    ext_diffusers_schedulers_scheduling_utils["diffusers.schedulers.scheduling_utils"]
    class ext_diffusers_schedulers_scheduling_utils ext;
    hyvideo_schedulers_scheduling_flow_match_discrete_py -.->|imports| ext_diffusers_schedulers_scheduling_utils
    hyvideo_utils_communications_py -.->|imports| ext_typing
    hyvideo_utils_communications_py -.->|imports| ext_torch
    hyvideo_utils_communications_py -.->|imports| ext_torch_distributed
    hyvideo_utils_communications_py -.->|imports| ext_torch_nn
    hyvideo_utils_data_utils_py -.->|imports| ext_numpy
    hyvideo_utils_data_utils_py -.->|imports| ext_PIL
    hyvideo_utils_flash_attn_no_pad_py -.->|imports| ext_einops
    hyvideo_utils_flash_attn_no_pad_py -.->|imports| ext_flash_attn
    ext_flash_attn_bert_padding["flash_attn.bert_padding"]
    class ext_flash_attn_bert_padding ext;
    hyvideo_utils_flash_attn_no_pad_py -.->|imports| ext_flash_attn_bert_padding
    hyvideo_utils_flash_attn_no_pad_py -.->|imports| ext_flash_attn
    hyvideo_utils_flash_attn_no_pad_py -.->|imports| ext_flash_attn_bert_padding
    hyvideo_utils_flash_attn_no_pad_py -.->|imports| ext_flash_attn_interface
    hyvideo_utils_infer_utils_py -.->|imports| ext_torch
    hyvideo_utils_multitask_utils_py -.->|imports| ext_torch
    hyvideo_utils_multitask_utils_py -.->|imports| ext_typing
    hyvideo_utils_multitask_utils_py -.->|imports| ext_numpy
    hyvideo_utils_multitask_utils_py -.->|imports| ext_PIL
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_json
    ext_time["time"]
    class ext_time ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_time
    ext_ast["ast"]
    class ext_ast ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_ast
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_os
    ext_io["io"]
    class ext_io ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_io
    ext_base64["base64"]
    class ext_base64 ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_base64
    ext_openai["openai"]
    class ext_openai ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_openai
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_loguru
    ext_tencentcloud_common_common_client["tencentcloud.common.common_client"]
    class ext_tencentcloud_common_common_client ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_tencentcloud_common_common_client
    ext_tencentcloud_common["tencentcloud.common"]
    class ext_tencentcloud_common ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_tencentcloud_common
    ext_tencentcloud_common_profile_client_profile["tencentcloud.common.profile.client_profile"]
    class ext_tencentcloud_common_profile_client_profile ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_tencentcloud_common_profile_client_profile
    ext_tencentcloud_common_profile_http_profile["tencentcloud.common.profile.http_profile"]
    class ext_tencentcloud_common_profile_http_profile ext;
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_tencentcloud_common_profile_http_profile
    hyvideo_utils_rewrite_clients_py -.->|imports| ext_PIL
    hyvideo_utils_rewrite_rewrite_utils_py -.->|imports| ext_os
```

---

## Architecture Reference

### PY (39 files)

#### `generate.py`
**Path:** `generate.py`

**Functions:**
- `save_video` (line 42) `def save_video(video, path)`
- `rank0_log` (line 50) `def rank0_log(message, level)`
- `save_config` (line 54) `def save_config(args, output_path, task, transformer_version)`
- `str_to_bool` (line 81) `def str_to_bool(value)` - *Convert string to boolean, supporting true/false, 1/0, yes/no.
If value is None (when flag is provided without value), returns True.*
- `load_checkpoint_to_transformer` (line 96) `def load_checkpoint_to_transformer(pipe, checkpoint_path)`
- `load_lora_adapter` (line 112) `def load_lora_adapter(pipe, lora_path)`
- `generate_video` (line 128) `def generate_video(args)`
- `main` (line 274) `def main()`

#### `__init__.py`
**Path:** `hyvideo/__init__.py`

**Functions:**
- `find_free_port` (line 25) `def find_free_port()`
- `__initialize_default_distributed_environment` (line 32) `def __initialize_default_distributed_environment()`

#### `__init__.py`
**Path:** `hyvideo/commons/__init__.py`

**Functions:**
- `_ntuple` (line 24) `def _ntuple(n)` - *Create a function that converts input to n-tuple.*
- `is_flash2_available` (line 142) `def is_flash2_available()`
- `is_flash3_available` (line 149) `def is_flash3_available()`
- `is_flash_available` (line 156) `def is_flash_available()`
- `is_sparse_attn_supported` (line 159) `def is_sparse_attn_supported()`
- `is_sparse_attn_available` (line 162) `def is_sparse_attn_available()`
- `is_angelslim_available` (line 171) `def is_angelslim_available()`
- `maybe_fallback_attn_mode` (line 178) `def maybe_fallback_attn_mode(attn_mode)` - *Determine the final attention mode based on configuration and availability.

Args:
    attn_mode: Requested attention mode
    infer_state: Inference configuration object (optional)
    block_idx: Current block index (optional)

Returns:
    Final attention mode to use*
- `auto_offload_model` (line 229) `def auto_offload_model(models, device, enabled)`
- `get_gpu_memory` (line 243) `def get_gpu_memory(device)`
- `get_rank` (line 254) `def get_rank()`
- `parse` (line 26) `def parse(x)`

#### `cache_helper.py`
**Path:** `hyvideo/commons/cache_helper.py`

**Classes:**
- `CacheHelper` (line 2) `class CacheHelper(object)`

**Functions:**
- `__init__` (line 3) `def __init__(self, pipe_model, timesteps, no_cache_steps, no_cache_block_id, no_cache_layer_id)`
- `enable` (line 17) `def enable(self)`
- `disable` (line 22) `def disable(self)`
- `is_skip_step` (line 26) `def is_skip_step(self, block_i, layer_i, blocktype)`
- `wrap_block_forward` (line 38) `def wrap_block_forward(self, block, block_name, block_i, layer_i, blocktype)`
- `wrap_modules` (line 56) `def wrap_modules(self)`
- `unwrap_modules` (line 61) `def unwrap_modules(self)`
- `reset_states` (line 65) `def reset_states(self)`
- `clear_cache` (line 71) `def clear_cache(self)`
- `wrapped_forward` (line 43) `def wrapped_forward()`

#### `infer_state.py`
**Path:** `hyvideo/commons/infer_state.py`

**Classes:**
- `InferState` (line 21) `class InferState`

**Functions:**
- `parse_range` (line 42) `def parse_range(value)`
- `initialize_infer_state` (line 49) `def initialize_infer_state(args)`
- `get_infer_state` (line 87) `def get_infer_state()`

#### `parallel_states.py`
**Path:** `hyvideo/commons/parallel_states.py`

**Classes:**
- `ParallelDims` (line 24) `class ParallelDims`

**Functions:**
- `initialize_parallel_state` (line 81) `def initialize_parallel_state(sp, dp_replicate)`
- `get_parallel_state` (line 89) `def get_parallel_state()`
- `__post_init__` (line 29) `def __post_init__(self)`
- `build_mesh` (line 37) `def build_mesh(self, device_type)`
- `sp_enabled` (line 68) `def sp_enabled(self)`
- `sp_mesh` (line 72) `def sp_mesh(self)`
- `dp_enabled` (line 76) `def dp_enabled(self)`

#### `__init__.py`
**Path:** `hyvideo/models/__init__.py`

*No symbols extracted*

#### `__init__.py`
**Path:** `hyvideo/models/autoencoders/__init__.py`

*No symbols extracted*

#### `hunyuanvideo_15_vae.py`
**Path:** `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`

**Classes:**
- `DecoderOutput` (line 40) `class DecoderOutput(BaseOutput)`
- `PatchCausalConv3d` (line 65) `class PatchCausalConv3d` - *Causal Conv3d with efficient patch processing for large tensors.*
- `RMS_norm` (line 110) `class RMS_norm` - *Root Mean Square Layer Normalization for Channel-First or Last*
- `CausalConv3d` (line 129) `class CausalConv3d` - *Causal Conv3d with configurable padding for temporal axis.*
- `AttnBlock` (line 186) `class AttnBlock` - *Self-attention block for 3D video tensors.*
- `ResnetBlock` (line 219) `class ResnetBlock` - *ResNet-style block for 3D video tensors.*
- `Downsample` (line 251) `class Downsample`
- `Upsample` (line 293) `class Upsample` - *Hierarchical upsampling with temporal/ spatial support.*
- `Encoder` (line 331) `class Encoder` - *Hierarchical video encoder with temporal and spatial factorization.*
- `Decoder` (line 413) `class Decoder` - *Hierarchical video decoder with upsampling factories.*
- `AutoencoderKLConv3D` (line 495) `class AutoencoderKLConv3D(ModelMixin, ConfigMixin)` - *KL regularized 3D Conv VAE with advanced tiling and slicing strategies.*

**Functions:**
- `swish` (line 45) `def swish(x, inplace)` - *Applies the swish activation function (SiLU) with optional inplace support.*
- `forward_with_checkpointing` (line 50) `def forward_with_checkpointing(module)` - *Forward with optional gradient checkpointing.*
- `prepare_causal_attention_mask` (line 163) `def prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)` - *Prepare a causal attention mask for 3D videos.

Args:
    n_frame (int): Number of frames (temporal length).
    n_hw (int): Product of height and width.
    dtype: Desired mask dtype.
    device: Device for the mask.
    batch_size (int, optional): If set, expands for batch.

Returns:
    torch.Tensor: Causal attention mask.*
- `create_custom_forward` (line 52) `def create_custom_forward(module)`
- `find_split_indices` (line 67) `def find_split_indices(self, seq_len, part_num)`
- `forward` (line 86) `def forward(self, input)`
- `__init__` (line 113) `def __init__(self, dim, channel_first, images, bias)`
- `forward` (line 123) `def forward(self, x)`
- `__init__` (line 132) `def __init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)`
- `forward` (line 158) `def forward(self, x)`
- `__init__` (line 189) `def __init__(self, in_channels)`
- `attention` (line 200) `def attention(self, h_)`
- `forward` (line 215) `def forward(self, x)`
- `__init__` (line 222) `def __init__(self, in_channels, out_channels)`
- `forward` (line 236) `def forward(self, x)`
- `__init__` (line 253) `def __init__(self, in_channels, out_channels, add_temporal_downsample)`
- `forward` (line 261) `def forward(self, x)`
- `__init__` (line 296) `def __init__(self, in_channels, out_channels, add_temporal_upsample)`
- `forward` (line 303) `def forward(self, x)`
- `__init__` (line 334) `def __init__(self, in_channels, z_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, downsample_match_channel)`
- `forward` (line 386) `def forward(self, x)` - *Forward pass through the encoder.*
- `__init__` (line 416) `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, upsample_match_channel)`
- `forward` (line 468) `def forward(self, z)` - *Forward pass through the decoder.*
- `__init__` (line 500) `def __init__(self, in_channels, out_channels, latent_channels, block_out_channels, layers_per_block, ffactor_spatial, ffactor_temporal, sample_size, sample_tsize, scaling_factor, shift_factor, downsample_match_channel, upsample_match_channel)`
- `set_tile_sample_min_size` (line 554) `def set_tile_sample_min_size(self, sample_size, tile_overlap_factor)`
- `_set_gradient_checkpointing` (line 563) `def _set_gradient_checkpointing(self, module, value)` - *Enable or disable gradient checkpointing on encoder and decoder.*
- `enable_temporal_tiling` (line 569) `def enable_temporal_tiling(self, use_tiling)`
- `disable_temporal_tiling` (line 573) `def disable_temporal_tiling(self)`
- `enable_spatial_tiling` (line 576) `def enable_spatial_tiling(self, use_tiling)`
- `disable_spatial_tiling` (line 579) `def disable_spatial_tiling(self)`
- `enable_tiling` (line 582) `def enable_tiling(self, use_tiling)`
- `disable_tiling` (line 585) `def disable_tiling(self)`
- `enable_slicing` (line 588) `def enable_slicing(self)`
- `disable_slicing` (line 591) `def disable_slicing(self)`
- `blend_h` (line 594) `def blend_h(self, a, b, blend_extent)` - *Blend tensor b horizontally into a at blend_extent region.*
- `blend_v` (line 601) `def blend_v(self, a, b, blend_extent)` - *Blend tensor b vertically into a at blend_extent region.*
- `blend_t` (line 608) `def blend_t(self, a, b, blend_extent)` - *Blend tensor b temporally into a at blend_extent region.*
- `spatial_tiled_encode` (line 615) `def spatial_tiled_encode(self, x)` - *Tiled spatial encoding for large inputs via overlapping.*
- `temporal_tiled_encode` (line 643) `def temporal_tiled_encode(self, x)` - *Tiled temporal encoding for large video sequences.*
- `enable_tile_parallelism` (line 671) `def enable_tile_parallelism(self)`
- `disable_tile_parallelism` (line 674) `def disable_tile_parallelism(self)`
- `tile_parallel_spatial_tiled_decode` (line 677) `def tile_parallel_spatial_tiled_decode(self, z)`
- `spatial_tiled_decode` (line 772) `def spatial_tiled_decode(self, z)`
- `temporal_tiled_decode` (line 803) `def temporal_tiled_decode(self, z)` - *Tiled temporal decoding for long sequence latents.*
- `encode` (line 833) `def encode(self, x, return_dict)`
- `decode` (line 856) `def decode(self, z, return_dict, generator)`
- `forward` (line 876) `def forward(self, sample, sample_posterior, return_posterior, return_dict)` - *Forward autoencoder pass. Returns both reconstruction and optionally the posterior.*
- `memory_efficient_context` (line 890) `def memory_efficient_context(self)`
- `custom_forward` (line 53) `def custom_forward()`
- `_encode` (line 835) `def _encode(x)`
- `_decode` (line 858) `def _decode(z)`

#### `__init__.py`
**Path:** `hyvideo/models/text_encoders/__init__.py`

**Classes:**
- `TextEncoderModelOutput` (line 131) `class TextEncoderModelOutput(ModelOutput)` - *Base class for model's outputs that also contains a pooling of the last hidden states.

Args:
    hidden_state (`torch.FloatTensor` of shape `(batch_size, sequence_length, hidden_size)`):
        Sequence of hidden-states at the output of the last layer of the model.
    attention_mask (`torch.LongTensor` of shape `(batch_size, sequence_length)`, *optional*):
        Mask to avoid performing attention on padding token indices. Mask values selected in ``[0, 1]``:
    hidden_states_list (`tuple(torch.FloatTensor)`, *optional*, returned when `output_hidden_states=True` is passed):
        Tuple of `torch.FloatTensor` (one for the output of the embeddings, if the model has an embedding layer, +
        one for the output of each layer) of shape `(batch_size, sequence_length, hidden_size)`.
        Hidden-states of the model at the output of each layer plus the optional initial embedding outputs.
    text_outputs (`list`, *optional*, returned when `return_texts=True` is passed):
        List of decoded texts.*
- `TextEncoder` (line 154) `class TextEncoder`

**Functions:**
- `use_default` (line 32) `def use_default(value, default)` - *Utility: return value if not None, else default.*
- `load_text_encoder` (line 84) `def load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)`
- `load_tokenizer` (line 114) `def load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)`
- `__init__` (line 155) `def __init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type, tokenizer_path, output_key, use_attention_mask, prompt_template, prompt_template_video, hidden_state_skip_layer, apply_final_norm, reproduce, logger, device)`
- `dtype` (line 245) `def dtype(self)`
- `device` (line 249) `def device(self)`
- `__repr__` (line 252) `def __repr__(self)`
- `apply_text_to_template` (line 256) `def apply_text_to_template(text, template, prevent_empty_text)` - *Apply text to template.

Args:
    text (str): Input text.
    template (str or list): Template string or list of chat conversation.
    prevent_empty_text (bool): If Ture, we will prevent the user text from being empty
        by adding a space. Defaults to True.*
- `calculate_crop_start` (line 281) `def calculate_crop_start(self, tokenized_input)` - *Automatically calculate the crop_start position based on identifying user tokens.

Args:
    tokenized_input: The output from the tokenizer containing input_ids
    
Returns:
    int: The position where the actual prompt content begins (after user markers)*
- `text2tokens` (line 316) `def text2tokens(self, text, data_type, max_length)` - *Tokenize the input text.

Args:
    text (str or list): Input text.*
- `encode` (line 415) `def encode(self, batch_encoding, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts, data_type, device, is_uncond)` - *Args:
    batch_encoding (dict): Batch encoding from tokenizer.
    use_attention_mask (bool): Whether to use attention mask. If None, use self.use_attention_mask.
        Defaults to None.
    output_hidden_states (bool): Whether to output hidden states. If False, return the value of
        self.output_key. If True, return the entire output. If set self.hidden_state_skip_layer,
        output_hidden_states will be set True. Defaults to False.
    do_sample (bool): Whether to sample from the model. Used for Decoder-Only LLMs. Defaults to None.
        When self.produce is False, do_sample is set to True by default.
    hidden_state_skip_layer (int): Number of hidden states to hidden_state_skip_layer. 0 means the last layer.
        If None, self.output_key will be used. Defaults to None.
    return_texts (bool): Whether to return the decoded texts. Defaults to False.*
- `forward` (line 487) `def forward(self, text, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts)`

#### `__init__.py`
**Path:** `hyvideo/models/text_encoders/byT5/__init__.py`

**Classes:**
- `ByT5Mapper` (line 187) `class ByT5Mapper` - *ByT5Mapper: Maps ByT5 encoder outputs to a new space, with optional residual connection.

Args:
    in_dim (int): Input dimension (must equal out_dim if use_residual).
    out_dim (int): Output dimension after second linear layer.
    hidden_dim (int): Hidden dimension for intermediate layer.
    out_dim1 (int): Final output dimension.
    use_residual (bool): Whether to use residual connection (default: True).*

**Functions:**
- `load_glyph_byT5_v2` (line 23) `def load_glyph_byT5_v2(args, device)` - *Loads ByT5 tokenizer and encoder model for glyph encoding.

Args:
    args (dict): Configuration dictionary containing paths and settings.
    device (str or torch.device): Device to load the model onto.

Returns:
    dict: Dictionary with keys 'byt5_tokenizer', 'byt5_model', 'byt5_max_length'.*
- `create_byt5` (line 43) `def create_byt5(args, device)` - *Create ByT5 tokenizer and encoder, load weights if provided.

Args:
    args (dict): Configuration dictionary.
    device (str or torch.device): Device to load the model onto.

Returns:
    tuple: (byt5_tokenizer, byt5_model, byt5_max_length)*
- `add_special_token` (line 89) `def add_special_token(tokenizer, text_encoder, add_color, add_font, color_ann_path, font_ann_path, multilingual)` - *Add special tokens for color and font to tokenizer and text encoder.

Args:
    tokenizer: Huggingface tokenizer.
    text_encoder: Huggingface T5 encoder.
    add_color (bool): Whether to add color tokens.
    add_font (bool): Whether to add font tokens.
    color_ann_path (str): Path to color annotation JSON.
    font_ann_path (str): Path to font annotation JSON.
    multilingual (bool): Whether to use multilingual font tokens.*
- `load_byt5_and_byt5_tokenizer` (line 131) `def load_byt5_and_byt5_tokenizer(byt5_name, special_token, color_special_token, font_special_token, color_ann_path, font_ann_path, huggingface_cache_dir, multilingual, device)` - *Load ByT5 encoder and tokenizer from Huggingface, and add special tokens if needed.

Args:
    byt5_name (str): Model name or path.
    special_token (bool): Whether to add special tokens.
    color_special_token (bool): Whether to add color tokens.
    font_special_token (bool): Whether to add font tokens.
    color_ann_path (str): Path to color annotation JSON.
    font_ann_path (str): Path to font annotation JSON.
    huggingface_cache_dir (str): Huggingface cache directory.
    multilingual (bool): Whether to use multilingual font tokens.
    device (str or torch.device): Device to load the model onto.

Returns:
    tuple: (byt5_text_encoder, byt5_tokenizer)*
- `__init__` (line 199) `def __init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)`
- `forward` (line 210) `def forward(self, x)` - *Forward pass for ByT5Mapper.

Args:
    x (Tensor): Input tensor of shape (..., in_dim).

Returns:
    Tensor: Output tensor of shape (..., out_dim1).*

#### `format_prompt.py`
**Path:** `hyvideo/models/text_encoders/byT5/format_prompt.py`

**Classes:**
- `MultilingualPromptFormat` (line 44) `class MultilingualPromptFormat`

**Functions:**
- `closest_color` (line 20) `def closest_color(requested_color)`
- `convert_rgb_to_names` (line 34) `def convert_rgb_to_names(rgb_tuple)`
- `__init__` (line 46) `def __init__(self, font_path, color_path)`
- `format_prompt` (line 56) `def format_prompt(self, texts, styles)` - *Text "{text}" in {color}, {type}.*

#### `hunyuanvideo_1_5_transformer.py`
**Path:** `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`

**Classes:**
- `MMDoubleStreamBlock` (line 45) `class MMDoubleStreamBlock`
- `MMSingleStreamBlock` (line 208) `class MMSingleStreamBlock`
- `HunyuanVideo_1_5_DiffusionTransformer` (line 316) `class HunyuanVideo_1_5_DiffusionTransformer(ModelMixin, ConfigMixin, PeftAdapterMixin)` - *HunyuanVideo Transformer backbone.

Args:
    patch_size (list): The size of the patch.
    in_channels (int): The number of input channels.
    out_channels (int): The number of output channels.
    hidden_size (int): The hidden size of the transformer backbone.
    heads_num (int): The number of attention heads.
    mlp_width_ratio (float): Width ratio for the transformer MLPs.
    mlp_act_type (str): Activation type for the transformer MLPs.
    mm_double_blocks_depth (int): Number of double-stream transformer blocks.
    mm_single_blocks_depth (int): Number of single-stream transformer blocks.
    rope_dim_list (list): Rotary embedding dim for t, h, w.
    qkv_bias (bool): Use bias in qkv projection.
    qk_norm (bool): Whether to use qk norm.
    qk_norm_type (str): Type of qk norm.
    guidance_embed (bool): Use guidance embedding for distillation.
    text_projection (str): Text input projection. Default is "single_refiner".
    use_attention_mask (bool): If to use attention mask.
    text_states_dim (int): Text encoder output dim.
    text_states_dim_2 (int): Secondary text encoder output dim.
    text_pool_type (str): Type for text pooling.
    rope_theta (int): Rotary embedding theta parameter.
    attn_mode (str): Attention mode identifier.
    attn_param (dict): Attention parameter dictionary.
    glyph_byT5_v2 (bool): Use ByT5 glyph module.
    vision_projection (str): Vision condition embedding mode.
    vision_states_dim (int): Vision encoder states input dim.
    is_reshape_temporal_channels (bool): For video VAE adaptation.
    use_cond_type_embedding (bool): Use condition type embedding.*

**Functions:**
- `__init__` (line 47) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- `enable_deterministic` (line 111) `def enable_deterministic(self)`
- `disable_deterministic` (line 114) `def disable_deterministic(self)`
- `forward` (line 117) `def forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)`
- `__init__` (line 210) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dtype, device)`
- `enable_deterministic` (line 255) `def enable_deterministic(self)`
- `disable_deterministic` (line 258) `def disable_deterministic(self)`
- `forward` (line 261) `def forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)` - *Forward pass for the single stream block.*
- `__init__` (line 351) `def __init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, mm_double_blocks_depth, mm_single_blocks_depth, rope_dim_list, qkv_bias, qk_norm, qk_norm_type, guidance_embed, use_meanflow, text_projection, use_attention_mask, text_states_dim, text_states_dim_2, text_pool_type, rope_theta, attn_mode, attn_param, glyph_byT5_v2, vision_projection, vision_states_dim, is_reshape_temporal_channels, use_cond_type_embedding, ideal_resolution, ideal_task)`
- `load_hunyuan_state_dict` (line 563) `def load_hunyuan_state_dict(self, model_path)`
- `enable_deterministic` (line 601) `def enable_deterministic(self)`
- `disable_deterministic` (line 607) `def disable_deterministic(self)`
- `get_rotary_pos_embed` (line 613) `def get_rotary_pos_embed(self, rope_sizes)`
- `reorder_txt_token` (line 631) `def reorder_txt_token(self, byt5_txt, txt, byt5_text_mask, text_mask, zero_feat, is_reorder)`
- `forward` (line 667) `def forward(self, hidden_states, timestep, text_states, text_states_2, encoder_attention_mask, timestep_r, vision_states, output_features, output_features_stride, attention_kwargs, freqs_cos, freqs_sin, return_dict, guidance, mask_type, extra_kwargs)`
- `unpatchify` (line 867) `def unpatchify(self, x, t, h, w)` - *Unpatchify a tensorized input back to frame format.

Args:
    x (Tensor): Input tensor of shape (N, T, patch_size**2 * C)
    t (int): Number of time steps
    h (int): Height in patch units
    w (int): Width in patch units

Returns:
    Tensor: Output tensor of shape (N, C, t * pt, h * ph, w * pw)*
- `set_attn_mode` (line 888) `def set_attn_mode(self, attn_mode)`
- `save_lora_adapter` (line 896) `def save_lora_adapter(self, save_directory, adapter_name, upcast_before_saving, safe_serialization, weight_name)` - *Save the LoRA parameters corresponding to the underlying model.

Arguments:
    save_directory (`str` or `os.PathLike`):
        Directory to save LoRA parameters to. Will be created if it doesn't exist.
    adapter_name: (`str`, defaults to "default"): The name of the adapter to serialize. Useful when the
        underlying model has multiple adapters loaded.
    upcast_before_saving (`bool`, defaults to `False`):
        Whether to cast the underlying model to `torch.float32` before serialization.
    safe_serialization (`bool`, *optional*, defaults to `True`):
        Whether to save the model using `safetensors` or the traditional PyTorch way with `pickle`.
    weight_name: (`str`, *optional*, defaults to `None`): Name of the file to serialize the state dict with.*
- `save_function` (line 943) `def save_function(weights, filename)`

#### `activation_layers.py`
**Path:** `hyvideo/models/transformers/modules/activation_layers.py`

**Functions:**
- `get_activation_layer` (line 20) `def get_activation_layer(act_type)` - *get activation layer

Args:
    act_type (str): the activation type

Returns:
    torch.nn.functional: the activation layer*

#### `attention.py`
**Path:** `hyvideo/models/transformers/modules/attention.py`

**Functions:**
- `attention` (line 50) `def attention(q, k, v, drop_rate, attn_mask, causal, attn_mode)` - *Compute attention using flash_attn_no_pad or torch scaled_dot_product_attention.

Args:
    q: Query tensor of shape [B, L, H, D]
    k: Key tensor of shape [B, L, H, D]
    v: Value tensor of shape [B, L, H, D]
    drop_rate: Dropout rate for attention weights.
    attn_mask: Optional attention mask of shape [B, L].
    causal: Whether to apply causal masking.
    attn_mode: Attention mode, either "flash" or "torch". Defaults to "flash".

Returns:
    Output tensor after attention of shape [B, L, H*D]*
- `parallel_attention` (line 112) `def parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
- `sequence_parallel_attention` (line 120) `def sequence_parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)`
- `shrink_head` (line 145) `def shrink_head(encoder_state, dim)`
- `score_mod` (line 188) `def score_mod(score, b, h, q_idx, kv_idx)`
- `get_image_tile` (line 231) `def get_image_tile(tile_size)`

#### `embed_layers.py`
**Path:** `hyvideo/models/transformers/modules/embed_layers.py`

**Classes:**
- `PatchEmbed` (line 23) `class PatchEmbed` - *2D Image to Patch Embedding

Image to Patch Embedding using Conv2d

A convolution based approach to patchifying a 2D image w/ embedding projection.

Based on the impl in https://github.com/google-research/vision_transformer

Hacked together by / Copyright 2020 Ross Wightman

Remove the _assert function in forward function to be compatible with multi-resolution images.*
- `TextProjection` (line 90) `class TextProjection` - *Projects text embeddings. Also handles dropout for classifier-free guidance.

Adapted from https://github.com/PixArt-alpha/PixArt-alpha/blob/master/diffusion/model/nets/PixArt_blocks.py*
- `VisionProjection` (line 122) `class VisionProjection`
- `ClipVisionProjection` (line 139) `class ClipVisionProjection`
- `TimestepEmbedder` (line 178) `class TimestepEmbedder` - *Embeds scalar timesteps into vector representations.*

**Functions:**
- `timestep_embedding` (line 151) `def timestep_embedding(t, dim, max_period)` - *Create sinusoidal timestep embeddings.

Args:
    t (torch.Tensor): a 1-D Tensor of N indices, one per batch element. These may be fractional.
    dim (int): the dimension of the output.
    max_period (int): controls the minimum frequency of the embeddings.

Returns:
    embedding (torch.Tensor): An (N, D) Tensor of positional embeddings.

.. ref_link: https://github.com/openai/glide-text2im/blob/main/glide_text2im/nn.py*
- `__init__` (line 37) `def __init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)`
- `forward` (line 82) `def forward(self, x)`
- `__init__` (line 97) `def __init__(self, in_channels, hidden_size, act_layer, dtype, device)`
- `forward` (line 114) `def forward(self, caption)`
- `__init__` (line 124) `def __init__(self, input_dim, output_dim)`
- `forward` (line 136) `def forward(self, vision_embeds)`
- `__init__` (line 140) `def __init__(self, in_channels, out_channels)`
- `forward` (line 147) `def forward(self, x)`
- `__init__` (line 183) `def __init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)`
- `forward` (line 208) `def forward(self, t)`

#### `mlp_layers.py`
**Path:** `hyvideo/models/transformers/modules/mlp_layers.py`

**Classes:**
- `MLP` (line 29) `class MLP` - *MLP as used in Vision Transformer, MLP-Mixer and related networks*
- `LinearWarpforSingle` (line 70) `class LinearWarpforSingle`
- `MLPEmbedder` (line 82) `class MLPEmbedder` - *copied from https://github.com/black-forest-labs/flux/blob/main/src/flux/modules/layers.py*
- `FinalLayer` (line 96) `class FinalLayer` - *The final layer of DiT.*

**Functions:**
- `__init__` (line 32) `def __init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)`
- `forward` (line 60) `def forward(self, x)`
- `__init__` (line 71) `def __init__(self, in_dim, out_dim, bias, device, dtype)`
- `forward` (line 76) `def forward(self, x, y)`
- `__init__` (line 85) `def __init__(self, in_dim, hidden_dim, device, dtype)`
- `forward` (line 92) `def forward(self, x)`
- `__init__` (line 99) `def __init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)`
- `forward` (line 133) `def forward(self, x, c)`

#### `modulate_layers.py`
**Path:** `hyvideo/models/transformers/modules/modulate_layers.py`

**Classes:**
- `ModulateDiT` (line 23) `class ModulateDiT` - *Modulation layer for DiT.*

**Functions:**
- `modulate` (line 46) `def modulate(x, shift, scale)` - *modulate by shift and scale

Args:
    x (torch.Tensor): input tensor.
    shift (torch.Tensor, optional): shift tensor. Defaults to None.
    scale (torch.Tensor, optional): scale tensor. Defaults to None.

Returns:
    torch.Tensor: the output tensor after modulate.*
- `apply_gate` (line 67) `def apply_gate(x, gate, tanh)` - *AI is creating summary for apply_gate

Args:
    x (torch.Tensor): input tensor.
    gate (torch.Tensor, optional): gate tensor. Defaults to None.
    tanh (bool, optional): whether to use tanh function. Defaults to False.

Returns:
    torch.Tensor: the output tensor after apply gate.*
- `ckpt_wrapper` (line 86) `def ckpt_wrapper(module)`
- `__init__` (line 26) `def __init__(self, hidden_size, factor, act_layer, dtype, device)`
- `forward` (line 42) `def forward(self, x)`
- `ckpt_forward` (line 87) `def ckpt_forward()`

#### `norm_layers.py`
**Path:** `hyvideo/models/transformers/modules/norm_layers.py`

**Classes:**
- `RMSNorm` (line 21) `class RMSNorm`

**Functions:**
- `get_norm_layer` (line 82) `def get_norm_layer(norm_layer)` - *Get the normalization layer.

Args:
    norm_layer (str): The type of normalization layer.

Returns:
    norm_layer (nn.Module): The normalization layer.*
- `__init__` (line 22) `def __init__(self, dim, elementwise_affine, eps, device, dtype)` - *Initialize the RMSNorm normalization layer.

Args:
    dim (int): The dimension of the input tensor.
    eps (float, optional): A small value added to the denominator for numerical stability. Default is 1e-6.

Attributes:
    eps (float): A small value added to the denominator for numerical stability.
    weight (nn.Parameter): Learnable scaling parameter.*
- `_norm` (line 48) `def _norm(self, x)` - *Apply the RMSNorm normalization to the input tensor.

Args:
    x (torch.Tensor): The input tensor.

Returns:
    torch.Tensor: The normalized tensor.*
- `reset_parameters` (line 61) `def reset_parameters(self)`
- `forward` (line 65) `def forward(self, x)` - *Forward pass through the RMSNorm layer.

Args:
    x (torch.Tensor): The input tensor.

Returns:
    torch.Tensor: The output tensor after applying RMSNorm.*

#### `posemb_layers.py`
**Path:** `hyvideo/models/transformers/modules/posemb_layers.py`

**Functions:**
- `_to_tuple` (line 23) `def _to_tuple(x, dim)`
- `get_meshgrid_nd` (line 32) `def get_meshgrid_nd(start)` - *Get n-D meshgrid with start, stop and num.

Args:
    start (int or tuple): If len(args) == 0, start is num; If len(args) == 1, start is start, args[0] is stop,
        step is 1; If len(args) == 2, start is start, args[0] is stop, args[1] is num. For n-dim, start/stop/num
        should be int or n-tuple. If n-tuple is provided, the meshgrid will be stacked following the dim order in
        n-tuples.
    *args: See above.
    dim (int): Dimension of the meshgrid. Defaults to 2.

Returns:
    grid (np.ndarray): [dim, ...]*
- `reshape_for_broadcast` (line 83) `def reshape_for_broadcast(freqs_cis, x, head_first)` - *Reshape frequency tensor for broadcasting it with another tensor.

This function reshapes the frequency tensor to have the same shape as the target tensor 'x'
for the purpose of broadcasting the frequency tensor during element-wise operations.

Notes:
    When using FlashMHAModified, head_first should be False.
    When using Attention, head_first should be True.

Args:
    freqs_cis (Union[torch.Tensor, Tuple[torch.Tensor]]): Frequency tensor to be reshaped.
    x (torch.Tensor): Target tensor for broadcasting compatibility.
    head_first (bool): head dimension first (except batch dim) or not.

Returns:
    torch.Tensor: Reshaped frequency tensor.

Raises:
    AssertionError: If the frequency tensor doesn't match the expected shape.
    AssertionError: If the target tensor 'x' doesn't have the expected number of dimensions.*
- `rotate_half` (line 151) `def rotate_half(x)`
- `apply_rotary_emb` (line 158) `def apply_rotary_emb(xq, xk, freqs_cis, head_first)` - *Apply rotary embeddings to input tensors using the given frequency tensor.

This function applies rotary embeddings to the given query 'xq' and key 'xk' tensors using the provided
frequency tensor 'freqs_cis'. The input tensors are reshaped as complex numbers, and the frequency tensor
is reshaped for broadcasting compatibility. The resulting tensors contain rotary embeddings and are
returned as real tensors.

Args:
    xq (torch.Tensor): Query tensor to apply rotary embeddings. [B, S, H, D]
    xk (torch.Tensor): Key tensor to apply rotary embeddings.   [B, S, H, D]
    freqs_cis (torch.Tensor or tuple): Precomputed frequency tensor for complex exponential.
    head_first (bool): head dimension first (except batch dim) or not.

Returns:
    Tuple[torch.Tensor, torch.Tensor]: Tuple of modified query tensor and key tensor with rotary embeddings.*
- `get_nd_rotary_pos_embed` (line 210) `def get_nd_rotary_pos_embed(rope_dim_list, start)` - *This is a n-d version of precompute_freqs_cis, which is a RoPE for tokens with n-d structure.

Args:
    rope_dim_list (list of int): Dimension of each rope. len(rope_dim_list) should equal to n.
        sum(rope_dim_list) should equal to head_dim of attention layer.
    start (int | tuple of int | list of int): If len(args) == 0, start is num; If len(args) == 1, start is start,
        args[0] is stop, step is 1; If len(args) == 2, start is start, args[0] is stop, args[1] is num.
    *args: See above.
    theta (float): Scaling factor for frequency computation. Defaults to 10000.0.
    use_real (bool): If True, return real part and imaginary part separately. Otherwise, return complex numbers.
        Some libraries such as TensorRT does not support complex64 data type. So it is useful to provide a real
        part and an imaginary part separately.
    theta_rescale_factor (float): Rescale factor for theta. Defaults to 1.0.

Returns:
    pos_embed (torch.Tensor): [HW, D/2]*
- `get_1d_rotary_pos_embed` (line 281) `def get_1d_rotary_pos_embed(dim, pos, theta, use_real, theta_rescale_factor, interpolation_factor)` - *Precompute the frequency tensor for complex exponential (cis) with given dimensions.
(Note: `cis` means `cos + i * sin`, where i is the imaginary unit.)

This function calculates a frequency tensor with complex exponential using the given dimension 'dim'
and the end index 'end'. The 'theta' parameter scales the frequencies.
The returned tensor contains complex values in complex64 data type.

Args:
    dim (int): Dimension of the frequency tensor.
    pos (int or torch.FloatTensor): Position indices for the frequency tensor. [S] or scalar
    theta (float, optional): Scaling factor for frequency computation. Defaults to 10000.0.
    use_real (bool, optional): If True, return real part and imaginary part separately.
                               Otherwise, return complex numbers.
    theta_rescale_factor (float, optional): Rescale factor for theta. Defaults to 1.0.

Returns:
    freqs_cis: Precomputed frequency tensor with complex exponential. [S, D/2]
    freqs_cos, freqs_sin: Precomputed frequency tensor with real and imaginary parts separately. [S, D]*

#### `ssta_attention.py`
**Path:** `hyvideo/models/transformers/modules/ssta_attention.py`

**Functions:**
- `tile` (line 23) `def tile(x, canvas_thw, tile_thw, sp_size)` - *Rearrange tensor into tiles for block-based attention.

Args:
    x: Input tensor with shape (b, head, s, d) where s = t * h * w
    canvas_thw: Tuple of (t, h, w) representing temporal, height, width dimensions
    tile_thw: Tuple of (tile_t, tile_h, tile_w) representing tile dimensions
    sp_size: Spatial size parameter, defaults to 1

Returns:
    Rearranged tensor organized by tiles*
- `untile` (line 53) `def untile(x, canvas_thw, tile_thw, sp_size)` - *Reverse the tiling operation to restore original tensor layout.

Args:
    x: Tiled tensor
    canvas_thw: Tuple of (t, h, w) representing temporal, height, width dimensions
    tile_thw: Tuple of (tile_t, tile_h, tile_w) representing tile dimensions
    sp_size: Spatial size parameter, defaults to 1

Returns:
    Restored tensor with original layout*
- `get_tile_t_h_w` (line 82) `def get_tile_t_h_w(tile_id, tile_thw_dim)` - *Extract temporal, height, and width indices from a flattened tile ID.*
- `importance_sampling` (line 90) `def importance_sampling(q, k, topk, threshold, lambda_, adaptive_pool)` - *Select top-k blocks based on importance scores considering both similarity and redundancy.

Args:
    q: Query tensor with shape (B, H, S, D)
    k: Key tensor with shape (B, H, K, D)
    topk: Number of top blocks to select
    threshold: Threshold parameter (not implemented)
    lambda_: Weight factor balancing similarity and redundancy
    adaptive_pool: Adaptive pooling parameter (unused)

Returns:
    top_block_indices: Indices of selected blocks with shape (B, H, S, topk)*
- `similarity_sampling` (line 126) `def similarity_sampling(q, k, topk, threshold, block_num, adaptive_pool, temperature)` - *Select top-k blocks based on similarity scores between query and key averages.

Args:
    q: Query tensor with shape (B, H, S, D)
    k: Key tensor with shape (B, H, K, D)
    topk: Number of top blocks to select
    threshold: Cumulative score threshold for dynamic topk selection
    block_num: Total number of blocks (unused)
    adaptive_pool: Adaptive pooling parameter (unused)
    temperature: Temperature scaling for softmax

Returns:
    top_block_indices: Indices of selected blocks with shape (B, H, S, topk)*
- `create_moba_3d_mask` (line 170) `def create_moba_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, add_text_mask, threshold, lambda_, mask_share_within_head, q_block_avg_pool, adaptive_pool, sampling_type)` - *Create MOBA (Mixture of Block Attention) 3D mask for sparse attention.

Args:
    q: Query tensor
    k: Key tensor
    canvas_thw: Canvas dimensions (t, h, w)
    topk: Number of top blocks to attend to
    tile_thw: Tile dimensions
    kernel_thw: Kernel dimensions
    text_block_num: Number of text blocks
    add_text_mask: Whether to add text mask
    threshold: Threshold for similarity sampling
    lambda_: Weight factor for importance sampling
    mask_share_within_head: Whether to share mask across heads
    q_block_avg_pool: Whether to apply average pooling to query blocks
    adaptive_pool: Adaptive pooling size
    sampling_type: Type of sampling ("similarity" or "importance")

Returns:
    moba_3d_mask: 3D attention mask with shape (num_heads, block_num, block_num)*
- `create_sta_3d_mask_optimize` (line 323) `def create_sta_3d_mask_optimize(canvas_thw, tile_thw, kernel_thw)` - *Create optimized STA (Spatio-Temporal Attention) 3D mask using vectorized operations.

Args:
    canvas_thw: String representation of canvas dimensions "t_h_w"
    tile_thw: String representation of tile dimensions "t_h_w"
    kernel_thw: String representation of kernel dimensions "t_h_w"

Returns:
    block_mask: Boolean mask tensor with shape (block_num, block_num)*
- `create_sta_3d_mask` (line 374) `def create_sta_3d_mask(canvas_thw, tile_thw, kernel_thw, text_block_num)` - *Create STA (Spatio-Temporal Attention) 3D mask.

Args:
    canvas_thw: Canvas dimensions (t, h, w)
    tile_thw: Tile dimensions
    kernel_thw: Kernel dimensions
    text_block_num: Number of text blocks to pad

Returns:
    sta_mask: Boolean mask tensor with optional text block padding*
- `create_ssta_3d_mask` (line 404) `def create_ssta_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, threshold, lambda_, text_mask, mask_share_within_head, adaptive_pool, sampling_type)` - *Create SSTA (Sparse Spatio-Temporal Attention) 3D mask combining STA and MOBA masks.

Args:
    q: Query tensor
    k: Key tensor
    canvas_thw: Canvas dimensions (t, h, w)
    topk: Number of top blocks to attend to
    tile_thw: Tile dimensions
    kernel_thw: Kernel dimensions
    text_block_num: Number of text blocks
    threshold: Threshold for similarity sampling
    lambda_: Weight factor for importance sampling
    text_mask: Optional text mask tensor
    mask_share_within_head: Whether to share mask across heads
    adaptive_pool: Adaptive pooling size
    sampling_type: Type of sampling ("similarity" or "importance")

Returns:
    ssta_3d_mask: Combined 3D attention mask*
- `ssta_3d_attention` (line 465) `def ssta_3d_attention(all_q, all_k, all_v, canvas_thw, topk, tile_thw, kernel_thw, text_len, sparse_type, threshold, lambda_, pad_type, text_mask, mask_share_within_head, sampling_type, adaptive_pool)` - *Sparse Spatio-Temporal Attention (SSTA) 3D attention mechanism.

Args:
    all_q: Query tensor with shape (B, H, S, D)
    all_k: Key tensor with shape (B, H, S, D)
    all_v: Value tensor with shape (B, H, S, D)
    canvas_thw: Canvas dimensions (t, h, w)
    topk: Number of top blocks to attend to
    tile_thw: Tile dimensions
    kernel_thw: Kernel dimensions
    text_len: Length of text sequence
    sparse_type: Type of sparse attention ('sta', 'block_attn', or 'ssta')
    threshold: Threshold for similarity sampling
    lambda_: Weight factor for importance sampling
    pad_type: Padding type ("zero" or "repeat")
    text_mask: Optional text mask tensor
    mask_share_within_head: Whether to share mask across heads
    sampling_type: Type of sampling ("similarity" or "importance")
    adaptive_pool: Adaptive pooling size

Returns:
    tuple: (output tensor, sparse_ratio)
        - output: Attention output with shape (B, H, S, D)
        - sparse_ratio: Ratio of non-zero attention weights*
- `get_block_avg_feat` (line 216) `def get_block_avg_feat(x, adaptive_pool, pooling_type)`

#### `token_refiner.py`
**Path:** `hyvideo/models/transformers/modules/token_refiner.py`

**Classes:**
- `IndividualTokenRefinerBlock` (line 33) `class IndividualTokenRefinerBlock` - *A single block for token refinement with self-attention and MLP.

Args:
    hidden_size: Hidden dimension size.
    heads_num: Number of attention heads.
    mlp_width_ratio: Expansion ratio for MLP hidden size.
    mlp_drop_rate: Dropout rate for MLP.
    act_type: Activation function type.
    qk_norm: Whether to use QK normalization.
    qk_norm_type: Type of QK normalization.
    qkv_bias: Whether to use bias in QKV projections.
    dtype: Optional torch dtype.
    device: Optional torch device.*
- `IndividualTokenRefiner` (line 127) `class IndividualTokenRefiner` - *Stacks multiple IndividualTokenRefinerBlock modules.

Args:
    hidden_size: Hidden dimension size.
    heads_num: Number of attention heads.
    depth: Number of blocks.
    mlp_width_ratio: Expansion ratio for MLP hidden size.
    mlp_drop_rate: Dropout rate for MLP.
    act_type: Activation function type.
    qk_norm: Whether to use QK normalization.
    qk_norm_type: Type of QK normalization.
    qkv_bias: Whether to use bias in QKV projections.
    dtype: Optional torch dtype.
    device: Optional torch device.*
- `SingleTokenRefiner` (line 203) `class SingleTokenRefiner` - *Single token refiner block for LLM text embedding refinement.

Args:
    in_channels: Input feature dimension.
    hidden_size: Hidden dimension size.
    heads_num: Number of attention heads.
    depth: Number of blocks.
    mlp_width_ratio: Expansion ratio for MLP hidden size.
    mlp_drop_rate: Dropout rate for MLP.
    act_type: Activation function type.
    qk_norm: Whether to use QK normalization.
    qk_norm_type: Type of QK normalization.
    qkv_bias: Whether to use bias in QKV projections.
    dtype: Optional torch dtype.
    device: Optional torch device.*

**Functions:**
- `__init__` (line 50) `def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- `forward` (line 98) `def forward(self, x, c, attn_mask)` - *Forward pass for IndividualTokenRefinerBlock.

Args:
    x: Input tensor of shape [B, L, C].
    c: Conditioning tensor of shape [B, C].
    attn_mask: Optional attention mask of shape [B, L].

Returns:
    Refined tensor of shape [B, L, C].*
- `__init__` (line 145) `def __init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- `forward` (line 178) `def forward(self, x, c, mask)` - *Forward pass for IndividualTokenRefiner.

Args:
    x: Input tensor of shape [B, L, C].
    c: Conditioning tensor of shape [B, C].
    mask: Optional mask tensor of shape [B, L].

Returns:
    Refined tensor of shape [B, L, C].*
- `__init__` (line 222) `def __init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)`
- `forward` (line 256) `def forward(self, x, t, mask)` - *Forward pass for SingleTokenRefiner.

Args:
    x: Input tensor of shape [B, L, in_channels].
    t: Timestep tensor of shape [B].
    mask: Optional mask tensor of shape [B, L].

Returns:
    Refined tensor of shape [B, L, hidden_size].*

#### `upsample.py`
**Path:** `hyvideo/models/transformers/modules/upsample.py`

**Classes:**
- `UpsamplerType` (line 38) `class UpsamplerType(Enum)`
- `UpsamplerConfig` (line 46) `class UpsamplerConfig`
- `SRResidualCausalBlock3D` (line 55) `class SRResidualCausalBlock3D`
- `SRTo720pUpsampler` (line 70) `class SRTo720pUpsampler(ModelMixin, ConfigMixin)`
- `SRTo1080pUpsampler` (line 100) `class SRTo1080pUpsampler(ModelMixin, ConfigMixin)`

**Functions:**
- `__init__` (line 56) `def __init__(self, channels)`
- `forward` (line 66) `def forward(self, x)`
- `__init__` (line 73) `def __init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)`
- `forward` (line 89) `def forward(self, x)`
- `__init__` (line 103) `def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)`
- `forward` (line 137) `def forward(self, z, target_shape)` - *Args:
    z: (B, C, T, H, W)
    target_shape: (H, W)*

#### `__init__.py`
**Path:** `hyvideo/models/vision_encoder/__init__.py`

**Classes:**
- `VisionEncoderModelOutput` (line 83) `class VisionEncoderModelOutput(ModelOutput)` - *Base class for vision encoder model's outputs.

Args:
    last_hidden_state (`torch.FloatTensor` of shape `(batch_size, sequence_length, hidden_size)`):
        Sequence of hidden-states at the output of the last layer of the model.
    pooler_output (`torch.FloatTensor` of shape `(batch_size, hidden_size)`, *optional*):
        Last layer hidden-state of the first token of the sequence (classification token)
        after further processing through the layers used for the auxiliary pretraining task.
    hidden_states (`tuple(torch.FloatTensor)`, *optional*, returned when `output_hidden_states=True` is passed):
        Tuple of `torch.FloatTensor` (one for the output of the embeddings, if the model has an embedding layer, +
        one for the output of each layer) of shape `(batch_size, sequence_length, hidden_size)`.
        Hidden-states of the model at the output of each layer plus the optional initial embedding outputs.*
- `VisionEncoder` (line 104) `class VisionEncoder`

**Functions:**
- `use_default` (line 29) `def use_default(value, default)`
- `load_vision_encoder` (line 33) `def load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)`
- `load_image_processor` (line 63) `def load_image_processor(processor_type, processor_path, logger)`
- `__init__` (line 105) `def __init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type, processor_path, output_key, logger, device)`
- `__repr__` (line 149) `def __repr__(self)`
- `encode_latents_to_images` (line 152) `def encode_latents_to_images(self, latents, vae, reorg_token)` - *Convert latents to images using VAE decoder.

Args:
    latents: Input latents tensor
    vae: VAE model for decoding
    reorg_token: Whether to reorg the token
Returns:
    images: Decoded images as numpy array*
- `encode_images` (line 179) `def encode_images(self, images)` - *Encode images using the vision encoder.

Args:
    images: Input images (numpy array or preprocessed tensor)
    
Returns:
    VisionEncoderModelOutput with encoded features*
- `encode_latents` (line 205) `def encode_latents(self, latents, vae, reorg_token)` - *Encode latents by first converting to images, then encoding.
This is the main function that replaces sigclip_vision_encode.

Args:
    latents: Input latent tensors
    vae: VAE model for decoding latents to images
    
Returns:
    Encoded image features*
- `forward` (line 225) `def forward(self, images)` - *Forward pass for direct image encoding.

Args:
    images: Input images
    
Returns:
    VisionEncoderModelOutput with encoded features*

#### `muon.py`
**Path:** `hyvideo/optim/muon.py`

**Classes:**
- `Muon` (line 54) `class Muon` - *Muon - MomentUm Orthogonalized by Newton-schulz

Arguments:
    muon_params: The parameters to be optimized by Muon.
    lr: The learning rate. The updates will have spectral norm of `lr`. (0.02 is a good default)
    momentum: The momentum used by the internal SGD. (0.95 is a good default)
    nesterov: Whether to use Nesterov-style momentum in the internal SGD. (recommended)
    ns_steps: The number of Newton-Schulz iterations to run. (6 is probably always enough)
    adamw_params: The parameters to be optimized by AdamW. Any parameters in `muon_params` which are
    {0, 1}-D or are detected as being the embed or lm_head will be optimized by AdamW as well.
    adamw_lr: The learning rate for the internal AdamW.
    adamw_betas: The betas for the internal AdamW.
    adamw_eps: The epsilon for the internal AdamW.
    adamw_wd: The weight decay for the internal AdamW.*

**Functions:**
- `zeropower_via_newtonschulz5` (line 17) `def zeropower_via_newtonschulz5(G, steps)` - *Newton-Schulz iteration to compute the zeroth power / orthogonalization of G. We opt to use a
quintic iteration whose coefficients are selected to maximize the slope at zero. For the purpose
of minimizing steps, it turns out to be empirically effective to keep increasing the slope at
zero even beyond the point where the iteration no longer converges all the way to one everywhere
on the interval. This iteration therefore does not produce UV^T but rather something like US'V^T
where S' is diagonal with S_{ii}' ~ Uniform(0.5, 1.5), which turns out not to hurt model
performance at all relative to UV^T, where USV^T = G is the SVD.*
- `get_muon_optimizer` (line 214) `def get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)`
- `__init__` (line 72) `def __init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)`
- `adjust_lr_for_muon` (line 108) `def adjust_lr_for_muon(self, lr, param_shape)`
- `step` (line 116) `def step(self, closure)` - *Perform a single optimization step.

Args:
    closure (Callable, optional): A closure that reevaluates the model
        and returns the loss.*

#### `hunyuan_video_pipeline.py`
**Path:** `hyvideo/pipelines/hunyuan_video_pipeline.py`

**Classes:**
- `HunyuanVideoPipelineOutput` (line 82) `class HunyuanVideoPipelineOutput(BaseOutput)`
- `HunyuanVideo_1_5_Pipeline` (line 87) `class HunyuanVideo_1_5_Pipeline(DiffusionPipeline)`

**Functions:**
- `__init__` (line 92) `def __init__(self, vae, text_encoder, transformer, scheduler, text_encoder_2, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)`
- `_create_scheduler` (line 185) `def _create_scheduler(cls, flow_shift)`
- `_load_byt5` (line 194) `def _load_byt5(cls, cached_folder, glyph_byT5_v2, byt5_max_length, device)`
- `encode_prompt` (line 242) `def encode_prompt(self, prompt, device, num_videos_per_prompt, do_classifier_free_guidance, negative_prompt, prompt_embeds, attention_mask, negative_prompt_embeds, negative_attention_mask, clip_skip, text_encoder, data_type)` - *Encodes the prompt into text encoder hidden states.

Args:
    prompt (`str` or `List[str]`, *optional*):
        prompt to be encoded
    device: (`torch.device`):
        torch device
    num_videos_per_prompt (`int`):
        number of videos that should be generated per prompt
    do_classifier_free_guidance (`bool`):
        whether to use classifier free guidance or not
    negative_prompt (`str` or `List[str]`, *optional*):
        The prompt or prompts not to guide the video generation. If not defined, one has to pass
        `negative_prompt_embeds` instead. Ignored when not using guidance (i.e., ignored if `guidance_scale` is
        less than `1`).
    prompt_embeds (`torch.Tensor`, *optional*):
        Pre-generated text embeddings. Can be used to easily tweak text inputs, *e.g.* prompt weighting. If not
        provided, text embeddings will be generated from `prompt` input argument.
    attention_mask (`torch.Tensor`, *optional*):
    negative_prompt_embeds (`torch.Tensor`, *optional*):
        Pre-generated negative text embeddings. Can be used to easily tweak text inputs, *e.g.* prompt
        weighting. If not provided, negative_prompt_embeds will be generated from `negative_prompt` input
        argument.
    negative_attention_mask (`torch.Tensor`, *optional*):
        Attention mask for negative prompt embeddings.
    clip_skip (`int`, *optional*):
        Number of layers to be skipped from CLIP while computing the prompt embeddings. A value of 1 means that
        the output of the pre-final layer will be used for computing the prompt embeddings.
    text_encoder (TextEncoder, *optional*):
        Text encoder to use. If None, uses the pipeline's default text encoder.
    data_type (`str`, *optional*):
        Type of data being encoded. Defaults to "image".*
- `prepare_extra_func_kwargs` (line 413) `def prepare_extra_func_kwargs(self, func, kwargs)` - *Prepare extra keyword arguments for scheduler functions.

Filters kwargs to only include parameters that the function accepts.
This is useful since not all schedulers have the same signature.*
- `prepare_latents` (line 429) `def prepare_latents(self, batch_size, num_channels_latents, latent_height, latent_width, video_length, dtype, device, generator, latents)` - *Prepare latents for video generation.

Args:
    batch_size: Batch size for generation.
    num_channels_latents: Number of channels in latent space.
    latent_height: Height of latent tensors.
    latent_width: Width of latent tensors.
    video_length: Number of frames in the video.
    dtype: Data type for latents.
    device: Target device for latents.
    generator: Random number generator.
    latents: Pre-computed latents. If None, random latents are generated.

Returns:
    torch.Tensor: Prepared latents tensor.*
- `get_guidance_scale_embedding` (line 483) `def get_guidance_scale_embedding(self, w, embedding_dim, dtype)` - *See https://github.com/google-research/vdm/blob/dc27b98a554f65cdc654b800da5aa1846545d41b/model_vdm.py#L298

Args:
    w (`torch.Tensor`):
        Generate embedding vectors with a specified guidance scale to subsequently enrich timestep embeddings.
    embedding_dim (`int`, *optional*, defaults to 512):
        Dimension of the embeddings to generate.
    dtype (`torch.dtype`, *optional*, defaults to `torch.float32`):
        Data type of the generated embeddings.

Returns:
    `torch.Tensor`: Embedding vectors with shape `(len(w), embedding_dim)`.*
- `guidance_scale` (line 517) `def guidance_scale(self)`
- `guidance_rescale` (line 521) `def guidance_rescale(self)`
- `clip_skip` (line 525) `def clip_skip(self)`
- `do_classifier_free_guidance` (line 532) `def do_classifier_free_guidance(self)`
- `cross_attention_kwargs` (line 536) `def cross_attention_kwargs(self)`
- `num_timesteps` (line 540) `def num_timesteps(self)`
- `interrupt` (line 544) `def interrupt(self)`
- `get_byt5_text_tokens` (line 548) `def get_byt5_text_tokens(byt5_tokenizer, byt5_max_length, text_prompt)` - *Tokenize text prompt for byT5 model.

Args:
    byt5_tokenizer: The byT5 tokenizer.
    byt5_max_length: Maximum sequence length for tokenization.
    text_prompt: Text prompt string to tokenize.

Returns:
    tuple[torch.Tensor, torch.Tensor]:
        - input_ids: Tokenized input IDs.
        - attention_mask: Attention mask tensor.*
- `_extract_glyph_texts` (line 573) `def _extract_glyph_texts(self, prompt)` - *Extract glyph texts from prompt using regex pattern.

Args:
    prompt: Input prompt string containing quoted text.

Returns:
    List[str]: List of extracted glyph texts (deduplicated if multiple).*
- `_process_single_byt5_prompt` (line 589) `def _process_single_byt5_prompt(self, prompt_text, device)` - *Process a single prompt for byT5 encoding.

Args:
    prompt_text: The prompt text to process.
    device: Target device for tensors.

Returns:
    tuple[torch.Tensor, torch.Tensor]:
        - byt5_embeddings: Encoded embeddings tensor.
        - byt5_mask: Attention mask tensor.*
- `_prepare_byt5_embeddings` (line 623) `def _prepare_byt5_embeddings(self, prompts, device)` - *Prepare byT5 embeddings for both positive and negative prompts.

Args:
    prompts: List of prompt strings or single prompt string.
    device: Target device for tensors.

Returns:
    dict: Dictionary containing:
        - "byt5_text_states": Combined embeddings tensor.
        - "byt5_text_mask": Combined attention mask tensor.
        Returns empty dict if glyph_byT5_v2 is disabled.*
- `extract_image_features` (line 680) `def extract_image_features(self, reference_image)` - *Extract features from a reference image using VisionEncoder.

Args:
    reference_image: numpy array of shape (H, W, 3) with dtype uint8.

Returns:
    VisionEncoderModelOutput: Encoded image features.*
- `_prepare_vision_states` (line 698) `def _prepare_vision_states(self, reference_image, target_resolution, latents, device)` - *Prepare vision states for multitask training.

Args:
    reference_image: Reference image for i2v tasks (None for t2v tasks).
    target_resolution: Target size for i2v tasks.
    latents: Latent tensors.
    device: Target device.

Returns:
    torch.Tensor or None: Vision states tensor or None if vision encoder is unavailable.*
- `_prepare_cond_latents` (line 734) `def _prepare_cond_latents(self, task_type, cond_latents, latents, multitask_mask)` - *Prepare conditional latents and mask for multitask training.

Args:
    task_type: Type of task ("i2v" or "t2v").
    cond_latents: Conditional latents tensor.
    latents: Main latents tensor.
    multitask_mask: Multitask mask tensor.

Returns:
    tuple[torch.Tensor, torch.Tensor]:
        - latents_concat: Concatenated conditional latents.
        - mask_concat: Concatenated mask tensor.*
- `get_task_mask` (line 766) `def get_task_mask(self, task_type, latent_target_length)`
- `get_closest_resolution_given_reference_image` (line 776) `def get_closest_resolution_given_reference_image(self, reference_image, target_resolution)` - *Get closest supported resolution for a reference image.

Args:
    reference_image: PIL Image or numpy array.
    target_resolution: Target resolution string (e.g., "720p", "1080p").

Returns:
    tuple[int, int]: (height, width) of closest supported resolution.*
- `get_closest_resolution_given_original_size` (line 800) `def get_closest_resolution_given_original_size(self, origin_size, target_size)` - *Get closest supported resolution for given original size and target resolution.

Args:
    origin_size: Tuple of (width, height) of original image.
    target_size: Target resolution string (e.g., "720p", "1080p").

Returns:
    tuple[int, int]: (height, width) of closest supported resolution.*
- `get_image_condition_latents` (line 826) `def get_image_condition_latents(self, task_type, reference_image, height, width)`
- `vae_spatial_compression_ratio` (line 861) `def vae_spatial_compression_ratio(self)`
- `vae_temporal_compression_ratio` (line 868) `def vae_temporal_compression_ratio(self)`
- `get_latent_size` (line 874) `def get_latent_size(self, video_length, height, width)`
- `__call__` (line 886) `def __call__(self, prompt, aspect_ratio, video_length, prompt_rewrite, num_inference_steps, guidance_scale, enable_sr, sr_num_inference_steps, negative_prompt, generator, seed, flow_shift, embedded_guidance_scale, reference_image, output_type, return_dict, return_pre_sr_video, enable_vae_tile_parallelism)` - *Generates a video (or videos) based on text (and optionally image) conditions.

Args:
    prompt (`str` or `List[str]`):
        Text prompt(s) to guide video generation.
    aspect_ratio (`str`):
        Output video aspect ratio as a string formatted like "720:1280" or "16:9". Required for text-to-video tasks.
    video_length (`int`):
        Number of frames in the generated video.
    num_inference_steps (`int`, *optional*, defaults to 50):
        Number of denoising steps during generation. Larger values may improve video quality at the expense of slower inference.
    guidance_scale (`float`, *optional*, defaults to value in config):
        Scale to encourage the model to better follow the prompt. `guidance_scale > 1` enables classifier-free guidance.
    enable_sr (`bool`, *optional*, defaults to True):
        Whether to apply super-resolution to the generated video.
    sr_num_inference_steps (`int`, *optional*, defaults to 30):
        Number of inference steps in the super-resolution module (if enabled).
    negative_prompt (`str` or `List[str]`, *optional*):
        Negative prompt(s) that describe what should NOT be shown in the generated video.
    generator (`torch.Generator` or `List[torch.Generator]`, *optional*):
        PyTorch random generator(s) for deterministic results.
    seed (`int`, *optional*):
        If specified, used to create the generator for reproducible sampling.
    flow_shift (`float`, *optional*):
        Flow shift parameter for the scheduler. Overrides the default pipeline configuration if provided.
    embedded_guidance_scale (`float`, *optional*):
        Additional control guidance scale, if supported.
    reference_image (PIL.Image or `str`, *optional*):
        Reference image for image-to-video (i2v) tasks. Can be a PIL image or a path to an image file. Set to `None` for text-to-video (t2v) generation.
    output_type (`str`, *optional*, defaults to "pt"):
        Output format of the returned video(s). Accepted values: `"pt"` for torch.Tensor or `"np"` for numpy.ndarray.
    return_dict (`bool`, *optional*, defaults to True):
        Whether to return a [`HunyuanVideoPipelineOutput`] or a tuple.
    **kwargs:
        Additional keyword arguments.

Returns:
    HunyuanVideoPipelineOutput or `tuple`:
        If `return_dict` is True, returns a [`HunyuanVideoPipelineOutput`] with fields:
            - `videos`: Generated video(s) as a tensor or numpy array.
            - `sr_videos`: Super-resolved video(s) if `enable_sr` is True, else None.
        Otherwise, returns a tuple containing the outputs as above.

Example:
    ```python
    pipe = HunyuanVideoPipeline.from_pretrained("your_model_dir")
    # Text-to-video
    video = pipe(prompt="A dog surfing on the beach", aspect_ratio="9:16", video_length=32).videos
    # Image-to-video
    video = pipe(prompt="Make this image move", reference_image="img.jpg", aspect_ratio="16:9", video_length=24).videos
    ```*
- `ideal_resolution` (line 1324) `def ideal_resolution(self)`
- `ideal_task` (line 1328) `def ideal_task(self)`
- `use_meanflow` (line 1332) `def use_meanflow(self)`
- `apply_infer_optimization` (line 1335) `def apply_infer_optimization(self, infer_state, enable_offloading, enable_group_offloading, overlap_group_offloading)` - *Apply inference optimizations to transformer based on infer_state.

Args:
    infer_state: Optional InferState object containing optimization settings.
    enable_offloading: Whether to enable CPU offloading.
    enable_group_offloading: Whether to enable group offloading.
    overlap_group_offloading: Whether to use overlapping group offloading.*
- `load_sr_transformer_upsampler` (line 1416) `def load_sr_transformer_upsampler(cls, cached_folder, sr_version, transformer_dtype, device)`
- `create_sr_pipeline` (line 1426) `def create_sr_pipeline(self, cached_folder, sr_version, transformer_dtype, device)`
- `get_transformer_version` (line 1452) `def get_transformer_version(resolution, task, cfg_distilled, step_distilled, sparse_attn)`
- `create_pipeline` (line 1467) `def create_pipeline(cls, pretrained_model_name_or_path, transformer_version, create_sr_pipeline, transformer_dtype, device, transformer_init_device)`
- `get_offloading_config` (line 1550) `def get_offloading_config(memory_limitation)`
- `get_vae_inference_config` (line 1566) `def get_vae_inference_config(memory_limitation)`
- `_load_text_encoders` (line 1582) `def _load_text_encoders(cls, pretrained_model_path, device)`
- `_load_vision_encoder` (line 1607) `def _load_vision_encoder(cls, pretrained_model_name_or_path, device)`

#### `hunyuan_video_sr_pipeline.py`
**Path:** `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`

**Classes:**
- `BucketMap` (line 46) `class BucketMap` - *Maps low-resolution bucket sizes to corresponding high-resolution bucket sizes.*
- `HunyuanVideo_1_5_SR_PipelineOutput` (line 81) `class HunyuanVideo_1_5_SR_PipelineOutput(BaseOutput)`
- `HunyuanVideo_1_5_SR_Pipeline` (line 85) `class HunyuanVideo_1_5_SR_Pipeline(HunyuanVideo_1_5_Pipeline)`

**Functions:**
- `expand_dims` (line 42) `def expand_dims(tensor, ndim)`
- `__init__` (line 49) `def __init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)`
- `__call__` (line 62) `def __call__(self, lr_bucket)` - *Args:
    lr_bucket (tuple): Low-resolution bucket size as (width, height).

Returns:
    tuple: High-resolution bucket size as (width, height).*
- `__init__` (line 87) `def __init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, base_resolution, text_encoder_2, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)`
- `add_noise_to_lq` (line 142) `def add_noise_to_lq(self, lq_latents, strength)`
- `_prepare_lq_cond_latents` (line 148) `def _prepare_lq_cond_latents(self, lq_latents)` - *Prepare conditional latents and mask for multitask training.

Args:
    lq_latents: Low-resolution latent tensor.

Returns:
    torch.Tensor: Low-resolution conditional latent tensor.*
- `__call__` (line 165) `def __call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt, num_videos_per_prompt, generator, seed, embedded_guidance_scale, reference_image, lq_latents, output_type, return_dict, enable_vae_tile_parallelism)` - *Runs the super-resolution (SR) pipeline for video generation.

Args:
    prompt (`str` or `List[str]`):
        Text prompt(s) that describe the desired video content.
    video_length (`int`):
        Number of frames in the video to generate.
    num_inference_steps (`int`, *optional*, defaults to value in config):
        Number of denoising steps during SR. Higher values may improve visual quality at the cost of slower inference.
    guidance_scale (`float`, *optional*, defaults to value in config):
        How closely to follow the prompt. `guidance_scale > 1` enables classifier-free guidance.
    negative_prompt (`str` or `List[str]`, *optional*):
        Prompt(s) of what should not appear in the generated video.
    num_videos_per_prompt (`int`, *optional*, defaults to 1):
        Number of videos to generate per prompt.
    generator (`torch.Generator` or `List[torch.Generator]`, *optional*):
        PyTorch random generator(s) for deterministic and reproducible results.
    seed (`int`, *optional*):
        If specified, used to construct a generator for reproducibility.
    embedded_guidance_scale (`float`, *optional*):
        Additional guidance scale for enhanced control, if model supports it.
    reference_image (PIL.Image or `str`, *optional*):
        Reference image for image-to-video (i2v) tasks. Can be a PIL image or local file path. Set to `None` for text-to-video (t2v) mode.
    lq_latents (`torch.Tensor`, *optional*):
        Low-quality (LQ) video latents to use as input for SR upsampling step. Should have shape (B, C, F, H, W).
    output_type (`str`, *optional*, defaults to "pt"):
        Output format, either `"pt"` (PyTorch tensor) or `"np"` (NumPy array).
    return_dict (`bool`, *optional*, defaults to True):
        Whether to return a [`HunyuanVideo_1_5_SR_PipelineOutput`] or a tuple.
    **kwargs:
        Additional keyword arguments.*

#### `pipeline_utils.py`
**Path:** `hyvideo/pipelines/pipeline_utils.py`

**Functions:**
- `retrieve_timesteps` (line 21) `def retrieve_timesteps(scheduler, num_inference_steps, device, timesteps, sigmas)` - *Calls the scheduler's `set_timesteps` method and retrieves timesteps from the scheduler after the call. Handles
custom timesteps. Any kwargs will be supplied to `scheduler.set_timesteps`.

Args:
    scheduler (`SchedulerMixin`):
        The scheduler to get timesteps from.
    num_inference_steps (`int`):
        The number of diffusion steps used when generating samples with a pre-trained model. If used, `timesteps`
        must be `None`.
    device (`str` or `torch.device`, *optional*):
        The device to which the timesteps should be moved to. If `None`, the timesteps are not moved.
    timesteps (`List[int]`, *optional*):
        Custom timesteps used to override the timestep spacing strategy of the scheduler. If `timesteps` is passed,
        `num_inference_steps` and `sigmas` must be `None`.
    sigmas (`List[float]`, *optional*):
        Custom sigmas used to override the timestep spacing strategy of the scheduler. If `sigmas` is passed,
        `num_inference_steps` and `timesteps` must be `None`.

Returns:
    `Tuple[torch.Tensor, int]`: A tuple where the first element is the timestep schedule from the scheduler and the
    second element is the number of inference steps.*
- `rescale_noise_cfg` (line 86) `def rescale_noise_cfg(noise_cfg, noise_pred_text, guidance_rescale)` - *Rescale `noise_cfg` according to `guidance_rescale`. Based on findings of [Common Diffusion Noise Schedules and
Sample Steps are Flawed](https://arxiv.org/pdf/2305.08891.pdf). See Section 3.4*

#### `scheduling_flow_match_discrete.py`
**Path:** `hyvideo/schedulers/scheduling_flow_match_discrete.py`

**Classes:**
- `FlowMatchDiscreteSchedulerOutput` (line 50) `class FlowMatchDiscreteSchedulerOutput(BaseOutput)` - *Output class for the scheduler's `step` function output.

Args:
    prev_sample (`torch.FloatTensor` of shape `(batch_size, num_channels, height, width)` for images):
        Computed sample `(x_{t-1})` of previous timestep. `prev_sample` should be used as next model input in the
        denoising loop.*
- `FlowMatchDiscreteScheduler` (line 63) `class FlowMatchDiscreteScheduler(SchedulerMixin, ConfigMixin)` - *Euler scheduler.

This model inherits from [`SchedulerMixin`] and [`ConfigMixin`]. Check the superclass documentation for the generic
methods the library implements for all schedulers such as loading and saving.

Args:
    num_train_timesteps (`int`, defaults to 1000):
        The number of diffusion steps to train the model.
    timestep_spacing (`str`, defaults to `"linspace"`):
        The way the timesteps should be scaled. Refer to Table 2 of the [Common Diffusion Noise Schedules and
        Sample Steps are Flawed](https://huggingface.co/papers/2305.08891) for more information.
    shift (`float`, defaults to 1.0):
        The shift value for the timestep schedule.
    reverse (`bool`, defaults to `True`):
        Whether to reverse the timestep schedule.*

**Functions:**
- `__init__` (line 86) `def __init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift, n_tokens, flux_base_token, flux_max_token, flux_shift_factor)`
- `step_index` (line 119) `def step_index(self)` - *The index counter for current timestep. It will increase 1 after each scheduler step.*
- `begin_index` (line 126) `def begin_index(self)` - *The index for the first timestep. It should be set from pipeline with `set_begin_index` method.*
- `set_begin_index` (line 133) `def set_begin_index(self, begin_index)` - *Sets the begin index for the scheduler. This function should be run from pipeline before the inference.

Args:
    begin_index (`int`):
        The begin index for the scheduler.*
- `_sigma_to_t` (line 143) `def _sigma_to_t(self, sigma)`
- `set_timesteps` (line 146) `def set_timesteps(self, num_inference_steps, device, n_tokens)` - *Sets the discrete timesteps used for the diffusion chain (to be run before inference).

Args:
    num_inference_steps (`int`):
        The number of diffusion steps used when generating samples with a pre-trained model.
    device (`str` or `torch.device`, *optional*):
        The device to which the timesteps should be moved to. If `None`, the timesteps are not moved.
    n_tokens (`int`, *optional*):
        Number of tokens in the input sequence.*
- `index_for_timestep` (line 182) `def index_for_timestep(self, timestep, schedule_timesteps)`
- `_init_step_index` (line 196) `def _init_step_index(self, timestep)`
- `scale_model_input` (line 204) `def scale_model_input(self, sample, timestep)`
- `get_lin_function` (line 208) `def get_lin_function(x1, y1, x2, y2)`
- `flux_time_shift` (line 214) `def flux_time_shift(mu, sigma, t)`
- `sd3_time_shift` (line 217) `def sd3_time_shift(self, t)`
- `step` (line 220) `def step(self, model_output, timestep, sample, generator, n_tokens, return_dict)` - *Predict the sample from the previous timestep by reversing the SDE. This function propagates the diffusion
process from the learned model outputs (most often the predicted noise).

Args:
    model_output (`torch.FloatTensor`):
        The direct output from learned diffusion model.
    timestep (`float`):
        The current discrete timestep in the diffusion chain.
    sample (`torch.FloatTensor`):
        A current instance of a sample created by the diffusion process.
    generator (`torch.Generator`, *optional*):
        A random number generator.
    n_tokens (`int`, *optional*):
        Number of tokens in the input sequence.
    return_dict (`bool`):
        Whether or not to return a [`~schedulers.scheduling_euler_discrete.EulerDiscreteSchedulerOutput`] or
        tuple.

Returns:
    [`~schedulers.scheduling_euler_discrete.EulerDiscreteSchedulerOutput`] or `tuple`:
        If return_dict is `True`, [`~schedulers.scheduling_euler_discrete.EulerDiscreteSchedulerOutput`] is
        returned, otherwise a tuple is returned where the first element is the sample tensor.*
- `__len__` (line 291) `def __len__(self)`

#### `communications.py`
**Path:** `hyvideo/utils/communications.py`

**Classes:**
- `SeqAllToAll4D` (line 147) `class SeqAllToAll4D`
- `_AllToAll` (line 195) `class _AllToAll` - *All-to-all communication.

Args:
    input_: input matrix
    process_group: communication group
    scatter_dim: scatter dimension
    gather_dim: gather dimension*
- `_Reduce_Scatter` (line 239) `class _Reduce_Scatter`
- `_AllGather` (line 255) `class _AllGather` - *All-gather communication with autograd support.

Args:
    input_: input tensor
    dim: dimension along which to concatenate*

**Functions:**
- `broadcast` (line 24) `def broadcast(input_, group)`
- `_all_to_all_4D` (line 29) `def _all_to_all_4D(input, scatter_idx, gather_idx, group)` - *all-to-all for QKV

Args:
    input (torch.tensor): a tensor sharded along dim scatter dim
    scatter_idx (int): default 1
    gather_idx (int): default 2
    group : torch process group

Returns:
    torch.tensor: resharded tensor (bs, seqlen/P, hc, hs)*
- `all_to_all_4D` (line 174) `def all_to_all_4D(input_, group, scatter_dim, gather_dim)`
- `_all_to_all` (line 180) `def _all_to_all(input_, world_size, group, scatter_dim, gather_dim)`
- `all_to_all` (line 233) `def all_to_all(input_, group, scatter_dim, gather_dim)`
- `all_gather` (line 304) `def all_gather(input_, dim, group)` - *Performs an all-gather operation on the input tensor along the specified dimension.

Args:
    input_ (torch.Tensor): Input tensor of shape [B, H, S, D].
    dim (int, optional): Dimension along which to concatenate. Defaults to 1.

Returns:
    torch.Tensor: Output tensor after all-gather operation, concatenated along 'dim'.*
- `forward` (line 149) `def forward(ctx, group, input, scatter_idx, gather_idx)`
- `backward` (line 163) `def backward(ctx)`
- `forward` (line 206) `def forward(ctx, input_, process_group, scatter_dim, gather_dim)`
- `backward` (line 217) `def backward(ctx, grad_output)`
- `forward` (line 242) `def forward(ctx, op, group, tensor)`
- `backward` (line 251) `def backward(ctx, grad_output)`
- `forward` (line 264) `def forward(ctx, input_, dim, group)`
- `backward` (line 283) `def backward(ctx, grad_output)`

#### `data_utils.py`
**Path:** `hyvideo/utils/data_utils.py`

**Functions:**
- `resize_and_center_crop` (line 20) `def resize_and_center_crop(image, target_width, target_height)`
- `get_closest_ratio` (line 38) `def get_closest_ratio(height, width, ratios, buckets)` - *Get the closest ratio in the buckets.

Args:
    height (float): video height
    width (float): video width
    ratios (list): video aspect ratio
    buckets (list): buckets generated by `generate_crop_size_list`

Returns:
    the closest size in the buckets and the corresponding ratio*
- `generate_crop_size_list` (line 61) `def generate_crop_size_list(base_size, patch_size, max_ratio)`

#### `flash_attn_no_pad.py`
**Path:** `hyvideo/utils/flash_attn_no_pad.py`

**Functions:**
- `flash_attn_no_pad` (line 20) `def flash_attn_no_pad(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`
- `flash_attn_no_pad_v3` (line 52) `def flash_attn_no_pad_v3(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`

#### `infer_utils.py`
**Path:** `hyvideo/utils/infer_utils.py`

**Functions:**
- `torch_compile_wrapper` (line 19) `def torch_compile_wrapper()`
- `decorator` (line 20) `def decorator(func)`
- `wrapper` (line 21) `def wrapper(self)`

#### `multitask_utils.py`
**Path:** `hyvideo/utils/multitask_utils.py`

**Functions:**
- `numpy_to_pil` (line 23) `def numpy_to_pil(images)` - *Convert a numpy image or a batch of images to a PIL image.

Args:
    images (np.ndarray): The image array to convert to PIL format.

Returns:
    List[Image.Image]: A list of PIL images.*
- `merge_tensor_by_mask` (line 45) `def merge_tensor_by_mask(tensor_1, tensor_2, mask, dim)`

#### `clients.py`
**Path:** `hyvideo/utils/rewrite/clients.py`

**Classes:**
- `NonStreamResponse` (line 29) `class NonStreamResponse(object)`
- `DeepSeekClient` (line 37) `class DeepSeekClient(object)`
- `QwenClient` (line 84) `class QwenClient(object)`
- `QwenVLClient` (line 133) `class QwenVLClient(object)`

**Functions:**
- `__init__` (line 30) `def __init__(self)`
- `_deserialize` (line 33) `def _deserialize(self, obj)`
- `__init__` (line 38) `def __init__(self, key_id, key_secret)`
- `run_single_recaption` (line 51) `def run_single_recaption(self, system_prompt, input_prompt)`
- `__init__` (line 85) `def __init__(self, base_url, model_name)`
- `qwen_api_call` (line 90) `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens)` - *Use Qwen Chat API to perform text rewriting, parse <think>...</think> sections for reasoning content, and return (thinking, result).*
- `run_single_recaption` (line 128) `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens)`
- `__init__` (line 135) `def __init__(self, base_url, model_name)`
- `_encode_image_to_base64` (line 141) `def _encode_image_to_base64(self, image_path, max_dimension)` - *参考 hyvideo/utils/rewrite/qwen_vllm.py 的实现：
加载本地图片，将其按比例缩放到 max_dimension，然后编码为 Base64 data URL。*
- `qwen_api_call` (line 176) `def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens, img_path)` - *Use Qwen3-VL to perform text rewriting.*
- `run_single_recaption` (line 246) `def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens, img_path)`

#### `i2v_prompt.py`
**Path:** `hyvideo/utils/rewrite/i2v_prompt.py`

*No symbols extracted*

#### `rewrite_utils.py`
**Path:** `hyvideo/utils/rewrite/rewrite_utils.py`

**Functions:**
- `t2v_rewrite` (line 22) `def t2v_rewrite(user_prompt, rewrite_client)`
- `i2v_rewrite` (line 40) `def i2v_rewrite(user_input, img_path, rewrite_client)` - *Use a rewrite client to generate a rewritten prompt for image-to-video.*
- `run_prompt_rewrite` (line 63) `def run_prompt_rewrite(user_prompt, img_path, task_type)`

#### `t2v_prompt.py`
**Path:** `hyvideo/utils/rewrite/t2v_prompt.py`

*No symbols extracted*

#### `train.py`
**Path:** `train.py`

**Classes:**
- `SNRType` (line 91) `class SNRType(str, Enum)`
- `TrainingConfig` (line 124) `class TrainingConfig`
- `LinearInterpolationSchedule` (line 186) `class LinearInterpolationSchedule` - *Simple linear interpolation schedule for flow matching*
- `TimestepSampler` (line 204) `class TimestepSampler`
- `HunyuanVideoTrainer` (line 347) `class HunyuanVideoTrainer`
- `DummyDataset` (line 1108) `class DummyDataset`

**Functions:**
- `str_to_bool` (line 98) `def str_to_bool(value)` - *Convert string to boolean, supporting true/false, 1/0, yes/no.
If value is None (when flag is provided without value), returns True.*
- `save_video` (line 114) `def save_video(video, path)`
- `timestep_transform` (line 269) `def timestep_transform(timesteps, T, shift)` - *Transform timesteps with shift*
- `is_src` (line 278) `def is_src(src, group_src, group)`
- `broadcast_object` (line 287) `def broadcast_object(obj, src, group, device, group_src)`
- `broadcast_tensor` (line 305) `def broadcast_tensor(tensor, src, group, async_op, group_src)` - *shape and dtype safe broadcast of tensor*
- `sync_tensor_for_sp` (line 333) `def sync_tensor_for_sp(tensor, sp_group)` - *Sync tensor within sequence parallel group.
Ensures all ranks in the SP group have the same tensor values.*
- `create_dummy_dataloader` (line 1047) `def create_dummy_dataloader(config)` - *Create a dummy dataloader for testing.

Note: This is a placeholder - users should implement their own dataset and dataloader
that loads actual video/image data.

Required fields for Dataset __getitem__:
- "pixel_values": torch.Tensor
    * For video: shape [C, F, H, W] where F is the number of frames
    * For image: shape [C, H, W]
    * Pixel values must be in range [-1, 1]
    * Data type: torch.float32
    * Note: For video data, temporal dimension F must be 4n+1 (e.g., 1, 5, 9, 13, 17, 21, ...)
      to satisfy VAE requirements. The dataset should ensure this before returning data.

- "text": str
    * Text prompt for this sample

- "data_type": str
    * "video" for video data (supports both t2v and i2v tasks based on i2v_prob)
    * "image" for image data (always uses t2v task)

Optional fields (for performance optimization):
- "latents": torch.Tensor, shape [C_latent, F, H_latent, W_latent]
    * Pre-encoded VAE latents. If provided, pixel_values will be ignored and VAE encoding
      will be skipped, significantly speeding up training.
    * Should be in the same format as VAE encoder output (after scaling_factor applied)
    * Temporal dimension F must still be 4n+1 for video data

Optional fields (for byT5 text encoding):
- "byt5_text_ids": Optional[torch.Tensor], shape [seq_len]
    * Pre-tokenized byT5 token IDs. If provided, will be used directly.
    * If not provided, text will be tokenized on-the-fly.

- "byt5_text_mask": Optional[torch.Tensor], shape [seq_len]
    * Attention mask for byT5 tokens (1 for valid tokens, 0 for padding)
    * Required if byt5_text_ids is provided

Task type selection (automatic based on data_type and config.i2v_prob):
- For "video" data: randomly samples between t2v (text-to-video) and i2v (image-to-video)
  based on config.i2v_prob probability
- For "image" data: always uses t2v task

Example sample format (what dataset __getitem__ should return):
{
    "pixel_values": torch.Tensor([3, 121, 480, 848]),  # Video example
    "text": "A cat playing",
    "data_type": "video",
    "byt5_text_ids": torch.Tensor([256]),  # Optional
    "byt5_text_mask": torch.Tensor([256]),  # Optional
}

Or with pre-encoded latents (faster):
{
    "latents": torch.Tensor([32, 31, 30, 53]),  # Pre-encoded VAE latents
    "text": "A cat playing",
    "data_type": "video",
}*
- `main` (line 1144) `def main()`
- `__init__` (line 188) `def __init__(self, T)`
- `forward` (line 191) `def forward(self, x0, x1, t)` - *Linear interpolation: x_t = (1 - t/T) * x0 + (t/T) * x1
Args:
    x0: starting point (clean latents)
    x1: ending point (noise)
    t: timesteps*
- `__init__` (line 209) `def __init__(self, T, device, snr_type)`
- `_check_interval` (line 219) `def _check_interval(self, eval)`
- `sample` (line 226) `def sample(self, batch_size, device)`
- `__init__` (line 348) `def __init__(self, config)`
- `_set_seed` (line 406) `def _set_seed(self, seed)`
- `_build_models` (line 412) `def _build_models(self)`
- `_apply_lora` (line 464) `def _apply_lora(self)`
- `_apply_fsdp` (line 498) `def _apply_fsdp(self)`
- `_apply_gradient_checkpointing` (line 529) `def _apply_gradient_checkpointing(self)`
- `_build_optimizer` (line 565) `def _build_optimizer(self)`
- `encode_text` (line 592) `def encode_text(self, prompts, data_type)`
- `encode_byt5` (line 608) `def encode_byt5(self, text_ids, attention_mask)`
- `encode_images` (line 615) `def encode_images(self, images)` - *Encode images to vision states (for i2v)*
- `encode_vae` (line 625) `def encode_vae(self, images)`
- `get_condition` (line 641) `def get_condition(self, latents, task_type)`
- `sample_task` (line 654) `def sample_task(self, data_type)` - *Sample task type based on data type and configuration.

For video data: samples between t2v and i2v based on i2v_prob
For image data: always returns t2v (image-to-video generation)*
- `prepare_batch` (line 671) `def prepare_batch(self, batch)` - *Prepare batch for training.

Expected batch format:
{
    "pixel_values": torch.Tensor, # [B, C, F, H, W] for video or [B, C, H, W] for image
                                  # Pixel values must be in range [-1, 1] 
    "text": List[str],
    "data_type": str,  # "image" or "video"
    "byt5_text_ids": Optional[torch.Tensor],
    "byt5_text_mask": Optional[torch.Tensor],
}

Note: For video data, the temporal dimension F must be 4n+1 (e.g., 1, 5, 9, 13, 17, ...)
to satisfy VAE requirements. The dataset should ensure this before returning data.*
- `train_step` (line 776) `def train_step(self, batch)`
- `save_checkpoint` (line 828) `def save_checkpoint(self, step)`
- `load_pretrained_lora` (line 892) `def load_pretrained_lora(self, lora_dir)`
- `load_checkpoint` (line 901) `def load_checkpoint(self, checkpoint_path)`
- `train` (line 959) `def train(self, dataloader)`
- `validate` (line 1001) `def validate(self, step)` - *Implement your own validation logic here
An example:


logger.info(f"Running validation at step {step}...")

self.transformer.eval()

try:
    for idx, prompt in enumerate(self.config.validation_prompts):
        logger.info(f"Generating validation video {idx+1}/{len(self.config.validation_prompts)}: {prompt[:50]}...")
        
        with torch.no_grad():
            output = self.pipeline(
                prompt=prompt,
                aspect_ratio="16:9",
                video_length=self.config.validate_video_length,
                enable_sr=False,  # Disable SR for faster validation
                prompt_rewrite=False,  # Disable prompt rewrite for faster validation
                output_type="pt",
                seed=42,
            )
            
            video_path = os.path.join(
                self.validation_output_dir,
                f"step_{step:06d}_prompt_{idx:02d}.mp4"
            )
            print(f"Prompt: {prompt}")
            video_to_save = output.videos
            if dist.get_rank() == 0:
                save_video(video_to_save, video_path)
                logger.info(f"Validation video saved to {video_path}")

except Exception as e:
    logger.error(f"Error during validation: {e}")
    import traceback
    logger.error(traceback.format_exc())

finally:
    self.transformer.train()
pass*
- `non_reentrant_wrapper` (line 547) `def non_reentrant_wrapper(module)`
- `selective_checkpointing` (line 553) `def selective_checkpointing(submodule)`
- `__init__` (line 1109) `def __init__(self, size)`
- `__len__` (line 1112) `def __len__(self)`
- `__getitem__` (line 1115) `def __getitem__(self, idx)`
