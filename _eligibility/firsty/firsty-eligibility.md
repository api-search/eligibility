---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: As a consumer, you benefit from the mandatory provisions of law of the country in which you are resident.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned residents
    text: 'Firsty reserves the right to restrict or deny App availability and eSIM provisioning based on various factors, including but not limited to: (i) Users who are residents of countries subject to sanctions under European Union (EU) or United Nations (UN) regulations'
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
name: Firsty
provenance_date: '2026-11-09'
provider_name: Firsty
provider_slug: firsty
slug: firsty-eligibility
source_date: '2026-11-09'
source_filename: firsty-eligibility.yml
source_heading: Eligibility
source_page: https://www.firsty.app/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firsty\naid: firsty\nurl: https://www.firsty.app/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: As a consumer, you benefit from the mandatory provisions of law of the country in which you are resident.\nrestricted_uses:\n- summary: Sanctioned residents\n  text: 'Firsty reserves the right to restrict or deny App availability and eSIM provisioning based on various factors,\n    including but not limited to: (i) Users who are residents of countries subject to sanctions under European Union\n    (EU) or United Nations\
  \ (UN) regulations'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firsty/eligibility/firsty-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Firsty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- eSIM
- Mobile
- Connectivity
- Telecommunications
- Travel
- Roaming
- Data
- Consumer
---
