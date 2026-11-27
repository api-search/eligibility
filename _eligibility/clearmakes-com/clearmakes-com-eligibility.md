---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When creating an account, you confirm that you are at least 18 years old and that your information is accurate and up to date.
    type: individual
  minimum_age:
    text: When creating an account, you confirm that you are at least 18 years old
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
name: clearmakes-com
provenance_date: '2026-11-09'
provider_name: clearmakes-com
provider_slug: clearmakes-com
slug: clearmakes-com-eligibility
source_date: '2026-11-09'
source_filename: clearmakes-com-eligibility.yml
source_heading: Eligibility
source_page: https://clearmakes.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: clearmakes-com\naid: clearmakes-com\nurl: https://clearmakes.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: When creating an account, you confirm that you are at least 18 years old and that your information is accurate\n    and up to date.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When creating an account, you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/clearmakes-com/eligibility/clearmakes-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from clearmakes-com's own page on 2026-11-09.
synthetic: false
tags:
- Customer Service
- Remote Teams
---
