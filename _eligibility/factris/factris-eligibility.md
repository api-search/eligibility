---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Voor mkb-bedrijven in heel Europa
  entity_types:
  - text: Factoring voor mkb-bedrijven die vooruit willen.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Factris
provenance_date: '2026-11-09'
provider_name: Factris
provider_slug: factris
slug: factris-eligibility
source_date: '2026-11-09'
source_filename: factris-eligibility.yml
source_heading: Eligibility
source_page: https://www.factris.com/nl/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Factris\naid: factris\nurl: https://www.factris.com/nl/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Voor mkb-bedrijven in heel Europa\nentity_types:\n- type: business\n  text: Factoring voor mkb-bedrijven die vooruit willen.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/factris/eligibility/factris-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Factris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Factoring
- Invoice Financing
- Working Capital
- SME Finance
- Debtor Management
- Credit Insurance
- Europe
---
