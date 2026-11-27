---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are 13 years old or older. If you are between the ages of 13 and 18, you represent that your legal guardian has reviewed and agreed to the Terms.
    type: individual
  minimum_age:
    text: You represent that you are 13 years old or older. If you are between the ages of 13 and 18, you represent that your legal guardian has reviewed and agreed to the Terms.
    value: '13'
  restricted_uses:
  - summary: No offensive, harassing or unlawful use
    text: You agree that your use of the Service shall be for lawful purposes and that you will comply with the usage rules.
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
name: 6 Waves
provenance_date: '2026-11-09'
provider_name: 6 Waves
provider_slug: 6-waves
slug: 6-waves-eligibility
source_date: '2026-11-09'
source_filename: 6-waves-eligibility.yml
source_heading: Eligibility
source_page: https://www.6waves.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 6 Waves\naid: 6-waves\nurl: https://www.6waves.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are 13 years old or older. If you are between the ages of 13 and 18, you represent\n    that your legal guardian has reviewed and agreed to the Terms.\nrestricted_uses:\n- summary: No offensive, harassing or unlawful use\n  text: You agree that your use of the Service shall be for lawful purposes and that you will comply with the usage\n    rules.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent that you are 13 years old or older. If you are between the ages of 13 and 18, you represent\n    that your legal guardian has reviewed and agreed to the Terms.\n"
source_yaml_url: https://artifacts.apis.io/6-waves/eligibility/6-waves-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 6 Waves's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Games
- Mobile Games
- Game Publishing
- Gaming
- Entertainment
---
