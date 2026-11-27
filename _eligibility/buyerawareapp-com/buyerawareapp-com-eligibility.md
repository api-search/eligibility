---
api_specs:
- filename: buyerawareapp-com-openapi-generated.yml
  format: yaml
  label: BuyerAware API
  slug: buyerawareapp-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyerawareapp-com/openapi/_ae-authored/buyerawareapp-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Reports must be for a specific used vehicle offered for sale in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Listings you are personally considering
    text: You agree to submit only listings you are personally considering for purchase
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
name: BuyerAware
provenance_date: '2026-11-09'
provider_name: BuyerAware
provider_slug: buyerawareapp-com
slug: buyerawareapp-com-eligibility
source_date: '2026-11-09'
source_filename: buyerawareapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://buyerawareapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuyerAware\naid: buyerawareapp-com\nurl: https://buyerawareapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Reports must be for a specific used vehicle offered for sale in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Listings you are personally considering\n  text: You agree to submit only listings you are personally considering for purchase\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/buyerawareapp-com/eligibility/buyerawareapp-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BuyerAware's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- Used Cars
- Vehicle Inspection
- Pricing
- Data Analytics
---
