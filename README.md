# 🚀 Real-World Machine Learning & Generative AI Projects (PS1–PS10)

## 📌 Overview

This repository contains **10 real-world Machine Learning, Deep Learning, Generative AI, Retrieval-Augmented Generation (RAG), and Agentic AI problem statements** completed or implemented as part of hands-on technical training.

The projects cover the complete journey from traditional predictive machine learning to enterprise-oriented AI systems, including data preprocessing, model development, evaluation, LLM integration, semantic search, hybrid retrieval, multi-agent workflows, fine-tuning, and security guardrails.

Each problem statement has its own project folder containing the available Python scripts, notebooks, datasets, ZIP archives, evaluation reports, documentation, and other implementation files.

## 🎯 Objectives

- Apply machine learning algorithms to practical industry problems.
- Develop classification, regression, clustering, and forecasting pipelines.
- Build applications using Generative AI and Large Language Models.
- Implement document ingestion, embeddings, vector search, and RAG.
- Develop hybrid retrieval and cross-encoder re-ranking workflows.
- Build AI agents with tool execution and multi-agent collaboration.
- Explore LoRA and QLoRA for parameter-efficient fine-tuning.
- Implement input/output security guardrails.
- Evaluate model and system performance using appropriate metrics.
- Maintain reusable code, project documentation, and reproducible workflows.

## 🗂️ Project Index

| Project | Problem Statement | Industry Domain | Main Topics |
|---|---|---|---|
| PS1 | Industrial IoT Telemetry Anomaly Detection & Failure Prediction Pipeline | Smart Manufacturing | Linear Regression, Logistic Regression, Feature Engineering |
| PS2 | Fintech Transaction Fraud Scoring & High-Value Customer Segmentation | Financial Services | Decision Trees, Random Forest, K-Means Clustering |
| PS3 | Supply Chain Demand Forecasting with Neural Networks & Automated Tuning | E-Commerce & Retail Logistics | MLP, Hyperparameter Tuning, Model Evaluation |
| PS4 | Enterprise Customer Support Intent Router & Dynamic Prompt Engineering | Enterprise Helpdesk | GenAI, LLM APIs, Prompt Engineering, Structured JSON |
| PS5 | Multi-Format Healthcare Clinical Manual Ingestion & Embedding RAG Pipeline | Healthcare | Document Parsing, Semantic Chunking, Embeddings, Vector Search |
| PS6 | Production Legal Contract Q&A with Hybrid Search & Cross-Encoder Re-Ranking | Legal Technology | BM25, Vector Search, Hybrid Retrieval, Re-Ranking |
| PS7 | Autonomous Financial Analyst Agent with Tool-Calling & Dynamic Execution | Finance | AI Agents, Tool Binding, ReAct, SQL, RAG |
| PS8 | Collaborative Multi-Agent DevSecOps Code Audit & Vulnerability Remediation | Cybersecurity | Multi-Agent Systems, Code Auditing, Remediation, QA |
| PS9 | Parameter-Efficient Fine-Tuning (LoRA / QLoRA) for Specialized Claims Processing | Insurance | QLoRA, PEFT, 4-bit Quantization, Fine-Tuning |
| PS10 | Enterprise Pipeline Agentic RAG System with Guardrails & RAGAS Evaluation | Global Supply Chain | Agentic RAG, Hybrid Search, Guardrails, Evaluation |

---

## 📁 Repository Structure

```text
Real-World-ML-GenAI-Problem-Statements/
│
├── README.md
│
├── PS1_Industrial_IoT_Anomaly_Detection/
│   ├── code/
│   ├── notebooks/
│   ├── data/
│   ├── reports/
│   └── zip/
│
├── PS2_Fintech_Fraud_Scoring/
│   ├── code/
│   ├── notebooks/
│   ├── data/
│   ├── reports/
│   └── zip/
│
├── PS3_Supply_Chain_Demand_Forecasting/
│   ├── code/
│   ├── notebooks/
│   ├── data/
│   ├── reports/
│   └── zip/
│
├── PS4_Customer_Support_Intent_Router/
│   ├── code/
│   ├── notebooks/
│   ├── data/
│   ├── reports/
│   └── zip/
│
├── PS5_Healthcare_Clinical_RAG/
│   ├── code/
│   ├── notebooks/
│   ├── documents/
│   ├── reports/
│   └── zip/
│
├── PS6_Legal_Contract_Hybrid_RAG/
│   ├── code/
│   ├── notebooks/
│   ├── documents/
│   ├── reports/
│   └── zip/
│
├── PS7_Financial_Analyst_Agent/
│   ├── code/
│   ├── notebooks/
│   ├── data/
│   ├── reports/
│   └── zip/
│
├── PS8_DevSecOps_Multi_Agent_Audit/
│   ├── code/
│   ├── notebooks/
│   ├── samples/
│   ├── reports/
│   └── zip/
│
├── PS9_QLoRA_Claims_Processing/
│   ├── code/
│   ├── notebooks/
│   ├── data/
│   ├── models/
│   ├── reports/
│   └── zip/
│
└── PS10_Agentic_RAG_Logistics_Control_Tower/
    ├── code/
    ├── notebooks/
    ├── data/
    ├── policies/
    ├── reports/
    ├── dashboard/
    ├── docs/
    └── zip/
```

