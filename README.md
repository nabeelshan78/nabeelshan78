<div align="center">
  <h1>Nabeel Shan</h1>
  <p>
    <strong>AI/ML Researcher & Engineer</strong> | B.E. Software Engineering @ <strong>NUST ('27)</strong>
  </p>
  <p>
    <strong>MITACS Globalink Research Intern</strong> @ University of Calgary
  </p>
  <p>
    Applied and theoretical machine learning — from raw NumPy backpropagation to multi-agent systems.
  </p>
  <p>
    Seeking a <strong>thesis-based MSc for Fall 2027</strong> — efficient adaptation and inference,
    RL for reasoning, agentic systems.
  </p>

  <div>
    <a href="https://nabeelshan.vercel.app/" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=react&logoColor=white" height="28" alt="Portfolio"/>
    </a>
    <a href="https://nabeelshan.vercel.app/cv" target="_blank">
      <img src="https://img.shields.io/badge/CV-4B5563?style=for-the-badge&logoColor=white" height="28" alt="CV"/>
    </a>
    <a href="https://www.linkedin.com/in/nabeelshan/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="28" alt="LinkedIn"/>
    </a>
    <a href="mailto:nabeelshan468@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="28" alt="Gmail"/>
    </a>
  </div>
</div>

---

### Research Focus

Building deep learning systems that are **efficient, reliable, and verifiable** enough for real-world and safety-critical deployment.

* **Efficient Adaptation & Inference** — PEFT (LoRA, Adapters), quantization, knowledge distillation
* **Alignment & Reinforcement Learning** — RLHF, PPO, GRPO, reward modeling, reward-hacking mitigation
* **Vision-Language & Multimodal Models** — VLM adaptation, visual grounding, semantic segmentation
* **Agentic Systems & Retrieval** — multi-agent orchestration, structured outputs, verifiable RAG

I build architectures from first principles before reaching for abstractions — Transformers, CNNs, RNNs, and PEFT modules implemented and validated from scratch.

---

### Currently

**MITACS Globalink Research Intern**, University of Calgary — Schulich School of Engineering

Architecting four parallel VLM adaptation pipelines over Qwen3-VL (2B/4B/8B) via two-phase LoRA SFT → GRPO on an H100/H200 SLURM cluster, to measure whether multi-task output helps or hurts each sub-task.

Most of that time has gone into reward design rather than training. Under flat true-negative constants, never predicting a rare class turned out to be *mathematically optimal* — a break-even IoU of 1.55, above the attainable maximum of 1.0 — so the policy was being paid to stay silent, and nothing in the training loop would have flagged it. I re-derived the constants from measured class prevalence and added a regression guard, one of 576 CPU-only tests, that fails the build whenever a degenerate policy outscores an honest one.

---

### Selected Work

| Project | Focus | Stack |
|---|---|---|
| [**Transformer Adaptation Playbook**](https://github.com/nabeelshan78/Transformer-Adaptation-Playbook) | Adapters & LoRA built from the papers' math; 5 adaptation strategies benchmarked — Adapters match full FT at 92% fewer params | PyTorch |
| [**Attention Is All You Need**](https://github.com/nabeelshan78/attention-is-all-you-need-scratch) | 63M-param Transformer verified at tensor, gradient, and memory-pointer level; exact analytic parameter count | PyTorch |
| [**RLHF from Scratch**](https://github.com/nabeelshan78/reinforcement-learning-human-feedback-scratch) | 3-stage alignment pipeline (SFT → RM → PPO), 98% reward-model accuracy, +54% mean reward | PyTorch, TRL, QLoRA |
| [**First-Principles Deep Learning**](https://github.com/nabeelshan78/First-Principles-Deep-Learning) | DNN, CNN, RNN in raw NumPy — no autograd, BPTT and optimizers derived by hand | NumPy |
| [**PixelSense**](https://github.com/nabeelshan78/pixelsense-ai-segmentation) | U-Net from scratch, no pretrained backbone, 23-class segmentation, 0.908 val mIoU | TensorFlow/Keras |
| [**ResearchFlow**](https://github.com/nabeelshan78/researchflow-multiagent-research-assistant) | Cyclical 4-agent system with self-correcting validation and HITL interrupts | LangGraph, Llama-3 |

---

### Stack

**Languages** `Python` `C++` `SQL` `Bash`  
**Deep Learning** `PyTorch` `TensorFlow/Keras` `Hugging Face` `NumPy` `Scikit-learn`  
**LLM & Agents** `Transformers` `PEFT/LoRA` `TRL` `LangChain` `LangGraph` `RAG`  
**Infrastructure** `Docker` `AWS` `SLURM` `FastAPI` `Weights & Biases` `Git` `Linux`

---

### Experience

* **Research Intern** — MITACS Globalink, University of Calgary *(Jul 2026 – Present)*
* **AI Engineer (Contract)** — DeepDocs AI, France *(Nov 2025 – Jan 2026)*
* **Quantum-AI Research Intern** — CETQAP *(Jun 2025 – Aug 2025)*
* **AI/ML Intern** — Software Productivity Strategists *(Apr 2025 – May 2025)*

---
