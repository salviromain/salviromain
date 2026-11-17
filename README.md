<h1 align="center">Hi, I'm Romain 👋</h1>
<p align="center">
  <strong>Data Scientist & AI Engineer · LLM Systems · Causal Inference · Scalable Analytics</strong><br>
  📍 Chicago, IL · <a href="https://www.linkedin.com/in/romain-salvi-dsml/">LinkedIn</a> · <a href="https://github.com/salviromain">GitHub</a>
</p>

## About Myself

I build practical AI and data science systems, from LLM-powered analytics in retail to causal studies of human-AI interaction and research on LLM inference. I’m completing dual master’s degrees in Computer Science and Data Science & Engineering at the University of Illinois Chicago and Politecnico di Torino.

### Brief Project Intros

- **Schnuck Markets · Conversational analytics:** built the company’s most-used Gemini Enterprise agent in October 2026 (**18 monthly active users, 219 sessions**) over billions of point-of-sale rows; reduced data wait from one day to 15 minutes and BigQuery query costs from about **$1 to under $0.10**.
- **Schnuck Markets · Ad proofing:** reduced a Marketing manager-estimated **100+ hours** of weekly proofing to about **5 hours**, processing recurring promotional PDFs for roughly **$4/week** in API costs.
- **Published research · Pirouette Software · MCC:** co-authored work published in the **AGI 2026 proceedings** (Springer LNAI 16855).
- **Causal inference · Empathetic AI:** estimated a **+0.73–0.77 point** average effect on a 1–7 attachment scale, with effects varying across users.
- **Applied ML · Age estimation:** finished **top 2 of 200** students in the course leaderboard.

## Featured projects

**Data Science & Gen AI Intern · Schnuck Markets** — Remote, St. Louis · June 2026–Present  
I owned both projects end to end: building and deploying the systems, leading demos, training analysts, writing user guides, and presenting progress to managers every two weeks.

### 1. Schnuck Markets · POS Exception Agent
I built a conversational analytics agent for Asset Protection that lets analysts investigate point-of-sale exceptions in natural language across billions of retail transactions. It replaced a third-party platform with a one-day data delay; the agent queries BigQuery data refreshed every 15 minutes. In October 2026, it was the company’s most-used Gemini Enterprise agent, with **18 monthly active users and 219 sessions**.

I created efficient, pre-joined BigQuery views for the agent and the team’s Domo dashboard, and added safeguards for read-only analysis. In a 40-question stakeholder evaluation, prompt changes addressing team terminology improved results from **35/35 standard questions** to **40/40 overall**. I compared Gemini 2.5 Pro and Flash on quality, latency, and cost, then shipped Flash. BigQuery costs per query fell from about **$1 to under $0.10**.

**Tools:** Python · Google ADK · Vertex AI · Gemini Enterprise · Gemini 2.5 · BigQuery · SQL · Google Sheets API · GCP logging

### 2. Schnuck Markets · Automated Ad-Proofing Workflow
I built a workflow that checks promotional PDFs against source pricing data, combining document extraction, structured data validation, automated matching, and an AI-assisted discrepancy audit. Since early November, it has processed recurring batches of promotional ads for Marketing.

The Marketing manager estimated that proofing time fell from **100+ hours to about 5 hours per week**. API costs are about **$4 per week**. In testing across seven PDFs, the workflow caught all **33 planted price and size errors**; adding embedded PDF text to the audit context fixed the initial symbol-error detection gap. The workflow is being expanded to cover more ad types.

**Tools:** Python · Gemini 2.5 Pro and Flash · PyMuPDF · Pydantic · Jupyter · Google Cloud Platform · scheduled GCP runs · Google Drive API · Google Sheets API · Google Chat

> Schnuck Markets source code, data, and implementation details are company property, so I share this work at a high level.

