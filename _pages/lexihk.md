---
permalink: /lexihk/
title: "LexiHK — AI Legal Assistant for Hong Kong"
author_profile: true
redirect_from:
  - /lexihk.html
---

<div class="lexihk-hero" style="background: #ffffff; border: 2px solid #0f3460; padding: 48px 36px; border-radius: 12px; margin-bottom: 36px; text-align: center;">
  <h1 style="font-family: 'Playfair Display', serif; font-size: 2.6em; font-weight: 800; margin: 0 0 4px 0; color: #0f3460; letter-spacing: 2px;">LexiHK</h1>
  <p style="font-size: 1.2em; color: #555; margin: 0 0 6px 0; font-weight: 500;">港法通</p>
  <hr style="width: 60px; border: none; border-top: 3px solid #e94560; margin: 16px auto;">
  <p style="font-size: 1.05em; color: #333; margin: 0 0 24px 0;">Hong Kong's First AI-Powered Legal Assistant — Built on HKGAI's Sovereign LLM</p>
  <a href="https://lexi.hkgai.asia/login" target="_blank" style="display: inline-block; background: #0f3460; color: #fff; padding: 12px 32px; border-radius: 8px; text-decoration: none; font-weight: 600; font-size: 1em;">Try LexiHK Pro &rarr;</a>
</div>

# Overview

