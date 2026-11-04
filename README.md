# Dataset: Reading-The-Prompt-Back
 
Generated videos used in **"Reading the Prompt Back: Detecting Prompt-Consistency Hallucinations in Text-to-Video Generation"** (WACV 2027).
 
**Hugging Face:** https://huggingface.co/datasets/trustworthy-engineered-autonomy-lab/Reading-prompts-back
 
## Contents
 
Videos from two text-to-video models, all generated with **seed 42**:
 
| Folder | Model | Benchmark | Videos |
|---|---|---|---|
| `t2v_hunyuan` | HunyuanVideo | T2V-CompBench | 1400 |
| `t2v_wan` | Wan 2.1 | T2V-CompBench | 1400 |
| `vibe_hunyuan` | HunyuanVideo | ViBe | 704 |
| `vibe_wan` | Wan 2.1 | ViBe | 704 |
 
Total: 4,208 videos (about 7.9 GB). The text prompts are in `prompts/`, and human labels for the videos can be found in `labels/`.
