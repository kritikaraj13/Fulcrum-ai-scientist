# 🔬 Fulcrum-AI: The Operational Scientist

**Fulcrum-AI** is an autonomous agentic platform designed to bridge the operational gap in scientific research. By automating Literature QC, Experimental Iteration, and Budgetary Logistics, we enable researchers to move from hypothesis to lab-execution in seconds rather than months.

## 🚀 The Problem (The "mRNA Gap")
Modern science is bottlenecked by operations. Principal Investigators spend up to 40% of their time on manual literature reviews, reagent sourcing, and navigating budgetary uncertainty. Fulcrum-AI solves this by "operationalizing" the reasoning process.

## 🧠 Technical Architecture (Three-Phase Engine)
The platform follows a strict three-phase autonomous workflow:

1.  **Phase 1: Idea Generation:** Analyzes internal datasets (Sustainability & Power CSVs) to identify regional risk signals and research gaps.
2.  **Phase 2: Experimental Iteration:** Utilizes the **Tavily Search API** to act as a "Live Librarian," scraping real-time market costs for reagents and the latest peer-reviewed protocols.
3.  **Phase 3: Paper Write-up:** Synthesizes a structured JSON report including:
    * **Novelty Signal:** A gated QC check (Green/Yellow) based on literature saturation.
    * **Lab Protocol:** Step-by-step instructions with mandatory validation (MS/NMR/SEM).
    * **Logistics:** A real-world budget featuring a **mandatory 30% Operational Contingency Buffer**.

## 🛠️ Tech Stack
* **Frontend:** React, Vite, Lovable.dev (Scientific Command Center UI)
* **Backend Logic:** Python, LangChain
* **Intelligence:** Tavily Search API (Real-time RAG), OpenAI GPT-4o
* **Environment:** Jupyter Notebook / Python 3.10+

## 📦 Installation & Setup
1. Clone the repo:
   ```bash
   git clone [https://github.com/kritikaraj13/fulcrum-ai-scientist.git](https://github.com/kritikaraj13/fulcrum-ai-scientist.git)