**LexiHK** (港法通) is an AI-powered legal assistant developed by the [Hong Kong Generative AI Research and Development Centre (HKGAI)](https://www.hkgai.info/). As the **founder and lead architect** of LexiHK, I designed and built this system to bridge the gap between advanced large language model capabilities and the practical needs of Hong Kong's legal community.

LexiHK is built on top of **HKGAI V1**, Hong Kong's first sovereign large language model — a locally fine-tuned foundation model based on DeepSeek, trained with Hong Kong legal data, local values, and trilingual capabilities (Cantonese, Mandarin, and English). It serves government departments, legal professionals, and the general public with efficient, compliant, and professional AI-assisted legal services.

LexiHK（港法通）是由香港生成式人工智能研发中心（HKGAI）开发的智能AI法律助手。作为LexiHK的创始人和首席架构师，我设计并构建了这一系统，旨在将大语言模型的前沿能力与香港法律界的实际需求相结合。LexiHK基于香港首个自主大语言模型HKGAI V1构建，为政府部门、法律专业人士和公众提供高效、合规、专业的AI法律服务。

---

# Key Capabilities

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 20px; margin: 24px 0;">
  <div style="background: #f8f9fa; border-left: 4px solid #0f3460; padding: 20px; border-radius: 8px;">
    <h3 style="margin-top: 0; color: #0f3460;">Hong Kong Ordinance Q&A</h3>
    <p style="margin-bottom: 0;">Query and interpret Hong Kong legislation with AI-powered natural language understanding, covering the full corpus of Hong Kong ordinances and subsidiary legislation.</p>
  </div>
  <div style="background: #f8f9fa; border-left: 4px solid #e94560; padding: 20px; border-radius: 8px;">
    <h3 style="margin-top: 0; color: #e94560;">Legal Opinion Generation</h3>
    <p style="margin-bottom: 0;">Generate structured legal opinions grounded in Hong Kong law, with traceable references to specific ordinances and case law.</p>
  </div>
  <div style="background: #f8f9fa; border-left: 4px solid #1a9988; padding: 20px; border-radius: 8px;">
    <h3 style="margin-top: 0; color: #1a9988;">Trilingual Support</h3>
    <p style="margin-bottom: 0;">Fully supports Cantonese, Mandarin, and English — reflecting Hong Kong's unique multilingual legal environment and dual legal system.</p>
  </div>
  <div style="background: #f8f9fa; border-left: 4px solid #f5a623; padding: 20px; border-radius: 8px;">
    <h3 style="margin-top: 0; color: #f5a623;">Compliance-First Design</h3>
    <p style="margin-bottom: 0;">Designed with legal compliance at its core, incorporating safeguards aligned with Hong Kong's regulatory framework and professional ethics standards.</p>
  </div>
</div>

---

# Recognition & Impact

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 24px; margin: 24px 0;">
  <div style="background: linear-gradient(135deg, #fdf6ec, #fef9f0); border: 1px solid #f0d9a0; padding: 24px; border-radius: 12px; text-align: center;">
    <div style="font-size: 2.5em; margin-bottom: 8px;">🥉</div>
    <h3 style="margin: 0 0 8px 0; color: #8b6914;">Bronze Medal</h3>
    <p style="margin: 0; font-size: 0.95em; color: #555;">50th International Exhibition of Inventions of Geneva (April 2025) — the world's largest exhibition devoted exclusively to inventions.</p>
  </div>
  <div style="background: linear-gradient(135deg, #eef6ff, #f0f8ff); border: 1px solid #a0c8f0; padding: 24px; border-radius: 12px; text-align: center;">
    <div style="font-size: 2.5em; margin-bottom: 8px;">🏛️</div>
    <h3 style="margin: 0 0 8px 0; color: #1a5276;">Government Adoption</h3>
    <p style="margin: 0; font-size: 0.95em; color: #555;">Part of the HKGAI V1 ecosystem adopted by 70+ Hong Kong government departments, supporting public service modernization.</p>
  </div>
  <div style="background: linear-gradient(135deg, #f0f9f0, #f5fdf5); border: 1px solid #a0d8a0; padding: 24px; border-radius: 12px; text-align: center;">
    <div style="font-size: 2.5em; margin-bottom: 8px;">🌐</div>
    <h3 style="margin: 0 0 8px 0; color: #1a7a3a;">Sovereign LLM</h3>
    <p style="margin: 0; font-size: 0.95em; color: #555;">Built on Hong Kong's first locally developed LLM, ensuring data sovereignty and alignment with local legal norms and values.</p>
  </div>
</div>

---

# Technical Architecture

LexiHK is not merely a chatbot wrapper — it represents a purpose-built legal AI system with several distinguishing technical features:

**Foundation Model.** LexiHK is powered by HKGAI V1, a sovereign large language model developed through full-parameter fine-tuning and continual training on Hong Kong-specific legal corpora. The base model builds upon DeepSeek and is customized for Hong Kong's trilingual, dual-legal-system environment.

**Legal Knowledge Grounding.** The system incorporates a comprehensive knowledge base of Hong Kong ordinances, subsidiary legislation, and case law. Retrieval-augmented generation (RAG) ensures that responses are grounded in authoritative legal sources with traceable citations.

**Safety and Compliance.** As a legal AI system, LexiHK integrates multiple layers of safety mechanisms, including content filtering, hallucination detection, and disclaimer generation, to ensure outputs meet professional standards and regulatory requirements.

**Multilingual Legal Reasoning.** The model supports legal reasoning across Cantonese, Mandarin, and English, a capability critical for Hong Kong's unique linguistic landscape where legal documents may exist in any of these languages.

---

# The HKGAI V1 Ecosystem

LexiHK is one of five vertical applications built on the HKGAI V1 foundation model. Together, these applications demonstrate the breadth of Hong Kong's sovereign AI capabilities:

| Application | Chinese Name | Function |
|:---|:---|:---|
| **HKChat** | 港话通 | AI chatbot for government and public services |
| **HKCopilot** | 港文通 | Document drafting and writing assistant for civil servants |
| **HKConference** | 港会通 | Multilingual meeting transcription and summarization |
| **LexiHK** | 港法通 | AI legal assistant for ordinance Q&A and legal opinions |
| **HKEcoLink** | 港环通 | Environmental data analysis and sustainability support |

The HKGAI V1 model was developed under the leadership of HKUST, in collaboration with HKU, CUHK, NUS, and other international research institutions. It was officially launched in 2025 and has been adopted by the Hong Kong SAR Government for public service applications.

---

# Media & References

The following sources provide additional context on LexiHK and the HKGAI V1 ecosystem:

- **Wikipedia:** [HKGAI V1 — 港法通](https://zh.wikipedia.org/zh-cn/HKGAI_V1) — Wikipedia entry documenting LexiHK as part of the HKGAI V1 system.
- **HKGAI Official:** [HKGAI Solutions](https://www.hkgai.info/solutions) — Official product page describing LexiHK and other HKGAI applications.
- **HKUST Research Portal:** [Geneva Bronze Medal — LexiHK](https://researchportal.hkust.edu.hk/en/prizes/50th-international-exhibition-of-inventions-of-geneva-bronze-meda/) — Award record for the 50th International Exhibition of Inventions of Geneva.
- **HK Government Press Release:** [LCQ5: Application of Legal Technology and AI](https://www.doj.gov.hk/en/community_engagement/press/20250709_pr2.html) — Hong Kong Department of Justice discussing HKGAI's legal AI applications.
- **HK Government Press Release:** [Hong Kong-developed LLMs](https://www.info.gov.hk/gia/general/202504/02/P2025040200262.htm) — Legislative Council Q&A on HKGAI V1 and its applications including LexiHK.
