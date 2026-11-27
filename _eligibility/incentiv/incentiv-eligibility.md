---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent, warrant and covenant that (a) you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  minimum_age:
    text: We do not knowingly collector solicit personally identifiable information from children under 16 years of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the Services
    value: '16'
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
name: Incentiv
provenance_date: '2026-11-09'
provider_name: Incentiv
provider_slug: incentiv
slug: incentiv-eligibility
source_date: '2026-11-09'
source_filename: incentiv-eligibility.yml
source_heading: Eligibility
source_page: https://www.incentiv.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Incentiv\naid: incentiv\nurl: https://www.incentiv.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent, warrant and covenant\n    that (a) you are authorized to agree to these Terms on that organization’s or entity’s behalf\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collector solicit personally identifiable information from children under 16 years of\n    age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the Services\n"
source_yaml_url: https://artifacts.apis.io/incentiv/eligibility/incentiv-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Incentiv's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compensation
- Private Equity
- Talent Management
- Software
---