### 3. [Discovering Machine Correlates of Consciousness](https://github.com/salviromain/mccviahat) 🧠
This research was part of my AI/ML Research Internship at Pirouette Software. We studied whether hardware anomaly traces from LLM inference differ between emotional and neutral prompts, while controlling for workload and thermal confounds. In our experiments, several power-throttle features for Llama 3.1 70B were statistically significant after Bonferroni correction; results for Llama 2 7B were not distinguishable from chance. The work was published in the AGI 2026 proceedings in Springer’s Lecture Notes in Artificial Intelligence (LNAI), volume 16855, pages 237–255. [Read the paper on arXiv](https://arxiv.org/abs/2608.28824).

**Focus:** LLM systems · experimental design · statistical analysis · Linux performance counters  
**Tools:** Python · llama.cpp · Docker · Linux `perf` · CloudLab

### 4. [Does Empathetic AI Language Cause User Attachment?](https://github.com/salviromain/llm-empathy-causal-study) 💬
A causal-inference study asking whether more empathetic chatbot responses increase users’ immediate emotional attachment. The project develops a matching strategy around prompt meaning and conversation context, and considers model differences and potential mediating mechanisms. Across semantic-matching and doubly robust analyses, the estimated average effect was **+0.73–0.77 points** on the 1–7 attachment-score scale, with estimated effects varying across users.

**Focus:** causal inference · LLM evaluation · semantic matching · research design  
**Tools:** Python · Sentence Transformers (MPNet) · scikit-learn · pandas · Mistral Small

### 5. [Mitigating Sycophancy in LLMs](https://github.com/salviromain/RLHF_sycophancy) 🤖
An end-to-end pipeline for reducing sycophantic model behavior through supervised fine-tuning. It covers data preparation, critique and revision, LoRA fine-tuning of Llama 3 8B, benchmark evaluation, and a human preference workflow.

**Focus:** LLM fine-tuning · RLHF · LoRA · automated and human evaluation  
**Tools:** Python · PyTorch · Hugging Face Transformers · TRL · PEFT · Unsloth · Google Apps Script

### 6. [Speaker Age Estimation](https://github.com/salviromain/Age-Estimation-Regression) 🎙️
A predictive modeling project estimating a speaker’s age from data. My Ridge model achieved a public evaluation RMSE of **9.056**, placing among the best results. I placed in the **top two out of 200 students** in the course leaderboard.

**Focus:** regression · feature engineering · predictive modeling  
**Tools:** Python · pandas · NumPy · librosa · scikit-learn · Matplotlib

### 7. [Spectral Clustering](https://github.com/salviromain/Spectral-Clustering) 🔎
An interactive MATLAB application comparing clustering methods across high-dimensional, nonlinear datasets. On the modified Iris dataset, normalized-Laplacian spectral clustering achieved an ARI of **0.77**; K-means with k=3 achieved **0.73**.

**Focus:** unsupervised learning · spectral methods · MATLAB · computational algebra  
**Tools:** MATLAB App Designer · `eigs` · inverse power method · deflation · DBSCAN · K-means

## Experience

- **Data Science & Gen AI Intern · Schnuck Markets** — owned the end-to-end delivery and stakeholder adoption of internal AI-enabled analytics tools.
- **AI/ML Research Intern · Pirouette Software** — studied hardware signals produced during LLM inference.
- **Data Science · MEC** — analyzed 500,000+ operational records, built Apache Airflow ETL pipelines, and created SQL-powered dashboards.

## Toolbox 🧰

**Languages:** Python · SQL · MATLAB · Java · JavaScript  
**AI & ML:** Vertex AI · Google ADK · Gemini Enterprise · PyTorch · scikit-learn · pandas · NumPy · EconML  
**Data & Cloud:** Google Cloud Platform (GCP) · BigQuery · Apache Spark · Hadoop · Domo  
**APIs & Automation:** REST APIs · Google Sheets API · Google Drive API · Model Context Protocol (MCP) · scheduled GCP runs · Google Apps Script  
**Development:** Jupyter · Pydantic · Apache Airflow · Docker · Linux · Git

## Connect 🤝

Interested in Data Science and AI Engineering opportunities, applied research, and responsible AI.

[LinkedIn](https://www.linkedin.com/in/romain-salvi-dsml/) · [GitHub](https://github.com/salviromain)
