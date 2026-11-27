---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - IT
    - FR
    text: 'Casavo in Europe: Italy, France (footer). Doris platform available only for agents in Milano, Turin, Florence, Bologna, Verona, Rome.'
  entity_types:
  - text: Casavo is interested in assessing the purchase of real estate from individuals who have legal capacity, as well as from legal entities.
    type: individual
  minimum_age:
    text: Only persons of legal age can use the Services. The use of the Services by minors is permitted on condition that theirs parents or guardian state and/or express such intention, in accordance with the laws in force.
    value: '18'
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
name: Casavo
provenance_date: '2026-11-09'
provider_name: Casavo
provider_slug: casavo
slug: casavo-eligibility
source_date: '2026-11-09'
source_filename: casavo-eligibility.yml
source_heading: Eligibility
source_page: https://casavo.com/en/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Casavo\naid: casavo\nurl: https://casavo.com/en/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IT\n  - FR\n  excluded: []\n  text: 'Casavo in Europe: Italy, France (footer). Doris platform available only for agents in Milano, Turin, Florence,\n    Bologna, Verona, Rome.'\nentity_types:\n- type: individual\n  text: Casavo is interested in assessing the purchase of real estate from individuals who have legal capacity,\n    as well as from legal entities.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: Only persons of legal age can use the Services. The use of the Services by minors is permitted on condition\n    that theirs parents or guardian state and/or express such intention, in accordance with the laws in force.\n"
source_yaml_url: https://artifacts.apis.io/casavo/eligibility/casavo-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Casavo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Marketplace
- Virtual Tours
- Property Listings
- Italy
- Spain
- France
- Mortgage
---
