---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"User," "you," "your" refers to any individual who accesses or uses the Service'
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Commercial purposes without authorization
    text: Use the Service for commercial purposes without authorization
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
name: doxa-app
provenance_date: '2026-11-09'
provider_name: doxa-app
provider_slug: doxa-app
slug: doxa-app-eligibility
source_date: '2026-11-09'
source_filename: doxa-app-eligibility.yml
source_heading: Eligibility
source_page: https://doxa.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: doxa-app\naid: doxa-app\nurl: https://doxa.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"User,\" \"you,\" \"your\" refers to any individual who accesses or uses the Service'\nrestricted_uses:\n- summary: Commercial purposes without authorization\n  text: Use the Service for commercial purposes without authorization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/doxa-app/eligibility/doxa-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from doxa-app's own page on 2026-11-09.
synthetic: false
tags:
- Faith
- Community
- Mobile App
- BibleResources
- Prophetic
---
