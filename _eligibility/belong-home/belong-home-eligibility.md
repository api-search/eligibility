---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not access or use the Services or accept the Terms if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: you may not access or use the Services or accept the Terms if you are not at least 18 years old.
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
name: Belong Home
provenance_date: '2026-11-09'
provider_name: Belong Home
provider_slug: belong-home
slug: belong-home-eligibility
source_date: '2026-11-09'
source_filename: belong-home-eligibility.yml
source_heading: Eligibility
source_page: https://belonghome.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Belong Home\naid: belong-home\nurl: https://belonghome.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not access or use the Services or accept the Terms if you are not at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Services or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/belong-home/eligibility/belong-home-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Belong Home's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Property Management
- Real Estate
- Rental Marketplace
- PropTech
- Residential
- Homeowners
- Rent
---
