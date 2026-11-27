---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years or older to use this Site.
    type: individual
  minimum_age:
    text: You must be 18 years or older to use this Site.
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
name: Prosper Health
provenance_date: '2026-11-10'
provider_name: Prosper Health
provider_slug: prosperhealth
slug: prosperhealth-eligibility
source_date: '2026-11-10'
source_filename: prosperhealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.prosperhealth.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prosper Health\naid: prosperhealth\nurl: https://www.prosperhealth.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years or older to use this Site.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use this Site.\n"
source_yaml_url: https://artifacts.apis.io/prosperhealth/eligibility/prosperhealth-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Prosper Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Mental Health
- Autism
- Neurodiversity
- Diagnostics
- Therapy
---
