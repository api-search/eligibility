---
api_specs:
- filename: 0bull-net-openapi-generated.yml
  format: yaml
  label: 0bull API
  slug: 0bull-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0bull-net/openapi/_ae-authored/0bull-net-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, or are a national or resident of, a country or territory that is subject to comprehensive sanctions
  entity_types:
  - text: 'The Service is designed for business use: agencies, creators operating as a business, and companies that run social media accounts at scale.'
    type: business
  - text: '"Consumer" means an individual who uses the Service for purposes wholly or mainly outside their trade, business, craft or profession.'
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher, to create an account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or platform-breaching use
    text: If you use the Service for anything illegal, or in any way that breaks the terms of TikTok, Instagram, YouTube or any other third-party platform, we will terminate your account and the affected Phones immediately, without notice and without a refund.
  - summary: Sanctioned persons or territories
    text: You agree not to use the Service to provide anything to, or for the benefit of, a sanctioned person or territory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may decline or delay an assignment at our discretion, for example when we cannot verify your identity, your payment method, or the intended use of the Phone.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 0bull
provenance_date: '2026-11-09'
provider_name: 0bull
provider_slug: 0bull-net
slug: 0bull-net-eligibility
source_date: '2026-11-09'
source_filename: 0bull-net-eligibility.yml
source_heading: Eligibility
source_page: https://0bull.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 0bull\naid: 0bull-net\nurl: https://0bull.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, or are a national or resident of, a country or territory\n    that is subject to comprehensive sanctions\nentity_types:\n- type: business\n  text: 'The Service is designed for business use: agencies, creators operating as a business, and companies that\n    run social media accounts at scale.'\n- type: individual\n  text: '\"Consumer\" means an individual who uses the Service for purposes wholly or mainly outside their trade,\n   \
  \ business, craft or profession.'\nrestricted_uses:\n- summary: Illegal or platform-breaching use\n  text: If you use the Service for anything illegal, or in any way that breaks the terms of TikTok, Instagram, YouTube\n    or any other third-party platform, we will terminate your account and the affected Phones immediately, without\n    notice and without a refund.\n- summary: Sanctioned persons or territories\n  text: You agree not to use the Service to provide anything to, or for the benefit of, a sanctioned person or territory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may decline or delay an assignment at our discretion, for example when we cannot verify your identity,\n    your payment method, or the intended use of the Phone.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher, to create an\n    account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/0bull-net/eligibility/0bull-net-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from 0bull's own page on 2026-11-09.
synthetic: false
tags:
- iPhone
- Rentals
- Social Media
- Automation
---
