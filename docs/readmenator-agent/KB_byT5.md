# Subsystem: byT5

## hyvideo/models/text_encoders/byT5/__init__.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `load_glyph_byT5_v2` (function, line 23) `def load_glyph_byT5_v2(args, device)`
  - `create_byt5` (function, line 43) `def create_byt5(args, device)`
  - `add_special_token` (function, line 89) `def add_special_token(tokenizer, text_encoder, add_color, add_font, color_ann_path, font_ann_path, multilingual)`
  - `load_byt5_and_byt5_tokenizer` (function, line 131) `def load_byt5_and_byt5_tokenizer(byt5_name, special_token, color_special_token, font_special_token, color_ann_path, font_ann_path, huggingface_cache_dir, multilingual, device)`
  - `ByT5Mapper` (class, line 187) `class ByT5Mapper(Module)`
  - `__init__` (method, line 199) `def __init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)`
  - `forward` (method, line 210) `def forward(self, x)`
- Imported by: `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`, `hyvideo/pipelines/hunyuan_video_pipeline.py`

## hyvideo/models/text_encoders/byT5/format_prompt.py
- Layer: business_logic
- Doc: Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in comp
- Language: py
- Symbols:
  - `closest_color` (function, line 20) `def closest_color(requested_color)`
  - `convert_rgb_to_names` (function, line 34) `def convert_rgb_to_names(rgb_tuple)`
  - `MultilingualPromptFormat` (class, line 44) `class MultilingualPromptFormat`
  - `__init__` (method, line 46) `def __init__(self, font_path, color_path)`
  - `format_prompt` (method, line 56) `def format_prompt(self, texts, styles)`
- Imported by: `hyvideo/pipelines/hunyuan_video_pipeline.py`
