---
api_specs:
- filename: bonsai-io-clusters-api-openapi.yml
  format: yaml
  label: Bonsai Clusters API
  slug: bonsai-io-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bonsai-io/openapi/bonsai-io-clusters-api-openapi.yml
- filename: bonsai-io-plans-api-openapi.yml
  format: yaml
  label: Bonsai Plans API
  slug: bonsai-io-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bonsai-io/openapi/bonsai-io-plans-api-openapi.yml
- filename: bonsai-io-releases-api-openapi.yml
  format: yaml
  label: Bonsai Releases API
  slug: bonsai-io-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bonsai-io/openapi/bonsai-io-releases-api-openapi.yml
- filename: bonsai-io-spaces-api-openapi.yml
  format: yaml
  label: Bonsai Spaces API
  slug: bonsai-io-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bonsai-io/openapi/bonsai-io-spaces-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer shall not permit any third party to access or use the Services in, or export such software to, a country subject to a United States embargo (including Cuba, Iran, North Korea, Sudan, and Syria).
  entity_types:
  - text: IF YOU ARE ACCEPTING THIS AGREEMENT AND USING THE SERVICES ON BEHALF OF A COMPANY, ORGANIZATION, GOVERNMENT, OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT TO THE COMPANY THAT YOU HAVE FULL POWER AND AUTHORITY TO DO SO.
    type: business
  minimum_age:
    text: You must be 13 years or older to use this Service.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: You may not use the Service for any illegal or unauthorized purpose.
  - summary: Competitive or abusive use
    text: access the Services in order to build a competitive product or service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bonsai
provenance_date: '2026-11-09'
provider_name: Bonsai
provider_slug: bonsai-io
slug: bonsai-io-eligibility
source_date: '2026-11-09'
source_filename: bonsai-io-eligibility.yml
source_heading: Eligibility
source_page: https://bonsai.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bonsai\naid: bonsai-io\nurl: https://bonsai.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer shall not permit any third party to access or use the Services in, or export such software to,\n    a country subject to a United States embargo (including Cuba, Iran, North Korea, Sudan, and Syria).\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING THIS AGREEMENT AND USING THE SERVICES ON BEHALF OF A COMPANY, ORGANIZATION, GOVERNMENT,\n    OR OTHER LEGAL ENTITY, YOU REPRESENT AND WARRANT TO THE COMPANY THAT YOU HAVE FULL\
  \ POWER AND AUTHORITY TO DO\n    SO.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: You may not use the Service for any illegal or unauthorized purpose.\n- summary: Competitive or abusive use\n  text: access the Services in order to build a competitive product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/bonsai-io/eligibility/bonsai-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bonsai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Search
- Elasticsearch
- OpenSearch
- Managed Service
- Vector Search
- Cloud Infrastructure
---
