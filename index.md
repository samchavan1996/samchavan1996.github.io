
# Sampada Chavan — Data Analyst (4+ years)

**Professional Summary**  
Data Analyst with **4+ years** across **healthcare, supply chain, and finance**. Strong in **Python, SQL, Power BI, Tableau**, and **cloud (AWS/Azure)**. I turn **raw data into valuable intelligence** by building reliable pipelines, interpretable models, and exec-ready dashboards in Agile teams.

[GitHub](https://github.com/samchavan1996) · [LinkedIn](https://www.linkedin.com/in/sampadachavan18/) · ✉︎ sampada1996@gmail.com

---

## Skills

**Programming & Data:** Python, SQL, R · NumPy, Pandas, Matplotlib, Seaborn, statsmodels, scikit-learn  
**Databases:** MySQL, SQL Server, Oracle, PostgreSQL, MongoDB, Snowflake  
**Cloud & Big Data:** AWS (EC2, S3, Lambda, RDS, Redshift, Glue, CloudWatch, Athena), Azure (ADF, ASA), Hadoop, Spark  
**BI:** **Power BI**, **Tableau**, Excel, Qlik Sense  
**Analysis:** A/B testing, cost/benefit, impact/GAP/SWOT/risk analysis  
**Data:** Cleaning, wrangling, warehousing, governance  
**Docs & Methods:** BRD, FRD, SRS · Agile/Scrum & Waterfall  
**Soft Skills:** Project/Product Management, Time management, Leadership, Problem-solving, Negotiation, Decision-making, Presentation, Communication, Root-cause Analysis

---

## Professional Experience (5)

### Data Analyst — **Techmentee Inc** *(United States · Jul 2025 – Present)*
- Built **Power BI** sales, returns, and exchanges dashboards for the e-commerce channel; added SKU-, vendor-, and cohort-level drill-downs.  
- Identified **financial leakages** (refunds, reship costs, reverse-logistics fees) by tracing order→RMA→settlement flows.  
- Root-caused top return drivers (size variance, packaging damage, delayed delivery) and partnered with Ops to pilot fixes.  
- Result: **return rate −12%** and **exchange due to mis-sizing −22%** within 8 weeks; weekly RMA cycle time down **18%**. *(dummy)*

### Data Analyst — **JPMorgan Chase** *(United States · Feb 2025 – Mar 2025)*
- Built an **AWS S3** data lake; **PySpark/SQL** pipelines streamlined campaign analytics and governed access.  
- Financial models for budgeting/forecasting improved **forecast accuracy +15%**; automated variance tracking.  
- Developed **Qlik** dashboards with parameters & hierarchies for leadership visibility.

### Data Analyst — **Blue Cross Blue Shield** *(City · Mar 2024 – Jan 2025)*
- ETL in **Python + AWS (RDS, Athena, S3, Glue) → Redshift**; monitored data quality and schema changes.  
- Tableau dashboards to track **provider performance, claims efficiency, and fraud signals**.  
- HIPAA-aligned EMR reporting from Epic; anomaly detection/ML prevented **$1.0M** in fraudulent claims.  
- **Spark/SQL** optimizations improved report accuracy **+20%** and reduced generation time.

### Data Analyst — **Mahindra Integrated Business Solutions** *(India · Feb 2020 – Dec 2021)*
- Created **SSIS** packages (extract/transform/load with derived columns, lookups).  
- Analyzed CC transactions to flag **credit-limit increase** candidates and cross-sell opportunities.  
- Built Customer complaint analytics from customer service data; delivered insights to Ops.  
- Churn analysis in Python improved retention **+10%**; A/B tests lifted conversions **+45%**.  
- Maintained **Power BI** dashboards; complex **DAX** for sales reporting; Excel macro automation saved **$78K/quarter**.  
- Predictive models (Python/R/SAS) improved Q1 retention **+30%**; recommended **paperless statements** to reduce costs.

### Technical Data Analyst — **Vedanta Group** *(India · Dec 2018 – Jan 2020)*
- Authored **42** user stories/specs & wireframes for MES device inventory; rollout drove **+1.1M MAU**.  
- Advanced SQL KPI reporting saved **32 hrs/cycle**; blended disparate sources for exec reviews.  
- Migrated on-prem data to **Azure Data Lake Gen2** via ADF; ran Agile delivery with 50+ stakeholder interviews; sprint analytics in Tableau.

---

## Projects (2)

### Airline Route Investment Analysis
**Goal:** Identify Top-5 domestic round-trip routes that maximize on-time performance and recover a **$90M** aircraft investment quickly.  
**Stack:** Python (pandas, numpy, matplotlib, seaborn)  
**Method:** Computed two normalized 0–1 scores—**Punctuality** (delay-based) and **Payback** (time to recoup investment)—and averaged them. Built reproducible functions for Data Mugging→ EDA → scoring.  
**Extras:** Break-even analysis to explain when the investment is recouped and what drives variance.

### API-Driven ASL Video Translation System
**Goal:** Translate English text/video transcripts into **ASL videos** end-to-end.  
**Stack:** Flask APIs, Deepgram (transcription), OpenAI API (language processing), AWS S3 + AWS MediaConvert (clip retrieval/assembly).  
### API-Driven ASL Video Translation System
**Goal:** Convert English text or audio/video into an **ASL video** by composing pre-recorded sign clips.

**Stack:** Python · Flask APIs · AWS S3 · AWS MediaConvert · Deepgram (speech-to-text) · OpenAI API

**Data:** Excel mapping of **words/letters → clip filenames**, with the corresponding video/audio clips stored in **S3** (e.g., MP4/MP3).

**My Scope (Part 2 — Clip Retrieval & Stitching)**
- **Ingested** the Excel mapping with Python and uploaded it to **S3**; produced a fast lookup index (token → S3 URI) for runtime use.
- Built a **search/matching service** to map the ASL token sequence to available clips in S3; added **fallbacks** (e.g., fingerspelling) when a token lacked a dedicated clip.
- **Assembled** the final video by generating an **AWS MediaConvert** job (JSON/EDL timeline) to **concatenate** clips into a single MP4; normalized fps/resolution and trimmed leading/trailing silences.
- Exposed a **Flask endpoint** that returned the output video’s S3 URL for the website to **render/playback**.
- Implemented basic **observability** (existence checks, error logs, idempotent retries) to make the pipeline reliable.
---

## Education

**MS — Engineering Management (Data Analytics)**, *Stevens Institute of Technology, NJ* — Jan 2022 – Dec 2023  

**BE — Mechanical Engineering**, *University of Mumbai* — Jul 2014 – May 2018

---

## Contact

- ✉︎ sampada1996@gmail.com  
- GitHub: <https://github.com/samchavan1996>  
- LinkedIn: <https://www.linkedin.com/in/sampadachavan18/>


