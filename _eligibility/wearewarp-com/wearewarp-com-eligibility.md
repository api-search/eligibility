---
api_specs:
- filename: wearewarp-com-freight-openapi.json
  format: json
  label: WARP API Documentation Freight API
  slug: warp-api-documentation-freight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wearewarp-com/openapi/_original/wearewarp-com-freight-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Platform license limited to use within the United States.
  entity_types:
  - text: If you are agreeing on behalf of a company, you represent that you are authorized to bind that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hazardous materials disclosure
    text: You are obligated to inform Warp before tendering any shipment that constitutes hazardous materials.
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
name: WARP
provenance_date: '2026-11-10'
provider_name: WARP
provider_slug: wearewarp-com
slug: wearewarp-com-eligibility
source_date: '2026-11-10'
source_filename: wearewarp-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.wearewarp.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WARP\naid: wearewarp-com\nurl: https://www.wearewarp.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Platform license limited to use within the United States.\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company, you represent that you are authorized to bind that company.\nrestricted_uses:\n- summary: Hazardous materials disclosure\n  text: You are obligated to inform Warp before tendering any shipment that constitutes hazardous materials.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wearewarp-com/eligibility/wearewarp-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from WARP's own page on 2026-11-10.
synthetic: false
tags:
- Freight
- LTL
- FTL
- Logistics
- Shipping
- Warehousing
- Supply Chain
---
