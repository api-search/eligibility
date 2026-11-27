---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Target Circle may be used only for personal, family and household purposes.
    type: individual
  minimum_age:
    text: The Site is intended for use by individuals 13 years of age or older. If you are under 18, you may use this Site only with involvement of a parent or guardian.
    value: '13'
  restricted_uses:
  - summary: No business use of Target Circle
    text: You agree that you will not use Target Circle for business or commercial purposes.
  - summary: No reselling via Target Circle
    text: Resellers are expressly excluded from Target Circle.
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
name: Target
provenance_date: '2026-11-10'
provider_name: Target
provider_slug: target
slug: target-eligibility
source_date: '2026-11-10'
source_filename: target-eligibility.yml
source_heading: Eligibility
source_page: https://www.target.com/c/terms-conditions/-/N-4sr7l
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Target\naid: target\nurl: https://www.target.com/c/terms-conditions/-/N-4sr7l\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Target Circle may be used only for personal, family and household purposes.\nrestricted_uses:\n- summary: No business use of Target Circle\n  text: You agree that you will not use Target Circle for business or commercial purposes.\n- summary: No reselling via Target Circle\n  text: Resellers are expressly excluded from Target Circle.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is intended for use by individuals 13 years of age or older. If you are under 18, you may use this\n    Site only with involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/target/eligibility/target-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Target's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 100
- E-Commerce
- Retail
- Product
- Inventory
- Stores
- Order
---
