<div align="center">

<img src="https://github.com/carpool11.png" width="120" alt="carpool11"/>

# Hi, I'm carpool11

<img src="https://komarev.com/ghpvc/?username=carpool11&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile Views"/>

### 研究生一年级 · NLP 与大语言模型 · 检索增强与模型微调

**从公式手推到工程落地，做可复现、可量化的项目**

<p>
  <a href="https://github.com/carpool11">
    <img src="https://img.shields.io/badge/GitHub-carpool11-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.guet.edu.cn">
    <img src="https://img.shields.io/badge/GUET-桂林电子科技大学-005BAC?style=for-the-badge&logo=schooloflife&logoColor=white" alt="GUET"/>
  </a>
  <a href="mailto:13307853713@163.com">
    <img src="https://img.shields.io/badge/Email-13307853713%40163.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

</div>

---

## 关于我 | About Me

### 中文

* **桂林电子科技大学（GUET）** 研究生一年级在读，方向为 **自然语言处理与大语言模型应用**
* 已完成 **BERT + CRF 中文命名实体识别**，设计三组消融实验，验证集 F1 达 **92.68%**
* 已完成 **Qwen2.5-0.5B 的 LoRA 指令微调** 与 **双路召回重排 RAG**，检索 Hit@1 100%、端到端问答 12/12
* 坚持 **白盒实现**：不依赖高层封装框架，检索与相似度计算全部手写 PyTorch
* 习惯用 **消融实验与量化指标** 验证每一次设计改动，而不是只看最终效果
* 正在推进 **vLLM 推理加速、Agent 工作流与服务化部署**（FastAPI / Gradio）
* 可以交流 **Python / PyTorch / Transformers / LoRA / RAG / NER / BM25 / BGE**
* 联系方式：**[13307853713@163.com](mailto:13307853713@163.com)**

### English

* First-year master's student at **Guilin University of Electronic Technology (GUET)**, focused on **NLP and LLM applications**
* Built **Chinese NER with BERT + CRF** with three ablation studies, dev F1 **92.68%**
* Fine-tuned **Qwen2.5-0.5B with LoRA** and built a **hybrid retrieval RAG** pipeline: Hit@1 100%, end-to-end QA 12/12
* Prefer **white-box implementations**: retrieval and similarity computed with hand-written PyTorch instead of high-level wrappers
* Validate every design change with **ablation studies and quantitative metrics**
* Currently working on **vLLM inference, Agent workflows and serving** (FastAPI / Gradio)
* Ask me about **Python / PyTorch / Transformers / LoRA / RAG / NER / BM25 / BGE**
* Contact: **[13307853713@163.com](mailto:13307853713@163.com)**

---

## 研究方向 | Research Interests

<div align="center">

<img src="https://img.shields.io/badge/LLM_Fine_Tuning-333333?style=for-the-badge" alt="LLM Fine-Tuning"/>
<img src="https://img.shields.io/badge/RAG-333333?style=for-the-badge" alt="RAG"/>
<img src="https://img.shields.io/badge/Information_Extraction-333333?style=for-the-badge" alt="Information Extraction"/>
<img src="https://img.shields.io/badge/Reranking-333333?style=for-the-badge" alt="Reranking"/>
<img src="https://img.shields.io/badge/LLM_Inference-333333?style=for-the-badge&logo=nvidia&logoColor=76B900" alt="LLM Inference"/>
<img src="https://img.shields.io/badge/NLP-333333?style=for-the-badge" alt="NLP"/>

</div>

<br>

| Research Area | 说明 |
| :--- | :--- |
| LLM Fine-Tuning | LoRA / QLoRA 低秩适配、指令微调与低显存训练优化 |
| Retrieval-Augmented Generation | 文档分块、向量化、稀疏与稠密双路召回 |
| Information Extraction | 中文命名实体识别、BIO 标注体系、序列标注 |
| Embedding & Reranking | BGE 向量模型与 Cross-Encoder 重排序，用 MRR 量化评估 |
| LLM Inference & Serving | vLLM 推理加速、FastAPI 封装与演示前端（进行中） |
| Agent Applications | 工具调用与工作流编排（进行中） |

---

## 技术栈 | Tech Stack

