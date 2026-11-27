---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Pindrop Security
provenance_date: '2026-11-10'
provider_name: Pindrop Security
provider_slug: pindropsecurity-com
slug: pindropsecurity-com-eligibility
source_date: '2026-11-10'
source_filename: pindropsecurity-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.pindrop.com/legal/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pindrop Security\naid: pindropsecurity-com\nurl: https://www.pindrop.com/legal/website-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available\
  \ to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/pindropsecurity-com/eligibility/pindropsecurity-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pindrop Security's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Fraud Prevention
- Deepfake Defense
- Voice Authentication
- Enterprise
---
