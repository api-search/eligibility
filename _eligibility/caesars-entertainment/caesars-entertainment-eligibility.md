---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Must be 21 years of age or older to enroll in Program and present valid, government-issued photo identification for proof of age
    type: individual
  minimum_age:
    text: Must be 21 years of age or older to enroll in Program
    value: '21'
  restricted_uses:
  - summary: Excluded individuals
    text: Individuals who are excluded from casino, racino, and off track betting (OTB) facilities and online gambling products, through a government program, their own request, at the sole discretion of Caesars, or through any other means, are not eligible to participate in the Program.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Caesars reserves the right to deny anyone application for membership or terminate anyone’s membership in the Program at any time in its sole discretion without recourse.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Caesars Entertainment
provenance_date: '2026-11-09'
provider_name: Caesars Entertainment
provider_slug: caesars-entertainment
slug: caesars-entertainment-eligibility
source_date: '2026-11-09'
source_filename: caesars-entertainment-eligibility.yml
source_heading: Eligibility
source_page: https://www.caesars.com/myrewards/caesars-rewards-rules-regs
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caesars Entertainment\naid: caesars-entertainment\nurl: https://www.caesars.com/myrewards/caesars-rewards-rules-regs\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Must be 21 years of age or older to enroll in Program and present valid, government-issued photo identification\n    for proof of age\nrestricted_uses:\n- summary: Excluded individuals\n  text: Individuals who are excluded from casino, racino, and off track betting (OTB) facilities and online gambling\n    products, through a government program, their own request, at the\
  \ sole discretion of Caesars, or through any\n    other means, are not eligible to participate in the Program.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Caesars reserves the right to deny anyone application for membership or terminate anyone’s membership in\n    the Program at any time in its sole discretion without recourse.\nminimum_age:\n  value: '21'\n  text: Must be 21 years of age or older to enroll in Program\n"
source_yaml_url: https://artifacts.apis.io/caesars-entertainment/eligibility/caesars-entertainment-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Caesars Entertainment's own page on 2026-11-09.
synthetic: false
tags:
- Hospitality
- Gaming
- Casinos
- Resorts
- Entertainment
- Loyalty
- Company
- Fortune 500
---
