### Kaushik Sarkar

AI and product leader with 17 years of experience building and scaling technology-driven products across 17 countries. I architect production AI systems at the intersection of **health**, **economics**, and **climate** -- from billion-row data infrastructure to multi-agent orchestration and foundation model training.

---

#### Industries

**Health and Life Sciences** -- Disease early warning systems deployed across South and Southeast Asia. Real-time surveillance platforms processing epidemiological signals from WHO, CDC, IHME, and national health ministries. Deep learning for medical imaging diagnostics. Foundation models trained on 268 million biomedical evidence spans and 33 million causal knowledge graph triples.

**Economics and Development Finance** -- Analytical infrastructure federating World Bank, OECD, AfDB, and ADB development indicators into unified queryable surfaces. Donor portfolio intelligence, ODA tracking, and country-level economic profiling across 40,000+ indicators. Trade and pharmaceutical market analysis pipelines.

**Climate and Environment** -- Climate-health forecasting combining ERA5 reanalysis with disease incidence time series. Integration of NOAA station observations (982M+ records), CMIP6 climate projections, sea level monitoring, and tropical cyclone tracking. Geospatial serving with Cloud-Optimized GeoTIFF at 100m resolution.

---

#### What I build

**Agentic AI and multi-agent systems**
- Multi-agent orchestration pipelines with specialized tool-calling agents, MCP (Model Context Protocol) servers, and autonomous task decomposition
- Workflow automation with n8n and custom agent frameworks for production decision support
- RAG architectures combining vector retrieval, knowledge graph traversal, and LLM reasoning across 268M embedded passages
- Edge AI deployment for low-connectivity environments in field health surveillance
- LLM-as-judge evaluation systems with multi-dimensional scoring and automated quality gates

**Data infrastructure at scale**
- Apache Iceberg lakehouse federating 1.78 billion rows from 85 source organizations (WHO, World Bank, NOAA, IHME, UNICEF, OECD, and 79 others) across 58,000+ geographic entities spanning 1807 to 2100
- 268 million vector embeddings in OpenSearch for semantic retrieval over biomedical literature
- 33 million causal relation triples in a knowledge graph built from structured biomedical sources
- Automated ingestion from 150+ APIs with EventBridge scheduling, deduplication, and lineage tracking

**Foundation models and training**
- End-to-end training pipelines: continued pretraining, supervised fine-tuning, direct preference optimization
- Hard-negative DPO generation with BM25 recall and neural reranking
- Custom evaluation benchmarks with multi-dimensional LLM-as-judge scoring
- Mixture-of-experts routing with domain-specialized adapters
- Distributed training across multi-GPU clusters with DeepSpeed and FSDP

**Production systems**
- Disease early warning and response systems serving national health programs
- Malaria prediction infrastructure with Terraform-managed cloud deployment
- Real-time surveillance dashboards processing multi-source health signals
- Enterprise serving layers with persona-aware views for ministers, analysts, and donors

---

#### Technical surface

```
Languages       Python, TypeScript, SQL, HCL, Shell
Agentic AI      MCP servers, tool-calling agents, n8n, LangGraph, autonomous orchestration
LLM/FM          PyTorch, Transformers, PEFT, DeepSpeed, vLLM, GGUF, Ollama
Data            Apache Iceberg, Athena, DuckDB, PostgreSQL, Parquet
Search          OpenSearch (AOSS + managed), BM25, kNN, HNSW
Cloud           AWS (S3, Lambda, Glue, Bedrock, SageMaker, EFA)
Edge            ONNX Runtime, TFLite, quantized models for field deployment
Infra           Terraform, Docker, EventBridge, CloudWatch
Serving         TiTiler (COG), FastAPI, Next.js
```

---

#### Organizations I lead

| Organization | Role | Focus |
|:-------------|:-----|:------|
| [IMACS-Health-Modeling](https://github.com/IMACS-Health-Modeling) | Founder and Lead | Foundation models, multi-agent platforms, SAGE engine, and climate-health intelligence across 22 repositories |
| [Forecasting-Healthy-Futures](https://github.com/Forecasting-Healthy-Futures) | Founder and Lead | Climate-informed disease forecasting and early warning systems for LMICs across 30 repositories with 8 contributors |
| [UnlockDigitalHealth](https://github.com/UnlockDigitalHealth) | Founder | Digital health infrastructure and open-source tools for health system strengthening |

#### Selected repositories

**Platform and AI systems** (under [IMACS-Health-Modeling](https://github.com/IMACS-Health-Modeling))

| Repository | What it does |
|:-----------|:-------------|
| [imacs-sage](https://github.com/IMACS-Health-Modeling/imacs-sage) | SAGE -- Scientific Advisory and Guidance Engine. Multi-agent orchestration platform for global health intelligence |
| [imacs-sage-playground](https://github.com/IMACS-Health-Modeling/imacs-sage-playground) | Foundation model AI playground -- interactive demo for the 7B parameter model with MoLE expert routing |
| [AI-Sandbox](https://github.com/IMACS-Health-Modeling/AI-Sandbox) | Agentic AI sandbox -- RAG pipelines, multi-agent prototyping, and tool-calling agent experimentation |
| [malaria-intelligence-platform](https://github.com/IMACS-Health-Modeling/malaria-intelligence-platform) | Multi-country malaria analytics with climate-driven forecasting and intervention tracking |
| [imacs-cdah-main](https://github.com/IMACS-Health-Modeling/imacs-cdah-main) | Climate Data Analytics Hub -- multi-tenant health intelligence with data fabric and RBAC |

**Data infrastructure and research**

| Repository | What it does |
|:-----------|:-------------|
| [sage-warehouse-master](https://github.com/drkaushiksarkar/sage-warehouse-master) | 1.78B-row analytical warehouse with 117 production scripts, enterprise API, and foundation model training pipeline |
| [spectra-enterprise](https://github.com/drkaushiksarkar/spectra-enterprise) | Enterprise health intelligence platform with multi-agent orchestration and autonomous data fusion |
| [bdewarspred](https://github.com/drkaushiksarkar/bdewarspred) | Full-stack disease early warning and prediction system (890K+ lines TypeScript) |
| [malaria-forecasting-system](https://github.com/drkaushiksarkar/malaria-forecasting-system) | Production malaria incidence forecasting with Terraform-managed cloud infrastructure |
| [climate-disease-forecast](https://github.com/drkaushiksarkar/climate-disease-forecast) | Climate-driven disease prediction models using ERA5 reanalysis data |

---

#### Research

Three active research tracks targeting NeurIPS 2026: a novel training paradigm for domain-specialized foundation models (EGDA), a multi-dimensional evaluation benchmark for health AI (CHIB), and expert routing in mixture-of-experts architectures (MoLE).

Prior work in computational epidemiology established AI-driven early warning systems for infectious disease outbreaks across low and middle-income countries -- systems now operational in multiple national health programs.

---

#### Scale

| Metric | Value |
|:-------|:------|
| Countries served | 17 |
| Data rows under management | 1.78 billion |
| Vector embeddings | 268 million |
| Knowledge graph triples | 33 million |
| Source organizations federated | 85 |
| Indicators catalogued | 40,000+ |
| Geographic entities | 58,000+ |
| Temporal coverage | 1807 to 2100 |

---

<sub>Delhi, India -- [drkaushiks.com](https://www.drkaushiks.com) -- [X/Twitter](https://twitter.com/drkaushiksarkar)</sub>
