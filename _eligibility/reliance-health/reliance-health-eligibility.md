---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By placing an order through this website, you warrant that you are at least 18 years old and are legally capable of entering into binding contracts.
    type: individual
  minimum_age:
    text: you warrant that you are at least 18 years old and are legally capable of entering into binding contracts
    value: '18'
  restricted_uses:
  - summary: Speculative or fraudulent orders
    text: Not to make any speculative, false or fraudulent enquiries or orders.
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
name: Reliance Health
provenance_date: '2026-11-10'
provider_name: Reliance Health
provider_slug: reliance-health
slug: reliance-health-eligibility
source_date: '2026-11-10'
source_filename: reliance-health-eligibility.yml
source_heading: Eligibility
source_page: https://getreliancehealth.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reliance Health\naid: reliance-health\nurl: https://getreliancehealth.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By placing an order through this website, you warrant that you are at least 18 years old and are legally\n    capable of entering into binding contracts.\nrestricted_uses:\n- summary: Speculative or fraudulent orders\n  text: Not to make any speculative, false or fraudulent enquiries or orders.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: you warrant that you are at least 18 years old and are legally capable of entering into binding contracts\n"
source_yaml_url: https://artifacts.apis.io/reliance-health/eligibility/reliance-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Reliance Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Insurance
- HMO
- Telehealth
- Employee Benefits
- Insurtech
- Africa
- Nigeria
---
