---
api_specs:
- filename: censys-account-management-api-openapi.yml
  format: yaml
  label: Censys Account Management API
  slug: censys-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-account-management-api-openapi.yml
- filename: censys-adversary-investigation-api-openapi.yml
  format: yaml
  label: Censys Adversary Investigation API
  slug: censys-adversary-investigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-adversary-investigation-api-openapi.yml
- filename: censys-asset-graphs-api-openapi.yml
  format: yaml
  label: Censys Asset Graphs API
  slug: censys-asset-graphs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-asset-graphs-api-openapi.yml
- filename: censys-assets-api-openapi.yml
  format: yaml
  label: Censys Assets API
  slug: censys-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-assets-api-openapi.yml
- filename: censys-collections-api-openapi.yml
  format: yaml
  label: Censys Collections API
  slug: censys-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-collections-api-openapi.yml
- filename: censys-excluded-assets-api-openapi.yml
  format: yaml
  label: Censys Excluded Assets API
  slug: censys-excluded-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-excluded-assets-api-openapi.yml
- filename: censys-global-data-api-openapi.yml
  format: yaml
  label: Censys Global Data API
  slug: censys-global-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-global-data-api-openapi.yml
- filename: censys-graph-executions-api-openapi.yml
  format: yaml
  label: Censys Graph Executions API
  slug: censys-graph-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-graph-executions-api-openapi.yml
- filename: censys-risks-api-openapi.yml
  format: yaml
  label: Censys Risks API
  slug: censys-risks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-risks-api-openapi.yml
- filename: censys-seeds-api-openapi.yml
  format: yaml
  label: Censys Seeds API
  slug: censys-seeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-seeds-api-openapi.yml
- filename: censys-shards-api-openapi.yml
  format: yaml
  label: Censys Shards API
  slug: censys-shards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-shards-api-openapi.yml
- filename: censys-supply-chain-intelligence-api-openapi.yml
  format: yaml
  label: Censys Supply Chain Intelligence API
  slug: censys-supply-chain-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-supply-chain-intelligence-api-openapi.yml
- filename: censys-tags-and-comments-api-openapi.yml
  format: yaml
  label: Censys Tags and Comments API
  slug: censys-tags-and-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-tags-and-comments-api-openapi.yml
- filename: censys-threat-hunting-api-openapi.yml
  format: yaml
  label: Censys Threat Hunting API
  slug: censys-threat-hunting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/censys/openapi/censys-threat-hunting-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE EXECUTING THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU HAVE AUTHORITY TO DO SO.
    type: business
  minimum_age:
    text: No individual under age 13 may use the Service under any circumstances or for any reason.
    value: '13'
  restricted_uses:
  - summary: No use for third parties' benefit
    text: the Service is offered only for Customer’s use, and not for the use or benefit of any third party.
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
name: Censys
provenance_date: '2026-11-09'
provider_name: Censys
provider_slug: censys
slug: censys-eligibility
source_date: '2026-11-09'
source_filename: censys-eligibility.yml
source_heading: Eligibility
source_page: https://censys.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Censys\naid: censys\nurl: https://censys.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE EXECUTING THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU HAVE\n    AUTHORITY TO DO SO.\nrestricted_uses:\n- summary: No use for third parties' benefit\n  text: the Service is offered only for Customer’s use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: No individual\
  \ under age 13 may use the Service under any circumstances or for any reason.\n"
source_yaml_url: https://artifacts.apis.io/censys/eligibility/censys-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Censys's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Internet Intelligence
- Attack Surface Management
- Threat Hunting
- Threat Intelligence
- OSINT
- Internet Scanning
- Certificates
- Asset Discovery
---
