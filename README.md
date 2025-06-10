# 📘 Learning Amazon Bedrock – Project by Shubham Yedekar

This repository is a hands-on extension of the **LinkedIn Learning course**: `Learning Amazon Bedrock`. While the original course provides foundational knowledge, this version goes beyond by implementing the exercises directly inside a GitHub Codespace. This project was configured, structured, and customized by **Shubham Yedekar**.

[📺 View the original course on LinkedIn Learning][[lil-course-url](https://www.linkedin.com/learning/learning-amazon-bedrock-23090599/learning-amazon-bedrock-overview)]  
![LinkedIn Learning Thumbnail][lil-thumbnail-url]

---

## 📌 About This Project

In this learning journey, I explored how to use **Amazon Bedrock** to build end-to-end Generative AI applications with real-world relevance. The key goal was to understand the practical deployment of **Foundation Models (FMs)** using **LangChain**, **boto3**, and **Streamlit**, all within an optimized and containerized development environment using **GitHub Codespaces**.

---

## 🧠 What We Built

### ✅ Project Goals
- Use Amazon Bedrock to access foundation models like Claude via `boto3`
- Implement **Retrieval-Augmented Generation (RAG)** using LangChain
- Build an interactive **Streamlit chatbot** that answers employee questions based on internal training documents
- Deploy the entire project inside a reproducible `.devcontainer` setup on Codespaces

---

### 📂 Data Used
- **social-media-training.pdf** (located in `/data/`):  
  This is a fictional internal training manual containing best practices, policies, and strategic content for a company’s social media team. The bot is trained to read and extract context from this document.

---

## 🛠️ Key Components

| Component              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `boto3`                | To access Amazon Bedrock's Claude foundation model via the Bedrock Runtime |
| `LangChain`            | Used for building the RAG pipeline and LLM chaining                         |
| `FAISS`                | Vector store used for similarity-based document retrieval                   |
| `PyPDFLoader`          | Extracts and splits text content from training PDFs                         |
| `Streamlit`            | Used for creating a clean, interactive chat UI                              |
| `.devcontainer`        | Codespaces setup to auto-install extensions and dependencies                |

---

## 💬 Chatbot Use Case

The app simulates a **Conversational Assistant** trained on a company's internal training document. It can:
- Answer employee questions using accurate and relevant context
- Retrieve document segments using semantic search
- Generate responses using Claude from Amazon Bedrock

---

## 🧑‍💻 Built By

**Shubham Yedekar**  
AI/ML Developer | Generative AI Enthusiast | Cloud-Native Engineer

---

## 📚 Original Instructor

**Lee Assam**  
Principal Cloud Technologist and Solution Architect Leader  
[More from Lee on LinkedIn Learning](https://www.linkedin.com/learning/instructors/lee-assam?u=104)

---

[0]: # (Replace these placeholder URLs with actual course URLs)  
[lil-course-url]: https://www.linkedin.com/learning/  
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQGeZZWDB8ySlQ/learning-public-crop_675_1200/0/1710533858658?e=2147483647&v=beta&t=9YTDxNEVEVHhMtOs4k_fEmMXOpwGOoPJYKb7a1sUcIA
