---
api_specs:
- filename: pigment-blocksapi-api-openapi.yml
  format: yaml
  label: Pigment BlocksApi API
  slug: pigment-blocksapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-blocksapi-api-openapi.yml
- filename: pigment-export-api-openapi.yml
  format: yaml
  label: Pigment Export API
  slug: pigment-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-export-api-openapi.yml
- filename: pigment-exportv1-api-openapi.yml
  format: yaml
  label: Pigment ExportV1 API
  slug: pigment-exportv1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-exportv1-api-openapi.yml
- filename: pigment-importconfigurationapi-api-openapi.yml
  format: yaml
  label: Pigment ImportConfigurationApi API
  slug: pigment-importconfigurationapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-importconfigurationapi-api-openapi.yml
- filename: pigment-importv1-api-openapi.yml
  format: yaml
  label: Pigment ImportV1 API
  slug: pigment-importv1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-importv1-api-openapi.yml
- filename: pigment-viewapi-api-openapi.yml
  format: yaml
  label: Pigment ViewApi API
  slug: pigment-viewapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-viewapi-api-openapi.yml
- filename: pigment-application-api-api-openapi.yml
  format: yaml
  label: Pigment Application API
  slug: pigment-application-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-application-api-api-openapi.yml
- filename: pigment-import-api-api-openapi.yml
  format: yaml
  label: Pigment Import API
  slug: pigment-import-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pigment/openapi/pigment-import-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - MX
    - FR
    - DE
    - GB
    - CH
    - IL
    - SG
    - AU
    text: United States of America, Canada and Mexico. (Pigment Inc.); France, Germany, any other European Economic Area country, United Kingdom, Switzerland, Israel, Singapore, Australia and any other country not specified above. (Pigment SAS)
  entity_types:
  - text: Your use of the Solution will be solely for Your internal business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: You will not permit any individual or entity to access the Solution if they are subject to sanctions imposed by any government authority or institution in the Sanctions Compliance Territories.
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
name: Pigment
provenance_date: '2026-11-10'
provider_name: Pigment
provider_slug: pigment
slug: pigment-eligibility
source_date: '2026-11-10'
source_filename: pigment-eligibility.yml
source_heading: Eligibility
source_page: https://www.pigment.com/msa/online-master-services-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pigment\naid: pigment\nurl: https://www.pigment.com/msa/online-master-services-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - MX\n  - FR\n  - DE\n  - GB\n  - CH\n  - IL\n  - SG\n  - AU\n  excluded: []\n  text: United States of America, Canada and Mexico. (Pigment Inc.); France, Germany, any other European Economic\n    Area country, United Kingdom, Switzerland, Israel, Singapore, Australia and any other country not specified\n    above. (Pigment SAS)\nentity_types:\n- type: business\n  text: Your use of the Solution will be solely for Your internal business purposes.\nrestricted_uses:\n\
  - summary: Sanctioned persons\n  text: You will not permit any individual or entity to access the Solution if they are subject to sanctions imposed\n    by any government authority or institution in the Sanctions Compliance Territories.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pigment/eligibility/pigment-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pigment's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Software
- Business Planning
- Financial Planning
- FP&A
- Analytics
- EPM
- Data Integration
- MCP
- SCIM
- Data Platform
- Visualization
- Collaboration
---
