<h1 align="center">Hi, I'm Romain Salvi 👋</h1>
<p align="center">
  <strong>Data Scientist & AI Engineer · LLM Systems · Causal Inference · Scalable Analytics</strong><br>
  📍 Chicago, IL · <a href="https://www.linkedin.com/in/romain-salvi-dsml/">LinkedIn</a> · <a href="https://github.com/salviromain">GitHub</a>
</p>

## Start here

I build practical AI and data science systems, from LLM-powered analytics in retail to causal studies of human-AI interaction and research on LLM inference. I’m completing dual master’s degrees in Computer Science and Data Science & Engineering at the University of Illinois Chicago and Politecnico di Torino.

### Selected impact

- **Schnuck Markets · Conversational analytics:** built the company’s most-used Gemini Enterprise agent in October 2026 (**18 users, 219 sessions**) over billions of point-of-sale rows; reduced query costs by **more than 90%**.
- **Schnuck Markets · Ad proofing:** automated a **100+ hour** weekly manual process to about **one hour** for 30 PDFs, at roughly **$3/week** in API costs.
- **Published research · Pirouette Software · MCC:** co-authored work published in the **AGI 2026 proceedings** (Springer LNAI 16855).
- **Causal inference · Empathetic AI:** estimated a **+0.73–0.77 point** average effect on a 1–7 attachment scale, with effects varying across users.
- **Applied ML · Age estimation:** finished **top 2 of 200** students in the course leaderboard.

## Featured projects

### 1. Schnuck Markets · Conversational Analytics Agent
I built a conversational agent that lets Asset Protection analysts ask questions in plain English across billions of retail point-of-sale rows. In October 2026, it became the company’s most-used agent in Gemini Enterprise, with **18 distinct users and 219 sessions**. It queries BigQuery data refreshed every 15 minutes, replacing a third-party platform with a one-day delay. To keep queries efficient at this scale, I created ad-hoc pre-joined BigQuery views using partitioning, filters, and complex SQL lookback queries; these views also power the team’s Domo dashboard. I added a SELECT-only SQL guardrail, validated 40 stakeholder questions (improving from 35/40 to 40/40 with team-specific terminology), and reduced query costs by more than 90%, from about $1 to under $0.10. I also led stakeholder adoption meetings.

**Tools:** Python · Google ADK · Vertex AI · Gemini Enterprise · BigQuery · SQL · Domo · Google Sheets API

### 2. Schnuck Markets · Automated Ad-Proofing Workflow
I built an automated workflow to proof **30 weekly ad PDFs** against ground-truth data. It reduced an estimated **100+ hours** of manual proofing to about **one hour per week**, at approximately **$3/week** in API costs. In testing, it caught all 33 planted price and size errors across seven PDFs. I’m expanding it to cover more ad types and led stakeholder adoption meetings with Marketing.

**Tools:** Python · Google Cloud scheduled notebooks · Pydantic · LLM APIs · Google Drive and Sheets APIs · email automation

> Schnuck Markets source code, data, and implementation details are company property, so I share this work only at a high level.

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

- **Data Science & Gen AI Intern · Schnuck Markets** — building internal AI-enabled analytics tools.
- **AI/ML Research Intern · Pirouette Software** — studied hardware signals produced during LLM inference.
- **Data Science · MEC** — analyzed 500,000+ operational records, built Apache Airflow ETL pipelines, and created SQL dashboards.

## Toolbox 🧰

**Languages:** Python · SQL · MATLAB · Java · JavaScript  
**Data & ML:** PyTorch · scikit-learn · pandas · NumPy · EconML  
**Engineering:** Apache Airflow · Docker · Linux · Git · Apache Spark

## Connect 🤝

Interested in Data Science and AI Engineering opportunities, applied research, and responsible AI.

[LinkedIn](https://www.linkedin.com/in/romain-salvi-dsml/) · [GitHub](https://github.com/salviromain)
