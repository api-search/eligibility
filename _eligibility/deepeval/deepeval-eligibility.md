---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PHI without BAA
    text: Customer may not store or process protected health information (as defined in HIPAA) using the Services unless Customer signs a Business Associate Agreement with Confident AI.
  - summary: No payment cardholder data
    text: Customer may not store any payment cardholder information using the Services without Confident AI's prior written approval.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DeepEval
provenance_date: '2026-11-09'
provider_name: DeepEval
provider_slug: deepeval
slug: deepeval-eligibility
source_date: '2026-11-09'
source_filename: deepeval-eligibility.yml
source_heading: Eligibility
source_page: https://www.confident-ai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeepEval\naid: deepeval\nurl: https://www.confident-ai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No PHI without BAA\n  text: Customer may not store or process protected health information (as defined in HIPAA) using the Services\n    unless Customer signs a Business Associate Agreement with Confident AI.\n- summary: No payment cardholder data\n  text: Customer may not store any payment cardholder information using the Services without Confident AI's prior\n    written approval.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/deepeval/eligibility/deepeval-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from DeepEval's own page on 2026-11-09.
synthetic: false
tags:
- LLM Evaluation
- LLM Testing
- Evaluation Framework
- Evaluation Metrics
- LLM Observability
- LLM as a Judge
- G-Eval
- RAG Evaluation
- Agent Evaluation
- Hallucination Detection
- Bias Detection
- Toxicity Detection
- Red Teaming
- Benchmarks
- MMLU
- Synthetic Data Generation
- Prompt Optimization
- CI/CD
- Pytest
- Python
- Open Source
- Apache 2.0
- MCP
---
