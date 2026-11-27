---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You will not permit Direct Users to access or use the Platform in a U.S.-embargoed country (currently Cuba, Iran, North Korea, Sudan, Syria, or Crimea (region of Ukraine))
  entity_types:
  - text: you must be at least 18 years old, or 13 and have the consent of your parent or guardian, to use it.
    type: individual
  - text: the power to enter into a binding contract with us – either for yourself or on behalf of the entity on whose behalf you are using the Platform.
    type: business
  minimum_age:
    text: you must be at least 18 years old, or 13 and have the consent of your parent or guardian, to use it.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aident Loadout
provenance_date: '2026-11-09'
provider_name: Aident Loadout
provider_slug: aident
slug: aident-eligibility
source_date: '2026-11-09'
source_filename: aident-eligibility.yml
source_heading: Eligibility
source_page: https://loadout.aident.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aident Loadout\naid: aident\nurl: https://loadout.aident.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You will not permit Direct Users to access or use the Platform in a U.S.-embargoed country (currently Cuba,\n    Iran, North Korea, Sudan, Syria, or Crimea (region of Ukraine))\nentity_types:\n- type: individual\n  text: you must be at least 18 years old, or 13 and have the consent of your parent or guardian, to use it.\n- type: business\n  text: the power to enter into a binding contract with us – either for yourself or\
  \ on behalf of the entity on whose\n    behalf you are using the Platform.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old, or 13 and have the consent of your parent or guardian, to use it.\n"
source_yaml_url: https://artifacts.apis.io/aident/eligibility/aident-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Aident Loadout's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Integration
- Automation
- Platform
---
