# Hi, I'm Chandrashekar DP 👋

**Senior AI Engineer · GenAI & LLM Systems · Open-Source Contributor**

> *"Build it end-to-end. Ship it. Then explain why it works."*

---

## 📄 Research

**Fragile Safety: Automated Circuit Discovery is Vulnerable to Dormant Feature Bundling**
*Chandrashekar DP — Zenodo Preprint, June 2026*

> Automated circuit discovery tools used for AI safety verification are structurally vulnerable to adversarial input manipulation. A linear probe achieving **97.5% accuracy on clean data** fails completely on adversarial inputs (**0% detection rate**). The adversarial distribution is geometrically inseparable from clean positives at the anchor token (cosine similarity 0.989). Reproduced on Pythia-410m. Practical mitigation: context-aware probing at the last sequence token achieves 100% adversarial detection with clean accuracy preserved. All experiments use TransformerLens and run on CPU.

📄 [Preprint — Zenodo](https://doi.org/10.5281/zenodo.20711675) · 💻 [Experiments code](https://github.com/chandrudp29/fragile-safety) · *arXiv submission pending endorsement*

---

## 🔭 What I'm currently working on

### Open-Source AI Research
- **[TransformerLens](https://github.com/TransformerLensOrg/TransformerLens)** — Contributing unit tests for architecture adapters in Google DeepMind's mechanistic interpretability library (3,500+ ⭐). 5 PRs submitted, 4 merged — covering GPT-Neo, GPT-NeoX, Apple OpenELM, LLaVA-OneVision, and LLaMA. Each PR adds production-quality test coverage (147 tests, 1,286 lines) for AI architectures used by safety researchers at Anthropic, Google DeepMind, and universities worldwide.

- **[enterprise-rag-patterns](https://github.com/chandrudp29/enterprise-rag-patterns)** — Production RAG architectures from my **"GenAI in Production"** newsletter. Code derived from real enterprise systems — not demo code.
  - `article-01`: Intelligent RCA Agent with Claude API + Databricks (80% triage reduction)
  - `article-02`: RAG Evaluation at scale — proxy metrics, embedding drift detection, labeled eval with Claude as judge

### Products I'm Building
- **[ComplianceShield](https://github.com/chandrudp29/ComplianceShield)** — AI compliance assistant with PII detection, session audit logging, multi-provider LLM support, and HITL review workflows. FastAPI + Streamlit + Docker. Built to solve the trust problem in enterprise AI deployments.

### Foundations (building from scratch)
- Working through **nanoGPT → micrograd → minbpe** (Karpathy's series) to understand transformers from raw math, not API calls
- Studying **mechanistic interpretability** via TransformerLens contributions — learning how attention heads and MLP circuits encode knowledge

---

## 💡 What I'm currently thinking about

- **The LLM observability gap**: LLMs are in production everywhere. Engineers have nothing equivalent to what researchers have in TransformerLens. No production-grade "Sentry for model reasoning." That's the problem I keep coming back to.

- **Why evaluation is harder than training**: Writing the RAG evaluation framework taught me that measuring whether an LLM is correct is a deeper problem than making it correct. Most teams skip it. The ones who don't, ship reliable AI.

- **Interpretability as infrastructure**: TransformerLens contributions are clarifying something — the people who build the measurement tools shape what the whole field builds next. Open-source research infrastructure is underrated leverage.

- **Foundations vs. APIs**: There's a big difference between engineers who use LLMs and engineers who understand them. Working through micrograd → nanoGPT is making that difference concrete for me.

---

## 📚 Currently reading / recently read

**AI & Research**
- *Concrete Problems in AI Safety* — Amodei et al.
- *Attention Is All You Need* — Vaswani et al.  
- Anthropic's Mechanistic Interpretability papers (superposition, features, circuits)
- Neel Nanda's mech interp blog posts

**Engineering**
- *Designing Machine Learning Systems* — Chip Huyen
- Building production RAG systems (hands-on, via enterprise-rag-patterns)

**Just for interest**
- *Thinking, Fast and Slow* — Daniel Kahneman
- My wife's opinions on everything (ongoing study, steep difficulty)

---

## 📫 Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-chandrudp-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/chandrudp)
[![GitHub](https://img.shields.io/badge/GitHub-chandrudp29-black?style=flat-square&logo=github)](https://github.com/chandrudp29)
[![Newsletter](https://img.shields.io/badge/Newsletter-GenAI%20in%20Production-orange?style=flat-square)](https://substack.com/@chandrashekar)
[![Email](https://img.shields.io/badge/Email-chandrudp29@gmail.com-red?style=flat-square&logo=gmail)](mailto:chandrudp29@gmail.com)

---

⚡ *Fun fact: I studied both AI interpretability research infrastructure and enterprise root cause analysis in the same week — and they're the same problem.*
