---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself or the business you represent.
    type: individual
  - text: on behalf of yourself or the business you represent
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
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
name: BotPhone
provenance_date: '2026-11-09'
provider_name: BotPhone
provider_slug: botphone-tel
slug: botphone-tel-eligibility
source_date: '2026-11-09'
source_filename: botphone-tel-eligibility.yml
source_heading: Eligibility
source_page: https://www.botphone.tel/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BotPhone\naid: botphone-tel\nurl: https://www.botphone.tel/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself\n    or the business you represent.\n- type: business\n  text: on behalf of yourself or the business you represent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/botphone-tel/eligibility/botphone-tel-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from BotPhone's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Telephony
- Receptionist
- Software-as-a-Service
- BotPhone
---
