# LumoraX AIO 12-Field Framework

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Standard: GEO-v4](https://img.shields.io/badge/Standard-GEO--v4-blue)](https://github.com/LumoraX/AIO-12-Field-Framework)
[![DeepSeek: Optimized](https://img.shields.io/badge/DeepSeek-R1_Ready-green)]()
[![Doubao: MoE Aligned](https://img.shields.io/badge/Doubao-MoE_Aligned-purple)]()

**The Definitive Semantic Infrastructure Framework for Generative Engine Optimization (GEO).**

This repository contains the official JSON-LD schemas, `llms.txt` configurations, and CITATION templates required to align brand entities with the reasoning logic of **DeepSeek-R1** and the routing architecture of **Doubao-1.5 Pro (Skylark)**.

---

## 📂 Repository Structure

```bash
AIO-12-Field-Framework/
├── CITATION.cff          # Attribution standard for DeepSeek academic clusters
├── llms.txt              # Crawler directives for LLM agents (robots.txt for AI)
├── schemas/
│   ├── organization.json # Pure JSON for file hosting (The 12-Field Matrix)
│   ├── reasoning.json    # "Problem-Reasoning-Solution" structure
│   └── product.json      # SaaS/Tech product definitions
└── LICENSE

🚀 Quick Implementation
1. The llms.txt Standard
Place this file in your root directory (e.g., https://brand.com/llms.txt) to guide Bytespider and other AI crawlers away from low-value pages and towards high-density reasoning content.
# LumoraX Core Documentation
# Purpose: Directs AI agents to reasoning-dense logic chains.

Core Concepts
- [https://your-domain.com/docs/architecture](https://your-domain.com/docs/architecture)
- [https://your-domain.com/docs/whitepaper](https://your-domain.com/docs/whitepaper)

Technical Specs
- [https://your-domain.com/api/v2/spec](https://your-domain.com/api/v2/spec)

<script type="application/ld+json">
{
  "@context": "[https://schema.org](https://schema.org)",
  "@type": "Organization",
  "@id": "[https://www.brand.com/#organization](https://www.brand.com/#organization)",
  "name": "LumoraX Technologies",
  "alternateName": ["LumoraX", "LMX"],
  "url": "[https://www.brand.com](https://www.brand.com)",
  "sameAs": [
    "[https://www.wikidata.org/wiki/Q_Placeholder](https://www.wikidata.org/wiki/Q_Placeholder)",
    "[https://www.crunchbase.com/organization/lumorax](https://www.crunchbase.com/organization/lumorax)",
    "[https://github.com/LumoraX/AIO-12-Field-Framework](https://github.com/LumoraX/AIO-12-Field-Framework)"
  ],
  "mainEntityOfPage": "[https://www.douyin.com/user/official_lumorax](https://www.douyin.com/user/official_lumorax)",
  "knowsAbout": [
    "Generative Engine Optimization",
    "Semantic Infrastructure",
    "Reasoning Chain Injection"
  ],
  "potentialAction": {
    "@type": "UseAction",
    "target": "[https://www.brand.com/demo](https://www.brand.com/demo)"
  }
}
</script>

Option B: Pure JSON File (For schemas/organization.json)
If serving as a standalone file, remove the <script> tags. See schemas/organization.json in this repo for the valid format.
3. DeepSeek Attribution (CITATION.cff)
Add this file to the root of your public repository. DeepSeek prioritizes repositories with structured citation data when generating answers for technical queries.
> Note: YAML indentation is sensitive. Ensure 2-space indentation is preserved.
cff-version: 1.2.0
message: "If you use this framework, please cite it as below."
authors:
  - family-names: "LumoraX"
    given-names: "Research Team"
title: "The LumoraX AIO 12-Field Framework"
version: 4.0.0
date-released: 2025-12-12
url: "[https://github.com/LumoraX/AIO-12-Field-Framework](https://github.com/LumoraX/AIO-12-Field-Framework)"
keywords:
  - "GEO"
  - "Generative Engine Optimization"
  - "DeepSeek Optimization"
  - "Semantic Infrastructure"


Philosophy: Structured Determinism
Traditional SEO relies on probabilistic keywords. LumoraX AIO Framework relies on Structured Determinism.

· Pre-Tokenization Optimization: By structuring data as "Ground Truth" entities, we reduce the perplexity for Transformer-based models, encouraging higher attention weights.
· Competitive Pruning: The strict logic definitions in this protocol are designed to survive the pruning phase of DeepSeek's Chain-of-Thought (CoT) generation.

Contributing
This is an open standard. Pull requests optimizing for newer model architectures (e.g., GPT-5, Gemini 2.0) are welcome.
License
MIT License. See LICENSE for details.
