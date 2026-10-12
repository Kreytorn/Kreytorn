# I work on sequence models: state space models, Transformer attention and hybrids of the two.

### Paper

**[Long-Context Modeling via GSS-Transformer Hybrid Architecture with Learnable Mixing](https://arxiv.org/abs/2606.16093)**

arXiv preprint, June 2026. First of five authors.

Self-attention scales quadratically with sequence length, while state space models scale linearly but struggle to retrieve precise information from their compressed state. The model runs a state space branch (Gated State Spaces), an attention branch and a feed-forward branch in parallel and learns how to mix them. At 180M parameters its WikiText-103 perplexity is comparable to the pure-attention baseline, with 24% higher throughput and up to 40% lower memory usage at long contexts.

### Other work

- **12-lead ECG classification** (team lead). An ensemble of 44 networks, mostly state space models, averaged 50/50 with the pretrained ECGFounder model. 0.90 macro-F1 on a self-run, pre-registered external test set of 4,707 ECGs.
- **Real-time UAV perception** (team lead). Detects objects in every frame, estimates position by visual odometry when GNSS drops out, and finds objects shown in reference photos.
- **Turkish dense retrieval** (team member, inzva AI Projects #10, ongoing). A benchmark that tests whether dense retrievers catch the meaning of one Turkish suffix.

### Interests

SSM-Transformer hybrids, attention variants and positional encoding. Outside architecture: skill rating and outcome prediction, biosignals and medical ML.
