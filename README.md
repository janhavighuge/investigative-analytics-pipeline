# 🔍 Investigative Analytics Pipeline

A full-stack crime data analytics project that simulates real-world law enforcement and identity verification use cases using U.S. crime data (2020–Present). This project integrates **entity resolution**, **link analysis**, **anomaly detection**, and **NLP + LLM prompt engineering** to generate actionable investigative insights and improve public safety decision-making.

---

## 🚀 Project Overview

In an era where crime and fraud threats are growing increasingly complex, agencies need rapid, intelligent tools to process vast datasets and uncover hidden connections. This project builds a prototype investigative system that:

- Resolves messy or inconsistent entity records (e.g., suspects, locations).
- Uncovers networks and hidden associations between people, places, and events.
- Flags unusual patterns or outliers in time-series and spatial crime data.
- Extracts structured insights and classifications from unstructured narratives.
- Leverages prompt engineering to simulate intelligence workflows using LLMs.

---

## 🧠 Key Features

| Component              | Description |
|------------------------|-------------|
| 🧩 **Entity Resolution** | Identify and unify duplicate records (e.g., same person with different name spellings). |
| 🌐 **Link Analysis**      | Create relationship graphs between suspects, crimes, and locations. |
| ⚠️ **Anomaly Detection**  | Detect unexpected spikes, drops, or outliers in crime data across time/geographies. |
| 🗣️ **NLP Tasks**          | Text cleaning, keyword extraction, classification (violent vs non-violent), entity extraction. |
| 🤖 **LLM Prompt Engineering** | Use GPT to summarize crime incidents, identify potential motives, and simulate investigations. |

---

## 📂 Folder Structure

```bash
investigative-analytics-pipeline/
│
├── data/                    # Raw & processed data
├── notebooks/               # Jupyter notebooks for each module
│   ├── 01_data_cleaning.ipynb
│   ├── 02_entity_resolution.ipynb
│   ├── 03_link_analysis.ipynb
│   ├── 04_anomaly_detection.ipynb
│   ├── 05_nlp_prompt_engineering.ipynb
│
├── prompts/                 # Prompt templates for LLMs
├── outputs/                 # Visualizations, graphs, and results
├── README.md
├── requirements.txt
└── config.py                # API keys and paths (excluded in .gitignore)

🧪 Tech Stack
Languages: Python (3.10+)

Libraries: pandas, scikit-learn, spaCy, NetworkX, matplotlib, seaborn, fuzzywuzzy

NLP & LLMs: OpenAI API, transformers, LangChain (optional)

Visualization: Plotly, matplotlib, seaborn

Graph Analysis: NetworkX

Others: Jupyter Notebook, Git, Kaggle Datasets
