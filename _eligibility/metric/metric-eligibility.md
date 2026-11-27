---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you state that you are not less than 18 (eighteen) years of age
    type: individual
  minimum_age:
    text: you state that you are not less than 18 (eighteen) years of age
    value: '18'
  restricted_uses:
  - summary: Activities competing with Metric
    text: Users may not use the Services and/or Site to engage themselves in activities which are identical or similar to Metric’s business.
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
name: Metric
provenance_date: '2026-11-10'
provider_name: Metric
provider_slug: metric
slug: metric-eligibility
source_date: '2026-11-10'
source_filename: metric-eligibility.yml
source_heading: Eligibility
source_page: https://metricapp.co/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metric\naid: metric\nurl: https://metricapp.co/terms-of-service.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you state that you are not less than 18 (eighteen) years of age\nrestricted_uses:\n- summary: Activities competing with Metric\n  text: Users may not use the Services and/or Site to engage themselves in activities which are identical or similar\n    to Metric’s business.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you state that you are not less\
  \ than 18 (eighteen) years of age\n"
source_yaml_url: https://artifacts.apis.io/metric/eligibility/metric-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Metric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Accounting
- Financial Management
- Fintech
- Bookkeeping
- Invoicing
- Artificial Intelligence
- VAT Compliance
- Small Business
---
