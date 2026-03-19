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

## Private repositories

Some repositories are private (exams / compliance):

* email-web-scraping (private)
* mt5-trading (private)

## Engineering & MLOps stack across projects

➡️ **[Open the interactive stack matrix](https://georgesnass.github.io/portfolio/stack-matrix.html)**

| Feature | Stack&nbsp;/&nbsp;Tools | OCR | doc&#8209;classification | icd10&#8209;prediction | mesh&#8209;semantic&#8209;expansion | clinical&#8209;ner | lab&#8209;clustering | autonomous&#8209;ai&#8209;platform | llm&#8209;proxy&#8209;gateway | rag&#8209;drive&#8209;gcp | local&#8209;finetuning | local&#8209;quantization | traffic&#8209;prediction | data&#8209;deduplication | monitoring&#8209;api&#8209;analytics |
|:--|:--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Containerization | Docker | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Container&nbsp;orchestration | Kubernetes | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| GPU&nbsp;acceleration | CUDA&nbsp;/&nbsp;vLLM | ✔ | ✔ | ✔ | ✖ | ✔ | ✖ | ✔⚡ | ✖ | ✔ | ✔⚡ | ✔ | ✖ | ✖ | ✖ |
| Secrets&nbsp;management | .env&nbsp;/&nbsp;vault | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✖ | ✔ | ✔ | ✔ |
| API&nbsp;security | JWT&nbsp;/&nbsp;API&nbsp;keys | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | ✖ | 🟡 | 🟡 | 🟡 |
| CI/CD&nbsp;pipelines | GitHub&nbsp;Actions&nbsp;/&nbsp;GitLab&nbsp;CI | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Orchestration&nbsp;pipelines | Airflow | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Batch&nbsp;inference&nbsp;pipelines | Airflow&nbsp;/&nbsp;Pandas&nbsp;/&nbsp;PySpark | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| Streaming&nbsp;/&nbsp;real&#8209;time&nbsp;inference | Kafka&nbsp;/&nbsp;FastAPI&nbsp;/&nbsp;Redis | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Auto&#8209;retraining&nbsp;pipelines | Airflow&nbsp;/&nbsp;MLflow&nbsp;/&nbsp;drift&nbsp;triggers | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| Experiment&nbsp;tracking | MLflow | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✔ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ |
| Model&nbsp;registry | MLflow&nbsp;Model&nbsp;Registry | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| Data&nbsp;versioning | DVC | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | ✖ |
| Data&nbsp;lineage&nbsp;/&nbsp;provenance | DVC&nbsp;/&nbsp;MLflow | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| Feature&nbsp;store | Feast&nbsp;/&nbsp;Redis&nbsp;/&nbsp;BigQuery | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| Object&nbsp;models | Pydantic&nbsp;/&nbsp;dataclasses | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Config&nbsp;structuring | Pydantic&nbsp;/&nbsp;dataclasses | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Error&nbsp;handling | exceptions&nbsp;/&nbsp;guards | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Structured&nbsp;logging | Python&nbsp;logging | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Testing | pytest | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ |
| Data&nbsp;validation | Pydantic&nbsp;/&nbsp;Pandera | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ |
| Data&nbsp;consistency | cross&#8209;source&nbsp;/&nbsp;business&nbsp;rules | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | 🟡 |
| Anomaly&nbsp;detection | z&#8209;score&nbsp;/&nbsp;IQR | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | 🟡 |
| Data&nbsp;drift&nbsp;detection | Evidently | ✖ | ✔ | ✔ | ✔ | ✔ | ✔ | ✔ | ✖ | ✔ | ✔ | ✖ | ✔ | ✔ | ✔ |
| Data&nbsp;&amp;&nbsp;model&nbsp;drift&nbsp;monitoring | Evidently&nbsp;/&nbsp;metrics | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | 🟡 |
| Model&nbsp;validation&nbsp;(offline) | F1&nbsp;/&nbsp;RMSE&nbsp;/&nbsp;precision&nbsp;/&nbsp;recall | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ |
| Model&nbsp;validation&nbsp;(business) | domain&nbsp;/&nbsp;stakeholder&nbsp;checks | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | 🟡 |
| Overfitting&nbsp;checks | CV&nbsp;/&nbsp;holdout&nbsp;/&nbsp;regularization | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✖ |
| End&#8209;to&#8209;end&nbsp;pipeline&nbsp;validation | source&nbsp;→&nbsp;API&nbsp;/&nbsp;dashboard | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✔ |
| Monitoring&nbsp;&amp;&nbsp;observability | Prometheus&nbsp;/&nbsp;Grafana | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | ✔ |
| Alerting&nbsp;&amp;&nbsp;incident&nbsp;response | Prometheus&nbsp;/&nbsp;Alertmanager&nbsp;/&nbsp;Grafana | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |
| Model&nbsp;explainability | SHAP&nbsp;/&nbsp;LIME&nbsp;/&nbsp;sklearn | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 | 🟡 |

✔ implemented  
⚡ GPU strongly recommended  
✖ not required  
🟡 planned / TODO


## Contact

- GitHub: https://github.com/GeorgesNass
- LinkedIn: [Georges Nassopoulos](https://www.linkedin.com/in/georges-nassopoulos-92a759151/)
