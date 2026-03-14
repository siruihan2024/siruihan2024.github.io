---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me

I am an **Assistant Professor** at the [Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk/) and **Head of the Large Language Model Division** at the [Hong Kong Generative AI Research and Development Centre (HKGAI)](https://www.hkgai.info/). Trained as both a **legal scholar** (Ph.D. in Law, CUHK) and a **computer scientist** (Ph.D. candidate in CS, HKUST), I am one of the few researchers globally who combines direct engineering access to a sovereign LLM with formal doctoral training in both disciplines. My research focuses on building AI systems that are **legally aligned, ethically accountable, and technically robust** — with a particular emphasis on Hong Kong's unique dual legal system as a natural laboratory for plural-norm AI governance.

<p style="color:#555; margin-top:10px;">我是<a href="https://hkust.edu.hk/">香港科技大学</a><strong>助理教授</strong>，同时担任<a href="https://www.hkgai.info/">香港生成式人工智能研发中心（HKGAI）</a><strong>大语言模型部门主管</strong>。我同时接受过<strong>法学</strong>（香港中文大学法学博士）和<strong>计算机科学</strong>（香港科技大学计算机博士候选人）的正式博士训练，是全球少数兼具主权大语言模型直接工程经验与跨学科博士背景的研究者。我的研究聚焦于构建<strong>合法合规、伦理可问责、技术稳健</strong>的AI系统——尤其以香港独特的双轨法律体系作为多元规范AI治理的天然实验室。</p>

<div class="key-metrics">
  <div class="metric-item">
    <span class="metric-number">HK$33M+</span>
    <span class="metric-label">Research Funding<br>科研经费</span>
  </div>
  <div class="metric-item">
    <span class="metric-number">50+</span>
    <span class="metric-label">Top-Venue Papers<br>顶会论文</span>
  </div>
  <div class="metric-item">
    <span class="metric-number">30+</span>
    <span class="metric-label">PhD Students<br>博士生</span>
  </div>
  <div class="metric-item">
    <span class="metric-number">11</span>
    <span class="metric-label">Industry Partners<br>产业合作伙伴</span>
  </div>
</div>

---

<span class='anchor' id='research-vision'></span>

# Research Vision

As AI systems increasingly operate within and across legal jurisdictions, the question of how to align these systems with diverse — sometimes conflicting — legal norms becomes urgent. My research program addresses this challenge at the **intersection of AI and law**, developing the theoretical foundations, technical methods, and governance frameworks needed to ensure that large language models can be trusted to operate within the rule of law. From **AI safety and RLHF** to **legal reasoning** and **multimodal intelligence**, my group pursues a unified vision: **trustworthy AI that respects human values and legal boundaries**.

<p style="color:#555; margin-top:10px;">随着AI系统日益在不同法律管辖区内及跨区运行，如何使其与多元甚至相互冲突的法律规范保持一致已成为紧迫课题。我的研究聚焦于<strong>人工智能与法律的交叉领域</strong>，致力于发展理论基础、技术方法和治理框架，以确保大语言模型能够在法治框架内可信运行。从<strong>基于人类反馈的强化学习（RLHF）与AI安全</strong>到<strong>法律推理</strong>和<strong>多模态智能</strong>，我的团队追求统一愿景：<strong>构建尊重人类价值与法律边界的可信赖AI</strong>。</p>

---

<span class='anchor' id='research-pillars'></span>

# Research Pillars

<div class="research-pillars">
  <div class="pillar-card">
    <div class="pillar-icon">&#9878;</div>
    <h3>Legal Alignment & AI Governance</h3>
    <p>Building AI systems aligned with plural legal norms. Key projects include SafeLawBench, LegalReasoner, PrivaCI-Bench, and the Trustworthy Legal Reasoning survey.</p>
    <a href="/research/#legal-alignment" class="pillar-link">Learn More →</a>
  </div>
  <div class="pillar-card">
    <div class="pillar-icon">&#128737;</div>
    <h3>AI Safety & RLHF</h3>
    <p>Developing safe reinforcement learning from human feedback for multimodal LLMs. Key projects include Safe RLHF-V, PKU-SafeRLHF, SafeMT, and AM3Safety.</p>
    <a href="/research/#ai-safety" class="pillar-link">Learn More →</a>
  </div>
  <div class="pillar-card">
    <div class="pillar-icon">&#9889;</div>
    <h3>Efficient & Robust LLMs</h3>
    <p>Advancing model compression, efficient fine-tuning, and inference optimization. Key projects include Sub-MoE, Nested LoRA, AIRA, and Outlier-Aware Merging.</p>
    <a href="/research/#efficient-llms" class="pillar-link">Learn More →</a>
  </div>
  <div class="pillar-card">
    <div class="pillar-icon">&#127916;</div>
    <h3>Multimodal Intelligence & Embodied AI</h3>
    <p>Pushing the boundaries of vision-language models, 3D understanding, and robotic manipulation. Key projects include ManipDreamer3D, GSRender, Motion-R1, and EgoTwin.</p>
    <a href="/research/#multimodal-ai" class="pillar-link">Learn More →</a>
  </div>
  <div class="pillar-card">
    <div class="pillar-icon">&#128218;</div>
    <h3>Computational Law & Social Science</h3>
    <p>Bridging computational methods with legal and social science inquiry, including AI manipulation, deepfake governance, and corpus inequality studies.</p>
    <a href="/research/#computational-law" class="pillar-link">Learn More →</a>
  </div>
</div>

---

<span class='anchor' id='featured-publications'></span>

# Featured Publications

<div class="publication-list">
  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#2563eb;">ACL 2025</span>
        <span>Legal Alignment</span>
      </div>
      <h4 class="publication-card__title"><a href="https://aclanthology.org/2025.findings-acl.721/">SafeLawBench: Towards Safe Alignment of Large Language Models</a></h4>
      <p class="publication-card__authors">Cao, Chuxue; Zhu, Han; Ji, Jiaming; ...; <strong>Han, Sirui*</strong>; Guo, Yike*</p>
      <p style="font-size:0.85em; color:#555;">A comprehensive benchmark for evaluating the legal safety alignment of LLMs, bridging AI safety research with legal compliance requirements.</p>
      <div>[<a href="https://arxiv.org/abs/2506.06636">arXiv</a>] [<a href="https://github.com/chuxuecao/SafeLawBench">Code</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#dc2626;">NeurIPS 2025</span>
        <span>AI Safety</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2503.17682">Safe RLHF-V: Safe Reinforcement Learning from Multi-modal Human Feedback</a></h4>
      <p class="publication-card__authors">Ji, Jiaming; Chen, Xinyu; ...; <strong>Han, Sirui</strong>; Guo, Yike; Yang, Yaodong</p>
      <p style="font-size:0.85em; color:#555;">Extending safe RLHF to the multimodal domain, enabling alignment of vision-language models with human safety preferences.</p>
      <div>[<a href="https://arxiv.org/abs/2503.17682">arXiv</a>] [<a href="https://github.com/saferlhf-v">Code</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#dc2626;">AAAI 2026</span>
        <span>Efficient LLMs</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2506.23266">Sub-MoE: Efficient Mixture-of-Expert LLMs Compression via Subspace Expert Merging</a></h4>
      <p class="publication-card__authors">Li, Lujun; Zhu, Qiyuan; ...; <strong>Han, Sirui*</strong>; Guo, Yike*</p>
      <p style="font-size:0.85em; color:#555;">A novel approach to compressing Mixture-of-Expert LLMs through subspace expert merging, achieving significant efficiency gains.</p>
      <div>[<a href="https://arxiv.org/abs/2506.23266">arXiv</a>] [<a href="https://github.com/siruihan2024/Sub-MoE">GitHub</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#16a34a;">CHI 2026</span>
        <span>Computational Law</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2602.06305">Reimagining Legal Fact Verification with GenAI: Toward Effective Human-AI Collaboration</a></h4>
      <p class="publication-card__authors"><strong>Han, Sirui</strong>; Zhang, Yuyao; Huang, Yidan; Li, Xueyan; Liu, Chengzhong; Guo, Yike*</p>
      <p style="font-size:0.85em; color:#555;">Pioneering the use of generative AI for legal fact verification, demonstrating effective human-AI collaboration in the legal domain.</p>
      <div>[<a href="https://arxiv.org/abs/2602.06305">arXiv</a>] [<a href="https://github.com/siruihan2024/Legal-Fact-Verification-GenAI">GitHub</a>]</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-card__body">
      <div class="publication-card__meta">
        <span class="publication-card__badge" style="background:#0ea5a4;">ICLR 2026</span>
        <span>Multimodal AI</span>
      </div>
      <h4 class="publication-card__title"><a href="https://arxiv.org/abs/2506.10353">Motion-R1: Enhancing Motion Generation with Decomposed Chain-of-Thought and RL Binding</a></h4>
      <p class="publication-card__authors">Ouyang, Runqi; Li, Haoyun; ...; <strong>Han, Sirui</strong>; Wang, Xingang*</p>
      <p style="font-size:0.85em; color:#555;">A novel framework that enhances motion generation quality through decomposed chain-of-thought reasoning and reinforcement learning.</p>
      <div>[<a href="https://arxiv.org/abs/2506.10353">arXiv</a>] [<a href="https://motion-r1.github.io/">Project</a>]</div>
    </div>
  </div>
</div>

<p style="text-align:center;"><a href="/publications/" class="btn btn--primary">View All Publications →</a></p>

---

<span class='anchor' id='recent-news'></span>

# Recent News

<div class="news-list">
  <div class="news-item">
    <span class="news-date">2026.03</span>
    <span class="news-text">4 papers accepted at <strong>CVPR 2026</strong>, <strong>ICRA 2026</strong>, and <strong>CHI 2026</strong>.</span>
  </div>
  <div class="news-item">
    <span class="news-date">2026.01</span>
    <span class="news-text">4 papers accepted at <strong>AAAI 2026</strong>, including Sub-MoE and ManipDreamer3D.</span>
  </div>
  <div class="news-item">
    <span class="news-date">2026.01</span>
    <span class="news-text">3 papers accepted at <strong>ICLR 2026</strong>, including Motion-R1, EffiVMT, and EgoTwin.</span>
  </div>
  <div class="news-item">
    <span class="news-date">2025.09</span>
    <span class="news-text">5 papers accepted at <strong>NeurIPS 2025</strong>, including Safe RLHF-V and IR3D-Bench.</span>
  </div>
  <div class="news-item">
    <span class="news-date">2025.05</span>
    <span class="news-text">8 papers accepted at <strong>ACL 2025</strong>, including SafeLawBench, LegalReasoner, and PKU-SafeRLHF.</span>
  </div>
  <div class="news-item">
    <span class="news-date">2025.10</span>
    <span class="news-text">3 papers accepted at <strong>ICCV 2025</strong>, including Nested LoRA and AIRA.</span>
  </div>
  <div class="news-item">
    <span class="news-date">2024.04</span>
    <span class="news-text">Awarded <strong>Bronze Medal</strong> at the 50th International Exhibition of Inventions of Geneva for LexiHK.</span>
  </div>
</div>

---

<span class='anchor' id='team-preview'></span>

# Team

I lead an active research group of **30+ PhD students**, **7 engineers**, and **research assistants** spanning AI safety, legal reasoning, efficient LLMs, and multimodal systems.

## PhD Students

[Chuxue CAO](https://scholar.google.com/citations?user=4klHp4oAAAAJ) · Jialiang CHEN · Long CHEN · [Xiaowei CHI](https://scholar.google.com/citations?user=Vl1X_-sAAAAJ) (co-supervision) · [Chi-Min CHAN](https://scholar.google.com/citations?user=5U4P54wAAAAJ&hl=zh-CN) · Yakun CUI · [Mengfei DU](https://scholar.google.com/citations?user=JONwde0AAAAJ) · [Hao GU](https://scholar.google.com/citations?user=ozg7axcAAAAJ) · [Shengyao GUO](https://scholar.google.com/citations?user=bEtLSugAAAAJ) · Chengyi JU · Qintao HUANG (co-supervision) · [Yidan HUANG](https://scholar.google.com/citations?user=KaeEsKMAAAAJ) · [Zhizhuo KOU](https://scholar.google.com/citations?user=jzJL2csAAAAJ&hl=zh-CN) · [Lujun LI](https://scholar.google.com/citations?user=aPl3DjIAAAAJ&hl=zh-CN) (co-supervision) · Ruoxi LI · Xinyao LIAO · [Guoying LU](https://scholar.google.com/citations?user=kdFMa2gAAAAJ&hl=zh-CN) · [Siyu PENG](https://scholar.google.com/citations?user=La4hHlUAAAAJ&hl=zh-CN) · [Xingqun QI](https://scholar.google.com/citations?user=3tO41a8AAAAJ&hl=zh-CN) (co-supervision) · Jiapeng SUN · [Pengcheng WEN](https://scholar.google.com/citations?user=4iKUa4MAAAAJ&hl=zh-CN) · Jian YANG (co-supervision) · Yanting ZHANG · Xiaojie ZHANG · [Yuyao ZHANG](https://scholar.google.com/citations?user=hoK4mPYAAAAJ&hl=en) · Zhenyuan ZHANG · [Yujin ZHOU](https://scholar.google.com/citations?user=FGtltRMAAAAJ&hl=zh-CN) · Han ZHU · [Qiyuan ZHU](https://dblp.org/pid/210/9778.html) · Junqi ZHU

## Engineers

Jieyang FENG · Xiangyu LONG · Zhiqiang QIAN · Xinyi WANG · Shuchao WU · Boqin YIN · Zhenghao ZHU

## Research Assistants

Xueyan LI

---

<span class='anchor' id='collaborators'></span>

# Institutional Collaborators

<div style="display:flex; flex-wrap:wrap; align-items:center; justify-content:center; gap:30px; margin:20px 0;">
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/bytedance.jpg' | relative_url }}" alt="ByteDance" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">ByteDance</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/china-telecom.png' | relative_url }}" alt="China Telecom International" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">China Telecom International</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/du-xiaoman.jpg' | relative_url }}" alt="Du Xiaoman Financial" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">Du Xiaoman Financial</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/hkgai.png' | relative_url }}" alt="HKGAI" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">HKGAI</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/metax.png' | relative_url }}" alt="MetaX" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">MetaX</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/pengcheng-lab.png' | relative_url }}" alt="Peng Cheng Laboratory" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">Peng Cheng Laboratory</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/phoenix-tv.png' | relative_url }}" alt="Phoenix TV" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">Phoenix TV</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/shanghai-ai-lab.png' | relative_url }}" alt="Shanghai AI Laboratory" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">Shanghai AI Laboratory</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/tsinghua-aiig.png' | relative_url }}" alt="Tsinghua I-AIIG" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">Tsinghua I-AIIG</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/webank.png' | relative_url }}" alt="WeBank" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">WeBank</p>
  </div>
  <div style="text-align:center;">
    <img src="{{ 'images/collaborators/wiselaw.png' | relative_url }}" alt="WiseLaw" style="height:80px; object-fit:contain;">
    <p style="margin-top:5px; font-size:85%;">WiseLaw</p>
  </div>
</div>
