---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am **Zhuo Wang (王茁)**, a junior majoring in **Software Engineering (Honors Class)** at [Beijing University of Technology (BJUT)](https://www.bjut.edu.cn). I maintain strong academic performance (top 7.69% in major) and have been actively pursuing research on multimodal AI since my sophomore year.

## Research Interests

- **LLMs & Agents** — software engineering agents, tool-augmented reasoning, modular agent harnesses
- **Multimodal LLMs & VLMs** — temporal reasoning, complex-scene understanding, vision-language alignment
- **LLMs in interdisciplinary domains** — remote sensing intelligence, geospatial AI, social computing
- **Trustworthy AIGC** — robust detection of AI-generated content, multimedia forensics, AI governance

## Research Experience

[Jan 2026 – present] **Harness Composer: Modular Harness Composition Framework for Software Engineering Agents**  
Project lead and student first author. Formalized harness construction for software engineering agents as a module composition problem across tools, context, tests, compression, control, and state. The system profiles each repository/task, routes it through deterministic policy rules, and composes a lean, auditable, task-adaptive harness instead of using fixed configurations or exposing all tools. On Terminal-Bench 2, Harness Composer reaches 65.2% accuracy with Claude Opus 4.6, outperforming Terminus 2 (62.9%) and Claude Code (58.0%) while reducing cost by 17%; on SWE-bench Verified-100, it improves pass@1 from 78% to 80% and reduces cost by 7.5%. Submitted to **NeurIPS 2026**.

<figure style="margin: 0.9rem 0 1.1rem;">
  <img src="/images/harness_composer/overview.png" alt="Harness Composer framework overview" style="width: 100%; height: auto;">
  <figcaption style="font-size: 0.85em; color: #6a737d; margin-top: 0.35rem;">Harness Composer overview: profile-driven policy routing, modular harness composition, and auditable agent execution.</figcaption>
</figure>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 0.8rem; margin: 0.5rem 0 1.5rem;">
  <figure style="margin: 0;">
    <img src="/images/harness_composer/result.png" alt="Harness Composer Terminal-Bench 2 main results" style="width: 100%; height: auto;">
    <figcaption style="font-size: 0.85em; color: #6a737d; margin-top: 0.35rem;">Main Terminal-Bench 2 results.</figcaption>
  </figure>
  <figure style="margin: 0;">
    <img src="/images/harness_composer/aba.png" alt="Harness Composer controlled efficiency analysis" style="width: 100%; height: auto;">
    <figcaption style="font-size: 0.85em; color: #6a737d; margin-top: 0.35rem;">Controlled efficiency analysis.</figcaption>
  </figure>
</div>

[Jun – Oct 2025] **MemeParser: Temporal Vision-Language Framework for Internet Meme Evolution**  
Designed a temporal VLM framework based on Qwen2.5-VL featuring a Visual Differential Layer, Delta Attention, and Semantic-Gated Cross-Attention. Constructed MemeEvo (500 groups, 10,247 instances), the first bilingual meme evolution dataset. Achieved 4.45% composite-metric improvement over SOTA. Submitted to **IEEE ICME 2026** (CCF-B) as student first author.

[Dec 2025 – present] **RobustSora: De-Watermarked Benchmark for Robust AIGC Video Detection** 
Constructed a 6,500-sample benchmark under four perturbation conditions; evaluated 10 SOTA detectors and exposed 2–8% robustness gaps due to watermark artifacts. Published at **AAAI 2026 Workshop on RSD** (CCF-A) as first author. Presented poster at AAAI 2026, Singapore.

[Sep – Dec 2025]  **GeoAgent: Lightweight Multi-Agent Framework for Geospatial Query** 
Research intern. Implemented semantic sliding-window segmentation over 230 unstructured reports into 9,975 chunks; achieved 6% hallucination rate and 88% relevance on 7,399 maritime safety records.

[Mar 2026 – present]  **SAR Multi-task Vision-Language Model** 
Research intern in **HPGC Lab**. Conducting systematic failure analysis of Qwen2.5-VL on SAR imagery and designing a SAR-Aware Visual Adapter and Spatial Reasoning Enhancement Module.

## Publications

1. **MemeParser: A Temporal Vision-Language Framework for Modeling Propagation and Semantic Shift of Internet Memes**  
   Xiliang Liu, **Zhuo Wang**, Tao Zhou, Li Tian, Zhixiang He, Xiaoying Zhi, Jiale Liu.  
   *IEEE ICME 2026* (CCF-B) *Review scores: 5, 3, 3, 2.(Max=5,Strong Accept)

2. **RobustSora: De-Watermarked Benchmark for Robust AI-Generated Video Detection**  
   **Zhuo Wang**, Xiliang Liu, Ligang Sun.  
   *AAAI 2026 Workshop on RSD* (CCF-A), Poster &nbsp;·&nbsp; [[arXiv]](https://arxiv.org/abs/2512.10248)

3. **Who Evaluates the Evaluators? Governance Challenges in AI Safety and Alignment Evaluations: A Review and Future Agenda**  
   **Zhuo Wang**, Xiliang Liu, Ligang Sun.  
   *AAAI 2026 Workshop on AI Governance* (CCF-A), Poster &nbsp;·&nbsp; [[OpenReview]](https://openreview.net/forum?id=Bg5aKILJcn)

## Selected Awards

| Award | Level | Year |
|-------|-------|------|
| Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM) | National Second Prize | 2024 |
| Mathematical Contest in Modeling (MCM/ICM) | International Honorable Mention | 2025 |
| Fudan Club Cup Academic English Vocabulary Competition | National Second Prize | 2024 |
| Beijing Intercollegiate Mathematical Modeling Contest | Provincial First Prize | 2024 |
| BJUT Innovation & Entrepreneurship Scholarship | University | 2024–2025 |

## Contact

- **Email**: [wangzhuo230410@emails.bjut.edu.cn](mailto:wangzhuo230410@emails.bjut.edu.cn)
- **GitHub**: [github.com/williamwang25](https://github.com/williamwang25)