### AI / Deep Learning

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch" alt="Python and PyTorch"/>

<br><br>

<img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000000" alt="Transformers"/>
<img src="https://img.shields.io/badge/PEFT-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000000" alt="PEFT"/>
<img src="https://img.shields.io/badge/LoRA-412991?style=for-the-badge" alt="LoRA"/>
<img src="https://img.shields.io/badge/ModelScope-3B7DDD?style=for-the-badge" alt="ModelScope"/>
<img src="https://img.shields.io/badge/Accelerate-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000000" alt="Accelerate"/>

</div>

**实践重点：** 模型加载与显存控制、LoRA 挂载与增量权重保存、指令数据构造、消融实验设计。

### NLP / RAG

<div align="center">

<img src="https://img.shields.io/badge/BM25-095AA7?style=for-the-badge" alt="BM25"/>
<img src="https://img.shields.io/badge/jieba-00B96B?style=for-the-badge" alt="jieba"/>
<img src="https://img.shields.io/badge/BGE_Embedding-7C3AED?style=for-the-badge" alt="BGE Embedding"/>
<img src="https://img.shields.io/badge/BGE_Reranker-7C3AED?style=for-the-badge" alt="BGE Reranker"/>
<img src="https://img.shields.io/badge/CRF-1F2937?style=for-the-badge" alt="CRF"/>
<img src="https://img.shields.io/badge/BIO_Tagging-1F2937?style=for-the-badge" alt="BIO Tagging"/>

</div>

**实践重点：** 中文分词与稀疏检索、稠密向量召回、交叉注意力重排、实体级 F1 与 Hit@K / MRR 评测。

### Development Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,vscode,linux,md" alt="Git, GitHub, VS Code, Linux and Markdown"/>

</div>

---

## 开源项目 | Featured Projects

### [Qwen-RAG-NER-Pipeline](https://github.com/carpool11/Qwen-RAG-NER-Pipeline)

[![Repo](https://img.shields.io/badge/GitHub-Qwen--RAG--NER--Pipeline-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/carpool11/Qwen-RAG-NER-Pipeline)

**基于大模型指令微调与双路重排检索增强的垂直领域问答系统**，全流程不依赖 LangChain 等封装框架，可在 4GB 显存笔记本上复现。

* **指令微调：** 32 条样本下用 LoRA 微调 Qwen2.5-0.5B-Instruct，使其严格按 JSON 输出 PERSON / COUNTRY / CITY 实体。
* **白盒检索：** 手写 PyTorch 完成文档向量化、余弦相似度矩阵与 Top-K 检索，不调用任何检索框架。
* **双路召回与重排：** jieba + BM25 稀疏路负责低频专有名词，bge-small-zh-v1.5 稠密路负责语义匹配，由 bge-reranker-base 交叉注意力统一打分。
* **量化评测：** 四组消融实验对比 BM25、纯向量、RRF 融合与重排方案，Hit@1 从 83.3% 提升至 100%，MRR 1.0000，端到端问答 12/12。

**Tech Stack:** `Python` · `PyTorch` · `Qwen2.5-0.5B` · `PEFT (LoRA)` · `BM25` · `BGE Embedding / Reranker`

---

### [chinese-ner-bert-crf](https://github.com/carpool11/chinese-ner-bert-crf)

[![Repo](https://img.shields.io/badge/GitHub-chinese--ner--bert--crf-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/carpool11/chinese-ner-bert-crf)

**基于 BERT + CRF 的中文命名实体识别系统**，覆盖数据处理、模型搭建、训练与消融实验的完整链路。

* **模型结构：** BERT 编码 + CRF 转移约束 + Viterbi 解码，解决 softmax 独立标注的标签非法转移问题。
* **消融实验：** 三组对比实验（冻结与解冻 BERT、分层学习率、CRF 与 Softmax 标注），验证集最佳 F1 达 **92.68%**。
* **工程实践：** 数据集划分与断点续训、子词对齐与 label 掩码、entity-level F1 评测。

**Tech Stack:** `Python` · `PyTorch` · `Transformers` · `BERT-base-chinese` · `CRF`

---

<div align="center">

### 从原理出发，用数据说话

**Keep Learning · Keep Building**

⭐ From [carpool11](https://github.com/carpool11)

</div>
