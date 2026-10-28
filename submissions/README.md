# Submissions

| Model | Edition | Decision Index | Complete results | Engine / commit | Hardware | Declared limits |
|---|---|---:|---|---|---|---|
| joey-1 ([`baselabs/joey-1`](https://huggingface.co/baselabs/joey-1) @ `3903da0`) | 0.3 | 63.30 | [`runs/joey-1`](https://huggingface.co/datasets/baselabs/joey-1-decision-index/tree/2ca6211587fa65b7c89c570d8c286b784b51610f/runs/joey-1) | in-process `engine:DecisionModel` (the repo's `engine.py`, OneJev `81ce62f` + `serve.patch`), kit `f5a6e4f` | 1 × 8 H100 80GB, one engine per GPU, one request at a time | 65,536 tokens per request; longer requests refused, never truncated; no options removed |
