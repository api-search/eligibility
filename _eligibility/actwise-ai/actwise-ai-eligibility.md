---
api_specs:
- filename: actwise-ai-openapi-generated.yml
  format: yaml
  label: Actwise API
  slug: actwise-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actwise-ai/openapi/_ae-authored/actwise-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to use the Services.
    value: '18'
  restricted_uses:
  - summary: Harmful, abusive, or fraudulent activity
    text: Use the Services for harmful, abusive, or fraudulent activity
  - summary: Violating laws
    text: Violate laws, regulations, or industry rules
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
name: Actwise
provenance_date: '2026-11-09'
provider_name: Actwise
provider_slug: actwise-ai
slug: actwise-ai-eligibility
source_date: '2026-11-09'
source_filename: actwise-ai-eligibility.yml
source_heading: Eligibility
source_page: https://actwise.ai/home/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Actwise\naid: actwise-ai\nurl: https://actwise.ai/home/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harmful, abusive, or fraudulent activity\n  text: Use the Services for harmful, abusive, or fraudulent activity\n- summary: Violating laws\n  text: Violate laws, regulations, or industry rules\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/actwise-ai/eligibility/actwise-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Actwise's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Governance
- Enterprise
- Delivery
---
