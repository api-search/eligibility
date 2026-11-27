---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use them for an organization, you represent that you can bind it, and "you" includes it.
    type: business
  minimum_age:
    text: You must be at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Regulated data
    text: The Services are not designed for regulated data such as protected health information (HIPAA) or payment-card data (PCI DSS).
  - summary: Export and sanctions
    text: You may not use the Services if you are barred from receiving them under U.S. export control or sanctions law, or for an end use those laws prohibit
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
name: Pixeltable
provenance_date: '2026-11-10'
provider_name: Pixeltable
provider_slug: pixeltable
slug: pixeltable-eligibility
source_date: '2026-11-10'
source_filename: pixeltable-eligibility.yml
source_heading: Eligibility
source_page: https://www.pixeltable.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pixeltable\naid: pixeltable\nurl: https://www.pixeltable.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use them for an organization, you represent that you can bind it, and \"you\" includes it.\nrestricted_uses:\n- summary: Regulated data\n  text: The Services are not designed for regulated data such as protected health information (HIPAA) or payment-card\n    data (PCI DSS).\n- summary: Export and sanctions\n  text: You may not use the Services if you are barred from receiving them under U.S. export control or sanctions\n\
  \    law, or for an end use those laws prohibit\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/pixeltable/eligibility/pixeltable-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pixeltable's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Data
- Multimodal AI
- AI Data Infrastructure
- Vector Search
- Embeddings
- RAG
- Agent Memory
- MCP
- Open Source
- Python
- Data Orchestration
- Computed Columns
- Video Processing
- Machine Learning
- A2A
---
