<h1 align="center">Kreyto</h1>
<h3 align="center">AI Researcher | Transformer Architect | TEKNOFEST Finalist | Istanbul, Turkey</h3>

---

### Research

**Parallel Hybrid Architecture (PHA)** | Submitted to ECML PKDD

Hybrid architecture for long-context language modeling. Runs GSS (Gated State Spaces), GQA, and FFN as parallel branches fused through learnable mixing, so each branch specializes instead of forcing SSMs to approximate attention or stacking them sequentially. Evaluated at 90M/125M/180M parameter scales on WikiText-103 and OpenWebText. 125M model hits 16.51 PPL on WikiText-103 (vs Hedgehog 16.70, H3 23.70), 180M matches pure attention quality with 24% higher throughput and up to 40% lower memory at long contexts. Ablations revealed a "Sandwich" pattern where GSS dominates boundary layers for global context while attention peaks in middle layers for retrieval.

**TEKNOFEST 2026 Healthcare AI** | ECG Classification

12-lead ECG classification (Normal / Rhythm Disorders / Conduction Disorders) on 81K recordings from 5 PhysioNet sources. TransformerCNN v5 + XResNet v4.1 SE ensemble, macro F1 0.8606. Trained 18 models across 6 architecture families, tested 44 ensemble configs.

**TUBİTAK 2204-A** | AI-Assisted Exam Evaluation

AI system for grading open-ended handwritten exams. Preprocessing pipeline (background removal, perspective correction, super-resolution), InternVL2-26B for text extraction, BERT-based Turkish diacritic restoration, rubric-based LLM scoring. Improved correlation with teacher scores from r=0.23 to r=0.89.

**NASA Space Apps 2025** | ExoHunter

Multi-method exoplanet detection combining transit photometry, radial velocity, astrometry, microlensing, and direct imaging. 2nd place locally at Gebze Technical University, selected as global nominee.

---

### Other

- Instructor at inzva Deep Learning Study Group, teaching Transformers
- Koç University summer research program (Medical LLMs, 2024)
- Leading AI & Robotics club at school
- Competed in ISBO Computer Science Olympiad

---

### Interests

- State Space Models, hybrid SSM-Transformer design, learnable mixing strategies
- Positional encoding (RoPE, ALiBi, relative position biases)
- Attention variants (GQA, linear attention, sparse attention, FlashAttention)
- Efficient long-context architectures, scaling laws at small parameter budgets

### Worked With

PHA hybrid architecture, ECG classification ensemble, handwritten exam grading (InternVL2 + BERT), exoplanet detection (ExoHunter), brain tumor detection (ViT), polyp segmentation (UNETR), Minecraft anti-cheat (movement pattern recognition), UAV object detection, breast cancer mammogram classification, custom LLM training, GAN-based synthetic data generation

---

### Contact

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
