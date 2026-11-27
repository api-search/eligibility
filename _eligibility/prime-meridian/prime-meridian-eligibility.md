---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service
    value: '18'
  restricted_uses:
  - summary: Unlawful or improper purposes
    text: (d) use the Services for any unlawful or improper purpose.
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
name: Prime Meridian
provenance_date: '2026-11-10'
provider_name: Prime Meridian
provider_slug: prime-meridian
slug: prime-meridian-eligibility
source_date: '2026-11-10'
source_filename: prime-meridian-eligibility.yml
source_heading: Eligibility
source_page: https://getprimemeridian.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prime Meridian\naid: prime-meridian\nurl: https://getprimemeridian.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or improper purposes\n  text: (d) use the Services for any unlawful or improper purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service\n"
source_yaml_url: https://artifacts.apis.io/prime-meridian/eligibility/prime-meridian-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Prime Meridian's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tax
- Tax Filing
- Fintech
- Consumer Finance
- Artificial Intelligence
- Accounting
---
