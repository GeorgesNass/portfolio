# Georges Nass — Portfolio

Applied ML & MLOps Engineer building production-grade AI systems (Medical NLP, Agentic LLM, scalable pipelines).

## Featured

* **OCR** → [link](https://github.com/GeorgesNass/ocr-universal)
 
  Modular OCR pipeline (Tesseract, EasyOCR, PaddleOCR, doc2text) to **extract and structure text from documents and images for downstream processing**.

* **Medical NLP suite** → [link](https://github.com/GeorgesNass/medical-nlp)

  | Name | Short description | Link |
  |------|------------------|------|
  | doc-classification | Semantic similarity pipeline for multi-label classification of medical documents to **automate document triage and support clinical workflows**. | [link](https://github.com/GeorgesNass/medical-nlp/tree/main/doc-classification) |
  | icd10-prediction | End-to-end ML pipeline predicting ICD10 codes from clinical text to **streamline medical coding and reduce manual workload**. | [link](https://github.com/GeorgesNass/medical-nlp/tree/main/icd10-prediction) |
  | mesh-semantic-expansion | NLP pipeline leveraging MeSH ontology for synonym and term expansion to **improve search, indexing and information retrieval**. | [link](https://github.com/GeorgesNass/medical-nlp/tree/main/mesh-semantic-expansion) |
  | clinical-ner | Clinical NER pipeline (entity extraction, normalization, negation, temporality) to **structure medical text for downstream analytics and decision support**. | [link](https://github.com/GeorgesNass/medical-nlp/tree/main/clinical-ner) |
  | lab-clustering | Unsupervised pipeline transforming lab reports into structured data and clusters to **enable analysis and support data-driven insights**. | [link](https://github.com/GeorgesNass/medical-nlp/tree/main/lab-clustering) |

* **Agentic LLM suite** → [link](https://github.com/GeorgesNass/agentic-llm)

  | Name | Short description | Link |
  |------|------------------|------|
  | autonomous-ai-platform | Agentic LLM platform (local models, vLLM, RAG, Text-to-SQL, Airflow) to **automate complex workflows and enable scalable AI-driven systems**. | [link](https://github.com/GeorgesNass/agentic-llm/tree/main/autonomous-ai-platform) |
  | llm-proxy-gateway | Gateway orchestrating multiple LLM providers (OpenAI, Gemini, xAI) with evaluation and cost simulation to **optimize usage and standardize AI integration**. | [link](https://github.com/GeorgesNass/agentic-llm/tree/main/llm-proxy-gateway) |
  | rag-drive-gcp | End-to-end RAG architecture on GCP (Drive ingestion, OCR, embeddings, chat interface) to **transform documents into actionable insights**. | [link](https://github.com/GeorgesNass/agentic-llm/tree/main/rag-drive-gcp) |
  | local-finetuning | LLM fine-tuning pipelines (LoRA / QLoRA) for **domain adaptation and improved task performance**. | [link](https://github.com/GeorgesNass/agentic-llm/tree/main/local-finetuning) |
  | local-quantization | LLM quantization techniques (GGUF, GPTQ, AWQ, ONNX) to **reduce infrastructure costs and enable efficient deployment**. | [link](https://github.com/GeorgesNass/agentic-llm/tree/main/local-quantization) |

* **Traffic prediction** → [link](https://github.com/Traffic-forecasting-project/traffic_prediction)

  MLOps pipeline for real-time traffic congestion forecasting (TomTom, OpenWeather) to **support data-driven decision-making and operational planning**.

* **Data deduplication** → [link](https://github.com/GeorgesNass/data-deduplication)

  Fuzzy matching pipeline (blocking, similarity metrics, supervised ML) to **detect duplicates and improve data quality across datasets**.

* **Monitoring API Analytics** → [link](https://github.com/GeorgesNass/monitoring-api-analytics)

  Monitoring pipeline (logs, BigQuery, dashboards) to **analyze API usage and ensure system performance and reliability**.  
  
* **MLOps Certifications** → [link](https://github.com/GeorgesNass/mlops-certifications)

  Hands-on certification exercises and technical projects covering multiple areas of the MLOps stack:

  * Docker containerization
  * Linux scripting and JSON processing with jq
  * BentoML model packaging and serving
  * Data and model drift monitoring
  * FastAPI production API services
  * Monitoring with Prometheus and Grafana
  * Workflow orchestration with Airflow
  * ML project deliverables and production packaging
  * DVC and Dagshub data versioning pipelines
  * Kubernetes deployment for ML workloads

## Private repositories+

Some repositories are private (exams / compliance):

* email-web-scraping (private)
* mt5-trading (private)

## Engineering & MLOps stack across projects

This section provides a comprehensive view of the ML lifecycle: INFRA → DATA → PIPELINES → ML → VALIDATION → OBSERVABILITY.

➡️ **[Open the interactive stack matrix](https://georgesnass.github.io/portfolio/stack-matrix.html)**

<p align="center">
✔ implemented &nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; ⚡ GPU strongly recommended &nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; ✖ not required &nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; 🟡 planned / TODO
</p>

| Category | Feature | Stack&nbsp;/&nbsp;Tools | OCR | doc&#8209;classification | icd10&#8209;prediction | mesh&#8209;semantic&#8209;expansion | clinical&#8209;ner | lab&#8209;clustering | autonomous&#8209;ai&#8209;platform | llm&#8209;proxy&#8209;gateway | rag&#8209;drive&#8209;gcp | local&#8209;finetuning | local&#8209;quantization | traffic&#8209;prediction | data&#8209;deduplication | monitoring&#8209;api&#8209;analytics |
|:--|:--|:--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| INFRASTRUCTURE | Containerization | Docker | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| INFRASTRUCTURE | Container&nbsp;orchestration | Kubernetes | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| INFRASTRUCTURE | GPU&nbsp;acceleration | CUDA&nbsp;/&nbsp;vLLM | ✔ | ✔ | ✔ | ✖ | ✔ | ✖ | ✔⚡ | ✖ | ✔ | ✔⚡ | ✔ | ✖ | ✖ | ✖ |
| INFRASTRUCTURE | Secrets&nbsp;management | .env&nbsp;/&nbsp;vault | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✖ | ✔ | ✔ | ✔ |
| INFRASTRUCTURE | API&nbsp;security | JWT&nbsp;/&nbsp;API&nbsp;keys | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✖ | ✔ | ✔ | ✔ |
| INFRASTRUCTURE | Access&nbsp;control&nbsp;/&nbsp;RBAC | OAuth2&nbsp;/&nbsp;roles | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✖ | ✔ | ✔ | ✔ |
| DATA&nbsp;QUALITY | Data&nbsp;validation | Pydantic&nbsp;/&nbsp;Pandera | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ |
| DATA&nbsp;QUALITY | Data&nbsp;consistency | cross&#8209;source&nbsp;/&nbsp;business&nbsp;rules | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ |
| DATA&nbsp;QUALITY | Anomaly&nbsp;detection | z&#8209;score&nbsp;/&nbsp;IQR | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | 🟡 |
| DATA&nbsp;QUALITY | Data&nbsp;drift&nbsp;detection | Evidently | ✖ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ |
| DATA&nbsp;QUALITY | Drift&nbsp;monitoring | Evidently&nbsp;/&nbsp;metrics | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | 🟡 |
| DATA&nbsp;QUALITY | Data&nbsp;contracts | schema&nbsp;validation&nbsp;/&nbsp;evolution | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | CI/CD&nbsp;pipelines | GitHub&nbsp;Actions&nbsp;/&nbsp;GitLab&nbsp;CI | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Orchestration&nbsp;pipelines | Airflow | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Data&nbsp;ingestion | APIs&nbsp;/&nbsp;ETL&nbsp;/&nbsp;connectors | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✖ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Feature&nbsp;engineering&nbsp;pipelines | transformations&nbsp;/&nbsp;feature&nbsp;pipelines | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Training&#8209;serving&nbsp;consistency | offline&nbsp;vs&nbsp;online&nbsp;features | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Batch&nbsp;inference&nbsp;pipelines | Airflow&nbsp;/&nbsp;Pandas&nbsp;/&nbsp;PySpark | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Real&#8209;time&nbsp;inference | Kafka&nbsp;/&nbsp;FastAPI&nbsp;/&nbsp;Redis | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Model&nbsp;serving | FastAPI&nbsp;/&nbsp;BentoML&nbsp;/&nbsp;vLLM | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Auto&#8209;retraining&nbsp;pipelines | Airflow&nbsp;/&nbsp;MLflow&nbsp;/&nbsp;drift&nbsp;triggers | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Scalability&nbsp;&amp;&nbsp;performance | load&nbsp;testing&nbsp;/&nbsp;autoscaling | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Error&nbsp;handling | exceptions&nbsp;/&nbsp;guards | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Testing | pytest | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Object&nbsp;models | Pydantic&nbsp;/&nbsp;dataclasses | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| PIPELINES&nbsp;&amp;&nbsp;DEPLOYMENT | Config&nbsp;structuring | Pydantic&nbsp;/&nbsp;dataclasses | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| ML&nbsp;LIFECYCLE | Experiment&nbsp;tracking | MLflow | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✔ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ |
| ML&nbsp;LIFECYCLE | Model&nbsp;registry | MLflow&nbsp;Model&nbsp;Registry | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| ML&nbsp;LIFECYCLE | Data&nbsp;versioning | DVC | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | ✖ |
| ML&nbsp;LIFECYCLE | Data&nbsp;lineage&nbsp;/&nbsp;provenance | DVC&nbsp;/&nbsp;MLflow | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| ML&nbsp;LIFECYCLE | Feature&nbsp;store | Feast&nbsp;/&nbsp;Redis&nbsp;/&nbsp;BigQuery | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| MODEL&nbsp;VALIDATION | Model&nbsp;validation&nbsp;(offline) | F1&nbsp;/&nbsp;RMSE&nbsp;/&nbsp;precision&nbsp;/&nbsp;recall | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ |
| MODEL&nbsp;VALIDATION | Model&nbsp;validation&nbsp;(business) | domain&nbsp;/&nbsp;stakeholder&nbsp;checks | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ | ✖ |
| MODEL&nbsp;VALIDATION | A/B&nbsp;testing | online&nbsp;experiments | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| MODEL&nbsp;VALIDATION | Reproducibility | environments&nbsp;/&nbsp;deterministic&nbsp;pipelines | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| MODEL&nbsp;VALIDATION | Underfitting&nbsp;checks | bias&nbsp;/&nbsp;model&nbsp;complexity | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| MODEL&nbsp;VALIDATION | Overfitting&nbsp;checks | CV&nbsp;/&nbsp;holdout&nbsp;/&nbsp;regularization | ✖ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ |
| MODEL&nbsp;VALIDATION | Model&nbsp;explainability | SHAP&nbsp;/&nbsp;LIME&nbsp;/&nbsp;sklearn | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| OBSERVABILITY | Structured&nbsp;logging | Python&nbsp;logging | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| OBSERVABILITY | Monitoring&nbsp;&amp;&nbsp;observability | Prometheus&nbsp;/&nbsp;Grafana | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✔ |
| OBSERVABILITY | Alerting&nbsp;&amp;&nbsp;incident&nbsp;response | Alertmanager | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| OBSERVABILITY | Cost&nbsp;monitoring | tokens&nbsp;/&nbsp;GPU&nbsp;/&nbsp;API&nbsp;usage | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✔ | ✔ | ✔ | ✔ | ✔ | 🟡 | 🟡 | 🟡 |

<p align="center">
✔ implemented &nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; ⚡ GPU strongly recommended &nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; ✖ not required &nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; 🟡 planned / TODO
</p>


## Contact

- GitHub: https://github.com/GeorgesNass
- LinkedIn: [Georges Nassopoulos](https://www.linkedin.com/in/georges-nassopoulos-92a759151/)
