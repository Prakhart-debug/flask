# 📂 Document Clustering and Summarization Using LLM and OPENAI API

##  Project Overview
This project uses advanced NLP techniques, including Large Language Models (LLMs) like GPT-3.5, to automate the clustering, deduplication, and summarization of documents. It is designed to help enterprises manage large document repositories efficiently by generating unique, consolidated reports.

Developed as part of an internship at **Genpact (Enquero)** and submitted to **Manipal Institute of Technology** as a B.Tech Final Year Project.

---

##  Technologies Used
- **Python 3.10+**
- **Flask** – Web backend
- **OpenAI API** – Text analysis and summarization
- **LangChain** – Retrieval & summarization pipelines
- **scikit-learn** – Clustering and vectorization (TF-IDF, Affinity Propagation)
- **spaCy** – NLP preprocessing
- **docx / python-docx** – DOCX file handling
- **Jupyter Notebook / VS Code** – Dev & Testing



## Features
- Upload multiple documents (PDF, DOCX, TXT)
- Cluster documents by content using Affinity Propagation
- Remove redundant content via GPT-based deduplication
- Generate cluster-wise consolidated summaries
- Evaluate content similarity using Cosine Similarity
- Output DOCX summaries for each cluster
- Streamlined UI via Flask app



## Setup Instructions

###  Prerequisites
- Python 3.10 or higher
- An OpenAI API Key (create one at [platform.openai.com](https://platform.openai.com/account/api-keys))

###  1. Clone the Repo
```bash
git clone https://github.com/yourusername/document-summarizer-ai.git
cd document-summarizer-ai
```
### 2. Virtual environment
```bash
python -m venv venv
source venv/bin/activate  # for Windows use this instead : venv\Scripts\activate
```
### 3. Install Requirement and Setup Environment API key
```bash
pip3 install -r requirement.txt
OPENAI_API_KEY=your_openai_api_key_here
```
## Output Format
- Consolidated reports generated as COMPANY_NAME_Consolidated_Output.docx

- Summary accuracy validated against expert insights

- Cosine similarity score provided for quality assurance

