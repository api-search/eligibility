---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: You agree to use the Service only for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must create an account with a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ThirdWatch
provenance_date: '2026-11-10'
provider_name: ThirdWatch
provider_slug: thirdwatch
slug: thirdwatch-eligibility
source_date: '2026-11-10'
source_filename: thirdwatch-eligibility.yml
source_heading: Eligibility
source_page: https://thirdwatch.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThirdWatch\naid: thirdwatch\nurl: https://thirdwatch.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: You agree to use the Service only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must create an account with a valid email address.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/thirdwatch/eligibility/thirdwatch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from ThirdWatch's own page on 2026-11-10.
synthetic: false
tags:
- API Monitoring
- OAuth
- JWT
- OpenAPI
- Alerting
- Performance Dashboard
- Multi‑organization
- Anomaly Detection
- Authentication
---
