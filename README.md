<h1 align="center">Kreyto</h1>
<h3 align="center">AI Researcher | Transformer Architect | TEKNOFEST Finalist | Istanbul, Turkey</h3>

---

### Research

**Parallel Hybrid Architecture (PHA)** | Submitted to ECML PKDD [[Paper]](#)

Hybrid architecture for long-context language modeling that runs GSS (Gated State Spaces), GQA (Grouped Query Attention), and FFN as parallel branches fused through a learnable mixing mechanism. Instead of forcing SSMs to approximate attention or stacking them sequentially, PHA lets each branch specialize: GSS handles global context via linear-time state propagation, attention handles selective token retrieval, and the mixer learns per-layer how much to rely on each.

Results at 90M/125M/180M scales on WikiText-103 and OpenWebText:
- 125M: 16.51 PPL on WikiText-103, beating Hedgehog (16.70) and H3-125M (23.70)
- 180M: 16.42 PPL, matching pure attention while delivering 24% higher throughput and up to 40% lower memory at long contexts
- 125M on OpenWebText: 19.72 PPL with only 23% of the training tokens used by baselines, outperforming standard Transformers (20.60) and GSS hybrids (19.80)

Ablations showed a "Sandwich" specialization pattern in the learned mixing weights: GSS dominates near input/output layers for global context, attention peaks in middle layers for retrieval. Parallel composition beat sequential stacking even with identical components, and the architecture maintained consistent results across multiple seeds.

**TEKNOFEST 2026 Healthcare AI** | ECG Classification

12-lead ECG classification into Normal, Rhythm Disorders, and Conduction Disorders on 81K recordings merged from 5 PhysioNet sources. Final system: TransformerCNN v5 (25M) + XResNet v4.1 SE (12M) ensemble via max confidence strategy, macro F1 0.8606. Trained 18 models across 6 architecture families (Transformer-CNN hybrids, XResNet, DualPath, pure Transformer, BiMamba/SSM, Spectrogram), tested 44 ensemble configurations.

---

### What I Work With

- Hybrid SSM-Transformer architectures (GSS, Mamba, S4, Hyena, learnable mixing strategies)
- Transformer design (ViT, Swin-UNETR, UAV-DETR, GQA, RoPE, FlashAttention)
- Medical signal/image processing (ECG classification, polyp segmentation, brain tumor detection)
- PyTorch, MONAI, deep learning optimization

---

### Contact

`kuzeytorlak@gmail.com`

<p align="left">
  <a href="https://twitter.com/kreytorn" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="kreytorn" height="20" width="30" />
  </a>
  <a href="https://instagram.com/kzytorlak" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="kzytorlak" height="20" width="30" />
  </a>
  <a href="https://www.youtube.com/c/kreytornkreyto" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="kreytornkreyto" height="20" width="30" />
  </a>
</p>

---

### Tech Stack

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" height="30" alt="PyTorch" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="30" alt="Jupyter" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="30" alt="NumPy" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="30" alt="Pandas" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" height="30" alt="OpenCV" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="30" alt="VSCode" />
</p>

---

### GitHub Stats

<p align="left">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kreytorn&theme=dark" alt="Streak Stats" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kreytorn&theme=dark&layout=compact" alt="Top Languages" />
</p>
