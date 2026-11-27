---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Although this Site may be accessible worldwide, we make no representation that materials on this Site are appropriate or available for use in locations outside the United States.
  entity_types:
  - text: if you are acting on behalf of a company or entity, that you are duly authorized to bind such entity.
    type: business
  minimum_age:
    text: You may not accept this Agreement or access the Services if you are not at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You are only entitled to access and use the Sites and Services for lawful purposes.
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
name: Arivalbank
provenance_date: '2026-11-09'
provider_name: Arivalbank
provider_slug: arivalbank
slug: arivalbank-eligibility
source_date: '2026-11-09'
source_filename: arivalbank-eligibility.yml
source_heading: Eligibility
source_page: https://arival.com/document/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arivalbank\naid: arivalbank\nurl: https://arival.com/document/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Although this Site may be accessible worldwide, we make no representation that materials on this Site are\n    appropriate or available for use in locations outside the United States.\nentity_types:\n- type: business\n  text: if you are acting on behalf of a company or entity, that you are duly authorized to bind such entity.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You are only entitled to access and use the Sites and Services for lawful purposes.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not accept this Agreement or access the Services if you are not at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/arivalbank/eligibility/arivalbank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arivalbank's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Banking
- Digital Banking
- Global Payments
- Stablecoins
---
