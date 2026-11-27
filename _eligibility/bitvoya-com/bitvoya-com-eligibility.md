---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the account established by the Company for You is for Your personal use only
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use only
    text: the account established by the Company for You is for Your personal use only
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: users who have registered with Bitvoya and completed real-name authentication
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitvoya
provenance_date: '2026-11-09'
provider_name: Bitvoya
provider_slug: bitvoya-com
slug: bitvoya-com-eligibility
source_date: '2026-11-09'
source_filename: bitvoya-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.bitvoya.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitvoya\naid: bitvoya-com\nurl: https://www.bitvoya.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the account established by the Company for You is for Your personal use only\nrestricted_uses:\n- summary: Personal use only\n  text: the account established by the Company for You is for Your personal use only\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: users who have registered with Bitvoya and completed real-name authentication\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bitvoya-com/eligibility/bitvoya-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Bitvoya's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Hospitality
- Luxury
- Curated
- Booking
---
