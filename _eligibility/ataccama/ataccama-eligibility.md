---
api_specs:
- filename: ataccama-ataccama-api-api-openapi.yml
  format: yaml
  label: Ataccama Ataccama API
  slug: ataccama-ataccama-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-ataccama-api-api-openapi.yml
- filename: ataccama-catalog-api-openapi.yml
  format: yaml
  label: Ataccama Catalog API
  slug: ataccama-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-catalog-api-openapi.yml
- filename: ataccama-data-quality-api-openapi.yml
  format: yaml
  label: Ataccama Data Quality API
  slug: ataccama-data-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-data-quality-api-openapi.yml
- filename: ataccama-reference-data-api-openapi.yml
  format: yaml
  label: Ataccama Reference Data API
  slug: ataccama-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-reference-data-api-openapi.yml
- filename: ataccama-rest-api-openapi.yml
  format: yaml
  label: Ataccama Rest API
  slug: ataccama-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ataccama/openapi/ataccama-rest-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use of the forum
    text: Users may not use the forum for (commercial) activities such as the advertising or sale of products or services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will be required to set up an account in order to post on the community and in the user group.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ataccama
provenance_date: '2026-11-09'
provider_name: Ataccama
provider_slug: ataccama
slug: ataccama-eligibility
source_date: '2026-11-09'
source_filename: ataccama-eligibility.yml
source_heading: Eligibility
source_page: https://community.ataccama.com/site/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ataccama\naid: ataccama\nurl: https://community.ataccama.com/site/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No commercial use of the forum\n  text: Users may not use the forum for (commercial) activities such as the advertising or sale of products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will be required to set up an account in order to post on the community and in the user group.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ataccama/eligibility/ataccama-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Ataccama's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Quality
- Data Governance
- Artificial Intelligence
- Enterprise
- Platform
---
