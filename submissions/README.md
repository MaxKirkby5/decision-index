# Submissions

| Model | Edition | Decision Index | Complete results | Engine / commit | Hardware | Declared limits |
|---|---|---:|---|---|---|---|
| elephant-1 ([`baselabs/elephant-1`](https://huggingface.co/baselabs/elephant-1) @ `14537f0`) | 0.3 | 72.24 | [`runs/elephant-1`](https://huggingface.co/datasets/baselabs/elephant-1-decision-index/tree/5b9623a47c47014d3e2def0fa9aa0c15eb8abc56/runs/elephant-1) | in-process `engine:DecisionModel` (the repo's `engine.py`, OneJev `81ce62f` + `serve.patch`), kit `f5a6e4f` | 2 × 8 H100 80GB, one engine per GPU, one request at a time | 65,536 tokens per request; longer requests refused, never truncated; no options removed |
