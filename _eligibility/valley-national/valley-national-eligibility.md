---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and the services described on the Site are intended for adult individuals only.
    type: individual
  minimum_age:
    text: Valley does not target children under the age of 18
    value: '18'
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
name: Valley National Bank
provenance_date: '2026-11-10'
provider_name: Valley National Bank
provider_slug: valley-national
slug: valley-national-eligibility
source_date: '2026-11-10'
source_filename: valley-national-eligibility.yml
source_heading: Eligibility
source_page: https://valley.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Valley National Bank\naid: valley-national\nurl: https://valley.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site and the services described on the Site are intended for adult individuals only.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Valley does not target children under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/valley-national/eligibility/valley-national-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Valley National Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Regional Bank
- Commercial Banking
- Open Finance
---
