# 🤖 Autonomous AI Document Generation Agent

An intelligent, autonomous AI agent that translates natural language prompts into highly comprehensive, professionally structured, and beautifully formatted Microsoft Word (`.docx`) business documents. Built using **LangChain**, **Gemini 2.5 Flash**, **Streamlit**, and **FastAPI**.

The agent handles the end-to-end workflow: it accepts a vague user prompt, automatically determines the necessary document type, structures an internal checklist (TODO), executes the content generation recursively, and formats the output using an Executive Navy typographic hierarchy.

---

## 🚀 Key Features
* **Autonomous Task Planning:** The agent analyzes user requests to formulate its own document structure and generation steps dynamically.
* **Streamlit & FastAPI Frontends:** Comes equipped with both a sleek, unified UI built with Streamlit and a robust backend integration route powered by FastAPI.
* **Professional Typography Formatting:** Automated Word document parsing ensures custom line spacing, margins, bold section headings, and explicit bulleted indents.
* **Native Structured Output:** Built using Gemini's native tool-calling features (`with_structured_output`) to prevent JSON parsing crashes.

---

## 🛠️ Local Setup Instructions

### 1. Prerequisites & Repository Preparation
Ensure you have Python 3.10+ or an Anaconda distribution ready. Navigate to your project directory and configure your virtual environment:

```bash
# Move to project drive and folder
D:
cd D:\Prac_Project_AI

# Create and activate a local virtual environment
python -m venv .venv
.venv\Scripts\activate
