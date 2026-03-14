---
permalink: /research/
title: "Research"
excerpt: ""
author_profile: true
---

# Research

My research program is driven by a central question: **How can we build AI systems that are technically powerful, legally compliant, and ethically accountable?** To address this, my group pursues five interconnected research pillars — from foundational AI safety and efficient model design to applied legal reasoning and computational social science.

---

<span class='anchor' id='legal-alignment'></span>

## Pillar 1: Legal Alignment & AI Governance

Hong Kong's unique position as a jurisdiction operating under two parallel legal systems — common law and mainland Chinese law — makes it the world's only natural laboratory for studying how AI systems can be aligned to plural legal norms simultaneously. This pillar focuses on developing benchmarks, methods, and frameworks for ensuring LLMs comply with diverse legal requirements.

**Key Contributions:**

<div class="publication-list">
  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#2563eb;">ACL 2025 Findings</span>
      </div>
      <h4 class="publication-card__title"><a href="https://aclanthology.org/2025.findings-acl.721/">SafeLawBench: Towards Safe Alignment of Large Language Models</a></h4>
      <p class="publication-card__authors">Cao, Chuxue; Zhu, Han; Ji, Jiaming; ...; <strong>Han, Sirui*</strong>; Guo, Yike*</p>
      <p style="font-size:0.85em; color:#555;">A comprehensive benchmark for evaluating the legal safety alignment of LLMs across multiple jurisdictions.</p>
      <div>[<a href="https://arxiv.org/abs/2506.06636">arXiv</a>] [<a href="https://github.com/chuxuecao/SafeLawBench">Code</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#1e3a8a;">ACL 2025</span>
      </div>
      <h4 class="publication-card__title"><a href="https://aclanthology.org/2025.acl-long.361/">LegalReasoner: Step-wised Verification-Correction for Legal Judgment Reasoning</a></h4>
      <p class="publication-card__authors">Shi, Weijie; Zhu, Han; ...; <strong>Han, Sirui*</strong>; Guo, Yike*.</p>
      <p style="font-size:0.85em; color:#555;">A step-wise verification-correction framework that significantly improves the accuracy and reliability of LLM-based legal judgment reasoning.</p>
      <div>[<a href="https://arxiv.org/abs/2506.07443">arXiv</a>] [<a href="https://github.com/UPSD1/LegalReasoner">Code</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#1e3a8a;">ACL 2025</span>
      </div>
      <h4 class="publication-card__title"><a href="https://aclanthology.org/2025.acl-long.518/">PrivaCI-Bench: Evaluating Privacy with Contextual Integrity and Legal Compliance</a></h4>
      <p class="publication-card__authors">Li, Haoran; Hu, Wenbin; ...; <strong>Han, Sirui*</strong>; Chu, Tianshu; Hu, Peizhao; Song, Yangqiu.</p>
      <p style="font-size:0.85em; color:#555;">A benchmark evaluating LLM privacy awareness through the lens of contextual integrity theory and legal compliance.</p>
      <div>[<a href="https://arxiv.org/abs/2502.17041">arXiv</a>] [<a href="https://github.com/HKUST-KnowComp/PrivaCI-Bench">Code</a>]</div>
    </div>
  </div>
</div>

**Other Related Work:**
- **Trustworthy Legal Reasoning: A Comprehensive Survey** — *Preprints 2026* — [Paper](https://www.preprints.org/manuscript/202602.0870)
- **Benchmarking Multi-National Value Alignment for LLMs** — *ACL 2025 Findings* — [arXiv](https://arxiv.org/abs/2504.12911)
- **LRAS: Advanced Legal Reasoning with Agentic Search** — *arXiv 2026* — [arXiv](https://arxiv.org/abs/2601.07296)
- **Awesome World Law Agent** — A comprehensive survey of the World Law Agent ecosystem (AI + Law) — [GitHub](https://github.com/siruihan2024/awesome-world-law-agent)
- **HK-O1aw** — A legal reasoning assistant for Hong Kong's common law system, built on LLaMA-3.1-8B with O1-style reasoning — [GitHub](https://github.com/HKAIR-Lab/HK-O1aw)

**Team Members:** Chuxue CAO, Han ZHU, Yujin ZHOU, Ruoxi LI, Yuyao ZHANG

---

<span class='anchor' id='ai-safety'></span>

## Pillar 2: AI Safety & RLHF

Ensuring that AI systems behave safely and align with human values is a fundamental challenge. This pillar develops methods for safe reinforcement learning from human feedback (RLHF), multi-modal safety alignment, and out-of-distribution detection — extending safety guarantees from text-only to multi-modal and multi-turn settings.

**Key Contributions:**

<div class="publication-list">
  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#dc2626;">NeurIPS 2025</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2503.17682">Safe RLHF-V: Safe Reinforcement Learning from Multi-modal Human Feedback</a></h4>
      <p class="publication-card__authors">Ji, Jiaming; Chen, Xinyu; ...; <strong>Han, Sirui</strong>; Guo, Yike; Yang, Yaodong.</p>
      <p style="font-size:0.85em; color:#555;">Extending safe RLHF to the multimodal domain, enabling alignment of vision-language models with human safety preferences.</p>
      <div>[<a href="https://arxiv.org/abs/2503.17682">arXiv</a>] [<a href="https://github.com/saferlhf-v">Code</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#1e3a8a;">ACL 2025</span>
      </div>
      <h4 class="publication-card__title"><a href="https://aclanthology.org/2025.acl-long.1544/">PKU-SafeRLHF: Towards Multi-Level Safety Alignment for LLMs</a></h4>
      <p class="publication-card__authors">Ji, Jiaming; Hong, Donghai; ...; <strong>Han, Sirui</strong>; Guo, Yike; Yang, Yaodong.</p>
      <p style="font-size:0.85em; color:#555;">A multi-level safety alignment framework and large-scale dataset for training safer LLMs.</p>
      <div>[<a href="https://arxiv.org/abs/2406.15513">arXiv</a>] [<a href="https://github.com/PKU-Alignment/safe-rlhf">Code</a>]</div>
    </div>
  </div>
</div>

**Other Related Work:**
- **SafeMT: Multi-turn Safety for Multimodal Language Models** — *arXiv 2025* — [arXiv](https://arxiv.org/abs/2510.12133)
- **AM3Safety: Towards Data Efficient Alignment of Multi-modal Multi-turn Safety for MLLMs** — *arXiv 2026* — [arXiv](https://arxiv.org/abs/2601.04736)
- **InterMT: Multi-Turn Interleaved Preference Alignment with Human Feedback** — *NeurIPS 2025* — [arXiv](https://arxiv.org/abs/2505.23950)
- **Context Reasoner: Incentivizing Reasoning Capability for Contextualized Privacy and Safety Compliance** — *EMNLP 2025* — [arXiv](https://arxiv.org/abs/2505.14585)

**Team Members:** Han ZHU, Chi-Min CHAN, Pengcheng WEN, Chuxue CAO

---

<span class='anchor' id='efficient-llms'></span>

## Pillar 3: Efficient & Robust LLMs

Deploying large language models in real-world applications requires overcoming significant computational and efficiency challenges. This pillar develops novel methods for model compression, parameter-efficient fine-tuning, and inference optimization — making powerful LLMs more accessible and practical.

**Key Contributions:**

<div class="publication-list">
  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#dc2626;">AAAI 2026</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2506.23266">Sub-MoE: Efficient Mixture-of-Expert LLMs Compression via Subspace Expert Merging</a></h4>
      <p class="publication-card__authors">Li, Lujun; Zhu, Qiyuan; ...; <strong>Han, Sirui*</strong>; Guo, Yike*.</p>
      <p style="font-size:0.85em; color:#555;">A novel approach to compressing MoE-based LLMs through subspace expert merging.</p>
      <div>[<a href="https://arxiv.org/abs/2506.23266">arXiv</a>] [<a href="https://github.com/siruihan2024/Sub-MoE">GitHub</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#dc2626;">ICCV 2025</span>
      </div>
      <h4 class="publication-card__title">Efficient Fine-Tuning of Large Models via Nested Low-Rank Adaptation (NoRA)</h4>
      <p class="publication-card__authors">Li, Lujun; Lin, Cheng; ...; <strong>Han, Sirui*</strong>; Guo, Yike*.</p>
      <p style="font-size:0.85em; color:#555;">A nested low-rank adaptation method that achieves superior parameter efficiency for fine-tuning large models.</p>
      <div>[<a href="https://arxiv.org/abs/2408.10280">arXiv</a>] [<a href="https://github.com/siruihan2024/NoRA">GitHub</a>]</div>
    </div>
  </div>
</div>

**Other Related Work:**
- **AIRA: Activation-Informed Low-Rank Adaptation** — *ICCV 2025*
- **Outlier Matters: Efficient Long-to-Short Reasoning via Outlier-Guided Model Merging** — *AAAI 2026*
- **Outlier-Aware Model Merging for Efficient Multitask Inference** — *ACM MM 2025*
- **Semantic-guided Diverse Decoding for Large Language Model** — *NeurIPS 2025* — [arXiv](https://arxiv.org/abs/2506.23601)
- **DIDS: Domain Impact-aware Data Sampling** — *EMNLP 2025* — [arXiv](https://arxiv.org/abs/2504.13227)

**Team Members:** Lujun LI, Qiyuan ZHU, Hao GU, Zhenyuan ZHANG

---

<span class='anchor' id='multimodal-ai'></span>

## Pillar 4: Multimodal Intelligence & Embodied AI

This pillar pushes the boundaries of AI systems that perceive, understand, and interact with the physical world through multiple modalities. Our work spans 3D scene understanding, robotic manipulation, motion generation, and vision-language model evaluation.

**Key Contributions:**

<div class="publication-list">
  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#dc2626;">AAAI 2026</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2509.05314">ManipDreamer3D: Synthesizing Plausible Robotic Manipulation Video with Occupancy-aware 3D Trajectory</a></h4>
      <p class="publication-card__authors">Li, Ying; Wei, Xiaobao; Chi, Xiaowei; ...; <strong>Han, Sirui</strong>; Zhang, Shanghang.</p>
      <p style="font-size:0.85em; color:#555;">Generating realistic robotic manipulation videos using occupancy-aware 3D trajectory synthesis.</p>
      <div>[<a href="https://arxiv.org/abs/2509.05314">arXiv</a>] [<a href="https://github.com/myendless1/ManipDreamer3D">Code</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#0ea5a4;">ICLR 2026</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2508.13013">EgoTwin: Dreaming Body and View in First Person</a></h4>
      <p class="publication-card__authors">Xiu, Jingqiao; Hong, Fangzhou; ...; <strong>Han, Sirui*</strong>; Pan, Liang*; Liu, Ziwei.</p>
      <p style="font-size:0.85em; color:#555;">A novel framework for first-person body and view generation through egocentric dreaming.</p>
      <div>[<a href="https://arxiv.org/abs/2508.13013">arXiv</a>] [<a href="https://egotwin.pages.dev/">Project</a>]</div>
    </div>
  </div>
</div>

**Other Related Work:**
- **Motion-R1: Enhancing Motion Generation with Decomposed Chain-of-Thought and RL Binding** — *ICLR 2026* — [arXiv](https://arxiv.org/abs/2506.10353)
- **EffiVMT: Video Motion Transfer via Efficient Spatial-Temporal Decoupled Finetuning** — *ICLR 2026* — [arXiv](https://arxiv.org/abs/2506.05207)
- **GSRender: Deduplicated Occupancy Prediction via Weakly Supervised 3D Gaussian Splatting** — *ICRA 2026* — [arXiv](https://arxiv.org/abs/2412.14579)
- **IR3D-Bench: Evaluating Vision-Language Model Scene Understanding as Agentic Inverse Rendering** — *NeurIPS 2025* — [arXiv](https://arxiv.org/abs/2506.23329)
- **DanceEditor: Iterative Editable Music-driven Dance Generation** — *ICCV 2025*

**Team Members:** Xiaowei CHI, Xingqun QI, Zhenyuan ZHANG, Yakun CUI

---

<span class='anchor' id='computational-law'></span>

## Pillar 5: Computational Law & Social Science

Bridging computational methods with legal and social science inquiry, this pillar examines the societal implications of AI systems — from deepfake governance and AI manipulation to corpus inequality and consumer protection in AI-governed markets.

**Key Contributions:**

<div class="publication-list">
  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#16a34a;">CHI 2026</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2602.06305">Reimagining Legal Fact Verification with GenAI: Toward Effective Human-AI Collaboration</a></h4>
      <p class="publication-card__authors"><strong>Han, Sirui</strong>; Zhang, Yuyao; Huang, Yidan; Li, Xueyan; Liu, Chengzhong; Guo, Yike*.</p>
      <p style="font-size:0.85em; color:#555;">Pioneering the use of generative AI for legal fact verification through effective human-AI collaboration.</p>
      <div>[<a href="https://arxiv.org/abs/2602.06305">arXiv</a>] [<a href="https://github.com/siruihan2024/Legal-Fact-Verification-GenAI">GitHub</a>]</div>
    </div>
  </div>
</div>

**Other Related Work:**
- **When AI Manipulates: Context-Dependent Effect and the Psychology of University Student Trust on Social Media** — *ICA 2026*
- **Deepfakes as Systemic Risk at the Media–Law Boundary** — *ICA 2026*
- **When Data Speaks for the North: Generative AI, Corpus Inequality, and the Reinforcement of Symbolic Power** — *ICA 2026*
- **Consumer Protection in AI–Governed Credit Markets: Algorithmic Bias and the Right to Explanation** — *UI JLTP 2026*
- **Simulated Justice: How AI Alignment Replaces Conflict with Coherence** — *IHRLR 2026*

**Journal Articles on Law & Finance:**
- **ESG Disclosure, Investor Awareness, and Carbon Risk Pricing** — *International Review of Law and Economics, 2024*
- **Harmonizing Arbitration Rules for Non-Signatories in International Trade** — *ICCLR, 2024*
- **Regulating Collective Labour Disputes in China** — *Journal of Comparative Law, 2016*

**Team Members:** Yidan HUANG, Siyu PENG, Guoying LU, Chengyi JU, Yuyao ZHANG
