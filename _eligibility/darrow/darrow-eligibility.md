---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The Torch Service may only be used by individuals who: (i) can form legally binding contracts under applicable law'
    type: individual
  minimum_age:
    text: Persons under 18 years of age are not authorized to use the Site.
    value: '18'
  restricted_uses:
  - summary: High-risk / fail-safe environments
    text: use the Torch Service in connection with any high-risk, hazardous environments requiring fail-safe performance
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
name: Darrow
provenance_date: '2026-11-09'
provider_name: Darrow
provider_slug: darrow
slug: darrow-eligibility
source_date: '2026-11-09'
source_filename: darrow-eligibility.yml
source_heading: Eligibility
source_page: https://www.darrow.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Darrow\naid: darrow\nurl: https://www.darrow.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'The Torch Service may only be used by individuals who: (i) can form legally binding contracts under applicable\n    law'\nrestricted_uses:\n- summary: High-risk / fail-safe environments\n  text: use the Torch Service in connection with any high-risk, hazardous environments requiring fail-safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: Persons under 18 years of age are not authorized to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/darrow/eligibility/darrow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Darrow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Intelligence
- Litigation
- Artificial Intelligence
- Compliance
- Risk Management
- Insurance
- Data Analytics
---
