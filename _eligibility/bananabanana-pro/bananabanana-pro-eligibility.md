---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to create an account.
    value: '13'
  restricted_uses:
  - summary: Illegal, harmful or abusive content
    text: Generate illegal, harmful, or abusive content
  - summary: IP-infringing content
    text: Create content that infringes on intellectual property rights of others
  - summary: CSAM
    text: Produce content depicting child sexual abuse material (CSAM)
  - summary: Violence, terrorism or hate speech
    text: Create content promoting violence, terrorism, or hate speech
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
name: BananaBanana
provenance_date: '2026-11-09'
provider_name: BananaBanana
provider_slug: bananabanana-pro
slug: bananabanana-pro-eligibility
source_date: '2026-11-09'
source_filename: bananabanana-pro-eligibility.yml
source_heading: Eligibility
source_page: https://bananabanana.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BananaBanana\naid: bananabanana-pro\nurl: https://bananabanana.pro/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal, harmful or abusive content\n  text: Generate illegal, harmful, or abusive content\n- summary: IP-infringing content\n  text: Create content that infringes on intellectual property rights of others\n- summary: CSAM\n  text: Produce content depicting child sexual abuse material (CSAM)\n- summary: Violence, terrorism or hate speech\n  text: Create content promoting violence, terrorism, or hate speech\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/bananabanana-pro/eligibility/bananabanana-pro-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BananaBanana's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Speech
- Crypto Payments
---
