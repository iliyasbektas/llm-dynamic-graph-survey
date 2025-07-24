## Papers

### 2025

- [LKD4DyTAG: LLM-Driven Knowledge Distillation for Dynamic Text-Attributed Graphs](https://arxiv.org/pdf/2502.10914)  
  - Author(s): Amit Roy, Ning Yan, Masood Mortazavi  
  - Date: 2025-02-15  
  - Venue: AAAI 2025  

- [LLM-Based Multi-Agent Systems are Scalable Graph Generative Models](https://arxiv.org/pdf/2410.09824)  
  - Author(s): Jiarui Ji, Runlin Lei, Jialing Bi, Zhewei Wei, Xu Chen, Yankai Lin, Xuchen Pan, Yaliang Li, Bolin Ding  
  - Date: 2025-01-06 (v6)  
  - Venue: -  

- [SceneLLM: Dynamic Scene Graph Generation via Video-to-Language Mapping and Large Language Models](https://arxiv.org/pdf/2412.11026)  
  - Author(s): Hang Zhang, Zhuoling Li, Jun Liu  
  - Date: 2025-05-07 (v2)  
  - Venue: -  

- [GraphVideoAgent: LLM-Guided Dynamic Entity Graph Reasoning for Long Video Understanding](https://arxiv.org/pdf/2501.15953)  
  - Author(s): Meng Chu, Yicong Li, Tat-Seng Chua  
  - Date: 2025-01-27  
  - Venue: -  

- [TGL-LLM: Integrating Temporal Graph Learning into LLM-Based Temporal Knowledge Graph Forecasting](https://arxiv.org/pdf/2501.11911)  
  - Author(s): He Chang, Jie Wu, Zhulin Tao, Yunshan Ma, Xianglin Huang, Tat-Seng Chua  
  - Date: 2025-01-21  
  - Venue: -  

- [LLM-DR: Rule Generation with Diffusion and LLM Constraints for Temporal Knowledge Graphs](https://ojs.aaai.org/index.php/AAAI/article/view/33249)  
  - Author(s): Kai Chen, Xin Song, Ye Wang, Liqun Gao, Aiping Li, Xiaojuan Zhao, Bin Zhou, Yalong Xie  
  - Date: 2025-04-11  
  - Venue: AAAI Technical Track on Data Mining & Knowledge Management I  

### 2024

- [DynLLM: Integrating LLM-Based Profiles with Dynamic Graph Recommendation](https://arxiv.org/pdf/2405.07580)  
  - Author(s): Ziwei Zhao, Fake Lin, Xi Zhu, Zhi Zheng, Tong Xu, Shitian Shen, Xueying Li, Zikai Yin, Enhong Chen  
  - Date: 2024-05-13  
  - Venue: -  

- [LLM-enabled UAV Graph Systems: Integrating Language Models for Dynamic Networked Decision-Making](https://arxiv.org/pdf/2407.20840)  
  - Author(s): Geng Sun, Yixian Wang, Dusit Niyato, Jiacheng Wang, Xinying Wang, H. Vincent Poor, Khaled B. Letaief  
  - Date: 2024-07-30  
  - Venue: -  

- [LLM-Guided Dynamic Adaptation for Temporal Knowledge Graph Reasoning](https://arxiv.org/pdf/2405.14170)  
  - Author(s): Jiapu Wang, Kai Sun, Linhao Luo, Wei Wei, Yongli Hu, Alan Wee-Chung Liew, Shirui Pan, Baocai Yin  
  - Date: 2024-12-30 (v3)  
  - Venue: NeurIPS 2024  

- [GAG: Dynamic and Textual Graph Generation via Large-Scale LLM-Based Agent Simulation](https://arxiv.org/html/2410.09824v1)  
  - Author(s): Jiarui Ji, Runlin Lei, Jialing Bi, Zhewei Wei, Yankai Lin, Xuchen Pan, Yaliang Li, Bolin Ding  
  - Date: 2024-10-13  
  - Venue: -  

- [AnomalyLLM: Few-shot Anomaly Edge Detection for Dynamic Graphs using Large Language Models](https://arxiv.org/pdf/2405.07626)  
  - Author(s): Shuo Liu, Di Yao, Lanting Fang, Zhetao Li, Wenbin Li, Kaiyu Feng, XiaoWen Ji, Jingping Bi  
  - Date: 2024-08-28 (v2)  
  - Venue: 2024 IEEE International Conference on Data Mining (ICDM)  

- [CasMLN: Cascaded Multi-Level Learning on Temporal Heterogeneous Graphs with LLM Knowledge](https://dl.acm.org/doi/10.1145/3626772.3657731)  
  - Author(s): Fengyi Wang, Guanghui Zhu, Chunfeng Yuan, Yihua Huang  
  - Date: 2024  
  - Venue: SIGIR 2024  

- [DTGB: A Benchmark Suite for Dynamic Text-Attributed Graphs](https://arxiv.org/pdf/2406.12072)  
  - Author(s): Jiasheng Zhang, Jialin Chen, Menglin Yang, Aosong Feng, Shuang Liang, Jie Shao, Rex Ying  
  - Date: 2024-11-04 (v3)  
  - Venue: NeurIPS 2024 Datasets and Benchmarks Track  

### 2023

- [LLM4DyG: Can Large Language Models Solve Spatial-Temporal Problems on Dynamic Graphs?](https://arxiv.org/pdf/2310.17110)  
  - Author(s): Zeyang Zhang, Xin Wang, Ziwei Zhang, Haoyang Li, Yijian Qin, Wenwu Zhu  
  - Date: 2024-07-08 (v3)  
  - Venue: KDD 2024  
 Dynamic Graphs

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


See `/summaries/` for details.

---

## 📄 License

MIT License – feel free to reuse materials with attribution.

---

## ✍️ Authors

**Iliyas Bektas**  
PhD Student,   
[ifb5104@psu.edu]

**Suhang Wang**  
Associate Professor,   
[szw494@psu.edu]


