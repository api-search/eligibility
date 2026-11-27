---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old and meet the minimum age of digital consent in your country.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create login credentials. We may refuse or revoke access if credentials are inappropriate.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Applied Compute
provenance_date: '2026-11-09'
provider_name: Applied Compute
provider_slug: applied-compute
slug: applied-compute-eligibility
source_date: '2026-11-09'
source_filename: applied-compute-eligibility.yml
source_heading: Eligibility
source_page: https://www.appliedcompute.com/legals/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Applied Compute\naid: applied-compute\nurl: https://www.appliedcompute.com/legals/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must create login credentials. We may refuse or revoke access if credentials are inappropriate.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old and meet the minimum age of digital consent in your country.\n"
source_yaml_url: https://artifacts.apis.io/applied-compute/eligibility/applied-compute-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from Applied Compute's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- LLM
- Model Training
- Inference
- AI Agents
- Enterprise AI
- Fine-Tuning
- Reinforcement Learning
---
