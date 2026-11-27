---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Country refers to Australia.
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful security testing
    text: You may not use the Service for unlawful security testing, penetration testing, or exploitation of systems outside the controlled environments provided by the Company.
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
name: secdim-com
provenance_date: '2026-11-10'
provider_name: secdim-com
provider_slug: secdim-com
slug: secdim-com-eligibility
source_date: '2026-11-10'
source_filename: secdim-com-eligibility.yml
source_heading: Eligibility
source_page: https://secdim.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: secdim-com\naid: secdim-com\nurl: https://secdim.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Country refers to Australia.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful security testing\n  text: You may not use the Service for unlawful security testing, penetration testing, or exploitation of systems\n    outside the controlled environments provided by the Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/secdim-com/eligibility/secdim-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from secdim-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Training
- Artificial Intelligence
- Developers
---
