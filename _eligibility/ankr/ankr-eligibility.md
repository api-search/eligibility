---
api_specs:
- filename: ankr-metrics-api-openapi.yml
  format: yaml
  label: ankr Metrics API
  slug: ankr-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ankr/openapi/ankr-metrics-api-openapi.yml
- filename: ankr-nft-api-openapi.yml
  format: yaml
  label: ankr NFT API
  slug: ankr-nft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ankr/openapi/ankr-nft-api-openapi.yml
- filename: ankr-query-api-openapi.yml
  format: yaml
  label: ankr Query API
  slug: ankr-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ankr/openapi/ankr-query-api-openapi.yml
- filename: ankr-ratio-api-openapi.yml
  format: yaml
  label: ankr Ratio API
  slug: ankr-ratio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ankr/openapi/ankr-ratio-api-openapi.yml
- filename: ankr-tasks-api-openapi.yml
  format: yaml
  label: ankr Tasks API
  slug: ankr-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ankr/openapi/ankr-tasks-api-openapi.yml
- filename: ankr-token-api-openapi.yml
  format: yaml
  label: ankr Token API
  slug: ankr-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ankr/openapi/ankr-token-api-openapi.yml
- filename: ankr-validators-api-openapi.yml
  format: yaml
  label: ankr Validators API
  slug: ankr-validators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ankr/openapi/ankr-validators-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims that the Website or any of its content is accessible or appropriate outside of the United States.
  entity_types:
  - text: solely for Customer’s own internal business purposes
    type: business
  minimum_age:
    text: Persons who are not the age of majority are not eligible to use the Website
    value: age of majority
  restricted_uses:
  - summary: Forge Program restricted jurisdictions and sanctioned persons
    text: not be located in, organized under the laws of, or a resident of any jurisdiction where participation in the Forge Program would be unlawful, and not be a person with whom dealings are restricted under applicable sanctions laws.
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
name: Ankr
provenance_date: '2026-11-09'
provider_name: Ankr
provider_slug: ankr
slug: ankr-eligibility
source_date: '2026-11-09'
source_filename: ankr-eligibility.yml
source_heading: Eligibility
source_page: https://www.ankr.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ankr\naid: ankr\nurl: https://www.ankr.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims that the Website or any of its content is accessible or appropriate outside of the United\n    States.\nentity_types:\n- type: business\n  text: solely for Customer’s own internal business purposes\nrestricted_uses:\n- summary: Forge Program restricted jurisdictions and sanctioned persons\n  text: not be located in, organized under the laws of, or a resident of any jurisdiction where participation in\n    the Forge Program would be unlawful, and not be a person with\
  \ whom dealings are restricted under applicable\n    sanctions laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: Persons who are not the age of majority are not eligible to use the Website\n"
source_yaml_url: https://artifacts.apis.io/ankr/eligibility/ankr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ankr's own page on 2026-11-09.
synthetic: false
tags:
- Web3
- EVM
- NFT
- Real-Time
- Ethereum
---
