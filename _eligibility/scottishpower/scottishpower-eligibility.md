---
api_specs:
- filename: scottishpower-catalog-api-openapi.yml
  format: yaml
  label: ScottishPower Catalog API
  slug: scottishpower-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scottishpower/openapi/scottishpower-catalog-api-openapi.yml
- filename: scottishpower-dataset-api-openapi.yml
  format: yaml
  label: ScottishPower Dataset API
  slug: scottishpower-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scottishpower/openapi/scottishpower-dataset-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: a worldwide, royalty-free, non-sublicensable, non-exclusive, irrevocable licence
  entity_types:
  - text: You means the individual or entity exercising the Licensed Rights under this Licence.
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
name: ScottishPower
provenance_date: '2026-11-10'
provider_name: ScottishPower
provider_slug: scottishpower
slug: scottishpower-eligibility
source_date: '2026-11-10'
source_filename: scottishpower-eligibility.yml
source_heading: Eligibility
source_page: https://spenergynetworks.opendatasoft.com/terms/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ScottishPower\naid: scottishpower\nurl: https://spenergynetworks.opendatasoft.com/terms/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: a worldwide, royalty-free, non-sublicensable, non-exclusive, irrevocable licence\nentity_types:\n- type: other\n  text: You means the individual or entity exercising the Licensed Rights under this Licence.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scottishpower/eligibility/scottishpower-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from ScottishPower's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Energy Retailer
- Smart Metering
- Grid
- Open Data
- Distribution Network Operator
- Renewables
- Energy Markets
---
