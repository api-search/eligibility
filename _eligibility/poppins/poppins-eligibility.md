---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: auprès d’acheteurs non professionnels (le “Client” ou les “Clients”)
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Poppins
provenance_date: '2026-11-10'
provider_name: Poppins
provider_slug: poppins
slug: poppins-eligibility
source_date: '2026-11-10'
source_filename: poppins-eligibility.yml
source_heading: Eligibility
source_page: https://www.poppins.io/nos-cgv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Poppins\naid: poppins\nurl: https://www.poppins.io/nos-cgv\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: auprès d’acheteurs non professionnels (le “Client” ou les “Clients”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/poppins/eligibility/poppins-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Poppins's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Digital Therapeutics
- Medical Devices
- Education
- Dyslexia
- Children
- France
---
