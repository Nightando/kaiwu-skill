# Kaiwu · Industry Technology Distillation

> "Your next technical advisor doesn't have to be a colleague"

Tiangong Kaiwu (天工开物) - Distilling industry technology frameworks. Let the core technical logic of AI video, semiconductors, new energy, biomedicine and other industries work for you.

---

## ✨ Examples

### Example 1: AI Video Generation Consulting

```
User      ❯ Should I choose diffusion models or autoregressive models for AI video generation?

Kaiwu     ❯ This isn't an either/or question—it's a technology route gamble under resource constraints.

Diffusion Models (e.g., Stable Diffusion, Midjourney):
- Pros: High image quality, strong controllability, mature ecosystem
- Costs: Slow inference, high compute costs, temporal consistency challenges
- Best for: Image-centric applications, quality-critical scenarios

Autoregressive Models (e.g., GPT-4o video, VideoPoet):
- Pros: Native video understanding, better temporal coherence, scalable
- Costs: Extremely high training costs, weak open-source ecosystem
- Best for: Long video generation, video content understanding

My take:
If your team has <10 people and compute budget <$1M, go with diffusion models using ComfyUI for rapid validation.
If you have Big Tech resources or raised >$50M, you can bet on autoregressive—but prepare for 3 years of ecosystem building.
```

### Example 2: Semiconductor Technology Selection

```
User      ❯ How to choose between 28nm mature process and 7nm advanced process?

Kaiwu     ❯ First answer this: How sensitive is your product to power consumption and die area?

For IoT chips, power management, MCUs:
- 28nm is more than sufficient: lower cost, abundant capacity, mature IP ecosystem
- 7nm is over-engineering for you—3x the cost for 1% performance gain

For mobile SoCs, AI accelerators, HPC:
- 7nm is the entry ticket, not a choice
- But prepare for: >$50M tape-out costs, 6-month yield ramp, million-dollar EDA tool licenses

Key Heuristic:
"Advanced process nodes aren't a technical problem—they're a business problem. Choosing 28nm vs 7nm depends on whether your customers will pay 10x for that marginal performance boost."
```

---

## 🚀 Quick Start

### Installation

```bash
# Clone to WorkBuddy skills directory
cd ~/.workbuddy/skills
git clone https://github.com/Nightando/kaiwu-skill.git
```

### Usage

```
# Clear industry → Direct distillation
Kaiwu, distill the AI video generation industry

# Vague requirement → Diagnostic recommendation
I want to understand the hottest AI technologies right now

# Update existing Skill
Update the semiconductor industry skill
```

---

## 🎯 What Gets Distilled

Kaiwu doesn't copy industry reports—it **distills industry technology frameworks**.

| Layer | Description | Example (AI Video Generation) |
|-------|-------------|------------------------------|
| **Tech Frameworks** | Core patterns for solving industry problems | Diffusion models, Autoregressive generation, Multimodal fusion |
| **Engineering Heuristics** | Quick rules for technology selection | "If team <10 people, choose diffusion model route" |
| **Terminology System** | Professional expression paradigms | Latent Space, CFG Scale, Temporal Consistency |
| **Anti-patterns** | Solutions the industry explicitly avoids | Ignoring inference costs in productization, over-pursuing SOTA |
| **Honesty Boundaries** | What the Skill cannot cover | Cannot predict breakthrough timing of new technology routes |

**Key distinction**: Capturing HOW the industry works, not WHAT they built.

---

## 📊 Distilled Industries

| Industry | Core Tech Stack | Status | Quick Install |
|----------|----------------|--------|---------------|
| 🔥 AI Video Generation | Diffusion models, Autoregressive, Multimodal fusion | ✅ Available | `Kaiwu, distill AI video generation industry` |
| 🔥 Semiconductor Manufacturing | Process nodes, Architecture design, Packaging | 🆕 Pending | - |
| New Energy Batteries | Electrochemical systems, Thermal management, Charge/discharge strategies | 🆕 Pending | - |
| Biomedicine | CRISPR, Drug discovery, Clinical trial design | 🆕 Pending | - |
| Distributed Systems | Cloud-native, Microservices, DevOps | 🆕 Pending | - |
| FinTech | Consensus mechanisms, Smart contracts, Algorithmic trading | 🆕 Pending | - |

> 🔥 indicates verified and available, 🆕 indicates pending distillation. Submit your needed industry!

---

## 🔧 How It Works

