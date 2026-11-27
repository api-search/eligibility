---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a jurisdiction in which it is illegal for you to use the Platform.
  entity_types:
  - text: If you are a natural person, you are at least 18 years old, of sound mind and capable of taking responsibility for your own actions
    type: individual
  - text: If you enter into the Agreement as an authorised representative of a partnership, company or other non-individual entity, you warrant that you are duly authorised to act on its behalf.
    type: business
  minimum_age:
    text: If you are a natural person, you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No credit card investments for retail clients
    text: Retail Clients are not permitted to use credit cards to make investments through the Platform.
  - summary: No joint account holders
    text: We do not accept joint account holders.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: As part of our customer due diligence process, you will be asked to provide information and documentation so that Smart Crowd can verify your identity, address, source of funds, source of wealth and other relevant information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Smart Crowd
provenance_date: '2026-11-10'
provider_name: Smart Crowd
provider_slug: smart-crowd
slug: smart-crowd-eligibility
source_date: '2026-11-10'
source_filename: smart-crowd-eligibility.yml
source_heading: Eligibility
source_page: https://www.smartcrowd.ae/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Smart Crowd\naid: smart-crowd\nurl: https://www.smartcrowd.ae/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a jurisdiction in which it is illegal for you to use the Platform.\nentity_types:\n- type: individual\n  text: If you are a natural person, you are at least 18 years old, of sound mind and capable of taking responsibility\n    for your own actions\n- type: business\n  text: If you enter into the Agreement as an authorised representative of a partnership, company or other non-individual\n    entity, you warrant that\
  \ you are duly authorised to act on its behalf.\nrestricted_uses:\n- summary: No credit card investments for retail clients\n  text: Retail Clients are not permitted to use credit cards to make investments through the Platform.\n- summary: No joint account holders\n  text: We do not accept joint account holders.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: As part of our customer due diligence process, you will be asked to provide information and documentation\n    so that Smart Crowd can verify your identity, address, source of funds, source of wealth and other relevant\n    information.\nminimum_age:\n  value: '18'\n  text: If you are a natural person, you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/smart-crowd/eligibility/smart-crowd-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Smart Crowd's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Investing
- Crowdfunding
- Fintech
- PropTech
- Dubai
- MENA
---
