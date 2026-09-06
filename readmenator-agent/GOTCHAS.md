# Gotchas

## God Nodes (high connectivity)

These files have the most connections. Changes here have high blast radius.

- `hyvideo/pipelines/hunyuan_video_pipeline.py` (score: 40.30)
- `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py` (score: 30.20)
- `hyvideo/commons/__init__.py` (score: 17.20)
- `hyvideo/pipelines/hunyuan_video_sr_pipeline.py` (score: 17.00)
- `hyvideo/models/transformers/modules/token_refiner.py` (score: 14.90)
- `hyvideo/commons/parallel_states.py` (score: 14.80)
- `hyvideo/models/transformers/modules/attention.py` (score: 14.60)
- `train.py` (score: 10.50)
- `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py` (score: 10.20)
- `hyvideo/models/transformers/modules/mlp_layers.py` (score: 9.20)

## Hotspots (complexity + centrality)

- `hyvideo/pipelines/hunyuan_video_pipeline.py` -- complexity: 0.7, centrality: 1.0, combined: 0.9
- `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py` -- complexity: 1.0, centrality: 0.3, combined: 0.6
- `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py` -- complexity: 0.4, centrality: 0.7, combined: 0.6
- `train.py` -- complexity: 0.7, centrality: 0.4, combined: 0.5
- `hyvideo/pipelines/hunyuan_video_sr_pipeline.py` -- complexity: 0.2, centrality: 0.5, combined: 0.3
- `hyvideo/commons/__init__.py` -- complexity: 0.2, centrality: 0.4, combined: 0.3
- `generate.py` -- complexity: 0.1, centrality: 0.3, combined: 0.2
- `hyvideo/models/transformers/modules/attention.py` -- complexity: 0.1, centrality: 0.3, combined: 0.2
- `hyvideo/utils/rewrite/clients.py` -- complexity: 0.2, centrality: 0.2, combined: 0.2
- `hyvideo/models/transformers/modules/token_refiner.py` -- complexity: 0.1, centrality: 0.3, combined: 0.2

## Dependency Cycles

Circular dependencies. Refactor to break the cycle.

- `hyvideo/pipelines/hunyuan_video_pipeline.py` -> `hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
