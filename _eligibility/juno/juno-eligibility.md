---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Services are intended for business and professional use within the property technology sector and related fields.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use our Services.
    value: '18'
  restricted_uses:
  - summary: Personal or unauthorized commercial use
    text: Personal or unauthorized commercial use is prohibited.
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
name: Juno
provenance_date: '2026-11-09'
provider_name: Juno
provider_slug: juno
slug: juno-eligibility
source_date: '2026-11-09'
source_filename: juno-eligibility.yml
source_heading: Eligibility
source_page: https://juno.co/service-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juno\naid: juno\nurl: https://juno.co/service-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Services are intended for business and professional use within the property technology sector and related\n    fields.\nrestricted_uses:\n- summary: Personal or unauthorized commercial use\n  text: Personal or unauthorized commercial use is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding\
  \ contract to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/juno/eligibility/juno-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Juno's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Construction Management
- Real Estate
- Multifamily
- Prefabrication
- Modular Construction
- Mass Timber
- PropTech
- Owner's Representation
- Sustainability
- Professional Services
---
