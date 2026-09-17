<div align="center">
  <h1>Nabeel Shan</h1>
  <p>
    <strong>AI/ML Researcher & Engineer</strong> · B.E. Software Engineering @ <strong>NUST ('27)</strong>
  </p>
  <p>
    <strong>MITACS Globalink Research Intern</strong> @ University of Calgary - Schulich School of Engineering
  </p>
  <p>
    Seeking a thesis-based MSc for <strong>Fall 2027</strong>.
  </p>

  <div>
    <a href="https://nabeelshan.vercel.app/" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=react&logoColor=white" height="28" alt="Portfolio"/>
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

### Research

I work on large language and vision-language models that reason better and cost less to run.

> Most of what I do comes down to one question: **where the compute goes.** We can spend it
> after pretraining with reinforcement learning, save it with efficient adaptation and
> compression, or spend it at inference - letting a model think longer, call a tool, or hand off
> to another agent. And we need evaluation we can trust to know whether any of it worked,
> because the failures that matter here rarely raise an error.

| | |
|---|---|
| **Post-Training & Reinforcement Learning** | RLHF, RL with verifiable rewards, GRPO/GSPO, preference optimisation, reward modelling and reward design |
| **Efficient Adaptation & Inference** | Parameter-efficient fine-tuning, quantization, and distillation |
| **Test-Time Compute & Agentic Systems** | Inference-time scaling, verification and self-correction loops, multi-agent orchestration, and tool use |
| **Evaluation & Trustworthy Systems** | Reward hacking, hallucination, silent capability loss, and evaluation |

I build architectures from first principles before reaching for abstractions - Transformers,
CNNs, RNNs and PEFT modules implemented and validated from scratch.

---

### Currently
>
**MITACS Globalink Research Intern, University of Calgary - Schulich School of Engineering**
>
> Four parallel VLM adaptation pipelines over Qwen3-VL at **2B, 4B and 8B** - captioning,
> object grounding, safety-violation reasoning, and all three jointly - two-phase LoRA SFT
> -> GRPO against verifiable, code-computed rewards on an H100 SLURM cluster. A
> single-variable design: does multi-task output help or hurt each sub-task, and does the
> answer change with model size?
>
> Running alongside it, an accuracy-latency-cost comparison across the three scales and a
> multi-agent tier - finding where the capability gain stops paying for the inference.

---

### Selected Work

| Project | Focus | Stack |
|---|---|---|
| [**RLHF from Scratch**](https://github.com/nabeelshan78/reinforcement-learning-human-feedback-scratch) | 3-stage alignment pipeline (SFT -> RM -> PPO), 98% reward-model accuracy, +54% mean reward | PyTorch, TRL, QLoRA |
| [**Transformer Adaptation Playbook**](https://github.com/nabeelshan78/Transformer-Adaptation-Playbook) | Adapters & LoRA built from the papers' math; 5 adaptation strategies benchmarked - Adapters match full FT at 92% fewer params | PyTorch |
| [**Attention Is All You Need**](https://github.com/nabeelshan78/attention-is-all-you-need-scratch) | 63M-param Transformer verified at tensor, gradient, and memory-pointer level; exact analytic parameter count | PyTorch |
| [**First-Principles Deep Learning**](https://github.com/nabeelshan78/First-Principles-Deep-Learning) | DNN, CNN, RNN in raw NumPy - no autograd, BPTT and optimizers derived by hand | NumPy |
| [**PixelSense**](https://github.com/nabeelshan78/pixelsense-ai-segmentation) | U-Net from scratch, no pretrained backbone, 23-class segmentation, 0.908 val mIoU | TensorFlow/Keras |
| [**Math-VLM**](https://github.com/nabeelshan78/math-vlm-finetune-pipeline) | PaliGemma-3B adapted with QLoRA for handwritten expression → LaTeX | PyTorch, PEFT |
| [**ResearchFlow**](https://github.com/nabeelshan78/researchflow-multiagent-research-assistant) | Cyclical 4-agent system with self-correcting validation and HITL interrupts | LangGraph, Llama-3 |

---

### Stack

**Languages** `Python` `C++` `SQL` `Bash`  
**Deep Learning** `PyTorch` `TensorFlow/Keras` `Hugging Face` `NumPy` `Scikit-learn`  
**LLM & Agents** `Transformers` `PEFT/LoRA` `TRL` `LangChain` `LangGraph` `RAG`  
**Infrastructure** `Docker` `AWS` `SLURM` `FastAPI` `Weights & Biases` `Git` `Linux`

---

### Experience

* **Research Intern** - MITACS Globalink, University of Calgary *(Jul 2026 – Present)*
* **AI Engineer (Contract)** - DeepDocs AI, France *(Nov 2025 – Jan 2026)*
* **Quantum-AI Research Intern** - CETQAP *(Jun 2025 – Aug 2025)*
* **AI/ML Intern** - Software Productivity Strategists *(Apr 2025 – May 2025)*

---
