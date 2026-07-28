<p align="center">
  <img src="assets/banner.png" alt="Priyam Choksi — Data Engineer & AI Engineer" width="100%">
</p>

<p align="center">
  <a href="https://priyamchoksi.com"><b>priyamchoksi.com</b></a> ·
  <a href="https://linkedin.com/in/priyamchoksi">LinkedIn</a> ·
  <a href="mailto:pymchoksi@gmail.com">Email</a>
</p>

---

I'm a Data Engineer with 4+ years building **production data platforms and the LLM and agent systems that run on top of them**, across healthcare, finance, and SaaS. I'm also a published medical-AI researcher with **five peer-reviewed papers** and an **ESC Young Investigator Award**.

Most of my work has been a version of the same problem in different industries: a legacy system nobody trusts, feeding decisions that actually matter. At **Brigham and Women's Hospital / Harvard Medical School** that meant rebuilding a genomic pipeline from 48-hour batch cycles to **15-minute distributed PySpark runs** over 5.8TB of biobank, EHR, and metabolomic data. Today I own the ingestion platform at Rebecca Everlene Trust Company: **5TB+** from 453 sources into Snowflake, a Pydantic validation gate that cut transformation errors **40%**, and a hybrid-retrieval RAG system at **92% accuracy**.

**Looking for:** Data Engineer / AI Engineer roles in healthcare, fintech, or SaaS. Open to remote or onsite anywhere in the US.

### Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Spark">
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks">
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Airflow">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt">
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake">
  <img src="https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white" alt="Redshift">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white" alt="BigQuery">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau">
</p>

### Selected work

| Project | The short version | Links |
|---|---|---|
| **Trade Arena** | 11-agent trading pipeline; 7 LLMs on identical data for 383 rounds, Llama-3.3-70B won at **+32.63%**; Strategy Arena ran 1,800 tournament rounds over a shared $1M pool | [Live](https://tradearena.site) · [Repo](https://github.com/priyam-choksi/matsmatsmats) |
| **Agentic Customer Triage** | 27-category routing at **91% accuracy**; resolves **74% of 2,000+ monthly tickets** without escalation; LangGraph travel graph + 3-agent banking chain with 0–100 confidence scoring | [Repo](https://github.com/priyam-choksi/agentic-customer-triage-system) |
| **CXR Latent Diffusion** | **151.8M-parameter** text-to-X-ray system; SSIM 0.82, FID 18.7, beating GAN and VQGAN baselines; first-author publication | [Paper](https://doi.org/10.20944/preprints202506.1783.v1) · [Repo](https://github.com/priyam-choksi/cxr_diffusion) |
| **Multi-omics Pipeline** | BWH/Harvard genomic pipeline: **48–72h → 15 min** on 5.8TB; researcher throughput 2–3 → 10–15 analyses/week (code confidential per BWH policy) | [Site](https://priyamchoksi.com/#/projects) |
| **DW & BI Integration** | 4 source platforms (SQL Server, MySQL, PostgreSQL, Oracle) into a star-schema warehouse via parallel Talend + SSIS pipelines | [Repo](https://github.com/priyam-choksi/Data-Integration-and-Business-Intelligence) |
| **Diabetes Prediction Platform** | Logistic regression at **95.97% / 0.9587 ROC-AUC** on 100K records; five-algorithm comparison written up as a paper | [Live](https://diabetes-prediction-and-analytics.streamlit.app/) · [Repo](https://github.com/priyam-choksi/Diabetes-Streamlit-App/) · [Demo](https://youtu.be/gIcCXWj7e-A) |

### Research

- **AI metabolomics score for cardiovascular risk in psoriasis** — *American Journal of Preventive Cardiology*, 2026 · ESC Young Investigator Award · [DOI](https://doi.org/10.1016/j.ajpc.2026.101696)
- **Plasma metabolites and incident HFrEF vs HFpEF** — *medRxiv*, 2026 · [DOI](https://doi.org/10.64898/2026.07.20.26358530)
- **ML over plasma metabolomics, 38,628 participants** — *Circulation* (AHA Scientific Sessions), 2025 · [DOI](https://doi.org/10.1161/circ.152.suppl_3.4347325)
- **Metabolomic signatures predicting MACE in rheumatoid arthritis** — *Annals of the Rheumatic Diseases* (EULAR), 2025 · [DOI](https://doi.org/10.1016/j.ard.2025.06.099)
- **Text-conditional chest X-ray generation via latent diffusion** — *Preprints*, 2025 · first author · [DOI](https://doi.org/10.20944/preprints202506.1783.v1)

### Off the clock

Currently reading *Designing Data-Intensive Applications* and *Fundamentals of Data Engineering*. The full shelf, with honest notes per book, lives on the [bookshelf](https://priyamchoksi.com/#/reading).

---

<p align="center"><i>"You have power over your mind — not outside events. Realize this, and you will find strength."</i><br><sub>MARCUS AURELIUS · MEDITATIONS</sub></p>

<p align="center"><sub>DESIGNED IN FIGMA · BUILT BY HAND · <a href="https://priyamchoksi.com">PRIYAMCHOKSI.COM</a></sub></p>

![Profile Views](https://komarev.com/ghpvc/?username=priyamchoksi&color=blue)