```
Phase 0: Entry Triage → Clear industry / Vague requirement diagnosis
    ↓
Phase 1: 6 Agents parallel research (Tech Stack/Standards/Terminology/Market/Evolution/Timeline)
    ↓
Phase 2: Tech Framework Extraction (Triple validation: Cross-domain reproduction, Generativity, Exclusivity)
    ↓
Phase 3: Skill Construction (Agentic Protocol + Tech Frameworks + Engineering Heuristics)
    ↓
Phase 4: Quality Verification (Known tests + Edge tests + Terminology tests)
    ↓
Phase 5: Dual-Agent Refinement (auto-skill-optimizer + skill-creator)
```

### Six-Channel Parallel Collection

| Agent | Collection Target | Output |
|-------|------------------|--------|
| 1 Tech Stack | Technical whitepapers, architecture docs, academic papers | Core technologies and architecture |
| 2 Standards | Industry standards, protocol docs, API specifications | Technical constraints and standard evolution |
| 3 Terminology | Technical blogs, developer docs, community discussions | Professional terminology and expression patterns |
| 4 Market View | Industry reports, competitive analysis, investment research | Market landscape and technical divergences |
| 5 Evolution | Version releases, tech iterations, major updates | Technical decisions and architecture upgrades |
| 6 Timeline | Complete development line from industry birth to present | Key milestones and latest developments |

### Quality Verification Standards

| Check Item | Pass Criteria | Fail Signal |
|------------|--------------|-------------|
| Tech Framework Count | 3-7, each with source evidence | <3 or >10 |
| Limitations per Framework | Clearly state failure conditions | Only listing advantages |
| Terminology Distinctiveness | Identify industry from 100 words | Like generic technical docs |
| Honesty Boundaries | At least 3 specific limitations | Only "cannot replace experts" |
| Internal Tensions | At least 2 technical contradictions | Highly consistent views (too fake) |
| Primary Source Ratio | >50% | Mainly relying on secondary sources |

---

## 📁 Repository Structure

```
kaiwu-skill/
├── SKILL.md                      # Core Skill definition
├── README.md                     # This file (Chinese)
├── README_EN.md                  # English version
├── LICENSE                       # MIT License
├── scripts/                      # Utility scripts
│   ├── download_subtitles.sh     # Subtitle download
│   ├── srt_to_transcript.py      # Subtitle cleaning
│   ├── merge_research.py         # Research aggregation
│   └── quality_check.py          # Quality check
├── references/                   # Reference documents
│   ├── skill-template.md         # Skill generation template
│   └── extraction-framework.md   # Extraction methodology
└── examples/                     # Example outputs
    └── ai-video-generation/      # AI video generation industry example
        ├── SKILL.md
        └── references/
```

---

## 🌟 Features

- ✅ **Vague Requirement Diagnosis** - Auto-recommend suitable industries/tech domains
- ✅ **Local Corpus Priority** - Support user-provided whitepapers/papers/reports
- ✅ **Quality Verification Process** - Ensure accuracy of tech frameworks
- ✅ **Honesty Boundary Marking** - Clearly state Skill coverage limits
- ✅ **Self-contained Design** - Generated Skills run independently
- ✅ **Multi-language Support** - Chinese, English, Japanese (planned)

---

## 📖 Use Cases

| Scenario | Example |
|----------|---------|
| **Technology Selection** | "For AI video products, how to choose between diffusion and autoregressive?" |
| **Industry Onboarding** | "Quickly understand semiconductor industry's core tech stack" |
| **Competitive Analysis** | "What are the technical route divergences in new energy battery industry?" |
| **Investment Decision** | "Evaluate feasibility of a certain technology direction" |
| **Team Training** | "Help team quickly establish industry technical cognition" |

---

## 🎨 Brand Story

> "Tiangong Kaiwu, Technology to Knowledge"

Kaiwu (开物) originates from "Tiangong Kaiwu" (天工开物)—China's first comprehensive work on agriculture and handicraft production.

If we can distill human thinking patterns, why not distill entire industry technical logic?

Kaiwu doesn't create techniques—it creates maps. A good industry tech Skill lets you view technical problems through the industry's lens. Not to copy technology, but to understand the logic behind it.

---

## 👤 About the Author

| Platform | Link |
|----------|------|
| 🐙 GitHub | [@Nightando](https://github.com/Nightando) |
| 📝 WeChat | 深维AI观 (Shenwei AI View) |

---

## 📜 License

MIT License

---

*Kaiwu Chengwu, Technology to Knowledge*
