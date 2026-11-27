---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled from offices and facilities within the United States. ULAC makes no representation that content or materials on this Site are appropriate or available for use in other jurisdictions.
  minimum_age:
    text: ULAC requires that Site users must be at least eighteen (18) years of age, which is the legal age to enter into binding agreements in most jurisdictions.
    value: '18'
  restricted_uses:
  - summary: Prohibited actions list
    text: 'You agree not to: (a) decompile, reverse engineer, disassemble, modify, or create derivative works based upon the Site or any part thereof'
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
name: Stance
provenance_date: '2026-11-10'
provider_name: Stance
provider_slug: stance
slug: stance-eligibility
source_date: '2026-11-10'
source_filename: stance-eligibility.yml
source_heading: Eligibility
source_page: https://www.stance.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stance\naid: stance\nurl: https://www.stance.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled from offices and facilities within the United States. ULAC makes no representation\n    that content or materials on this Site are appropriate or available for use in other jurisdictions.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited actions list\n  text: 'You agree not to: (a) decompile, reverse engineer, disassemble, modify, or create derivative works based\n    upon the Site or any part thereof'\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: ULAC requires that Site users must be at least eighteen (18) years of age, which is the legal age to enter\n    into binding agreements in most jurisdictions.\n"
source_yaml_url: https://artifacts.apis.io/stance/eligibility/stance-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Stance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Apparel
- Retail
- E-Commerce
- Socks
- Direct to Consumer
- Shopify
---
