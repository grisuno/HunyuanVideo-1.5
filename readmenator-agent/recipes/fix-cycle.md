# Recipe: Fix a Dependency Cycle

Target cycle: `hyvideo/pipelines/hunyuan_video_pipeline.py` -> `hyvideo/pipelines/hunyuan_video_sr_pipeline.py` -> `hyvideo/pipelines/hunyuan_video_pipeline.py`

1. Read the imports between these files: `grep -n '^import\|^from\|#include' hyvideo/pipelines/hunyuan_video_pipeline.py`, `grep -n '^import\|^from\|#include' hyvideo/pipelines/hunyuan_video_sr_pipeline.py`
2. Move the shared symbols into a new leaf module both sides import
3. Verify: `readmenator . && grep -c 'Dependency Cycles' readmenator-agent/GOTCHAS.md`
