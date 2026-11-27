---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply to individuals and to businesses.
    type: individual
  - text: These Terms apply to individuals and to businesses.
    type: business
  minimum_age:
    text: You must be 18 or older to use Bitcall.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You only need an email address to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitcall
provenance_date: '2026-11-09'
provider_name: Bitcall
provider_slug: bitcall
slug: bitcall-eligibility
source_date: '2026-11-09'
source_filename: bitcall-eligibility.yml
source_heading: Eligibility
source_page: https://bitcall.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitcall\naid: bitcall\nurl: https://bitcall.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms apply to individuals and to businesses.\n- type: business\n  text: These Terms apply to individuals and to businesses.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You only need an email address to create an account.\nminimum_age:\n  value: '18'\n  text: You must be 18 or older to use Bitcall.\n"
source_yaml_url: https://artifacts.apis.io/bitcall/eligibility/bitcall-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bitcall's own page on 2026-11-09.
synthetic: false
tags:
- Telecommunications
- VoIP
- SMS
- eSIM
---
