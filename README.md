# Dev Patram

**Solutions engineer: AI engineering, production software, customer-facing delivery.**

I build software that people in plants and field operations use every day: phone apps for capturing work, pipelines
that turn those entries into customer reports, and AI steps that suggest while a person decides. Electrical and
computer engineer, 20 years at EchoStar across field service, technical training, solutions and electrical
engineering, now building the reliability platform behind customer engagements at Advanced Technology Services.
D.Eng. candidate in AI and Machine Learning at George Washington University.

## Projects

Public versions of patterns I use at work, rebuilt from scratch with made-up or public data. Each has tests that run
in CI and a README that shows its results, including what does not work yet.

| Repo | What it shows |
| --- | --- |
| [gemini-workorder-agent](https://github.com/devpatram/gemini-workorder-agent) | A Google ADK agent on Gemini that answers maintenance questions from work-order history through four tested tools, cites order numbers, reads CSV or BigQuery, and deploys to Agent Runtime or Cloud Run. |
| [llm-guardrails-hitl](https://github.com/devpatram/llm-guardrails-hitl) | Model suggests, deterministic checks and a second opinion filter, a person accepts, edits or rejects, and every decision is logged. Evaluated on 40 labeled cases. |
| [sec-10k-rag-benchmark](https://github.com/devpatram/sec-10k-rag-benchmark) | Dense vs BM25 vs hybrid vs query-decomposition retrieval over three 10-K filings (455 pages), with open models and a failure analysis. |
| [workorder-failure-classifier](https://github.com/devpatram/workorder-failure-classifier) | Keyword rules vs TF-IDF vs an LLM with output validation for classifying free-text work orders, scored on wording the models have and have not seen. |
| [field-reports-pipeline](https://github.com/devpatram/field-reports-pipeline) | Low-code capture, Python run by a CI pipeline, people own the exceptions: validation, idempotent re-runs, report revisions and a run log, on Azure DevOps and GitHub Actions. |

## At work (the code stays there)

- A field reporting platform built on Power Apps, SharePoint, Power Automate and Azure DevOps pipelines running
  Python: 3 canvas apps, 20+ flows, 9 pipelines and 6 Python repos with 421 tests, now in daily use by technicians.
- A language-model step in production that classifies equipment work orders, called from Python in batches of 50 at
  temperature 0.
- Reliability engagements at manufacturing sites: FMEA workshops and equipment assessments, with tools that prepare
  the workshop material in advance.

## Skills

Python · SQL · Power Apps · Power Automate · AI Builder · SharePoint · Azure DevOps · Git · GitHub Actions ·
Google ADK · Gemini · retrieval-augmented generation (FAISS, BM25) · scikit-learn · PyTorch ·
Hugging Face Transformers · reliability engineering (FMEA, RCA)

## Education

- D.Eng., Artificial Intelligence and Machine Learning, George Washington University (in progress)
- M.S., Computer Engineering, Johns Hopkins University
- B.S., Electrical Engineering, Arizona State University

[LinkedIn](https://www.linkedin.com/in/dev-patram/)
