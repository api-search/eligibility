---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Currently it's not permitted to buy our products when you're outside the UK.
  entity_types:
  - text: You can only use our app to purchase motor insurance for yourself.
    type: individual
  minimum_age:
    text: Use our services if you are not able to form legally binding contracts or drive (for example, if you are a minor)
    value: null
  restricted_uses:
  - summary: Users must be able to contract and drive
    text: Use our services if you are not able to form legally binding contracts or drive (for example, if you are a minor)
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
name: Cuvva
provenance_date: '2026-11-09'
provider_name: Cuvva
provider_slug: cuvva
slug: cuvva-eligibility
source_date: '2026-11-09'
source_filename: cuvva-eligibility.yml
source_heading: Eligibility
source_page: https://support.cuvva.com/en/articles/5907873-cuvva-s-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuvva\naid: cuvva\nurl: https://support.cuvva.com/en/articles/5907873-cuvva-s-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Currently it's not permitted to buy our products when you're outside the UK.\nentity_types:\n- type: individual\n  text: You can only use our app to purchase motor insurance for yourself.\nrestricted_uses:\n- summary: Users must be able to contract and drive\n  text: Use our services if you are not able to form legally binding contracts or drive (for example, if you are\n    a minor)\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: Use our services if you are not able to form legally binding contracts or drive (for example, if you are\n    a minor)\n"
source_yaml_url: https://artifacts.apis.io/cuvva/eligibility/cuvva-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cuvva's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Car Insurance
- Financial Services
- Mobile
- OAuth
- United Kingdom
- Authentication
---
