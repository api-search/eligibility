---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service helps people outside Japan research, shortlist, and, if they choose, pursue the purchase of Japanese real estate.
  entity_types:
  - text: If you are using the Service on behalf of an organisation, you represent that you have authority to bind that organisation.
    type: other
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
name: Engawa Homes
provenance_date: '2026-11-09'
provider_name: Engawa Homes
provider_slug: engawahomes-com
slug: engawahomes-com-eligibility
source_date: '2026-11-09'
source_filename: engawahomes-com-eligibility.yml
source_heading: Eligibility
source_page: https://engawahomes.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Engawa Homes\naid: engawahomes-com\nurl: https://engawahomes.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service helps people outside Japan research, shortlist, and, if they choose, pursue the purchase of\n    Japanese real estate.\nentity_types:\n- type: other\n  text: If you are using the Service on behalf of an organisation, you represent that you have authority to bind\n    that organisation.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/engawahomes-com/eligibility/engawahomes-com-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Engawa Homes's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Japan
- Property
- Listings
---
