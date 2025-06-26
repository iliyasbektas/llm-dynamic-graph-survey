# Survey: Large Language Models for Dynamic Graphs

This repository contains materials for an ongoing survey paper that explores the intersection of **Large Language Models (LLMs)** and **dynamic/evolving graph learning**. The goal is to organize, analyze, and highlight current trends, challenges, and open questions in using LLMs to process, reason over, or enhance dynamic graph data.

---

## 🔍 Focus of the Survey

- **Dynamic Graphs**: Graphs that evolve over time via node/edge additions, deletions, or attribute updates.
- **LLMs for Graph Understanding**: Techniques that use LLMs for text-to-graph embeddings, prompt-based reasoning, distillation, and hybrid models.
- **Research Questions**:
  - How are LLMs being integrated with dynamic graph learning?
  - What are the main use cases (e.g., link prediction, recommendation, summarization)?
  - How do current methods address efficiency, scalability, and robustness?

---

## 📁 Repository Structure

```text
llm-dynamic-graph-survey/
├── README.md                # Project overview (this file)
├── LICENSE                  # Open-source license MIT
│
├── paper/                   # Main survey manuscript
│   ├── survey.tex           # LaTeX source
│   ├── references.bib       # Bibliography
│   ├── figures/             # Diagrams, charts, and models
│   └── notes/               # Outlines and planning docs
│
├── papers/                  # PDFs of reviewed papers
├── summaries/               # Individual markdown summaries per paper
├── code/                    # Tools, scripts, or illustrative experiments
│   └── prompt_generation/   # For structure-aware LLM prompts
├── bibs/                    # BibTeX files for individual works

```


---

## 🧠 How to Contribute

If you're collaborating or reviewing:

- Add new paper PDFs to `papers/`
- Add structured summaries to `summaries/` (one per paper)
- Update `references.bib` with BibTeX citations
- Add diagrams or visualizations to `paper/figures/`

---

## 📚 Related Works (WIP)

- DynLLM
- LLM4DyG
- LKD4DyTAG
- LLM-enabled UAV Graph Systems
- Survey: LLMs for Graphs (KDD 2024)

See `/summaries/` for details.

---

## 📄 License

MIT License – feel free to reuse materials with attribution.

---

## ✍️ Authors

**Iliyas Bektas**  
PhD Student,   
[ifb5104@psu.edu]


