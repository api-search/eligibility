---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not for diagnosis or treatment decisions
    text: 'Do not use Phi Longevity to: • Diagnose a medical condition • Make treatment decisions'
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
name: Phi Longevity
provenance_date: '2026-11-10'
provider_name: Phi Longevity
provider_slug: philongevity-com
slug: philongevity-com-eligibility
source_date: '2026-11-10'
source_filename: philongevity-com-eligibility.yml
source_heading: Eligibility
source_page: https://philongevity.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phi Longevity\naid: philongevity-com\nurl: https://philongevity.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Not for diagnosis or treatment decisions\n  text: 'Do not use Phi Longevity to: • Diagnose a medical condition • Make treatment decisions'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/philongevity-com/eligibility/philongevity-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Phi Longevity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Data
- Lab Results
- Biomarkers
- Chronic Disease
- Longevity
- MCP
- A2A
- Agentic Payments
- x402
- Artificial Intelligence
---
