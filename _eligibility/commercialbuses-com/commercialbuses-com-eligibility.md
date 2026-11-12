---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Search buses from dealers across the U.S.
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
name: CommercialBuses
provenance_date: '2026-11-09'
provider_name: CommercialBuses
provider_slug: commercialbuses-com
slug: commercialbuses-com-eligibility
source_date: '2026-11-09'
source_filename: commercialbuses-com-eligibility.yml
source_heading: Eligibility
source_page: https://commercialbuses.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CommercialBuses\naid: commercialbuses-com\nurl: https://commercialbuses.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Search buses from dealers across the U.S.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commercialbuses-com/eligibility/commercialbuses-com-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from CommercialBuses's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commercial Buses
- Vehicle Marketplace
- Transportation
- Dealers
- School Buses
- MCP
---
