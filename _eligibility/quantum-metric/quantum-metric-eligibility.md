---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Websites are offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: These Websites are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: Use the Websites or any services or materials available through the Websites for any commercial purposes.
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
name: Quantum Metric
provenance_date: '2026-11-10'
provider_name: Quantum Metric
provider_slug: quantum-metric
slug: quantum-metric-eligibility
source_date: '2026-11-10'
source_filename: quantum-metric-eligibility.yml
source_heading: Eligibility
source_page: https://www.quantummetric.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quantum Metric\naid: quantum-metric\nurl: https://www.quantummetric.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Websites are offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: No commercial use\n  text: Use the Websites or any services or materials available through the Websites for any commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: These Websites are offered and available\
  \ to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/quantum-metric/eligibility/quantum-metric-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Quantum Metric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Digital Experience
- Session Replay
- Customer Experience
- Product Analytics
- Observability
---
