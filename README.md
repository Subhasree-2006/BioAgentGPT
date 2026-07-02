# BioAgentGPT
A Multi-Agent Retrieval-Augmented Generation (RAG) system for biomedical literature analysis using Qwen2.5, LangGraph, FAISS, PubMed, and Gradio.

# 🧬 BioAgentGPT

> **A Multi-Agent Retrieval-Augmented Generation (RAG) System for Cancer Biomarker and Pathway Research**

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![LangGraph](https://img.shields.io/badge/LangGraph-Multi--Agent-green)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Database-orange)
![Gradio](https://img.shields.io/badge/Gradio-Web%20Interface-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Overview

BioAgentGPT is an AI-powered biomedical research assistant that combines **Retrieval-Augmented Generation (RAG)**, **Large Language Models (LLMs)**, and **Multi-Agent AI** to answer biomedical research questions using **live PubMed literature**.

Instead of relying only on an LLM's internal knowledge, BioAgentGPT retrieves relevant scientific literature, performs semantic search using FAISS, identifies important genes and biological pathways, and generates structured scientific reports.

This project was developed as part of the **AI in Healthcare** course for the B.Tech Bioinformatics program.

---

# 🚀 Features

- 🔍 PubMed Literature Retrieval
- 📚 Retrieval-Augmented Generation (RAG)
- 🤖 Qwen2.5-3B-Instruct Large Language Model
- 🧠 Multi-Agent Workflow using LangGraph
- 🧬 Gene Detection
- 🧪 Biological Pathway Mapping
- 📄 Scientific Report Generation
- 📥 PDF Report Download
- 🌐 Interactive Gradio Web Application

---

# 🏗️ System Architecture

```
                User Query
                     │
                     ▼
              Planner Agent
                     │
                     ▼
          Literature Search Agent
                     │
                     ▼
         PubMed Literature Retrieval
                     │
                     ▼
           Text Chunking & Embeddings
                     │
                     ▼
              FAISS Vector Database
                     │
                     ▼
               Semantic Retrieval
                     │
                     ▼
         Qwen2.5-3B-Instruct (LLM)
                     │
        ┌────────────┴────────────┐
        ▼                         ▼
  Gene Detection          Pathway Mapping
        │                         │
        └────────────┬────────────┘
                     ▼
        Scientific Report Generation
                     │
                     ▼
          Gradio Web Application
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Google Colab | Development Environment |
| Qwen2.5-3B-Instruct | Large Language Model |
| LangGraph | Multi-Agent Workflow |
| FAISS | Vector Database |
| Sentence Transformers | Text Embeddings |
| PubMed (NCBI) | Biomedical Literature |
| Biopython | PubMed API Access |
| Gradio | Web Interface |
| ReportLab | PDF Report Generation |
| Pandas | Data Processing |

---

# 🔄 Workflow

1. User submits a biomedical research question.
2. Planner Agent determines the required tasks.
3. PubMed abstracts are retrieved.
4. Literature is converted into vector embeddings.
5. FAISS retrieves the most relevant documents.
6. Gene Agent identifies important biomarkers.
7. Pathway Agent maps genes to biological pathways.
8. Qwen2.5 generates a structured scientific report.
9. A downloadable PDF report is created.

---

# 📂 Project Structure

```
BioAgentGPT/
│
├── notebooks/
│   └── BioAgentGPT.ipynb
│
├── reports/
│
├── images/
│
├── data/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# ▶️ Running the Project

## Clone the repository

```bash
git clone https://github.com/Subhasree-2006/BioAgentGPT.git
cd BioAgentGPT
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Open the notebook

Launch the notebook in **Google Colab** or **Jupyter Notebook** and execute the cells sequentially.

---

# 📊 Example Query

```
Find breast cancer biomarkers
```

Example Output:

- Detected Genes
  - AR
  - HER2
  - PD-L1

- Related Pathways
  - PI3K-AKT Signaling
  - MAPK Signaling
  - PD-1 Checkpoint Pathway
  - Androgen Receptor Signaling

- AI Generated Scientific Report

- Downloadable PDF Report

---

# 📌 Current Features

- ✅ PubMed Literature Search
- ✅ Semantic Search using FAISS
- ✅ Retrieval-Augmented Generation
- ✅ Multi-Agent Workflow
- ✅ LangGraph Integration
- ✅ Gene Detection
- ✅ Pathway Mapping
- ✅ PDF Report Generation
- ✅ Gradio Interface

---

# 🔮 Future Improvements

- Biomedical Named Entity Recognition (BioBERT/SciSpaCy)
- KEGG & Reactome Pathway Integration
- Drug Target Identification
- Clinical Trial Retrieval
- Multi-Disease Support
- Deployment on Hugging Face Spaces

---

# 👩‍💻 Authors

**Subha Sree M**

B.Tech Bioinformatics

SASTRA Deemed University

---

# 📚 References

- PubMed (NCBI)
- Sentence Transformers
- FAISS
- LangGraph
- Qwen2.5
- Gradio
- Biopython

---

# 📄 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project interesting, consider giving it a star on GitHub.
