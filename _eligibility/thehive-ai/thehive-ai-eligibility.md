---
api_specs:
- filename: thehive-ai-task-api-openapi.yml
  format: yaml
  label: Hive Task API
  slug: thehive-ai-task-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thehive-ai/openapi/thehive-ai-task-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO ENTER INTO THE TERMS (TYPICALLY, AT LEAST 18 YEARS OLD).
    value: '18'
  restricted_uses:
  - summary: Facial recognition and identification
    text: unless otherwise expressly authorized in writing by Deploy, Customer shall not use the AI Service for the purpose of identifying any person
  - summary: High-risk and EU AI Act-similar uses
    text: use the Services or output therefrom in connection with any (i) practice similar to prohibited practices described under Regulation (EU) 2024/1689, as amended (the “EU AI Act”), or (ii) system similar to any system considered to be a high-risk AI system under the EU AI Act
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
name: Hive
provenance_date: '2026-11-10'
provider_name: Hive
provider_slug: thehive-ai
slug: thehive-ai-eligibility
source_date: '2026-11-10'
source_filename: thehive-ai-eligibility.yml
source_heading: Eligibility
source_page: https://deploy.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hive\naid: thehive-ai\nurl: https://deploy.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Facial recognition and identification\n  text: unless otherwise expressly authorized in writing by Deploy, Customer shall not use the AI Service for the\n    purpose of identifying any person\n- summary: High-risk and EU AI Act-similar uses\n  text: use the Services or output therefrom in connection with any (i) practice similar to prohibited practices\n    described under Regulation (EU) 2024/1689, as\
  \ amended (the “EU AI Act”), or (ii) system similar to any system\n    considered to be a high-risk AI system under the EU AI Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE OF LEGAL AGE TO ENTER INTO THE TERMS (TYPICALLY, AT LEAST 18 YEARS OLD).\n"
source_yaml_url: https://artifacts.apis.io/thehive-ai/eligibility/thehive-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Data Labeling
- Enterprise
---
