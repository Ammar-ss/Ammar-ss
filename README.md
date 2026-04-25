# Ammar Bhilwarawala

**Undergraduate ML researcher** @ KIIT University · CGPA 9.03/10

I build things at the edge of medical image segmentation, uncertainty-aware deep learning, and agentic clinical AI. My work tends to start with a clinical problem that doesn't have a clean solution, and end with something that actually measures up against state-of-the-art. Currently in my third year, already with one published paper (Best Paper Award, ANTIC 2025) and several under review at MICCAI 2026 and Elsevier journals.

---

## Research

> All work is first-authored unless noted.

**[FETALFusion](https://github.com/Ammar-ss/My_U-Net_Model_variations)** · *Under Review at MICCAI 2026*
Dual-path CNN-Mamba encoder with resolution-aware state-space scanning for multi-domain fetal ultrasound segmentation. DSC = 0.9635, HD95 = 1.07 mm on 472 validation images. HD95 std 3.2× lower than VM-UNet.

**[Attention-ResUNet for Fetal Head Segmentation](https://github.com/Ammar-ss/My_U-Net_Model_variations)** · *Published at ANTIC 2025 (Springer LNCS)* · 🏆 Best Paper, Image Processing Track
Multi-scale attention gates + residual skip connections. DSC = 99.30 ± 0.14% on HC18 (n=200). Zero false-negative segmentations. 23 ms inference on RTX 3080.

**[BRIDGE + TCH-Net](https://github.com/Ammar-ss/-YVOO-for-Credit-Scoring-Fraud-Mitigation)** · *Under Review at JNCA (Elsevier)* · 📦 [Model](https://huggingface.co/Ammar-ss/BRIDGE_and_TCH-Net) · 📊 [Dataset](https://huggingface.co/datasets/Ammar-ss/BRIDGE) · 📄 [Preprint](https://huggingface.co/papers/2604.11324)
First formally-specified leave-one-domain-out generalisation benchmark for IoT botnet detection across 5 heterogeneous datasets (CICIDS-2017, CIC-IoT-2023, Bot-IoT, Edge-IIoTset, N-BaIoT). TCH-Net achieves F1 = 0.8296, AUC = 0.9380. **Invited by Niels Rogge (Lead ML Engineer, Hugging Face)** to host artifacts on the Hub; commended by the HF team for advancing reproducibility in IoT security research.

**[AdaptiMed](https://github.com/Ammar-ss)** · *Technical Report*
Extended MedAgent-Pro (ICLR 2026) with guideline-grounded adaptive agentic diagnosis. +24 pp category accuracy, +26 pp broad accuracy on REFUGE2 fundus cases. −25.7% tool calls per case.

**[FETALFusion-v2](https://github.com/Ammar-ss/My_U-Net_Model_variations)** · *In Preparation at Medical Image Analysis (Elsevier)*
Single-network dual-decoder CNN-Mamba for simultaneous binary segmentation + Gaussian landmark heatmaps (BPD, OFD, PS, FH). Trained on >10k images across 5 public datasets.

**[CAGED](https://github.com/Ammar-ss)** · *Work in Progress*
Replacing heuristic early-exit gates in agentic diagnosis with principled Dirichlet posteriors. Guideline-RAG threshold retrieval (EGS 2020, ACC/AHA, WHO ICD-11) enables cross-domain transfer without retraining.

**[GPR-DE Architecture for Seismic Control of a Benchmark Cable-Stayed Bridge](https://github.com/Ammar-ss)** · Under Review at Journal of Vibration Engineering & Technologies (Springer) · 2nd Author
GPR surrogate (Matérn 5/2, ARD) on 91 FEA simulations achieving LOOCV R² > 0.999; DE with UCB acquisition (κ=1.0) yielded 45% reduction in peak deck displacement under near-fault motions at ~1000× speedup over direct NLTHA-based optimisation.



---

## Skills

**ML / Deep Learning** — PyTorch, scikit-learn, NumPy, Pandas, XGBoost, GPR, SciPy
**Architectures** — U-Net variants, Attention mechanisms, State Space Models (Mamba), BiGRU/LSTM, DS-Conv
**Agentic / LLM** — LLM orchestration, RAG pipelines, tool-use agentic workflows, Groq API
**Research tooling** — LaTeX, Weights & Biases, TensorBoard, Grad-CAM, UMAP/t-SNE, Jupyter
**Languages** — Python, Java, C, SQL, Bash
**Infrastructure** — Git, Linux, Docker

---

## Recognition

- 🏆 **Best Paper Award** in Image Processing Track, ANTIC 2025 (Springer LNCS)
- 🇮🇳 **National Finalist** at Smart India Hackathon 2025, KIIT University nominee
- 🤗 **Invited Contributor** at Hugging Face Hub (approached by Lead ML Engineer Niels Rogge); TCH-Net checkpoints, BRIDGE benchmark, and interactive Demo Space publicly released

---

## What I'm Looking For

Research Assistant / Internship positions in **medical AI**, **uncertainty quantification**, or **data-driven computational modelling**. Open to lab collaborations, especially those working at the intersection of clinical relevance and methodological rigour.

---

## Get in Touch

📬 ammarbhilwarawala@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/ammar-bww) · [Hugging Face](https://huggingface.co/Ammar-ss) · [Kaggle](https://kaggle.com/ammarbhilwarawala) · [Resume](https://drive.google.com/file/d/1-nYz_Jh647ffEowdqI215mtPx-tyfHsk/view?usp=drive_link)

> *Open to a conversation about almost anything — drop a mail.*
