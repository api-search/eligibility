---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The Site is directed to users who are 18 years or older (or otherwise possess legal parental or guardian consent) and reside in or use the Site within Australia.
  entity_types:
  - text: The Site is directed to users who are 18 years or older (or otherwise possess legal parental or guardian consent)
    type: individual
  - source: https://view.com.au/customer-terms-conditions/
    text: If you are an agent then, in relation to properties, you are a licensed real estate agent as defined in section 4 of the Estate Agents Act 1980 (Vic)
    type: business
  - source: https://view.com.au/customer-terms-conditions/
    text: if you are a marketing services provider then you are duly authorised to enter into this Agreement
    type: other
  minimum_age:
    text: The Site is directed to users who are 18 years or older (or otherwise possess legal parental or guardian consent)
    value: '18'
  restricted_uses:
  - summary: AI generation of inappropriate content
    text: to generate (such as through the Site’s AI features) inappropriate content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Where possible, we may request that you provide identification to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: View.com.au
provenance_date: '2026-11-10'
provider_name: View.com.au
provider_slug: view-com-au
slug: view-com-au-eligibility
source_date: '2026-11-10'
source_filename: view-com-au-eligibility.yml
source_heading: Eligibility
source_page: https://view.com.au/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: View.com.au\naid: view-com-au\nurl: https://view.com.au/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://view.com.au/customer-terms-conditions/\n  - https://view.com.au/terms-of-use/\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The Site is directed to users who are 18 years or older (or otherwise possess legal parental or guardian\n    consent) and reside in or use the Site within Australia.\nentity_types:\n- type: individual\n  text: The Site is directed to users who are 18 years or older (or otherwise possess legal parental or guardian\n    consent)\n- type: business\n  text: If\
  \ you are an agent then, in relation to properties, you are a licensed real estate agent as defined in\n    section 4 of the Estate Agents Act 1980 (Vic)\n  source: https://view.com.au/customer-terms-conditions/\n- type: other\n  text: if you are a marketing services provider then you are duly authorised to enter into this Agreement\n  source: https://view.com.au/customer-terms-conditions/\nrestricted_uses:\n- summary: AI generation of inappropriate content\n  text: to generate (such as through the Site’s AI features) inappropriate content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Where possible, we may request that you provide identification to verify your identity.\nminimum_age:\n  value: '18'\n  text: The Site is directed to users who are 18 years or older (or otherwise possess legal parental or guardian\n    consent)\n"
source_yaml_url: https://artifacts.apis.io/view-com-au/eligibility/view-com-au-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from View.com.au's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Australia
- Property Listings
- Property Portal
- PropTech
- Rentals
- Off-Market Property Data
- MCP
- Agent-Native
---
