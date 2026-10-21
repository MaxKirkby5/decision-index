# Submissions

| Model | Edition | Decision Index | Complete results | Engine / commit | Hardware | Declared limits |
|---|---|---:|---|---|---|---|
| mammoth-1 ([`baselabs/mammoth-1`](https://huggingface.co/baselabs/mammoth-1) @ `9d1962f`) | 0.3 | 75.34 | [`runs/mammoth-1`](https://huggingface.co/datasets/baselabs/mammoth-1-decision-index/tree/32ddc7a7726402db0fedc12fe5663e2f9499a366/runs/mammoth-1) | in-process `engine:DecisionModel` (the repo's `engine.py`, OneJev `81ce62f` + `serve.patch`), kit `f5a6e4f` | 2 × 8 H200, one engine per GPU, one request at a time | 65,536 tokens per request; longer requests refused, never truncated; no options removed |
