---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not represent or warrant that the Services are appropriate or available for use in any particular jurisdiction other than the United States.
  entity_types:
  - text: You may not use the Services and you may not accept these Terms if you are not of legal age to form a binding contract with us, which is 18 years of age in most states.
    type: individual
  minimum_age:
    text: which is 18 years of age in most states.
    value: '18'
  restricted_uses:
  - summary: Soliciting minors' data
    text: solicit personal information from anyone under the age of 18
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
name: Pasito
provenance_date: '2026-11-10'
provider_name: Pasito
provider_slug: pasito
slug: pasito-eligibility
source_date: '2026-11-10'
source_filename: pasito-eligibility.yml
source_heading: Eligibility
source_page: https://pasito.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pasito\naid: pasito\nurl: https://pasito.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not represent or warrant that the Services are appropriate or available for use in any particular\n    jurisdiction other than the United States.\nentity_types:\n- type: individual\n  text: You may not use the Services and you may not accept these Terms if you are not of legal age to form a binding\n    contract with us, which is 18 years of age in most states.\nrestricted_uses:\n- summary: Soliciting minors' data\n  text: solicit personal information from anyone under\
  \ the age of 18\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: which is 18 years of age in most states.\n"
source_yaml_url: https://artifacts.apis.io/pasito/eligibility/pasito-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pasito's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Employee Benefits
- Insurance
- Artificial Intelligence
- Insurtech
- Human Resources
- Health
- AI Agents
---
