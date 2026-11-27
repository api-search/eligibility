---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users between the ages of 13 and 18 require parental or legal guardian consent to utilize Grand Games' Services.
    type: individual
  minimum_age:
    text: Users between the ages of 13 and 18 require parental or legal guardian consent to utilize Grand Games' Services.
    value: '13'
  restricted_uses:
  - summary: No sales refunds
    text: All sales made through the Services are final, and refunds or exchanges are not provided unless required by law.
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
name: Grand Games
provenance_date: '2026-11-09'
provider_name: Grand Games
provider_slug: grand
slug: grand-eligibility
source_date: '2026-11-09'
source_filename: grand-eligibility.yml
source_heading: Eligibility
source_page: https://grand.gs/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grand Games\naid: grand\nurl: https://grand.gs/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users between the ages of 13 and 18 require parental or legal guardian consent to utilize Grand Games' Services.\nrestricted_uses:\n- summary: No sales refunds\n  text: All sales made through the Services are final, and refunds or exchanges are not provided unless required\n    by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Users between the ages of 13\
  \ and 18 require parental or legal guardian consent to utilize Grand Games' Services.\n"
source_yaml_url: https://artifacts.apis.io/grand/eligibility/grand-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Grand Games's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Game Development
- Mobile Games
- Hybrid-Casual
- Puzzle Games
- Consumer
---
