---
api_specs:
- filename: factori-ai-people-api-openapi.yml
  format: yaml
  label: Factori People API
  slug: factori-ai-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factori-ai/openapi/factori-ai-people-api-openapi.yml
- filename: factori-ai-poi-api-openapi.yml
  format: yaml
  label: Factori Poi API
  slug: factori-ai-poi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factori-ai/openapi/factori-ai-poi-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for business and enterprise users.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Services.
    value: '18'
  restricted_uses:
  - summary: Eligibility decisions
    text: you may not use the Services or Data Products to make or support eligibility decisions, including for credit, employment, housing, insurance eligibility, or similar decisions.
  - summary: Sensitive attribute inference
    text: Use Data Products to infer or exploit sensitive attributes (e.g., health status, religion, sexual orientation) unless explicitly permitted under a specific product agreement and lawful.
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
name: Factori
provenance_date: '2026-11-09'
provider_name: Factori
provider_slug: factori-ai
slug: factori-ai-eligibility
source_date: '2026-11-09'
source_filename: factori-ai-eligibility.yml
source_heading: Eligibility
source_page: https://factori.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Factori\naid: factori-ai\nurl: https://factori.ai/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for business and enterprise users.\nrestricted_uses:\n- summary: Eligibility decisions\n  text: you may not use the Services or Data Products to make or support eligibility decisions, including for credit,\n    employment, housing, insurance eligibility, or similar decisions.\n- summary: Sensitive attribute inference\n  text: Use Data Products to infer or exploit sensitive attributes (e.g., health\
  \ status, religion, sexual orientation)\n    unless explicitly permitted under a specific product agreement and lawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/factori-ai/eligibility/factori-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Factori's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Real-World Data
- Forecasting
- Enterprise
- Analytics
---
