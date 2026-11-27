---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only to at least 16 years old individuals. The only exception to the age limit is for Appy Pie Agents which requires you to be at least 18 years old.
    type: individual
  minimum_age:
    text: The Service is available only to at least 16 years old individuals.
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
name: Appy Pie LLP
provenance_date: '2026-11-09'
provider_name: Appy Pie LLP
provider_slug: appypie
slug: appypie-eligibility
source_date: '2026-11-09'
source_filename: appypie-eligibility.yml
source_heading: Eligibility
source_page: https://www.appypie.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appy Pie LLP\naid: appypie\nurl: https://www.appypie.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only to at least 16 years old individuals. The only exception to the age limit\n    is for Appy Pie Agents which requires you to be at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Service is available only to at least 16 years old individuals.\n"
source_yaml_url: https://artifacts.apis.io/appypie/eligibility/appypie-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Appy Pie LLP's own page on 2026-11-09.
synthetic: false
tags:
- No-Code
- Artificial Intelligence
- App Builder
- Mobile App
- Web App
---
