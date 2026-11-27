---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'For business users: To the fullest extent permitted by law, we exclude all implied warranties and shall not be liable for indirect or consequential losses'
    type: business
  - text: 'For consumers: We do not exclude liability for death or personal injury caused by negligence, fraud, or anything else that cannot be excluded by law.'
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
name: Burbank
provenance_date: '2026-11-09'
provider_name: Burbank
provider_slug: burbank
slug: burbank-eligibility
source_date: '2026-11-09'
source_filename: burbank-eligibility.yml
source_heading: Eligibility
source_page: https://www.burbankdev.co.uk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Burbank\naid: burbank\nurl: https://www.burbankdev.co.uk/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'For business users: To the fullest extent permitted by law, we exclude all implied warranties and shall\n    not be liable for indirect or consequential losses'\n- type: individual\n  text: 'For consumers: We do not exclude liability for death or personal injury caused by negligence, fraud, or\n    anything else that cannot be excluded by law.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/burbank/eligibility/burbank-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Burbank's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Authentication
- Fintech
- Card Present
- SoftPOS
- Fraud Prevention
- Identity Verification
---
