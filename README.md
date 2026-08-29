# DHANANJAY NERKAR

### AI/ML Engineer Candidate · RAG · LLM Applications · Applied Machine Learning

I build evidence-grounded AI applications and evaluation-aware machine-learning systems with Python.

My strongest public work combines local LLM inference, document ingestion, embeddings, hybrid retrieval, pgvector, reranking, citations, access control, model artifacts, and reproducible evaluation.

[GitHub](https://github.com/dhananjaynerkar) · [LinkedIn](https://www.linkedin.com/in/dhananjay-nerkar) · [Portfolio](https://portfolio-dhananjay-pi.vercel.app/) · [Resume](https://drive.google.com/file/d/1ECEzfyvgtdTXVBgBlhFwMT5JSecnWnET/view?usp=sharing)

> Portfolio boundary: production deployment, cloud ownership, user scale, and business impact are not claimed unless the linked repository provides evidence.

---

## What I Build

| Focus | Repositories | Demonstrated capability |
|---|---|---|
| **Grounded document AI** | [Port Management RAG](https://github.com/dhananjaynerkar/ai_powered_port_management_system) | PDF/OCR ingestion, hybrid retrieval, citations, ACLs, local generation |
| **Fraud and risk ML** | [ClaimShield](https://github.com/dhananjaynerkar/claimshield) · [Insurerisk](https://github.com/dhananjaynerkar/insurerisk) | Leakage-aware preprocessing, imbalance handling, temporal validation, threshold and business-loss analysis |
| **Data and ML engineering** | [Spark education analytics](https://github.com/dhananjaynerkar/case_study_apache_spark) | RDDs, DataFrames, Spark SQL, ETL, Spark ML, Docker, Kubernetes packaging |
| **NLP retrieval** | [HealthBot](https://github.com/dhananjaynerkar/HealthBot) | Structured symptom matching, dense retrieval, multilingual normalization, safety rules |

## Verified Technology Stack

| Area | Tools and methods |
|---|---|
| **Programming** | Python · SQL |
| **Machine Learning** | scikit-learn · TensorFlow/Keras · Spark ML · feature engineering · imbalanced learning · model evaluation |
| **GenAI and RAG** | Ollama · embeddings · PostgreSQL full-text search · pgvector · hybrid retrieval · reciprocal rank fusion · reranking · citations · provenance |
| **Applications and Data** | FastAPI · Flask · Streamlit · PostgreSQL · PySpark · Spark SQL |
| **Quality and Reproducibility** | pytest · Ruff · model/artifact serialization · configuration-driven pipelines · GitHub Actions · Docker · Kubernetes packaging |

## Featured Projects

### 1. [AI-Powered Port Management System](https://github.com/dhananjaynerkar/ai_powered_port_management_system)

**Status:** Local-first prototype; production deployment is not verified.

A port-management RAG and workflow platform using Python, FastAPI, PostgreSQL, pgvector, Ollama, and BGE-M3.

- PDF/OCR ingestion with page-level provenance and quarantine states.
- Lexical plus dense retrieval with rank fusion, reranking, ACL filtering, and citation validation.
- Documented corpus-bound checkpoint: AnyHit@5 **0.89**, EvidenceCoverage@5 **0.85**, **10/10** mapped facts covered, and **9/9** citation-valid replays.
- Includes architecture, security, evaluation, workflow, operations, and bounded CI documentation.

### 2. [ClaimShield](https://github.com/dhananjaynerkar/claimshield)

**Status:** Deep-learning decision-support workflow; dataset redistribution rights require confirmation.

A TensorFlow/Keras insurance-fraud workflow with leakage-aware preprocessing, training-only imbalance handling, validation-based threshold selection, and reloadable inference artifacts.

- Uses structured preprocessing, class-imbalance handling, regularization, early stopping, and saved model metadata.
- Documented test checkpoint: ROC-AUC **0.8161**, PR-AUC **0.1829**, and fraud recall **0.8811** at threshold **0.30**.
- Intended to support investigation, not automatically reject claims.

### 3. [Insurance Fraud and Claim Risk Pipeline](https://github.com/dhananjaynerkar/insurerisk)

**Status:** Evaluation-aware local ML pipeline.

A time-aware tabular ML workflow with leakage auditing, temporal features, imbalance handling, threshold tuning, business-loss analysis, serialized artifacts, and Streamlit scoring.

- Documents the temporal split, evaluation boundary, input provenance, and model-selection trade-offs.
- The recorded test-window checkpoint is weak; no production success or business impact is claimed.

### 4. [Smart Education Analytics with PySpark](https://github.com/dhananjaynerkar/case_study_apache_spark)

**Status:** Academic case study with local Docker/Kubernetes packaging; not a production Spark cluster.

An OULAD-based education analytics workflow covering RDDs, DataFrames, Spark SQL, ETL feature preparation, and Spark ML classification.

- Provides a Mermaid architecture diagram, notebook runner, generated metrics, Dockerfile, Kubernetes manifests, and GitHub Actions checks.
- Reported holdout metrics are AUC **0.9706**, accuracy **0.9142**, and F1 **0.9142** for the provided case-study outcome proxy.

## AI/ML Engineering Capabilities

- **Retrieval systems:** dense retrieval, hybrid search, pgvector, rank fusion, reranking, page-level provenance, and access-controlled context.
- **LLM applications:** local inference, grounded generation, prompt controls, output validation, citation checks, and no-evidence handling.
- **Machine learning:** feature engineering, leakage auditing, temporal validation, class-imbalance handling, threshold tuning, and task-appropriate metrics.
- **AI application engineering:** FastAPI services, PostgreSQL-backed workflows, Streamlit scoring, readiness checks, tests, and serialized artifacts.

## Engineering Practices

- Separate implementation evidence from deployment and production-readiness claims.
- Treat datasets, credentials, evaluation splits, and generated artifacts as explicit boundaries.
- Prefer reproducible configuration, model contracts, provenance notes, and failure handling.
- Use tests and CI to verify portable behavior while documenting excluded live-database or fixture-dependent checks.

## Proof of Work

```
Problem
  ↓
Data or document corpus
  ↓
Retrieval / model pipeline
  ↓
API or application
  ↓
Evaluation and failure handling
  ↓
Reproducibility and bounded deployment
```

| Capability | Proof |
|---|---|
| **RAG / LLM** | [Port RAG](https://github.com/dhananjaynerkar/ai_powered_port_management_system) → retrieval, citation, ACL, and runtime evaluation |
| **Fraud ML** | [ClaimShield](https://github.com/dhananjaynerkar/claimshield) → thresholded deep-learning inference and test metrics |
| **Evaluation-aware ML** | [Insurerisk](https://github.com/dhananjaynerkar/insurerisk) → temporal validation, leakage notes, and business-loss framing |
| **Data engineering** | [Spark case study](https://github.com/dhananjaynerkar/case_study_apache_spark) → Spark ETL, Spark ML, Docker, Kubernetes packaging, and CI |

## Current Focus

Strengthening clean-checkout reproducibility, corpus-versioned evaluation, citation/grounding checks, and clearly bounded local deployment for existing AI/ML systems.

## Connect

- Email: nerkarr.dhananjay@gmail.com
- LinkedIn: https://www.linkedin.com/in/dhananjay-nerkar
- Portfolio: https://portfolio-dhananjay-pi.vercel.app/
- GitHub: https://github.com/dhananjaynerkar
