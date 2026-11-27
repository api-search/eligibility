---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You have been granted access to use the App by your Organisation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal use
    text: The App, and the card payment function, is not for personal use;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: You will only be able to access certain features and functions of your account once your Organisation has approved access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Conferma
provenance_date: '2026-11-09'
provider_name: Conferma
provider_slug: conferma
slug: conferma-eligibility
source_date: '2026-11-09'
source_filename: conferma-eligibility.yml
source_heading: Eligibility
source_page: https://app.conferma.com/Terms.aspx
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conferma\naid: conferma\nurl: https://app.conferma.com/Terms.aspx\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You have been granted access to use the App by your Organisation\nrestricted_uses:\n- summary: No personal use\n  text: The App, and the card payment function, is not for personal use;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: You will only be able to access certain features and functions of your account once your Organisation has\n    approved access.\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/conferma/eligibility/conferma-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Conferma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Virtual Card
- Fintech
- B2B
---
