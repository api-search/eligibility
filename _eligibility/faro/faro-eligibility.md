---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: this Site may not be appropriate or available for use in other locations
  entity_types:
  - text: as an individual accessing and using this website or any other website we own or operate
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You are permitted to access and use the Site only for your personal, non-commercial use
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
name: Faro
provenance_date: '2026-11-09'
provider_name: Faro
provider_slug: faro
slug: faro-eligibility
source_date: '2026-11-09'
source_filename: faro-eligibility.yml
source_heading: Eligibility
source_page: https://faro.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Faro\naid: faro\nurl: https://faro.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: this Site may not be appropriate or available for use in other locations\nentity_types:\n- type: individual\n  text: as an individual accessing and using this website or any other website we own or operate\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You are permitted to access and use the Site only for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/faro/eligibility/faro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Faro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Clinical Development
- Clinical Trials
- Healthcare
- Life Sciences
- Artificial Intelligence
- Biopharma
- Protocol Authoring
- Workflow Automation
---
