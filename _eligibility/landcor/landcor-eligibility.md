---
api_specs:
- filename: landcor-avm-summary-api-openapi.yml
  format: yaml
  label: Landcor Data AVM Summary API
  slug: landcor-avm-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landcor/openapi/landcor-avm-summary-api-openapi.yml
- filename: landcor-comparables-api-openapi.yml
  format: yaml
  label: Landcor Data Comparables API
  slug: landcor-comparables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landcor/openapi/landcor-comparables-api-openapi.yml
- filename: landcor-health-api-openapi.yml
  format: yaml
  label: Landcor Data Health API
  slug: landcor-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landcor/openapi/landcor-health-api-openapi.yml
- filename: landcor-property-api-openapi.yml
  format: yaml
  label: Landcor Data Property API
  slug: landcor-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landcor/openapi/landcor-property-api-openapi.yml
- filename: landcor-valuation-api-openapi.yml
  format: yaml
  label: Landcor Data Valuation API
  slug: landcor-valuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landcor/openapi/landcor-valuation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: provides unparalleled real estate data and analytics across British Columbia.
  entity_types:
  - text: allows your organization to use Landcor products and services in certain ways
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Solicitation or mailing use of data
    text: it shall not be used nor made available to obtain addresses for solicitation or mailing purposes of any kind
  - summary: Harassment of members of the public
    text: it shall not be used in any way to harass members of the public
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
name: Landcor Data
provenance_date: '2026-11-09'
provider_name: Landcor Data
provider_slug: landcor
slug: landcor-eligibility
source_date: '2026-11-09'
source_filename: landcor-eligibility.yml
source_heading: Eligibility
source_page: https://www.landcor.com/acceptable-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Landcor Data\naid: landcor\nurl: https://www.landcor.com/acceptable-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: provides unparalleled real estate data and analytics across British Columbia.\nentity_types:\n- type: business\n  text: allows your organization to use Landcor products and services in certain ways\nrestricted_uses:\n- summary: Solicitation or mailing use of data\n  text: it shall not be used nor made available to obtain addresses for solicitation or mailing purposes of any\n    kind\n- summary: Harassment of members of the public\n  text: it shall not be used\
  \ in any way to harass members of the public\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/landcor/eligibility/landcor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Landcor Data's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Canada
- Valuation
- AVM
- Property Records
- Title
- Land Registry
- Mortgage
- PropTech
- Property Data
---
