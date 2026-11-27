---
api_specs:
- filename: climate-fieldview-fields-api-openapi.yml
  format: yaml
  label: Climate FieldView Fields API
  slug: climate-fieldview-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-fields-api-openapi.yml
- filename: climate-fieldview-boundaries-api-openapi.yml
  format: yaml
  label: Climate FieldView Boundaries API
  slug: climate-fieldview-boundaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-boundaries-api-openapi.yml
- filename: climate-fieldview-exports-api-openapi.yml
  format: yaml
  label: Climate FieldView Exports API
  slug: climate-fieldview-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-exports-api-openapi.yml
- filename: climate-fieldview-farmorganizations-api-openapi.yml
  format: yaml
  label: Climate FieldView Farm Organizations API
  slug: climate-fieldview-farmorganizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-farmorganizations-api-openapi.yml
- filename: climate-fieldview-layers-api-openapi.yml
  format: yaml
  label: Climate FieldView Layers API
  slug: climate-fieldview-layers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-layers-api-openapi.yml
- filename: climate-fieldview-operations-api-openapi.yml
  format: yaml
  label: Climate FieldView Operations API
  slug: climate-fieldview-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-operations-api-openapi.yml
- filename: climate-fieldview-resourceowners-api-openapi.yml
  format: yaml
  label: Climate FieldView Resource Owners API
  slug: climate-fieldview-resourceowners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-resourceowners-api-openapi.yml
- filename: climate-fieldview-uploads-api-openapi.yml
  format: yaml
  label: Climate FieldView Uploads API
  slug: climate-fieldview-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/climate-fieldview/openapi/climate-fieldview-uploads-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - AR
    - BR
    - MX
    text: 'Service Territory: United States of America, Canada, Argentina, Brazil, Mexico. Licensed Affiliates are listed per territory; FieldView Services may not be available in all Service Territories.'
  entity_types:
  - text: FIELDVIEW SERVICES ARE INTENDED FOR BUSINESS USE ONLY. THIS AGREEMENT ESTABLISHES A BUSINESS-TO-BUSINESS RELATIONSHIP BETWEEN YOU AND US.
    type: business
  minimum_age:
    text: By downloading, installing, activating, or otherwise using the FieldView Services, You represent and warrant that You are at least 18 years old or the age of majority under the laws of where You reside
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
name: Climate FieldView
provenance_date: '2026-11-09'
provider_name: Climate FieldView
provider_slug: climate-fieldview
slug: climate-fieldview-eligibility
source_date: '2026-11-09'
source_filename: climate-fieldview-eligibility.yml
source_heading: Eligibility
source_page: https://climate.com/en-us/legal/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Climate FieldView\naid: climate-fieldview\nurl: https://climate.com/en-us/legal/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  - AR\n  - BR\n  - MX\n  excluded: []\n  text: 'Service Territory: United States of America, Canada, Argentina, Brazil, Mexico. Licensed Affiliates are\n    listed per territory; FieldView Services may not be available in all Service Territories.'\nentity_types:\n- type: business\n  text: FIELDVIEW SERVICES ARE INTENDED FOR BUSINESS USE ONLY. THIS AGREEMENT ESTABLISHES A BUSINESS-TO-BUSINESS\n    RELATIONSHIP BETWEEN YOU AND\
  \ US.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By downloading, installing, activating, or otherwise using the FieldView Services, You represent and warrant\n    that You are at least 18 years old or the age of majority under the laws of where You reside\n"
source_yaml_url: https://artifacts.apis.io/climate-fieldview/eligibility/climate-fieldview-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Climate FieldView's own page on 2026-11-09.
synthetic: false
tags:
- Agriculture
- Bayer
- Crop Data
- Field Boundaries
- Harvest
- OAuth
- Planting
- Precision Agriculture
- AgTech
- Authentication
---
