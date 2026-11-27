---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity identified as Customer in the applicable Order Form
    type: business
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
name: PreVeil
provenance_date: '2026-11-10'
provider_name: PreVeil
provider_slug: preveil
slug: preveil-eligibility
source_date: '2026-11-10'
source_filename: preveil-eligibility.yml
source_heading: Eligibility
source_page: https://www.preveil.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PreVeil\naid: preveil\nurl: https://www.preveil.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity identified as Customer in the applicable Order Form\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/preveil/eligibility/preveil-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from PreVeil's own page on 2026-11-10.
synthetic: false
tags:
- Encryption
- End-to-End Encryption
- Email
- File Sharing
- Security
- Compliance
- CMMC
- ITAR
- CUI
- Defense
- Cybersecurity
- Data Protection
---
