# Kalyanamastu

### A Benchmark for Cultural Understanding

**Kalyanamastu** is a benchmark dataset designed to evaluate the ability of AI systems to understand **cultural rituals, traditions, practices, and their contextual significance**.

The initial release focuses on **Tamil and Telugu cultural contexts**, with the goal of developing more culturally grounded and context-aware AI systems.

> **Can AI understand culture beyond language?**

---

## Why Kalyanamastu?

Current AI benchmarks often evaluate language, reasoning, knowledge, and multimodal understanding while giving limited attention to **cultural context**.

Cultural practices are rarely isolated facts. Their meaning depends on context—including **rituals, traditions, social practices, language, symbolism, communities, and regional variations**.

Kalyanamastu aims to provide a structured benchmark for studying this dimension of intelligence.

---

## Scope

The initial version of Kalyanamastu focuses on:

* 🇮🇳 Tamil cultural contexts
* 🇮🇳 Telugu cultural contexts
* Rituals and ceremonies
* Traditional practices
* Cultural objects and symbols
* Festivals and celebrations
* Social and familial traditions
* Cultural context and significance

The benchmark is designed to be extensible to additional cultures and cultural contexts.

---

## Benchmark Tasks

Kalyanamastu can support research on:

1. **Cultural Recognition**
   Can an AI system identify a cultural practice or ritual?

2. **Cultural Understanding**
   Can it explain what a practice means within its cultural context?

3. **Contextual Reasoning**
   Can it distinguish between similar practices and understand when and why they occur?

4. **Cultural Grounding**
   Can an AI system provide culturally appropriate interpretations rather than relying on generic or stereotypical knowledge?

---

## Dataset

Each instance may contain structured information such as:

```json
{
  "culture": "Telugu",
  "category": "Ritual",
  "name": "...",
  "description": "...",
  "context": "...",
  "significance": "...",
  "region": "...",
  "source": "..."
}
```

The exact schema and annotation guidelines are available in [`data/schemas`](data/schemas/) and [`annotations`](annotations/).

---

## Research Questions

Kalyanamastu is intended to support research into questions such as:

* How well do AI models understand culturally specific practices?
* Do multilingual models understand culture beyond linguistic patterns?
* Can models distinguish culturally similar but contextually different practices?
* How does cultural grounding affect reasoning and generation?
* Where do current AI systems exhibit cultural gaps or misconceptions?

---

## Dataset Design

The dataset is being developed with an emphasis on:

**Cultural specificity · Context · Diversity · Traceability · Evaluation**

Each entry is intended to capture not only *what* a practice is, but also **where, when, why, and how it is understood within its cultural context**.

---

## Status

🚧 **Kalyanamastu is currently under development.**

The initial release focuses on Tamil and Telugu cultural contexts. Dataset size, annotation methodology, benchmark tasks, and evaluation protocols will evolve across releases.

---

## Contributing

We welcome contributions from researchers, cultural practitioners, linguists, domain experts, and the open-source community.

Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) before submitting data, annotations, corrections, or benchmark tasks.

---

## Citation

If you use Kalyanamastu in your research, please cite:

```bibtex
@dataset{kalyanamastu,
  title        = {Kalyanamastu: A Benchmark for Cultural Understanding},
  author       = {Parasa, Niharika Sri},
  year         = {2026},
  publisher    = {GitHub},
  url          = {<repository-url>}
}
```

---

## License

See [`LICENSE`](LICENSE) for the terms of use.

---

### Building AI that understands culture.

** Srirastu Shubhamastu Kalyanamastu**
