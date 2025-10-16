# LLMs & Dynamic Graph Learning: Survey Repository

---

This repository contains materials for an ongoing **survey paper** that explores the intersection of **Large Language Models (LLMs)** and **dynamic/evolving graph learning**. The goal is to organize, analyze, and highlight current trends, challenges, and open questions in using LLMs to process, reason over, or enhance dynamic graph data.

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
- Update the README.md to include the new paper entry in the appropriate year section

---

## 📚 Papers

### 2025

- [Leveraging temporal validity of rules via LLMs for enhanced temporal knowledge graph reasoning](https://www.sciencedirect.com/science/article/pii/S0950705125011396?casa_token=pkKfK3WZ08AAAAAA:QTEaOlBPSVcRZvbooQpOTdKXHRf-gzTp3x9LBZUhPactEAJJ3XK4wtcGFBwUwK8JU6AmKx4oOBk)  
  - Author(s): Qihong Pan, Limin Yao, Guojiang Shen, Xiao Han, Yichuan Chen, Xiangjie Kong  
  - Date: 2025-10-09  
  - Venue: Knowledge-Based Systems  

- [Using Large Language Models to Tackle Fundamental Challenges in Graph Learning: A Comprehensive Survey](https://arxiv.org/pdf/2505.18475)  
  - Author(s): Mengran Li, Pengyu Zhang, Wenbin Xing, Yijia Zheng, Klim Zaporojets, Junzhou Chen, Ronghui Zhang, Yong Zhang, Siyuan Gong, Jia Hu, Xiaolei Ma, Zhiyuan Liu, Paul Groth, Marcel Worring  
  - Date: 2025-05-27  
  - Venue: Preprint submitted to Elsevier  

<!-- This looks like a CV paper. Is this relevant? -->
- [SceneLLM: Dynamic Scene Graph Generation via Video-to-Language Mapping and Large Language Models](https://arxiv.org/pdf/2412.11026)  
  - Author(s): Hang Zhang, Zhuoling Li, Jun Liu  
  - Date: 2025-05-07 (v2)  
  - Venue: -  

- [Unifying Text Semantics and Graph Structures for Temporal Text-attributed Graphs with Large Language Models](https://arxiv.org/pdf/2503.14411)  
  - Author(s): Siwei Zhang, Yun Xiong, Yateng Tang, Xi Chen, Zian Jia, Zehao Gu, Jiarong Xu, Jiawei Zhang  
  - Date: 2025-05-19 (v2)  
  - Venue: Preprint  

- [A Survey on Temporal Interaction Graph Representation Learning: Progress, Challenges, and Opportunities](https://arxiv.org/pdf/2505.04461)  
  - Author(s): Pengfei Jiao, Hongjiang Chen, Xuan Guo, Zhidong Zhao, Dongxiao He, Di Jin  
  - Date: 2025-05-07  
  - Venue: IJCAI 2025 Survey Track  

- [LLM-DR: Rule Generation with Diffusion and LLM Constraints for Temporal Knowledge Graphs](https://ojs.aaai.org/index.php/AAAI/article/view/33249)  
  - Author(s): Kai Chen, Xin Song, Ye Wang, Liqun Gao, Aiping Li, Xiaojuan Zhao, Bin Zhou, Yalong Xie  
  - Date: 2025-04-11  
  - Venue: AAAI Technical Track on Data Mining & Knowledge Management I  

- [Marrying LLMs with Dynamic Forecasting: A Graph Mixture-of-expert Perspective](https://aclanthology.org/2025.findings-naacl.24.pdf)  
  - Author(s): Dapeng Jiang, Xiao Luo  
  - Date: 2025-04 (Findings of NAACL 2025)  
  - Venue: Findings of the Association for Computational Linguistics: NAACL 2025  

- [Ignite Forecasting with SPARK: An Efficient Generative Framework for Refining LLMs in Temporal Knowledge Graph Forecasting](https://arxiv.org/pdf/2503.22748)  
  - Author(s): Gongzhu Yin, Hongli Zhang, Yi Luo, Yuchen Yang, Kun Lu, Chao Meng  
  - Date: 2025-03-27  
  - Venue: -  

- [LKD4DyTAG: LLM-Driven Knowledge Distillation for Dynamic Text-Attributed Graphs](https://arxiv.org/pdf/2502.10914)  
  - Author(s): Amit Roy, Ning Yan, Masood Mortazavi  
  - Date: 2025-02-15  
  - Venue: AAAI 2025  

- [Can Large Language Models Effectively Modify Graphs?](https://openreview.net/pdf?id=WRKVA3TgSv)  
  - Author(s): Cazamere Comrie, Jon Kleinberg  
  - Date: 2025-02-05  
  - Venue: ICLR 2025 (Submitted)  

- [Interactions Exhibit Clustering Rhythm: A Prevalent Observation for Advancing Temporal Link Prediction](https://openreview.net/pdf?id=JZOPwrRYtI)  
  - Author(s): Siwei Zhang, Xi Chen, Yun Xiong, Xixi Wu, Yizhu Jiao, Yao Zhang, Mingyang Zhang, Tengfei Liu, Weiqiang Wang, Jiawei Zhang  
  - Date: 2025-02-05  
  - Venue: ICLR 2025 (Submitted)  

- [GraphVideoAgent: LLM-Guided Dynamic Entity Graph Reasoning for Long Video Understanding](https://arxiv.org/pdf/2501.15953)  
  - Author(s): Meng Chu, Yicong Li, Tat-Seng Chua  
  - Date: 2025-01-27  
  - Venue: -  

- [TGL-LLM: Integrating Temporal Graph Learning into LLM-Based Temporal Knowledge Graph Forecasting](https://arxiv.org/pdf/2501.11911)  
  - Author(s): He Chang, Jie Wu, Zhulin Tao, Yunshan Ma, Xianglin Huang, Tat-Seng Chua  
  - Date: 2025-01-21  
  - Venue: -  

- [Multivariate Wireless Link Quality Prediction Based on Pre-trained Large Language Models](https://arxiv.org/pdf/2501.11247)  
  - Author(s): Zhuangzhuang Yan, Xinyu Gu, Shilong Fan, Zhenyu Liu  
  - Date: 2025-01-20  
  - Venue: -  

- [LLM-Based Multi-Agent Systems are Scalable Graph Generative Models](https://arxiv.org/pdf/2410.09824)  
  - Author(s): Jiarui Ji, Runlin Lei, Jialing Bi, Zhewei Wei, Xu Chen, Yankai Lin, Xuchen Pan, Yaliang Li, Bolin Ding  
  - Date: 2025-01-06 (v6)  
  - Venue: -  

- [Are Large Language Models Good Temporal Graph Learners?](https://arxiv.org/pdf/2506.05393)  
  - Author(s): Shenyang Huang, Ali Parviz, Emma Kondrup, Zachary Yang, Zifeng Ding, Michael Bronstein, Reihaneh Rabbany, Guillaume Rabusseau  
  - Date: 2025-06-03  
  - Venue: -  

- [Unlocking Multi-Modal Potentials for Link Prediction on Dynamic Text-Attributed Graphs](https://arxiv.org/pdf/2502.19651)  
  - Author(s): Yuanyuan Xu, Wenjie Zhang, Ying Zhang, Xuemin Lin, Xiwei Xu  
  - Date: 2025-08-01 (v2)  
  - Venue: AAAI 2026 (Copyright © 2026 AAAI)  

---

### 2024

- [LLM-Guided Dynamic Adaptation for Temporal Knowledge Graph Reasoning](https://arxiv.org/pdf/2405.14170)  
  - Author(s): Jiapu Wang, Kai Sun, Linhao Luo, Wei Wei, Yongli Hu, Alan Wee-Chung Liew, Shirui Pan, Baocai Yin  
  - Date: 2024-12-30 (v3)  
  - Venue: NeurIPS 2024  

- [DTGB: A Benchmark Suite for Dynamic Text-Attributed Graphs](https://arxiv.org/pdf/2406.12072)  
  - Author(s): Jiasheng Zhang, Jialin Chen, Menglin Yang, Aosong Feng, Shuang Liang, Jie Shao, Rex Ying  
  - Date: 2024-11-04 (v3)  
  - Venue: NeurIPS 2024 Datasets and Benchmarks Track  

<!-- Is this relevant? -->
- [GAG: Dynamic and Textual Graph Generation via Large-Scale LLM-Based Agent Simulation](https://arxiv.org/html/2410.09824v1)  
  - Author(s): Jiarui Ji, Runlin Lei, Jialing Bi, Zhewei Wei, Yankai Lin, Xuchen Pan, Yaliang Li, Bolin Ding  
  - Date: 2024-10-13  
  - Venue: -  

- [AgentKit: Structured LLM Reasoning with Dynamic Graphs](https://arxiv.org/pdf/2404.11483)  
  - Author(s): Yue Wu, Yewen Fan, So Yeon Min, Shrimai Prabhumoye, Stephen McAleer, Yonatan Bisk, Ruslan Salakhutdinov, Yuanzhi Li, Tom Mitchell  
  - Date: 2024-07-24 (v2)  
  - Venue: COLM 2024  

- [AnomalyLLM: Few-shot Anomaly Edge Detection for Dynamic Graphs using Large Language Models](https://arxiv.org/pdf/2405.07626)  
  - Author(s): Shuo Liu, Di Yao, Lanting Fang, Zhetao Li, Wenbin Li, Kaiyu Feng, XiaoWen Ji, Jingping Bi  
  - Date: 2024-08-28 (v2)  
  - Venue: 2024 IEEE International Conference on Data Mining (ICDM)  

- [Large Language Model (LLM)-enabled Graphs in Dynamic Networking](https://arxiv.org/pdf/2407.20840)  
  - Author(s): Geng Sun, Yixian Wang, Dusit Niyato, Jiacheng Wang, Xinying Wang, H. Vincent Poor, Khaled B. Letaief  
  - Date: 2024-07-30  
  - Venue: -  

- [CasMLN: Cascaded Multi-Level Learning on Temporal Heterogeneous Graphs with LLM Knowledge](https://dl.acm.org/doi/10.1145/3626772.3657731)  
  - Author(s): Fengyi Wang, Guanghui Zhu, Chunfeng Yuan, Yihua Huang  
  - Date: 2024-07-11  
  - Venue: SIGIR 2024  

- [LLM4DyG: Can Large Language Models Solve Spatial-Temporal Problems on Dynamic Graphs?](https://arxiv.org/pdf/2310.17110)  
  - Author(s): Zeyang Zhang, Xin Wang, Ziwei Zhang, Haoyang Li, Yijian Qin, Wenwu Zhu  
  - Date: 2024-07-08 (v3)  
  - Venue: KDD 2024  

- [DARG: Dynamic Evaluation of Large Language Models via Adaptive Reasoning Graph](https://arxiv.org/pdf/2406.17271)  
  - Author(s): Zhehao Zhang, Jiaao Chen, Diyi Yang  
  - Date: 2024-06-25  
  - Venue: -  

- [DynLLM: Integrating LLM-Based Profiles with Dynamic Graph Recommendation](https://arxiv.org/pdf/2405.07580)  
  - Author(s): Ziwei Zhao, Fake Lin, Xi Zhu, Zhi Zheng, Tong Xu, Shitian Shen, Xueying Li, Zikai Yin, Enhong Chen  
  - Date: 2024-05-13  
  - Venue: -  
---
## 📄 License

MIT License – feel free to reuse materials with attribution.

---

## ✍️ Authors

**Iliyas Bektas**  
PhD Student, Penn State University  
[ifb5104@psu.edu]

**Suhang Wang**  
Associate Professor, Penn State University  
[szw494@psu.edu]
