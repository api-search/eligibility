---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are a resident of a country embargoed by the United States or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: Any use of or access to the Service by anyone under 18 is strictly prohibited and in violation of this Agreement.
    type: individual
  minimum_age:
    text: Any use of or access to the Service by anyone under 18 is strictly prohibited and in violation of this Agreement.
    value: '18'
  restricted_uses:
  - summary: Embargoed or blocked persons
    text: You may not use the Service if you are a resident of a country embargoed by the United States or are a foreign person or entity blocked or denied by the United States government.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Carrot relies on this information to provide the Service and does not independently verify the information you give us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carrot
provenance_date: '2026-11-09'
provider_name: Carrot
provider_slug: carrot
slug: carrot-eligibility
source_date: '2026-11-09'
source_filename: carrot-eligibility.yml
source_heading: Eligibility
source_page: https://www.get-carrot.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carrot\naid: carrot\nurl: https://www.get-carrot.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are a resident of a country embargoed by the United States or are a foreign\n    person or entity blocked or denied by the United States government.\nentity_types:\n- type: individual\n  text: Any use of or access to the Service by anyone under 18 is strictly prohibited and in violation of this Agreement.\nrestricted_uses:\n- summary: Embargoed or blocked persons\n  text: You may not use the Service if you are\
  \ a resident of a country embargoed by the United States or are a foreign\n    person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Carrot relies on this information to provide the Service and does not independently verify the information\n    you give us.\nminimum_age:\n  value: '18'\n  text: Any use of or access to the Service by anyone under 18 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/carrot/eligibility/carrot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Carrot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Fertility
- Family Building
- Employee Benefits
- Reproductive Health
- Health Plans
- Menopause
---
