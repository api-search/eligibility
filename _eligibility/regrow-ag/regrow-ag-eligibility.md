---
api_specs:
- filename: regrow-ag-ogc-api-general-api-openapi.yml
  format: yaml
  label: Regrow OGC API - General API
  slug: regrow-ag-ogc-api-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-ogc-api-general-api-openapi.yml
- filename: regrow-ag-ogc-api-processes-api-openapi.yml
  format: yaml
  label: Regrow OGC API - Processes API
  slug: regrow-ag-ogc-api-processes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-ogc-api-processes-api-openapi.yml
- filename: regrow-ag-v0-explore-api-intervention-api-openapi.yml
  format: yaml
  label: Regrow V0 Explore API - Intervention API
  slug: regrow-ag-v0-explore-api-intervention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v0-explore-api-intervention-api-openapi.yml
- filename: regrow-ag-v0-measure-api-intervention-api-openapi.yml
  format: yaml
  label: Regrow V0 Measure API - Intervention API
  slug: regrow-ag-v0-measure-api-intervention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v0-measure-api-intervention-api-openapi.yml
- filename: regrow-ag-v0-measure-api-inventory-api-openapi.yml
  format: yaml
  label: Regrow V0 Measure API - Inventory API
  slug: regrow-ag-v0-measure-api-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v0-measure-api-inventory-api-openapi.yml
- filename: regrow-ag-v1-measure-api-enteric-api-openapi.yml
  format: yaml
  label: Regrow V1 Measure API - Enteric API
  slug: regrow-ag-v1-measure-api-enteric-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v1-measure-api-enteric-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the account holder that registers for an account to access and use Regrow online services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use prohibited by law
    text: use the Service in any manner prohibited by law
  - summary: Regulated data restricted
    text: You will not upload any data or information that is subject to specific regulatory requirements or restricted handling
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
name: Regrow
provenance_date: '2026-11-10'
provider_name: Regrow
provider_slug: regrow-ag
slug: regrow-ag-eligibility
source_date: '2026-11-10'
source_filename: regrow-ag-eligibility.yml
source_heading: Eligibility
source_page: https://www.regrow.ag/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Regrow\naid: regrow-ag\nurl: https://www.regrow.ag/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the account holder that registers for an account to access and use Regrow online services\nrestricted_uses:\n- summary: Use prohibited by law\n  text: use the Service in any manner prohibited by law\n- summary: Regulated data restricted\n  text: You will not upload any data or information that is subject to specific regulatory requirements or restricted\n    handling\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/regrow-ag/eligibility/regrow-ag-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Regrow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agriculture
- Sustainability
- Greenhouse Gas Emissions
- Carbon
- Regenerative Agriculture
- Remote Sensing
- Climate
---
