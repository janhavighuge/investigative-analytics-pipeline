# 🔍 Repeat Offender Detection: Investigative Analytics on U.S. Crime Data

A focused crime analytics case study that simulates real-world investigative workflows using U.S. crime data (2020–Present). This project identifies **repeat violent offenders** across multiple jurisdictions by integrating **entity resolution**, **NLP classification**, and **spatial-temporal analysis** — all while dealing with messy, inconsistent records.

---

## 🎯 Problem Statement

Law enforcement databases often suffer from inconsistent entries — the same individual may appear under multiple aliases, name spellings, or incomplete records. This makes it difficult to accurately:

- Track repeat offenders,
- Identify cross-jurisdictional threats, and
- Allocate investigative resources efficiently.

---

## ✅ Project Goal

To detect and profile **repeat violent crime offenders** by:

- Resolving inconsistent or duplicate suspect names (e.g., “Jon Doe” vs. “Johnathan D.”).
- Classifying incidents as **violent or non-violent** using NLP on crime descriptions.
- Analyzing patterns in **offender recurrence** across **time** and **geographies**.

---

## 📊 Key Metrics

- 🔄 **Repeat Offender Count** (before vs. after entity resolution)
- 📎 **Entity Variants Merged**: Number of unique offenders identified from messy name variations
- 📈 **Classification Accuracy**: Precision/Recall of NLP model for violent crime detection

---

## 🧠 Methods & Features

| Component              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🧩 Entity Resolution    | Fuzzy matching & rule-based logic to unify suspect aliases                 |
| 🗣️ NLP Classification   | Extract & classify violent vs. non-violent incidents from text descriptions |
| 🌐 Geo-Temporal Analysis | Track repeat offenses over time and by location                            |
| 🤖 LLM Prompt Engineering | Simulate “offender profile” generation and narrative summarization         |

---

## 🗂️ Folder Structure


investigative-repeat-offenders/
│
├── data/ # Raw & processed crime data
├── notebooks/ # Jupyter notebooks for each module
│ ├── 01_data_cleaning.ipynb
│ ├── 02_entity_resolution.ipynb
│ ├── 03_nlp_classification.ipynb
│ ├── 04_repeat_offender_analysis.ipynb
│ ├── 05_llm_profiling.ipynb
│
├── prompts/ # Prompt templates for LLMs (e.g., offender profile generation)
├── outputs/ # Visualizations, maps, final results
├── README.md
├── requirements.txt
└── config.py # API keys and file paths (excluded in .gitignore)

