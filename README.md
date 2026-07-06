# Hi there, I'm nishant! 👋
🔭 Currently working on Distributed Systems, Query Engines, and Cloud<br>🌱 Learning Rust<br>

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](www.linkedin.com/in/nishant-choudhary-620292325) 

### 💻 Tech Stack
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black) ![Apache DataFusion](https://img.shields.io/badge/Apache%20DataFusion-FF6600?style=for-the-badge) ![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge&logo=delta&logoColor=white) ![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-FF3621?style=for-the-badge) ![Azure Databricks](https://img.shields.io/badge/Azure%20Databricks-FF3621.svg?style=for-the-badge&logo=databricks&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visualstudiocode&logoColor=white)

## 📊 GitHub Stats

[![GitHub Streak](https://streak-stats.demolab.com/?user=nis12ram)](https://git.io/streak-stats)

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=nis12ram&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)


## 🚀 **Data Engineering Projects**
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



## 📚 **TECHNICAL LEARNING & KNOWLEDGE SHARING**

I enjoy documenting my Data Engineering learnings in simple, digestible explanations to improve my understanding.

Posts Website: [DEDigest](https://nis12ram.github.io/DEDigest/)

