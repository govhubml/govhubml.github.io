# GovHub ML // Sovereign AI & Financial LLM Datasets

Pre-normalised, structure-sealed **JSON Lines (`.jsonl`)** training corpora compiled from official UK Central Government (Whitehall), local council, HM Land Registry, and international open expenditure disclosures.

Eliminate weeks of fragile regex parsing and schema normalisation. Every dataset includes deterministic **90/10 `train.jsonl` and `validation.jsonl` splits**, a **100-row instant preview**, and full **UK Open Government Licence v3.0 (OGL v3)** provenance.

---

## 🆓 Free 1,000-Row Starter Sample (Test Our Schema)

Download our stratified 1,000-row multi-task sample to test our 50+ engineered KYB, temporal, UK fiscal quarter, and forensic spend features in Python before purchasing full corpora:

* **[Download Free on Gumroad (£0)](https://gumroad.com)**
* **[Stream on Hugging Face Hub](https://huggingface.co)**
* **[Explore on Kaggle Datasets](https://kaggle.com)**

### Quickstart Python Loader
```python
from datasets import load_dataset

dataset = load_dataset("govhubml/uk-sovereign-procurement-nlp-sample")
print(dataset["train"])
```

---

## 📦 Commercial AI/ML Training Catalogue

### 1. Flagship Enterprise Bundle

| Dataset Suite | Format & Features | Price | Purchase |
| :--- | :--- | :--- | :--- |
| **UK Sovereign AI & Financial LLM Mega-Bundle (7-in-1)** | Complete stack: Yearly Corpora, DPO, KYB Entity Resolution, Forensic CoT, MCP Tool-Calling, Text-to-SQL & GraphRAG | **£999** | **[Buy on Gumroad](https://gumroad.com)** |

### 2. Core Yearly & Vertical Corpora (50+ Engineered Features)

| Dataset Suite | Scope & Use Case | Price | Purchase |
| :--- | :--- | :--- | :--- |
| **UK Whitehall National ML Suite (2025 / 2026)** | Central government expenditure (>£25k) with KYB suffixes, UK fiscal quarters & Benford signals | **£399** | **[Buy on Gumroad](https://gumroad.com)** |
| **UK Local Councils Regional ML Suite (2025 / 2026)** | High-volume local authority spend (>£500) rich in SME vendor entities | **£449** | **[Buy on Gumroad](https://gumroad.com)** |
| **Vertical Domain Fine-Tuning Suites** | Targeted corpora for `GovTech & Cloud`, `Legal Advisory`, `Estates & Construction`, `Workforce HR`, and `Education` | **£229** | **[Buy on Gumroad](https://gumroad.com)** |

### 3. Post-Training, Alignment & Specialized Suites

| Dataset Suite | ML / NLP Task | Price | Purchase |
| :--- | :--- | :--- | :--- |
| **Cross-Jurisdiction Schema Harmonisation** | Raw UK (`GBP`), Canada (`CAD`), Australia (`AUD`), US (`USD`) & EU (`EUR`) rows mapped to one global JSON schema | **£549** | **[Buy on Gumroad](https://gumroad.com)** |
| **DPO Preference Alignment Corpus** | `prompt` / `chosen` / `rejected` pairs eliminating numerical, KYB & fiscal-quarter hallucinations | **£499** | **[Buy on Gumroad](https://gumroad.com)** |
| **Multi-Turn Agentic RAG & MCP Tool Traces** | ChatML `tool_calls` + grounded JSON database responses for financial co-pilots | **£449** | **[Buy on Gumroad](https://gumroad.com)** |
| **Text-to-SQL & DuckDB Analytical Suite** | `CREATE TABLE` DDL + executable SQL (aggregations, `HAVING` anomaly filters & window functions) | **£399** | **[Buy on Gumroad](https://gumroad.com)** |
| **Knowledge Graph Triples (GraphRAG)** | Typed `Subject -> Predicate -> Object` triples & qualifiers for Neo4j and Microsoft GraphRAG | **£399** | **[Buy on Gumroad](https://gumroad.com)** |
| **Forensic Audit & Red-Flag Triage (CoT)** | Step-by-step Chain-of-Thought reasoning on threshold hugging, split invoices & March FYE surges | **£399** | **[Buy on Gumroad](https://gumroad.com)** |
| **Contrastive Entity Resolution & KYB Pairs** | Corporate spelling variants (`label: 1`) + shared-token hard negatives (`label: 0`) for BGE / E5 embeddings | **£349** | **[Buy on Gumroad](https://gumroad.com)** |
| **UK GDPR & FOIA PII Redaction Corpus** | Scrubs personal names, emails, NINOs & bank details while preserving commercial companies | **£349** | **[Buy on Gumroad](https://gumroad.com)** |
| **Document AI & OCR Robustness Suite** | Noisy optical scan text (homoglyphs, line-wrap hyphens) paired with clean JSON output | **£349** | **[Buy on Gumroad](https://gumroad.com)** |
| **GPC & ePCS Corporate Card Telemetry** | Government purchasing card merchant normalisation & expense categorisation | **£329** | **[Buy on Gumroad](https://gumroad.com)** |

### 4. PropTech & Real Estate AI Suites (HM Land Registry UK HPI)

| Dataset Suite | PropTech Use Case | Price | Purchase |
| :--- | :--- | :--- | :--- |
| **UK House Price Index Forecasting Suite** | Sliding 12-month windows (9m history -> 3m forecast) across all UK local authorities | **£349** | **[Buy on Gumroad](https://gumroad.com)** |
| **PropTech Text-to-SQL & Agent Traces** | Regional housing SQL queries + multi-turn valuation tool traces | **£399** | **[Buy on Gumroad](https://gumroad.com)** |
| **PropTech Data-to-Text Market Briefings** | Zero-hallucination regional housing, dwelling-type & cash-vs-mortgage narratives | **£299** | **[Buy on Gumroad](https://gumroad.com)** |

---

## 🔒 Data Lineage & Open Licensing
All datasets are compiled from verified public-sector transparency disclosures and distributed under the statutory terms of the **UK Open Government Licence v3.0 (OGL v3)** and respective regional open-data licences. Every `.zip` archive includes a complete `SOURCES_PROVENANCE.txt` audit manifest.
