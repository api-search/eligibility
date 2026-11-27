---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted commodities
    text: You will not tender any restricted commodities including, but not limited to, hazardous materials and waste
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
name: Drayalliance
provenance_date: '2026-11-09'
provider_name: Drayalliance
provider_slug: drayalliance
slug: drayalliance-eligibility
source_date: '2026-11-09'
source_filename: drayalliance-eligibility.yml
source_heading: Eligibility
source_page: https://www.drayalliance.com/shipper-tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Drayalliance\naid: drayalliance\nurl: https://www.drayalliance.com/shipper-tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Restricted commodities\n  text: You will not tender any restricted commodities including, but not limited to, hazardous materials and waste\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/drayalliance/eligibility/drayalliance-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Drayalliance's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- Drayage
- Supply Chain
- Transportation
---
