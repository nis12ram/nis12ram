# Hi there, I'm nishant! 👋

## **Aspiring Data Engineer | Databricks • Apache Spark • Azure**

I build scalable data pipelines and lakehouse solutions using **Databricks and PySpark**, with **Azure services** for orchestration and storage.  

My focus is on **distributed data processing**, **Delta Lake architectures**, and building **reliable, analytics-ready datasets** with strong data quality practices.

### 🛠️ Technical Stack

* **Big Data:** Apache Spark (PySpark), Delta Lake, Unity Catalog  
* **Cloud Data Tools (Azure):** Azure Databricks, Azure Data Factory (ADF), Azure Data Lake Storage (ADLS Gen2), Azure SQL Server  
* **Programming:** Python, SQL, Pandas, NumPy, PyTorch  
* **Additional Knowledge:** Data Modeling, Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), Generative AI  
* **Development Tools:** Git, VS Code, Jupyter Notebook, Google Colab  



### 🚀 **Projects**
<details>
<summary>
  <strong>Multi-Region Sales Data Pipeline (UnifiedSalesReportingPipeline)</strong>
</summary>


Designed and implemented an end-to-end Azure lakehouse pipeline to consolidate ~12M daily sales records from each regional branch into a unified dataset.
* **Orchestration:** Built modular, fault-tolerant workflows in ADF with centralized logging, retry logic, and restart-from-failure handling.
* **Transformation:** Developed parameterized notebooks in Databricks for cleaning, normalization, and metadata enrichment.
* **Governance:** Implemented data quality checks by quarantining invalid records and enforcing NOT NULL/CHECK constraints.
* **Storage:** Wrote optimized, ACID-compliant Delta Lake tables on ADLS Gen.

[Github Link](https://github.com/nis12ram/UnifiedSalesReportingPipeline)


<img width="1345" height="819" alt="UnifiedSalesPipeline" src="https://github.com/user-attachments/assets/e340aafc-6467-4b10-ab26-99464ca0ab9d" />

</details>

<details>
<summary><strong>Agricultural Commodity Price Arbitrage Pipeline (agri-price-arbitrage-adf-pipeline)</strong></summary>
  
Built an ADF-driven pipeline to ingest and process daily agricultural commodity price data from external APIs.

* **Architecture:** Utilized a Medallion (Bronze-Silver-Gold) architecture for structured data processing.
* **Data Flow:** Cleaned and standardized nested JSON data using ADF Data Flows to ensure consistent schema and quality.
* **Analytics:** Implemented business logic to identify in-state price arbitrage opportunities for actionable trading insights.

[Github Link](https://github.com/nis12ram/agri-price-arbitrage-adf-pipeline)

<img width="3194" height="1354" alt="agri_poster1" src="https://github.com/user-attachments/assets/f640b26e-caba-4733-95ea-d13439b49457" />

</details>



### 📚 **TECHNICAL LEARNING & KNOWLEDGE SHARING**

I enjoy documenting my Data Engineering learnings in simple, digestible explanations to improve my understanding.

Posts Website: [DEDigest](https://nis12ram.github.io/DEDigest/)

### 🤖 LLM Research & Experiments

<details>
<summary>
  <strong>HindiNER-4B-v1.0 — Fine-tuned Large Language Model for Hindi Named Entity Recognition</strong>
</summary>

- Fine-tuned a **4B parameter auto-regressive language model** for **general-purpose Hindi Named Entity Recognition (NER)**.
- Adapted the base LLM for **downstream NER tasks for Hindi, English and Hinglish** using **custom curated dataset** and **parameter efficient fine-tuning**.
- Achieved **competitive performance on the Hindi-NER task** while maintaining strong general language capabilities.
- Demonstrates practical application of **LLM adaptation for low-resource language NLP tasks**.

**Model:** [HindiNER-4B-v1.0](https://huggingface.co/nis12ram/HindiNER-4B-v1.0)
**Post:** [HindiNER-4B-v1.0](https://www.linkedin.com/posts/nishant-choudhary-620292325_ner-hindiner-indicner-activity-7350379087946821634-p0y_/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFIW0fgBT2zGDRtRxsSDdsT1rqXo-tSW3g8)
</details>


### 📜 **Certifications**

Databricks Fundamentals [Link](https://credentials.databricks.com/92eff652-152c-4c27-83d8-ba3a043da6ba#acc.B5c8Gz0f)

Databricks Generative Ai Fundamentals [Link](https://credentials.databricks.com/217ec94f-1980-4da4-bfd1-f83d49cd390c#acc.59BOqyz8)

---


*Thanks for visiting my profile! Feel free to connect or check back soon for more updates.*
