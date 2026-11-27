---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    value: null
  restricted_uses:
  - summary: Unlawful or malicious purposes
    text: You may access and use the Services for lawful purposes only.
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
name: Notti
provenance_date: '2026-11-10'
provider_name: Notti
provider_slug: notti
slug: notti-eligibility
source_date: '2026-11-10'
source_filename: notti-eligibility.yml
source_heading: Eligibility
source_page: https://nottipetfood.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Notti\naid: notti\nurl: https://nottipetfood.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Unlawful or malicious purposes\n  text: You may access and use the Services for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By agreeing to these Terms\
  \ of Service, you represent that you are at least the age of majority in your state\n    or province of residence\n"
source_yaml_url: https://artifacts.apis.io/notti/eligibility/notti-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Notti's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pet Food
- Pet Nutrition
- Consumer Packaged Goods
- Direct to Consumer
- E-Commerce
- Pets
- Malaysia
---
