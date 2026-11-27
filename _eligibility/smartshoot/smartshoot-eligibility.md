---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  minimum_age:
    text: you are over the age of 13, as the SmartShoot® Website is not intended for children under 13
    value: '13'
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
name: SmartShoot
provenance_date: '2026-11-10'
provider_name: SmartShoot
provider_slug: smartshoot
slug: smartshoot-eligibility
source_date: '2026-11-10'
source_filename: smartshoot-eligibility.yml
source_heading: Eligibility
source_page: https://www.smartshoot.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmartShoot\naid: smartshoot\nurl: https://www.smartshoot.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental\n    or guardian consent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are over the age of 13, as the SmartShoot® Website is not intended for children under 13\n"
source_yaml_url: https://artifacts.apis.io/smartshoot/eligibility/smartshoot-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from SmartShoot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Photography
- Video Production
- Creative Services
- Marketplace
- Content Production
- Enterprise
---
