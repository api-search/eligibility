---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may only use the Text Messaging Platform as a resident of the United States located in the United States.
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Medical advice
    text: THE SERVICES DO NOT PROVIDE MEDICAL OR HEALTH CARE OR RELATED ADVICE, RECOMMENDATIONS OR SUGGESTIONS.
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
name: Wizard
provenance_date: '2026-11-10'
provider_name: Wizard
provider_slug: wizard
slug: wizard-eligibility
source_date: '2026-11-10'
source_filename: wizard-eligibility.yml
source_heading: Eligibility
source_page: https://wizard.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wizard\naid: wizard\nurl: https://wizard.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may only use the Text Messaging Platform as a resident of the United States located in the United States.\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\nrestricted_uses:\n- summary: Medical advice\n  text: THE SERVICES DO NOT PROVIDE MEDICAL OR HEALTH CARE OR RELATED ADVICE, RECOMMENDATIONS OR SUGGESTIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/wizard/eligibility/wizard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Wizard's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Shopping
- E-Commerce
- Artificial Intelligence
- Shopping Assistant
- Conversational Commerce
---
