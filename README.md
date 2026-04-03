### Kaushik Sarkar

AI systems engineer. I build production infrastructure for health intelligence and climate-health forecasting at national and global scale.

Currently leading the architecture of [SAGE](https://github.com/drkaushiksarkar/sage-warehouse-master) -- a unified analytical warehouse that federates 1.78 billion observations from 85 source organizations (WHO, World Bank, NOAA, IHME, UNICEF, OECD, and 79 others) into a single queryable surface. The system spans epidemiological surveillance, climate reanalysis, economic development, disaster risk, and population demographics across 58,000+ geographic entities from 1807 to 2100.

---

#### What I build

**Data infrastructure at scale**
- Apache Iceberg lakehouse on Athena v3 with ACID transactions, partition-pruned queries across 40,000+ indicators
- 268 million vector embeddings (PubMed Central + evidence corpus) in OpenSearch for semantic retrieval
- 33 million causal relation triples in a knowledge graph built from biomedical literature
- Automated ingestion from 150+ APIs with EventBridge scheduling, deduplication, and lineage tracking

**Machine learning systems**
- Foundation model training pipelines: continued pretraining, supervised fine-tuning, direct preference optimization
- Hard-negative DPO generation with BM25 recall and neural reranking (Titan Embeddings)
- Custom evaluation benchmarks with multi-dimensional LLM-as-judge scoring
- Mixture-of-experts routing with domain-specialized adapters

**Health AI and forecasting**
- Disease early warning systems deployed across South and Southeast Asia
- Climate-disease forecasting combining ERA5 reanalysis with epidemiological time series
- Malaria prediction systems with Terraform-managed infrastructure
- Real-time surveillance dashboards processing multi-source health signals

---

#### Technical surface

```
Languages     Python, TypeScript, SQL, HCL, Shell
Data          Apache Iceberg, Athena, DuckDB, PostgreSQL, Parquet
Search        OpenSearch (AOSS + managed), BM25, kNN, HNSW
ML/DL         PyTorch, Transformers, PEFT, DeepSpeed, vLLM
Cloud         AWS (S3, Lambda, Glue, Bedrock, SageMaker, EFA)
Infra         Terraform, Docker, EventBridge, CloudWatch
Serving       TiTiler (COG), FastAPI, Next.js
```

---

#### Selected repositories

| Repository | What it does |
|:-----------|:-------------|
| [sage-warehouse-master](https://github.com/drkaushiksarkar/sage-warehouse-master) | 1.78B-row analytical warehouse with 117 production scripts, enterprise serving layer, and foundation model training pipeline |
| [SPECTRA----Enterprise](https://github.com/drkaushiksarkar/SPECTRA----Enterprise) | Enterprise platform for spectral analysis and health system intelligence |
| [bdewarspred](https://github.com/drkaushiksarkar/bdewarspred) | Full-stack disease early warning and prediction system (890K+ lines TypeScript) |
| [malaria-forecasting-system](https://github.com/drkaushiksarkar/malaria-forecasting-system) | Malaria incidence forecasting with Terraform-managed cloud infrastructure |
| [climate-disease-forecast](https://github.com/drkaushiksarkar/climate-disease-forecast) | Climate-driven disease prediction models using ERA5 reanalysis data |
| [CNN_Skin_Cancer](https://github.com/drkaushiksarkar/CNN_Skin_Cancer) | Deep learning for dermatological diagnosis with class imbalance handling |

---

#### Research

Preparing submissions for NeurIPS 2026 on three topics: a training paradigm for domain-specialized foundation models, a multi-dimensional evaluation benchmark for health AI, and expert routing in mixture-of-experts architectures.

Doctoral research in computational epidemiology with focus on AI-driven early warning systems for infectious disease outbreaks in low and middle-income countries.

---

<sub>Delhi, India -- [drkaushiks.com](https://www.drkaushiks.com) -- [X/Twitter](https://twitter.com/drkaushiksarkar)</sub>
