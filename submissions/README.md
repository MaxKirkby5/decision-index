# Submissions

| Model | Edition | Decision Index | Complete results | Engine / commit | Hardware | Declared limits |
|---|---|---:|---|---|---|---|
| mammoth-1 ([`baselabs/mammoth-1`](https://huggingface.co/baselabs/mammoth-1) @ `b9f2f2c`) | 0.3 | 75.18 | [`runs/mammoth-1`](https://huggingface.co/datasets/baselabs/mammoth-1-decision-index/tree/f20c58a98994acebe353ae65af3a86b531809bb9/runs/mammoth-1) | in-process `engine:DecisionModel` (the repo's `engine.py`, OneJev `81ce62f` + `serve.patch`), kit `f5a6e4f` | 2 × 8 H200, one engine per GPU, one request at a time | 65,536 tokens per request; longer requests refused, never truncated; no options removed |