*The structure above is the recommended organization. Keep only folders and files that you actually have for each project; do not create empty folders just to imply that a component was implemented.*

## 🧰 Technologies & Tools

The exact stack varies by project. Technologies used or explored across the project collection include:

- **Programming:** Python, SQL
- **Machine Learning:** Scikit-learn, classification, regression, clustering, feature engineering
- **Deep Learning:** TensorFlow, Keras, PyTorch, neural networks
- **Generative AI:** Large Language Models, prompt engineering, structured outputs, API integration
- **RAG:** Document parsing, semantic chunking, embeddings, vector databases
- **Advanced Retrieval:** BM25, hybrid search, cross-encoder re-ranking
- **Agentic AI:** Tool execution, ReAct workflows, multi-agent collaboration
- **Fine-Tuning:** LoRA, QLoRA, PEFT, BitsAndBytes quantization
- **Security:** Prompt-injection detection, PII redaction, output screening
- **Evaluation:** Classification metrics, regression metrics, retrieval evaluation, RAGAS
- **Development:** Jupyter Notebook, Google Colab, VS Code, Git, GitHub

Not every technology is used in every project.

## 📊 Evaluation & Documentation

Each project includes the evaluation artifacts available for its implementation, which may include:

- Model performance reports and metric comparisons
- Training and validation loss curves
- Hyperparameter tuning results
- Retrieval and search results
- Agent execution traces
- Security audit logs
- Evaluation dashboards and scorecards
- README files and implementation notes

Results are documented according to the actual execution outputs. Experimental, synthetic-data, proxy-based, and incomplete evaluations are identified separately rather than presented as verified production performance.

## ▶️ How to Use This Repository

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   cd Real-World-ML-GenAI-Problem-Statements
   ```

2. Open the folder for the problem statement you want to explore.

3. Review its README, requirements file, and documentation.

4. Open the provided Jupyter notebook in Google Colab or a compatible environment, or run the Python scripts according to the project's instructions.

5. Install the dependencies required for that specific project.

6. Review the available datasets, outputs, evaluation reports, and implementation notes.

**Important:** Each project may have different dependency versions, hardware requirements, API requirements, and setup steps. Use its own instructions instead of assuming that one environment works for all ten projects.

## 🔐 Security & Data Handling

- Never upload API keys, access tokens, passwords, or other credentials.
- Use environment variables or a secure secrets manager for API credentials.
- Remove sensitive personal information from datasets and notebook outputs before committing.
- Avoid committing virtual environments, temporary files, model caches, or unnecessary generated files.
- Check large datasets and model checkpoints before uploading them to GitHub.
- Follow the licensing and usage conditions of datasets, models, and documents.

## ⚠️ Project Scope & Limitations

These projects are hands-on training and capstone implementations. Their completeness, deployment readiness, and evaluation methodology vary by problem statement.

Synthetic datasets, demonstration rules, incomplete external API evaluations, and local evaluation proxies are documented where applicable. A working prototype should not automatically be interpreted as a production deployment.

For PS10, the functional benchmark reported a 100% pass rate across its 50 supplied scenarios. The official model-judged RAGAS metrics and harm evaluation remain pending; supplementary lexical proxy metrics are not official RAGAS results.

## 🏁 Conclusion

This repository brings together ten industry-oriented problem statements spanning traditional machine learning, deep learning, Generative AI, RAG, AI agents, model fine-tuning, and enterprise AI safety.

It serves as a consolidated portfolio of hands-on implementations, experiments, source code, notebooks, and technical documentation, demonstrating the progression from foundational ML techniques to more advanced AI application architectures.

**Repository:** Real-World-ML-GenAI-Problem-Statements  
**Coverage:** Problem Statements 1–10  
**Focus:** Machine Learning · Deep Learning · GenAI · RAG · Agentic AI · QLoRA · Guardrails · Evaluation
