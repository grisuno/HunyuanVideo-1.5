# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM, Ruby, Swift, Kotlin, Scala, Lua, Elixir.
> No LLMs. No tokens. Pure static analysis. See more [here](https://github.com/grisuno/ReadMenator)

**Total Files Parsed:** 38 | **Total Symbols Extracted:** 409 | **Total Imports:** 293
 | **Resolved Imports:** 64

<!-- ranking_model: v1.0 | weights: {ppr:0.45,auth:0.2,test:0.15,doc:0.1,fresh:0.1} | alpha:0.85 | commit:75d209c | date:2026-07-18 -->


## Table of Contents

1. [Statistics Dashboard](#statistics-dashboard)
2. [Architectural Layers](#architectural-layers)
3. [Ranked Context](#ranked-context)
4. [God Nodes](#god-nodes)
5. [Community Analysis](#community-analysis)
6. [Surprising Connections](#surprising-connections)
7. [Suggested Questions](#suggested-questions)
8. [Hotspot Analysis](#hotspot-analysis)
9. [Dependency Cycles](#dependency-cycles)
10. [Change Impact Analysis](#change-impact-analysis)
11. [Suggested Linting Rules](#suggested-linting-rules)
12. [Query Recipes](#query-recipes)
13. [Structural Knowledge Map](#structural-knowledge-map)
14. [UML Class Diagram](#uml-class-diagram)
15. [Code Property Graph](#code-property-graph)
16. [Architecture Reference](#architecture-reference)
    - [PY (38 files)](#py-38-files)

---

## Statistics Dashboard

| Metric | Value |
|--------|-------|
| Total Files | 38 |
| Total Symbols | 409 |
| Total Imports | 293 |
| Call Edges | 2720 |
| Inheritance Edges | 60 |
| Languages | 1 |
| Avg Symbols/File | 10.8 |
| Avg Imports/File | 7.7 |
| Resolved Imports | 64 |

### Top Files by Import Count (Fan-Out)

| File | Imports | Symbols | Language |
|------|---------|---------|----------|
| `hunyuan_video_pipeline.py` | 38 | 43 | py |
| `hunyuanvideo_1_5_transformer.py` | 28 | 22 | py |
| `train.py` | 22 | 45 | py |
| `hunyuan_video_sr_pipeline.py` | 18 | 10 | py |
| `hunyuanvideo_15_vae.py` | 17 | 62 | py |
| `generate.py` | 16 | 8 | py |
| `__init__.py` | 14 | 12 | py |
| `attention.py` | 13 | 6 | py |
| `clients.py` | 13 | 15 | py |
| `upsample.py` | 11 | 11 | py |

---

## Architectural Layers

Auto-detected from path patterns, naming conventions, and imported frameworks.

| Layer | Files |
|-------|-------|
| business_logic | 18 |
| utility | 17 |
| infrastructure | 2 |
| data_access | 1 |

### utility

- `generate.py` (py, 8 symbols)
- `__init__.py` (py, 2 symbols)
- `__init__.py` (py, 12 symbols)
- `infer_state.py` (py, 4 symbols)
- `parallel_states.py` (py, 8 symbols)
- `muon.py` (py, 6 symbols)
- `hunyuan_video_pipeline.py` (py, 43 symbols)
- `hunyuan_video_sr_pipeline.py` (py, 10 symbols)
- `pipeline_utils.py` (py, 2 symbols)
- `communications.py` (py, 18 symbols)
- `flash_attn_no_pad.py` (py, 2 symbols)
- `infer_utils.py` (py, 3 symbols)
- `multitask_utils.py` (py, 2 symbols)
- `i2v_prompt.py` (py, 0 symbols)
- `rewrite_utils.py` (py, 3 symbols)
- *... and 2 more*

### business_logic

- `__init__.py` (py, 0 symbols)
- `__init__.py` (py, 0 symbols)
- `hunyuanvideo_15_vae.py` (py, 62 symbols)
- `__init__.py` (py, 14 symbols)
- `__init__.py` (py, 7 symbols)
- `format_prompt.py` (py, 5 symbols)
- `hunyuanvideo_1_5_transformer.py` (py, 22 symbols)
- `activation_layers.py` (py, 1 symbols)
- `attention.py` (py, 6 symbols)
- `embed_layers.py` (py, 16 symbols)
- `mlp_layers.py` (py, 12 symbols)
- `modulate_layers.py` (py, 7 symbols)
- `norm_layers.py` (py, 6 symbols)
- `posemb_layers.py` (py, 7 symbols)
- `ssta_attention.py` (py, 11 symbols)
- *... and 3 more*

### infrastructure

- `scheduling_flow_match_discrete.py` (py, 16 symbols)
- `clients.py` (py, 15 symbols)

### data_access

- `data_utils.py` (py, 3 symbols)

---

## Ranked Context

Files ranked by composite score for the current query context. The ranking combines Personalized PageRank (query relevance), global authority, test coverage, documentation coverage, and code freshness. Model: v1.0.

| Rank | File | Composite | PPR | Authority | Test | Doc |
|------|------|-----------|-----|-----------|------|-----|
| 1 | `activation_layers.py` | 0.2159 | 0.0245 | 0.0245 | 0.00 | 2.00 |
| 2 | `pipeline_utils.py` | 0.1665 | 0.0254 | 0.0254 | 0.00 | 1.50 |
| 3 | `i2v_prompt.py` | 0.1168 | 0.0258 | 0.0258 | 0.00 | 1.00 |
| 4 | `t2v_prompt.py` | 0.1168 | 0.0258 | 0.0258 | 0.00 | 1.00 |
| 5 | `ssta_attention.py` | 0.1156 | 0.0239 | 0.0239 | 0.00 | 1.00 |
| 6 | `multitask_utils.py` | 0.1139 | 0.0214 | 0.0214 | 0.00 | 1.00 |
| 7 | `posemb_layers.py` | 0.0997 | 0.0215 | 0.0215 | 0.00 | 0.86 |
| 8 | `norm_layers.py` | 0.0993 | 0.0245 | 0.0245 | 0.00 | 0.83 |
| 9 | `token_refiner.py` | 0.0917 | 0.0215 | 0.0215 | 0.00 | 0.78 |
| 10 | `data_utils.py` | 0.0821 | 0.0237 | 0.0237 | 0.00 | 0.67 |

---

## God Nodes

Most architecturally central files ranked by combined import/export degree and symbol richness.

| File | Score | Connections | PageRank |
|------|-------|-------------|----------|
| `hunyuan_video_pipeline.py` | 40.3 | | 0.0000 |
| `hunyuanvideo_1_5_transformer.py` | 30.2 | | 0.0000 |
| `__init__.py` | 17.2 | | 0.0000 |
| `hunyuan_video_sr_pipeline.py` | 17.0 | | 0.0000 |
| `token_refiner.py` | 14.9 | | 0.0215 |
| `parallel_states.py` | 14.8 | | 0.0000 |
| `attention.py` | 14.6 | | 0.0000 |
| `train.py` | 10.5 | | 0.0000 |
| `hunyuanvideo_15_vae.py` | 10.2 | | 0.0000 |
| `mlp_layers.py` | 9.2 | | 0.0000 |

---

## Community Analysis

Files grouped by import-based community detection. Cohesion measures how tightly connected each community is internally.

### hyvideo/pipelines (Cohesion: 0.46)

**11 files** in this community:

- `generate.py` (py, 8 symbols)
- `infer_state.py` (py, 4 symbols)
- `__init__.py` (py, 0 symbols)
- `__init__.py` (py, 14 symbols)
- `format_prompt.py` (py, 5 symbols)
- `__init__.py` (py, 11 symbols)
- `hunyuan_video_pipeline.py` (py, 43 symbols)
- `pipeline_utils.py` (py, 2 symbols)
- `scheduling_flow_match_discrete.py` (py, 16 symbols)
- `data_utils.py` (py, 3 symbols)
- `multitask_utils.py` (py, 2 symbols)

### hyvideo/models/transformers/modules (Cohesion: 0.74)

**21 files** in this community:

- `__init__.py` (py, 2 symbols)
- `__init__.py` (py, 12 symbols)
- `parallel_states.py` (py, 8 symbols)
- `hunyuanvideo_15_vae.py` (py, 62 symbols)
- `__init__.py` (py, 7 symbols)
- `hunyuanvideo_1_5_transformer.py` (py, 22 symbols)
- `activation_layers.py` (py, 1 symbols)
- `attention.py` (py, 6 symbols)
- `embed_layers.py` (py, 16 symbols)
- `mlp_layers.py` (py, 12 symbols)
- `modulate_layers.py` (py, 7 symbols)
- `norm_layers.py` (py, 6 symbols)
- `posemb_layers.py` (py, 7 symbols)
- `ssta_attention.py` (py, 11 symbols)
- `token_refiner.py` (py, 9 symbols)
- `upsample.py` (py, 11 symbols)
- `muon.py` (py, 6 symbols)
- `hunyuan_video_sr_pipeline.py` (py, 10 symbols)
- `communications.py` (py, 18 symbols)
- `flash_attn_no_pad.py` (py, 2 symbols)
- ... and 1 more files

### hyvideo/utils/rewrite (Cohesion: 0.75)

**4 files** in this community:

- `clients.py` (py, 15 symbols)
- `i2v_prompt.py` (py, 0 symbols)
- `rewrite_utils.py` (py, 3 symbols)
- `t2v_prompt.py` (py, 0 symbols)

---

## Surprising Connections

Files in different communities connected through 3+ indirect hops.

- `ssta_attention.py` <-> `clients.py` (5 hops, across 3 communities)
- `ssta_attention.py` <-> `i2v_prompt.py` (5 hops, across 3 communities)
- `ssta_attention.py` <-> `t2v_prompt.py` (5 hops, across 3 communities)
- `flash_attn_no_pad.py` <-> `clients.py` (5 hops, across 3 communities)
- `flash_attn_no_pad.py` <-> `i2v_prompt.py` (5 hops, across 3 communities)

---

## Suggested Questions

Auto-generated exploration prompts based on graph structure:

- What does hunyuan_video_pipeline.py depend on, and what depends on it? (18 connections)
- What does hunyuanvideo_1_5_transformer.py depend on, and what depends on it? (14 connections)
- What does __init__.py depend on, and what depends on it? (8 connections)
- How are the 11 files in 'hyvideo/pipelines' related to each other?
- Why are ssta_attention.py and clients.py connected through 5 hops across 3 communities?

---

## Hotspot Analysis

Files ranked by combined complexity (symbol count) and centrality (connection count). High-scoring files are architecturally critical and may need refactoring attention.

| File | Complexity | Centrality | Combined | Symbols | Connections |
|------|-----------|------------|----------|---------|-------------|
| `activation_layers.py` | 0.016 | 0.052 | 0.037 | 1 | 3 |
| `pipeline_utils.py` | 0.032 | 0.103 | 0.075 | 2 | 6 |
| `i2v_prompt.py` | 0.000 | 0.017 | 0.010 | 0 | 1 |
| `t2v_prompt.py` | 0.000 | 0.017 | 0.010 | 0 | 1 |
| `ssta_attention.py` | 0.177 | 0.121 | 0.143 | 11 | 7 |
| `multitask_utils.py` | 0.032 | 0.086 | 0.065 | 2 | 5 |
| `posemb_layers.py` | 0.113 | 0.069 | 0.086 | 7 | 4 |
| `norm_layers.py` | 0.097 | 0.069 | 0.080 | 6 | 4 |
| `token_refiner.py` | 0.145 | 0.293 | 0.234 | 9 | 17 |
| `data_utils.py` | 0.048 | 0.069 | 0.061 | 3 | 4 |
| `hunyuan_video_pipeline.py` | 0.694 | 1.000 | 0.877 | 43 | 58 |
| `hunyuanvideo_15_vae.py` | 1.000 | 0.328 | 0.597 | 62 | 19 |
| `hunyuanvideo_1_5_transformer.py` | 0.355 | 0.724 | 0.576 | 22 | 42 |
| `train.py` | 0.726 | 0.431 | 0.549 | 45 | 25 |
| `hunyuan_video_sr_pipeline.py` | 0.161 | 0.466 | 0.344 | 10 | 27 |

---

## Dependency Cycles

Circular dependencies detected in the resolved import graph. Cycles increase coupling and make refactoring harder.

| Cycle | Length | Files |
|-------|--------|-------|
| `hunyuan_video_pipeline.py -> hunyuan_video_sr_pipeline.py` | 2 | 2 |

---

## Change Impact Analysis

Files sorted by how many other files would be affected if they changed. High-impact files should be changed with caution.

| File | Direct Dependents | Transitive Dependents | Total Impact |
|------|------------------|----------------------|--------------|
| `__init__.py` | 8 | 3 | 11 |
| `parallel_states.py` | 7 | 2 | 9 |
| `modulate_layers.py` | 3 | 4 | 7 |
| `ssta_attention.py` | 1 | 6 | 7 |
| `communications.py` | 2 | 5 | 7 |
| `flash_attn_no_pad.py` | 1 | 6 | 7 |
| `activation_layers.py` | 2 | 4 | 6 |
| `attention.py` | 2 | 4 | 6 |
| `embed_layers.py` | 2 | 4 | 6 |
| `mlp_layers.py` | 2 | 4 | 6 |
| `norm_layers.py` | 2 | 4 | 6 |
| `hunyuanvideo_15_vae.py` | 1 | 4 | 5 |
| `__init__.py` | 2 | 3 | 5 |
| `posemb_layers.py` | 1 | 4 | 5 |
| `token_refiner.py` | 1 | 4 | 5 |

---

## Suggested Linting Rules

Automatically suggested linting and security rules based on patterns detected in the codebase. These can be exported as Semgrep rules using the `--export-rules` flag.

| Rule ID | Severity | Description | Language | Matches |
|---------|----------|-------------|----------|---------|
| `RM001` | info | Large number of functions in py: 346 total | py | 346 |
| `RM002` | info | Print statement found (consider logging instead) | python | 9 |

---

## Query Recipes

Example queries you can run against this knowledge base using the ranking engine:

```
# Find files most relevant to a concept
readmenator query "Where is the import resolver implemented?"

# Rank files by relevance to a topic
readmenator query "How does documentation generation work?"

# Explain why a file ranks highly
readmenator query "explain readmenator/_documentation.py"

# Trace dependency paths with ranked context
readmenator query "path from CLI to exporter"
```

The ranking model uses the following signals:

- **Personalized PageRank** (45% weight): query-specific relevance via seed propagation
- **Global Authority** (20% weight): structural importance via standard PageRank
- **Test Coverage** (15% weight): fraction of symbols referenced in test files
- **Doc Coverage** (10% weight): presence of docstrings and file-level docs
- **Freshness** (10% weight): recent modification activity

Results include score decomposition and justification paths for each ranked item.

---

## Structural Knowledge Map

```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray:5 5,color:#aaa;
    subgraph community_0 ["hyvideo/pipelines"]
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
    end
    subgraph community_1 ["hyvideo/models/transformers/modules"]
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py["hunyuanvideo_1_5_transformer.py (py)"]
    class hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py mod;
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py["hunyuan_video_sr_pipeline.py (py)"]
    class hyvideo_pipelines_hunyuan_video_sr_pipeline_py mod;
    train_py["train.py (py)"]
    class train_py mod;
    generate_py["generate.py (py)"]
    class generate_py mod;
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py["hunyuanvideo_15_vae.py (py)"]
    class hyvideo_models_autoencoders_hunyuanvideo_15_vae_py mod;
    hyvideo_models_transformers_modules_attention_py["attention.py (py)"]
    class hyvideo_models_transformers_modules_attention_py mod;
    hyvideo_models_transformers_modules_token_refiner_py["token_refiner.py (py)"]
    class hyvideo_models_transformers_modules_token_refiner_py mod;
    hyvideo_commons___init___py["__init__.py (py)"]
    class hyvideo_commons___init___py mod;
    end
    subgraph community_2 ["hyvideo/utils/rewrite"]
    hyvideo_utils_rewrite_clients_py["clients.py (py)"]
    class hyvideo_utils_rewrite_clients_py mod;
    hyvideo_models_transformers_modules_upsample_py["upsample.py (py)"]
    class hyvideo_models_transformers_modules_upsample_py mod;
    hyvideo_models_vision_encoder___init___py["__init__.py (py)"]
    class hyvideo_models_vision_encoder___init___py mod;
    hyvideo_schedulers_scheduling_flow_match_discrete_py["scheduling_flow_match_discrete.py (py)"]
    class hyvideo_schedulers_scheduling_flow_match_discrete_py mod;
    hyvideo_models_text_encoders___init___py["__init__.py (py)"]
    class hyvideo_models_text_encoders___init___py mod;
    hyvideo_models_transformers_modules_mlp_layers_py["mlp_layers.py (py)"]
    class hyvideo_models_transformers_modules_mlp_layers_py mod;
    hyvideo_utils_rewrite_rewrite_utils_py["rewrite_utils.py (py)"]
    class hyvideo_utils_rewrite_rewrite_utils_py mod;
    hyvideo_models_transformers_modules_ssta_attention_py["ssta_attention.py (py)"]
    class hyvideo_models_transformers_modules_ssta_attention_py mod;
    hyvideo_utils_flash_attn_no_pad_py["flash_attn_no_pad.py (py)"]
    class hyvideo_utils_flash_attn_no_pad_py mod;
    hyvideo_models_transformers_modules_embed_layers_py["embed_layers.py (py)"]
    class hyvideo_models_transformers_modules_embed_layers_py mod;
    hyvideo_utils_communications_py["communications.py (py)"]
    class hyvideo_utils_communications_py mod;
    hyvideo_commons_parallel_states_py["parallel_states.py (py)"]
    class hyvideo_commons_parallel_states_py mod;
    hyvideo_models_text_encoders_byT5___init___py["__init__.py (py)"]
    class hyvideo_models_text_encoders_byT5___init___py mod;
    hyvideo_optim_muon_py["muon.py (py)"]
    class hyvideo_optim_muon_py mod;
    hyvideo_models_text_encoders_byT5_format_prompt_py["format_prompt.py (py)"]
    class hyvideo_models_text_encoders_byT5_format_prompt_py mod;
    hyvideo___init___py["__init__.py (py)"]
    class hyvideo___init___py mod;
    hyvideo_utils_multitask_utils_py["multitask_utils.py (py)"]
    class hyvideo_utils_multitask_utils_py mod;
    hyvideo_models_transformers_modules_modulate_layers_py["modulate_layers.py (py)"]
    class hyvideo_models_transformers_modules_modulate_layers_py mod;
    hyvideo_models_transformers_modules_posemb_layers_py["posemb_layers.py (py)"]
    class hyvideo_models_transformers_modules_posemb_layers_py mod;
    hyvideo_pipelines_pipeline_utils_py["pipeline_utils.py (py)"]
    class hyvideo_pipelines_pipeline_utils_py mod;
    hyvideo_models_transformers_modules_norm_layers_py["norm_layers.py (py)"]
    class hyvideo_models_transformers_modules_norm_layers_py mod;
    hyvideo_commons_infer_state_py["infer_state.py (py)"]
    class hyvideo_commons_infer_state_py mod;
    hyvideo_utils_data_utils_py["data_utils.py (py)"]
    class hyvideo_utils_data_utils_py mod;
    hyvideo_utils_infer_utils_py["infer_utils.py (py)"]
    class hyvideo_utils_infer_utils_py mod;
    hyvideo_models_transformers_modules_activation_layers_py["activation_layers.py (py)"]
    class hyvideo_models_transformers_modules_activation_layers_py mod;
    hyvideo_models___init___py["__init__.py (py)"]
    class hyvideo_models___init___py mod;
    hyvideo_models_autoencoders___init___py["__init__.py (py)"]
    class hyvideo_models_autoencoders___init___py mod;
    hyvideo_utils_rewrite_i2v_prompt_py["i2v_prompt.py (py)"]
    class hyvideo_utils_rewrite_i2v_prompt_py mod;
    hyvideo_utils_rewrite_t2v_prompt_py["t2v_prompt.py (py)"]
    class hyvideo_utils_rewrite_t2v_prompt_py mod;
    end
    generate_py -- resolved_imports --> hyvideo_pipelines_hunyuan_video_pipeline_py
    generate_py -- resolved_imports --> hyvideo_commons_parallel_states_py
    generate_py -- resolved_imports --> hyvideo_commons_infer_state_py
    hyvideo___init___py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_models_autoencoders_hunyuanvideo_15_vae_py -- resolved_imports --> hyvideo_commons_parallel_states_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_activation_layers_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_norm_layers_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_embed_layers_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_attention_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_posemb_layers_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_mlp_layers_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_modulate_layers_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_transformers_modules_token_refiner_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_utils_communications_py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_models_text_encoders_byT5___init___py
    hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py -- resolved_imports --> hyvideo_commons_parallel_states_py
    hyvideo_models_transformers_modules_attention_py -- resolved_imports --> hyvideo_commons_parallel_states_py
    hyvideo_models_transformers_modules_attention_py -- resolved_imports --> hyvideo_utils_communications_py
    hyvideo_models_transformers_modules_attention_py -- resolved_imports --> hyvideo_utils_flash_attn_no_pad_py
    hyvideo_models_transformers_modules_attention_py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_models_transformers_modules_attention_py -- resolved_imports --> hyvideo_models_transformers_modules_ssta_attention_py
    hyvideo_models_transformers_modules_embed_layers_py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_models_transformers_modules_mlp_layers_py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_models_transformers_modules_mlp_layers_py -- resolved_imports --> hyvideo_models_transformers_modules_modulate_layers_py
    hyvideo_models_transformers_modules_token_refiner_py -- resolved_imports --> hyvideo_models_transformers_modules_activation_layers_py
    hyvideo_models_transformers_modules_token_refiner_py -- resolved_imports --> hyvideo_models_transformers_modules_embed_layers_py
    hyvideo_models_transformers_modules_token_refiner_py -- resolved_imports --> hyvideo_models_transformers_modules_mlp_layers_py
    hyvideo_models_transformers_modules_token_refiner_py -- resolved_imports --> hyvideo_models_transformers_modules_modulate_layers_py
    hyvideo_models_transformers_modules_token_refiner_py -- resolved_imports --> hyvideo_models_transformers_modules_norm_layers_py
    hyvideo_models_transformers_modules_token_refiner_py -- resolved_imports --> hyvideo_models_transformers_modules_attention_py
    hyvideo_models_transformers_modules_upsample_py -- resolved_imports --> hyvideo_models_autoencoders_hunyuanvideo_15_vae_py
    hyvideo_models_vision_encoder___init___py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_pipelines_pipeline_utils_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_commons_parallel_states_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_models_autoencoders___init___py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_models_text_encoders___init___py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_models_text_encoders_byT5___init___py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_models_text_encoders_byT5_format_prompt_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_models_transformers_modules_upsample_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_models_vision_encoder___init___py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_schedulers_scheduling_flow_match_discrete_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_utils_data_utils_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_utils_multitask_utils_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_commons_infer_state_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_pipelines_pipeline_utils_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_pipelines_hunyuan_video_sr_pipeline_py
    hyvideo_pipelines_hunyuan_video_pipeline_py -- resolved_imports --> hyvideo_utils_rewrite_rewrite_utils_py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_commons_parallel_states_py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_commons___init___py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_models_text_encoders___init___py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_models_transformers_hunyuanvideo_1_5_transformer_py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_models_transformers_modules_upsample_py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_utils_data_utils_py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_pipelines_hunyuan_video_pipeline_py
    hyvideo_pipelines_hunyuan_video_sr_pipeline_py -- resolved_imports --> hyvideo_pipelines_pipeline_utils_py
    hyvideo_utils_rewrite_rewrite_utils_py -- resolved_imports --> hyvideo_utils_rewrite_clients_py
    hyvideo_utils_rewrite_rewrite_utils_py -- resolved_imports --> hyvideo_utils_rewrite_t2v_prompt_py
    hyvideo_utils_rewrite_rewrite_utils_py -- resolved_imports --> hyvideo_utils_rewrite_i2v_prompt_py
    train_py -- resolved_imports --> hyvideo_pipelines_hunyuan_video_pipeline_py
    train_py -- resolved_imports --> hyvideo_commons_parallel_states_py
    train_py -- resolved_imports --> hyvideo_optim_muon_py
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
    ext_hyvideo_utils_rewrite_clients["hyvideo.utils.rewrite.clients"]
    class ext_hyvideo_utils_rewrite_clients ext;
    hyvideo_utils_rewrite_rewrite_utils_py -.->|imports| ext_hyvideo_utils_rewrite_clients
    ext_hyvideo_utils_rewrite_t2v_prompt["hyvideo.utils.rewrite.t2v_prompt"]
    class ext_hyvideo_utils_rewrite_t2v_prompt ext;
    hyvideo_utils_rewrite_rewrite_utils_py -.->|imports| ext_hyvideo_utils_rewrite_t2v_prompt
    ext_hyvideo_utils_rewrite_i2v_prompt["hyvideo.utils.rewrite.i2v_prompt"]
    class ext_hyvideo_utils_rewrite_i2v_prompt ext;
    hyvideo_utils_rewrite_rewrite_utils_py -.->|imports| ext_hyvideo_utils_rewrite_i2v_prompt
    train_py -.->|imports| ext_os
    train_py -.->|imports| ext_random
    train_py -.->|imports| ext_math
    train_py -.->|imports| ext_argparse
    train_py -.->|imports| ext_dataclasses
    train_py -.->|imports| ext_typing
    train_py -.->|imports| ext_enum
    train_py -.->|imports| ext_torch
    train_py -.->|imports| ext_torch_distributed
    train_py -.->|imports| ext_torch_nn
    train_py -.->|imports| ext_torch_distributed_checkpoint
    train_py -.->|imports| ext_torch_distributed_checkpoint_state_dict
    ext_diffusers_optimization["diffusers.optimization"]
    class ext_diffusers_optimization ext;
    train_py -.->|imports| ext_diffusers_optimization
    train_py -.->|imports| ext_loguru
    train_py -.->|imports| ext_einops
    train_py -.->|imports| ext_imageio
    train_py -.->|imports| ext_hyvideo_pipelines_hunyuan_video_pipeline
    train_py -.->|imports| ext_hyvideo_commons_parallel_states
    ext_hyvideo_optim_muon["hyvideo.optim.muon"]
    class ext_hyvideo_optim_muon ext;
    train_py -.->|imports| ext_hyvideo_optim_muon
    ext_torch_distributed__composable_fsdp["torch.distributed._composable.fsdp"]
    class ext_torch_distributed__composable_fsdp ext;
    train_py -.->|imports| ext_torch_distributed__composable_fsdp
    ext_torch_distributed_algorithms__checkpoint_checkpoint_wrapper["torch.distributed.algorithms._checkpoint.checkpoint_wrapper"]
    class ext_torch_distributed_algorithms__checkpoint_checkpoint_wrapper ext;
    train_py -.->|imports| ext_torch_distributed_algorithms__checkpoint_checkpoint_wrapper
    ext_peft["peft"]
    class ext_peft ext;
    train_py -.->|imports| ext_peft
```

---

## UML Class Diagram

Auto-generated Mermaid class diagram from parsed class-level symbols. Shows classes, structs, interfaces, traits, and their methods with inheritance and dependency relationships.

```mermaid
classDiagram
  class infer_state_py_InferState {
    <<class>>
    +parse_range(value)
    +initialize_infer_state(args)
    +get_infer_state()
  }
  class parallel_states_py_ParallelDims {
    <<class>>
    +initialize_parallel_state(sp, dp_replicate)
    +get_parallel_state()
    +__post_init__(self)
    +build_mesh(self, device_type)
    +sp_enabled(self)
    +sp_mesh(self)
    +dp_enabled(self)
  }
  class hunyuanvideo_15_vae_py_DecoderOutput {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_PatchCausalConv3d {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_RMS_norm {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_CausalConv3d {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_AttnBlock {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_ResnetBlock {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_Downsample {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_Upsample {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_Encoder {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_Decoder {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class hunyuanvideo_15_vae_py_AutoencoderKLConv3D {
    <<class>>
    +swish(x, inplace)
    +forward_with_checkpointing(module)
    +prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)
    +create_custom_forward(module)
    +find_split_indices(self, seq_len, part_num)
    +forward(self, input)
    +__init__(self, dim, channel_first, images, bias)
    +forward(self, x)
    +__init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)
    +forward(self, x)
  }
  class __init___py_TextEncoderModelOutput {
    <<class>>
    +use_default(value, default)
    +load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)
    +load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)
    +__init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type, tokenizer_path, output_key, use_attention_mask, prompt_template, prompt_template_video, hidden_state_skip_layer, apply_final_norm, reproduce, logger, device)
    +dtype(self)
    +device(self)
    +__repr__(self)
    +apply_text_to_template(text, template, prevent_empty_text)
    +calculate_crop_start(self, tokenized_input)
    +text2tokens(self, text, data_type, max_length)
  }
  class __init___py_TextEncoder {
    <<class>>
    +use_default(value, default)
    +load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)
    +load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)
    +__init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type, tokenizer_path, output_key, use_attention_mask, prompt_template, prompt_template_video, hidden_state_skip_layer, apply_final_norm, reproduce, logger, device)
    +dtype(self)
    +device(self)
    +__repr__(self)
    +apply_text_to_template(text, template, prevent_empty_text)
    +calculate_crop_start(self, tokenized_input)
    +text2tokens(self, text, data_type, max_length)
  }
  class __init___py_ByT5Mapper {
    <<class>>
    +load_glyph_byT5_v2(args, device)
    +create_byt5(args, device)
    +add_special_token(tokenizer, text_encoder, add_color, add_font, color_ann_path, font_ann_path, multilingual)
    +load_byt5_and_byt5_tokenizer(byt5_name, special_token, color_special_token, font_special_token, color_ann_path, font_ann_path, huggingface_cache_dir, multilingual, device)
    +__init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)
    +forward(self, x)
  }
  class format_prompt_py_MultilingualPromptFormat {
    <<class>>
    +closest_color(requested_color)
    +convert_rgb_to_names(rgb_tuple)
    +__init__(self, font_path, color_path)
    +format_prompt(self, texts, styles)
  }
  class hunyuanvideo_1_5_transformer_py_MMDoubleStreamBlock {
    <<class>>
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +enable_deterministic(self)
    +disable_deterministic(self)
    +forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dtype, device)
    +enable_deterministic(self)
    +disable_deterministic(self)
    +forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)
    +__init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, mm_double_blocks_depth, mm_single_blocks_depth, rope_dim_list, qkv_bias, qk_norm, qk_norm_type, guidance_embed, use_meanflow, text_projection, use_attention_mask, text_states_dim, text_states_dim_2, text_pool_type, rope_theta, attn_mode, attn_param, glyph_byT5_v2, vision_projection, vision_states_dim, is_reshape_temporal_channels, use_cond_type_embedding, ideal_resolution, ideal_task)
    +load_hunyuan_state_dict(self, model_path)
  }
  class hunyuanvideo_1_5_transformer_py_MMSingleStreamBlock {
    <<class>>
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +enable_deterministic(self)
    +disable_deterministic(self)
    +forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dtype, device)
    +enable_deterministic(self)
    +disable_deterministic(self)
    +forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)
    +__init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, mm_double_blocks_depth, mm_single_blocks_depth, rope_dim_list, qkv_bias, qk_norm, qk_norm_type, guidance_embed, use_meanflow, text_projection, use_attention_mask, text_states_dim, text_states_dim_2, text_pool_type, rope_theta, attn_mode, attn_param, glyph_byT5_v2, vision_projection, vision_states_dim, is_reshape_temporal_channels, use_cond_type_embedding, ideal_resolution, ideal_task)
    +load_hunyuan_state_dict(self, model_path)
  }
  class hunyuanvideo_1_5_transformer_py_HunyuanVideo_1_5_DiffusionTransformer {
    <<class>>
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +enable_deterministic(self)
    +disable_deterministic(self)
    +forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dtype, device)
    +enable_deterministic(self)
    +disable_deterministic(self)
    +forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)
    +__init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, mm_double_blocks_depth, mm_single_blocks_depth, rope_dim_list, qkv_bias, qk_norm, qk_norm_type, guidance_embed, use_meanflow, text_projection, use_attention_mask, text_states_dim, text_states_dim_2, text_pool_type, rope_theta, attn_mode, attn_param, glyph_byT5_v2, vision_projection, vision_states_dim, is_reshape_temporal_channels, use_cond_type_embedding, ideal_resolution, ideal_task)
    +load_hunyuan_state_dict(self, model_path)
  }
  class embed_layers_py_PatchEmbed {
    <<class>>
    +timestep_embedding(t, dim, max_period)
    +__init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)
    +forward(self, x)
    +__init__(self, in_channels, hidden_size, act_layer, dtype, device)
    +forward(self, caption)
    +__init__(self, input_dim, output_dim)
    +forward(self, vision_embeds)
    +__init__(self, in_channels, out_channels)
    +forward(self, x)
    +__init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)
  }
  class embed_layers_py_TextProjection {
    <<class>>
    +timestep_embedding(t, dim, max_period)
    +__init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)
    +forward(self, x)
    +__init__(self, in_channels, hidden_size, act_layer, dtype, device)
    +forward(self, caption)
    +__init__(self, input_dim, output_dim)
    +forward(self, vision_embeds)
    +__init__(self, in_channels, out_channels)
    +forward(self, x)
    +__init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)
  }
  class embed_layers_py_VisionProjection {
    <<class>>
    +timestep_embedding(t, dim, max_period)
    +__init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)
    +forward(self, x)
    +__init__(self, in_channels, hidden_size, act_layer, dtype, device)
    +forward(self, caption)
    +__init__(self, input_dim, output_dim)
    +forward(self, vision_embeds)
    +__init__(self, in_channels, out_channels)
    +forward(self, x)
    +__init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)
  }
  class embed_layers_py_ClipVisionProjection {
    <<class>>
    +timestep_embedding(t, dim, max_period)
    +__init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)
    +forward(self, x)
    +__init__(self, in_channels, hidden_size, act_layer, dtype, device)
    +forward(self, caption)
    +__init__(self, input_dim, output_dim)
    +forward(self, vision_embeds)
    +__init__(self, in_channels, out_channels)
    +forward(self, x)
    +__init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)
  }
  class embed_layers_py_TimestepEmbedder {
    <<class>>
    +timestep_embedding(t, dim, max_period)
    +__init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)
    +forward(self, x)
    +__init__(self, in_channels, hidden_size, act_layer, dtype, device)
    +forward(self, caption)
    +__init__(self, input_dim, output_dim)
    +forward(self, vision_embeds)
    +__init__(self, in_channels, out_channels)
    +forward(self, x)
    +__init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)
  }
  class mlp_layers_py_MLP {
    <<class>>
    +__init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)
    +forward(self, x)
    +__init__(self, in_dim, out_dim, bias, device, dtype)
    +forward(self, x, y)
    +__init__(self, in_dim, hidden_dim, device, dtype)
    +forward(self, x)
    +__init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)
    +forward(self, x, c)
  }
  class mlp_layers_py_LinearWarpforSingle {
    <<class>>
    +__init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)
    +forward(self, x)
    +__init__(self, in_dim, out_dim, bias, device, dtype)
    +forward(self, x, y)
    +__init__(self, in_dim, hidden_dim, device, dtype)
    +forward(self, x)
    +__init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)
    +forward(self, x, c)
  }
  class mlp_layers_py_MLPEmbedder {
    <<class>>
    +__init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)
    +forward(self, x)
    +__init__(self, in_dim, out_dim, bias, device, dtype)
    +forward(self, x, y)
    +__init__(self, in_dim, hidden_dim, device, dtype)
    +forward(self, x)
    +__init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)
    +forward(self, x, c)
  }
  class mlp_layers_py_FinalLayer {
    <<class>>
    +__init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)
    +forward(self, x)
    +__init__(self, in_dim, out_dim, bias, device, dtype)
    +forward(self, x, y)
    +__init__(self, in_dim, hidden_dim, device, dtype)
    +forward(self, x)
    +__init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)
    +forward(self, x, c)
  }
  class modulate_layers_py_ModulateDiT {
    <<class>>
    +modulate(x, shift, scale)
    +apply_gate(x, gate, tanh)
    +ckpt_wrapper(module)
    +__init__(self, hidden_size, factor, act_layer, dtype, device)
    +forward(self, x)
    +ckpt_forward()
  }
  class norm_layers_py_RMSNorm {
    <<class>>
    +get_norm_layer(norm_layer)
    +__init__(self, dim, elementwise_affine, eps, device, dtype)
    +_norm(self, x)
    +reset_parameters(self)
    +forward(self, x)
  }
  class token_refiner_py_IndividualTokenRefinerBlock {
    <<class>>
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, c, attn_mask)
    +__init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, c, mask)
    +__init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, t, mask)
  }
  class token_refiner_py_IndividualTokenRefiner {
    <<class>>
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, c, attn_mask)
    +__init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, c, mask)
    +__init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, t, mask)
  }
  class token_refiner_py_SingleTokenRefiner {
    <<class>>
    +__init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, c, attn_mask)
    +__init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, c, mask)
    +__init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)
    +forward(self, x, t, mask)
  }
  class upsample_py_UpsamplerType {
    <<class>>
    +__init__(self, channels)
    +forward(self, x)
    +__init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)
    +forward(self, x)
    +__init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)
    +forward(self, z, target_shape)
  }
  class upsample_py_UpsamplerConfig {
    <<class>>
    +__init__(self, channels)
    +forward(self, x)
    +__init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)
    +forward(self, x)
    +__init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)
    +forward(self, z, target_shape)
  }
  class upsample_py_SRResidualCausalBlock3D {
    <<class>>
    +__init__(self, channels)
    +forward(self, x)
    +__init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)
    +forward(self, x)
    +__init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)
    +forward(self, z, target_shape)
  }
  class upsample_py_SRTo720pUpsampler {
    <<class>>
    +__init__(self, channels)
    +forward(self, x)
    +__init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)
    +forward(self, x)
    +__init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)
    +forward(self, z, target_shape)
  }
  class upsample_py_SRTo1080pUpsampler {
    <<class>>
    +__init__(self, channels)
    +forward(self, x)
    +__init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)
    +forward(self, x)
    +__init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)
    +forward(self, z, target_shape)
  }
  class __init___py_VisionEncoderModelOutput {
    <<class>>
    +use_default(value, default)
    +load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)
    +load_image_processor(processor_type, processor_path, logger)
    +__init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type, processor_path, output_key, logger, device)
    +__repr__(self)
    +encode_latents_to_images(self, latents, vae, reorg_token)
    +encode_images(self, images)
    +encode_latents(self, latents, vae, reorg_token)
    +forward(self, images)
  }
  class __init___py_VisionEncoder {
    <<class>>
    +use_default(value, default)
    +load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)
    +load_image_processor(processor_type, processor_path, logger)
    +__init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type, processor_path, output_key, logger, device)
    +__repr__(self)
    +encode_latents_to_images(self, latents, vae, reorg_token)
    +encode_images(self, images)
    +encode_latents(self, latents, vae, reorg_token)
    +forward(self, images)
  }
  class muon_py_Muon {
    <<class>>
    +zeropower_via_newtonschulz5(G, steps)
    +get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)
    +__init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)
    +adjust_lr_for_muon(self, lr, param_shape)
    +step(self, closure)
  }
  class hunyuan_video_pipeline_py_HunyuanVideoPipelineOutput {
    <<class>>
    +__init__(self, vae, text_encoder, transformer, scheduler, text_encoder_2, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)
    +_create_scheduler(cls, flow_shift)
    +_load_byt5(cls, cached_folder, glyph_byT5_v2, byt5_max_length, device)
    +encode_prompt(self, prompt, device, num_videos_per_prompt, do_classifier_free_guidance, negative_prompt, prompt_embeds, attention_mask, negative_prompt_embeds, negative_attention_mask, clip_skip, text_encoder, data_type)
    +prepare_extra_func_kwargs(self, func, kwargs)
    +prepare_latents(self, batch_size, num_channels_latents, latent_height, latent_width, video_length, dtype, device, generator, latents)
    +get_guidance_scale_embedding(self, w, embedding_dim, dtype)
    +guidance_scale(self)
    +guidance_rescale(self)
    +clip_skip(self)
  }
  class hunyuan_video_pipeline_py_HunyuanVideo_1_5_Pipeline {
    <<class>>
    +__init__(self, vae, text_encoder, transformer, scheduler, text_encoder_2, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)
    +_create_scheduler(cls, flow_shift)
    +_load_byt5(cls, cached_folder, glyph_byT5_v2, byt5_max_length, device)
    +encode_prompt(self, prompt, device, num_videos_per_prompt, do_classifier_free_guidance, negative_prompt, prompt_embeds, attention_mask, negative_prompt_embeds, negative_attention_mask, clip_skip, text_encoder, data_type)
    +prepare_extra_func_kwargs(self, func, kwargs)
    +prepare_latents(self, batch_size, num_channels_latents, latent_height, latent_width, video_length, dtype, device, generator, latents)
    +get_guidance_scale_embedding(self, w, embedding_dim, dtype)
    +guidance_scale(self)
    +guidance_rescale(self)
    +clip_skip(self)
  }
  class hunyuan_video_sr_pipeline_py_BucketMap {
    <<class>>
    +expand_dims(tensor, ndim)
    +__init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)
    +__call__(self, lr_bucket)
    +__init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, base_resolution, text_encoder_2, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)
    +add_noise_to_lq(self, lq_latents, strength)
    +_prepare_lq_cond_latents(self, lq_latents)
    +__call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt, num_videos_per_prompt, generator, seed, embedded_guidance_scale, reference_image, lq_latents, output_type, return_dict, enable_vae_tile_parallelism)
  }
  class hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_PipelineOutput {
    <<class>>
    +expand_dims(tensor, ndim)
    +__init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)
    +__call__(self, lr_bucket)
    +__init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, base_resolution, text_encoder_2, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)
    +add_noise_to_lq(self, lq_latents, strength)
    +_prepare_lq_cond_latents(self, lq_latents)
    +__call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt, num_videos_per_prompt, generator, seed, embedded_guidance_scale, reference_image, lq_latents, output_type, return_dict, enable_vae_tile_parallelism)
  }
  class hunyuan_video_sr_pipeline_py_HunyuanVideo_1_5_SR_Pipeline {
    <<class>>
    +expand_dims(tensor, ndim)
    +__init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)
    +__call__(self, lr_bucket)
    +__init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, base_resolution, text_encoder_2, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)
    +add_noise_to_lq(self, lq_latents, strength)
    +_prepare_lq_cond_latents(self, lq_latents)
    +__call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt, num_videos_per_prompt, generator, seed, embedded_guidance_scale, reference_image, lq_latents, output_type, return_dict, enable_vae_tile_parallelism)
  }
  class scheduling_flow_match_discrete_py_FlowMatchDiscreteSchedulerOutput {
    <<class>>
    +__init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift, n_tokens, flux_base_token, flux_max_token, flux_shift_factor)
    +step_index(self)
    +begin_index(self)
    +set_begin_index(self, begin_index)
    +_sigma_to_t(self, sigma)
    +set_timesteps(self, num_inference_steps, device, n_tokens)
    +index_for_timestep(self, timestep, schedule_timesteps)
    +_init_step_index(self, timestep)
    +scale_model_input(self, sample, timestep)
    +get_lin_function(x1, y1, x2, y2)
  }
  class scheduling_flow_match_discrete_py_FlowMatchDiscreteScheduler {
    <<class>>
    +__init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift, n_tokens, flux_base_token, flux_max_token, flux_shift_factor)
    +step_index(self)
    +begin_index(self)
    +set_begin_index(self, begin_index)
    +_sigma_to_t(self, sigma)
    +set_timesteps(self, num_inference_steps, device, n_tokens)
    +index_for_timestep(self, timestep, schedule_timesteps)
    +_init_step_index(self, timestep)
    +scale_model_input(self, sample, timestep)
    +get_lin_function(x1, y1, x2, y2)
  }
  class communications_py_SeqAllToAll4D {
    <<class>>
    +broadcast(input_, group)
    +_all_to_all_4D(input, scatter_idx, gather_idx, group)
    +all_to_all_4D(input_, group, scatter_dim, gather_dim)
    +_all_to_all(input_, world_size, group, scatter_dim, gather_dim)
    +all_to_all(input_, group, scatter_dim, gather_dim)
    +all_gather(input_, dim, group)
    +forward(ctx, group, input, scatter_idx, gather_idx)
    +backward(ctx)
    +forward(ctx, input_, process_group, scatter_dim, gather_dim)
    +backward(ctx, grad_output)
  }
```

---

## Code Property Graph

Machine-readable Code Property Graph (CPG) in JSON-LD format. This block allows AI agents to parse the full structural graph without additional file reads. Compatible with GraphRAG pipelines.

```json
{"@context": "https://schema.org", "analysis": {"communities": [{"cohesion": 0.458, "id": 0, "label": "hyvideo/pipelines", "size": 11}, {"cohesion": 0.745, "id": 1, "label": "hyvideo/models/transformers/modules", "size": 21}, {"cohesion": 0.75, "id": 2, "label": "hyvideo/utils/rewrite", "size": 4}], "god_nodes": [{"node_id": "hyvideo/pipelines/hunyuan_video_pipeline.py", "score": 40.3}, {"node_id": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "score": 30.2}, {"node_id": "hyvideo/commons/__init__.py", "score": 17.2}, {"node_id": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "score": 17.0}, {"node_id": "hyvideo/models/transformers/modules/token_refiner.py", "score": 14.9}, {"node_id": "hyvideo/commons/parallel_states.py", "score": 14.8}, {"node_id": "hyvideo/models/transformers/modules/attention.py", "score": 14.6}, {"node_id": "train.py", "score": 10.5}, {"node_id": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "score": 10.2}, {"node_id": "hyvideo/models/transformers/modules/mlp_layers.py", "score": 9.2}], "surprising_connections": [{"hops": 5, "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "hyvideo/utils/rewrite/clients.py"}, {"hops": 5, "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "hyvideo/utils/rewrite/i2v_prompt.py"}, {"hops": 5, "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "hyvideo/utils/rewrite/t2v_prompt.py"}, {"hops": 5, "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "hyvideo/utils/rewrite/clients.py"}, {"hops": 5, "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "hyvideo/utils/rewrite/i2v_prompt.py"}]}, "edges": [{"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "copy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "datetime"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "json"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "loguru"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "argparse"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "imageio"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "torch.distributed.checkpoint"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "torch.distributed.checkpoint.state_dict"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "hyvideo.pipelines.hunyuan_video_pipeline"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "hyvideo.commons.parallel_states"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "hyvideo.commons.infer_state"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "generate.py", "target": "sgl_kernel"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/__init__.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/__init__.py", "target": "socket"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/__init__.py", "target": "commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "itertools"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "contextlib"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "collections.abc"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "warnings"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "diffusers.hooks.group_offloading"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "flash_attn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "flash_attn_interface"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "flex_block_attn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "angelslim"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/__init__.py", "target": "sageattention"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/infer_state.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/infer_state.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/parallel_states.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/parallel_states.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/parallel_states.py", "target": "torch.distributed"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/commons/parallel_states.py", "target": "torch.distributed.device_mesh"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "math"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "contextlib"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "loguru"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "torch.nn.functional"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "diffusers.configuration_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "diffusers.models.autoencoders.vae"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "diffusers.models.modeling_outputs"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "diffusers.models.modeling_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "hyvideo.commons.parallel_states"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "copy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "transformers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/__init__.py", "target": "transformers.utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/__init__.py", "target": "json"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/__init__.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/__init__.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/__init__.py", "target": "transformers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/format_prompt.py", "target": "json"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/format_prompt.py", "target": "webcolors"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/format_prompt.py", "target": "webcolors"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/text_encoders/byT5/format_prompt.py", "target": "webcolors"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "loguru"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "diffusers.models"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "diffusers.configuration_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.activation_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.norm_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.embed_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.attention"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.posemb_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.mlp_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.modulate_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "modules.token_refiner"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo.utils.communications"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo.models.text_encoders.byT5"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo.commons.parallel_states"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "diffusers.loaders.peft"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "peft.utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "diffusers.loaders.lora_base"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "diffusers.utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "safetensors"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "json"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "pathlib"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "safetensors.torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/activation_layers.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "loguru"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "torch.nn.functional"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo.commons.parallel_states"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo.utils.communications"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo.utils.flash_attn_no_pad"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo.models.transformers.modules.ssta_attention"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "torch.nn.attention.flex_attention"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "sageattention"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/embed_layers.py", "target": "math"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/embed_layers.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/embed_layers.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/embed_layers.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/mlp_layers.py", "target": "functools"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/mlp_layers.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/mlp_layers.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/mlp_layers.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/mlp_layers.py", "target": "modulate_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/modulate_layers.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/modulate_layers.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/modulate_layers.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/norm_layers.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/norm_layers.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/posemb_layers.py", "target": "functools"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/posemb_layers.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/posemb_layers.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "math"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "functools"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/ssta_attention.py", "target": "flex_block_attn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "activation_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "embed_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "mlp_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "modulate_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "norm_layers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "attention"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "collections.abc"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "enum"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "torch.nn.functional"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "diffusers.models"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "diffusers.configuration_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "hyvideo.models.autoencoders.hunyuanvideo_15_vae"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "transformers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "transformers.utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/optim/muon.py", "target": "math"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/optim/muon.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/optim/muon.py", "target": "torch.distributed.tensor"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/optim/muon.py", "target": "torch.distributed.tensor.placement_types"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "psutil"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "inspect"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "random"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "re"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "loguru"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "PIL"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "torchvision.transforms"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "diffusers.configuration_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "diffusers.image_processor"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "diffusers.models"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "diffusers.pipelines.pipeline_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "diffusers.schedulers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "diffusers.utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.commons.parallel_states"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.models.autoencoders"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.models.text_encoders"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.models.text_encoders.byT5"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.models.text_encoders.byT5.format_prompt"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.models.transformers.hunyuanvideo_1_5_transformer"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.models.transformers.modules.upsample"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.models.vision_encoder"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.schedulers.scheduling_flow_match_discrete"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.utils.data_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.utils.multitask_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.commons.infer_state"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "pipeline_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hunyuan_video_sr_pipeline"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo.utils.rewrite.rewrite_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "angelslim.compressor.diffusion"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "angelslim.compressor.diffusion"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "PIL"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "diffusers.models"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "diffusers.schedulers"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "diffusers.utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo.commons.parallel_states"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo.commons"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo.models.text_encoders"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo.models.transformers.hunyuanvideo_1_5_transformer"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo.models.transformers.modules.upsample"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo.utils.data_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hunyuan_video_pipeline"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "pipeline_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/pipeline_utils.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/pipeline_utils.py", "target": "inspect"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/pipelines/pipeline_utils.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "math"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "diffusers.configuration_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "diffusers.utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "target": "diffusers.schedulers.scheduling_utils"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/communications.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/communications.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/communications.py", "target": "torch.distributed"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/communications.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/data_utils.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/data_utils.py", "target": "PIL"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "flash_attn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "flash_attn.bert_padding"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "flash_attn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "flash_attn.bert_padding"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/flash_attn_no_pad.py", "target": "flash_attn_interface"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/infer_utils.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/multitask_utils.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/multitask_utils.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/multitask_utils.py", "target": "numpy"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/multitask_utils.py", "target": "PIL"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "json"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "time"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "ast"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "io"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "base64"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "openai"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "loguru"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "tencentcloud.common.common_client"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "tencentcloud.common"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "tencentcloud.common.profile.client_profile"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "tencentcloud.common.profile.http_profile"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/clients.py", "target": "PIL"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/rewrite_utils.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/rewrite_utils.py", "target": "hyvideo.utils.rewrite.clients"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/rewrite_utils.py", "target": "hyvideo.utils.rewrite.t2v_prompt"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "hyvideo/utils/rewrite/rewrite_utils.py", "target": "hyvideo.utils.rewrite.i2v_prompt"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "os"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "random"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "math"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "argparse"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "dataclasses"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "typing"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "enum"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "torch"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "torch.distributed"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "torch.nn"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "torch.distributed.checkpoint"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "torch.distributed.checkpoint.state_dict"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "diffusers.optimization"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "loguru"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "einops"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "imageio"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "hyvideo.pipelines.hunyuan_video_pipeline"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "hyvideo.commons.parallel_states"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "hyvideo.optim.muon"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "torch.distributed._composable.fsdp"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "torch.distributed.algorithms._checkpoint.checkpoint_wrapper"}, {"confidence": "EXTRACTED", "relation": "imports", "source": "train.py", "target": "peft"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "generate.py", "target": "hyvideo/pipelines/hunyuan_video_pipeline.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "generate.py", "target": "hyvideo/commons/parallel_states.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "generate.py", "target": "hyvideo/commons/infer_state.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/__init__.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "target": "hyvideo/commons/parallel_states.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/activation_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/norm_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/embed_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/attention.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/posemb_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/mlp_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/modulate_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/transformers/modules/token_refiner.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/utils/communications.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/models/text_encoders/byT5/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "target": "hyvideo/commons/parallel_states.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo/commons/parallel_states.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo/utils/communications.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo/utils/flash_attn_no_pad.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/attention.py", "target": "hyvideo/models/transformers/modules/ssta_attention.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/embed_layers.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/mlp_layers.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/mlp_layers.py", "target": "hyvideo/models/transformers/modules/modulate_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "hyvideo/models/transformers/modules/activation_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "hyvideo/models/transformers/modules/embed_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "hyvideo/models/transformers/modules/mlp_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "hyvideo/models/transformers/modules/modulate_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "hyvideo/models/transformers/modules/norm_layers.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/token_refiner.py", "target": "hyvideo/models/transformers/modules/attention.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/transformers/modules/upsample.py", "target": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/models/vision_encoder/__init__.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/pipelines/pipeline_utils.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/commons/parallel_states.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/models/autoencoders/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/models/text_encoders/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/models/text_encoders/byT5/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/models/text_encoders/byT5/format_prompt.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/models/transformers/modules/upsample.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/models/vision_encoder/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/schedulers/scheduling_flow_match_discrete.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/utils/data_utils.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/utils/multitask_utils.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/commons/infer_state.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/pipelines/pipeline_utils.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_pipeline.py", "target": "hyvideo/utils/rewrite/rewrite_utils.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/commons/parallel_states.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/commons/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/models/text_encoders/__init__.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/models/transformers/modules/upsample.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/utils/data_utils.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/pipelines/hunyuan_video_pipeline.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "target": "hyvideo/pipelines/pipeline_utils.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/utils/rewrite/rewrite_utils.py", "target": "hyvideo/utils/rewrite/clients.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/utils/rewrite/rewrite_utils.py", "target": "hyvideo/utils/rewrite/t2v_prompt.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "hyvideo/utils/rewrite/rewrite_utils.py", "target": "hyvideo/utils/rewrite/i2v_prompt.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "train.py", "target": "hyvideo/pipelines/hunyuan_video_pipeline.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "train.py", "target": "hyvideo/commons/parallel_states.py"}, {"confidence": "EXTRACTED", "relation": "resolved_imports", "source": "train.py", "target": "hyvideo/optim/muon.py"}], "generator": "readmenator", "metadata": {"edge_count": 3137, "file_count": 38, "language_count": 1, "symbol_count": 409}, "nodes": [{"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "generate.py", "kind": "module", "label": "generate.py", "language": "py", "sha256": "fc496bf4636200fc", "symbol_count": 8, "symbols": [{"kind": "function", "line": 42, "name": "save_video", "signature": "def save_video(video, path)"}, {"kind": "function", "line": 50, "name": "rank0_log", "signature": "def rank0_log(message, level)"}, {"kind": "function", "line": 54, "name": "save_config", "signature": "def save_config(args, output_path, task, transformer_version)"}, {"doc": "Convert string to boolean, supporting true/false, 1/0, yes/no.\nIf value is None (when flag is provided without value), returns True.", "kind": "function", "line": 81, "name": "str_to_bool", "signature": "def str_to_bool(value)"}, {"kind": "function", "line": 96, "name": "load_checkpoint_to_transformer", "signature": "def load_checkpoint_to_transformer(pipe, checkpoint_path)"}, {"kind": "function", "line": 112, "name": "load_lora_adapter", "signature": "def load_lora_adapter(pipe, lora_path)"}, {"kind": "function", "line": 128, "name": "generate_video", "signature": "def generate_video(args)"}, {"kind": "function", "line": 274, "name": "main", "signature": "def main()"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/__init__.py", "kind": "module", "label": "__init__.py", "language": "py", "sha256": "304aed06074e3d83", "symbol_count": 2, "symbols": [{"kind": "function", "line": 25, "name": "find_free_port", "signature": "def find_free_port()"}, {"kind": "function", "line": 32, "name": "__initialize_default_distributed_environment", "signature": "def __initialize_default_distributed_environment()"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/commons/__init__.py", "kind": "module", "label": "__init__.py", "language": "py", "sha256": "096b05f13b45fa32", "symbol_count": 12, "symbols": [{"doc": "Create a function that converts input to n-tuple.", "kind": "function", "line": 24, "name": "_ntuple", "signature": "def _ntuple(n)"}, {"kind": "function", "line": 142, "name": "is_flash2_available", "signature": "def is_flash2_available()"}, {"kind": "function", "line": 149, "name": "is_flash3_available", "signature": "def is_flash3_available()"}, {"kind": "function", "line": 156, "name": "is_flash_available", "signature": "def is_flash_available()"}, {"kind": "function", "line": 159, "name": "is_sparse_attn_supported", "signature": "def is_sparse_attn_supported()"}, {"kind": "function", "line": 162, "name": "is_sparse_attn_available", "signature": "def is_sparse_attn_available()"}, {"kind": "function", "line": 171, "name": "is_angelslim_available", "signature": "def is_angelslim_available()"}, {"doc": "Determine the final attention mode based on configuration and availability.\n\nArgs:\n    attn_mode: Requested attention mode\n    infer_state: Inference configuration object (optional)\n    block_idx: Current block index (optional)\n\nReturns:\n    Final attention mode to use", "kind": "function", "line": 178, "name": "maybe_fallback_attn_mode", "signature": "def maybe_fallback_attn_mode(attn_mode)"}, {"kind": "function", "line": 229, "name": "auto_offload_model", "signature": "def auto_offload_model(models, device, enabled)"}, {"kind": "function", "line": 243, "name": "get_gpu_memory", "signature": "def get_gpu_memory(device)"}, {"kind": "function", "line": 254, "name": "get_rank", "signature": "def get_rank()"}, {"kind": "function", "line": 26, "name": "parse", "signature": "def parse(x)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/commons/infer_state.py", "kind": "module", "label": "infer_state.py", "language": "py", "sha256": "db52056c521f4259", "symbol_count": 4, "symbols": [{"kind": "class", "line": 21, "name": "InferState", "signature": "class InferState"}, {"kind": "method", "line": 42, "name": "parse_range", "signature": "def parse_range(value)"}, {"kind": "method", "line": 49, "name": "initialize_infer_state", "signature": "def initialize_infer_state(args)"}, {"kind": "method", "line": 87, "name": "get_infer_state", "signature": "def get_infer_state()"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/commons/parallel_states.py", "kind": "module", "label": "parallel_states.py", "language": "py", "sha256": "65f517e60ccf5350", "symbol_count": 8, "symbols": [{"kind": "class", "line": 24, "name": "ParallelDims", "signature": "class ParallelDims"}, {"kind": "method", "line": 81, "name": "initialize_parallel_state", "signature": "def initialize_parallel_state(sp, dp_replicate)"}, {"kind": "method", "line": 89, "name": "get_parallel_state", "signature": "def get_parallel_state()"}, {"kind": "method", "line": 29, "name": "__post_init__", "signature": "def __post_init__(self)"}, {"kind": "method", "line": 37, "name": "build_mesh", "signature": "def build_mesh(self, device_type)"}, {"kind": "method", "line": 68, "name": "sp_enabled", "signature": "def sp_enabled(self)"}, {"kind": "method", "line": 72, "name": "sp_mesh", "signature": "def sp_mesh(self)"}, {"kind": "method", "line": 76, "name": "dp_enabled", "signature": "def dp_enabled(self)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/__init__.py", "kind": "module", "label": "__init__.py", "language": "py", "sha256": "36435c312f43d4df", "symbol_count": 0, "symbols": []}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/autoencoders/__init__.py", "kind": "module", "label": "__init__.py", "language": "py", "sha256": "9c3b2ce7d40e46e3", "symbol_count": 0, "symbols": []}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/autoencoders/hunyuanvideo_15_vae.py", "kind": "module", "label": "hunyuanvideo_15_vae.py", "language": "py", "sha256": "2e9b13bfc0ac159a", "symbol_count": 62, "symbols": [{"kind": "class", "line": 40, "name": "DecoderOutput", "signature": "class DecoderOutput(BaseOutput)"}, {"doc": "Applies the swish activation function (SiLU) with optional inplace support.", "kind": "method", "line": 45, "name": "swish", "signature": "def swish(x, inplace)"}, {"doc": "Forward with optional gradient checkpointing.", "kind": "method", "line": 50, "name": "forward_with_checkpointing", "signature": "def forward_with_checkpointing(module)"}, {"doc": "Causal Conv3d with efficient patch processing for large tensors.", "kind": "class", "line": 65, "name": "PatchCausalConv3d", "signature": "class PatchCausalConv3d(Conv3d)"}, {"doc": "Root Mean Square Layer Normalization for Channel-First or Last", "kind": "class", "line": 110, "name": "RMS_norm", "signature": "class RMS_norm(Module)"}, {"doc": "Causal Conv3d with configurable padding for temporal axis.", "kind": "class", "line": 129, "name": "CausalConv3d", "signature": "class CausalConv3d(Module)"}, {"doc": "Prepare a causal attention mask for 3D videos.\n\nArgs:\n    n_frame (int): Number of frames (temporal length).\n    n_hw (int): Product of height and width.\n    dtype: Desired mask dtype.\n    device: Device for the mask.\n    batch_size (int, optional): If set, expands for batch.\n\nReturns:\n    torch.Tensor: Causal attention mask.", "kind": "method", "line": 163, "name": "prepare_causal_attention_mask", "signature": "def prepare_causal_attention_mask(n_frame, n_hw, dtype, device, batch_size)"}, {"doc": "Self-attention block for 3D video tensors.", "kind": "class", "line": 186, "name": "AttnBlock", "signature": "class AttnBlock(Module)"}, {"doc": "ResNet-style block for 3D video tensors.", "kind": "class", "line": 219, "name": "ResnetBlock", "signature": "class ResnetBlock(Module)"}, {"kind": "class", "line": 251, "name": "Downsample", "signature": "class Downsample(Module)"}, {"doc": "Hierarchical upsampling with temporal/ spatial support.", "kind": "class", "line": 293, "name": "Upsample", "signature": "class Upsample(Module)"}, {"doc": "Hierarchical video encoder with temporal and spatial factorization.", "kind": "class", "line": 331, "name": "Encoder", "signature": "class Encoder(Module)"}, {"doc": "Hierarchical video decoder with upsampling factories.", "kind": "class", "line": 413, "name": "Decoder", "signature": "class Decoder(Module)"}, {"doc": "KL regularized 3D Conv VAE with advanced tiling and slicing strategies.", "kind": "class", "line": 495, "name": "AutoencoderKLConv3D", "signature": "class AutoencoderKLConv3D(ModelMixin, ConfigMixin)"}, {"kind": "method", "line": 52, "name": "create_custom_forward", "signature": "def create_custom_forward(module)"}, {"kind": "method", "line": 67, "name": "find_split_indices", "signature": "def find_split_indices(self, seq_len, part_num)"}, {"kind": "method", "line": 86, "name": "forward", "signature": "def forward(self, input)"}, {"kind": "method", "line": 113, "name": "__init__", "signature": "def __init__(self, dim, channel_first, images, bias)"}, {"kind": "method", "line": 123, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 132, "name": "__init__", "signature": "def __init__(self, chan_in, chan_out, kernel_size, stride, dilation, pad_mode, disable_causal, enable_patch_conv)"}, {"kind": "method", "line": 158, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 189, "name": "__init__", "signature": "def __init__(self, in_channels)"}, {"kind": "method", "line": 200, "name": "attention", "signature": "def attention(self, h_)"}, {"kind": "method", "line": 215, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 222, "name": "__init__", "signature": "def __init__(self, in_channels, out_channels)"}, {"kind": "method", "line": 236, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 253, "name": "__init__", "signature": "def __init__(self, in_channels, out_channels, add_temporal_downsample)"}, {"kind": "method", "line": 261, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 296, "name": "__init__", "signature": "def __init__(self, in_channels, out_channels, add_temporal_upsample)"}, {"kind": "method", "line": 303, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 334, "name": "__init__", "signature": "def __init__(self, in_channels, z_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, downsample_match_channel)"}, {"doc": "Forward pass through the encoder.", "kind": "method", "line": 386, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 416, "name": "__init__", "signature": "def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, ffactor_spatial, ffactor_temporal, upsample_match_channel)"}, {"doc": "Forward pass through the decoder.", "kind": "method", "line": 468, "name": "forward", "signature": "def forward(self, z)"}, {"kind": "method", "line": 500, "name": "__init__", "signature": "def __init__(self, in_channels, out_channels, latent_channels, block_out_channels, layers_per_block, ffactor_spatial, ffactor_temporal, sample_size, sample_tsize, scaling_factor, shift_factor, downsample_match_channel, upsample_match_channel)"}, {"kind": "method", "line": 554, "name": "set_tile_sample_min_size", "signature": "def set_tile_sample_min_size(self, sample_size, tile_overlap_factor)"}, {"doc": "Enable or disable gradient checkpointing on encoder and decoder.", "kind": "method", "line": 563, "name": "_set_gradient_checkpointing", "signature": "def _set_gradient_checkpointing(self, module, value)"}, {"kind": "method", "line": 569, "name": "enable_temporal_tiling", "signature": "def enable_temporal_tiling(self, use_tiling)"}, {"kind": "method", "line": 573, "name": "disable_temporal_tiling", "signature": "def disable_temporal_tiling(self)"}, {"kind": "method", "line": 576, "name": "enable_spatial_tiling", "signature": "def enable_spatial_tiling(self, use_tiling)"}, {"kind": "method", "line": 579, "name": "disable_spatial_tiling", "signature": "def disable_spatial_tiling(self)"}, {"kind": "method", "line": 582, "name": "enable_tiling", "signature": "def enable_tiling(self, use_tiling)"}, {"kind": "method", "line": 585, "name": "disable_tiling", "signature": "def disable_tiling(self)"}, {"kind": "method", "line": 588, "name": "enable_slicing", "signature": "def enable_slicing(self)"}, {"kind": "method", "line": 591, "name": "disable_slicing", "signature": "def disable_slicing(self)"}, {"doc": "Blend tensor b horizontally into a at blend_extent region.", "kind": "method", "line": 594, "name": "blend_h", "signature": "def blend_h(self, a, b, blend_extent)"}, {"doc": "Blend tensor b vertically into a at blend_extent region.", "kind": "method", "line": 601, "name": "blend_v", "signature": "def blend_v(self, a, b, blend_extent)"}, {"doc": "Blend tensor b temporally into a at blend_extent region.", "kind": "method", "line": 608, "name": "blend_t", "signature": "def blend_t(self, a, b, blend_extent)"}, {"doc": "Tiled spatial encoding for large inputs via overlapping.", "kind": "method", "line": 615, "name": "spatial_tiled_encode", "signature": "def spatial_tiled_encode(self, x)"}, {"doc": "Tiled temporal encoding for large video sequences.", "kind": "method", "line": 643, "name": "temporal_tiled_encode", "signature": "def temporal_tiled_encode(self, x)"}, {"kind": "method", "line": 671, "name": "enable_tile_parallelism", "signature": "def enable_tile_parallelism(self)"}, {"kind": "method", "line": 674, "name": "disable_tile_parallelism", "signature": "def disable_tile_parallelism(self)"}, {"kind": "method", "line": 677, "name": "tile_parallel_spatial_tiled_decode", "signature": "def tile_parallel_spatial_tiled_decode(self, z)"}, {"kind": "method", "line": 772, "name": "spatial_tiled_decode", "signature": "def spatial_tiled_decode(self, z)"}, {"doc": "Tiled temporal decoding for long sequence latents.", "kind": "method", "line": 803, "name": "temporal_tiled_decode", "signature": "def temporal_tiled_decode(self, z)"}, {"kind": "method", "line": 833, "name": "encode", "signature": "def encode(self, x, return_dict)"}, {"kind": "method", "line": 856, "name": "decode", "signature": "def decode(self, z, return_dict, generator)"}, {"doc": "Forward autoencoder pass. Returns both reconstruction and optionally the posterior.", "kind": "method", "line": 876, "name": "forward", "signature": "def forward(self, sample, sample_posterior, return_posterior, return_dict)"}, {"kind": "method", "line": 890, "name": "memory_efficient_context", "signature": "def memory_efficient_context(self)"}, {"kind": "method", "line": 53, "name": "custom_forward", "signature": "def custom_forward()"}, {"kind": "method", "line": 835, "name": "_encode", "signature": "def _encode(x)"}, {"kind": "method", "line": 858, "name": "_decode", "signature": "def _decode(z)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/text_encoders/__init__.py", "kind": "module", "label": "__init__.py", "language": "py", "sha256": "77115ea175fa8f6e", "symbol_count": 14, "symbols": [{"doc": "Utility: return value if not None, else default.", "kind": "function", "line": 32, "name": "use_default", "signature": "def use_default(value, default)"}, {"kind": "function", "line": 84, "name": "load_text_encoder", "signature": "def load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)"}, {"kind": "function", "line": 114, "name": "load_tokenizer", "signature": "def load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)"}, {"doc": "Base class for model's outputs that also contains a pooling of the last hidden states.\n\nArgs:\n    hidden_state (`torch.FloatTensor` of shape `(batch_size, sequence_length, hidden_size)`):\n        Sequence of hidden-states at the output of the last layer of the model.\n    attention_mask (`torch.LongTensor` of shape `(batch_size, sequence_length)`, *optional*):\n        Mask to avoid performing attention on padding token indices. Mask values selected in ``[0, 1]``:\n    hidden_states_list (`tuple(torch.FloatTensor)`, *optional*, returned when `output_hidden_states=True` is passed):\n        Tuple of `torch.FloatTensor` (one for the output of the embeddings, if the model has an embedding layer, +\n        one for the output of each layer) of shape `(batch_size, sequence_length, hidden_size)`.\n        Hidden-states of the model at the output of each layer plus the optional initial embedding outputs.\n    text_outputs (`list`, *optional*, returned when `return_texts=True` is passed):\n        List of decoded texts.", "kind": "class", "line": 131, "name": "TextEncoderModelOutput", "signature": "class TextEncoderModelOutput(ModelOutput)"}, {"kind": "class", "line": 154, "name": "TextEncoder", "signature": "class TextEncoder(Module)"}, {"kind": "method", "line": 155, "name": "__init__", "signature": "def __init__(self, text_encoder_type, max_length, text_encoder_precision, text_encoder_path, tokenizer_type, tokenizer_path, output_key, use_attention_mask, prompt_template, prompt_template_video, hidden_state_skip_layer, apply_final_norm, reproduce, logger, device)"}, {"kind": "method", "line": 245, "name": "dtype", "signature": "def dtype(self)"}, {"kind": "method", "line": 249, "name": "device", "signature": "def device(self)"}, {"kind": "method", "line": 252, "name": "__repr__", "signature": "def __repr__(self)"}, {"doc": "Apply text to template.\n\nArgs:\n    text (str): Input text.\n    template (str or list): Template string or list of chat conversation.\n    prevent_empty_text (bool): If Ture, we will prevent the user text from being empty\n        by adding a space. Defaults to True.", "kind": "method", "line": 256, "name": "apply_text_to_template", "signature": "def apply_text_to_template(text, template, prevent_empty_text)"}, {"doc": "Automatically calculate the crop_start position based on identifying user tokens.\n\nArgs:\n    tokenized_input: The output from the tokenizer containing input_ids\n    \nReturns:\n    int: The position where the actual prompt content begins (after user markers)", "kind": "method", "line": 281, "name": "calculate_crop_start", "signature": "def calculate_crop_start(self, tokenized_input)"}, {"doc": "Tokenize the input text.\n\nArgs:\n    text (str or list): Input text.", "kind": "method", "line": 316, "name": "text2tokens", "signature": "def text2tokens(self, text, data_type, max_length)"}, {"doc": "Args:\n    batch_encoding (dict): Batch encoding from tokenizer.\n    use_attention_mask (bool): Whether to use attention mask. If None, use self.use_attention_mask.\n        Defaults to None.\n    output_hidden_states (bool): Whether to output hidden states. If False, return the value of\n        self.output_key. If True, return the entire output. If set self.hidden_state_skip_layer,\n        output_hidden_states will be set True. Defaults to False.\n    do_sample (bool): Whether to sample from the model. Used for Decoder-Only LLMs. Defaults to None.\n        When self.produce is False, do_sample is set to True by default.\n    hidden_state_skip_layer (int): Number of hidden states to hidden_state_skip_layer. 0 means the last layer.\n        If None, self.output_key will be used. Defaults to None.\n    return_texts (bool): Whether to return the decoded texts. Defaults to False.", "kind": "method", "line": 415, "name": "encode", "signature": "def encode(self, batch_encoding, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts, data_type, device, is_uncond)"}, {"kind": "method", "line": 487, "name": "forward", "signature": "def forward(self, text, use_attention_mask, output_hidden_states, do_sample, hidden_state_skip_layer, return_texts)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/text_encoders/byT5/__init__.py", "kind": "module", "label": "__init__.py", "language": "py", "sha256": "fdbdeac5627c11f9", "symbol_count": 7, "symbols": [{"doc": "Loads ByT5 tokenizer and encoder model for glyph encoding.\n\nArgs:\n    args (dict): Configuration dictionary containing paths and settings.\n    device (str or torch.device): Device to load the model onto.\n\nReturns:\n    dict: Dictionary with keys 'byt5_tokenizer', 'byt5_model', 'byt5_max_length'.", "kind": "function", "line": 23, "name": "load_glyph_byT5_v2", "signature": "def load_glyph_byT5_v2(args, device)"}, {"doc": "Create ByT5 tokenizer and encoder, load weights if provided.\n\nArgs:\n    args (dict): Configuration dictionary.\n    device (str or torch.device): Device to load the model onto.\n\nReturns:\n    tuple: (byt5_tokenizer, byt5_model, byt5_max_length)", "kind": "function", "line": 43, "name": "create_byt5", "signature": "def create_byt5(args, device)"}, {"doc": "Add special tokens for color and font to tokenizer and text encoder.\n\nArgs:\n    tokenizer: Huggingface tokenizer.\n    text_encoder: Huggingface T5 encoder.\n    add_color (bool): Whether to add color tokens.\n    add_font (bool): Whether to add font tokens.\n    color_ann_path (str): Path to color annotation JSON.\n    font_ann_path (str): Path to font annotation JSON.\n    multilingual (bool): Whether to use multilingual font tokens.", "kind": "function", "line": 89, "name": "add_special_token", "signature": "def add_special_token(tokenizer, text_encoder, add_color, add_font, color_ann_path, font_ann_path, multilingual)"}, {"doc": "Load ByT5 encoder and tokenizer from Huggingface, and add special tokens if needed.\n\nArgs:\n    byt5_name (str): Model name or path.\n    special_token (bool): Whether to add special tokens.\n    color_special_token (bool): Whether to add color tokens.\n    font_special_token (bool): Whether to add font tokens.\n    color_ann_path (str): Path to color annotation JSON.\n    font_ann_path (str): Path to font annotation JSON.\n    huggingface_cache_dir (str): Huggingface cache directory.\n    multilingual (bool): Whether to use multilingual font tokens.\n    device (str or torch.device): Device to load the model onto.\n\nReturns:\n    tuple: (byt5_text_encoder, byt5_tokenizer)", "kind": "function", "line": 131, "name": "load_byt5_and_byt5_tokenizer", "signature": "def load_byt5_and_byt5_tokenizer(byt5_name, special_token, color_special_token, font_special_token, color_ann_path, font_ann_path, huggingface_cache_dir, multilingual, device)"}, {"doc": "ByT5Mapper: Maps ByT5 encoder outputs to a new space, with optional residual connection.\n\nArgs:\n    in_dim (int): Input dimension (must equal out_dim if use_residual).\n    out_dim (int): Output dimension after second linear layer.\n    hidden_dim (int): Hidden dimension for intermediate layer.\n    out_dim1 (int): Final output dimension.\n    use_residual (bool): Whether to use residual connection (default: True).", "kind": "class", "line": 187, "name": "ByT5Mapper", "signature": "class ByT5Mapper(Module)"}, {"kind": "method", "line": 199, "name": "__init__", "signature": "def __init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)"}, {"doc": "Forward pass for ByT5Mapper.\n\nArgs:\n    x (Tensor): Input tensor of shape (..., in_dim).\n\nReturns:\n    Tensor: Output tensor of shape (..., out_dim1).", "kind": "method", "line": 210, "name": "forward", "signature": "def forward(self, x)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/text_encoders/byT5/format_prompt.py", "kind": "module", "label": "format_prompt.py", "language": "py", "sha256": "46533659845d9b9d", "symbol_count": 5, "symbols": [{"kind": "function", "line": 20, "name": "closest_color", "signature": "def closest_color(requested_color)"}, {"kind": "function", "line": 34, "name": "convert_rgb_to_names", "signature": "def convert_rgb_to_names(rgb_tuple)"}, {"kind": "class", "line": 44, "name": "MultilingualPromptFormat", "signature": "class MultilingualPromptFormat"}, {"kind": "method", "line": 46, "name": "__init__", "signature": "def __init__(self, font_path, color_path)"}, {"doc": "Text \"{text}\" in {color}, {type}.", "kind": "method", "line": 56, "name": "format_prompt", "signature": "def format_prompt(self, texts, styles)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py", "kind": "module", "label": "hunyuanvideo_1_5_transformer.py", "language": "py", "sha256": "2e635a41812a3775", "symbol_count": 22, "symbols": [{"kind": "class", "line": 45, "name": "MMDoubleStreamBlock", "signature": "class MMDoubleStreamBlock(Module)"}, {"kind": "class", "line": 208, "name": "MMSingleStreamBlock", "signature": "class MMSingleStreamBlock(Module)"}, {"doc": "HunyuanVideo Transformer backbone.\n\nArgs:\n    patch_size (list): The size of the patch.\n    in_channels (int): The number of input channels.\n    out_channels (int): The number of output channels.\n    hidden_size (int): The hidden size of the transformer backbone.\n    heads_num (int): The number of attention heads.\n    mlp_width_ratio (float): Width ratio for the transformer MLPs.\n    mlp_act_type (str): Activation type for the transformer MLPs.\n    mm_double_blocks_depth (int): Number of double-stream transformer blocks.\n    mm_single_blocks_depth (int): Number of single-stream transformer blocks.\n    rope_dim_list (list): Rotary embedding dim for t, h, w.\n    qkv_bias (bool): Use bias in qkv projection.\n    qk_norm (bool): Whether to use qk norm.\n    qk_norm_type (str): Type of qk norm.\n    guidance_embed (bool): Use guidance embedding for distillation.\n    text_projection (str): Text input projection. Default is \"single_refiner\".\n    use_attention_mask (bool): If to use attention mask.\n    text_states_dim (int): Text encoder output dim.\n    text_states_dim_2 (int): Secondary text encoder output dim.\n    text_pool_type (str): Type for text pooling.\n    rope_theta (int): Rotary embedding theta parameter.\n    attn_mode (str): Attention mode identifier.\n    attn_param (dict): Attention parameter dictionary.\n    glyph_byT5_v2 (bool): Use ByT5 glyph module.\n    vision_projection (str): Vision condition embedding mode.\n    vision_states_dim (int): Vision encoder states input dim.\n    is_reshape_temporal_channels (bool): For video VAE adaptation.\n    use_cond_type_embedding (bool): Use condition type embedding.", "kind": "class", "line": 316, "name": "HunyuanVideo_1_5_DiffusionTransformer", "signature": "class HunyuanVideo_1_5_DiffusionTransformer(ModelMixin, ConfigMixin, PeftAdapterMixin)"}, {"kind": "method", "line": 47, "name": "__init__", "signature": "def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qkv_bias, dtype, device)"}, {"kind": "method", "line": 111, "name": "enable_deterministic", "signature": "def enable_deterministic(self)"}, {"kind": "method", "line": 114, "name": "disable_deterministic", "signature": "def disable_deterministic(self)"}, {"kind": "method", "line": 117, "name": "forward", "signature": "def forward(self, img, txt, vec, freqs_cis, text_mask, attn_param, is_flash, block_idx)"}, {"kind": "method", "line": 210, "name": "__init__", "signature": "def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, attn_mode, qk_norm, qk_norm_type, qk_scale, dtype, device)"}, {"kind": "method", "line": 255, "name": "enable_deterministic", "signature": "def enable_deterministic(self)"}, {"kind": "method", "line": 258, "name": "disable_deterministic", "signature": "def disable_deterministic(self)"}, {"doc": "Forward pass for the single stream block.", "kind": "method", "line": 261, "name": "forward", "signature": "def forward(self, x, vec, txt_len, freqs_cis, text_mask, attn_param, is_flash)"}, {"kind": "method", "line": 351, "name": "__init__", "signature": "def __init__(self, patch_size, in_channels, concat_condition, out_channels, hidden_size, heads_num, mlp_width_ratio, mlp_act_type, mm_double_blocks_depth, mm_single_blocks_depth, rope_dim_list, qkv_bias, qk_norm, qk_norm_type, guidance_embed, use_meanflow, text_projection, use_attention_mask, text_states_dim, text_states_dim_2, text_pool_type, rope_theta, attn_mode, attn_param, glyph_byT5_v2, vision_projection, vision_states_dim, is_reshape_temporal_channels, use_cond_type_embedding, ideal_resolution, ideal_task)"}, {"kind": "method", "line": 563, "name": "load_hunyuan_state_dict", "signature": "def load_hunyuan_state_dict(self, model_path)"}, {"kind": "method", "line": 601, "name": "enable_deterministic", "signature": "def enable_deterministic(self)"}, {"kind": "method", "line": 607, "name": "disable_deterministic", "signature": "def disable_deterministic(self)"}, {"kind": "method", "line": 613, "name": "get_rotary_pos_embed", "signature": "def get_rotary_pos_embed(self, rope_sizes)"}, {"kind": "method", "line": 631, "name": "reorder_txt_token", "signature": "def reorder_txt_token(self, byt5_txt, txt, byt5_text_mask, text_mask, zero_feat, is_reorder)"}, {"kind": "method", "line": 667, "name": "forward", "signature": "def forward(self, hidden_states, timestep, text_states, text_states_2, encoder_attention_mask, timestep_r, vision_states, output_features, output_features_stride, attention_kwargs, freqs_cos, freqs_sin, return_dict, guidance, mask_type, extra_kwargs)"}, {"doc": "Unpatchify a tensorized input back to frame format.\n\nArgs:\n    x (Tensor): Input tensor of shape (N, T, patch_size**2 * C)\n    t (int): Number of time steps\n    h (int): Height in patch units\n    w (int): Width in patch units\n\nReturns:\n    Tensor: Output tensor of shape (N, C, t * pt, h * ph, w * pw)", "kind": "method", "line": 867, "name": "unpatchify", "signature": "def unpatchify(self, x, t, h, w)"}, {"kind": "method", "line": 888, "name": "set_attn_mode", "signature": "def set_attn_mode(self, attn_mode)"}, {"doc": "Save the LoRA parameters corresponding to the underlying model.\n\nArguments:\n    save_directory (`str` or `os.PathLike`):\n        Directory to save LoRA parameters to. Will be created if it doesn't exist.\n    adapter_name: (`str`, defaults to \"default\"): The name of the adapter to serialize. Useful when the\n        underlying model has multiple adapters loaded.\n    upcast_before_saving (`bool`, defaults to `False`):\n        Whether to cast the underlying model to `torch.float32` before serialization.\n    safe_serialization (`bool`, *optional*, defaults to `True`):\n        Whether to save the model using `safetensors` or the traditional PyTorch way with `pickle`.\n    weight_name: (`str`, *optional*, defaults to `None`): Name of the file to serialize the state dict with.", "kind": "method", "line": 896, "name": "save_lora_adapter", "signature": "def save_lora_adapter(self, save_directory, adapter_name, upcast_before_saving, safe_serialization, weight_name)"}, {"kind": "method", "line": 943, "name": "save_function", "signature": "def save_function(weights, filename)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/activation_layers.py", "kind": "module", "label": "activation_layers.py", "language": "py", "sha256": "df0cd6971c1290e3", "symbol_count": 1, "symbols": [{"doc": "get activation layer\n\nArgs:\n    act_type (str): the activation type\n\nReturns:\n    torch.nn.functional: the activation layer", "kind": "function", "line": 20, "name": "get_activation_layer", "signature": "def get_activation_layer(act_type)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/attention.py", "kind": "module", "label": "attention.py", "language": "py", "sha256": "be5738f69647f565", "symbol_count": 6, "symbols": [{"doc": "Compute attention using flash_attn_no_pad or torch scaled_dot_product_attention.\n\nArgs:\n    q: Query tensor of shape [B, L, H, D]\n    k: Key tensor of shape [B, L, H, D]\n    v: Value tensor of shape [B, L, H, D]\n    drop_rate: Dropout rate for attention weights.\n    attn_mask: Optional attention mask of shape [B, L].\n    causal: Whether to apply causal masking.\n    attn_mode: Attention mode, either \"flash\" or \"torch\". Defaults to \"flash\".\n\nReturns:\n    Output tensor after attention of shape [B, L, H*D]", "kind": "function", "line": 50, "name": "attention", "signature": "def attention(q, k, v, drop_rate, attn_mask, causal, attn_mode)"}, {"kind": "function", "line": 112, "name": "parallel_attention", "signature": "def parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)"}, {"kind": "function", "line": 120, "name": "sequence_parallel_attention", "signature": "def sequence_parallel_attention(q, k, v, img_q_len, img_kv_len, attn_mode, text_mask, attn_param, block_idx)"}, {"kind": "function", "line": 145, "name": "shrink_head", "signature": "def shrink_head(encoder_state, dim)"}, {"kind": "function", "line": 188, "name": "score_mod", "signature": "def score_mod(score, b, h, q_idx, kv_idx)"}, {"kind": "function", "line": 231, "name": "get_image_tile", "signature": "def get_image_tile(tile_size)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/embed_layers.py", "kind": "module", "label": "embed_layers.py", "language": "py", "sha256": "33b37e11354aec18", "symbol_count": 16, "symbols": [{"doc": "2D Image to Patch Embedding\n\nImage to Patch Embedding using Conv2d\n\nA convolution based approach to patchifying a 2D image w/ embedding projection.\n\nBased on the impl in https://github.com/google-research/vision_transformer\n\nHacked together by / Copyright 2020 Ross Wightman\n\nRemove the _assert function in forward function to be compatible with multi-resolution images.", "kind": "class", "line": 23, "name": "PatchEmbed", "signature": "class PatchEmbed(Module)"}, {"doc": "Projects text embeddings. Also handles dropout for classifier-free guidance.\n\nAdapted from https://github.com/PixArt-alpha/PixArt-alpha/blob/master/diffusion/model/nets/PixArt_blocks.py", "kind": "class", "line": 90, "name": "TextProjection", "signature": "class TextProjection(Module)"}, {"kind": "class", "line": 122, "name": "VisionProjection", "signature": "class VisionProjection(Module)"}, {"kind": "class", "line": 139, "name": "ClipVisionProjection", "signature": "class ClipVisionProjection(Module)"}, {"doc": "Create sinusoidal timestep embeddings.\n\nArgs:\n    t (torch.Tensor): a 1-D Tensor of N indices, one per batch element. These may be fractional.\n    dim (int): the dimension of the output.\n    max_period (int): controls the minimum frequency of the embeddings.\n\nReturns:\n    embedding (torch.Tensor): An (N, D) Tensor of positional embeddings.\n\n.. ref_link: https://github.com/openai/glide-text2im/blob/main/glide_text2im/nn.py", "kind": "method", "line": 151, "name": "timestep_embedding", "signature": "def timestep_embedding(t, dim, max_period)"}, {"doc": "Embeds scalar timesteps into vector representations.", "kind": "class", "line": 178, "name": "TimestepEmbedder", "signature": "class TimestepEmbedder(Module)"}, {"kind": "method", "line": 37, "name": "__init__", "signature": "def __init__(self, patch_size, in_chans, embed_dim, is_reshape_temporal_channels, concat_condition, norm_layer, flatten, bias, dtype, device)"}, {"kind": "method", "line": 82, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 97, "name": "__init__", "signature": "def __init__(self, in_channels, hidden_size, act_layer, dtype, device)"}, {"kind": "method", "line": 114, "name": "forward", "signature": "def forward(self, caption)"}, {"kind": "method", "line": 124, "name": "__init__", "signature": "def __init__(self, input_dim, output_dim)"}, {"kind": "method", "line": 136, "name": "forward", "signature": "def forward(self, vision_embeds)"}, {"kind": "method", "line": 140, "name": "__init__", "signature": "def __init__(self, in_channels, out_channels)"}, {"kind": "method", "line": 147, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 183, "name": "__init__", "signature": "def __init__(self, hidden_size, act_layer, frequency_embedding_size, max_period, out_size, dtype, device)"}, {"kind": "method", "line": 208, "name": "forward", "signature": "def forward(self, t)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.  Modified from timm library: https://github.com/huggingface/pytorch-image-models/blob/648aaa41233ba83eb38faf5ba9d415d574823241/timm/layers/mlp.py#L13", "id": "hyvideo/models/transformers/modules/mlp_layers.py", "kind": "module", "label": "mlp_layers.py", "language": "py", "sha256": "b7d961e7ef213c3d", "symbol_count": 12, "symbols": [{"doc": "MLP as used in Vision Transformer, MLP-Mixer and related networks", "kind": "class", "line": 29, "name": "MLP", "signature": "class MLP(Module)"}, {"kind": "class", "line": 70, "name": "LinearWarpforSingle", "signature": "class LinearWarpforSingle(Module)"}, {"doc": "copied from https://github.com/black-forest-labs/flux/blob/main/src/flux/modules/layers.py", "kind": "class", "line": 82, "name": "MLPEmbedder", "signature": "class MLPEmbedder(Module)"}, {"doc": "The final layer of DiT.", "kind": "class", "line": 96, "name": "FinalLayer", "signature": "class FinalLayer(Module)"}, {"kind": "method", "line": 32, "name": "__init__", "signature": "def __init__(self, in_channels, hidden_channels, out_features, act_layer, norm_layer, bias, drop, use_conv, device, dtype)"}, {"kind": "method", "line": 60, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 71, "name": "__init__", "signature": "def __init__(self, in_dim, out_dim, bias, device, dtype)"}, {"kind": "method", "line": 76, "name": "forward", "signature": "def forward(self, x, y)"}, {"kind": "method", "line": 85, "name": "__init__", "signature": "def __init__(self, in_dim, hidden_dim, device, dtype)"}, {"kind": "method", "line": 92, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 99, "name": "__init__", "signature": "def __init__(self, hidden_size, patch_size, out_channels, act_layer, device, dtype)"}, {"kind": "method", "line": 133, "name": "forward", "signature": "def forward(self, x, c)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/modulate_layers.py", "kind": "module", "label": "modulate_layers.py", "language": "py", "sha256": "783b5a276bc73698", "symbol_count": 7, "symbols": [{"doc": "Modulation layer for DiT.", "kind": "class", "line": 23, "name": "ModulateDiT", "signature": "class ModulateDiT(Module)"}, {"doc": "modulate by shift and scale\n\nArgs:\n    x (torch.Tensor): input tensor.\n    shift (torch.Tensor, optional): shift tensor. Defaults to None.\n    scale (torch.Tensor, optional): scale tensor. Defaults to None.\n\nReturns:\n    torch.Tensor: the output tensor after modulate.", "kind": "method", "line": 46, "name": "modulate", "signature": "def modulate(x, shift, scale)"}, {"doc": "AI is creating summary for apply_gate\n\nArgs:\n    x (torch.Tensor): input tensor.\n    gate (torch.Tensor, optional): gate tensor. Defaults to None.\n    tanh (bool, optional): whether to use tanh function. Defaults to False.\n\nReturns:\n    torch.Tensor: the output tensor after apply gate.", "kind": "method", "line": 67, "name": "apply_gate", "signature": "def apply_gate(x, gate, tanh)"}, {"kind": "method", "line": 86, "name": "ckpt_wrapper", "signature": "def ckpt_wrapper(module)"}, {"kind": "method", "line": 26, "name": "__init__", "signature": "def __init__(self, hidden_size, factor, act_layer, dtype, device)"}, {"kind": "method", "line": 42, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 87, "name": "ckpt_forward", "signature": "def ckpt_forward()"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/norm_layers.py", "kind": "module", "label": "norm_layers.py", "language": "py", "sha256": "d3f26a88c49f958f", "symbol_count": 6, "symbols": [{"kind": "class", "line": 21, "name": "RMSNorm", "signature": "class RMSNorm(Module)"}, {"doc": "Get the normalization layer.\n\nArgs:\n    norm_layer (str): The type of normalization layer.\n\nReturns:\n    norm_layer (nn.Module): The normalization layer.", "kind": "method", "line": 82, "name": "get_norm_layer", "signature": "def get_norm_layer(norm_layer)"}, {"doc": "Initialize the RMSNorm normalization layer.\n\nArgs:\n    dim (int): The dimension of the input tensor.\n    eps (float, optional): A small value added to the denominator for numerical stability. Default is 1e-6.\n\nAttributes:\n    eps (float): A small value added to the denominator for numerical stability.\n    weight (nn.Parameter): Learnable scaling parameter.", "kind": "method", "line": 22, "name": "__init__", "signature": "def __init__(self, dim, elementwise_affine, eps, device, dtype)"}, {"doc": "Apply the RMSNorm normalization to the input tensor.\n\nArgs:\n    x (torch.Tensor): The input tensor.\n\nReturns:\n    torch.Tensor: The normalized tensor.", "kind": "method", "line": 48, "name": "_norm", "signature": "def _norm(self, x)"}, {"kind": "method", "line": 61, "name": "reset_parameters", "signature": "def reset_parameters(self)"}, {"doc": "Forward pass through the RMSNorm layer.\n\nArgs:\n    x (torch.Tensor): The input tensor.\n\nReturns:\n    torch.Tensor: The output tensor after applying RMSNorm.", "kind": "method", "line": 65, "name": "forward", "signature": "def forward(self, x)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/posemb_layers.py", "kind": "module", "label": "posemb_layers.py", "language": "py", "sha256": "5bd475aa7cbe509d", "symbol_count": 7, "symbols": [{"kind": "function", "line": 23, "name": "_to_tuple", "signature": "def _to_tuple(x, dim)"}, {"doc": "Get n-D meshgrid with start, stop and num.\n\nArgs:\n    start (int or tuple): If len(args) == 0, start is num; If len(args) == 1, start is start, args[0] is stop,\n        step is 1; If len(args) == 2, start is start, args[0] is stop, args[1] is num. For n-dim, start/stop/num\n        should be int or n-tuple. If n-tuple is provided, the meshgrid will be stacked following the dim order in\n        n-tuples.\n    *args: See above.\n    dim (int): Dimension of the meshgrid. Defaults to 2.\n\nReturns:\n    grid (np.ndarray): [dim, ...]", "kind": "function", "line": 32, "name": "get_meshgrid_nd", "signature": "def get_meshgrid_nd(start)"}, {"doc": "Reshape frequency tensor for broadcasting it with another tensor.\n\nThis function reshapes the frequency tensor to have the same shape as the target tensor 'x'\nfor the purpose of broadcasting the frequency tensor during element-wise operations.\n\nNotes:\n    When using FlashMHAModified, head_first should be False.\n    When using Attention, head_first should be True.\n\nArgs:\n    freqs_cis (Union[torch.Tensor, Tuple[torch.Tensor]]): Frequency tensor to be reshaped.\n    x (torch.Tensor): Target tensor for broadcasting compatibility.\n    head_first (bool): head dimension first (except batch dim) or not.\n\nReturns:\n    torch.Tensor: Reshaped frequency tensor.\n\nRaises:\n    AssertionError: If the frequency tensor doesn't match the expected shape.\n    AssertionError: If the target tensor 'x' doesn't have the expected number of dimensions.", "kind": "function", "line": 83, "name": "reshape_for_broadcast", "signature": "def reshape_for_broadcast(freqs_cis, x, head_first)"}, {"kind": "function", "line": 151, "name": "rotate_half", "signature": "def rotate_half(x)"}, {"doc": "Apply rotary embeddings to input tensors using the given frequency tensor.\n\nThis function applies rotary embeddings to the given query 'xq' and key 'xk' tensors using the provided\nfrequency tensor 'freqs_cis'. The input tensors are reshaped as complex numbers, and the frequency tensor\nis reshaped for broadcasting compatibility. The resulting tensors contain rotary embeddings and are\nreturned as real tensors.\n\nArgs:\n    xq (torch.Tensor): Query tensor to apply rotary embeddings. [B, S, H, D]\n    xk (torch.Tensor): Key tensor to apply rotary embeddings.   [B, S, H, D]\n    freqs_cis (torch.Tensor or tuple): Precomputed frequency tensor for complex exponential.\n    head_first (bool): head dimension first (except batch dim) or not.\n\nReturns:\n    Tuple[torch.Tensor, torch.Tensor]: Tuple of modified query tensor and key tensor with rotary embeddings.", "kind": "function", "line": 158, "name": "apply_rotary_emb", "signature": "def apply_rotary_emb(xq, xk, freqs_cis, head_first)"}, {"doc": "This is a n-d version of precompute_freqs_cis, which is a RoPE for tokens with n-d structure.\n\nArgs:\n    rope_dim_list (list of int): Dimension of each rope. len(rope_dim_list) should equal to n.\n        sum(rope_dim_list) should equal to head_dim of attention layer.\n    start (int | tuple of int | list of int): If len(args) == 0, start is num; If len(args) == 1, start is start,\n        args[0] is stop, step is 1; If len(args) == 2, start is start, args[0] is stop, args[1] is num.\n    *args: See above.\n    theta (float): Scaling factor for frequency computation. Defaults to 10000.0.\n    use_real (bool): If True, return real part and imaginary part separately. Otherwise, return complex numbers.\n        Some libraries such as TensorRT does not support complex64 data type. So it is useful to provide a real\n        part and an imaginary part separately.\n    theta_rescale_factor (float): Rescale factor for theta. Defaults to 1.0.\n\nReturns:\n    pos_embed (torch.Tensor): [HW, D/2]", "kind": "function", "line": 210, "name": "get_nd_rotary_pos_embed", "signature": "def get_nd_rotary_pos_embed(rope_dim_list, start)"}, {"doc": "Precompute the frequency tensor for complex exponential (cis) with given dimensions.\n(Note: `cis` means `cos + i * sin`, where i is the imaginary unit.)\n\nThis function calculates a frequency tensor with complex exponential using the given dimension 'dim'\nand the end index 'end'. The 'theta' parameter scales the frequencies.\nThe returned tensor contains complex values in complex64 data type.\n\nArgs:\n    dim (int): Dimension of the frequency tensor.\n    pos (int or torch.FloatTensor): Position indices for the frequency tensor. [S] or scalar\n    theta (float, optional): Scaling factor for frequency computation. Defaults to 10000.0.\n    use_real (bool, optional): If True, return real part and imaginary part separately.\n                               Otherwise, return complex numbers.\n    theta_rescale_factor (float, optional): Rescale factor for theta. Defaults to 1.0.\n\nReturns:\n    freqs_cis: Precomputed frequency tensor with complex exponential. [S, D/2]\n    freqs_cos, freqs_sin: Precomputed frequency tensor with real and imaginary parts separately. [S, D]", "kind": "function", "line": 281, "name": "get_1d_rotary_pos_embed", "signature": "def get_1d_rotary_pos_embed(dim, pos, theta, use_real, theta_rescale_factor, interpolation_factor)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/ssta_attention.py", "kind": "module", "label": "ssta_attention.py", "language": "py", "sha256": "8146083b4fcabc42", "symbol_count": 11, "symbols": [{"doc": "Rearrange tensor into tiles for block-based attention.\n\nArgs:\n    x: Input tensor with shape (b, head, s, d) where s = t * h * w\n    canvas_thw: Tuple of (t, h, w) representing temporal, height, width dimensions\n    tile_thw: Tuple of (tile_t, tile_h, tile_w) representing tile dimensions\n    sp_size: Spatial size parameter, defaults to 1\n\nReturns:\n    Rearranged tensor organized by tiles", "kind": "function", "line": 23, "name": "tile", "signature": "def tile(x, canvas_thw, tile_thw, sp_size)"}, {"doc": "Reverse the tiling operation to restore original tensor layout.\n\nArgs:\n    x: Tiled tensor\n    canvas_thw: Tuple of (t, h, w) representing temporal, height, width dimensions\n    tile_thw: Tuple of (tile_t, tile_h, tile_w) representing tile dimensions\n    sp_size: Spatial size parameter, defaults to 1\n\nReturns:\n    Restored tensor with original layout", "kind": "function", "line": 53, "name": "untile", "signature": "def untile(x, canvas_thw, tile_thw, sp_size)"}, {"doc": "Extract temporal, height, and width indices from a flattened tile ID.", "kind": "function", "line": 82, "name": "get_tile_t_h_w", "signature": "def get_tile_t_h_w(tile_id, tile_thw_dim)"}, {"doc": "Select top-k blocks based on importance scores considering both similarity and redundancy.\n\nArgs:\n    q: Query tensor with shape (B, H, S, D)\n    k: Key tensor with shape (B, H, K, D)\n    topk: Number of top blocks to select\n    threshold: Threshold parameter (not implemented)\n    lambda_: Weight factor balancing similarity and redundancy\n    adaptive_pool: Adaptive pooling parameter (unused)\n\nReturns:\n    top_block_indices: Indices of selected blocks with shape (B, H, S, topk)", "kind": "function", "line": 90, "name": "importance_sampling", "signature": "def importance_sampling(q, k, topk, threshold, lambda_, adaptive_pool)"}, {"doc": "Select top-k blocks based on similarity scores between query and key averages.\n\nArgs:\n    q: Query tensor with shape (B, H, S, D)\n    k: Key tensor with shape (B, H, K, D)\n    topk: Number of top blocks to select\n    threshold: Cumulative score threshold for dynamic topk selection\n    block_num: Total number of blocks (unused)\n    adaptive_pool: Adaptive pooling parameter (unused)\n    temperature: Temperature scaling for softmax\n\nReturns:\n    top_block_indices: Indices of selected blocks with shape (B, H, S, topk)", "kind": "function", "line": 126, "name": "similarity_sampling", "signature": "def similarity_sampling(q, k, topk, threshold, block_num, adaptive_pool, temperature)"}, {"doc": "Create MOBA (Mixture of Block Attention) 3D mask for sparse attention.\n\nArgs:\n    q: Query tensor\n    k: Key tensor\n    canvas_thw: Canvas dimensions (t, h, w)\n    topk: Number of top blocks to attend to\n    tile_thw: Tile dimensions\n    kernel_thw: Kernel dimensions\n    text_block_num: Number of text blocks\n    add_text_mask: Whether to add text mask\n    threshold: Threshold for similarity sampling\n    lambda_: Weight factor for importance sampling\n    mask_share_within_head: Whether to share mask across heads\n    q_block_avg_pool: Whether to apply average pooling to query blocks\n    adaptive_pool: Adaptive pooling size\n    sampling_type: Type of sampling (\"similarity\" or \"importance\")\n\nReturns:\n    moba_3d_mask: 3D attention mask with shape (num_heads, block_num, block_num)", "kind": "function", "line": 170, "name": "create_moba_3d_mask", "signature": "def create_moba_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, add_text_mask, threshold, lambda_, mask_share_within_head, q_block_avg_pool, adaptive_pool, sampling_type)"}, {"doc": "Create optimized STA (Spatio-Temporal Attention) 3D mask using vectorized operations.\n\nArgs:\n    canvas_thw: String representation of canvas dimensions \"t_h_w\"\n    tile_thw: String representation of tile dimensions \"t_h_w\"\n    kernel_thw: String representation of kernel dimensions \"t_h_w\"\n\nReturns:\n    block_mask: Boolean mask tensor with shape (block_num, block_num)", "kind": "function", "line": 323, "name": "create_sta_3d_mask_optimize", "signature": "def create_sta_3d_mask_optimize(canvas_thw, tile_thw, kernel_thw)"}, {"doc": "Create STA (Spatio-Temporal Attention) 3D mask.\n\nArgs:\n    canvas_thw: Canvas dimensions (t, h, w)\n    tile_thw: Tile dimensions\n    kernel_thw: Kernel dimensions\n    text_block_num: Number of text blocks to pad\n\nReturns:\n    sta_mask: Boolean mask tensor with optional text block padding", "kind": "function", "line": 374, "name": "create_sta_3d_mask", "signature": "def create_sta_3d_mask(canvas_thw, tile_thw, kernel_thw, text_block_num)"}, {"doc": "Create SSTA (Sparse Spatio-Temporal Attention) 3D mask combining STA and MOBA masks.\n\nArgs:\n    q: Query tensor\n    k: Key tensor\n    canvas_thw: Canvas dimensions (t, h, w)\n    topk: Number of top blocks to attend to\n    tile_thw: Tile dimensions\n    kernel_thw: Kernel dimensions\n    text_block_num: Number of text blocks\n    threshold: Threshold for similarity sampling\n    lambda_: Weight factor for importance sampling\n    text_mask: Optional text mask tensor\n    mask_share_within_head: Whether to share mask across heads\n    adaptive_pool: Adaptive pooling size\n    sampling_type: Type of sampling (\"similarity\" or \"importance\")\n\nReturns:\n    ssta_3d_mask: Combined 3D attention mask", "kind": "function", "line": 404, "name": "create_ssta_3d_mask", "signature": "def create_ssta_3d_mask(q, k, canvas_thw, topk, tile_thw, kernel_thw, text_block_num, threshold, lambda_, text_mask, mask_share_within_head, adaptive_pool, sampling_type)"}, {"doc": "Sparse Spatio-Temporal Attention (SSTA) 3D attention mechanism.\n\nArgs:\n    all_q: Query tensor with shape (B, H, S, D)\n    all_k: Key tensor with shape (B, H, S, D)\n    all_v: Value tensor with shape (B, H, S, D)\n    canvas_thw: Canvas dimensions (t, h, w)\n    topk: Number of top blocks to attend to\n    tile_thw: Tile dimensions\n    kernel_thw: Kernel dimensions\n    text_len: Length of text sequence\n    sparse_type: Type of sparse attention ('sta', 'block_attn', or 'ssta')\n    threshold: Threshold for similarity sampling\n    lambda_: Weight factor for importance sampling\n    pad_type: Padding type (\"zero\" or \"repeat\")\n    text_mask: Optional text mask tensor\n    mask_share_within_head: Whether to share mask across heads\n    sampling_type: Type of sampling (\"similarity\" or \"importance\")\n    adaptive_pool: Adaptive pooling size\n\nReturns:\n    tuple: (output tensor, sparse_ratio)\n        - output: Attention output with shape (B, H, S, D)\n        - sparse_ratio: Ratio of non-zero attention weights", "kind": "function", "line": 465, "name": "ssta_3d_attention", "signature": "def ssta_3d_attention(all_q, all_k, all_v, canvas_thw, topk, tile_thw, kernel_thw, text_len, sparse_type, threshold, lambda_, pad_type, text_mask, mask_share_within_head, sampling_type, adaptive_pool)"}, {"kind": "function", "line": 216, "name": "get_block_avg_feat", "signature": "def get_block_avg_feat(x, adaptive_pool, pooling_type)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/token_refiner.py", "kind": "module", "label": "token_refiner.py", "language": "py", "sha256": "800df4c0f0879bcb", "symbol_count": 9, "symbols": [{"doc": "A single block for token refinement with self-attention and MLP.\n\nArgs:\n    hidden_size: Hidden dimension size.\n    heads_num: Number of attention heads.\n    mlp_width_ratio: Expansion ratio for MLP hidden size.\n    mlp_drop_rate: Dropout rate for MLP.\n    act_type: Activation function type.\n    qk_norm: Whether to use QK normalization.\n    qk_norm_type: Type of QK normalization.\n    qkv_bias: Whether to use bias in QKV projections.\n    dtype: Optional torch dtype.\n    device: Optional torch device.", "kind": "class", "line": 33, "name": "IndividualTokenRefinerBlock", "signature": "class IndividualTokenRefinerBlock(Module)"}, {"doc": "Stacks multiple IndividualTokenRefinerBlock modules.\n\nArgs:\n    hidden_size: Hidden dimension size.\n    heads_num: Number of attention heads.\n    depth: Number of blocks.\n    mlp_width_ratio: Expansion ratio for MLP hidden size.\n    mlp_drop_rate: Dropout rate for MLP.\n    act_type: Activation function type.\n    qk_norm: Whether to use QK normalization.\n    qk_norm_type: Type of QK normalization.\n    qkv_bias: Whether to use bias in QKV projections.\n    dtype: Optional torch dtype.\n    device: Optional torch device.", "kind": "class", "line": 127, "name": "IndividualTokenRefiner", "signature": "class IndividualTokenRefiner(Module)"}, {"doc": "Single token refiner block for LLM text embedding refinement.\n\nArgs:\n    in_channels: Input feature dimension.\n    hidden_size: Hidden dimension size.\n    heads_num: Number of attention heads.\n    depth: Number of blocks.\n    mlp_width_ratio: Expansion ratio for MLP hidden size.\n    mlp_drop_rate: Dropout rate for MLP.\n    act_type: Activation function type.\n    qk_norm: Whether to use QK normalization.\n    qk_norm_type: Type of QK normalization.\n    qkv_bias: Whether to use bias in QKV projections.\n    dtype: Optional torch dtype.\n    device: Optional torch device.", "kind": "class", "line": 203, "name": "SingleTokenRefiner", "signature": "class SingleTokenRefiner(Module)"}, {"kind": "method", "line": 50, "name": "__init__", "signature": "def __init__(self, hidden_size, heads_num, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)"}, {"doc": "Forward pass for IndividualTokenRefinerBlock.\n\nArgs:\n    x: Input tensor of shape [B, L, C].\n    c: Conditioning tensor of shape [B, C].\n    attn_mask: Optional attention mask of shape [B, L].\n\nReturns:\n    Refined tensor of shape [B, L, C].", "kind": "method", "line": 98, "name": "forward", "signature": "def forward(self, x, c, attn_mask)"}, {"kind": "method", "line": 145, "name": "__init__", "signature": "def __init__(self, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)"}, {"doc": "Forward pass for IndividualTokenRefiner.\n\nArgs:\n    x: Input tensor of shape [B, L, C].\n    c: Conditioning tensor of shape [B, C].\n    mask: Optional mask tensor of shape [B, L].\n\nReturns:\n    Refined tensor of shape [B, L, C].", "kind": "method", "line": 178, "name": "forward", "signature": "def forward(self, x, c, mask)"}, {"kind": "method", "line": 222, "name": "__init__", "signature": "def __init__(self, in_channels, hidden_size, heads_num, depth, mlp_width_ratio, mlp_drop_rate, act_type, qk_norm, qk_norm_type, qkv_bias, dtype, device)"}, {"doc": "Forward pass for SingleTokenRefiner.\n\nArgs:\n    x: Input tensor of shape [B, L, in_channels].\n    t: Timestep tensor of shape [B].\n    mask: Optional mask tensor of shape [B, L].\n\nReturns:\n    Refined tensor of shape [B, L, hidden_size].", "kind": "method", "line": 256, "name": "forward", "signature": "def forward(self, x, t, mask)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/transformers/modules/upsample.py", "kind": "module", "label": "upsample.py", "language": "py", "sha256": "c1d58b87d2303088", "symbol_count": 11, "symbols": [{"kind": "class", "line": 38, "name": "UpsamplerType", "signature": "class UpsamplerType(Enum)"}, {"kind": "class", "line": 46, "name": "UpsamplerConfig", "signature": "class UpsamplerConfig"}, {"kind": "class", "line": 55, "name": "SRResidualCausalBlock3D", "signature": "class SRResidualCausalBlock3D(Module)"}, {"kind": "class", "line": 70, "name": "SRTo720pUpsampler", "signature": "class SRTo720pUpsampler(ModelMixin, ConfigMixin)"}, {"kind": "class", "line": 100, "name": "SRTo1080pUpsampler", "signature": "class SRTo1080pUpsampler(ModelMixin, ConfigMixin)"}, {"kind": "method", "line": 56, "name": "__init__", "signature": "def __init__(self, channels)"}, {"kind": "method", "line": 66, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 73, "name": "__init__", "signature": "def __init__(self, in_channels, out_channels, hidden_channels, num_blocks, global_residual)"}, {"kind": "method", "line": 89, "name": "forward", "signature": "def forward(self, x)"}, {"kind": "method", "line": 103, "name": "__init__", "signature": "def __init__(self, z_channels, out_channels, block_out_channels, num_res_blocks, is_residual)"}, {"doc": "Args:\n    z: (B, C, T, H, W)\n    target_shape: (H, W)", "kind": "method", "line": 137, "name": "forward", "signature": "def forward(self, z, target_shape)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/models/vision_encoder/__init__.py", "kind": "module", "label": "__init__.py", "language": "py", "sha256": "03eb7b1120fa9591", "symbol_count": 11, "symbols": [{"kind": "function", "line": 29, "name": "use_default", "signature": "def use_default(value, default)"}, {"kind": "function", "line": 33, "name": "load_vision_encoder", "signature": "def load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)"}, {"kind": "function", "line": 63, "name": "load_image_processor", "signature": "def load_image_processor(processor_type, processor_path, logger)"}, {"doc": "Base class for vision encoder model's outputs.\n\nArgs:\n    last_hidden_state (`torch.FloatTensor` of shape `(batch_size, sequence_length, hidden_size)`):\n        Sequence of hidden-states at the output of the last layer of the model.\n    pooler_output (`torch.FloatTensor` of shape `(batch_size, hidden_size)`, *optional*):\n        Last layer hidden-state of the first token of the sequence (classification token)\n        after further processing through the layers used for the auxiliary pretraining task.\n    hidden_states (`tuple(torch.FloatTensor)`, *optional*, returned when `output_hidden_states=True` is passed):\n        Tuple of `torch.FloatTensor` (one for the output of the embeddings, if the model has an embedding layer, +\n        one for the output of each layer) of shape `(batch_size, sequence_length, hidden_size)`.\n        Hidden-states of the model at the output of each layer plus the optional initial embedding outputs.", "kind": "class", "line": 83, "name": "VisionEncoderModelOutput", "signature": "class VisionEncoderModelOutput(ModelOutput)"}, {"kind": "class", "line": 104, "name": "VisionEncoder", "signature": "class VisionEncoder(Module)"}, {"kind": "method", "line": 105, "name": "__init__", "signature": "def __init__(self, vision_encoder_type, vision_encoder_precision, vision_encoder_path, processor_type, processor_path, output_key, logger, device)"}, {"kind": "method", "line": 149, "name": "__repr__", "signature": "def __repr__(self)"}, {"doc": "Convert latents to images using VAE decoder.\n\nArgs:\n    latents: Input latents tensor\n    vae: VAE model for decoding\n    reorg_token: Whether to reorg the token\nReturns:\n    images: Decoded images as numpy array", "kind": "method", "line": 152, "name": "encode_latents_to_images", "signature": "def encode_latents_to_images(self, latents, vae, reorg_token)"}, {"doc": "Encode images using the vision encoder.\n\nArgs:\n    images: Input images (numpy array or preprocessed tensor)\n    \nReturns:\n    VisionEncoderModelOutput with encoded features", "kind": "method", "line": 179, "name": "encode_images", "signature": "def encode_images(self, images)"}, {"doc": "Encode latents by first converting to images, then encoding.\nThis is the main function that replaces sigclip_vision_encode.\n\nArgs:\n    latents: Input latent tensors\n    vae: VAE model for decoding latents to images\n    \nReturns:\n    Encoded image features", "kind": "method", "line": 205, "name": "encode_latents", "signature": "def encode_latents(self, latents, vae, reorg_token)"}, {"doc": "Forward pass for direct image encoding.\n\nArgs:\n    images: Input images\n    \nReturns:\n    VisionEncoderModelOutput with encoded features", "kind": "method", "line": 225, "name": "forward", "signature": "def forward(self, images)"}]}, {"id": "hyvideo/optim/muon.py", "kind": "module", "label": "muon.py", "language": "py", "sha256": "3b89f2c087990d3b", "symbol_count": 6, "symbols": [{"doc": "Newton-Schulz iteration to compute the zeroth power / orthogonalization of G. We opt to use a\nquintic iteration whose coefficients are selected to maximize the slope at zero. For the purpose\nof minimizing steps, it turns out to be empirically effective to keep increasing the slope at\nzero even beyond the point where the iteration no longer converges all the way to one everywhere\non the interval. This iteration therefore does not produce UV^T but rather something like US'V^T\nwhere S' is diagonal with S_{ii}' ~ Uniform(0.5, 1.5), which turns out not to hurt model\nperformance at all relative to UV^T, where USV^T = G is the SVD.", "kind": "function", "line": 17, "name": "zeropower_via_newtonschulz5", "signature": "def zeropower_via_newtonschulz5(G, steps)"}, {"doc": "Muon - MomentUm Orthogonalized by Newton-schulz\n\nArguments:\n    muon_params: The parameters to be optimized by Muon.\n    lr: The learning rate. The updates will have spectral norm of `lr`. (0.02 is a good default)\n    momentum: The momentum used by the internal SGD. (0.95 is a good default)\n    nesterov: Whether to use Nesterov-style momentum in the internal SGD. (recommended)\n    ns_steps: The number of Newton-Schulz iterations to run. (6 is probably always enough)\n    adamw_params: The parameters to be optimized by AdamW. Any parameters in `muon_params` which are\n    {0, 1}-D or are detected as being the embed or lm_head will be optimized by AdamW as well.\n    adamw_lr: The learning rate for the internal AdamW.\n    adamw_betas: The betas for the internal AdamW.\n    adamw_eps: The epsilon for the internal AdamW.\n    adamw_wd: The weight decay for the internal AdamW.", "kind": "class", "line": 54, "name": "Muon", "signature": "class Muon(Optimizer)"}, {"kind": "method", "line": 214, "name": "get_muon_optimizer", "signature": "def get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)"}, {"kind": "method", "line": 72, "name": "__init__", "signature": "def __init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)"}, {"kind": "method", "line": 108, "name": "adjust_lr_for_muon", "signature": "def adjust_lr_for_muon(self, lr, param_shape)"}, {"doc": "Perform a single optimization step.\n\nArgs:\n    closure (Callable, optional): A closure that reevaluates the model\n        and returns the loss.", "kind": "method", "line": 116, "name": "step", "signature": "def step(self, closure)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/pipelines/hunyuan_video_pipeline.py", "kind": "module", "label": "hunyuan_video_pipeline.py", "language": "py", "sha256": "887b788570164fed", "symbol_count": 43, "symbols": [{"kind": "class", "line": 82, "name": "HunyuanVideoPipelineOutput", "signature": "class HunyuanVideoPipelineOutput(BaseOutput)"}, {"kind": "class", "line": 87, "name": "HunyuanVideo_1_5_Pipeline", "signature": "class HunyuanVideo_1_5_Pipeline(DiffusionPipeline)"}, {"kind": "method", "line": 92, "name": "__init__", "signature": "def __init__(self, vae, text_encoder, transformer, scheduler, text_encoder_2, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)"}, {"kind": "method", "line": 185, "name": "_create_scheduler", "signature": "def _create_scheduler(cls, flow_shift)"}, {"kind": "method", "line": 194, "name": "_load_byt5", "signature": "def _load_byt5(cls, cached_folder, glyph_byT5_v2, byt5_max_length, device)"}, {"doc": "Encodes the prompt into text encoder hidden states.\n\nArgs:\n    prompt (`str` or `List[str]`, *optional*):\n        prompt to be encoded\n    device: (`torch.device`):\n        torch device\n    num_videos_per_prompt (`int`):\n        number of videos that should be generated per prompt\n    do_classifier_free_guidance (`bool`):\n        whether to use classifier free guidance or not\n    negative_prompt (`str` or `List[str]`, *optional*):\n        The prompt or prompts not to guide the video generation. If not defined, one has to pass\n        `negative_prompt_embeds` instead. Ignored when not using guidance (i.e., ignored if `guidance_scale` is\n        less than `1`).\n    prompt_embeds (`torch.Tensor`, *optional*):\n        Pre-generated text embeddings. Can be used to easily tweak text inputs, *e.g.* prompt weighting. If not\n        provided, text embeddings will be generated from `prompt` input argument.\n    attention_mask (`torch.Tensor`, *optional*):\n    negative_prompt_embeds (`torch.Tensor`, *optional*):\n        Pre-generated negative text embeddings. Can be used to easily tweak text inputs, *e.g.* prompt\n        weighting. If not provided, negative_prompt_embeds will be generated from `negative_prompt` input\n        argument.\n    negative_attention_mask (`torch.Tensor`, *optional*):\n        Attention mask for negative prompt embeddings.\n    clip_skip (`int`, *optional*):\n        Number of layers to be skipped from CLIP while computing the prompt embeddings. A value of 1 means that\n        the output of the pre-final layer will be used for computing the prompt embeddings.\n    text_encoder (TextEncoder, *optional*):\n        Text encoder to use. If None, uses the pipeline's default text encoder.\n    data_type (`str`, *optional*):\n        Type of data being encoded. Defaults to \"image\".", "kind": "method", "line": 242, "name": "encode_prompt", "signature": "def encode_prompt(self, prompt, device, num_videos_per_prompt, do_classifier_free_guidance, negative_prompt, prompt_embeds, attention_mask, negative_prompt_embeds, negative_attention_mask, clip_skip, text_encoder, data_type)"}, {"doc": "Prepare extra keyword arguments for scheduler functions.\n\nFilters kwargs to only include parameters that the function accepts.\nThis is useful since not all schedulers have the same signature.", "kind": "method", "line": 413, "name": "prepare_extra_func_kwargs", "signature": "def prepare_extra_func_kwargs(self, func, kwargs)"}, {"doc": "Prepare latents for video generation.\n\nArgs:\n    batch_size: Batch size for generation.\n    num_channels_latents: Number of channels in latent space.\n    latent_height: Height of latent tensors.\n    latent_width: Width of latent tensors.\n    video_length: Number of frames in the video.\n    dtype: Data type for latents.\n    device: Target device for latents.\n    generator: Random number generator.\n    latents: Pre-computed latents. If None, random latents are generated.\n\nReturns:\n    torch.Tensor: Prepared latents tensor.", "kind": "method", "line": 429, "name": "prepare_latents", "signature": "def prepare_latents(self, batch_size, num_channels_latents, latent_height, latent_width, video_length, dtype, device, generator, latents)"}, {"doc": "See https://github.com/google-research/vdm/blob/dc27b98a554f65cdc654b800da5aa1846545d41b/model_vdm.py#L298\n\nArgs:\n    w (`torch.Tensor`):\n        Generate embedding vectors with a specified guidance scale to subsequently enrich timestep embeddings.\n    embedding_dim (`int`, *optional*, defaults to 512):\n        Dimension of the embeddings to generate.\n    dtype (`torch.dtype`, *optional*, defaults to `torch.float32`):\n        Data type of the generated embeddings.\n\nReturns:\n    `torch.Tensor`: Embedding vectors with shape `(len(w), embedding_dim)`.", "kind": "method", "line": 483, "name": "get_guidance_scale_embedding", "signature": "def get_guidance_scale_embedding(self, w, embedding_dim, dtype)"}, {"kind": "method", "line": 517, "name": "guidance_scale", "signature": "def guidance_scale(self)"}, {"kind": "method", "line": 521, "name": "guidance_rescale", "signature": "def guidance_rescale(self)"}, {"kind": "method", "line": 525, "name": "clip_skip", "signature": "def clip_skip(self)"}, {"kind": "method", "line": 532, "name": "do_classifier_free_guidance", "signature": "def do_classifier_free_guidance(self)"}, {"kind": "method", "line": 536, "name": "cross_attention_kwargs", "signature": "def cross_attention_kwargs(self)"}, {"kind": "method", "line": 540, "name": "num_timesteps", "signature": "def num_timesteps(self)"}, {"kind": "method", "line": 544, "name": "interrupt", "signature": "def interrupt(self)"}, {"doc": "Tokenize text prompt for byT5 model.\n\nArgs:\n    byt5_tokenizer: The byT5 tokenizer.\n    byt5_max_length: Maximum sequence length for tokenization.\n    text_prompt: Text prompt string to tokenize.\n\nReturns:\n    tuple[torch.Tensor, torch.Tensor]:\n        - input_ids: Tokenized input IDs.\n        - attention_mask: Attention mask tensor.", "kind": "method", "line": 548, "name": "get_byt5_text_tokens", "signature": "def get_byt5_text_tokens(byt5_tokenizer, byt5_max_length, text_prompt)"}, {"doc": "Extract glyph texts from prompt using regex pattern.\n\nArgs:\n    prompt: Input prompt string containing quoted text.\n\nReturns:\n    List[str]: List of extracted glyph texts (deduplicated if multiple).", "kind": "method", "line": 573, "name": "_extract_glyph_texts", "signature": "def _extract_glyph_texts(self, prompt)"}, {"doc": "Process a single prompt for byT5 encoding.\n\nArgs:\n    prompt_text: The prompt text to process.\n    device: Target device for tensors.\n\nReturns:\n    tuple[torch.Tensor, torch.Tensor]:\n        - byt5_embeddings: Encoded embeddings tensor.\n        - byt5_mask: Attention mask tensor.", "kind": "method", "line": 589, "name": "_process_single_byt5_prompt", "signature": "def _process_single_byt5_prompt(self, prompt_text, device)"}, {"doc": "Prepare byT5 embeddings for both positive and negative prompts.\n\nArgs:\n    prompts: List of prompt strings or single prompt string.\n    device: Target device for tensors.\n\nReturns:\n    dict: Dictionary containing:\n        - \"byt5_text_states\": Combined embeddings tensor.\n        - \"byt5_text_mask\": Combined attention mask tensor.\n        Returns empty dict if glyph_byT5_v2 is disabled.", "kind": "method", "line": 623, "name": "_prepare_byt5_embeddings", "signature": "def _prepare_byt5_embeddings(self, prompts, device)"}, {"doc": "Extract features from a reference image using VisionEncoder.\n\nArgs:\n    reference_image: numpy array of shape (H, W, 3) with dtype uint8.\n\nReturns:\n    VisionEncoderModelOutput: Encoded image features.", "kind": "method", "line": 680, "name": "extract_image_features", "signature": "def extract_image_features(self, reference_image)"}, {"doc": "Prepare vision states for multitask training.\n\nArgs:\n    reference_image: Reference image for i2v tasks (None for t2v tasks).\n    target_resolution: Target size for i2v tasks.\n    latents: Latent tensors.\n    device: Target device.\n\nReturns:\n    torch.Tensor or None: Vision states tensor or None if vision encoder is unavailable.", "kind": "method", "line": 698, "name": "_prepare_vision_states", "signature": "def _prepare_vision_states(self, reference_image, target_resolution, latents, device)"}, {"doc": "Prepare conditional latents and mask for multitask training.\n\nArgs:\n    task_type: Type of task (\"i2v\" or \"t2v\").\n    cond_latents: Conditional latents tensor.\n    latents: Main latents tensor.\n    multitask_mask: Multitask mask tensor.\n\nReturns:\n    tuple[torch.Tensor, torch.Tensor]:\n        - latents_concat: Concatenated conditional latents.\n        - mask_concat: Concatenated mask tensor.", "kind": "method", "line": 734, "name": "_prepare_cond_latents", "signature": "def _prepare_cond_latents(self, task_type, cond_latents, latents, multitask_mask)"}, {"kind": "method", "line": 766, "name": "get_task_mask", "signature": "def get_task_mask(self, task_type, latent_target_length)"}, {"doc": "Get closest supported resolution for a reference image.\n\nArgs:\n    reference_image: PIL Image or numpy array.\n    target_resolution: Target resolution string (e.g., \"720p\", \"1080p\").\n\nReturns:\n    tuple[int, int]: (height, width) of closest supported resolution.", "kind": "method", "line": 776, "name": "get_closest_resolution_given_reference_image", "signature": "def get_closest_resolution_given_reference_image(self, reference_image, target_resolution)"}, {"doc": "Get closest supported resolution for given original size and target resolution.\n\nArgs:\n    origin_size: Tuple of (width, height) of original image.\n    target_size: Target resolution string (e.g., \"720p\", \"1080p\").\n\nReturns:\n    tuple[int, int]: (height, width) of closest supported resolution.", "kind": "method", "line": 800, "name": "get_closest_resolution_given_original_size", "signature": "def get_closest_resolution_given_original_size(self, origin_size, target_size)"}, {"kind": "method", "line": 826, "name": "get_image_condition_latents", "signature": "def get_image_condition_latents(self, task_type, reference_image, height, width)"}, {"kind": "method", "line": 861, "name": "vae_spatial_compression_ratio", "signature": "def vae_spatial_compression_ratio(self)"}, {"kind": "method", "line": 868, "name": "vae_temporal_compression_ratio", "signature": "def vae_temporal_compression_ratio(self)"}, {"kind": "method", "line": 874, "name": "get_latent_size", "signature": "def get_latent_size(self, video_length, height, width)"}, {"doc": "Generates a video (or videos) based on text (and optionally image) conditions.\n\nArgs:\n    prompt (`str` or `List[str]`):\n        Text prompt(s) to guide video generation.\n    aspect_ratio (`str`):\n        Output video aspect ratio as a string formatted like \"720:1280\" or \"16:9\". Required for text-to-video tasks.\n    video_length (`int`):\n        Number of frames in the generated video.\n    num_inference_steps (`int`, *optional*, defaults to 50):\n        Number of denoising steps during generation. Larger values may improve video quality at the expense of slower inference.\n    guidance_scale (`float`, *optional*, defaults to value in config):\n        Scale to encourage the model to better follow the prompt. `guidance_scale > 1` enables classifier-free guidance.\n    enable_sr (`bool`, *optional*, defaults to True):\n        Whether to apply super-resolution to the generated video.\n    sr_num_inference_steps (`int`, *optional*, defaults to 30):\n        Number of inference steps in the super-resolution module (if enabled).\n    negative_prompt (`str` or `List[str]`, *optional*):\n        Negative prompt(s) that describe what should NOT be shown in the generated video.\n    generator (`torch.Generator` or `List[torch.Generator]`, *optional*):\n        PyTorch random generator(s) for deterministic results.\n    seed (`int`, *optional*):\n        If specified, used to create the generator for reproducible sampling.\n    flow_shift (`float`, *optional*):\n        Flow shift parameter for the scheduler. Overrides the default pipeline configuration if provided.\n    embedded_guidance_scale (`float`, *optional*):\n        Additional control guidance scale, if supported.\n    reference_image (PIL.Image or `str`, *optional*):\n        Reference image for image-to-video (i2v) tasks. Can be a PIL image or a path to an image file. Set to `None` for text-to-video (t2v) generation.\n    output_type (`str`, *optional*, defaults to \"pt\"):\n        Output format of the returned video(s). Accepted values: `\"pt\"` for torch.Tensor or `\"np\"` for numpy.ndarray.\n    return_dict (`bool`, *optional*, defaults to True):\n        Whether to return a [`HunyuanVideoPipelineOutput`] or a tuple.\n    **kwargs:\n        Additional keyword arguments.\n\nReturns:\n    HunyuanVideoPipelineOutput or `tuple`:\n        If `return_dict` is True, returns a [`HunyuanVideoPipelineOutput`] with fields:\n            - `videos`: Generated video(s) as a tensor or numpy array.\n            - `sr_videos`: Super-resolved video(s) if `enable_sr` is True, else None.\n        Otherwise, returns a tuple containing the outputs as above.\n\nExample:\n    ```python\n    pipe = HunyuanVideoPipeline.from_pretrained(\"your_model_dir\")\n    # Text-to-video\n    video = pipe(prompt=\"A dog surfing on the beach\", aspect_ratio=\"9:16\", video_length=32).videos\n    # Image-to-video\n    video = pipe(prompt=\"Make this image move\", reference_image=\"img.jpg\", aspect_ratio=\"16:9\", video_length=24).videos\n    ```", "kind": "method", "line": 886, "name": "__call__", "signature": "def __call__(self, prompt, aspect_ratio, video_length, prompt_rewrite, num_inference_steps, guidance_scale, enable_sr, sr_num_inference_steps, negative_prompt, generator, seed, flow_shift, embedded_guidance_scale, reference_image, output_type, return_dict, return_pre_sr_video, enable_vae_tile_parallelism)"}, {"kind": "method", "line": 1324, "name": "ideal_resolution", "signature": "def ideal_resolution(self)"}, {"kind": "method", "line": 1328, "name": "ideal_task", "signature": "def ideal_task(self)"}, {"kind": "method", "line": 1332, "name": "use_meanflow", "signature": "def use_meanflow(self)"}, {"doc": "Apply inference optimizations to transformer based on infer_state.\n\nArgs:\n    infer_state: Optional InferState object containing optimization settings.\n    enable_offloading: Whether to enable CPU offloading.\n    enable_group_offloading: Whether to enable group offloading.\n    overlap_group_offloading: Whether to use overlapping group offloading.", "kind": "method", "line": 1335, "name": "apply_infer_optimization", "signature": "def apply_infer_optimization(self, infer_state, enable_offloading, enable_group_offloading, overlap_group_offloading)"}, {"kind": "method", "line": 1416, "name": "load_sr_transformer_upsampler", "signature": "def load_sr_transformer_upsampler(cls, cached_folder, sr_version, transformer_dtype, device)"}, {"kind": "method", "line": 1426, "name": "create_sr_pipeline", "signature": "def create_sr_pipeline(self, cached_folder, sr_version, transformer_dtype, device)"}, {"kind": "method", "line": 1452, "name": "get_transformer_version", "signature": "def get_transformer_version(resolution, task, cfg_distilled, step_distilled, sparse_attn)"}, {"kind": "method", "line": 1467, "name": "create_pipeline", "signature": "def create_pipeline(cls, pretrained_model_name_or_path, transformer_version, create_sr_pipeline, transformer_dtype, device, transformer_init_device)"}, {"kind": "method", "line": 1550, "name": "get_offloading_config", "signature": "def get_offloading_config(memory_limitation)"}, {"kind": "method", "line": 1566, "name": "get_vae_inference_config", "signature": "def get_vae_inference_config(memory_limitation)"}, {"kind": "method", "line": 1582, "name": "_load_text_encoders", "signature": "def _load_text_encoders(cls, pretrained_model_path, device)"}, {"kind": "method", "line": 1607, "name": "_load_vision_encoder", "signature": "def _load_vision_encoder(cls, pretrained_model_name_or_path, device)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/pipelines/hunyuan_video_sr_pipeline.py", "kind": "module", "label": "hunyuan_video_sr_pipeline.py", "language": "py", "sha256": "02574115e498e03a", "symbol_count": 10, "symbols": [{"kind": "function", "line": 42, "name": "expand_dims", "signature": "def expand_dims(tensor, ndim)"}, {"doc": "Maps low-resolution bucket sizes to corresponding high-resolution bucket sizes.", "kind": "class", "line": 46, "name": "BucketMap", "signature": "class BucketMap"}, {"kind": "class", "line": 81, "name": "HunyuanVideo_1_5_SR_PipelineOutput", "signature": "class HunyuanVideo_1_5_SR_PipelineOutput(BaseOutput)"}, {"kind": "class", "line": 85, "name": "HunyuanVideo_1_5_SR_Pipeline", "signature": "class HunyuanVideo_1_5_SR_Pipeline(HunyuanVideo_1_5_Pipeline)"}, {"kind": "method", "line": 49, "name": "__init__", "signature": "def __init__(self, lr_base_size, hr_base_size, lr_patch_size, hr_patch_size)"}, {"doc": "Args:\n    lr_bucket (tuple): Low-resolution bucket size as (width, height).\n\nReturns:\n    tuple: High-resolution bucket size as (width, height).", "kind": "method", "line": 62, "name": "__call__", "signature": "def __call__(self, lr_bucket)"}, {"kind": "method", "line": 87, "name": "__init__", "signature": "def __init__(self, vae, text_encoder, transformer, scheduler, upsampler, flow_shift, guidance_scale, num_inference_steps, embedded_guidance_scale, base_resolution, text_encoder_2, progress_bar_config, vision_num_semantic_tokens, vision_states_dim, glyph_byT5_v2, byt5_model, byt5_tokenizer, byt5_max_length, prompt_format, execution_device, vision_encoder, enable_offloading)"}, {"kind": "method", "line": 142, "name": "add_noise_to_lq", "signature": "def add_noise_to_lq(self, lq_latents, strength)"}, {"doc": "Prepare conditional latents and mask for multitask training.\n\nArgs:\n    lq_latents: Low-resolution latent tensor.\n\nReturns:\n    torch.Tensor: Low-resolution conditional latent tensor.", "kind": "method", "line": 148, "name": "_prepare_lq_cond_latents", "signature": "def _prepare_lq_cond_latents(self, lq_latents)"}, {"doc": "Runs the super-resolution (SR) pipeline for video generation.\n\nArgs:\n    prompt (`str` or `List[str]`):\n        Text prompt(s) that describe the desired video content.\n    video_length (`int`):\n        Number of frames in the video to generate.\n    num_inference_steps (`int`, *optional*, defaults to value in config):\n        Number of denoising steps during SR. Higher values may improve visual quality at the cost of slower inference.\n    guidance_scale (`float`, *optional*, defaults to value in config):\n        How closely to follow the prompt. `guidance_scale > 1` enables classifier-free guidance.\n    negative_prompt (`str` or `List[str]`, *optional*):\n        Prompt(s) of what should not appear in the generated video.\n    num_videos_per_prompt (`int`, *optional*, defaults to 1):\n        Number of videos to generate per prompt.\n    generator (`torch.Generator` or `List[torch.Generator]`, *optional*):\n        PyTorch random generator(s) for deterministic and reproducible results.\n    seed (`int`, *optional*):\n        If specified, used to construct a generator for reproducibility.\n    embedded_guidance_scale (`float`, *optional*):\n        Additional guidance scale for enhanced control, if model supports it.\n    reference_image (PIL.Image or `str`, *optional*):\n        Reference image for image-to-video (i2v) tasks. Can be a PIL image or local file path. Set to `None` for text-to-video (t2v) mode.\n    lq_latents (`torch.Tensor`, *optional*):\n        Low-quality (LQ) video latents to use as input for SR upsampling step. Should have shape (B, C, F, H, W).\n    output_type (`str`, *optional*, defaults to \"pt\"):\n        Output format, either `\"pt\"` (PyTorch tensor) or `\"np\"` (NumPy array).\n    return_dict (`bool`, *optional*, defaults to True):\n        Whether to return a [`HunyuanVideo_1_5_SR_PipelineOutput`] or a tuple.\n    **kwargs:\n        Additional keyword arguments.", "kind": "method", "line": 165, "name": "__call__", "signature": "def __call__(self, prompt, video_length, num_inference_steps, guidance_scale, negative_prompt, num_videos_per_prompt, generator, seed, embedded_guidance_scale, reference_image, lq_latents, output_type, return_dict, enable_vae_tile_parallelism)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/pipelines/pipeline_utils.py", "kind": "module", "label": "pipeline_utils.py", "language": "py", "sha256": "bfe35e3f4f774be8", "symbol_count": 2, "symbols": [{"doc": "Calls the scheduler's `set_timesteps` method and retrieves timesteps from the scheduler after the call. Handles\ncustom timesteps. Any kwargs will be supplied to `scheduler.set_timesteps`.\n\nArgs:\n    scheduler (`SchedulerMixin`):\n        The scheduler to get timesteps from.\n    num_inference_steps (`int`):\n        The number of diffusion steps used when generating samples with a pre-trained model. If used, `timesteps`\n        must be `None`.\n    device (`str` or `torch.device`, *optional*):\n        The device to which the timesteps should be moved to. If `None`, the timesteps are not moved.\n    timesteps (`List[int]`, *optional*):\n        Custom timesteps used to override the timestep spacing strategy of the scheduler. If `timesteps` is passed,\n        `num_inference_steps` and `sigmas` must be `None`.\n    sigmas (`List[float]`, *optional*):\n        Custom sigmas used to override the timestep spacing strategy of the scheduler. If `sigmas` is passed,\n        `num_inference_steps` and `timesteps` must be `None`.\n\nReturns:\n    `Tuple[torch.Tensor, int]`: A tuple where the first element is the timestep schedule from the scheduler and the\n    second element is the number of inference steps.", "kind": "function", "line": 21, "name": "retrieve_timesteps", "signature": "def retrieve_timesteps(scheduler, num_inference_steps, device, timesteps, sigmas)"}, {"doc": "Rescale `noise_cfg` according to `guidance_rescale`. Based on findings of [Common Diffusion Noise Schedules and\nSample Steps are Flawed](https://arxiv.org/pdf/2305.08891.pdf). See Section 3.4", "kind": "function", "line": 86, "name": "rescale_noise_cfg", "signature": "def rescale_noise_cfg(noise_cfg, noise_pred_text, guidance_rescale)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.  ============================================================================== Modified from diffusers ============================================================================== Copyright 2024 Stability AI, Katherine Crowson and The HuggingFace Team. All rights reserved.  Licensed under the Apache License, Version 2.0 (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  http://www.apache.org/licenses/LICENSE-2.0  Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an \"AS IS\" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.", "id": "hyvideo/schedulers/scheduling_flow_match_discrete.py", "kind": "module", "label": "scheduling_flow_match_discrete.py", "language": "py", "sha256": "1fd75fd328f2e229", "symbol_count": 16, "symbols": [{"doc": "Output class for the scheduler's `step` function output.\n\nArgs:\n    prev_sample (`torch.FloatTensor` of shape `(batch_size, num_channels, height, width)` for images):\n        Computed sample `(x_{t-1})` of previous timestep. `prev_sample` should be used as next model input in the\n        denoising loop.", "kind": "class", "line": 50, "name": "FlowMatchDiscreteSchedulerOutput", "signature": "class FlowMatchDiscreteSchedulerOutput(BaseOutput)"}, {"doc": "Euler scheduler.\n\nThis model inherits from [`SchedulerMixin`] and [`ConfigMixin`]. Check the superclass documentation for the generic\nmethods the library implements for all schedulers such as loading and saving.\n\nArgs:\n    num_train_timesteps (`int`, defaults to 1000):\n        The number of diffusion steps to train the model.\n    timestep_spacing (`str`, defaults to `\"linspace\"`):\n        The way the timesteps should be scaled. Refer to Table 2 of the [Common Diffusion Noise Schedules and\n        Sample Steps are Flawed](https://huggingface.co/papers/2305.08891) for more information.\n    shift (`float`, defaults to 1.0):\n        The shift value for the timestep schedule.\n    reverse (`bool`, defaults to `True`):\n        Whether to reverse the timestep schedule.", "kind": "class", "line": 63, "name": "FlowMatchDiscreteScheduler", "signature": "class FlowMatchDiscreteScheduler(SchedulerMixin, ConfigMixin)"}, {"kind": "method", "line": 86, "name": "__init__", "signature": "def __init__(self, num_train_timesteps, shift, reverse, solver, use_flux_shift, flux_base_shift, flux_max_shift, n_tokens, flux_base_token, flux_max_token, flux_shift_factor)"}, {"doc": "The index counter for current timestep. It will increase 1 after each scheduler step.", "kind": "method", "line": 119, "name": "step_index", "signature": "def step_index(self)"}, {"doc": "The index for the first timestep. It should be set from pipeline with `set_begin_index` method.", "kind": "method", "line": 126, "name": "begin_index", "signature": "def begin_index(self)"}, {"doc": "Sets the begin index for the scheduler. This function should be run from pipeline before the inference.\n\nArgs:\n    begin_index (`int`):\n        The begin index for the scheduler.", "kind": "method", "line": 133, "name": "set_begin_index", "signature": "def set_begin_index(self, begin_index)"}, {"kind": "method", "line": 143, "name": "_sigma_to_t", "signature": "def _sigma_to_t(self, sigma)"}, {"doc": "Sets the discrete timesteps used for the diffusion chain (to be run before inference).\n\nArgs:\n    num_inference_steps (`int`):\n        The number of diffusion steps used when generating samples with a pre-trained model.\n    device (`str` or `torch.device`, *optional*):\n        The device to which the timesteps should be moved to. If `None`, the timesteps are not moved.\n    n_tokens (`int`, *optional*):\n        Number of tokens in the input sequence.", "kind": "method", "line": 146, "name": "set_timesteps", "signature": "def set_timesteps(self, num_inference_steps, device, n_tokens)"}, {"kind": "method", "line": 182, "name": "index_for_timestep", "signature": "def index_for_timestep(self, timestep, schedule_timesteps)"}, {"kind": "method", "line": 196, "name": "_init_step_index", "signature": "def _init_step_index(self, timestep)"}, {"kind": "method", "line": 204, "name": "scale_model_input", "signature": "def scale_model_input(self, sample, timestep)"}, {"kind": "method", "line": 208, "name": "get_lin_function", "signature": "def get_lin_function(x1, y1, x2, y2)"}, {"kind": "method", "line": 214, "name": "flux_time_shift", "signature": "def flux_time_shift(mu, sigma, t)"}, {"kind": "method", "line": 217, "name": "sd3_time_shift", "signature": "def sd3_time_shift(self, t)"}, {"doc": "Predict the sample from the previous timestep by reversing the SDE. This function propagates the diffusion\nprocess from the learned model outputs (most often the predicted noise).\n\nArgs:\n    model_output (`torch.FloatTensor`):\n        The direct output from learned diffusion model.\n    timestep (`float`):\n        The current discrete timestep in the diffusion chain.\n    sample (`torch.FloatTensor`):\n        A current instance of a sample created by the diffusion process.\n    generator (`torch.Generator`, *optional*):\n        A random number generator.\n    n_tokens (`int`, *optional*):\n        Number of tokens in the input sequence.\n    return_dict (`bool`):\n        Whether or not to return a [`~schedulers.scheduling_euler_discrete.EulerDiscreteSchedulerOutput`] or\n        tuple.\n\nReturns:\n    [`~schedulers.scheduling_euler_discrete.EulerDiscreteSchedulerOutput`] or `tuple`:\n        If return_dict is `True`, [`~schedulers.scheduling_euler_discrete.EulerDiscreteSchedulerOutput`] is\n        returned, otherwise a tuple is returned where the first element is the sample tensor.", "kind": "method", "line": 220, "name": "step", "signature": "def step(self, model_output, timestep, sample, generator, n_tokens, return_dict)"}, {"kind": "method", "line": 291, "name": "__len__", "signature": "def __len__(self)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/communications.py", "kind": "module", "label": "communications.py", "language": "py", "sha256": "1fa43b63a36e7105", "symbol_count": 18, "symbols": [{"kind": "function", "line": 24, "name": "broadcast", "signature": "def broadcast(input_, group)"}, {"doc": "all-to-all for QKV\n\nArgs:\n    input (torch.tensor): a tensor sharded along dim scatter dim\n    scatter_idx (int): default 1\n    gather_idx (int): default 2\n    group : torch process group\n\nReturns:\n    torch.tensor: resharded tensor (bs, seqlen/P, hc, hs)", "kind": "function", "line": 29, "name": "_all_to_all_4D", "signature": "def _all_to_all_4D(input, scatter_idx, gather_idx, group)"}, {"kind": "class", "line": 147, "name": "SeqAllToAll4D", "signature": "class SeqAllToAll4D(Function)"}, {"kind": "method", "line": 174, "name": "all_to_all_4D", "signature": "def all_to_all_4D(input_, group, scatter_dim, gather_dim)"}, {"kind": "method", "line": 180, "name": "_all_to_all", "signature": "def _all_to_all(input_, world_size, group, scatter_dim, gather_dim)"}, {"doc": "All-to-all communication.\n\nArgs:\n    input_: input matrix\n    process_group: communication group\n    scatter_dim: scatter dimension\n    gather_dim: gather dimension", "kind": "class", "line": 195, "name": "_AllToAll", "signature": "class _AllToAll(Function)"}, {"kind": "method", "line": 233, "name": "all_to_all", "signature": "def all_to_all(input_, group, scatter_dim, gather_dim)"}, {"kind": "class", "line": 239, "name": "_Reduce_Scatter", "signature": "class _Reduce_Scatter(Function)"}, {"doc": "All-gather communication with autograd support.\n\nArgs:\n    input_: input tensor\n    dim: dimension along which to concatenate", "kind": "class", "line": 255, "name": "_AllGather", "signature": "class _AllGather(Function)"}, {"doc": "Performs an all-gather operation on the input tensor along the specified dimension.\n\nArgs:\n    input_ (torch.Tensor): Input tensor of shape [B, H, S, D].\n    dim (int, optional): Dimension along which to concatenate. Defaults to 1.\n\nReturns:\n    torch.Tensor: Output tensor after all-gather operation, concatenated along 'dim'.", "kind": "method", "line": 304, "name": "all_gather", "signature": "def all_gather(input_, dim, group)"}, {"kind": "method", "line": 149, "name": "forward", "signature": "def forward(ctx, group, input, scatter_idx, gather_idx)"}, {"kind": "method", "line": 163, "name": "backward", "signature": "def backward(ctx)"}, {"kind": "method", "line": 206, "name": "forward", "signature": "def forward(ctx, input_, process_group, scatter_dim, gather_dim)"}, {"kind": "method", "line": 217, "name": "backward", "signature": "def backward(ctx, grad_output)"}, {"kind": "method", "line": 242, "name": "forward", "signature": "def forward(ctx, op, group, tensor)"}, {"kind": "method", "line": 251, "name": "backward", "signature": "def backward(ctx, grad_output)"}, {"kind": "method", "line": 264, "name": "forward", "signature": "def forward(ctx, input_, dim, group)"}, {"kind": "method", "line": 283, "name": "backward", "signature": "def backward(ctx, grad_output)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/data_utils.py", "kind": "module", "label": "data_utils.py", "language": "py", "sha256": "47ee617fed1cdea3", "symbol_count": 3, "symbols": [{"kind": "function", "line": 20, "name": "resize_and_center_crop", "signature": "def resize_and_center_crop(image, target_width, target_height)"}, {"doc": "Get the closest ratio in the buckets.\n\nArgs:\n    height (float): video height\n    width (float): video width\n    ratios (list): video aspect ratio\n    buckets (list): buckets generated by `generate_crop_size_list`\n\nReturns:\n    the closest size in the buckets and the corresponding ratio", "kind": "function", "line": 38, "name": "get_closest_ratio", "signature": "def get_closest_ratio(height, width, ratios, buckets)"}, {"kind": "function", "line": 61, "name": "generate_crop_size_list", "signature": "def generate_crop_size_list(base_size, patch_size, max_ratio)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/flash_attn_no_pad.py", "kind": "module", "label": "flash_attn_no_pad.py", "language": "py", "sha256": "ff2e7bb2c59e57d2", "symbol_count": 2, "symbols": [{"kind": "function", "line": 20, "name": "flash_attn_no_pad", "signature": "def flash_attn_no_pad(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)"}, {"kind": "function", "line": 52, "name": "flash_attn_no_pad_v3", "signature": "def flash_attn_no_pad_v3(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/infer_utils.py", "kind": "module", "label": "infer_utils.py", "language": "py", "sha256": "26345913f81d9e83", "symbol_count": 3, "symbols": [{"kind": "function", "line": 19, "name": "torch_compile_wrapper", "signature": "def torch_compile_wrapper()"}, {"kind": "function", "line": 20, "name": "decorator", "signature": "def decorator(func)"}, {"kind": "function", "line": 21, "name": "wrapper", "signature": "def wrapper(self)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/multitask_utils.py", "kind": "module", "label": "multitask_utils.py", "language": "py", "sha256": "2a29b4672c456402", "symbol_count": 2, "symbols": [{"doc": "Convert a numpy image or a batch of images to a PIL image.\n\nArgs:\n    images (np.ndarray): The image array to convert to PIL format.\n\nReturns:\n    List[Image.Image]: A list of PIL images.", "kind": "function", "line": 23, "name": "numpy_to_pil", "signature": "def numpy_to_pil(images)"}, {"kind": "function", "line": 45, "name": "merge_tensor_by_mask", "signature": "def merge_tensor_by_mask(tensor_1, tensor_2, mask, dim)"}]}, {"doc": "-*- coding: utf-8 -*- Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/rewrite/clients.py", "kind": "module", "label": "clients.py", "language": "py", "sha256": "f64f7e575181a470", "symbol_count": 15, "symbols": [{"kind": "class", "line": 29, "name": "NonStreamResponse", "signature": "class NonStreamResponse(object)"}, {"kind": "class", "line": 37, "name": "DeepSeekClient", "signature": "class DeepSeekClient(object)"}, {"kind": "class", "line": 84, "name": "QwenClient", "signature": "class QwenClient(object)"}, {"kind": "class", "line": 133, "name": "QwenVLClient", "signature": "class QwenVLClient(object)"}, {"kind": "method", "line": 30, "name": "__init__", "signature": "def __init__(self)"}, {"kind": "method", "line": 33, "name": "_deserialize", "signature": "def _deserialize(self, obj)"}, {"kind": "method", "line": 38, "name": "__init__", "signature": "def __init__(self, key_id, key_secret)"}, {"kind": "method", "line": 51, "name": "run_single_recaption", "signature": "def run_single_recaption(self, system_prompt, input_prompt)"}, {"kind": "method", "line": 85, "name": "__init__", "signature": "def __init__(self, base_url, model_name)"}, {"doc": "Use Qwen Chat API to perform text rewriting, parse <think>...</think> sections for reasoning content, and return (thinking, result).", "kind": "method", "line": 90, "name": "qwen_api_call", "signature": "def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens)"}, {"kind": "method", "line": 128, "name": "run_single_recaption", "signature": "def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens)"}, {"kind": "method", "line": 135, "name": "__init__", "signature": "def __init__(self, base_url, model_name)"}, {"doc": "参考 hyvideo/utils/rewrite/qwen_vllm.py 的实现：\n加载本地图片，将其按比例缩放到 max_dimension，然后编码为 Base64 data URL。", "kind": "method", "line": 141, "name": "_encode_image_to_base64", "signature": "def _encode_image_to_base64(self, image_path, max_dimension)"}, {"doc": "Use Qwen3-VL to perform text rewriting.", "kind": "method", "line": 176, "name": "qwen_api_call", "signature": "def qwen_api_call(self, system_prompt, user_input, temperature, max_tokens, img_path)"}, {"kind": "method", "line": 246, "name": "run_single_recaption", "signature": "def run_single_recaption(self, system_prompt, input_prompt, temperature, max_tokens, img_path)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/rewrite/i2v_prompt.py", "kind": "module", "label": "i2v_prompt.py", "language": "py", "sha256": "0fdc0f768e99edca", "symbol_count": 0, "symbols": []}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/rewrite/rewrite_utils.py", "kind": "module", "label": "rewrite_utils.py", "language": "py", "sha256": "be275a6b5da2f5c6", "symbol_count": 3, "symbols": [{"kind": "function", "line": 22, "name": "t2v_rewrite", "signature": "def t2v_rewrite(user_prompt, rewrite_client)"}, {"doc": "Use a rewrite client to generate a rewritten prompt for image-to-video.", "kind": "function", "line": 40, "name": "i2v_rewrite", "signature": "def i2v_rewrite(user_input, img_path, rewrite_client)"}, {"kind": "function", "line": 63, "name": "run_prompt_rewrite", "signature": "def run_prompt_rewrite(user_prompt, img_path, task_type)"}]}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "hyvideo/utils/rewrite/t2v_prompt.py", "kind": "module", "label": "t2v_prompt.py", "language": "py", "sha256": "621542845949c9c5", "symbol_count": 0, "symbols": []}, {"doc": "Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the \"License\"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided \"AS IS\" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.", "id": "train.py", "kind": "module", "label": "train.py", "language": "py", "sha256": "dac41eef7520b562", "symbol_count": 45, "symbols": [{"kind": "class", "line": 91, "name": "SNRType", "signature": "class SNRType(str, Enum)"}, {"doc": "Convert string to boolean, supporting true/false, 1/0, yes/no.\nIf value is None (when flag is provided without value), returns True.", "kind": "method", "line": 98, "name": "str_to_bool", "signature": "def str_to_bool(value)"}, {"kind": "method", "line": 114, "name": "save_video", "signature": "def save_video(video, path)"}, {"kind": "class", "line": 124, "name": "TrainingConfig", "signature": "class TrainingConfig"}, {"doc": "Simple linear interpolation schedule for flow matching", "kind": "class", "line": 186, "name": "LinearInterpolationSchedule", "signature": "class LinearInterpolationSchedule"}, {"kind": "class", "line": 204, "name": "TimestepSampler", "signature": "class TimestepSampler"}, {"doc": "Transform timesteps with shift", "kind": "method", "line": 269, "name": "timestep_transform", "signature": "def timestep_transform(timesteps, T, shift)"}, {"kind": "method", "line": 278, "name": "is_src", "signature": "def is_src(src, group_src, group)"}, {"kind": "method", "line": 287, "name": "broadcast_object", "signature": "def broadcast_object(obj, src, group, device, group_src)"}, {"doc": "shape and dtype safe broadcast of tensor", "kind": "method", "line": 305, "name": "broadcast_tensor", "signature": "def broadcast_tensor(tensor, src, group, async_op, group_src)"}, {"doc": "Sync tensor within sequence parallel group.\nEnsures all ranks in the SP group have the same tensor values.", "kind": "method", "line": 333, "name": "sync_tensor_for_sp", "signature": "def sync_tensor_for_sp(tensor, sp_group)"}, {"kind": "class", "line": 347, "name": "HunyuanVideoTrainer", "signature": "class HunyuanVideoTrainer"}, {"doc": "Create a dummy dataloader for testing.\n\nNote: This is a placeholder - users should implement their own dataset and dataloader\nthat loads actual video/image data.\n\nRequired fields for Dataset __getitem__:\n- \"pixel_values\": torch.Tensor\n    * For video: shape [C, F, H, W] where F is the number of frames\n    * For image: shape [C, H, W]\n    * Pixel values must be in range [-1, 1]\n    * Data type: torch.float32\n    * Note: For video data, temporal dimension F must be 4n+1 (e.g., 1, 5, 9, 13, 17, 21, ...)\n      to satisfy VAE requirements. The dataset should ensure this before returning data.\n\n- \"text\": str\n    * Text prompt for this sample\n\n- \"data_type\": str\n    * \"video\" for video data (supports both t2v and i2v tasks based on i2v_prob)\n    * \"image\" for image data (always uses t2v task)\n\nOptional fields (for performance optimization):\n- \"latents\": torch.Tensor, shape [C_latent, F, H_latent, W_latent]\n    * Pre-encoded VAE latents. If provided, pixel_values will be ignored and VAE encoding\n      will be skipped, significantly speeding up training.\n    * Should be in the same format as VAE encoder output (after scaling_factor applied)\n    * Temporal dimension F must still be 4n+1 for video data\n\nOptional fields (for byT5 text encoding):\n- \"byt5_text_ids\": Optional[torch.Tensor], shape [seq_len]\n    * Pre-tokenized byT5 token IDs. If provided, will be used directly.\n    * If not provided, text will be tokenized on-the-fly.\n\n- \"byt5_text_mask\": Optional[torch.Tensor], shape [seq_len]\n    * Attention mask for byT5 tokens (1 for valid tokens, 0 for padding)\n    * Required if byt5_text_ids is provided\n\nTask type selection (automatic based on data_type and config.i2v_prob):\n- For \"video\" data: randomly samples between t2v (text-to-video) and i2v (image-to-video)\n  based on config.i2v_prob probability\n- For \"image\" data: always uses t2v task\n\nExample sample format (what dataset __getitem__ should return):\n{\n    \"pixel_values\": torch.Tensor([3, 121, 480, 848]),  # Video example\n    \"text\": \"A cat playing\",\n    \"data_type\": \"video\",\n    \"byt5_text_ids\": torch.Tensor([256]),  # Optional\n    \"byt5_text_mask\": torch.Tensor([256]),  # Optional\n}\n\nOr with pre-encoded latents (faster):\n{\n    \"latents\": torch.Tensor([32, 31, 30, 53]),  # Pre-encoded VAE latents\n    \"text\": \"A cat playing\",\n    \"data_type\": \"video\",\n}", "kind": "method", "line": 1047, "name": "create_dummy_dataloader", "signature": "def create_dummy_dataloader(config)"}, {"kind": "method", "line": 1144, "name": "main", "signature": "def main()"}, {"kind": "method", "line": 188, "name": "__init__", "signature": "def __init__(self, T)"}, {"doc": "Linear interpolation: x_t = (1 - t/T) * x0 + (t/T) * x1\nArgs:\n    x0: starting point (clean latents)\n    x1: ending point (noise)\n    t: timesteps", "kind": "method", "line": 191, "name": "forward", "signature": "def forward(self, x0, x1, t)"}, {"kind": "method", "line": 209, "name": "__init__", "signature": "def __init__(self, T, device, snr_type)"}, {"kind": "method", "line": 219, "name": "_check_interval", "signature": "def _check_interval(self, eval)"}, {"kind": "method", "line": 226, "name": "sample", "signature": "def sample(self, batch_size, device)"}, {"kind": "method", "line": 348, "name": "__init__", "signature": "def __init__(self, config)"}, {"kind": "method", "line": 406, "name": "_set_seed", "signature": "def _set_seed(self, seed)"}, {"kind": "method", "line": 412, "name": "_build_models", "signature": "def _build_models(self)"}, {"kind": "method", "line": 464, "name": "_apply_lora", "signature": "def _apply_lora(self)"}, {"kind": "method", "line": 498, "name": "_apply_fsdp", "signature": "def _apply_fsdp(self)"}, {"kind": "method", "line": 529, "name": "_apply_gradient_checkpointing", "signature": "def _apply_gradient_checkpointing(self)"}, {"kind": "method", "line": 565, "name": "_build_optimizer", "signature": "def _build_optimizer(self)"}, {"kind": "method", "line": 592, "name": "encode_text", "signature": "def encode_text(self, prompts, data_type)"}, {"kind": "method", "line": 608, "name": "encode_byt5", "signature": "def encode_byt5(self, text_ids, attention_mask)"}, {"doc": "Encode images to vision states (for i2v)", "kind": "method", "line": 615, "name": "encode_images", "signature": "def encode_images(self, images)"}, {"kind": "method", "line": 625, "name": "encode_vae", "signature": "def encode_vae(self, images)"}, {"kind": "method", "line": 641, "name": "get_condition", "signature": "def get_condition(self, latents, task_type)"}, {"doc": "Sample task type based on data type and configuration.\n\nFor video data: samples between t2v and i2v based on i2v_prob\nFor image data: always returns t2v (image-to-video generation)", "kind": "method", "line": 654, "name": "sample_task", "signature": "def sample_task(self, data_type)"}, {"doc": "Prepare batch for training.\n\nExpected batch format:\n{\n    \"pixel_values\": torch.Tensor, # [B, C, F, H, W] for video or [B, C, H, W] for image\n                                  # Pixel values must be in range [-1, 1] \n    \"text\": List[str],\n    \"data_type\": str,  # \"image\" or \"video\"\n    \"byt5_text_ids\": Optional[torch.Tensor],\n    \"byt5_text_mask\": Optional[torch.Tensor],\n}\n\nNote: For video data, the temporal dimension F must be 4n+1 (e.g., 1, 5, 9, 13, 17, ...)\nto satisfy VAE requirements. The dataset should ensure this before returning data.", "kind": "method", "line": 671, "name": "prepare_batch", "signature": "def prepare_batch(self, batch)"}, {"kind": "method", "line": 776, "name": "train_step", "signature": "def train_step(self, batch)"}, {"kind": "method", "line": 828, "name": "save_checkpoint", "signature": "def save_checkpoint(self, step)"}, {"kind": "method", "line": 892, "name": "load_pretrained_lora", "signature": "def load_pretrained_lora(self, lora_dir)"}, {"kind": "method", "line": 901, "name": "load_checkpoint", "signature": "def load_checkpoint(self, checkpoint_path)"}, {"kind": "method", "line": 959, "name": "train", "signature": "def train(self, dataloader)"}, {"doc": "Implement your own validation logic here\nAn example:\n\n\nlogger.info(f\"Running validation at step {step}...\")\n\nself.transformer.eval()\n\ntry:\n    for idx, prompt in enumerate(self.config.validation_prompts):\n        logger.info(f\"Generating validation video {idx+1}/{len(self.config.validation_prompts)}: {prompt[:50]}...\")\n        \n        with torch.no_grad():\n            output = self.pipeline(\n                prompt=prompt,\n                aspect_ratio=\"16:9\",\n                video_length=self.config.validate_video_length,\n                enable_sr=False,  # Disable SR for faster validation\n                prompt_rewrite=False,  # Disable prompt rewrite for faster validation\n                output_type=\"pt\",\n                seed=42,\n            )\n            \n            video_path = os.path.join(\n                self.validation_output_dir,\n                f\"step_{step:06d}_prompt_{idx:02d}.mp4\"\n            )\n            print(f\"Prompt: {prompt}\")\n            video_to_save = output.videos\n            if dist.get_rank() == 0:\n                save_video(video_to_save, video_path)\n                logger.info(f\"Validation video saved to {video_path}\")\n\nexcept Exception as e:\n    logger.error(f\"Error during validation: {e}\")\n    import traceback\n    logger.error(traceback.format_exc())\n\nfinally:\n    self.transformer.train()\npass", "kind": "method", "line": 1001, "name": "validate", "signature": "def validate(self, step)"}, {"kind": "class", "line": 1108, "name": "DummyDataset", "signature": "class DummyDataset"}, {"kind": "method", "line": 547, "name": "non_reentrant_wrapper", "signature": "def non_reentrant_wrapper(module)"}, {"kind": "method", "line": 553, "name": "selective_checkpointing", "signature": "def selective_checkpointing(submodule)"}, {"kind": "method", "line": 1109, "name": "__init__", "signature": "def __init__(self, size)"}, {"kind": "method", "line": 1112, "name": "__len__", "signature": "def __len__(self)"}, {"kind": "method", "line": 1115, "name": "__getitem__", "signature": "def __getitem__(self, idx)"}]}], "type": "CodePropertyGraph", "version": "1.0"}
```

---

## Architecture Reference

### PY (38 files)

#### `generate.py`
**Path:** `generate.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Functions:**
- `find_free_port` (line 25) `def find_free_port()`
- `__initialize_default_distributed_environment` (line 32) `def __initialize_default_distributed_environment()`

#### `__init__.py`
**Path:** `hyvideo/commons/__init__.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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

#### `infer_state.py`
**Path:** `hyvideo/commons/infer_state.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `InferState` (line 21) `class InferState`

**Methods:**
- `parse_range` (line 42) `def parse_range(value)`
- `initialize_infer_state` (line 49) `def initialize_infer_state(args)`
- `get_infer_state` (line 87) `def get_infer_state()`

#### `parallel_states.py`
**Path:** `hyvideo/commons/parallel_states.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `ParallelDims` (line 24) `class ParallelDims`

**Methods:**
- `initialize_parallel_state` (line 81) `def initialize_parallel_state(sp, dp_replicate)`
- `get_parallel_state` (line 89) `def get_parallel_state()`
- `__post_init__` (line 29) `def __post_init__(self)`
- `build_mesh` (line 37) `def build_mesh(self, device_type)`
- `sp_enabled` (line 68) `def sp_enabled(self)`
- `sp_mesh` (line 72) `def sp_mesh(self)`
- `dp_enabled` (line 76) `def dp_enabled(self)`

#### `__init__.py`
**Path:** `hyvideo/models/__init__.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

*No symbols extracted*

#### `__init__.py`
**Path:** `hyvideo/models/autoencoders/__init__.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

*No symbols extracted*

#### `hunyuanvideo_15_vae.py`
**Path:** `hyvideo/models/autoencoders/hunyuanvideo_15_vae.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `DecoderOutput` (line 40) `class DecoderOutput(BaseOutput)`
- `PatchCausalConv3d` (line 65) `class PatchCausalConv3d(Conv3d)` - *Causal Conv3d with efficient patch processing for large tensors.*
- `RMS_norm` (line 110) `class RMS_norm(Module)` - *Root Mean Square Layer Normalization for Channel-First or Last*
- `CausalConv3d` (line 129) `class CausalConv3d(Module)` - *Causal Conv3d with configurable padding for temporal axis.*
- `AttnBlock` (line 186) `class AttnBlock(Module)` - *Self-attention block for 3D video tensors.*
- `ResnetBlock` (line 219) `class ResnetBlock(Module)` - *ResNet-style block for 3D video tensors.*
- `Downsample` (line 251) `class Downsample(Module)`
- `Upsample` (line 293) `class Upsample(Module)` - *Hierarchical upsampling with temporal/ spatial support.*
- `Encoder` (line 331) `class Encoder(Module)` - *Hierarchical video encoder with temporal and spatial factorization.*
- `Decoder` (line 413) `class Decoder(Module)` - *Hierarchical video decoder with upsampling factories.*
- `AutoencoderKLConv3D` (line 495) `class AutoencoderKLConv3D(ModelMixin, ConfigMixin)` - *KL regularized 3D Conv VAE with advanced tiling and slicing strategies.*

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
- `TextEncoder` (line 154) `class TextEncoder(Module)`

**Functions:**
- `use_default` (line 32) `def use_default(value, default)` - *Utility: return value if not None, else default.*
- `load_text_encoder` (line 84) `def load_text_encoder(text_encoder_type, text_encoder_precision, text_encoder_path, logger, device)`
- `load_tokenizer` (line 114) `def load_tokenizer(tokenizer_type, tokenizer_path, padding_side, logger)`

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `ByT5Mapper` (line 187) `class ByT5Mapper(Module)` - *ByT5Mapper: Maps ByT5 encoder outputs to a new space, with optional residual connection.

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

**Methods:**
- `__init__` (line 199) `def __init__(self, in_dim, out_dim, hidden_dim, out_dim1, use_residual)`
- `forward` (line 210) `def forward(self, x)` - *Forward pass for ByT5Mapper.

Args:
    x (Tensor): Input tensor of shape (..., in_dim).

Returns:
    Tensor: Output tensor of shape (..., out_dim1).*

#### `format_prompt.py`
**Path:** `hyvideo/models/text_encoders/byT5/format_prompt.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `MultilingualPromptFormat` (line 44) `class MultilingualPromptFormat`

**Functions:**
- `closest_color` (line 20) `def closest_color(requested_color)`
- `convert_rgb_to_names` (line 34) `def convert_rgb_to_names(rgb_tuple)`

**Methods:**
- `__init__` (line 46) `def __init__(self, font_path, color_path)`
- `format_prompt` (line 56) `def format_prompt(self, texts, styles)` - *Text "{text}" in {color}, {type}.*

#### `hunyuanvideo_1_5_transformer.py`
**Path:** `hyvideo/models/transformers/hunyuanvideo_1_5_transformer.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `MMDoubleStreamBlock` (line 45) `class MMDoubleStreamBlock(Module)`
- `MMSingleStreamBlock` (line 208) `class MMSingleStreamBlock(Module)`
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

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Functions:**
- `get_activation_layer` (line 20) `def get_activation_layer(act_type)` - *get activation layer

Args:
    act_type (str): the activation type

Returns:
    torch.nn.functional: the activation layer*

#### `attention.py`
**Path:** `hyvideo/models/transformers/modules/attention.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `PatchEmbed` (line 23) `class PatchEmbed(Module)` - *2D Image to Patch Embedding

Image to Patch Embedding using Conv2d

A convolution based approach to patchifying a 2D image w/ embedding projection.

Based on the impl in https://github.com/google-research/vision_transformer

Hacked together by / Copyright 2020 Ross Wightman

Remove the _assert function in forward function to be compatible with multi-resolution images.*
- `TextProjection` (line 90) `class TextProjection(Module)` - *Projects text embeddings. Also handles dropout for classifier-free guidance.

Adapted from https://github.com/PixArt-alpha/PixArt-alpha/blob/master/diffusion/model/nets/PixArt_blocks.py*
- `VisionProjection` (line 122) `class VisionProjection(Module)`
- `ClipVisionProjection` (line 139) `class ClipVisionProjection(Module)`
- `TimestepEmbedder` (line 178) `class TimestepEmbedder(Module)` - *Embeds scalar timesteps into vector representations.*

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.  Modified from timm library: https://github.com/huggingface/pytorch-image-models/blob/648aaa41233ba83eb38faf5ba9d415d574823241/timm/layers/mlp.py#L13*

**Classes:**
- `MLP` (line 29) `class MLP(Module)` - *MLP as used in Vision Transformer, MLP-Mixer and related networks*
- `LinearWarpforSingle` (line 70) `class LinearWarpforSingle(Module)`
- `MLPEmbedder` (line 82) `class MLPEmbedder(Module)` - *copied from https://github.com/black-forest-labs/flux/blob/main/src/flux/modules/layers.py*
- `FinalLayer` (line 96) `class FinalLayer(Module)` - *The final layer of DiT.*

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `ModulateDiT` (line 23) `class ModulateDiT(Module)` - *Modulation layer for DiT.*

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `RMSNorm` (line 21) `class RMSNorm(Module)`

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `IndividualTokenRefinerBlock` (line 33) `class IndividualTokenRefinerBlock(Module)` - *A single block for token refinement with self-attention and MLP.

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
- `IndividualTokenRefiner` (line 127) `class IndividualTokenRefiner(Module)` - *Stacks multiple IndividualTokenRefinerBlock modules.

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
- `SingleTokenRefiner` (line 203) `class SingleTokenRefiner(Module)` - *Single token refiner block for LLM text embedding refinement.

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

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `UpsamplerType` (line 38) `class UpsamplerType(Enum)`
- `UpsamplerConfig` (line 46) `class UpsamplerConfig`
- `SRResidualCausalBlock3D` (line 55) `class SRResidualCausalBlock3D(Module)`
- `SRTo720pUpsampler` (line 70) `class SRTo720pUpsampler(ModelMixin, ConfigMixin)`
- `SRTo1080pUpsampler` (line 100) `class SRTo1080pUpsampler(ModelMixin, ConfigMixin)`

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
- `VisionEncoder` (line 104) `class VisionEncoder(Module)`

**Functions:**
- `use_default` (line 29) `def use_default(value, default)`
- `load_vision_encoder` (line 33) `def load_vision_encoder(vision_encoder_type, vision_encoder_precision, vision_encoder_path, logger, device)`
- `load_image_processor` (line 63) `def load_image_processor(processor_type, processor_path, logger)`

**Methods:**
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
- `Muon` (line 54) `class Muon(Optimizer)` - *Muon - MomentUm Orthogonalized by Newton-schulz

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

**Methods:**
- `get_muon_optimizer` (line 214) `def get_muon_optimizer(model, lr, weight_decay, momentum, adamw_betas, adamw_eps)`
- `__init__` (line 72) `def __init__(self, lr, wd, muon_params, momentum, nesterov, ns_steps, adamw_params, adamw_betas, adamw_eps)`
- `adjust_lr_for_muon` (line 108) `def adjust_lr_for_muon(self, lr, param_shape)`
- `step` (line 116) `def step(self, closure)` - *Perform a single optimization step.

Args:
    closure (Callable, optional): A closure that reevaluates the model
        and returns the loss.*

#### `hunyuan_video_pipeline.py`
**Path:** `hyvideo/pipelines/hunyuan_video_pipeline.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `HunyuanVideoPipelineOutput` (line 82) `class HunyuanVideoPipelineOutput(BaseOutput)`
- `HunyuanVideo_1_5_Pipeline` (line 87) `class HunyuanVideo_1_5_Pipeline(DiffusionPipeline)`

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `BucketMap` (line 46) `class BucketMap` - *Maps low-resolution bucket sizes to corresponding high-resolution bucket sizes.*
- `HunyuanVideo_1_5_SR_PipelineOutput` (line 81) `class HunyuanVideo_1_5_SR_PipelineOutput(BaseOutput)`
- `HunyuanVideo_1_5_SR_Pipeline` (line 85) `class HunyuanVideo_1_5_SR_Pipeline(HunyuanVideo_1_5_Pipeline)`

**Functions:**
- `expand_dims` (line 42) `def expand_dims(tensor, ndim)`

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.  ============================================================================== Modified from diffusers ============================================================================== Copyright 2024 Stability AI, Katherine Crowson and The HuggingFace Team. All rights reserved.  Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  http://www.apache.org/licenses/LICENSE-2.0  Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.*

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

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `SeqAllToAll4D` (line 147) `class SeqAllToAll4D(Function)`
- `_AllToAll` (line 195) `class _AllToAll(Function)` - *All-to-all communication.

Args:
    input_: input matrix
    process_group: communication group
    scatter_dim: scatter dimension
    gather_dim: gather dimension*
- `_Reduce_Scatter` (line 239) `class _Reduce_Scatter(Function)`
- `_AllGather` (line 255) `class _AllGather(Function)` - *All-gather communication with autograd support.

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

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Functions:**
- `flash_attn_no_pad` (line 20) `def flash_attn_no_pad(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`
- `flash_attn_no_pad_v3` (line 52) `def flash_attn_no_pad_v3(qkv, key_padding_mask, causal, dropout_p, softmax_scale, deterministic)`

#### `infer_utils.py`
**Path:** `hyvideo/utils/infer_utils.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Functions:**
- `torch_compile_wrapper` (line 19) `def torch_compile_wrapper()`
- `decorator` (line 20) `def decorator(func)`
- `wrapper` (line 21) `def wrapper(self)`

#### `multitask_utils.py`
**Path:** `hyvideo/utils/multitask_utils.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Functions:**
- `numpy_to_pil` (line 23) `def numpy_to_pil(images)` - *Convert a numpy image or a batch of images to a PIL image.

Args:
    images (np.ndarray): The image array to convert to PIL format.

Returns:
    List[Image.Image]: A list of PIL images.*
- `merge_tensor_by_mask` (line 45) `def merge_tensor_by_mask(tensor_1, tensor_2, mask, dim)`

#### `clients.py`
**Path:** `hyvideo/utils/rewrite/clients.py`
**File Doc:** *-*- coding: utf-8 -*- Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `NonStreamResponse` (line 29) `class NonStreamResponse(object)`
- `DeepSeekClient` (line 37) `class DeepSeekClient(object)`
- `QwenClient` (line 84) `class QwenClient(object)`
- `QwenVLClient` (line 133) `class QwenVLClient(object)`

**Methods:**
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
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

*No symbols extracted*

#### `rewrite_utils.py`
**Path:** `hyvideo/utils/rewrite/rewrite_utils.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Functions:**
- `t2v_rewrite` (line 22) `def t2v_rewrite(user_prompt, rewrite_client)`
- `i2v_rewrite` (line 40) `def i2v_rewrite(user_input, img_path, rewrite_client)` - *Use a rewrite client to generate a rewritten prompt for image-to-video.*
- `run_prompt_rewrite` (line 63) `def run_prompt_rewrite(user_prompt, img_path, task_type)`

#### `t2v_prompt.py`
**Path:** `hyvideo/utils/rewrite/t2v_prompt.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

*No symbols extracted*

#### `train.py`
**Path:** `train.py`
**File Doc:** *Licensed under the TENCENT HUNYUAN COMMUNITY LICENSE AGREEMENT (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5/blob/main/LICENSE  Unless and only to the extent required by applicable law, the Tencent Hunyuan works and any output and results therefrom are provided "AS IS" without any express or implied warranties of any kind including any warranties of title, merchantability, noninfringement, course of dealing, usage of trade, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using, reproducing, modifying, performing, displaying or distributing any of the Tencent Hunyuan works or outputs and assume any and all risks associated with your or a third party's use or distribution of any of the Tencent Hunyuan works or outputs and your exercise of rights and permissions under this agreement. See the License for the specific language governing permissions and limitations under the License.*

**Classes:**
- `SNRType` (line 91) `class SNRType(str, Enum)`
- `TrainingConfig` (line 124) `class TrainingConfig`
- `LinearInterpolationSchedule` (line 186) `class LinearInterpolationSchedule` - *Simple linear interpolation schedule for flow matching*
- `TimestepSampler` (line 204) `class TimestepSampler`
- `HunyuanVideoTrainer` (line 347) `class HunyuanVideoTrainer`
- `DummyDataset` (line 1108) `class DummyDataset`

**Methods:**
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
