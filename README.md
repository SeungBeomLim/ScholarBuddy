# ScholarBuddy: Scholarship Chatbot for Handong University 🎓🤖
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/14d752f1-dea9-4daa-bd29-a79b5678151b" />
ScholarBuddy is an AI-powered chatbot developed during the 2025 Winter Handong University Big Data Camp.  
It helps students easily access scholarship information through a user-friendly interface and AI-based document retrieval.

---

## 📌 Project Overview

🎯 **Goal**:  
To reduce confusion around scattered scholarship information by building a centralized chatbot using LLM and retrieval techniques.

🧩 **Approach**:  
- Applied RAG (Retrieval-Augmented Generation) structure  
- Built three databases: FAQ, Official Notices, and University Rules  
- Used custom prompt engineering and document routing to match queries with the correct data source

---

## 🛠️ Tech Stack

| Category         | Tools / Libraries                            |
|------------------|----------------------------------------------|
| Language         | Python                                       |
| LLM / API        | OpenAI GPT (via API)                         |
| Frontend         | Streamlit                                    |
| Prompt Handling  | Custom logic + few-shot examples             |
| Data             | KOSAF FAQ, School Policies, Notice Crawling  |

---

## 🔍 Key Features

- Multi-database support (Q&A, Notices, Rules)
- Query classification to select the right source
- Context-aware prompt templates for each type of content
- Fast and intuitive chatbot UI with Streamlit

---

## ⚠️ Challenges & Solutions

- **Challenge**: Gathering large amounts of clean data from fragmented sources  
  → **Solution**: Combined automated crawling and manual collection to build three usable datasets

- **Challenge**: Unstructured formats including images, metadata, and raw text  
  → **Solution**: Simplified one-entry-per-document format with minimal preprocessing

- **Challenge**: Routing the query to the correct DB  
  → **Solution**: Prompt engineering with keyword rules and few-shot examples to guide the model

---

## 🔗 Project Info

- 🏫 **Team**: Team 9 – 2025 Winter Big Data Camp  
- 🏆 **Award**: Excellence Award (우수상)  

---

## 📁 Repository Status

> This repository was created after the project for documentation and demonstration purposes.  
> Code may be partially refactored from original implementation.

> This README is generated by ChatGPT
