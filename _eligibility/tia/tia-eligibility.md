---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are over the age of eighteen (18);
    type: individual
  minimum_age:
    text: You are over the age of eighteen (18);
    value: '18'
  restricted_uses:
  - summary: Membership transfer
    text: Transfer of your Membership to any other person is strictly prohibited.
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
name: Tia
provenance_date: '2026-11-10'
provider_name: Tia
provider_slug: tia
slug: tia-eligibility
source_date: '2026-11-10'
source_filename: tia-eligibility.yml
source_heading: Eligibility
source_page: https://asktia.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tia\naid: tia\nurl: https://asktia.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are over the age of eighteen (18);\nrestricted_uses:\n- summary: Membership transfer\n  text: Transfer of your Membership to any other person is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are over the age of eighteen (18);\n"
source_yaml_url: https://artifacts.apis.io/tia/eligibility/tia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Women's Health
- Primary Care
- Gynecology
- Telehealth
- Mental Health
---
